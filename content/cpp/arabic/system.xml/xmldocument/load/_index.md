---
title: Load()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحميل مستند XML من عنوان URL المحدد.
type: docs
weight: 508
url: /ar/system.xml/xmldocument/load/
---
## XmlDocument::Load(String) طريقة

يقوم بتحميل مستند XML من عنوان URL المحدد.

```cpp
virtual void System::Xml::XmlDocument::Load(String filename)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| filename | [String](../../../system/string/) | عنوان URL للملف الذي يحتوي على مستند XML المراد تحميله. يمكن أن يكون عنوان URL إما ملفًا محليًا أو عنوان URL HTTP (عنوان [Web](../../../system.web/)). |

## XmlDocument::Load(SharedPtr\<IO::Stream\>) طريقة

يقوم بتحميل مستند XML من التيار المحدد.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::Stream> inStream)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| inStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | التيار الذي يحتوي على مستند XML المراد تحميله. |

## XmlDocument::Load(SharedPtr\<IO::TextReader\>) طريقة

يقوم بتحميل مستند XML من الـ TextReader المحدد.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::TextReader> txtReader)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| txtReader | [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | الـ TextReader المستخدم لتغذية بيانات XML إلى المستند. |

## XmlDocument::Load(SharedPtr\<XmlReader\>) طريقة

يقوم بتحميل مستند XML من الـ [XmlReader](../../xmlreader/) المحدد.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<XmlReader> reader)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | الـ [XmlReader](../../xmlreader/) المستخدم لتغذية بيانات XML إلى المستند. |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [XmlDocument](../)
* فئة [Stream](../../../system.io/stream/)
* فئة [TextReader](../../../system.io/textreader/)
* فئة [XmlReader](../../xmlreader/)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)