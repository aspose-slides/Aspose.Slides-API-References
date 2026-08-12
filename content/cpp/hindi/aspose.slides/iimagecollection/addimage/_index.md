---
title: AddImage()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: प्रस्तुति में एक छवि जोड़ें।
type: docs
weight: 14
url: /hi/aspose.slides/iimagecollection/addimage/
---
## IImageCollection::AddImage(System::SharedPtr\<IImage\>) विधि

प्रस्तुति में एक छवि जोड़ें।

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IImage> image)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | जोड़ने के लिए छवि। |

### रिटर्न मान

जोड़ी गई छवि।

## टिप्पणी

यह विधि WMF/EMF मेटाफाइलों को प्रस्तुति में सम्मिलित करने से पहले रास्टर PNG छवि में बदलती है।

## IImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) विधि

मेमोरी स्ट्रीम से छवि जोड़ता है।

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | मेमोरी स्ट्रीम। |

### रिटर्न मान

जोड़ी गई छवि।

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) विधि

स्ट्रीम से प्रस्तुति में छवि जोड़ें।

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | छवि जोड़ने के लिए स्ट्रीम। |

### रिटर्न मान

जोड़ी गई छवि।

## टिप्पणी

यह विधि WMF/EMF मेटाफाइलों को रास्टर PNG छवि में परिवर्तित किए बिना प्रस्तुति में जोड़ सकती है।

## IImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) विधि

स्ट्रीम से प्रस्तुति में छवि बनाता और जोड़ता है।

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | छवि फ़ाइल जोड़ने के लिए स्ट्रीम। |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | वह व्यवहार जो स्ट्रीम पर लागू किया जाएगा। |

### रिटर्न मान

जोड़ी गई [IPPImage](../../ippimage/)।

## IImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) विधि

निर्दिष्ट बफ़र से प्रस्तुति में छवि जोड़ता है।

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | बफ़र। |

### रिटर्न मान

जोड़ी गई छवि।

## IImageCollection::AddImage(System::SharedPtr\<IPPImage\>) विधि

एक अन्य प्रस्तुति से छवि की प्रति जोड़ता है।

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | स्रोत छवि। |

### रिटर्न मान

जोड़ी गई छवि।

## IImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) विधि

SVG ऑब्जेक्ट से प्रस्तुति में छवि जोड़ें।

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | SVG छवि ऑब्जेक्ट [ISvgImage](../../isvgimage/) |

### रिटर्न मान

जोड़ी गई छवि।

## देखें

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPPImage](../../ippimage/)
* Class [IImage](../../iimage/)
* Class [IImageCollection](../)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)