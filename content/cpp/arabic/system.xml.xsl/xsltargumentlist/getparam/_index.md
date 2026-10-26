---
title: GetParam()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يرجع المعامل المرتبط بالاسم المؤهل لمساحة الاسم.
type: docs
weight: 14
url: /ar/system.xml.xsl/xsltargumentlist/getparam/
---
## XsltArgumentList::GetParam(const String\&, const String\&) method


يرجع المعامل المرتبط باسم مؤهل مساحة الاسم.

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetParam(const String &name, const String &namespaceUri)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | اسم المعامل. [XsltArgumentList](../) لا يتحقق لضمان أن الاسم الممرَّ هو اسم محلي صالح؛ ومع ذلك، لا يمكن أن يكون الاسم **nullptr**. |
| namespaceUri | const [String](../../../system/string/)\& | معرّف URI لمساحة الاسم المرتبط بالمعامل. |

### قيمة الإرجاع

كائن المعامل أو **nullptr** إذا لم يتم العثور على أحد.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [String](../../../system/string/)
* فئة [XsltArgumentList](../)
* مساحة اسم [System::Xml::Xsl](../../)
* مكتبة [Aspose.Slides](../../../)