---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides للغة C++ – مرجع API
description: عند تجاوزها في فئة مشتقة، تُولِّد وتكتب كيان الحرف البديل للزوج البديل من الأحرف.
type: docs
weight: 261
url: /ar/system.xml/xmlwriter/writesurrogatecharentity/
---
## XmlWriter::WriteSurrogateCharEntity(char16_t, char16_t) طريقة

عند تجاوزها في فئة مشتقة، تُولد وتكتب كيان الحرف البديل للزوج البديل من الأحرف.

```cpp
virtual void System::Xml::XmlWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar)=0
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| lowChar | char16_t | البديل المنخفض. يجب أن تكون قيمته بين 0xDC00 و 0xDFFF. |
| highChar | char16_t | البديل العالي. يجب أن تكون قيمته بين 0xD800 و 0xDBFF. |

## انظر أيضًا

* الفئة [XmlWriter](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)