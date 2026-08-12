---
title: Bitmap()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट मौजूदा छवि से एक नया Bitmap ऑब्जेक्ट बनाता है।
type: docs
weight: 1
url: /hi/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) निर्माता

निर्दिष्ट मौजूदा छवि से एक नया [Bitmap](../) ऑब्जेक्ट बनाता है।

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```

### आर्ग्युमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | बिटमैप छवि बनाने के लिए मौजूदा छवि |

## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) निर्माता

निर्दिष्ट स्ट्रीम से एक नया [Bitmap](../) ऑब्जेक्ट बनाता है।

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```

### आर्ग्युमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | छवि डेटा शामिल करने वाला स्ट्रीम |
| useIcm | **bool** | उपेक्षित |

## Bitmap::Bitmap(const String\&) निर्माता

निर्दिष्ट फ़ाइल से एक नया [Bitmap](../) ऑब्जेक्ट बनाता है।

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```

### आर्ग्युमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | छवि डेटा युक्त फ़ाइल का नाम |

## Bitmap::Bitmap(const String\&, bool) निर्माता

निर्दिष्ट फ़ाइल से एक नया [Bitmap](../) ऑब्जेक्ट बनाता है।

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```

### आर्ग्युमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | छवि डेटा युक्त फ़ाइल का नाम |
| useIcm | **bool** | उपेक्षित |

## Bitmap::Bitmap(int, int, Imaging::PixelFormat) निर्माता

निर्दिष्ट चौड़ाई, ऊँचाई, पिक्सेल फ़ॉर्मेट और पिक्सेल डेटा के साथ एक बिटमैप छवि का प्रतिनिधित्व करने वाला नया [Bitmap](../) ऑब्जेक्ट बनाता है।

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```

### आर्ग्युमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| width | int | छवि की चौड़ाई |
| height | int | छवि की ऊँचाई |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | छवि का पिक्सेल फ़ॉर्मेट |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) निर्माता

निर्दिष्ट मौजूदा छवि से, निर्धारित आकार में स्केल करके एक नया [Bitmap](../) ऑब्जेक्ट बनाता है।

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```

### आर्ग्युमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | बिटमैप छवि बनाने के लिए मौजूदा छवि |
| size | const [Size](../../size/)\& | नई छवि का आकार |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) निर्माता

निर्दिष्ट मौजूदा छवि से, निर्दिष्ट मानों में स्केल की गई चौड़ाई और ऊँचाई के साथ एक नया [Bitmap](../) ऑब्जेक्ट बनाता है।

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```

### आर्ग्युमेंट्स

| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | बिटमैप छवि बनाने के लिए मौजूदा छवि |
| width | int | नई छवि की चौड़ाई |
| height | int | नई छवि की ऊँचाई |

## देखें

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Image](../../image/)
* क्लास [Bitmap](../)
* क्लास [Stream](../../../system.io/stream/)
* क्लास [String](../../../system/string/)
* क्लास [Size](../../size/)
* नेमस्पेस [System::Drawing](../../)
* लाइब्रेरी [Aspose.Slides](../../../)