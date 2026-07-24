---
title: ExportToHtml()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert die angegebenen Absätze in HTML und gibt sie als String-Objekt zurück.
type: docs
weight: 170
url: /de/aspose.slides/paragraphcollection/exporttohtml/
---
## ParagraphCollection::ExportToHtml(int32_t, int32_t, System::SharedPtr\<Export::ITextToHtmlConversionOptions\>) Methode

Konvertiert die angegebenen Absätze in HTML und gibt es als String-Objekt zurück.

```cpp
System::String Aspose::Slides::ParagraphCollection::ExportToHtml(int32_t firstParagraphIndex, int32_t paragraphsCount, System::SharedPtr<Export::ITextToHtmlConversionOptions> options) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstParagraphIndex | **int32_t** | Erster Absatzindex **int32_t** |
| paragraphsCount | **int32_t** | [Paragraph](../../paragraph/) Anzahl **int32_t** |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)\> | Konvertierungsoptionen [Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/) |

### Rückgabewert

Generiertes HTML.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [String](../../../system/string/)
* Klasse [ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)
* Klasse [ParagraphCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)