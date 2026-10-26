---
title: get_OperatorEmulator()
second_title: Aspose.Slides C++-os API hivatkozás
description: "Operator Emulator. Ha true, a doboz és tartalma egyetlen operátorként viselkedik, és örökli egy operátor tulajdonságait. Ez azt jelenti, hogy például a karakter szolgálhat sorvége jelzésként, és igazítható más operátorokhoz. Az Operator Emulator-okat gyakran használják, amikor egy vagy több glif kombinálódik egy operátor létrehozásához, például '=='. Alapértelmezett érték: false"
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/mathbox/get_operatoremulator/
---
## MathBox::get_OperatorEmulator() metódus


Operator Emulator. Ha true, a doboz és tartalma egyetlen operátorként viselkedik, és örökli egy operátor tulajdonságait. Ez azt jelenti, hogy például a karakter szolgálhat sorvége jelzésként, és igazítható más operátorokhoz. Operator Emulators gyakran használatosak, amikor egy vagy több glif egy operátort alkot, például '=='. Alapértelmezett érték: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_OperatorEmulator() override
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