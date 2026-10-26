---
title: HighlightText()
second_title: Aspose.Slides για το API αναφορά C++
description: Επισημαίνει όλες τις αντιστοιχίες του κειμένου δείγματος με το καθορισμένο χρώμα.
type: docs
weight: 495
url: /el/aspose.slides/presentation/highlighttext/
---
## Presentation::HighlightText(System::String, System::Drawing::Color) μέθοδος

Επισημαίνει όλες τις αντιστοιχίες του κειμένου δείγματος με το καθορισμένο χρώμα.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Το κείμενο προς επισήμανση. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Το χρώμα για την επισήμανση του κειμένου. |

## Παρατηρήσεις

Το παρακάτω παράδειγμα κώδικα δείχνει πώς να επισημάνετε κείμενο σε μια παρουσίαση PowerPoint. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// επισημαίνοντας όλες τις ξεχωριστές εμφανίσεις του 'the'
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Presentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) μέθοδος

Επισημαίνει όλες τις αντιστοιχίες του κειμένου δείγματος με το καθορισμένο χρώμα.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Το κείμενο προς επισήμανση. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Το χρώμα για την επισήμανση του κειμένου. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Επιλογές αναζήτησης κειμένου [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Το αντικείμενο callback για λήψη των αποτελεσμάτων αναζήτησης [IFindResultCallback](../../ifindresultcallback/). |

## Παρατηρήσεις

Το παρακάτω παράδειγμα κώδικα δείχνει πώς να επισημάνετε κείμενο σε μια παρουσίαση PowerPoint. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// επισημαίνοντας όλες τις ξεχωριστές εμφανίσεις του 'the'
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [Color](../../../system.drawing/color/)
* Κλάση [Presentation](../)
* Κλάση [ITextSearchOptions](../../itextsearchoptions/)
* Κλάση [IFindResultCallback](../../ifindresultcallback/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)