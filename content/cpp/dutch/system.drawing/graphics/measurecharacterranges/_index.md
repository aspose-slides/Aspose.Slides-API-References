---
title: MeasureCharacterRanges()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een array van regio's die elk de tekenposities in de opgegeven string begrenzen.
type: docs
weight: 508
url: /nl/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges(const System::String\&, const SharedPtr\<Font\>\&, RectangleF, const SharedPtr\<StringFormat\>\&) methode

Retourneert een array van regio's die elk de tekenposities in de opgegeven string begrenzen.

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | De string om te meten |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Het font dat wordt gebruikt tijdens het meten van de string |
| layoutRect | [RectangleF](../../rectanglef/) | De layoutrechthoek die wordt gebruikt tijdens het meten van de string |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\>\& | Het stringformaat, bevat de tekenbereiken om te meten |

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Region](../../region/)
* Klasse [String](../../../system/string/)
* Klasse [Font](../../font/)
* Klasse [RectangleF](../../rectanglef/)
* Klasse [StringFormat](../../stringformat/)
* Klasse [Graphics](../)
* Naamruimte [System::Drawing](../../)
* Bibliotheek [Aspose.Slides](../../../)