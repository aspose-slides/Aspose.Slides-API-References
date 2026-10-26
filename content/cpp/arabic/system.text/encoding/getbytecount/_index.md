---
title: GetByteCount()
second_title: مرجع API Aspose.Slides للغة C++
description: احصل على عدد الأحرف المطلوبة لترميز مخزن الأحرف.
type: docs
weight: 235
url: /ar/system.text/encoding/getbytecount/
---
## Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) طريقة

احصل على عدد الأحرف المطلوبة لترميز مخزن الأحرف.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | مخزن الأحرف. |
| index | int | بداية القطعة. |
| count | int | حجم القطعة. |

### قيمة الإرجاع

حجم المخزن المطلوب.

## Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) طريقة

احصل على عدد الأحرف المطلوبة لترميز مخزن الأحرف.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | مخزن الأحرف. |
| index | int | بداية القطعة. |
| count | int | حجم القطعة. |

### قيمة الإرجاع

حجم المخزن المطلوب.

## Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) طريقة

احصل على عدد الأحرف المطلوبة لترميز مخزن الأحرف.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | مخزن الأحرف. |
| index | int | بداية القطعة. |
| count | int | حجم القطعة. |

### قيمة الإرجاع

حجم المخزن المطلوب.

## Encoding::GetByteCount(const String\&) طريقة

احصل على عدد الأحرف المطلوبة لترميز سلسلة.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) للترميز. |

### قيمة الإرجاع

حجم المخزن المطلوب.

## Encoding::GetByteCount(ArrayPtr\<char_t\>) طريقة

احصل على عدد الأحرف المطلوبة لترميز مخزن الأحرف.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | مخزن الأحرف. |

### قيمة الإرجاع

حجم المخزن المطلوب.

## Encoding::GetByteCount(const char_t *, int) طريقة

احصل على عدد الأحرف المطلوبة لترميز مخزن الأحرف.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| chars | const char_t * | مخزن الأحرف. |
| count | int | [Buffer](../../../system/buffer/) حجم. |

### قيمة الإرجاع

حجم المخزن المطلوب.

## انظر أيضاً

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)