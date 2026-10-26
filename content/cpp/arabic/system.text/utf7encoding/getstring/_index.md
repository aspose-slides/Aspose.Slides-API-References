---
title: GetString()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يفك ترميز مخزن مؤقت من البايتات إلى سلسلة.
type: docs
weight: 170
url: /ar/system.text/utf7encoding/getstring/
---
## UTF7Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) طريقة

يفك ترميز مخزن مؤقت من البايتات إلى سلسلة.

```cpp
String System::Text::UTF7Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لقراءة البايتات من. |
| index | int | إزاحة المخزن المؤقت للمدخل. |
| count | int | حجم المخزن المؤقت للمدخل. |

### قيمة الإرجاع

[String](../../../system/string/) من الأحرف المفكوكة.

## UTF7Encoding::GetString(uint8_t *, int) طريقة

يفك ترميز مخزن مؤقت من البايتات إلى سلسلة.

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) لقراءة البايتات من. |
| byte_count | int | حجم المخزن المؤقت للمدخل. |

### قيمة الإرجاع

[String](../../../system/string/) من الأحرف المفكوكة.

## UTF7Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) طريقة

يفك ترميز مخزن مؤقت من البايتات إلى سلسلة.

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) لقراءة البايتات من. |

### قيمة الإرجاع

[String](../../../system/string/) من الأحرف المفكوكة.

## UTF7Encoding::GetString(ArrayPtr\<uint8_t\>) طريقة

يفك ترميز مخزن مؤقت من البايتات إلى سلسلة.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لقراءة البايتات من. |

### قيمة الإرجاع

[String](../../../system/string/) من الأحرف المفكوكة.

## UTF7Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) طريقة

يفك ترميز مخزن مؤقت من البايتات إلى سلسلة.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) لقراءة البايتات من. |

### قيمة الإرجاع

[String](../../../system/string/) من الأحرف المفكوكة.

## UTF7Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) طريقة

يفك ترميز مخزن مؤقت من البايتات إلى سلسلة.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) لقراءة البايتات من. |

### قيمة الإرجاع

[String](../../../system/string/) من الأحرف المفكوكة.

## UTF7Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) طريقة

يفك ترميز مخزن مؤقت من البايتات إلى سلسلة.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لقراءة البايتات من. |
| index | int | إزاحة المخزن المؤقت للمدخل. |
| count | int | حجم المخزن المؤقت للمدخل. |

### قيمة الإرجاع

[String](../../../system/string/) من الأحرف المفكوكة.

## UTF7Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) طريقة

يفك ترميز مخزن مؤطم من البايتات إلى سلسلة.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) لقراءة البايتات من. |
| index | int | إزاحة المخزن المؤطم للمدخل. |
| count | int | حجم المخزن المؤطم للمدخل. |

### قيمة الإرجاع

[String](../../../system/string/) من الأحرف المفكوكة.

## UTF7Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) طريقة

يفك ترميز مخزن مؤطم من البايتات إلى سلسلة.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) لقراءة البايتات من. |
| index | int | إزاحة المخزن المؤطم للمدخل. |
| count | int | حجم المخزن المؤطم للمدخل. |

### قيمة الإرجاع

[String](../../../system/string/) من الأحرف المفكوكة.

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [String](../../../system/string/)
* فئة [UTF7Encoding](../)
* فئة [ReadOnlySpan](../../../system/readonlyspan/)
* النطاق [System::Text](../../)
* مكتبة [Aspose.Slides](../../../)