---
title: Intersect()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान ऑब्जेक्ट द्वारा प्रदर्शित आयत को उस आयत से प्रतिस्थापित करता है जो निर्दिष्ट ऑब्जेक्ट द्वारा प्रदर्शित आयत के साथ उसके प्रतिच्छेदन से प्राप्त होती है।
type: docs
weight: 274
url: /hi/system.drawing/rectangle/intersect/
---
## Rectangle::Intersect(const Rectangle\&) मेथड

वर्तमान ऑब्जेक्ट द्वारा प्रदर्शित आयत को उस आयत से प्रतिस्थापित करता है जो निर्दिष्ट ऑब्जेक्ट द्वारा प्रदर्शित आयत के साथ उसके प्रतिच्छेदन से प्राप्त होती है।

```cpp
void System::Drawing::Rectangle::Intersect(const Rectangle &rect)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | [Rectangle](../) ऑब्जेक्ट जो उस आयत का प्रतिनिधित्व करता है जिसे वर्तमान ऑब्जेक्ट द्वारा प्रदर्शित आयत के साथ प्रतिच्छेदित किया जाता है। |

## Rectangle::Intersect(const Rectangle\&, const Rectangle\&) मेथड

निर्दिष्ट आयतों के प्रतिच्छेदन का परिणामस्वरूप एक आयत लौटाता है।

```cpp
static Rectangle System::Drawing::Rectangle::Intersect(const Rectangle &a, const Rectangle &b)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| a | const [Rectangle](../)\& | पहली आयत जिसे प्रतिच्छेदित करना है |
| b | const [Rectangle](../)\& | दूसरी आयत जिसे प्रतिच्छेदित करना है |

### Return Value

**a** और **b** के प्रतिच्छेदन का परिणाम

## See Also

* क्लास [Rectangle](../)
* नामस्थान [System::Drawing](../../)
* लाइब्रेरी [Aspose.Slides](../../../)