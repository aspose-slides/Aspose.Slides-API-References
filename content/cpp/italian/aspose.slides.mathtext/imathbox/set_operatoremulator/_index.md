---
title: set_OperatorEmulator()
second_title: Riferimento API di Aspose.Slides per C++
description: "Emulatore di operatore. Quando true, la casella e il suo contenuto si comportano come un singolo operatore e ereditano le proprietà di un operatore. Ciò significa, per esempio, che il carattere può servire come punto per un'interruzione di riga e può essere allineato ad altri operatori. Gli emulatori di operatore sono spesso usati quando uno o più glifi si combinano per formare un operatore, come '=='. Valore predefinito: false"
type: docs
weight: 27
url: /it/aspose.slides.mathtext/imathbox/set_operatoremulator/
---
## IMathBox::set_OperatorEmulator(bool) metodo

Emulatore di operatore. Quando true, la casella e i suoi contenuti si comportano come un unico operatore e ereditano le proprietà di un operatore. Questo significa, per esempio, che il carattere può fungere da punto per un'interruzione di riga e può essere allineato ad altri operatori. Gli emulatori di operatore sono spesso usati quando uno o più glifi si combinano per formare un operatore, come '=='. Valore predefinito: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_OperatorEmulator(bool value)=0
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