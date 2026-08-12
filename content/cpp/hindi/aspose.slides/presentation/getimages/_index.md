---
title: GetImages()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक प्रेज़ेंटेशन की सभी स्लाइड्स के लिए Image ऑब्जेक्ट्स लौटाता है।
type: docs
weight: 456
url: /hi/aspose.slides/presentation/getimages/
---
## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) मेथड

एक प्रेजेंटेशन की सभी स्लाइड्स के लिए Image ऑब्जेक्ट्स लौटाता है।

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff विकल्प। |

### रिटर्न वैल्यू

Image ऑब्जेक्ट्स।

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) मेथड

एक प्रेजेंटेशन की निर्दिष्ट स्लाइड्स के लिए Thumbnail Image ऑब्जेक्ट्स लौटाता है।

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff विकल्प। |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | स्लाइड स्थितियों की एरे, 1 से शुरू। |

### रिटर्न वैल्यू

Image ऑब्जेक्ट्स।

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) मेथड

कस्टम स्केलिंग के साथ एक प्रेजेंटेशन की सभी स्लाइड्स के लिए Thumbnail Image ऑब्जेक्ट्स लौटाता है।

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff विकल्प। |
| scaleX | **float** | x-अक्ष दिशा में इस Thumbnail को स्केल करने के लिए मान। |
| scaleY | **float** | y-अक्ष दिशा में इस Thumbnail को स्केल करने के लिए मान। |

### रिटर्न वैल्यू

Image ऑब्जेक्ट्स।

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) मेथड

कस्टम स्केलिंग के साथ एक प्रेजेंटेशन की निर्दिष्ट स्लाइड्स के लिए Thumbnail Image ऑब्जेक्ट्स लौटाता है।

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff विकल्प। |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | स्लाइड स्थितियों की एरे, 1 से शुरू। |
| scaleX | **float** | x-अक्ष दिशा में इस Thumbnail को स्केल करने के लिए मान। |
| scaleY | **float** | y-अक्ष दिशा में इस Thumbnail को स्केल करने के लिए मान। |

### रिटर्न वैल्यू

Image ऑब्जेक्ट्स।

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) मेथड

निर्दिष्ट आकार के साथ एक प्रेजेंटेशन की सभी स्लाइड्स के लिए Thumbnail Image ऑब्जेक्ट्स लौटाता है।

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff विकल्प। |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | बनायी जाने वाली छवि का आकार। |

### रिटर्न वैल्यू

Image ऑब्जेक्ट्स।

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) मेथड

निर्दिष्ट आकार के साथ एक प्रेजेंटेशन की निर्दिष्ट स्लाइड्स के लिए Thumbnail Image ऑब्जेक्ट्स लौटाता है।

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff विकल्प। |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | स्लाइड स्थितियों की एरे, 1 से शुरू। |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | बनायी जाने वाली छवि का आकार। |

### रिटर्न वैल्यू

Image ऑब्जेक्ट्स।

## संबंधित देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IImage](../../iimage/)
* क्लास [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* क्लास [Presentation](../)
* क्लास [Size](../../../system.drawing/size/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)