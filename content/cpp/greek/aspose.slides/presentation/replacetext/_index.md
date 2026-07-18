---
title: ReplaceText()
second_title: Αναφορά API Aspose.Slides για C++
description: Αντικαθιστά όλες τις εμφανίσεις του καθορισμένου κειμένου με άλλο καθορισμένο κείμενο.
type: docs
weight: 521
url: /el/aspose.slides/presentation/replacetext/
---
## Presentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) μέθοδος


Αντικαθιστά όλες τις εμφανίσεις του καθορισμένου κειμένου με άλλο καθορισμένο κείμενο.

```cpp
void Aspose::Slides::Presentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | Η συμβολοσειρά που θα αντικατασταθεί. |
| newText | [System::String](../../../system/string/) | Η συμβολοσειρά που θα αντικαταστήσει όλες τις εμφανίσεις του oldText. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Επιλογές αναζήτησης κειμένου [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Το αντικείμενο callback για λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../ifindresultcallback/). |
## Παρατηρήσεις



Ο παρακάτω κώδικας δείγματος δείχνει πώς να αντικαταστήσετε μια καθορισμένη συμβολοσειρά με άλλη καθορισμένη συμβολοσειρά. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Αντικαταστήστε όλες τις ξεχωριστές εμφανίσεις του 'the' με '<em><strong>'
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [ITextSearchOptions](../../itextsearchoptions/)
* Κλάση [IFindResultCallback](../../ifindresultcallback/)
* Κλάση [Presentation](../)
* Ονομαχώρος [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)