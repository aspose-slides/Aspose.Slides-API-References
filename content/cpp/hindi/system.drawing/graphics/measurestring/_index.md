---
title: MeasureString()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: निर्दिष्ट फ़ॉन्ट और निर्दिष्ट फ़ॉर्मेट में खींची गई निर्दिष्ट स्ट्रिंग का आकार लौटाता है।
type: docs
weight: 521
url: /hi/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, PointF const\&, System::SharedPtr\<StringFormat\> const\&) const विधि

निर्दिष्ट फ़ॉन्ट में निर्दिष्ट प्रारूप में खींची गई स्ट्रिंग का आकार लौटाता है।

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | जिस स्ट्रिंग का आकार गणना किया जाना है |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | स्ट्रिंग को खींचने के लिए उपयोग किया गया फ़ॉन्ट |
| origin | [PointF](../../pointf/) const\& | स्ट्रिंग के ऊपरी बाएँ कोने के स्थान को निर्दिष्ट करता है |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | स्ट्रिंग फ़ॉर्मेट को निर्दिष्ट करता है |

### रिटर्न वैल्यू

एक [SizeF](../../sizef/) ऑब्जेक्ट जो वर्तमान Grapphics ऑब्जेक्ट की PageUnit प्रॉपर्टी द्वारा निर्दिष्ट माप इकाइयों में स्ट्रिंग का आकार दर्शाता है।

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, int, System::SharedPtr\<StringFormat\> const\&) const विधि

निर्दिष्ट फ़ॉन्ट में निर्दिष्ट प्रारूप में खींची गई स्ट्रिंग का आकार लौटाता है।

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | जिस स्ट्रिंग का आकार गणना किया जाना है |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | स्ट्रिंग को खींचने के लिए उपयोग किया गया फ़ॉन्ट |
| width | int | स्ट्रिंग की अधिकतम चौड़ाई |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | स्ट्रिंग फ़ॉर्मेट को निर्दिष्ट करता है |

### रिटर्न वैल्यू

एक [SizeF](../../sizef/) ऑब्जेक्ट जो वर्तमान Grapphics ऑब्जेक्ट की PageUnit प्रॉपर्टी द्वारा निर्दिष्ट माप इकाइयों में स्ट्रिंग का आकार दर्शाता है।

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&, int\&, int\&) const विधि

अभी लागू नहीं किया गया है।

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&) const विधि

निर्दिष्ट फ़ॉन्ट में निर्दिष्ट प्रारूप में खींची गई स्ट्रिंग का आकार लौटाता है।

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | जिस स्ट्रिंग का आकार गणना किया जाना है |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | स्ट्रिंग को खींचने के लिए उपयोग किया गया फ़ॉन्ट |
| layoutArea | [SizeF](../../sizef/) const\& | स्ट्रिंग का अधिकतम लेआउट क्षेत्र |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | स्ट्रिंग फ़ॉर्मेट को निर्दिष्ट करता है |

### रिटर्न वैल्यू

एक [SizeF](../../sizef/) ऑब्जेक्ट जो वर्तमान Grapphics ऑब्जेक्ट की PageUnit प्रॉपर्टी द्वारा निर्दिष्ट माप इकाइयों में स्ट्रिंग का आकार दर्शाता है।

## सम्बंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [SizeF](../../sizef/)
* क्लास [String](../../../system/string/)
* क्लास [Font](../../font/)
* क्लास [PointF](../../pointf/)
* क्लास [StringFormat](../../stringformat/)
* क्लास [Graphics](../)
* नेमस्पेस [System::Drawing](../../)
* लाइब्रेरी [Aspose.Slides](../../../)