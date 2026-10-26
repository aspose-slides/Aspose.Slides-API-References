---
title: ReadToFollowing()
second_title: مرجع API Aspose.Slides للغة C++
description: يقرأ حتى يتم العثور على عنصر بالاسم المؤهل المحدد.
type: docs
weight: 898
url: /ar/system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String) method


يقرأ حتى يتم العثور على عنصر بالاسم المؤهل المحدد.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```


### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم المؤهل للعنصر. |

### قيمة الإرجاع

**true** إذا تم العثور على عنصر مطابق؛ وإلا **false** وتكون [XmlReader](../) في حالة نهاية الملف.

## XmlReader::ReadToFollowing(String, String) method


يقرأ حتى يتم العثور على عنصر بالاسم المحلي المحدد ومسار URI للمجال.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```


### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| localName | [String](../../../system/string/) | الاسم المحلي للعنصر. |
| namespaceURI | [String](../../../system/string/) | URI مساحة الاسم للعنصر. |

### قيمة الإرجاع

**true** إذا تم العثور على عنصر مطابق؛ وإلا **false** وتكون [XmlReader](../) في حالة نهاية الملف.

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlReader](../)
* مساحة الاسم [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)