---
title: TryParse()
second_title: Aspose.Slides لمرجع واجهة برمجة تطبيقات C++
description: تحاول تحويل سلسلة مكوَّنة من حرف واحد إلى حرف UTF-16. تنجح الدالة فقط عندما لا تكون السلسلة المدخلة فارغة ويكون طولها حرفًا واحدًا بالضبط.
type: docs
weight: 300
url: /ar/system/char/tryparse/
---
## Char::TryParse(const System::String\&, char_t\&) طريقة

تحاول تحويل سلسلة تتكون من حرف واحد إلى حرف UTF-16. تنجح الدالة فقط عندما لا تكون السلسلة المدخلة فارغة وتكون بطول حرف واحد تمامًا.

```cpp
static bool System::Char::TryParse(const System::String &s, char_t &result)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| s | const [System::String](../../string/)\& | [String](../../string/) للتحويل |
| result | char_t\& | المتغير الناتج الذي سيحتوي على نتيجة التحويل إذا نجحت عملية التحويل |

### قيمة الإرجاع

صحيح إذا نجحت عملية التحويل، وإلا - خطأ

## انظر أيضًا

* فئة [String](../../string/)
* فئة [Char](../)
* مساحة الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)