---
title: get_InkEffectImages()
second_title: Aspose.Slides for C++ API संदर्भ
description: कस्टम छवियों का संग्रह प्राप्त करता है जो इंक ब्रश के विज़ुअल इफ़ेक्ट्स को सिम्युलेट करने के लिए उपयोग होता है। ये छवियां विशेष InkEffectType मानों जैसे Galaxy, Rainbow आदि के साथ इंक को रेंडर करने पर उपयोग की जाती हैं। अपनी खुद की छवियां प्रदान करके, आप प्रत्येक इंक इफ़ेक्ट के दिखने के तरीके को नियंत्रित कर सकते हैं।
type: docs
weight: 14
url: /hi/aspose.slides.ink/ink/get_inkeffectimages/
---
## Ink::get_InkEffectImages() विधि

Gets the collection of custom images used to simulate visual effects for ink brushes. These images are used when rendering ink with specific [InkEffectType](../../inkeffecttype/) values, such as Galaxy, Rainbow, etc. By providing your own images, you can control how each ink effect appears.

```cpp
static System::SharedPtr<System::Collections::Generic::IDictionary<InkEffectType, System::SharedPtr<IImage>>> Aspose::Slides::Ink::Ink::get_InkEffectImages()
```

## टिप्पणी

This property allows replacing the default ink effect textures with user-defined ones, which is particularly useful when default assets are restricted by licensing or unavailable at runtime.

Each entry in the dictionary must associate an [InkEffectType](../../inkeffecttype/) value with a corresponding [IImage](../../../aspose.slides/iimage/) object (e.g., Bitmap, or an **Aspose** image interface). 

```cpp
System::SharedPtr<IImage> image = Images::FromFile(u"image.png");
Ink::get_InkEffectImages()->Add(InkEffectType::Galaxy, image);
```

## देखें

* Enum [InkEffectType](../../inkeffecttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [IImage](../../../aspose.slides/iimage/)
* Class [Ink](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)