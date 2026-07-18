---
title: HighlightRegex()
second_title: Aspose.Slides για την αναφορά API του C++
description: Επισημαίνει όλα τα ταιριάσματα της κανονικής έκφρασης με το καθορισμένο χρώμα.
type: docs
weight: 469
url: /el/aspose.slides/ipresentation/highlightregex/
---
## IPresentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) method

Επισημαίνει όλα τα ταιριάσματα της κανονικής έκφρασης με το καθορισμένο χρώμα.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Η κανονική έκφραση [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) για λήψη των συμβολοσειρών που θα επισημανθούν. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Το χρώμα για την επισήμανση του κειμένου. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Το αντικείμενο callback για τη λήψη των αποτελεσμάτων αναζήτησης [IFindResultCallback](../../ifindresultcallback/). |

## Remarks

Το παρακάτω παράδειγμα κώδικα δείχνει πώς να επισημάνετε κείμενο σε ένα PowerPoint [Presentation](../../presentation/) χρησιμοποιώντας μία κανονική έκφραση.

```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// επισήμανση όλων των λέξεων με 10 ή περισσότερους χαρακτήρες
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [Color](../../../system.drawing/color/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [IPresentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)