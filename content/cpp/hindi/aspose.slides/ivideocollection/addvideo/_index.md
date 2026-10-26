---
title: AddVideo()
second_title: Aspose.Slides for C++ API संदर्भ
description: किसी अन्य प्रस्तुति से वीडियो फ़ाइल की एक प्रति जोड़ता है।
type: docs
weight: 14
url: /hi/aspose.slides/ivideocollection/addvideo/
---
## IVideoCollection::AddVideo(System::SharedPtr\<IVideo\>) विधि


एक अन्य प्रस्तुति से वीडियो फ़ाइल की एक प्रति जोड़ता है।

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<IVideo> video)=0
```


### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | स्रोत वीडियो। |

### Return Value

जोड़ी गई वीडियो।

## IVideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) विधि


स्ट्रीम से एक प्रस्तुति में वीडियो बनाता और जोड़ता है।

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | वीडियो फ़ाइल जोड़ने के लिए स्ट्रीम। |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | स्ट्रीम पर लागू किया जाने वाला व्यवहार। |

### Return Value

जोड़ा गया [IVideo](../../ivideo/)।

## IVideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) विधि


बाइट एरे से एक प्रस्तुति में वीडियो बनाता और जोड़ता है।

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData)=0
```


### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) बाइट्स। |

### Return Value

जोड़ी गई वीडियो।

## अन्य देखें

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IVideo](../../ivideo/)
* Class [IVideoCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)