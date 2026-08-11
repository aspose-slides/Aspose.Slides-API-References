---
title: GetBytes()
second_title: Aspose.Slides لـ C++ مرجع API
description: احصل على البايتات الناتجة عن ترميز مخزن أحرف.
type: docs
weight: 40
url: /ar/system.text/icuencoding/getbytes/
---
## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) طريقة

احصل على البايتات الناتجة عن ترميز مخزن أحرف.

```cpp
int System::Text::ICUEncoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| chars | const char_t * | الأحرف للترميز. |
| char_count | int | عدد الأحرف للتحويل. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| byte_count | int | حجم المخزن المؤقت للإخراج. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) طريقة

احصل على البايتات الناتجة عن ترميز مخزن أحرف.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | الأحرف للترميز. |
| char_index | int | بداية مقطع الأحرف. |
| char_count | int | عدد الأحرف للتحويل. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| byte_index | int | إزاحة المخزن المؤقت للإخراج. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## ICUEncoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) طريقة

احصل على البايتات الناتجة عن ترميز مخزن أحرف.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | الأحرف للترميز. |
| char_index | int | بداية مقطع الأحرف. |
| char_count | int | عدد الأحرف للتحويل. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| byte_index | int | إزاحة المخزن المؤقت للإخراج. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## ICUEncoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) طريقة

احصل على البايتات الناتجة عن ترميز مخزن أحرف.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | الأحرف للترميز. |
| char_index | int | بداية مقطع الأحرف. |
| char_count | int | عدد الأحرف للتحويل. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| byte_index | int | إزاحة المخزن المؤقت للإخراج. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## ICUEncoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) طريقة

احصل على البايتات الناتجة عن ترميز مخزن أحرف.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) للترميز. |
| char_index | int | بداية مقطع الأحرف. |
| char_count | int | عدد الأحرف للتحويل. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| byte_index | int | إزاحة المخزن المؤقت للإخراج. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## ICUEncoding::GetBytes(const String\&) طريقة

احصل على البايتات الناتجة عن ترميز مخزن أحرف.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) للترميز. |

### قيمة الإرجاع

[Buffer](../../../system/buffer/) التي تحتوي على تمثيل الأحرف المشفرة.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int) طريقة

احصل على البايتات الناتجة عن ترميز مخزن أحرف.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | الأحرف للترميز. |
| index | int | بداية مقطع الأحرف. |
| count | int | عدد الأحرف للتحويل. |

### قيمة الإرجاع

[Buffer](../../../system/buffer/) التي تحتوي على تمثيل الأحرف المشفرة.

## ICUEncoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) طريقة

احصل على البايتات الناتجة عن ترميز مخزن أحرف.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | الأحرف للترميز. |
| index | int | بداية مقطع الأحرف. |
| count | int | عدد الأحرف للتحويل. |

### قيمة الإرجاع

[Buffer](../../../system/buffer/) التي تحتوي على تمثيل الأحرف المشفرة.

## ICUEncoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) طريقة

احصل على البايتات الناتجة عن ترميز مخزن أحرف.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | الأحرف للترميز. |
| index | int | بداية مقطع الأحرف. |
| count | int | عدد الأحرف للتحويل. |

### قيمة الإرجاع

[Buffer](../../../system/buffer/) التي تحتوي على تمثيل الأحرف المشفرة.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>) طريقة

احصل على البايتات الناتجة عن ترميز مخزن أحرف.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | الأحرف للترميز. |

### قيمة الإرجاع

[Buffer](../../../system/buffer/) التي تحتوي على تمثيل الأحرف المشفرة.

## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) طريقة

احصل على البايتات الناتجة عن ترميز مخزن أحرف.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| chars | const char_t * | الأحرف للترميز. |
| char_count | int | عدد الأحرف للتحويل. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| byte_count | int | حجم المخزن المؤقت للإخراج. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [ICUEncoding](../)
* فئة [String](../../../system/string/)
* نطاق [System::Text](../../)
* مكتبة [Aspose.Slides](../../../)