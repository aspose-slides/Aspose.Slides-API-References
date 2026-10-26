---
title: get_OperatorEmulator()
second_title: Aspose.Slides for C++ API-referencia
description: "Operátor emulátor. Ha igaz, a doboz és tartalma egyetlen operátorként viselkedik, és örökli egy operátor tulajdonságait. Ez azt jelenti például, hogy a karakter szolgálhat sortörés pontként, és igazítható más operátorokhoz. Az operátor emulátorokat gyakran használják, ha egy vagy több glif kombinálódik egy operátor létrehozásához, például a '=='. Alapértelmezett érték: false"
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/imathbox/get_operatoremulator/
---
## IMathBox::get_OperatorEmulator() metódus

Operator Emulator. Amikor igaz, a doboz és tartalma egyetlen operátorként viselkedik, és örökli egy operátor tulajdonságait. Ez azt jelenti például, hogy a karakter szolgálhat sortörés pontként, és igazítható más operátorokhoz. Operator Emulators gyakran használatosak, ha egy vagy több glif kombinálódik operátorrá, például a '=='. Alapértelmezett érték: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_OperatorEmulator()=0
```

## Megjegyzések


Példa: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## Lásd még

* Osztály [IMathBox](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)