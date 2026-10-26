---
title: Deserialize()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بإلغاء تسلسل مستند XML إلى كائن.
type: docs
weight: 14
url: /ar/system.xml.serialization/xmlserializer/deserialize/
---
## XmlSerializer::Deserialize(System::SharedPtr\<IO::Stream\>) طريقة

يقوم بإلغاء تسلسل مستند XML إلى كائن.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::Stream> stream)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | دفق لقراءة المستند منه. |

### قيمة الإرجاع

[Object](../../../system/object/) الذي تم تسلسله مسبقًا في المستند المُعطى.

## XmlSerializer::Deserialize(System::SharedPtr\<IO::TextReader\>) طريقة

يقوم بإلغاء تسلسل مستند XML إلى كائن.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::TextReader> textReader)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| textReader | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | قارئ لقراءة المستند منه. |

### قيمة الإرجاع

[Object](../../../system/object/) الذي تم تسلسله مسبقًا في المستند المُعطى.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>) طريقة

يقوم بإلغاء تسلسل مستند XML إلى كائن.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | قارئ لقراءة المستند منه. |

### قيمة الإرجاع

[Object](../../../system/object/) الذي تم تسلسله مسبقًا في المستند المُعطى.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>, String) طريقة

يقوم بإلغاء تسلسل مستند XML إلى كائن.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader, String encodingStyle)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | قارئ لقراءة المستند منه. |
| encodingStyle | [String](../../../system/string/) | النمط المستخدم لتسلسل الكائن. |

### قيمة الإرجاع

[Object](../../../system/object/) الذي تم تسلسله مسبقًا في المستند المُعطى.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [Stream](../../../system.io/stream/)
* فئة [XmlSerializer](../)
* فئة [TextReader](../../../system.io/textreader/)
* فئة [XmlReader](../../../system.xml/xmlreader/)
* فئة [String](../../../system/string/)
* مساحة الأسماء [System::Xml::Serialization](../../)
* مكتبة [Aspose.Slides](../../../)