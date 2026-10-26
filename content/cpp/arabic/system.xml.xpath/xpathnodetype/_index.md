---
title: XPathNodeType
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد أنواع عقد XPath التي يمكن إرجاعها من فئة XPathNavigator.
type: docs
weight: 157
url: /ar/system.xml.xpath/xpathnodetype/
---
## XPathNodeType تعداد

يعرف أنواع العقد [XPath](../) التي يمكن إرجاعها من الفئة [XPathNavigator](../xpathnavigator/).

```cpp
enum class XPathNodeType
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Root | 0 | العقدة الجذرية لوثيقة XML أو شجرة العقد. |
| Element | 1 | عنصر، مثل **<element>**. |
| Attribute | 2 | سمة، مثل **id='123'**. |
| Namespace | 3 | نطاق اسم، مثل **xmlns=\"namespace\"**. |
| Text | 4 | المحتوى النصي لعقدة. ما يعادل نموذج المستند [Object](../../system/object/) (DOM) [Text](../../system.text/) وأنواع عقد CDATA. يحتوي على حرف واحد على الأقل. |
| SignificantWhitespace | 5 | عقدة تحتوي على أحرف مسافة بيضاء و **xml:space** مُعَدة إلى **preserve**. |
| Whitespace | 6 | عقدة تحتوي فقط على أحرف مسافة بيضاء ولا تحتوي على مسافة بيضاء ذات دلالة. أحرف المسافة البيضاء هي **'\x20'**, **'\x0d'**, **'\x0a'**, **'\x09'**. |
| ProcessingInstruction | 7 | تعليمات معالجة، مثل **<?pi test?>**. لا تشمل إعلانات XML، التي لا تكون مرئية للفئة [XPathNavigator](../xpathnavigator/). |
| Comment | 8 | تعليق، مثل ****. |
| All | 9 | أي من أنواع عقد XPathNodeType. |

## انظر أيضًا

* النطاق [System::Xml::XPath](../)
* المكتبة [Aspose.Slides](../../)