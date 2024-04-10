---
title: WriteAsSvg()
second_title: Aspose.Slides for C++ API Reference
description: Saves content of slide as SVG file.
type: docs
weight: 183
url: /aspose.slides/slide/writeassvg/
---
## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>) method


Saves content of slide as SVG file.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Target stream |
## Remarks



The following example shows how to convert PowerPoint to PDF with custom options. 
```cpp
// Presentation object can load PowerPoint formats like PPT, PPTX, ODP etc.
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto slides = pres->get_Slides();

for (int32_t index = 0; index < slides->get_Count(); index++)
{
    auto slide = slides->idx_get(index);
    auto fileStream = System::MakeObject<System::IO::FileStream>(System::String::Format(u"slide-{0}.svg", index),
                                                                 System::IO::FileMode::Create,
                                                                 System::IO::FileAccess::Write);
    slide->WriteAsSvg(fileStream);
}
```

## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Export::ISVGOptions\>) method


Saves content of slide as SVG file.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Export::ISVGOptions> svgOptions) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Target stream |
| svgOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | SVG generation options |
## Remarks



The following example code shows how to generate SVG image with Custom [Shape](../../shape/) IDS from PowerPoint [Presentation](../../presentation/). 
```cpp
// Instantiate a Presentation class that represents the presentation file
auto pres = System::MakeObject<Presentation>(u"CreateSlidesSVGImage.pptx");

// Access the first slide
auto slide = pres->get_Slides()->idx_get(0);
// Create a memory stream object
auto svgStream = System::MakeObject<System::IO::MemoryStream>();
// Generate SVG image of slide and save in memory stream
slide->WriteAsSvg(svgStream);
svgStream->set_Position(0);
// Save memory stream to file
auto fileStream = System::IO::File::OpenWrite(u"Aspose_out.svg");

System::ArrayPtr<uint8_t> buffer = System::MakeArray<uint8_t>(8 * 1024, 0);
int32_t len;
while ((len = svgStream->Read(buffer, 0, buffer->get_Length())) > 0)
{
    fileStream->Write(buffer, 0, len);
}

svgStream->Close();
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Slide](../)
* Class [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)