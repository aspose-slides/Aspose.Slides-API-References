---
title: AddAudio()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक अन्य प्रस्तुति से ऑडियो फ़ाइल की एक प्रति जोड़ता है।
type: docs
weight: 53
url: /hi/aspose.slides/audiocollection/addaudio/
---
## AudioCollection::AddAudio(System::SharedPtr\<IAudio\>) विधि

एक अन्य प्रस्तुति से ऑडियो फ़ाइल की एक प्रतिलिपि जोड़ता है।

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<IAudio> audio) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | स्रोत ऑडियो। |

### रिटर्न मान

जोड़ा गया ऑडियो।

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) विधि

स्ट्रीम से एक ऑडियो बनाता है और उसे प्रस्तुति में जोड़ता है।

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | ऑडियो जोड़ने के लिए स्ट्रीम। |

### रिटर्न मान

जोड़ा गया ऑडियो।

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) विधि

स्ट्रीम से एक ऑडियो बनाता है और उसे प्रस्तुति में जोड़ता है।

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | वीडियो ऑडियो जोड़ने के लिए स्ट्रीम। |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | वह व्यवहार जो स्ट्रीम पर लागू किया जाएगा। |

### रिटर्न मान

जोड़ा गया ऑडियो।

## AudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) विधि

बाइट एरे से एक ऑडियो बनाता है और उसे प्रस्तुति में जोड़ता है।

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) बाइट्स। |

### रिटर्न मान

जोड़ा गया ऑडियो।

## देखें

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [IAudio](../../iaudio/)
* क्लास [AudioCollection](../)
* क्लास [Stream](../../../system.io/stream/)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)