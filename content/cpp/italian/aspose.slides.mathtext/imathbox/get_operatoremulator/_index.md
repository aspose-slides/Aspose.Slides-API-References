---
title: get_OperatorEmulator()
second_title: Riferimento API di Aspose.Slides per C++
description: "Operator Emulator. Quando è vero, la casella e i suoi contenuti si comportano come un singolo operatore e ereditano le proprietà di un operatore. Ciò significa, per esempio, che il carattere può fungere da punto per un'interruzione di riga e può essere allineato ad altri operatori. Operator Emulator sono spesso usati quando uno o più glifi si combinano per formare un operatore, come '=='. Valore predefinito: false"
type: docs
weight: 14
url: /it/aspose.slides.mathtext/imathbox/get_operatoremulator/
---
## IMathBox::get_OperatorEmulator() metodo

Operator Emulator. Quando è vero, la casella e i suoi contenuti si comportano come un singolo operatore e ereditano le proprietà di un operatore. Ciò significa, ad esempio, che il carattere può fungere da punto per un'interruzione di riga e può essere allineato ad altri operatori. Operator Emulators sono spesso usati quando uno o più glifi si combinano per formare un operatore, come '=='. Valore predefinito: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_OperatorEmulator()=0
```

## Osservazioni

Esempio: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## Vedi anche

* Classe [IMathBox](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)