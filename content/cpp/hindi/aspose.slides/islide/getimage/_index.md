---
title: GetImage()
second_title: Aspose.Slides for C++ API संदर्भ
description: कस्टम स्केलिंग के साथ एक इमेज ऑब्जेक्ट लौटाता है।
type: docs
weight: 105
url: /hi/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) विधि

कस्टम स्केलिंग के साथ एक Image ऑब्जेक्ट लौटाता है।

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| scaleX | **float** | x-अक्ष दिशा में इस Thumbnail को स्केल करने का मान। |
| scaleY | **float** | y-अक्ष दिशा में इस Thumbnail को स्केल करने का मान। |

### वापसी मान

Image ऑब्जेक्ट [IImage](../../iimage/)

## ISlide::GetImage() विधि

एक Thumbnail Image ऑब्जेक्ट (वास्तविक आकार का 20%) लौटाता है।

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```

### वापसी मान

Image ऑब्जेक्ट [IImage](../../iimage/)

## ISlide::GetImage(System::Drawing::Size) विधि

निर्दिष्ट आकार के साथ एक Image ऑब्जेक्ट लौटाता है।

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | बनाने के लिए इमेज का आकार। |

### वापसी मान

Image ऑब्जेक्ट [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) विधि

निर्दिष्ट पैरामीटरों के साथ एक Thumbnail tiff बिटमैप ऑब्जेक्ट लौटाता है।

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff विकल्प। |

### वापसी मान

Image ऑब्जेक्ट [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) विधि

एक Thumbnail Bitmap ऑब्जेक्ट लौटाता है।

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering विकल्प। |

### वापसी मान

Image ऑब्जेक्ट [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) विधि

कस्टम स्केलिंग के साथ एक Thumbnail Bitmap ऑब्जेक्ट लौटाता है।

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering विकल्प। |
| scaleX | **float** | x-अक्ष दिशा में इस Thumbnail को स्केल करने का मान। |
| scaleY | **float** | y-अक्ष दिशा में इस Thumbnail को स्केल करने का मान। |

### वापसी मान

Image ऑब्जेक्ट [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) विधि

निर्दिष्ट आकार के साथ एक Thumbnail Bitmap ऑब्जेक्ट लौटाता है।

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Rendering विकल्प। |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | बनाने के लिए इमेज का आकार। |

### वापसी मान

Image ऑब्जेक्ट [IImage](../../iimage/)

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IImage](../../iimage/)
* क्लास [ISlide](../)
* क्लास [Size](../../../system.drawing/size/)
* क्लास [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* क्लास [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)