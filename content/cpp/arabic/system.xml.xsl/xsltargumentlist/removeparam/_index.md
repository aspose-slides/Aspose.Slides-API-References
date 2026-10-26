---
title: RemoveParam()
second_title: Aspose.Slides لواجهة برمجة التطبيقات C++
description: يزيل المعامل من XsltArgumentList.
type: docs
weight: 66
url: /ar/system.xml.xsl/xsltargumentlist/removeparam/
---
## XsltArgumentList::RemoveParam(const String\&, const String\&) method

يزيل المعامل من [XsltArgumentList](../).

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveParam(const String &name, const String &namespaceUri)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | اسم المعامل الذي سيتم إزالته. [XsltArgumentList](../) لا يتحقق من صحة أن الاسم الممرَّ هو اسم محلي صالح؛ مع ذلك، لا يمكن أن يكون الاسم **nullptr**. |
| namespaceUri | const [String](../../../system/string/)\& | معرّف URI للمساحة الاسمية للمعامل الذي سيتم إزالته. |

### قيمة الإرجاع

كائن المعامل أو **nullptr** إذا لم يتم العثور عليه.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [String](../../../system/string/)
* فئة [XsltArgumentList](../)
* نطاق [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)