---
title: WriteShapeEnd()
second_title: Aspose.Slides C++ API-referencia
description: A forma megjelenítése előtt hívódik. Formánként egyszer kerül meghívásra. Ha ez a függvény bármit ír a generátorba, a jelenlegi diakép generálása befejeződik, a hozzáadott HTML töredék beillesztésre kerül, és egy új kép indul a korábbi tetején.
type: docs
weight: 66
url: /hu/aspose.slides.export/ihtmlformattingcontroller/writeshapeend/
---
## IHtmlFormattingController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) metódus

A forma megjelenítése előtt hívódik. Formánként egyszer kerül meghívásra. Ha ez a függvény bármit ír a generátorba, a jelenlegi diakép generálása befejeződik, a hozzáadott HTML töredék beillesztésre kerül, és egy új kép indul a korábbi tetején.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Kimeneti objektum. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) amelyik utoljára van renderelve. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IHtmlGenerator](../../ihtmlgenerator/)
* Osztály [IShape](../../../aspose.slides/ishape/)
* Osztály [IHtmlFormattingController](../)
* Névtér [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)