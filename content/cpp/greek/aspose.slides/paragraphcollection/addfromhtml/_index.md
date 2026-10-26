---
title: AddFromHtml()
second_title: Aspose.Slides για την Αναφορά API C++
description: Προσθέτει κείμενο από την καθορισμένη συμβολοσειρά HTML στη συλλογή.
type: docs
weight: 157
url: /el/aspose.slides/paragraphcollection/addfromhtml/
---
## ParagraphCollection::AddFromHtml(System::String) μέθοδος

Προσθέτει κείμενο από την καθορισμένη συμβολοσειρά HTML στη συλλογή.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Κείμενο HTML. |

## ParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) μέθοδος

Προσθέτει κείμενο από την καθορισμένη συμβολοσειρά HTML στη συλλογή.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Κείμενο HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Αντικείμενο κλήσης resolver που επιλύει URIs και ανακτά τα αναφερόμενα αντικείμενα. |
| uri | [System::String](../../../system/string/) | URI για την προσθήκη του εγγράφου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

## Παρατηρήσεις

Η καθορισμένη resolver μπορεί ενδεχομένως να εισαγάγει μια ευπάθεια. Χρησιμοποιήστε το με προσοχή.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [ParagraphCollection](../)
* Κλάση [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)