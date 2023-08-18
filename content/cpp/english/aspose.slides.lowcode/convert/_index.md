---
title: Convert
second_title: Aspose.Slides for C++ API Reference
description: Represents a group of methods intended to convert Presentation.
type: docs
weight: 27
url: /aspose.slides.lowcode/convert/
---
## Convert class


Represents a group of methods intended to convert [Presentation](../../aspose.slides/presentation/).

```cpp
class Convert
```

## Methods

| Method | Description |
| --- | --- |
| static void [AutoByExtension](./autobyextension/)([System::String](../../system/string/), [System::String](../../system/string/)) | Converts [Presentation](../../aspose.slides/presentation/) using the passed output path extension to determine the required export format. |
|  [Convert](./convert/)() |  |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/)) | Converts [Presentation](../../aspose.slides/presentation/) to PDF. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Converts [Presentation](../../aspose.slides/presentation/) to PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Converts [Presentation](../../aspose.slides/presentation/) to PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Converts [Presentation](../../aspose.slides/presentation/) to PDF. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/)) | Converts [Presentation](../../aspose.slides/presentation/) to SVG. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/), [Convert::GetOutPathCallback](./getoutpathcallback/)) | Converts [Presentation](../../aspose.slides/presentation/) to SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/)) | Converts [Presentation](../../aspose.slides/presentation/) to SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Converts [Presentation](../../aspose.slides/presentation/) to SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Converts [Presentation](../../aspose.slides/presentation/) to SVG. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [GetOutPathCallback](./getoutpathcallback/) | Callback that will be invoked for each [Slide](../../aspose.slides/slide/), the output path expected to be returned. |
## Remarks



```cpp
Convert::AutoByExtension(u"pres.pptx", u"pres.pdf");
```

## See Also

* Namespace [Aspose::Slides::LowCode](../)
* Library [Aspose.Slides](../../)