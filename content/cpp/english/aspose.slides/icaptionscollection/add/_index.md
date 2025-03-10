---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Adds WebVTT closed captions to the end of the collection.
type: docs
weight: 27
url: /aspose.slides/icaptionscollection/add/
---
## ICaptionsCollection::Add(System::String, System::String) method


Adds WebVTT closed captions to the end of the collection.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::String filePath)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | The label of the closed captions. |
| filePath | [System::String](../../../system/string/) | The path to the WebVTT file. |

### Return Value

The added [ICaptions](../../icaptions/) instance.

## ICaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) method


Adds WebVTT closed captions to the end of the collection from a stream.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | The label of the closed captions. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | The input stream containing data in WebVTT format. |

### Return Value

The added [ICaptions](../../icaptions/) instance.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICaptions](../../icaptions/)
* Class [String](../../../system/string/)
* Class [ICaptionsCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)