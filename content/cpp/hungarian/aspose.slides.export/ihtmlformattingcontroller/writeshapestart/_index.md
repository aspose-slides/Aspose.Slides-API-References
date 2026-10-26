---
title: WriteShapeStart()
second_title: Aspose.Slides for C++ API referenciája
description: A shape renderelése előtt hívódik. Minden shape esetén egyszer hívódik. Ha ez a függvény bármit ír a generatorba, a jelenlegi diakép generálása befejeződik, a hozzáadott HTML töredék beillesztésre kerül, és egy új kép indul a korábbi tetején.
type: docs
weight: 53
url: /hu/aspose.slides.export/ihtmlformattingcontroller/writeshapestart/
---
## IHtmlFormattingController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) metódus

A shape renderelése előtt hívódik. Minden shape esetén egyszer hívódik. Ha ez a függvény bármit ír a generatorba, a jelenlegi diakép generálása befejeződik, a hozzáadott HTML töredék beillesztésre kerül, és egy új kép indul a korábbi tetején.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Kimeneti objektum. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) amely a megjelenítéshez készül. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IHtmlGenerator](../../ihtmlgenerator/)
* Osztály [IShape](../../../aspose.slides/ishape/)
* Osztály [IHtmlFormattingController](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)