---
title: AppendFormat()
second_title: مرجع API Aspose.Slides للـ C++
description: يقوم بإلحاق سلسلة مُنسقة إلى المُنشئ.
type: docs
weight: 131
url: /ar/system.text/stringbuilder/appendformat/
---
## StringBuilder::AppendFormat(const String\&, const TArgs\&...) طريقة

يقوم بإلحاق سلسلة مُنسّقة إلى المُنشئ.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const String &format, const TArgs &... args)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TArgs | نوع المعاملات. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | سلسلة التنسيق. |
| args | const TArgs\&... | المعاملات لإدراجها في مواضع سلسلة التنسيق. |

### القيمة المرتجعة

هذا المؤشر.

## StringBuilder::AppendFormat(const SharedPtr\<IFormatProvider\>\&, const String\&, const TArgs\&...) طريقة

يقوم بإلحاق سلسلة مُنسّقة إلى المُنشئ.

```cpp
template<class...> StringBuilder * System::Text::StringBuilder::AppendFormat(const SharedPtr<IFormatProvider> &fp, const String &format, const TArgs &... args)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TArgs | نوع المعاملات. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fp | const [SharedPtr](../../../system/sharedptr/)\<[IFormatProvider](../../../system/iformatprovider/)\>\& | موفر الصيغة؛ يتم تجاهله. |
| format | const [String](../../../system/string/)\& | سلسلة التنسيق. |
| args | const TArgs\&... | المعاملات لإدراجها في مواضع سلسلة التنسيق. |

### القيمة المرتجعة

هذا المؤشر.

## راجع أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [StringBuilder](../)
* فئة [String](../../../system/string/)
* فئة [IFormatProvider](../../../system/iformatprovider/)
* نطاق [System::Text](../../)
* مكتبة [Aspose.Slides](../../../)