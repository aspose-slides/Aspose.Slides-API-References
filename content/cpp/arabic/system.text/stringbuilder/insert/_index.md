---
title: Insert()
second_title: Aspose.Slides لمرجع API الخاص بـ C++
description: يدرج سلسلة في الموضع الثابت للـ builder.
type: docs
weight: 183
url: /ar/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const String\&) طريقة

يدرج سلسلة في الموضع الثابت للـ builder.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| startIndex | int | الموضع لإدراج الأحرف فيه. |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) للإدراج. |

### قيمة الإرجاع

هذا المؤشر.

## StringBuilder::Insert(int32_t, const String\&, int32_t) طريقة

يدرج سلسلة مكررة في الموضع الثابت للـ builder.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | **int32_t** | الموضع لإدراج الأحرف فيه. |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/) للإدراج. |
| count | **int32_t** | عدد مرات تكرار **value** سلسلة. |

### قيمة الإرجاع

هذا المؤشر.

## StringBuilder::Insert(int, char_t) طريقة

يدرج حرفًا في الموضع الثابت للـ builder.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| startIndex | int | الموضع لإدراج الأحرف فيه. |
| ch | char_t | الحرف لإدراجه. |

### قيمة الإرجاع

هذا المؤشر.

## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) طريقة

يدرج أحرفًا في الموضع الثابت للـ builder.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الموضع لإدراج الأحرف فيه. |
| chars | const [System::ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | [Array](../../../system/array/) لإدراج الجزء من. |
| startIndex | int | [Array](../../../system/array/) فهرس بداية الجزء. |
| charCount | int | [Array](../../../system/array/) طول الجزء. |

### قيمة الإرجاع

هذا المؤشر.

## StringBuilder::Insert(int, T) طريقة

يدرج قيمة في الموضع الثابت للـ builder.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```

### معلمات القالب

| المعلمة | الوصف |
| --- | --- |
| Parameter | نوع. |

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| startIndex | int | الموضع لإدراج الأحرف فيه. |
| value | T | القيمة لتنسيقها وإدراجها. |

### قيمة الإرجاع

هذا المؤشر.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* الفئة [StringBuilder](../)
* الفئة [String](../../../system/string/)
* النطاق [System::Text](../../)
* المكتبة [Aspose.Slides](../../../)