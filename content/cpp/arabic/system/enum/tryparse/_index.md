---
title: TryParse()
second_title: مرجع API Aspose.Slides للغة C++
description: يحاول تحويل السلسلة المحددة إلى ثابت تعداد مكافئ.
type: docs
weight: 79
url: /ar/system/enum/tryparse/
---
## Enum::TryParse(const String\&, E\&) طريقة

تحاول تحويل السلسلة المحددة إلى ثابت تعداد مكافئ.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, E &result)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) التي تُفسَّر على أنها تحتوي على اسم ثابت تعداد |
| result | E\& | معلمة الإخراج التي إذا نجحت التحويل تحتوي على نتيجة التحويل في الدالة |

### قيمة الإرجاع

True إذا نجح التحويل، وإلا - false

## Enum::TryParse(const String\&, bool, E\&) طريقة

تحاول تحويل السلسلة المحددة إلى ثابت تعداد مكافئ.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, bool ignoreCase, E &result)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) التي تُفسَّر على أنها تحتوي على اسم ثابت تعداد |
| ignoreCase | **bool** | يحدد ما إذا كان يجب تجاهل حالة الأحرف عند تفسير السلسلة |
| result | E\& | معلمة الإخراج التي إذا نجحت التحويل تحتوي على نتيجة التحويل عند إرجاع الدالة |

### قيمة الإرجاع

True إذا نجح التحويل، وإلا - false

## انظر أيضاً

* الفئة [String](../../string/)
* الهيكل [Enum](../)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)