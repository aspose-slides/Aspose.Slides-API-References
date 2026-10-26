---
title: ReplaceRegex()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντικαθιστά όλες τις αντιστοιχίες της κανονικής έκφρασης με την καθορισμένη συμβολοσειρά.
type: docs
weight: 495
url: /el/aspose.slides/ipresentation/replaceregex/
---
## IPresentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) μέθοδος

Αντικαθιστά όλες τις αντιστοιχίες της κανονικής έκφρασης με την καθορισμένη συμβολοσειρά.

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Η κανονική έκφραση [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) για λήψη συμβολοσειρών προς αντικατάσταση. |
| newText | [System::String](../../../system/string/) | Η συμβολοσειρά για αντικατάσταση όλων των περιστατικών των συμβολοσειρών προς αντικατάσταση. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Το αντικείμενο callback για λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../ifindresultcallback/). |
## Παρατηρήσεις

Το παρακάτω δείγμα κώδικα δείχνει πώς να αντικαταστήσετε κείμενο χρησιμοποιώντας κανονική έκφραση με την καθορισμένη συμβολοσειρά. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Αντικαθιστά όλες τις λέξεις με 10 ή περισσότερους χαρακτήρες με '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [String](../../../system/string/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [IPresentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)