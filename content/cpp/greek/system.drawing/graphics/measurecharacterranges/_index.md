---
title: MeasureCharacterRanges()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει έναν πίνακα περιοχών, ο καθένας από τις οποίες περιορίζει τις θέσεις χαρακτήρων στη συγκεκριμένη συμβολοσειρά.
type: docs
weight: 508
url: /el/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges(const System::String\&, const SharedPtr\<Font\>\&, RectangleF, const SharedPtr\<StringFormat\>\&) μέθοδος

Επιστρέφει έναν πίνακα περιοχών, ο καθένας από τις οποίες περιορίζει τις θέσεις χαρακτήρων στη δοσμένη συμβολοσειρά.

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | Η συμβολοσειρά για μέτρηση |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Η γραμματοσειρά που χρησιμοποιείται κατά τη μέτρηση της συμβολοσειράς |
| layoutRect | [RectangleF](../../rectanglef/) | Το ορθογώνιο διάταξης που χρησιμοποιείται κατά τη μέτρηση της συμβολοσειράς |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\>\& | Η μορφή συμβολοσειράς, περιέχει τις περιοχές χαρακτήρων που θα μετρηθούν |

## Δείτε επίσης

* Τύπος [ArrayPtr](../../../system/arrayptr/)
* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [Region](../../region/)
* Κλάση [String](../../../system/string/)
* Κλάση [Font](../../font/)
* Κλάση [RectangleF](../../rectanglef/)
* Κλάση [StringFormat](../../stringformat/)
* Κλάση [Graphics](../)
* Χώρος ονομάτων [System::Drawing](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)