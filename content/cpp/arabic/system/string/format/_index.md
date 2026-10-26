---
title: Format()
second_title: مرجع API Aspose.Slides للـ C++
description: يقوم بتنسيق السلسلة على نمط C#.
type: docs
weight: 885
url: /ar/system/string/format/
---
## String::Format(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) method

يقوم بتنسيق السلسلة على نمط C#.

```cpp
template<class...> String System::String::Format(const SharedPtr<IFormatProvider> &fp, const String &format, const Args &... args)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| Args | الوسائط لتنسيق السلسلة. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مقدم التنسيق المستخدم لتحويل الوسائط إلى سلاسل. |
| format | const [String](../)\& | سلسلة التنسيق. |
| args | const Args\&... | الوسائط لتنسيق السلسلة. |

## String::Format(std::nullptr_t, const String\&, const Args\&...) method

يقوم بتنسيق السلسلة على نمط C#.

```cpp
template<class...> String System::String::Format(std::nullptr_t, const String &format, const Args &... args)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| Args | الوسائط لتنسيق السلسلة. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| format | std::nullptr_t | سلسلة التنسيق. |
| args | const [String](../)\& | الوسائط لتنسيق السلسلة. |

## String::Format(std::nullptr_t, const char16_t(&), const Args\&...) method

يقوم بتنسيق السلسلة على نمط C#.

```cpp
template<std::size_t,class...> String System::String::Format(std::nullptr_t, const char16_t(&format)[N], const Args &... args)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| Args | الوسائط لتنسيق السلسلة. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| format | std::nullptr_t | سلسلة التنسيق. |
| args | const char16_t(&) | الوسائط لتنسيق السلسلة. |

## String::Format(const String\&, const Args\&...) method

يقوم بتنسيق السلسلة على نمط C#.

```cpp
template<class...> String System::String::Format(const String &format, const Args &... args)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| Args | الوسائط لتنسيق السلسلة. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| format | const [String](../)\& | سلسلة التنسيق. |
| args | const Args\&... | الوسائط لتنسيق السلسلة. |

## String::Format(const String\&, const System::ArrayPtr\<T\>\&) method

يقوم بتنسيق السلسلة على نمط C#.

```cpp
template<class T> String System::String::Format(const String &format, const System::ArrayPtr<T> &args)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | الوسائط لتنسيق السلسلة. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| format | const [String](../)\& | سلسلة التنسيق. |
| args | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | الوسائط لتنسيق السلسلة. |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../sharedptr/)
* تعريف نوع [ArrayPtr](../../arrayptr/)
* فئة [String](../)
* فئة [IFormatProvider](../../iformatprovider/)
* مساحة أسماء [System](../../)
* مكتبة [Aspose.Slides](../../../)