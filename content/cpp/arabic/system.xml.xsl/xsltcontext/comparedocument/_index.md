---
title: CompareDocument()
second_title: Aspose.Slides for C++ مرجع API
description: عندما يتم إعادة تعريفه في فئة مشتقة، يقارن معرفات الموارد الموحدة (URIs) لملفين بناءً على ترتيب تحميلهما بواسطة معالج XSLT (أي فئة XslTransform).
type: docs
weight: 53
url: /ar/system.xml.xsl/xsltcontext/comparedocument/
---
## XsltContext::CompareDocument(String, String) method

عند إعادة تعريفه في فئة مشتقة، يقارن معرفات الموارد الموحدة (URIs) الأساسية لملفين بناءً على ترتيب تحميلهما بواسطة معالج XSLT (أي فئة [XslTransform](../../xsltransform/)).

```cpp
virtual int32_t System::Xml::Xsl::XsltContext::CompareDocument(String baseUri, String nextbaseUri)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| baseUri | [String](../../../system/string/) | معرف URI الأساسي للوثيقة الأولى للمقارنة. |
| nextbaseUri | [String](../../../system/string/) | معرف URI الأساسي للوثيقة الثانية للمقارنة. |

### قيمة الإرجاع

قيمة عددية صحيحة تصف الترتيب النسبي للمعرفين الأساسيين: -1 إذا ظهر **baseUri** قبل **nextbaseUri**؛ 0 إذا كان المعرفان الأساسيان متطابقين؛ و 1 إذا ظهر **baseUri** بعد **nextbaseUri**.

## انظر أيضًا

* فئة [String](../../../system/string/)
* فئة [XsltContext](../)
* مساحة الأسماء [System::Xml::Xsl](../../)
* مكتبة [Aspose.Slides](../../../)