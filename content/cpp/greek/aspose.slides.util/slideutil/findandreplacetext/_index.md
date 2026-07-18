---
title: FindAndReplaceText()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αναζητά και αντικαθιστά κείμενο στην παρουσίαση με το δεδομένο μορφότυπο
type: docs
weight: 40
url: /el/aspose.slides.util/slideutil/findandreplacetext/
---
## SlideUtil::FindAndReplaceText(System::SharedPtr\<IPresentation\>, bool, System::String, System::String, System::SharedPtr\<PortionFormat\>) μέθοδος

Αναζητά και αντικαθιστά κείμενο στην παρουσίαση με το συγκεκριμένο μορφότυπο

```cpp
static void Aspose::Slides::Util::SlideUtil::FindAndReplaceText(System::SharedPtr<IPresentation> presentation, bool withMasters, System::String find, System::String replace, System::SharedPtr<PortionFormat> format=nullptr)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| presentation | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Σαρωμένη παρουσίαση. |
| withMasters | **bool** | Καθορίζει εάν πρέπει να σαρωθούν οι κύριες διαφάνειες. |
| find | [System::String](../../../system/string/) | Τιμή συμβολοσειράς για αναζήτηση. |
| replace | [System::String](../../../system/string/) | Τιμή συμβολοσειράς για αντικατάσταση. |
| format | [System::SharedPtr](../../../system/sharedptr/)\<[PortionFormat](../../../aspose.slides/portionformat/)\> | Μορφή για αντικατάσταση τμήματος κειμένου. Εάν είναι null, θα χρησιμοποιηθεί η μορφή του πρώτου χαρακτήρα της αναζητημένης συμβολοσειράς |

## Παρατηρήσεις

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto format = System::MakeObject<PortionFormat>();
format->set_FontHeight(24.0f);
format->set_FontItalic(NullableBool::True);
auto fillFormat = format->get_FillFormat();
fillFormat->set_FillType(FillType::Solid);
fillFormat->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());

SlideUtil::FindAndReplaceText(pres, true, u"[this block] ", u"my text ", format);
pres->Save(u"replaced", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IPresentation](../../../aspose.slides/ipresentation/)
* Κλάση [String](../../../system/string/)
* Κλάση [PortionFormat](../../../aspose.slides/portionformat/)
* Κλάση [SlideUtil](../)
* Χώρος ονομάτων [Aspose::Slides::Util](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)