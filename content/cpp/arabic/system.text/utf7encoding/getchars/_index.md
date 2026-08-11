---
title: GetChars()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: الحصول على الأحرف الناتجة عن فك ترميز مخزن بايتات.
type: docs
weight: 92
url: /ar/system.text/utf7encoding/getchars/
---
## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) طريقة

الحصول على الأحرف الناتجة عن فك ترميز مخزن البايتات.

```cpp
int System::Text::UTF7Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index) override
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لقراءة البايتات من. |
| byte_index | int | إزاحة مخزن الإدخال. |
| byte_count | int | حجم مخزن الإدخال. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| char_index | int | إزاحة مخزن الإخراج. |

### قيمة الإرجاع

عدد الأحرف المكتوبة.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) طريقة

الحصول على الأحرف الناتجة عن فك ترميز مخزن البايتات.

```cpp
int System::Text::UTF7Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) لقراءة البايتات من. |
| byte_count | int | حجم مخزن الإدخال. |
| chars | char_t * | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| char_count | int | حجم مخزن الإخراج. |

### قيمة الإرجاع

عدد الأحرف المكتوبة.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) طريقة

الحصول على الأحرف الناتجة عن فك ترميز مخزن البايتات.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لقراءة البايتات من. |
| byte_index | int | إزاحة مخزن الإدخال. |
| byte_count | int | حجم مخزن الإدخال. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| char_index | int | إزاحة مخزن الإخراج. |

### قيمة الإرجاع

عدد الأحرف المكتوبة.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) طريقة

الحصول على الأحرف الناتجة عن فك ترميز مخزن البايتات.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لقراءة البايتات من. |
| index | int | إزاحة مخزن الإدخال. |
| count | int | حجم مخزن الإدخال. |

### قيمة الإرجاع

[Buffer](../../../system/buffer/) من الأحرف المفكوكة.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>) طريقة

الحصول على الأحرف الناتجة عن فك ترميز مخزن البايتات.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لقراءة البايتات من. |

### قيمة الإرجاع

[Buffer](../../../system/buffer/) من الأحرف المفكوكة.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) طريقة

الحصول على الأحرف الناتجة عن فك ترميز مخزن البايتات.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) لقراءة البايتات من. |
| byte_count | int | حجم مخزن الإدخال. |
| chars | char_t * | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| char_count | int | حجم مخزن الإخراج. |

### قيمة الإرجاع

عدد الأحرف المكتوبة.

## انظر أيضًا

* تعريف النوع [ArrayPtr](../../../system/arrayptr/)
* فئة [UTF7Encoding](../)
* مساحة الاسم [System::Text](../../)
* مكتبة [Aspose.Slides](../../../)