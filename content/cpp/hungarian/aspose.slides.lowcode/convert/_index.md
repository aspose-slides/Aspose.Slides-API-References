---
title: Convert
second_title: Aspose.Slides C++ API hivatkozás
description: Egy módszercsoportot képvisel, amelynek célja a Presentation átalakítása.
type: docs
weight: 27
url: /hu/aspose.slides.lowcode/convert/
---
## Átalakító osztály


Olyan módszercsoportot képvisel, amelynek célja a [Presentation](../../aspose.slides/presentation/) átalakítása.

```cpp
class Convert
```

## Metódusok

| Method | Leírás |
| --- | --- |
| static void [AutoByExtension](./autobyextension/)([System::String](../../system/string/), [System::String](../../system/string/)) | Átalakítja a [Presentation](../../aspose.slides/presentation/)-t a megadott kimeneti útvonal kiterjesztésének felhasználásával a szükséges export formátum meghatározásához. |
|  [Convert](./convert/)() |  |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Átalakítja a bemeneti prezentációt egy JPEG formátumú képek sorozatává. 

 Ha a kimeneti fájlnevet a "myPath/myFilename.jpeg" formában adják meg, az eredmény egy "myPath/myFilename_N.jpeg" fájlok sorozataként lesz mentve, ahol N a dia száma. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | Átalakítja a bemeneti prezentációt egy JPEG formátumú képek sorozatává. 

 Ha a kimeneti fájlnevet a "myPath/myFilename.jpeg" formában adják meg, az eredmény egy "myPath/myFilename_N.jpeg" fájlok sorozataként lesz mentve, ahol N a dia száma. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | Átalakítja a bemeneti prezentációt egy JPEG formátumú képek sorozatává. 

 Ha a kimeneti fájlnevet a "myPath/myFilename.jpeg" formában adják meg, az eredmény egy "myPath/myFilename_N.jpeg" fájlok sorozataként lesz mentve, ahol N a dia száma. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/)) | Átalakítja a [Presentation](../../aspose.slides/presentation/)-t PDF-é. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Átalakítja a [Presentation](../../aspose.slides/presentation/)-t PDF-é. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Átalakítja a [Presentation](../../aspose.slides/presentation/)-t PDF-é. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Átalakítja a [Presentation](../../aspose.slides/presentation/)-t PDF-é. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Átalakítja a bemeneti prezentációt egy PNG formátumú képek sorozatává. 

 Ha a kimeneti fájlnevet a "myPath/myFilename.png" formában adják meg, az eredmény egy "myPath/myFilename_N.png" fájlok sorozataként lesz mentve, ahol N a dia száma. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | Átalakítja a bemeneti prezentációt egy PNG formátumú képek sorozatává. 

 Ha a kimeneti fájlnevet a "myPath/myFilename.png" formában adják meg, az eredmény egy "myPath/myFilename_N.png" fájlok sorozataként lesz mentve, ahol N a dia száma. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | Átalakítja a bemeneti prezentációt egy PNG formátumú képek sorozatává. 

 Ha a kimeneti fájlnevet a "myPath/myFilename.png" formában adják meg, az eredmény egy "myPath/myFilename_N.png" fájlok sorozataként lesz mentve, ahol N a dia száma. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/)) | Átalakítja a [Presentation](../../aspose.slides/presentation/)-t SVG-é. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/), [Convert::GetOutPathCallback](./getoutpathcallback/)) | Átalakítja a [Presentation](../../aspose.slides/presentation/)-t SVG-é. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/)) | Átalakítja a [Presentation](../../aspose.slides/presentation/)-t SVG-é. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Átalakítja a [Presentation](../../aspose.slides/presentation/)-t SVG-é. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Átalakítja a [Presentation](../../aspose.slides/presentation/)-t SVG-é. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Átalakítja a bemeneti prezentációt egy TIFF formátumú képek sorozatává. 

 Ha a kimeneti fájlnevet a "myPath/myFilename.tiff" formában adják meg, az eredmény egy "myPath/myFilename_N.tiff" fájlok sorozataként lesz mentve, ahol N a dia száma. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>, **bool**) | Egyedi beállításokkal alakítja át a bemeneti prezentációt TIFF formátumúvá. Ha a kimeneti fájlnevet a "myPath/myFilename.tiff" formában adják meg, és a *multipage* **false**, az eredmény egy "myPath/myFilename_N.tiff" fájlok sorozataként lesz mentve, ahol N a dia száma. Ha a *multipage* **true**, az eredmény egy többoldalas "myPath/myFilename.tiff" dokumentum lesz. |

## Típusdefiníciók

| Typedef | Leírás |
| --- | --- |
| [GetOutPathCallback](./getoutpathcallback/) | Visszahívás, amely minden egyes [Slide](../../aspose.slides/slide/) esetén meghívásra kerül, a kimeneti útvonal visszaadásával. |

## Megjegyzések



```cpp
Convert::AutoByExtension(u"pres.pptx", u"pres.pdf");
```

## Lásd még

* Névtér [Aspose::Slides::LowCode](../)
* Könyvtár [Aspose.Slides](../../)