---
title: Hyperlink()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί μια παρουσία υπερσυνδέσμου.
type: docs
weight: 339
url: /el/aspose.slides/hyperlink/hyperlink/
---
## Hyperlink::Hyperlink(System::String) constructor

Δημιουργεί μια παρουσία υπερσυνδέσμου.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::String url)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../) URL. |

## Hyperlink::Hyperlink(System::SharedPtr\<ISlide\>) constructor

Δημιουργεί μια παρουσία υπερσυνδέσμου που οδηγεί σε μια συγκεκριμένη διαφάνεια. Σημείωση: ο δημιουργημένος υπερσύνδεσμος πρέπει να ανατεθεί σε κάποιο αντικείμενο από την ίδια παρουσίαση, διαφορετικά ο σύνδεσμος θα αποθηκευθεί ως NoAction.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<ISlide> slide)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Διαφάνεια προορισμού. |

## Hyperlink::Hyperlink(System::SharedPtr\<Hyperlink\>, System::String, System::String, bool, bool, bool) constructor

Δημιουργεί μια παρουσία υπερσυνδέσμου χρησιμοποιώντας έναν άλλο υπερσύνδεσμο ως πηγή, παρακάμπτοντας δευτερεύουσες ιδιότητες.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<Hyperlink> source, System::String targetFrame, System::String tooltip, bool history, bool stopSoundsOnClick, bool highlightClick)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | [System::SharedPtr](../../../system/sharedptr/)\<[Hyperlink](../)\> | Πηγή υπερσύνδεσμου |
| targetFrame | [System::String](../../../system/string/) | Πλαίσιο προορισμού |
| tooltip | [System::String](../../../system/string/) | Κείμενο υπόδειξης |
| history | **bool** |  |
| stopSoundsOnClick | **bool** |  |
| highlightClick | **bool** |  |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [Hyperlink](../)
* Κλάση [ISlide](../../islide/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)