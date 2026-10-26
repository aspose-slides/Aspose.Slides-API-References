---
title: set_OperatorEmulator()
second_title: Aspose.Slides for C++ API Referencia
description: "Operátor emulátor. Ha igaz, a doboz és tartalma egyetlen operátorként viselkedik, és örökli egy operátor tulajdonságait. Ez azt jelenti, például, hogy a karakter sorvégzőpontként szolgálhat, és más operátorokhoz igazítható. Az operátor emulátorokat gyakran használják, amikor egy vagy több glif kombinálódik egy operátor létrehozásához, például '=='. Alapértelmezett érték: false"
type: docs
weight: 27
url: /hu/aspose.slides.mathtext/mathbox/set_operatoremulator/
---
## MathBox::set_OperatorEmulator(bool) metódus

Operator Emulator. When true, the box and its contents behave as a single operator and inherit the properties of an operator. This means, for example, that the character can serve as a point for a line break and can be aligned to other operators. Operator Emulators are often used when one or more glyphs combine to form an operator, such as '=='. Alapértelmezett érték: false

```cpp
void Aspose::Slides::MathText::MathBox::set_OperatorEmulator(bool value) override
```

## Megjegyzések

Példa: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## Lásd még

* Osztály [MathBox](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)