---
title: set_OperatorEmulator()
second_title: Riferimento API di Aspose.Slides per C++
description: "Emulatore di Operatore. Quando true, la casella e il suo contenuto si comportano come un unico operatore e ereditano le proprietà di un operatore. Questo significa, ad esempio, che il carattere può fungere da punto per un'interruzione di linea e può essere allineato ad altri operatori. Gli Emulatori di Operatore sono spesso usati quando uno o più glifi si combinano per formare un operatore, come '=='. Valore predefinito: false"
type: docs
weight: 27
url: /it/aspose.slides.mathtext/mathbox/set_operatoremulator/
---
## MathBox::set_OperatorEmulator(bool) metodo

Emulatore operatore. Quando è vero, la scatola e il suo contenuto si comportano come un unico operatore e ereditano le proprietà di un operatore. Ciò significa, ad esempio, che il carattere può fungere da punto per un’interruzione di linea e può essere allineato ad altri operatori. Gli emulatori operatore sono spesso usati quando uno o più glifi si combinano per formare un operatore, come '=='. Valore predefinito: false

```cpp
void Aspose::Slides::MathText::MathBox::set_OperatorEmulator(bool value) override
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