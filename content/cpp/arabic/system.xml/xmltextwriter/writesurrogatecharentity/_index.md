---
title: WriteSurrogateCharEntity()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بإنشاء وكتابة كيان الحرف البديل للزوج البديل من الأحرف.
type: docs
weight: 391
url: /ar/system.xml/xmltextwriter/writesurrogatecharentity/
---
## XmlTextWriter::WriteSurrogateCharEntity(char16_t, char16_t) طريقة

يقوم بإنشاء وكتابة كيان الحرف البديل للزوج البديل من الأحرف.

```cpp
void System::Xml::XmlTextWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lowChar | char16_t | المحرف البديل المنخفض. يجب أن تكون هذه قيمة بين **0xDC00** و **0xDFFF**. |
| highChar | char16_t | المحرف البديل العالي. يجب أن تكون هذه قيمة بين **0xD800** و **0xDBFF**. |

## انظر أيضًا

* الفئة [XmlTextWriter](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)