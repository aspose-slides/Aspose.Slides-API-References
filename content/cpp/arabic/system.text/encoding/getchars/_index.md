---
title: GetChars()
second_title: مرجع API ل Aspose.Slides للغة C++
description: احصل على الأحرف الناتجة عن فك ترميز مخزن بايت.
type: docs
weight: 274
url: /ar/system.text/encoding/getchars/
---
## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) طريقة

احصل على الأحرف التي تنتج عن فك ترميز مخزن بايت.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لقراءة البايتات من. |
| byte_index | int | إزاحة المخزن الإدخالي. |
| byte_count | int | حجم المخزن الإدخالي. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) لوضع الأحرف في. |
| char_index | int | إزاحة المخزن الإخراجي. |

### قيمة الإرجاع

عدد الأحرف المكتوبة.

## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) طريقة

احصل على الأحرف التي تنتج عن فك ترميز مخزن بايت.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لقراءة البايتات من. |
| index | int | إزاحة المخزن الإدخالي. |
| count | int | حجم المخزن الإدخالي. |

### قيمة الإرجاع

[Buffer](../../../system/buffer/) من الأحرف المفكوكة.

## Encoding::GetChars(ArrayPtr\<uint8_t\>) طريقة

احصل على الأحرف التي تنتج عن فك ترميز مخزن بايت.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لقراءة البايتات من. |

### قيمة الإرجاع

[Buffer](../../../system/buffer/) من الأحرف المفكوكة.

## Encoding::GetChars(const uint8_t *, int, char_t *, int) طريقة

احصل على الأحرف التي تنتج عن فك ترميز مخزن بايت.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) لقراءة البايتات من. |
| byte_count | int | حجم المخزن الإدخالي. |
| chars | char_t * | [Buffer](../../../system/buffer/) لوضع الأحرف في. |
| char_count | int | حجم المخزن الإخراجي. |

### قيمة الإرجاع

عدد الأحرف المكتوبة.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* الفئة [Encoding](../)
* نطاق الاسم [System::Text](../../)
* المكتبة [Aspose.Slides](../../../)