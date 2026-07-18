---
title: HighlightRegex()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επισημαίνει όλα τα ταιριάσματα της κανονικής έκφρασης με το καθορισμένο χρώμα.
type: docs
weight: 508
url: /el/aspose.slides/presentation/highlightregex/
---
## Presentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) μέθοδος

Επισημαίνει όλα τα ταιριάσματα της κανονικής έκφρασης με το καθορισμένο χρώμα.

```cpp
void Aspose::Slides::Presentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Η κανονική έκφραση [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) για την απόκτηση των συμβολοσειρών που θα επισημανθούν. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Το χρώμα για την επισήμανση του κειμένου. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Το αντικείμενο callback για τη λήψη των αποτελεσμάτων αναζήτησης [IFindResultCallback](../../ifindresultcallback/). |
## Σχόλια

Το παρακάτω παράδειγμα κώδικα δείχνει πώς να επισημάνετε κείμενο σε ένα PowerPoint [Presentation](../) χρησιμοποιώντας μια κανονική έκφραση. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// επισημαίνοντας όλες τις λέξεις με 10 ή περισσότερους χαρακτήρες
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Regex](../../../system.text.regularexpressions/regex/)
* Κλάση [Color](../../../system.drawing/color/)
* Κλάση [IFindResultCallback](../../ifindresultcallback/)
* Κλάση [Presentation](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)