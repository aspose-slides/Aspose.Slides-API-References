---
title: AddAudio()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक अन्य प्रस्तुति से ऑडियो फ़ाइल की एक कॉपी जोड़ता है।
type: docs
weight: 14
url: /hi/aspose.slides/iaudiocollection/addaudio/
---
## IAudioCollection::AddAudio(System::SharedPtr\<IAudio\>) मेथड


एक अन्य प्रस्तुति से ऑडियो फ़ाइल की कॉपी जोड़ता है।

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<IAudio> audio)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | स्रोत ऑडियो। |

### रिटर्न वैल्यू

जोड़ा गया ऑडियो।

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) मेथड


स्ट्रीम से प्रस्तुति में एक ऑडियो बनाता है और जोड़ता है।

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | ऑडियो जोड़ने के लिए स्ट्रीम। |

### रिटर्न वैल्यू

जोड़ा गया ऑडियो।

अप्रचलित
:   AddAudio(Stream stream, LoadingStreamBehavior loadingStreamBehavior) का प्रयोग करें। यह मेथड संस्करण 17.10 में हटा दिया जाएगा।

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) मेथड


स्ट्रीम से प्रस्तुति में एक ऑडियो बनाता है और जोड़ता है।

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | वीडियो ऑडियो जोड़ने के लिए स्ट्रीम। |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | स्ट्रीम पर लागू किया जाने वाला व्यवहार। |

### रिटर्न वैल्यू

जोड़ा गया ऑडियो।

## IAudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) मेथड


बाइट ऐरे से प्रस्तुति में एक ऑडियो बनाता है और जोड़ता है।

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) बाइट्स। |

### रिटर्न वैल्यू

जोड़ा गया ऑडियो।

## संबन्धित देखें

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [IAudio](../../iaudio/)
* क्लास [IAudioCollection](../)
* क्लास [Stream](../../../system.io/stream/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)