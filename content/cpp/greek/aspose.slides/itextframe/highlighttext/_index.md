---
title: HighlightText()
second_title: Αναφορά API του Aspose.Slides για C++
description: Στιλπώνει όλες τις αντιστοιχίες του κειμένου δείγματος με το καθορισμένο χρώμα.
type: docs
weight: 105
url: /el/aspose.slides/itextframe/highlighttext/
---
## ITextFrame::HighlightText(System::String, System::Drawing::Color) μέθοδος


Στιλπώνει όλες τις αντιστοιχίες του κειμένου δείγματος με το καθορισμένο χρώμα.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Το κείμενο προς στίλπωση. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Το χρώμα με το οποίο θα στιλπώσει το κείμενο. |

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) μέθοδος


Στιλπώνει όλες τις αντιστοιχίες του κειμένου δείγματος με το καθορισμένο χρώμα.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Το κείμενο προς στίλπωση. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Το χρώμα με το οποίο θα στιλπώσει το κείμενο. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Επιλογές στίλπωσης. |

Αποσυρμένο
:   Χρησιμοποιήστε τη μέθοδο HighlightText(string text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) αντʼ αυτά. Η μέθοδος θα αφαιρεθεί μετά την έκδοση 24.10.

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) μέθοδος


Στιλπώνει όλες τις αντιστοιχίες του κειμένου δείγματος με το καθορισμένο χρώμα.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Το κείμενο προς στίλπωση. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Το χρώμα με το οποίο θα στιλπώσει το κείμενο. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Επιλογές αναζήτησης κειμένου [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Το αντικείμενο callback για λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../ifindresultcallback/). |
## Παρατηρήσεις



Το παρακάτω δείγμα κώδικα δείχνει πώς να στίλπωση κείμενο σε ένα [TextFrame](../../textframe/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// highlighting all separate 'the' occurrences
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [ITextFrame](../)
* Class [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Class [ITextSearchOptions](../../itextsearchoptions/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)