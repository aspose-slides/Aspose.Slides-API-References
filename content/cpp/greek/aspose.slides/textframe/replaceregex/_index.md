---
title: ReplaceRegex()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντικαθιστά όλα τα ταιριάσματα της κανονικής έκφρασης με την καθορισμένη συμβολοσειρά.
type: docs
weight: 183
url: /el/aspose.slides/textframe/replaceregex/
---
## TextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) μέθοδος


Αντικαθιστά όλα τα ταιριάσματα της κανονικής έκφρασης με την καθορισμένη συμβολοσειρά.

```cpp
void Aspose::Slides::TextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Η κανονική έκφραση [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) για την λήψη συμβολοσειρών που θα αντικατασταθούν. |
| newText | [System::String](../../../system/string/) | Η συμβολοσειρά για την αντικατάσταση όλων των εμφανίσεων των συμβολοσειρών που θα αντικατασταθούν. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Αντικείμενο callback για την αποθήκευση του αποτελέσματος της λειτουργίας αντικατάστασης [IFindResultCallback](../../ifindresultcallback/). |
## Παρατηρήσεις



Ο παρακάτω κώδικας δείγματος δείχνει πώς να αντικαταστήσετε κείμενο χρησιμοποιώντας κανονική έκφραση με καθορισμένη συμβολοσειρά. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Regex](../../../system.text.regularexpressions/regex/)
* Κλάση [String](../../../system/string/)
* Κλάση [IFindResultCallback](../../ifindresultcallback/)
* Κλάση [TextFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)