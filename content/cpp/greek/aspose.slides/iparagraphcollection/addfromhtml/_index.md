---
title: AddFromHtml()
second_title: Aspose.Slides για C++ Αναφορά API
description: Προσθέτει κείμενο από τη συγκεκριμένη συμβολοσειρά HTML στη συλλογή.
type: docs
weight: 92
url: /el/aspose.slides/iparagraphcollection/addfromhtml/
---
## IParagraphCollection::AddFromHtml(System::String) method

Προσθέτει κείμενο από το συγκεκριμένο συμβολοσειρά HTML στη συλλογή.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML κείμενο. |

## IParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Προσθέτει κείμενο από το συγκεκριμένο συμβολοσειρά HTML στη συλλογή.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML κείμενο. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Αντικείμενο κλήσης ανάκτησης που επιλύει URI και φέρνει τα αναφερόμενα αντικείμενα. |
| uri | [System::String](../../../system/string/) | URI για την προσθήκη του εγγράφου HTML. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

## Παρατηρήσεις

Η καθορισμένη ανάκτηση μπορεί ενδεχομένως να εισαγάγει ευπάθεια. Χρησιμοποιήστε με προσοχή.

## Δείτε επίσης

* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [IParagraphCollection](../)
* Κλάση [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)