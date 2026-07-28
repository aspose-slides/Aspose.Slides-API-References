---
title: WriteShapeStart()
second_title: Aspose.Slides for C++ API Referencia
description: A forma renderelése előtt hívják. Minden forma esetén egyszer hívják. Ha ez a függvény bármit ír a generátorba, az aktuális dia kép generálása befejeződik, a hozzáadott HTML töredék beillesztésre kerül, és egy új kép kezdődik az előző tetején.
type: docs
weight: 66
url: /hu/aspose.slides.export/embedallfontshtmlcontroller/writeshapestart/
---
## EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) metódus

A forma renderelése előtt hívják. Minden forma esetén egyszer hívják. Ha ez a függvény bármit is ír a generátorba, az aktuális dia kép generálása befejeződik, hozzáadott HTML töredék kerül beillesztésre, és egy új kép indul az előző tetején.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Kimeneti objektum. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) amely renderelésre készül. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* osztály [IHtmlGenerator](../../ihtmlgenerator/)
* osztály [IShape](../../../aspose.slides/ishape/)
* osztály [EmbedAllFontsHtmlController](../)
* névtér [Aspose::Slides::Export](../../)
* könyvtár [Aspose.Slides](../../../)