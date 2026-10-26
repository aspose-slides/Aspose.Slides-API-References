---
title: GetImages()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक प्रस्तुति की सभी स्लाइड्स के लिए थंबनेल इमेज ऑब्जेक्ट्स लौटाता है।
type: docs
weight: 417
url: /hi/aspose.slides/ipresentation/getimages/
---
## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) मेथड

सभी स्लाइड्स के लिए थंबनेल इमेज ऑब्जेक्ट्स लौटाता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | रेंडरिंग विकल्प। |

### वापसी मान

Bitmap ऑब्जेक्ट्स।

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) मेथड

निर्दिष्ट स्लाइड्स के लिए थंबनेल बिटमैप ऑब्जेक्ट्स लौटाता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | रेंडरिंग विकल्प। |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | स्लाइड स्थितियों की एरे, 1 से शुरू। |

### वापसी मान

Bitmap ऑब्जेक्ट्स।

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) मेथड

कस्टम स्केलिंग के साथ सभी स्लाइड्स के लिए थंबनेल इमेज ऑब्जेक्ट्स लौटाता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | रेंडरिंग विकल्प। |
| scaleX | **float** | x-अक्ष दिशा में इस थंबनेल को स्केल करने का मान। |
| scaleY | **float** | y-अक्ष दिशा में इस थंबनेल को स्केल करने का मान। |

### वापसी मान

Bitmap ऑब्जेक्ट्स।

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) मेथड

कस्टम स्केलिंग के साथ निर्दिष्ट स्लाइड्स के लिए थंबनेल इमेज ऑब्जेक्ट्स लौटाता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | रेंडरिंग विकल्प। |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | स्लाइड स्थितियों की एरे, 1 से शुरू। |
| scaleX | **float** | x-अक्ष दिशा में इस थंबनेल को स्केल करने का मान। |
| scaleY | **float** | y-अक्ष दिशा में इस थंबनेल को स्केल करने का मान। |

### वापसी मान

Bitmap ऑब्जेक्ट्स।

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) मेथड

निर्दिष्ट आकार के साथ सभी स्लाइड्स के लिए थंबनेल इमेज ऑब्जेक्ट्स लौटाता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | रेंडरिंग विकल्प। |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | बनाने के लिए इमेज का आकार। |

### वापसी मान

Bitmap ऑब्जेक्ट्स।

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) मेथड

निर्दिष्ट आकार के साथ निर्दिष्ट स्लाइड्स के लिए थंबनेल इमेज ऑब्जेक्ट्स लौटाता है।

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | रेंडरिंग विकल्प। |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | स्लाइड स्थितियों की एरे, 1 से शुरू। |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | बनाने के लिए इमेज का आकार। |

### वापसी मान

Bitmap ऑब्जेक्ट्स।

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Class [IPresentation](../)
* Class [Size](../../../system.drawing/size/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)