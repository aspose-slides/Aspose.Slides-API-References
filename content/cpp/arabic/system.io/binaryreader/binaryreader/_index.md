---
title: BinaryReader()
second_title: Aspose.Slides للـ C++ - مرجع API
description: ينشئ كائنًا من فئة BinaryReader يقرأ البيانات من الدفق المحدد باستخدام ترميز UTF-8.
type: docs
weight: 1
url: /ar/system.io/binaryreader/binaryreader/
---
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&) منشئ


ينشئ كائنًا من الفئة [BinaryReader](../) التي تقرأ البيانات من الدفق المحدد باستخدام ترميز UTF-8.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input)
```


### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | دفق الإدخال |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) منشئ


ينشئ كائنًا من الفئة [BinaryReader](../) التي تقرأ البيانات من الدفق المحدد باستخدام الترميز المحدد.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding)
```


### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | دفق الإدخال |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | الترميز للاستخدام |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) منشئ


ينشئ كائنًا من الفئة [BinaryReader](../) التي تقرأ البيانات من الدفق المحدد باستخدام الترميز المحدد.

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding, bool leaveOpen)
```


### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | دفق الإدخال |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | الترميز للاستخدام |
| leaveOpen | **bool** | يحدد ما إذا كان يجب ترك الدفق **input** مفتوحًا (true) بعد التخلص من الكائن الحالي أم لا (false) |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Stream](../../stream/)
* فئة [BinaryReader](../)
* فئة [Encoding](../../../system.text/encoding/)
* نطاق [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)