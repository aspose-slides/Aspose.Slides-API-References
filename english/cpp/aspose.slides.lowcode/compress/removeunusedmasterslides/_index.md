---
title: RemoveUnusedMasterSlides()
second_title: Aspose.Slides for C++ API Reference
description: Makes compression of the Presentation by removing unused master slides.
type: docs
weight: 1
url: /cpp/aspose.slides.lowcode/compress/removeunusedmasterslides/
---
## Compress::RemoveUnusedMasterSlides(System::SharedPtr\<Presentation\>) method


Makes compression of the [Presentation](../../../aspose.slides/presentation/) by removing unused master slides.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedMasterSlides(System::SharedPtr<Presentation> pres)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | The presentation instance |
## Remarks




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [Compress](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)