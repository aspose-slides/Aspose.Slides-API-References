---
title: Slide()
second_title: Αναφορά API του Aspose.Slides για C++
description: "Επανάληψη κάθε ForEach::Slide στην Παρουσίαση."
type: docs
weight: 1
url: /el/aspose.slides.lowcode/foreach/slide/
---
## ForEach::Slide(System::SharedPtr\<Presentation\>, ForEach::ForEachSlideCallback) μέθοδος


Επανάληψη κάθε [ForEach::Slide](./) στο [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Slide(System::SharedPtr<Presentation> pres, ForEach::ForEachSlideCallback forEachSlide)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) για επανάληψη διαφανειών |
| forEachSlide | [ForEach::ForEachSlideCallback](../foreachslidecallback/) | Callback που θα κληθεί για κάθε διαφάνεια |
## Παρατηρήσεις




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"Slide #{0}", index));
});

ForEach::Slide(pres, callback);
```




## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachSlideCallback](../foreachslidecallback/)
* Κλάση [Presentation](../../../aspose.slides/presentation/)
* Κλάση [ForEach](../)
* Χώρος ονομάτων [Aspose::Slides::LowCode](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)