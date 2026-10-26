---
title: DrawString()
second_title: Aspose.Slides για C++ - Αναφορά API
description: Σχεδιάζει τη συγκεκριμένη συμβολοσειρά στην καθορισμένη θέση χρησιμοποιώντας τη συγκεκριμένη γραμματοσειρά και το πινέλο.
type: docs
weight: 365
url: /el/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) μέθοδος

Σχεδιάζει τη συγκεκριμένη συμβολοσειρά στην καθορισμένη τοποθεσία χρησιμοποιώντας τη συγκεκριμένη γραμματοσειρά και το πινέλο.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Η συμβολοσειρά προς σχεδίαση |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Μια γραμματοσειρά προς χρήση |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Ένα [Brush](../../brush/) αντικείμενο προς χρήση για σχεδίαση |
| topLeft | [PointF](../../pointf/) | Καθορίζει τη θέση της επάνω αριστερής γωνίας της σχεδιασμένης συμβολοσειράς |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Καθορίζει τη μορφή της συμβολοσειράς |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) μέθοδος

Σχεδιάζει τη συγκεκριμένη συμβολοσειρά μέσα στο καθορισμένο ορθογώνιο χρησιμοποιώντας τη συγκεκριμένη γραμματοσειρά και το πινέλο.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Η συμβολοσειρά προς σχεδίαση |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Μια γραμματοσειρά προς χρήση |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Ένα [Brush](../../brush/) αντικείμενο προς χρήση για σχεδίαση |
| layoutRectangle | [RectangleF](../../rectanglef/) | Καθορίζει ένα ορθογώνιο στο οποίο θα σχεδιαστεί η συμβολοσειρά |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Καθορίζει τη μορφή της συμβολοσειράς |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) μέθοδος

Σχεδιάζει τη συγκεκριμένη συμβολοσειρά στην καθορισμένη τοποθεσία χρησιμοποιώντας τη συγκεκριμένη γραμματοσειρά και το πινέλο.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Η συμβολοσειρά προς σχεδίαση |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Μια γραμματοσειρά προς χρήση |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Ένα [Brush](../../brush/) αντικείμενο προς χρήση για σχεδίαση |
| x | **float** | Η συντεταγμένη X της θέσης της επάνω αριστερής γωνίας της σχεδιασμένης συμβολοσειράς |
| y | **float** | Η συντεταγμένη Y της θέσης της επάνω αριστερής γωνίας της σχεδιασμένης συμβολοσειράς |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Καθορίζει τη μορφή της συμβολοσειράς |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [Font](../../font/)
* Κλάση [Brush](../../brush/)
* Κλάση [PointF](../../pointf/)
* Κλάση [StringFormat](../../stringformat/)
* Κλάση [Graphics](../)
* Κλάση [RectangleF](../../rectanglef/)
* Χώρος ονομάτων [System::Drawing](../../)
* Library [Aspose.Slides](../../../)