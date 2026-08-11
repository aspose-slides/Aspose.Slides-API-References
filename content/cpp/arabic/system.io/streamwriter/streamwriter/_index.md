---
title: StreamWriter()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides لـ C++
description: ينشئ مثيلاً لكائن StreamWriter يكتب الأحرف إلى التيار الأساسي المحدد باستخدام ترميز UTF-8 ومخزن مؤقت بحجم افتراضي قدره 1024 بايت.
type: docs
weight: 1
url: /ar/system.io/streamwriter/streamwriter/
---
## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&) المنشئ


ينشئ مثيلاً لكائن [StreamWriter](../) يكتب الأحرف إلى التيار الأساسي المحدد باستخدام ترميز UTF-8 ومخزن مؤقت بحجم افتراضي قدره 1024 بايت.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream)
```


### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | التيار الأساسي لكتابة الأحرف إليه |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&) المنشئ


ينشئ مثيلاً لكائن [StreamWriter](../) يكتب الأحرف إلى التيار الأساسي المحدد باستخدام الترميز المحدد ومخزن مؤقت بحجم افتراضي قدره 1024 بايت.

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding)
```


### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | التيار الأساسي لكتابة الأحرف إليه |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | الترميز المستخدم |

## StreamWriter::StreamWriter(const SharedPtr\<Stream\>\&, const EncodingPtr\&, int, bool) المنشئ


ينشئ مثيلاً لكائن [StreamWriter](../) يكتب الأحرف إلى التيار الأساسي المحدد باستخدام الترميز المحدد ومخزن مؤقت بحجم محدد. يُحدِّد معطى ما إذا كان يجب إغلاق التيار الأساسي عند التخلص من كائن [StreamWriter](../).

```cpp
System::IO::StreamWriter::StreamWriter(const SharedPtr<Stream> &stream, const EncodingPtr &encoding, int buffer_size, bool leave_open=false)
```


### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | التيار الأساسي لكتابة الأحرف إليه |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | الترميز المستخدم |
| buffer_size | int | الحد الأدنى لحجم المخزن المؤقت بالبايت |
| leave_open | **bool** | يُحدِّد ما إذا كان يجب ترك التيار الأساسي مفتوحًا بعد التخلص من كائن [StreamWriter](../) الحالي |

## StreamWriter::StreamWriter(const String\&) المنشئ


ينشئ مثيلاً لكائن [StreamWriter](../) يكتب الأحرف إلى الملف المحدد باستخدام ترميز UTF-8 ومخزن مؤقت بحجم افتراضي قدره 1024 بايت.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path)
```


### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسار الملف لكتابة الأحرف إليه |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&) المنشئ


ينشئ مثيلاً لكائن [StreamWriter](../) يكتب الأحرف إلى الملف المحدد باستخدام الترميز المحدد ومخزن مؤقت بحجم افتراضي قدره 1024 بايت. يُحدِّد معطى ما إذا كان ينبغي إلحاق البيانات إلى الملف أو استبدال الملف.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked())
```


### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسار الملف لكتابة الأحرف إليه |
| append | **bool** | يُحدِّد ما إذا كان ينبغي إلحاق البيانات إلى الملف المحدد (true) أو استبدال الملف (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | الترميز المستخدم |

## StreamWriter::StreamWriter(const String\&, bool, const EncodingPtr\&, int) المنشئ


ينشئ مثيلاً لكائن [StreamWriter](../) يكتب الأحرف إلى الملف المحدد باستخدام الترميز المحدد وحجم المخزن المؤقت. يُحدِّد معطى ما إذا كان ينبغي إلحاق البيانات إلى الملف أو استبدال الملف.

```cpp
System::IO::StreamWriter::StreamWriter(const String &path, bool append, const EncodingPtr &encoding, int buffer_size)
```


### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسار الملف لكتابة الأحرف إليه |
| append | **bool** | يُحدِّد ما إذا كان ينبغي إلحاق البيانات إلى الملف المحدد (true) أو استبدال الملف (false) |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | الترميز المستخدم |
| buffer_size | int | حجم المخزن المؤقت المُستخدم |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [EncodingPtr](../../../system/encodingptr/)
* فئة [Stream](../../stream/)
* فئة [StreamWriter](../)
* فئة [String](../../../system/string/)
* مساحة اسم [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)