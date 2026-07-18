---
title: ReplaceText()
second_title: Aspose.Slides για C++ API Reference
description: Αντικαθιστά όλες τις εμφανίσεις του καθορισμένου κειμένου με άλλο καθορισμένο κείμενο.
type: docs
weight: 170
url: /el/aspose.slides/textframe/replacetext/
---
## TextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) μέθοδος

Αντικαθιστά όλες τις εμφανίσεις του καθορισμένου κειμένου με άλλο καθορισμένο κείμενο.

```cpp
void Aspose::Slides::TextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | Η συμβολοσειρά που θα αντικατασταθεί. |
| newText | [System::String](../../../system/string/) | Η συμβολοσειρά που αντικαθιστά όλες τις εμφανίσεις του oldText. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Επιλογές αναζήτησης κειμένου [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Αντικείμενο Callback για αποθήκευση του αποτελέσματος της λειτουργίας αντικατάστασης [IFindResultCallback](../../ifindresultcallback/). |

## Παρατηρήσεις

Ο παρακάτω κώδικας παραδείγματος δείχνει πώς να αντικαταστήσετε μια συγκεκριμένη συμβολοσειρά με μια άλλη συγκεκριμένη συμβολοσειρά. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Αντικαθιστά όλες τις ξεχωριστές εμφανίσεις του 'the' με '<em><strong>'
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ITextSearchOptions](../../itextsearchoptions/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [TextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)