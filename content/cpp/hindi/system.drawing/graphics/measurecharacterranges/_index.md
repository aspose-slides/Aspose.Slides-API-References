---
title: MeasureCharacterRanges()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट स्ट्रिंग में वर्ण स्थितियों को सीमित करने वाले प्रत्येक क्षेत्र की एक सरणी लौटाता है।
type: docs
weight: 508
url: /hi/system.drawing/graphics/measurecharacterranges/
---
## Graphics::MeasureCharacterRanges(const System::String\&, const SharedPtr\<Font\>\&, RectangleF, const SharedPtr\<StringFormat\>\&) विधि


निर्दिष्ट स्ट्रिंग में वर्ण स्थितियों को बाधित करने वाले प्रत्येक क्षेत्र का एक सरणी लौटाता है।

```cpp
ArrayPtr<SharedPtr<Region>> System::Drawing::Graphics::MeasureCharacterRanges(const System::String &text, const SharedPtr<Font> &font, RectangleF layoutRect, const SharedPtr<StringFormat> &stringFormat)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | मापने के लिए स्ट्रिंग |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | स्ट्रिंग के माप के दौरान उपयोग किया गया फ़ॉन्ट |
| layoutRect | [RectangleF](../../rectanglef/) | स्ट्रिंग के माप के दौरान उपयोग किया गया लेआउट आयत |
| stringFormat | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\>\& | स्ट्रिंग फ़ॉर्मेट, जिसमें मापने के लिए वर्ण रेंज शामिल हैं |

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [Region](../../region/)
* क्लास [String](../../../system/string/)
* क्लास [Font](../../font/)
* क्लास [RectangleF](../../rectanglef/)
* क्लास [StringFormat](../../stringformat/)
* क्लास [Graphics](../)
* नामस्थान [System::Drawing](../../)
* Library [Aspose.Slides](../../../)