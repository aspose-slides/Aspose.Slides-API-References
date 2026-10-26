---
title: ExportToHtml()
second_title: Aspose.Slides C++ API Referencia
description: Átalakítja a megadott bekezdéseket HTML-re, és visszaadja String objektumként.
type: docs
weight: 105
url: /hu/aspose.slides/iparagraphcollection/exporttohtml/
---
## IParagraphCollection::ExportToHtml(int32_t, int32_t, System::SharedPtr\<Export::ITextToHtmlConversionOptions\>) metódus


Átalakítja a megadott bekezdéseket HTML-re, és visszaadja String objektumként.

```cpp
virtual System::String Aspose::Slides::IParagraphCollection::ExportToHtml(int32_t firstParagraphIndex, int32_t paragraphsCount, System::SharedPtr<Export::ITextToHtmlConversionOptions> options)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| firstParagraphIndex | **int32_t** | Az első bekezdés indexe **int32_t** |
| paragraphsCount | **int32_t** | [Paragraph](../../paragraph/) darab **int32_t** |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)\> | Átalakítási beállítások [Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/) |

### Visszatérési érték

Generált HTML.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)
* Osztály [IParagraphCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)