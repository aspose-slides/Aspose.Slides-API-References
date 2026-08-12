---
title: GetImage()
second_title: Aspose.Slides for C++ API संदर्भ
description: कस्टम स्केलिंग के साथ एक इमेज ऑब्जेक्ट लौटाता है।
type: docs
weight: 105
url: /hi/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) मेथड

निर्दिष्ट कस्टम स्केलिंग के साथ एक इमेज ऑब्जेक्ट लौटाता है।

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| scaleX | **float** | x-अक्ष दिशा में इस थंबनेल को स्केल करने के लिए मान। |
| scaleY | **float** | y-अक्ष दिशा में इस थंबनेल को स्केल करने के लिए मान। |

### वापसी मान

छवि ऑब्जेक्ट [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage() मेथड

वास्तविक आकार के 20% पर एक थंबनेल इमेज ऑब्जेक्ट लौटाता है।

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```

### वापसी मान

छवि ऑब्जेक्ट [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage(System::Drawing::Size) मेथड

निर्दिष्ट आकार के साथ एक इमेज ऑब्जेक्ट लौटाता है।

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | बनाने वाली इमेज का आकार। |

### वापसी मान

बिटमैप ऑब्जेक्ट।

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) मेथड

निर्दिष्ट पैरामीटरों के साथ एक थंबनेल टिफ़ बिटमैप ऑब्जेक्ट लौटाता है।

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | टिफ़ विकल्प। |

### वापसी मान

छवि ऑब्जेक्ट।

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) मेथड

एक थंबनेल बिटमैप ऑब्जेक्ट लौटाता है।

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | रेन्डरिंग विकल्प। |

### वापसी मान

बिटमैप ऑब्जेक्ट्स।

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) मेथड

कस्टम स्केलिंग के साथ एक थंबनेल बिटमैप ऑब्जेक्ट लौटाता है।

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | रेन्डरिंग विकल्प। |
| scaleX | **float** | x-अक्ष दिशा में इस थंबनेल को स्केल करने के लिए मान। |
| scaleY | **float** | y-अक्ष दिशा में इस थंबनेल को स्केल करने के लिए मान। |

### वापसी मान

बिटमैप ऑब्जेक्ट्स।

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) मेथड

निर्दिष्ट आकार के साथ एक थंबनेल बिटमैप ऑब्जेक्ट लौटाता है।

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | रेन्डरिंग विकल्प। |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | बनाने वाली इमेज का आकार। |

### वापसी मान

बिटमैप ऑब्जेक्ट्स।

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [ISlide](../)
* Class [Size](../../../system.drawing/size/)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)