---
title: Matches()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดว่ากโหนดปัจจุบันตรงกับ XPathExpression ที่ระบุหรือไม่.
type: docs
weight: 820
url: /th/system.xml.xpath/xpathnavigator/matches/
---
## XPathNavigator::Matches(SharedPtr\<XPathExpression\>) เมธอด


กำหนดว่ากโหนดปัจจุบันตรงกับ [XPathExpression](../../xpathexpression/) ที่ระบุหรือไม่.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(SharedPtr<XPathExpression> expr)
```


### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | อ็อบเจ็กต์ [XPathExpression](../../xpathexpression/) ที่บรรจุนิพจน์ [XPath](../../) ที่คอมไพล์แล้ว. |

### Return Value

**true** หากโหนดปัจจุบันตรงกับ [XPathExpression](../../xpathexpression/); หากไม่เช่นนั้น **false**.

## XPathNavigator::Matches(String) เมธอด


กำหนดว่ากโหนดปัจจุบันตรงกับนิพจน์ [XPath](../../) ที่ระบุหรือไม่.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(String xpath)
```


### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | นิพจน์ [XPath](../../). |

### Return Value

**true** หากโหนดปัจจุบันตรงกับนิพจน์ [XPath](../../) ที่ระบุ; หากไม่เช่นนั้น **false**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)