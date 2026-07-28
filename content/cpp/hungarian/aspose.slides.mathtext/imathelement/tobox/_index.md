---
title: ToBox()
second_title: Aspose.Slides for C++ API referenciához
description: Az elem elhelyezése egy nem látható dobozba (logikai csoportba), amelyet egyenlet vagy más matematikai szöveg összetevőinek csoportosítására használnak. Egy dobozba helyezett objektum (például) szolgálhat operátor emulátorként elhelyezési ponttal vagy anélkül, szolgálhat sortörés pontként, vagy úgy csoportosítható, hogy a dobozon belül ne legyenek sortörések.
type: docs
weight: 274
url: /hu/aspose.slides.mathtext/imathelement/tobox/
---
## IMathElement::ToBox() metódus

Az elem elhelyezése egy nem látható dobozba (logikai csoportba), amelyet egyenlet vagy más matematikai szöveg példányának összetevőinek csoportosítására használnak. Egy dobozba helyezett objektum (például) szolgálhat operátor emulátorként elhelyezési ponttal vagy anélkül, szolgálhat sortörés pontként, vagy úgy csoportosítható, hogy a dobozon belül ne legyenek sortörések.

```cpp
virtual System::SharedPtr<IMathBox> Aspose::Slides::MathText::IMathElement::ToBox()=0
```

### Visszatérési érték

Logikai doboz, amelyben ez az elem el van helyezve

## Megjegyzések

Példa:
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathBox](../../imathbox/)
* Osztály [IMathElement](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)