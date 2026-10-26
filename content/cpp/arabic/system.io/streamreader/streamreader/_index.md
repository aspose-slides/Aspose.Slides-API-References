---
title: StreamReader()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ كائنًا من نوع StreamReader يقرأ الأحرف من الدفق الأساسي المحدد باستخدام ترميز UTF-8 ومخزن مؤقت بحجم افتراضي قدره 1024 بايت.
type: docs
weight: 1
url: /ar/system.io/streamreader/streamreader/
---
## StreamReader::StreamReader(const SharedPtr\<Stream\>\&) المنشئ

ينشئ كائنًا من النوع [StreamReader](../) يقرأ الأحرف من الدفق الأساسي المحدد باستخدام ترميز UTF-8 ومخزن مؤقت بحجم افتراضي قدره 1024 بايت.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | الدفق الأساسي لقراءة الأحرف منه |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, bool) المنشئ

ينشئ كائنًا من النوع [StreamReader](../) يقرأ الأحرف من الدفق الأساسي المحدد باستخدام ترميز UTF-8 ومخزن مؤقت بحجم افتراضي قدره 1024 بايت. يحدد معامل ما إذا كان يجب تمكين اكتشاف علامة ترتيب البايت.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, bool detectEncodingFromByteOrderMarks)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | الدفق الأساسي لقراءة الأحرف منه |
| detectEncodingFromByteOrderMarks | **bool** | ‎True للبحث عن علامات ترتيب البايت في بداية الدفق، وإلا ‎false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&) المنشئ

ينشئ كائنًا من النوع [StreamReader](../) يقرأ الأحرف من الدفق الأساسي المحدد باستخدام الترميز المحدد ومخزن مؤقت بحجم افتراضي قدره 1024 بايت.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | الدفق الأساسي لقراءة الأحرف منه |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | الترميز المستخدم |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool) المنشئ

ينشئ كائنًا من النوع [StreamReader](../) يقرأ الأحرف من الدفق الأساسي المحدد باستخدام الترميز المحدد ومخزن مؤقت بحجم افتراضي قدره 1024 بايت. يحدد معامل ما إذا كان يجب تمكين اكتشاف علامة ترتيب البايت.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | الدفق الأساسي لقراءة الأحرف منه |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | الترميز المستخدم |
| detectEncodingFromByteOrderMarks | **bool** | ‎True للبحث عن علامات ترتيب البايت في بداية الدفق، وإلا ‎false |

## StreamReader::StreamReader(const SharedPtr\<Stream\>\&, const EncodingPtr\&, bool, int) المنشئ

ينشئ كائنًا من النوع [StreamReader](../) يقرأ الأحرف من الدفق الأساسي المحدد باستخدام الترميز المحدد ومخزن مؤقت بالحجم المحدد. يحدد معامل ما إذا كان يجب تمكين اكتشاف علامة ترتيب البايت.

```cpp
System::IO::StreamReader::StreamReader(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | الدفق الأساسي لقراءة الأحرف منه |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | الترميز المستخدم |
| detectEncodingFromByteOrderMarks | **bool** | ‎True للبحث عن علامات ترتيب البايت في بداية الدفق، وإلا ‎false |
| bufferSize | int | الحد الأدنى لحجم المخزن المؤقت بالبايت |

## StreamReader::StreamReader(const System::String\&) المنشئ

ينشئ كائنًا من النوع [StreamReader](../) يقرأ الأحرف من الملف المحدد باستخدام ترميز UTF-8 ومخزن مؤقت بحجم افتراضي قدره 4096 بايت.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | مسار الملف لقراءة الأحرف منه |

## StreamReader::StreamReader(const System::String\&, bool) المنشئ

ينشئ كائنًا من النوع [StreamReader](../) يقرأ الأحرف من الملف المحدد باستخدام ترميز UTF-8 ومخزن مؤقت بحجم افتراضي قدره 4096 بايت. يحدد معامل ما إذا كان يجب تمكين اكتشاف علامة ترتيب البايت.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, bool detectEncodingFromByteOrderMarks)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | مسار الملف لقراءة الأحرف منه |
| detectEncodingFromByteOrderMarks | **bool** | ‎True للبحث عن علامات ترتيب البايت في بداية الملف، وإلا ‎false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&) المنشئ

ينشئ كائنًا من النوع [StreamReader](../) يقرأ الأحرف من الملف المحدد باستخدام الترميز المحدد ومخزن مؤقت بحجم افتراضي قدره 4096 بايت.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | مسار الملف لقراءة الأحرف منه |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | الترميز المستخدم |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool) المنشئ

ينشئ كائنًا من النوع [StreamReader](../) يقرأ الأحرف من الدفق الأساسي المحدد باستخدام الترميز المحدد ومخزن مؤقت بحجم افتراضي قدره 4096 بايت. يحدد معامل ما إذا كان يجب تمكين اكتشاف علامة ترتيب البايت.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | مسار الملف لقراءة الأحرف منه |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | الترميز المستخدم |
| detectEncodingFromByteOrderMarks | **bool** | ‎True للبحث عن علامات ترتيب البايت في بداية الملف، وإلا ‎false |

## StreamReader::StreamReader(const System::String\&, const EncodingPtr\&, bool, int) المنشئ

ينشئ كائنًا من النوع [StreamReader](../) يقرأ الأحرف من الملف المحدد باستخدام الترميز المحدد ومخزن مؤقت بالحجم المحدد. يحدد معامل ما إذا كان يجب تمكين اكتشاف علامة ترتيب البايت.

```cpp
System::IO::StreamReader::StreamReader(const System::String &path, const EncodingPtr &encoding, bool detectEncodingFromByteOrderMarks, int bufferSize)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | const [System::String](../../../system/string/)\& | مسار الملف لقراءة الأحرف منه |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | الترميز المستخدم |
| detectEncodingFromByteOrderMarks | **bool** | ‎True للبحث عن علامات ترتيب البايت في بداية الملف، وإلا ‎false |
| bufferSize | int | الحد الأدنى لحجم المخزن المؤقت بالبايت |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* فئة [Stream](../../stream/)
* فئة [StreamReader](../)
* فئة [String](../../../system/string/)
* نطاق [System::IO](../../)
* Library [Aspose.Slides](../../../)