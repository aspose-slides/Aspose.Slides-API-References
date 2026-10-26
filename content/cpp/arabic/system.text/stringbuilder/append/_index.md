---
title: Append()
second_title: Aspose.Slides لمرجع API الخاص بـ C++
description: يضيف حرفًا إلى المنشئ.
type: docs
weight: 118
url: /ar/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) طريقة

يضيف حرفًا إلى المنشئ.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| c | char_t | قيمة الحرف. |

### قيمة الإرجاع

هذا المؤشر.

## StringBuilder::Append(char_t, int) طريقة

يضيف أحرفًا إلى المنشئ.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| c | char_t | قيمة الحرف. |
| count | int | عدد مرات تكرار الحرف المُضاف. |

### قيمة الإرجاع

هذا المؤشر.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&) طريقة

يضيف مصفوفة أحرف إلى المنشئ.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | أحرف للإضافة. |

### قيمة الإرجاع

هذا المؤشر.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) طريقة

يضيف شريحة من مصفوفة الأحرف إلى المنشئ.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | أحرف للإضافة. |
| startIndex | int | فهرس بداية الشريحة. |
| charCount | int | طول الشريحة. |

### قيمة الإرجاع

هذا المؤشر.

## StringBuilder::Append(const String\&) طريقة

يضيف سلسلة نصية إلى المنشئ.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) للإضافة. |

### قيمة الإرجاع

هذا المؤشر.

## StringBuilder::Append(const String\&, int, int) طريقة

يضيف شريحة من السلسلة النصية إلى المنشئ.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) للإضافة. |
| startIndex | int | فهرس بداية الشريحة. |
| charCount | int | طول الشريحة. |

### قيمة الإرجاع

هذا المؤشر.

## StringBuilder::Append(const SharedPtr\<T\>\&) طريقة

يضيف تمثيل الكائن النصي إلى المنشئ.

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | [Object](../../../system/object/) نوع. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<T\>\& | [Object](../../../system/object/) لتسلسل وإضافتها. |

### قيمة الإرجاع

هذا المؤشر.

## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) طريقة

يضيف محتوى المنشئ إلى المنشئ.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| builder | const [SharedPtr](../../../system/sharedptr/)\<[StringBuilder](../)\>\& | المنشيء لإضافة المحتوى منه. |

### قيمة الإرجاع

هذا المؤشر.

## StringBuilder::Append(float) طريقة

يضيف قيمة نقطة عائمة إلى المنشئ.

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| f | **float** | القيمة لتسلسل وإضافتها. |

### قيمة الإرجاع

هذا المؤشر.

## StringBuilder::Append(double) طريقة

يضيف قيمة نقطة عائمة إلى المنشئ.

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| df | **double** | القيمة لتسلسل وإضافتها. |

### قيمة الإرجاع

هذا المؤشر.

## StringBuilder::Append(int) طريقة

يضيف قيمة عدد صحيح إلى المنشئ.

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| i | int | القيمة لتسلسل وإضافتها. |

### قيمة الإرجاع

هذا المؤشر.

## StringBuilder::Append(T) طريقة

يضيف قيمة حسابية إلى المنشئ.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع حسابي. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | T | القيمة لتسلسل وإضافتها. |

### قيمة الإرجاع

هذا المؤشر.

## StringBuilder::Append(E) طريقة

يضيف تمثيل قيمة تعداد إلى المنشئ.

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| E | [Enum](../../../system/enum/) نوع. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| e | E | القيمة لتسلسل وإضافتها. |

### قيمة الإرجاع

هذا المؤشر.

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [StringBuilder](../)
* فئة [String](../../../system/string/)
* نطاق [System::Text](../../)
* مكتبة [Aspose.Slides](../../../)