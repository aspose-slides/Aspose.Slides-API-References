---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till WebVTT-undertexter i slutet av samlingen.
type: docs
weight: 27
url: /sv/aspose.slides/icaptionscollection/add/
---
## ICaptionsCollection::Add(System::String, System::String) method

Lägger till WebVTT-undertexter i slutet av samlingen.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::String filePath)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Etiketten för undertexterna. |
| filePath | [System::String](../../../system/string/) | Sökvägen till WebVTT-filen. |

### Returvärde

Den tillagda [ICaptions](../../icaptions/)-instansen.

## ICaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) method

Lägger till WebVTT-undertexter i slutet av samlingen från en ström.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Etiketten för undertexterna. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Indataströmmen som innehåller data i WebVTT-format. |

### Returvärde

Den tillagda [ICaptions](../../icaptions/)-instansen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ICaptions](../../icaptions/)
* Klass [String](../../../system/string/)
* Klass [ICaptionsCollection](../)
* Klass [Stream](../../../system.io/stream/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)