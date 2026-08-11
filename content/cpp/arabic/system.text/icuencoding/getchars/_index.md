---
title: GetChars()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: احصل على الأحرف الناتجة عن فك ترميز مخزن البايتات.
type: docs
weight: 66
url: /ar/system.text/icuencoding/getchars/
---
## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) طريقة

احصل على الأحرف الناتجة عن فك ترميز مخزن البايتات.

```cpp
int System::Text::ICUEncoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) لقراءة البايتات من. |
| byte_count | int | حجم المخزن الإدخالي. |
| chars | char_t * | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| char_count | int | حجم المخزن الإخراجي. |

### قيمة الإرجاع

عدد الأحرف المكتوبة.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) طريقة

احصل على الأحرف الناتجة عن فك ترميز مخزن البايتات.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لقراءة البايتات من. |
| byte_index | int | إزاحة المخزن الإدخالي. |
| byte_count | int | حجم المخزن الإدخالي. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| char_index | int | إزاحة المخزن الإخراجي. |

### قيمة الإرجاع

عدد الأحرف المكتوبة.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int) طريقة

احصل على الأحرف الناتجة عن فك ترميز مخزن البايتات.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لقراءة البايتات من. |
| index | int | إزاحة المخزن الإدخالي. |
| count | int | حجم المخزن الإدخالي. |

### قيمة الإرجاع

[Buffer](../../../system/buffer/) من الأحرف المُفَكَّرة.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>) طريقة

احصل على الأحرف الناتجة عن فك ترميز مخزن البايتات.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لقراءة البايتات من. |

### قيمة الإرجاع

[Buffer](../../../system/buffer/) من الأحرف المُفَكَّرة.

## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) طريقة

احصل على الأحرف الناتجة عن فك ترميز مخزن البايتات.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) لقراءة البايتات من. |
| byte_count | int | حجم المخزن الإدخالي. |
| chars | char_t * | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| char_count | int | حجم المخزن الإخراجي. |

### قيمة الإرجاع

عدد الأحرف المكتوبة.

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* الفئة [ICUEncoding](../)
* النطاق [System::Text](../../)
* Library [Aspose.Slides](../../../)