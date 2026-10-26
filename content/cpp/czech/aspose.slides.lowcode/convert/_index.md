---
title: Convert
second_title: Aspose.Slides pro C++ referenční příručka API
description: Představuje skupinu metod určených k převodu prezentace.
type: docs
weight: 27
url: /cs/aspose.slides.lowcode/convert/
---
## Convert třída


Represents a group of methods intended to convert [Presentation](../../aspose.slides/presentation/).

```cpp
class Convert
```

## Metody

| Method | Description |
| --- | --- |
| static void [AutoByExtension](./autobyextension/)([System::String](../../system/string/), [System::String](../../system/string/)) | Převádí [Presentation](../../aspose.slides/presentation/) pomocí předané přípony výstupní cesty k určení požadovaného formátu exportu. |
|  [Convert](./convert/)() |  |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Převádí vstupní prezentaci na sadu obrázků ve formátu JPEG. 

 Pokud je zadáno jméno výstupního souboru jako "myPath/myFilename.jpeg", výsledek bude uložen jako sada souborů "myPath/myFilename_N.jpeg", kde N je číslo snímku. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | Převádí vstupní prezentaci na sadu obrázků ve formátu JPEG. 

 Pokud je zadáno jméno výstupního souboru jako "myPath/myFilename.jpeg", výsledek bude uložen jako sada souborů "myPath/myFilename_N.jpeg", kde N je číslo snímku. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | Převádí vstupní prezentaci na sadu obrázků ve formátu JPEG. 

 Pokud je zadáno jméno výstupního souboru jako "myPath/myFilename.jpeg", výsledek bude uložen jako sada souborů "myPath/myFilename_N.jpeg", kde N je číslo snímku. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/)) | Převádí [Presentation](../../aspose.slides/presentation/) do PDF. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Převádí [Presentation](../../aspose.slides/presentation/) do PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Převádí [Presentation](../../aspose.slides/presentation/) do PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Převádí [Presentation](../../aspose.slides/presentation/) do PDF. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Převádí vstupní prezentaci na sadu obrázků ve formátu PNG. 

 Pokud je zadáno jméno výstupního souboru jako "myPath/myFilename.png", výsledek bude uložen jako sada souborů "myPath/myFilename_N.png", kde N je číslo snímku. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | Převádí vstupní prezentaci na sadu obrázků ve formátu PNG. 

 Pokud je zadáno jméno výstupního souboru jako "myPath/myFilename.png", výsledek bude uložen jako sada souborů "myPath/myFilename_N.png", kde N je číslo snímku. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | Převádí vstupní prezentaci na sadu obrázků ve formátu PNG. 

 Pokud je zadáno jméno výstupního souboru jako "myPath/myFilename.png", výsledek bude uložen jako sada souborů "myPath/myFilename_N.png", kde N je číslo snímku. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/)) | Převádí [Presentation](../../aspose.slides/presentation/) do SVG. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/), [Convert::GetOutPathCallback](./getoutpathcallback/)) | Převádí [Presentation](../../aspose.slides/presentation/) do SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/)) | Převádí [Presentation](../../aspose.slides/presentation/) do SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Převádí [Presentation](../../aspose.slides/presentation/) do SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Převádí [Presentation](../../aspose.slides/presentation/) do SVG. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Převádí vstupní prezentaci na sadu obrázků ve formátu TIFF. 

 Pokud je zadáno jméno výstupního souboru jako "myPath/myFilename.tiff", výsledek bude uložen jako sada souborů "myPath/myFilename_N.tiff", kde N je číslo snímku. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>, **bool**) | Převádí vstupní prezentaci do formátu TIFF s vlastními možnostmi. Pokud je zadáno jméno výstupního souboru jako "myPath/myFilename.tiff" a *multipage* je **false**, výsledek bude uložen jako sada souborů "myPath/myFilename_N.tiff", kde N je číslo snímku. Jinak, pokud je *multipage* **true**, výsledek bude vícestránkový dokument "myPath/myFilename.tiff". |
## Typedefy

| Typedef | Description |
| --- | --- |
| [GetOutPathCallback](./getoutpathcallback/) | Callback, který bude volán pro každý [Slide](../../aspose.slides/slide/), očekávaná výstupní cesta má být vrácena. |
## Poznámky



```cpp
Convert::AutoByExtension(u"pres.pptx", u"pres.pdf");
```

## Viz také

* Jmenný prostor [Aspose::Slides::LowCode](../)
* Knihovna [Aspose.Slides](../../)