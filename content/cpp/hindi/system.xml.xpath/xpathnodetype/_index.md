---
title: XPathNodeType
second_title: Aspose.Slides for C++ API संदर्भ
description: XPathNavigator वर्ग से लौटाए जा सकने वाले XPath नोड प्रकारों को परिभाषित करता है।
type: docs
weight: 157
url: /hi/system.xml.xpath/xpathnodetype/
---
## XPathNodeType enum

Defines the [XPath](../) node types that can be returned from the [XPathNavigator](../xpathnavigator/) class.

```cpp
enum class XPathNodeType
```

### मान

| Name | Value | Description |
| --- | --- | --- |
| Root | 0 | XML दस्तावेज़ या नोड ट्री का रूट नोड। |
| Element | 1 | एक तत्व, जैसे **<element>**। |
| Attribute | 2 | एक गुण, जैसे **id='123'**। |
| Namespace | 3 | एक नेमस्पेस, जैसे **xmlns=\"namespace\"**। |
| Text | 4 | नोड की टेक्स्ट सामग्री। Document [Object](../../system/object/) Model (DOM) [Text](../../system.text/) और CDATA नोड प्रकारों के समान। इसमें कम से कम एक अक्षर होता है। |
| SignificantWhitespace | 5 | सफेद स्थान अक्षरों वाला नोड और **xml:space** को **preserve** पर सेट किया गया है। |
| Whitespace | 6 | केवल सफेद स्थान अक्षरों वाला नोड और कोई महत्वपूर्ण सफेद स्थान नहीं। सफेद स्थान अक्षर हैं **'\x20'**, **'\x0d'**, **'\x0a'**, **'\x09'**। |
| ProcessingInstruction | 7 | एक प्रोसेसिंग इंस्ट्रक्शन, जैसे **<?pi test?>**। इसमें XML घोषणाएं शामिल नहीं हैं, जो [XPathNavigator](../xpathnavigator/) क्लास को दिखाई नहीं देतीं। |
| Comment | 8 | एक टिप्पणी, जैसे ****। |
| All | 9 | XPathNodeType नोड प्रकारों में से कोई भी। |

## See Also

* Namespace [System::Xml::XPath](../)
* Library [Aspose.Slides](../../)