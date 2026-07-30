---
title: get_OperatorEmulator()
second_title: Riferimento API di Aspose.Slides per C++
description: "Operator Emulator. Quando è true, la casella e il suo contenuto si comportano come un unico operatore e ereditano le proprietà di un operatore. Ciò significa, ad esempio, che il carattere può fungere da punto per un'interruzione di riga e può essere allineato ad altri operatori. Operator Emulators sono spesso usati quando uno o più glifi si combinano per formare un operatore, come '=='. Valore predefinito: false"
type: docs
weight: 14
url: /it/aspose.slides.mathtext/mathbox/get_operatoremulator/
---
## MathBox::get_OperatorEmulator() metodo


Operator Emulator. Quando è true, la casella e il suo contenuto si comportano come un unico operatore e ereditano le proprietà di un operatore. Ciò significa, ad esempio, che il carattere può fungere da punto per un'interruzione di riga e può essere allineato ad altri operatori. Operator Emulators sono spesso usati quando uno o più glifi si combinano per formare un operatore, come '=='. Valore predefinito: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_OperatorEmulator() override
```

## Osservazioni


Esempio: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## Vedi anche

* Classe [MathBox](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)