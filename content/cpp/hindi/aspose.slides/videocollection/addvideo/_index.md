---
title: AddVideo()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: एक अन्य प्रस्तुति से वीडियो फ़ाइल की प्रतिलिपि जोड़ता है।
type: docs
weight: 53
url: /hi/aspose.slides/videocollection/addvideo/
---
## VideoCollection::AddVideo(System::SharedPtr\<IVideo\>) विधि

एक अन्य प्रस्तुति से वीडियो फ़ाइल की प्रतिलिपि जोड़ता है।

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<IVideo> video) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | स्रोत वीडियो। |

### रिटर्न वैल्यू

जोडा गया वीडियो।

## VideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) विधि

स्ट्रीम से प्रस्तुति में वीडियो बनाता है और जोड़ता है।

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | स्ट्रीम जिससे वीडियो फ़ाइल जोड़नी है। |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | स्ट्रीम पर लागू किया जाएगा ऐसा व्यवहार। |

### रिटर्न वैल्यू

जोडा गया [IVideo](../../ivideo/)।

## VideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) विधि

बाइट एरे से प्रस्तुति में वीडियो बनाता है और जोड़ता है।

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) बाइट्स। |

### रिटर्न वैल्यू

जोडा गया वीडियो।

## संबंधित देखें

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [IVideo](../../ivideo/)
* क्लास [VideoCollection](../)
* क्लास [Stream](../../../system.io/stream/)
* नामस्थान [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)