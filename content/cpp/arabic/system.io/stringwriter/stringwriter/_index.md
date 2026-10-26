---
title: StringWriter()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ نسخة جديدة من StringWriter باستخدام StringBuilder المحدد و IFormatProvider.
type: docs
weight: 1
url: /ar/system.io/stringwriter/stringwriter/
---
## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) مُنشئ

إنشاء نسخة جديدة من [StringWriter](../) باستخدام StringBuilder المحدد و [IFormatProvider](../../../system/iformatprovider/).

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb, const IFormatProviderPtr &formatProvider)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | كائن StringBuilder الذي سيُستخدم بواسطة [StringWriter](../) الجاري إنشاؤه |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | كائن [IFormatProvider](../../../system/iformatprovider/) الذي سيُستخدم بواسطة الكائن الجاري إنشاؤه |

## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&) مُنشئ

إنشاء نسخة جديدة من [StringWriter](../) باستخدام StringBuilder المحدد و[IFormatProvider](../../../system/iformatprovider/) من الثقافة الحالية.

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | كائن StringBuilder الذي سيُستخدم بواسطة [StringWriter](../) الجاري إنشاؤه |

## StringWriter::StringWriter(const IFormatProviderPtr\&) مُنشئ

إنشاء نسخة جديدة من [StringWriter](../) باستخدام [IFormatProvider](../../../system/iformatprovider/) المحدد.

```cpp
System::IO::StringWriter::StringWriter(const IFormatProviderPtr &formatProvider)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | كائن [IFormatProvider](../../../system/iformatprovider/) الذي سيُستخدم بواسطة الكائن الجاري إنشاؤه |

## StringWriter::StringWriter() مُنشئ

إنشاء نسخة جديدة من [StringWriter](../) باستخدام [IFormatProvider](../../../system/iformatprovider/) من الثقافة الحالية.

```cpp
System::IO::StringWriter::StringWriter()
```

## انظر أيضًا

* نوع معرف [SharedPtr](../../../system/sharedptr/)
* نوع معرف [IFormatProviderPtr](../../../system/iformatproviderptr/)
* فئة [StringBuilder](../../../system.text/stringbuilder/)
* فئة [StringWriter](../)
* نطاق [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)