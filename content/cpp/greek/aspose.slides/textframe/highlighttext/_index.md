---
title: HighlightText()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επισημαίνει όλες τις εμφανίσεις του δείγματος κειμένου με το συγκεκριμένο χρώμα.
type: docs
weight: 131
url: /el/aspose.slides/textframe/highlighttext/
---
## TextFrame::HighlightText(System::String, System::Drawing::Color) μέθοδος

Επισημαίνει όλες τις εμφανίσεις του δείγματος κειμένου με το συγκεκριμένο χρώμα.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Δείγμα κειμένου για επισήμανση. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Το χρώμα για επισήμανση του κειμένου. |


## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) μέθοδος

Επισημαίνει όλες τις εμφανίσεις του δείγματος κειμένου με το συγκεκριμένο χρώμα.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Το κείμενο για επισήμανση. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Το χρώμα για επισήμανση του κειμένου. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Επιλογές επισήμανσης. |


## Σχόλια

Αποσυρμένο
:   Χρησιμοποιήστε HighlightText(string text, Color highlightColor, ITextSearchOptions options) μέθοδος αντί αυτού. Η μέθοδος θα αφαιρεθεί μετά την έκδοση 24.10.

Ο ακόλουθος κώδικας δείγματος δείχνει πώς να επισημάνετε κείμενο σε ένα [TextFrame](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"title", System::Drawing::Color::get_LightBlue());

auto textHighlightOptions = System::MakeObject<TextHighlightingOptions>();
textHighlightOptions->set_WholeWordsOnly(true);

// highlighting all separate 'the' occurrences
shape->get_TextFrame()->HighlightText(u"to", System::Drawing::Color::get_Violet(), textHighlightOptions);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) μέθοδος

Επισημαίνει όλες τις εμφανίσεις του δείγματος κειμένου με το συγκεκριμένο χρώμα.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Το κείμενο για επισήμανση. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Το χρώμα για επισήμανση του κειμένου. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Επιλογές αναζήτησης κειμένου [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Το αντικείμενο callback για λήψη αποτελεσμάτων αναζήτησης [IFindResultCallback](../../ifindresultcallback/). |


## Σχόλια



Το ακόλουθο δείγμα κώδικα δείχνει πώς να επισημάνετε κείμενο σε ένα [TextFrame](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// Επισήμανση όλων των λέξεων 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Επισήμανση όλων των ξεχωριστών εμφανίσεων του 'the'
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [Color](../../../system.drawing/color/)
* Κλάση [TextFrame](../)
* Κλάση [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Κλάση [ITextSearchOptions](../../itextsearchoptions/)
* Κλάση [IFindResultCallback](../../ifindresultcallback/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)