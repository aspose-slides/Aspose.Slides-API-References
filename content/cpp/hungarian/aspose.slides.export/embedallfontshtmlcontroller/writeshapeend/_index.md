---
title: WriteShapeEnd()
second_title: Aspose.Slides C++ API Referencia
description: Shape megjelenítése előtt hívják. Minden shape esetén egyszer hívják. Ha ez a függvény bármit ír a generatorba, a jelenlegi dia kép generálása befejeződik, a hozzáadott HTML töredék beillesztésre kerül, és egy új kép indul a korábbi tetejéről.
type: docs
weight: 79
url: /hu/aspose.slides.export/embedallfontshtmlcontroller/writeshapeend/
---
## EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) metódus

A shape megjelenítése előtt hívják. Minden shape esetén egyszer hívják. Ha ez a függvény bármit ír a generator-ba, a jelenlegi dia kép generálása befejeződik, a hozzáadott html töredék beillesztésre kerül, és egy új kép indul a korábbi tetejéről.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Kimeneti objektum. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) ami utoljára kerül megjelenítésre. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IHtmlGenerator](../../ihtmlgenerator/)
* Osztály [IShape](../../../aspose.slides/ishape/)
* Osztály [EmbedAllFontsHtmlController](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)