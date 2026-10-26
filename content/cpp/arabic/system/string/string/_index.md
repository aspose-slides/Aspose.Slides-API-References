---
title: String()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: المنشئ الافتراضي. يُنشئ كائن سلسلة يُعتبر null.
type: docs
weight: 14
url: /ar/system/string/string/
---
## String::String() المنشئ


المنشئ الافتراضي. يُنشئ كائن سلسلة يُعتبر فارغًا.

```cpp
System::String::String()
```

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) المنشئ


ينشئ سلسلة بناءً على ثابت حرفي. يعتبر الثابت سلسلة منتهية بـ null، ويحسب طول السلسلة المستهدفة بناءً على حجم الثابت.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```


### الوسائط

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | T\& | [String](../) مؤشر حرفي. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) المنشئ


ينشئ سلسلة بناءً على مؤشر سلسلة حرفية. يعامل السلسلة المشار إليها كمنتهية بـ null، ويحسب طول السلسلة المستهدفة بناءً على حرف null.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```


### الوسائط

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | const T\& | مؤشر سلسلة حروف. |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) المنشئ


ينشئ سلسلة بناءً على ثابت حرفي. يعتبر الثابت سلسلة منتهية بـ null بتشفير UTF8، ويحسب طول السلسلة المستهدفة بناءً على حجم الثابت.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```


### الوسائط

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | T\& | [String](../) مؤشر حرفي. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) المنشئ


ينشئ سلسلة بناءً على مؤشر سلسلة حرفية. يعامل السلسلة المشار إليها كمنتهية بـ null بتشفير UTF8، ويحسب طول السلسلة المستهدفة بناءً على حرف null.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```


### الوسائط

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | const T\& | مؤشر سلسلة حروف. |

## String::String(const char16_t *, int) المنشئ


ينشئ سلسلة من مؤشر سلسلة حرفية وطول صريح.

```cpp
System::String::String(const char16_t *str, int length)
```


### الوسائط

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| str | const char16_t * | [String](../) مؤشر، قد يكون ثابتًا أو مصفوفة. |
| length | int | طول السلسلة الصريح |

## String::String(const ReadOnlySpan\<char16_t\>\&) المنشئ


يُهيئ نسخة جديدة من الفئة [System.String](../) إلى الحروف Unicode المحددة في المدى للقراءة فقط المحدد.

```cpp
System::String::String(const ReadOnlySpan<char16_t> &value)
```


### الوسائط

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | const [ReadOnlySpan](../../readonlyspan/)\<char16_t\>\& | مدى قراءة فقط لحروف Unicode. |

## String::String(const char *, int) المنشئ


ينشئ سلسلة من مؤشر سلسلة حرفية وطول صريح.

```cpp
System::String::String(const char *str, int length)
```


### الوسائط

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| str | const char * | [String](../) مؤشر إلى بيانات UTF8، قد يكون ثابتًا أو مصفوفة. |
| length | int | طول السلسلة الصريح |

## String::String(const char16_t *, int, int) المنشئ


ينشئ سلسلة من مؤشر سلسلة حرفية بدءًا من موضع محدد باستخدام الطول.

```cpp
System::String::String(const char16_t *str, int start, int length)
```


### الوسائط

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| str | const char16_t * | [String](../) مؤشر، قد يكون ثابتًا أو مصفوفة. |
| start | int | الموضع البديئي. |
| length | int | [String](../) الطول. |

## String::String(const char16_t, int) المنشئ


منشئ التعبئة.

```cpp
System::String::String(const char16_t ch, int count)
```


### الوسائط

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| ch | const char16_t | حرف التعبئة. |
| count | int | الطول المستهدف. |

## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) المنشئ


منشئ nullptr. تم الإعلان عنه كقالب لحل الأولويات مع منشئات القالب الأخرى.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | يجب أن يكون nullptr_t |

### الوسائط

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | const T\& | nullptr |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) المنشئ


ينشئ سلسلة بناءً على ثابت سلسلة عريضة. يعتبر الثابت سلسلة منتهية بـ null، ويحسب طول السلسلة المستهدفة بناءً على حجم الثابت. التحويل من **wchar_t** يستغرق وقتًا على بعض المنصات، لذا لا يُسمح بالتحويلات الضمنية.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```


### الوسائط

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | T\& | [String](../) مؤشر ثابت. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) المنشئ


ينشئ سلسلة بناءً على مؤشر سلسلة عريضة. يعامل السلسلة المشار إليها كمنتهية بـ null، ويحسب طول السلسلة المستهدفة بناءً على حرف null. التحويل من **wchar_t** يستغرق وقتًا على بعض المنصات، لذا لا يُسمح بالتحويلات الضمنية.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```


### الوسائط

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | const T\& | مؤشر سلسلة حروف. |

## String::String(const wchar_t *, int) المنشئ


ينشئ سلسلة من مؤشر سلسلة عريضة وطول صريح. التحويل من **wchar_t** يستغرق وقتًا على بعض المنصات، لذا لا يُسمح بالتحويلات الضمنية.

```cpp
System::String::String(const wchar_t *str, int length)
```


### الوسائط

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| str | const **wchar_t** * | [String](../) مؤشر، قد يكون ثابتًا أو مصفوفة. |
| length | int | طول السلسلة الصريح |

## String::String(const wchar_t, int) المنشئ


منشئ التعبئة. التحويل من **wchar_t** يستغرق وقتًا على بعض المنصات، لذا لا يُسمح بالتحويلات الضمنية.

```cpp
System::String::String(const wchar_t ch, int count=1)
```


### الوسائط

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| ch | const **wchar_t** | حرف التعبئة. |
| count | int | الطول المستهدف. |

## String::String(const String\&) المنشئ


منشئ النسخ.

```cpp
System::String::String(const String &str)
```


### الوسائط

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) للنسخ. |

## String::String(String\&&) المنشئ


منشئ النقل.

```cpp
System::String::String(String &&str) noexcept
```


### الوسائط

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| str | [String](../)\&& | [String](../) لنقل البيانات منه. |

## String::String(const ArrayPtr\<char16_t\>\&) المنشئ


يحوّل مصفوفة الحروف بالكامل إلى سلسلة.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```


### الوسائط

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | [Array](../../array/) للتحويل إلى سلسلة. |

## String::String(const ArrayPtr\<char16_t\>\&, int, int) المنشئ


يحوّل نطاقًا فرعيًا من مصفوفة الحروف إلى سلسلة. إذا كانت المعلمات خارج حدود المصفوفة، تُنشأ سلسلة فارغة.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```


### الوسائط

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | مصفوفة الحروف. |
| offset | int | فهرس بداية النطاق الفرعي. |
| len | int | طول النطاق الفرعي. |

## String::String(const codeporting_icu::UnicodeString\&) المنشئ


يغلف UnicodeString داخل [String](../).

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```


### الوسائط

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString لتغليفه داخل [String](../). |

## String::String(codeporting_icu::UnicodeString\&&) المنشئ


منشئ النقل.

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```


### الوسائط

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString لتغليفه داخل [String](../). |

## String::String(const std::wstring\&) المنشئ


ينشئ [String](../) من سلسلة عريضة.

```cpp
System::String::String(const std::wstring &str)
```


### الوسائط

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| str | const std::wstring\& | سلسلة عريضة للتحويل إلى [String](../). |

## String::String(const std::u16string\&) المنشئ


ينشئ [String](../) من سلسلة utf16.

```cpp
System::String::String(const std::u16string &str)
```


### الوسائط

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| str | const std::u16string\& | سلسلة Utf16 للتحويل إلى [String](../). |

## String::String(const std::string\&) المنشئ


ينشئ [String](../) من سلسلة std::string بتنسيق UTF-8.

```cpp
System::String::String(const std::string &utf8str)
```


### الوسائط

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| utf8str | const std::string\& | سلسلة std::string للتحويل إلى [String](../). |

## String::String(const std::u32string\&) المنشئ


ينشئ [String](../) من سلسلة std::u32string.

```cpp
System::String::String(const std::u32string &u32str)
```


### الوسائط

| الوسيط | النوع | الوصف |
| --- | --- | --- |
| u32str | const std::u32string\& | سلسلة std::u32string للتحويل إلى [String](../). |

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../arrayptr/)
* فئة [String](../)
* فئة [ReadOnlySpan](../../readonlyspan/)
* بنية [IsStringLiteral](../../isstringliteral/)
* بنية [IsStringPointer](../../isstringpointer/)
* مساحة الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)