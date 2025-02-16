---
title: WriteAsEmf()
second_title: Aspose.Slides for C++ API Reference
description: Saves the slide content as an EMF file.
type: docs
weight: 196
url: /aspose.slides/slide/writeasemf/
---
## Slide::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) method


Saves the slide content as an EMF file.

```cpp
void Aspose::Slides::Slide::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Target stream |
## Remarks



The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.emf");

// Saves the first slide as a metafile
pres->get_Slide(0)->WriteAsEmf(fileStream);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Slide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)