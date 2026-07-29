---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till WebVTT stängda undertexter i slutet av samlingen.
type: docs
weight: 27
url: /sv/aspose.slides/captionscollection/add/
---
## CaptionsCollection::Add(System::String, System::String) metod


Lägger till WebVTT stängda undertexter i slutet av samlingen.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::String filePath) override
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Etiketten för de stängda undertexterna. |
| filePath | [System::String](../../../system/string/) | Sökvägen till WebVTT-filen. |

### Returvärde

Den tillagda [ICaptions](../../icaptions/)-instansen.

## CaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) metod


Lägger till WebVTT stängda undertexter i slutet av samlingen från en ström.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream) override
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Etiketten för de stängda undertexterna. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ingångsströmmen som innehåller data i WebVTT-format. |

### Returvärde

Den tillagda [ICaptions](../../icaptions/)-instansen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ICaptions](../../icaptions/)
* Klass [String](../../../system/string/)
* Klass [CaptionsCollection](../)
* Klass [Stream](../../../system.io/stream/)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)