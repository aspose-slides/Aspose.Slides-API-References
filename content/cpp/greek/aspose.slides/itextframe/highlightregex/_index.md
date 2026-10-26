---
title: HighlightRegex()
second_title: Αναφορά API Aspose.Slides για C++
description: Επισημαίνει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα.
type: docs
weight: 131
url: /el/aspose.slides/itextframe/highlightregex/
---
## ITextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) method

Επισημαίνει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Η κανονική έκφραση [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) για λήψη συμβολοσειρών προς επισήμανση. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Το χρώμα για την επισήμανση του κειμένου. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Το αντικείμενο callback για λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../ifindresultcallback/). |

## Remarks

Το παρακάτω δείγμα κώδικα δείχνει πώς να επισημάνετε κείμενο σε ένα [TextFrame](../../textframe/) χρησιμοποιώντας μια κανονική έκφραση.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// επισήμανση όλων των λέξεων με 10 ή περισσότερους χαρακτήρες
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ITextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) method

Επισημαίνει όλες τις αντιστοιχίες της κανονικής έκφρασης με το καθορισμένο χρώμα.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Κείμενο της κανονικής έκφρασης για λήψη κειμένου προς επισήμανση. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Το χρώμα για την επισήμανση του κειμένου. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Επιλογές επισήμανσης. |

Αποσυρμένο
:   Χρησιμοποιήστε τη μέθοδο HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) αντ' αυτού. Η μέθοδος θα αφαιρεθεί μετά την έκδοση 24.10.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [Color](../../../system.drawing/color/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [ITextFrame](../)
* Class [String](../../../system/string/)
* Class [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)