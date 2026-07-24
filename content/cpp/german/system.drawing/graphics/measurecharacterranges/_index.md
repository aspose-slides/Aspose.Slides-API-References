---
title: MeasureCharacterRanges()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein Array von Regionen zurück, von denen jede die Zeichenpositionen im angegebenen String begrenzt.
type: docs
weight: 508
url: /de/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges(const System::String\&, const SharedPtr\<Font\>\&, RectangleF, const SharedPtr\<StringFormat\>\&) method

Gibt ein Array von Regionen zurück, von denen jede die Zeichenpositionen im angegebenen String begrenzt.

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | Der zu messende String |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Die Schriftart, die bei der Messung des Strings verwendet wird |
| layoutRect | [RectangleF](../../rectanglef/) | Das Layoutrechteck, das bei der Messung des Strings verwendet wird |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\>\& | Das String-Format, das die zu messenden Zeichenbereiche enthält |

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Region](../../region/)
* Klasse [String](../../../system/string/)
* Klasse [Font](../../font/)
* Klasse [RectangleF](../../rectanglef/)
* Klasse [StringFormat](../../stringformat/)
* Klasse [Graphics](../)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)