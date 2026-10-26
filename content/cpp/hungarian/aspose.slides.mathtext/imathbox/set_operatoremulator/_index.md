---
title: set_OperatorEmulator()
second_title: Aspose.Slides C++ API Referenciája
description: "Operátor emulátor. Ha igaz, a doboz és tartalma egyetlen operátorként viselkedik, és örökli egy operátor tulajdonságait. Ez azt jelenti például, hogy a karakter szolgálhat sortörési pontként, és összeilleszthető más operátorokkal. Az operátor emulátorokat gyakran használják, amikor egy vagy több glif kombinálódik egy operátor létrehozásához, például a '==' esetében. Alapértelmezett érték: false"
type: docs
weight: 27
url: /hu/aspose.slides.mathtext/imathbox/set_operatoremulator/
---
## IMathBox::set_OperatorEmulator(bool) metódus

Operátor emulátor. Ha igaz, a doboz és a tartalma egyetlen operátorként viselkedik, és örökli egy operátor tulajdonságait. Ez azt jelenti, például, hogy a karakter szolgálhat sortörés pontként, és egyesíthető más operátorokkal. Az operátor emulátorokat gyakran használják, amikor egy vagy több glif kombinálódik egy operátor létrehozásához, például a '==' esetében. Alapértelmezett érték: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_OperatorEmulator(bool value)=0
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