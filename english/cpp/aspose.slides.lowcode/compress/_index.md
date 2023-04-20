---
title: Compress
second_title: Aspose.Slides for C++ API Reference
description: Represents a group of methods intended to compress Presentation.
type: docs
weight: 14
url: /cpp/aspose.slides.lowcode/compress/
---
## Compress class


Represents a group of methods intended to compress [Presentation](../../aspose.slides/presentation/).

```cpp
class Compress
```

## Methods

| Method | Description |
| --- | --- |
|  [Compress](./compress/)() |  |
| static void [CompressEmbeddedFonts](./compressembeddedfonts/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Makes compression of the [Presentation](../../aspose.slides/presentation/) by removing unused characters from embedded fonts. |
| static void [RemoveUnusedLayoutSlides](./removeunusedlayoutslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Makes compression of the [Presentation](../../aspose.slides/presentation/) by removing unused layout slides. |
| static void [RemoveUnusedMasterSlides](./removeunusedmasterslides/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Makes compression of the [Presentation](../../aspose.slides/presentation/) by removing unused master slides. |
## Remarks



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## See Also

* Namespace [Aspose::Slides::LowCode](../)
* Library [Aspose.Slides](../../)