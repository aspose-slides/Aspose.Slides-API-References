---
title: GetString()
second_title: Aspose.Slides لواجهة برمجة التطبيقات C++
description: يفك تشفير مخزن مؤقت من البايتات إلى سلسلة.
type: docs
weight: 313
url: /ar/system.text/encoding/getstring/
---
## Encoding::GetString(uint8_t *, int) طريقة

يقوم بفك تشفير مخزن مؤقت من البايتات إلى سلسلة.

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) لقراءة البايتات من. |
| byte_count | int | حجم المخزن المؤقت للمدخلات. |

### قيمة الإرجاع

[String](../../../system/string/) من الأحرف المفكوكة.

## Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) طريقة

يقوم بفك تشفير مخزن مؤقت من البايتات إلى سلسلة.

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) لقراءة البايتات من. |

### قيمة الإرجاع

[String](../../../system/string/) من الأحرف المفكوكة.

## Encoding::GetString(ArrayPtr\<uint8_t\>) طريقة

يقوم بفك تشفير مخزن مؤقت من البايتات إلى سلسلة.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لقراءة البايتات من. |

### قيمة الإرجاع

[String](../../../system/string/) من الأحرف المفكوكة.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) طريقة

يقوم بفك تشفير مخزن مؤقت من البايتات إلى سلسلة.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) لقراءة البايتات من. |

### قيمة الإرجاع

[String](../../../system/string/) من الأحرف المفكوكة.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) طريقة

يقوم بفك تشفير مخزن مؤقت من البايتات إلى سلسلة.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) لقراءة البايتات من. |

### قيمة الإرجاع

[String](../../../system/string/) من الأحرف المفكوكة.

## Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) طريقة

يقوم بفك تشفير مخزن مؤقت من البايتات إلى سلسلة.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لقراءة البايتات من. |
| index | int | إزاحة المخزن المؤقت للمدخلات. |
| count | int | حجم المخزن المؤقت للمدخلات. |

### قيمة الإرجاع

[String](../../../system/string/) من الأحرف المفكوكة.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) طريقة

يقوم بفك تشفير مخزن مؤقت من البايتات إلى سلسلة.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) لقراءة البايتات من. |
| index | int | إزاحة المخزن المؤقت للمدخلات. |
| count | int | حجم المخزن المؤقت للمدخلات. |

### قيمة الإرجاع

[String](../../../system/string/) من الأحرف المفكوكة.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) طريقة

يقوم بفك تشفير مخزن مؤقت من البايتات إلى سلسلة.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) لقراءة البايتات من. |
| index | int | إزاحة المخزن المؤقت للمدخلات. |
| count | int | حجم المخزن المؤقت للمدخلات. |

### قيمة الإرجاع

[String](../../../system/string/) من الأحرف المفكوكة.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [String](../../../system/string/)
* فئة [Encoding](../)
* فئة [ReadOnlySpan](../../../system/readonlyspan/)
* مساحة الأسماء [System::Text](../../)
* مكتبة [Aspose.Slides](../../../)