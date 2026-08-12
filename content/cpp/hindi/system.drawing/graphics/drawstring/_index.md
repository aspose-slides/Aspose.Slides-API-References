---
title: DrawString()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट फ़ॉन्ट और ब्रश का उपयोग करके निर्दिष्ट स्थान पर निर्दिष्ट स्ट्रिंग को आरेखित करता है।
type: docs
weight: 365
url: /hi/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) विधि

निर्दिष्ट फ़ॉन्ट और ब्रश का उपयोग करके निर्दिष्ट स्थान पर निर्दिष्ट स्ट्रिंग को आरेखित करता है।

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | आरेखित करने हेतु स्ट्रिंग |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | उपयोग के लिए फ़ॉन्ट |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | आरेखण के लिए उपयोग किया जाने वाला एक [Brush](../../brush/) ऑब्जेक्ट |
| topLeft | [PointF](../../pointf/) | आरेखित स्ट्रिंग के ऊपरी बाएँ कोने के स्थान को निर्दिष्ट करता है |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | स्ट्रिंग के प्रारूप को निर्दिष्ट करता है |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) विधि

निर्दिष्ट फ़ॉन्ट और ब्रश का उपयोग करके निर्दिष्ट आयत में निर्दिष्ट स्ट्रिंग को आरेखित करता है।

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | आरेखित करने हेतु स्ट्रिंग |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | उपयोग के लिए फ़ॉन्ट |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | आरेखण के लिए उपयोग किया जाने वाला एक [Brush](../../brush/) ऑब्जेक्ट |
| layoutRectangle | [RectangleF](../../rectanglef/) | स्ट्रिंग को आरेखित करने के लिये एक आयत निर्दिष्ट करता है |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | स्ट्रिंग के प्रारूप को निर्दिष्ट करता है |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) विधि

निर्दिष्ट फ़ॉन्ट और ब्रश का उपयोग करके निर्दिष्ट स्थान पर निर्दिष्ट स्ट्रिंग को आरेखित करता है।

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | आरेखित करने हेतु स्ट्रिंग |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | उपयोग के लिए फ़ॉन्ट |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | आरेखण के लिए उपयोग किया जाने वाला एक [Brush](../../brush/) ऑब्जेक्ट |
| x | **float** | आरेखित स्ट्रिंग के ऊपरी बाएँ कोने के स्थान का X निर्देशांक |
| y | **float** | आरेखित स्ट्रिंग के ऊपरी बाएँ कोने के स्थान का Y निर्देशांक |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | स्ट्रिंग के प्रारूप को निर्दिष्ट करता है |

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [String](../../../system/string/)
* क्लास [Font](../../font/)
* क्लास [Brush](../../brush/)
* क्लास [PointF](../../pointf/)
* क्लास [StringFormat](../../stringformat/)
* क्लास [Graphics](../)
* क्लास [RectangleF](../../rectanglef/)
* नेमस्पेस [System::Drawing](../../)
* Library [Aspose.Slides](../../../)