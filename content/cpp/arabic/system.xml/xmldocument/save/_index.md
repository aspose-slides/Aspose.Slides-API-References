---
title: Save()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحفظ مستند XML إلى الملف المحدد. إذا كان الملف المحدد موجودًا، فإن هذه الطريقة تستبدله.
type: docs
weight: 534
url: /ar/system.xml/xmldocument/save/
---
## XmlDocument::Save(String) طريقة

يحفظ مستند XML إلى الملف المحدد. إذا كان الملف المحدد موجودًا، فإن هذه الطريقة تستبدله.

```cpp
virtual void System::Xml::XmlDocument::Save(String filename)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | [String](../../../system/string/) | الموقع الذي تريد حفظ المستند فيه. |

## XmlDocument::Save(SharedPtr\<IO::Stream\>) طريقة

يحفظ مستند XML إلى التدفق المحدد.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::Stream> outStream)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | التدفق الذي تريد الحفظ إليه. |

## XmlDocument::Save(SharedPtr\<IO::TextWriter\>) طريقة

يحفظ مستند XML إلى الـ TextWriter المحدد.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::TextWriter> writer)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| writer | [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | الـ TextWriter الذي تريد الحفظ إليه. |

## XmlDocument::Save(SharedPtr\<XmlWriter\>) طريقة

يحفظ مستند XML إلى الـ [XmlWriter](../../xmlwriter/) المحدد.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<XmlWriter> w)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| w | [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../xmlwriter/)\> | الـ [XmlWriter](../../xmlwriter/) الذي تريد الحفظ إليه. |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [XmlDocument](../)
* فئة [Stream](../../../system.io/stream/)
* فئة [TextWriter](../../../system.io/textwriter/)
* فئة [XmlWriter](../../xmlwriter/)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)