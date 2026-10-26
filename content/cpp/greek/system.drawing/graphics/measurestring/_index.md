---
title: MeasureString()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει το μέγεθος της καθορισμένης συμβολοσειράς όταν σχεδιάζεται στην καθορισμένη γραμματοσειρά στη καθορισμένη μορφή.
type: docs
weight: 521
url: /el/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, PointF const\&, System::SharedPtr\<StringFormat\> const\&) const μέθοδος

Επιστρέφει το μέγεθος της καθορισμένης συμβολοσειράς όταν σχεδιάζεται στην καθορισμένη γραμματοσειρά στη καθορισμένη μορφή.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | Η συμβολοσειρά του οποίου το μέγεθος υπολογίζεται |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Η γραμματοσειρά που χρησιμοποιείται για τη σχεδίαση της συμβολοσειράς |
| origin | [PointF](../../pointf/) const\& | Καθορίζει τη θέση της επάνω αριστερής γωνίας της συμβολοσειράς |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Καθορίζει τη μορφή της συμβολοσειράς |

### Τιμή Επιστροφής

Ένα αντικείμενο [SizeF](../../sizef/) που αντιπροσωπεύει το μέγεθος της συμβολοσειράς στις μονάδες μέτρησης που ορίζονται από την ιδιότητα PageUnit του τρέχοντος αντικειμένου Grapphics.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, int, System::SharedPtr\<StringFormat\> const\&) const μέθοδος

Επιστρέφει το μέγεθος της καθορισμένης συμβολοσειράς όταν σχεδιάζεται στην καθορισμένη γραμματοσειρά στη καθορισμένη μορφή.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | Η συμβολοσειρά του οποίου το μέγεθος υπολογίζεται |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Η γραμματοσειρά που χρησιμοποιείται για τη σχεδίαση της συμβολοσειράς |
| width | int | Το μέγιστο πλάτος της συμβολοσειράς |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Καθορίζει τη μορφή της συμβολοσειράς |

### Τιμή Επιστροφής

Ένα αντικείμενο [SizeF](../../sizef/) που αντιπροσωπεύει το μέγεθος της συμβολοσειράς στις μονάδες μέτρησης που ορίζονται από την ιδιότητα PageUnit του τρέχοντος αντικειμένου Grapphics.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&, int\&, int\&) const μέθοδος

ΔΕΝ ΥΛΟΠΟΙΕΙΤΑΙ.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&) const μέθοδος

Επιστρέφει το μέγεθος της καθορισμένης συμβολοσειράς όταν σχεδιάζεται στην καθορισμένη γραμματοσειρά στη καθορισμένη μορφή.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | Η συμβολοσειρά του οποίου το μέγεθος υπολογίζεται |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Η γραμματοσειρά που χρησιμοποιείται για τη σχεδίαση της συμβολοσειράς |
| layoutArea | [SizeF](../../sizef/) const\& | Η μέγιστη περιοχή διάταξης της συμβολοσειράς |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Καθορίζει τη μορφή της συμβολοσειράς |

### Τιμή Επιστροφής

Ένα αντικείμενο [SizeF](../../sizef/) που αντιπροσωπεύει το μέγεθος της συμβολοσειράς στις μονάδες μέτρησης που ορίζονται από την ιδιότητα PageUnit του τρέχοντος αντικειμένου Grapphics.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [SizeF](../../sizef/)
* Κλάση [String](../../../system/string/)
* Κλάση [Font](../../font/)
* Κλάση [PointF](../../pointf/)
* Κλάση [StringFormat](../../stringformat/)
* Κλάση [Graphics](../)
* Χώρος ονομάτων [System::Drawing](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)