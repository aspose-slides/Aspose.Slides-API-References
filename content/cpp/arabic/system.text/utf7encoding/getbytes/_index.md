---
title: GetBytes()
second_title: مرجع API Aspose.Slides للغة C++
description: احصل على البايتات الناتجة عن ترميز مخزن الأحرف.
type: docs
weight: 66
url: /ar/system.text/utf7encoding/getbytes/
---
## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) طريقة


احصل على البايتات الناتجة عن ترميز مخزن الأحرف.

```cpp
int System::Text::UTF7Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```


### المتغيّرات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | الأحرف التي سيتم ترميزها. |
| char_index | int | بداية جزء الأحرف. |
| char_count | int | عدد الأحرف التي سيتم تحويلها. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| byte_index | int | إزاحة مخزن الإخراج. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) طريقة


احصل على البايتات الناتجة عن ترميز مخزن الأحرف.

```cpp
int System::Text::UTF7Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```


### المتغيّرات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| chars | const char_t * | الأحرف التي سيتم ترميزها. |
| char_count | int | عدد الأحرف التي سيتم تحويلها. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| byte_count | int | حجم مخزن الإخراج. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) طريقة


احصل على البايتات الناتجة عن ترميز مخزن الأحرف.

```cpp
int System::Text::UTF7Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```


### المتغيّرات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) للترميز. |
| char_index | int | بداية جزء الأحرف. |
| char_count | int | عدد الأحرف التي سيتم تحويلها. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| byte_index | int | إزاحة مخزن الإخراج. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) طريقة


احصل على البايتات الناتجة عن ترميز مخزن الأحرف.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### المتغيّرات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | الأحرف التي سيتم ترميزها. |
| char_index | int | بداية جزء الأحرف. |
| char_count | int | عدد الأحرف التي سيتم تحويلها. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| byte_index | int | إزاحة مخزن الإخراج. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## UTF7Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) طريقة


احصل على البايتات الناتجة عن ترميز مخزن الأحرف.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```


### المتغيّرات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | الأحرف التي سيتم ترميزها. |
| char_index | int | بداية جزء الأحرف. |
| char_count | int | عدد الأحرف التي سيتم تحويلها. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| byte_index | int | إزاحة مخزن الإخراج. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## UTF7Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) طريقة


احصل على البايتات الناتجة عن ترميز مخزن الأحرف.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```


### المتغيّرات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | الأحرف التي سيتم ترميزها. |
| char_index | int | بداية جزء الأحرف. |
| char_count | int | عدد الأحرف التي سيتم تحويلها. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| byte_index | int | إزاحة مخزن الإخراج. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) طريقة


احصل على البايتات الناتجة عن ترميز مخزن الأحرف.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### المتغيّرات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) للترميز. |
| char_index | int | بداية جزء الأحرف. |
| char_count | int | عدد الأحرف التي سيتم تحويلها. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| byte_index | int | إزاحة مخزن الإخراج. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## UTF7Encoding::GetBytes(const String\&) طريقة


احصل على البايتات الناتجة عن ترميز مخزن الأحرف.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```


### المتغيّرات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) للترميز. |

### قيمة الإرجاع

[Buffer](../../../system/buffer/) التي تحمل تمثيل الأحرف التي تم ترميزها.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) طريقة


احصل على البايتات الناتجة عن ترميز مخزن الأحرف.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```


### المتغيّرات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | الأحرف التي سيتم ترميزها. |
| index | int | بداية جزء الأحرف. |
| count | int | عدد الأحرف التي سيتم تحويلها. |

### قيمة الإرجاع

[Buffer](../../../system/buffer/) التي تحمل تمثيل الأحرف التي تم ترميزها.

## UTF7Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) طريقة


احصل على البايتات الناتجة عن ترميز مخزن الأحرف.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```


### المتغيّرات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | الأحرف التي سيتم ترميزها. |
| index | int | بداية جزء الأحرف. |
| count | int | عدد الأحرف التي سيتم تحويلها. |

### قيمة الإرجاع

[Buffer](../../../system/buffer/) التي تحمل تمثيل الأحرف التي تم ترميزها.

## UTF7Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) طريقة


احصل على البايتات الناتجة عن ترميز مخزن الأحرف.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


### المتغيّرات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | الأحرف التي سيتم ترميزها. |
| index | int | بداية جزء الأحرف. |
| count | int | عدد الأحرف التي سيتم تحويلها. |

### قيمة الإرجاع

[Buffer](../../../system/buffer/) التي تحمل تمثيل الأحرف التي تم ترميزها.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>) طريقة


احصل على البايتات الناتجة عن ترميز مخزن الأحرف.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```


### المتغيّرات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | الأحرف التي سيتم ترميزها. |

### قيمة الإرجاع

[Buffer](../../../system/buffer/) التي تحمل تمثيل الأحرف التي تم ترميزها.

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) طريقة


احصل على البايتات الناتجة عن ترميز مخزن الأحرف.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```


### المتغيّرات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| chars | const char_t * | الأحرف التي سيتم ترميزها. |
| char_count | int | عدد الأحرف التي سيتم تحويلها. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) لوضع الأحرف فيه. |
| byte_count | int | حجم مخزن الإخراج. |

### قيمة الإرجاع

عدد البايتات المكتوبة.

## انظر أيضاً

* Typedef [ArrayPtr](../../../system/arrayptr/)
* الفئة [UTF7Encoding](../)
* الفئة [String](../../../system/string/)
* النطاق [System::Text](../../)
* المكتبة [Aspose.Slides](../../../)