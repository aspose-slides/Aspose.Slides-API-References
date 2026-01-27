---
title: ToTiff()
second_title: Aspose.Slides for C++ API Reference
description: Converts the input presentation to a set of TIFF format images.  If the output file name is given as \"myPath/myFilename.tiff\", the result will be saved as a set of \"myPath/myFilename_N.tiff\" files, where N is a slide number.
type: docs
weight: 66
url: /aspose.slides.lowcode/convert/totiff/
---
## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String) method


Converts the input presentation to a set of TIFF format images. 

 If the output file name is given as \"myPath/myFilename.tiff\", the result will be saved as a set of \"myPath/myFilename_N.tiff\" files, where N is a slide number.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | The input presentation. |
| outputFileName | [System::String](../../../system/string/) | The output file name. |
## Remarks




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"presImage.tiff");
```

## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ITiffOptions\>, bool) method


Converts the input presentation to TIFF format with custom options. If the output file name is given as \"myPath/myFilename.tiff\" and *multipage*  is **false**, the result will be saved as a set of \"myPath/myFilename_N.tiff\" files, where N is a slide number. Otherwise, if *multipage*  is **true**, the result will be a multi-page \"myPath/myFilename.tiff\" document.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ITiffOptions> options, bool multipage)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | The input presentation. |
| outputFileName | [System::String](../../../system/string/) | The output file name. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | The TIFF saving options. |
| multipage | **bool** | Specifies whether the generated TIFF document should be a multi-page. |
## Remarks




```cpp
System::SharedPtr<ITiffOptions> options = System::MakeObject<TiffOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);
options->set_CompressionType(TiffCompressionTypes::CCITT3);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"pres.tiff", options, false);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [String](../../../system/string/)
* Class [Convert](../)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)