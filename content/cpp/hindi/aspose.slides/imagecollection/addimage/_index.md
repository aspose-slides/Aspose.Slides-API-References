---
title: AddImage()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक अन्य प्रस्तुति से छवि की एक प्रति जोड़ता है।
type: docs
weight: 53
url: /hi/aspose.slides/imagecollection/addimage/
---
## ImageCollection::AddImage(System::SharedPtr\<IPPImage\>) विधि

एक अन्य प्रस्तुति से छवि की एक प्रति जोड़ता है।

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IPPImage> imageSource) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| imageSource | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | स्रोत छवि। |

### वापसी मान

जोड़ाई गई छवि।

## ImageCollection::AddImage(System::SharedPtr\<IImage\>) विधि

प्रस्तुति में एक छवि जोड़ें।

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<IImage> image) override
```

### आर्ज्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IImage](../../iimage/)\> | जोड़ने वाली छवि। |

### वापसी मान

जोड़ाई गई छवि।

## टिप्पणियाँ

यह विधि WMF/EMF मेटाफाइल को रास्टर PNG छवि में परिवर्तित करती है, प्रस्तुति में सम्मिलित करने से पहले।

## ImageCollection::AddImage(System::SharedPtr\<System::IO::MemoryStream\>) विधि

स्ट्रीम से प्रस्तुति में एक छवि जोड़ें।

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::MemoryStream> stream) override
```

### आर्ज्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::MemoryStream](../../../system.io/memorystream/)\> | छवि जोड़ने के लिये स्ट्रीम। |

### वापसी मान

जोड़ाई गई छवि।

## टिप्पणियाँ

यह विधि WMF/EMF मेटाफाइल को रास्टर PNG छवि में परिवर्तित किए बिना प्रस्तुति में जोड़ सकती है।

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>) विधि

स्ट्रीम से प्रस्तुति में एक छवि जोड़ें।

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream) override
```

### आर्ज्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | छवि जोड़ने के लिये स्ट्रीम। |

### वापसी मान

जोड़ाई गई छवि।

## टिप्पणियाँ

यह विधि WMF/EMF मेटाफाइल को रास्टर PNG छवि में परिवर्तित किए बिना प्रस्तुति में जोड़ सकती है।

## ImageCollection::AddImage(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) विधि

स्ट्रीम से प्रस्तुति में एक छवि बनाता है और जोड़ता है।

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### आर्ज्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | छवि फ़ाइल जोड़ने के लिए स्ट्रीम। |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | स्ट्रीम पर लागू किया जाने वाला व्यवहार। |

### वापसी मान

जोड़ा गया [IPPImage](../../ippimage/)।

## ImageCollection::AddImage(System::ArrayPtr\<uint8_t\>) विधि

निर्दिष्ट बफ़र से प्रस्तुति में एक छवि जोड़ता है।

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::ArrayPtr<uint8_t> buffer) override
```

### आर्ज्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | बफ़र। |

### वापसी मान

जोड़ाई गई छवि।

## ImageCollection::AddImage(System::SharedPtr\<ISvgImage\>) विधि

Svg ऑब्जेक्ट से प्रस्तुति में एक छवि जोड़ें।

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ImageCollection::AddImage(System::SharedPtr<ISvgImage> svgImage) override
```

### आर्ज्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Svg छवि ऑब्जेक्ट [ISvgImage](../../isvgimage/) |

### वापसी मान

जोड़ाई गई छवि।

## देखें भी

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPPImage](../../ippimage/)
* Class [ImageCollection](../)
* Class [IImage](../../iimage/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)