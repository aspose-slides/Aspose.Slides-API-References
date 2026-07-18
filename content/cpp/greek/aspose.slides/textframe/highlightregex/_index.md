---
title: HighlightRegex()
second_title: Αναφορά API Aspose.Slides για C++
description: Επισημαίνει όλα τα ταιριάσματα της κανονικής έκφρασης με το καθορισμένο χρώμα.
type: docs
weight: 157
url: /el/aspose.slides/textframe/highlightregex/
---
## TextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) μέθοδος

Επισημαίνει όλα τα ταιριάσματα της κανονικής έκφρασης με το συγκεκριμένο χρώμα.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Κείμενο της κανονικής έκφρασης για λήψη κειμένου προς επισήμανση. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Το χρώμα για την επισήμανση του κειμένου. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Επιλογές επισήμανσης. |
## Σχόλια

Παρωχημένο  
:   Χρησιμοποιήστε τη μέθοδο HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) αντ' αυτού. Η μέθοδος θα αφαιρεθεί μετά την κυκλοφορία της έκδοσης 24.10.

Το παρακάτω δείγμα κώδικα δείχνει πώς να επισημάνετε κείμενο σε ένα [TextFrame](../) χρησιμοποιώντας κανονική έκφραση.  
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto options = System::MakeObject<TextHighlightingOptions>();

// επισημαίνοντας όλες τις λέξεις με 10 ή περισσότερους χαρακτήρες
shape->get_TextFrame()->HighlightRegex(u"\\b[^\\s]{10,}\\b", System::Drawing::Color::get_Blue(), options);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) μέθοδος

Επισημαίνει όλα τα ταιριάσματα της κανονικής έκφρασης με το συγκεκριμένο χρώμα.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Η κανονική έκφραση [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) για λήψη συμβολοσειρών προς επισήμανση. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Το χρώμα για την επισήμανση του κειμένου. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Το αντικείμενο κλήσης επιστροφής για λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../ifindresultcallback/). |
## Σχόλια



Το παρακάτω δείγμα κώδικα δείχνει πώς να επισημάνετε κείμενο σε ένα [TextFrame](../) χρησιμοποιώντας κανονική έκφραση.  
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");
// επισημαίνοντας όλες τις λέξεις με 10 ή περισσότερους χαρακτήρες
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Class [TextFrame](../)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)