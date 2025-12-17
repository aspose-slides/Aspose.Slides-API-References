---
title: ToJpeg()
second_title: Aspose.Slides for C++ API Reference
description: Converts the input presentation to a set of JPEG format images.  If the output file name is given as \"myPath/myFilename.jpeg\", the result will be saved as a set of \"myPath/myFilename_N.jpeg\" files, where N is a slide number.
type: docs
weight: 40
url: /aspose.slides.lowcode/convert/tojpeg/
---
## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String) method


Converts the input presentation to a set of JPEG format images. 

 If the output file name is given as \"myPath/myFilename.jpeg\", the result will be saved as a set of \"myPath/myFilename_N.jpeg\" files, where N is a slide number.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | The input presentation. |
| outputFileName | [System::String](../../../system/string/) | The output file name. |
## Remarks




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg");
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) method


Converts the input presentation to a set of JPEG format images. 

 If the output file name is given as \"myPath/myFilename.jpeg\", the result will be saved as a set of \"myPath/myFilename_N.jpeg\" files, where N is a slide number.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | The input presentation |
| outputFileName | [System::String](../../../system/string/) | The output file name. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | The size of each generated image. |
## Remarks




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", System::Drawing::Size(720, 540));
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) method


Converts the input presentation to a set of JPEG format images. 

 If the output file name is given as \"myPath/myFilename.jpeg\", the result will be saved as a set of \"myPath/myFilename_N.jpeg\" files, where N is a slide number.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | The input presentation. |
| outputFileName | [System::String](../../../system/string/) | The output file name. |
| scale | **float** | The scaling factor applied to the output images relative to the original slide size. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | The rendering options. |
## Remarks




```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", 2.0f, options);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [String](../../../system/string/)
* Class [Convert](../)
* Class [Size](../../../system.drawing/size/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)