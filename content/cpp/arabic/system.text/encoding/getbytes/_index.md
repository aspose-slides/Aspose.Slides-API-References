---
title: GetBytes()
second_title: مرجع API Aspose.Slides للغة C++
description: احصل على البايتات التي ينتجها ترميز مخزن الأحرف.
type: docs
weight: 248
url: /ar/system.text/encoding/getbytes/
---
## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) method

احصل على البايتات التي ينتجها ترميز مخزن الأحرف.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | الأحرف المراد ترميزها. |
| char_index | int | بداية مقطع الأحرف. |
| char_count | int | عدد الأحرف المراد تحويلها. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| byte_index | int | إزاحة مخزن الإخراج. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) method

احصل على البايتات التي ينتجها ترميز مخزن الأحرف.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | الأحرف المراد ترميزها. |
| char_index | int | بداية مقطع الأحرف. |
| char_count | int | عدد الأحرف المراد تحويلها. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| byte_index | int | إزاحة مخزن الإخراج. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) method

احصل على البايتات التي ينتجها ترميز مخزن الأحرف.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | الأحرف المراد ترميزها. |
| char_index | int | بداية مقطع الأحرف. |
| char_count | int | عدد الأحرف المراد تحويلها. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| byte_index | int | إزاحة مخزن الإخراج. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) method

احصل على البايتات التي ينتجها ترميز مخزن الأحرف.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) لترميزها. |
| char_index | int | بداية مقطع الأحرف. |
| char_count | int | عدد الأحرف المراد تحويلها. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| byte_index | int | إزاحة مخزن الإخراج. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## Encoding::GetBytes(const String\&) method

احصل على البايتات التي ينتجها ترميز مخزن الأحرف.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) لترميزها. |

### قيمة الإرجاع

[Buffer](../../../system/buffer/) التي تحتوي على تمثيل الأحرف التي تم ترميزها.

## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) method

احصل على البايتات التي ينتجها ترميز مخزن الأحرف.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | الأحرف المراد ترميزها. |
| index | int | بداية مقطع الأحرف. |
| count | int | عدد الأحرف المراد تحويلها. |

### قيمة الإرجاع

[Buffer](../../../system/buffer/) التي تحتوي على تمثيل الأحرف التي تم ترميزها.

## Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) method

احصل على البايتات التي ينتجها ترميز مخزن الأحرف.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | الأحرف المراد ترميزها. |
| index | int | بداية مقطع الأحرف. |
| count | int | عدد الأحرف المراد تحويلها. |

### قيمة الإرجاع

[Buffer](../../../system/buffer/) التي تحتوي على تمثيل الأحرف التي تم ترميزها.

## Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) method

احصل على البايتات التي ينتجها ترميز مخزن الأحرف.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | الأحرف المراد ترميزها. |
| index | int | بداية مقطع الأحرف. |
| count | int | عدد الأحرف المراد تحويلها. |

### قيمة الإرجاع

[Buffer](../../../system/buffer/) التي تحتوي على تمثيل الأحرف التي تم ترميزها.

## Encoding::GetBytes(ArrayPtr\<char_t\>) method

احصل على البايتات التي ينتجها ترميز مخزن الأحرف.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | الأحرف المراد ترميزها. |

### قيمة الإرجاع

[Buffer](../../../system/buffer/) التي تحتوي على تمثيل الأحرف التي تم ترميزها.

## Encoding::GetBytes(const char_t *, int, uint8_t *, int) method

احصل على البايتات التي ينتجها ترميز مخزن الأحرف.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | الأحرف المراد ترميزها. |
| char_count | int | عدد الأحرف المراد تحويلها. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| byte_count | int | حجم مخزن الإخراج. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)