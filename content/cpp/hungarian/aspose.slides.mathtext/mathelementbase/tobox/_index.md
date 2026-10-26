---
title: ToBox()
second_title: Aspose.Slides C++ API referencia
description: Az elemet egy nem vizuális dobozba (logikai csoportosítás) helyezi, amelyet egy egyenlet vagy más matematikai szöveg példányának komponenseinek csoportosítására használnak. Egy dobozba helyezett objektum (például) működhet operátor emulátorként igazítási ponttal vagy anélkül, szolgálhat sortörés pontként, vagy úgy csoportosítható, hogy ne engedje meg a sorok törését a belsejében.
type: docs
weight: 261
url: /hu/aspose.slides.mathtext/mathelementbase/tobox/
---
## MathElementBase::ToBox() metódus


Az elem ezt a nem vizuális dobozba (logikai csoportosítás) helyezi, amelyet egy egyenlet vagy más matematikai szöveg példányának komponenseinek csoportosítására használnak. Egy dobozba helyezett objektum (például) működhet operátor emulátorként egy igazítási ponttal vagy anélkül, szolgálhat sortörés pontként, vagy úgy csoportosítható, hogy ne engedje meg a sorok törését belül.

```cpp
System::SharedPtr<IMathBox> Aspose::Slides::MathText::MathElementBase::ToBox() override
```


### Visszatérési érték

Logikai doboz, amelyben ez az elem elhelyezve van
## Megjegyzések



Példa: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathBox](../../imathbox/)
* Osztály [MathElementBase](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)