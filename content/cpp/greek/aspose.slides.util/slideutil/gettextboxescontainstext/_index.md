---
title: GetTextBoxesContainsText()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει όλα τα πλαίσια κειμένου στη συγκεκριμένη διαφάνεια που περιέχουν το δοσμένο κείμενο.
type: docs
weight: 66
url: /el/aspose.slides.util/slideutil/gettextboxescontainstext/
---
## SlideUtil::GetTextBoxesContainsText(System::SharedPtr\<IBaseSlide\>, System::String, bool) μέθοδος

Επιστρέφει όλα τα πλαίσια κειμένου στη συγκεκριμένη διαφάνεια που περιέχουν το δεδομένο κείμενο.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetTextBoxesContainsText(System::SharedPtr<IBaseSlide> slide, System::String text, bool checkPlaceholderText)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Το slide προς αναζήτηση. |
| text | [System::String](../../../system/string/) | Το text για αναζήτηση μέσα στα πλαίσια κειμένου. |
| checkPlaceholderText | **bool** | Καθορίζει εάν θα συμπεριληφθούν πλαίσια κειμένου που είναι άδεια, αλλά το placeholder text τους περιέχει το text αναζήτησης. |

### Τιμή Επιστροφής

Ένας πίνακας αντικειμένων [ITextFrame](../../../aspose.slides/itextframe/) που περιέχουν το καθορισμένο κείμενο.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITextFrame](../../../aspose.slides/itextframe/)
* Class [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Class [String](../../../system/string/)
* Class [SlideUtil](../)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)