---
title: RegexOptions
second_title: مرجع API لـ Aspose.Slides للـ C++
description: خيارات Regex.
type: docs
weight: 118
url: /ar/system.text.regularexpressions/regexoptions/
---
## RegexOptions تعداد

[Regex](../regex/) خيارات.

```cpp
enum class RegexOptions
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | 0 | السلوك الافتراضي. |
| Compiled | 1 | تجميع regex لتحسين الأداء. يتم ذلك دائمًا بشكل افتراضي. |
| CultureInvariant | 2 | استخدام مطابقة غير معتمدة على الثقافة. تم التجاهل. |
| ECMAScript | 4 | استخدام بنية ECMAScript. تم التجاهل. |
| ExplicitCapture | 8 | التقاط صريح فقط. تم التجاهل. |
| IgnoreCase | 16 | تجاهل حالة الأحرف عند المطابقة. |
| IgnorePatternWhitespace | 32 | تجاهل المسافات البيضاء في النمط. غير مدعوم. |
| Multiline | 64 | معالجة '^' و '$' كبداية ونهاية السطر، وليس السلسلة الكاملة. |
| RightToLeft | 128 | مطابقة من اليمين إلى اليسار. غير مدعوم. |
| Singleline | 256 | يجعل '.' يطابق أي حرف دون استثناءات (عادةً، لا يتم مطابقة أحرف السطر الجديد). |

## انظر أيضًا

* النطاق [System::Text::RegularExpressions](../)
* المكتبة [Aspose.Slides](../../)