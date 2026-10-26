---
title: SupportsType()
second_title: مرجع API Aspose.Slides للغة C++
description: يحدد ما إذا كان المُحلِّل يدعم أنواعًا أخرى غير Stream فقط.
type: docs
weight: 66
url: /ar/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) method


يحدد ما إذا كان المُحلِّل يدعم أنواعًا أخرى غير Stream فقط.

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | عنوان URI المطلق للتحقق منه. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | النوع المراد إرجاعه. |

### قيمة الإرجاع

**true** إذا كان النوع مدعومًا؛ وإلا، **false**.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)