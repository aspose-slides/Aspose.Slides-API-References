---
title: FieldAttributes
second_title: مرجع API ل Aspose.Slides للغة C++
description: السمات المنعكسة للحقل.
type: docs
weight: 170
url: /ar/system.reflection/fieldattributes/
---
## FieldAttributes تعداد

السمات المنعكسة للحقل.

```cpp
enum class FieldAttributes
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| FieldAccessMask | 7 | قناع وصول العضو. استخدم هذا القناع لاسترجاع معلومات إمكانية الوصول. |
| PrivateScope | 0 | أعضاء غير قابلين للإشارة. |
| Private | 1 | أعضاء خاصة. |
| FamANDAssem | 2 | أعضاء خاصة ومحددة بنطاق التجميع. |
| Assembly | 3 | أعضاء محددة بنطاق التجميع. |
| Family | 4 | أعضاء يمكن الوصول إليها عبر النوع والأنواع الفرعية. |
| FamORAssem | 5 | أعضاء يمكن الوصول إليها عبر النوع والأنواع الفرعية والتجميع. |
| Public | 6 | أعضاء يمكن للجميع الوصول إليها. |
| Static | 16 | أعضاء ثابتة على عكس الأعضاء المتمثلة. |
| InitOnly | 32 | أعضاء ثابتة لا يمكن سوى تهيئتها ولا يمكن تغييرها. |
| Literal | 64 | أعضاء ثابتة في وقت التجميع. |
| NotSerialized | 128 | أعضاء غير مسلسلة. |
| SpecialName | 512 | حقل خاص بأحد الأسماء أدناه. |
| PinvokeImpl | 8192 | تنفيذ مُعاد توجيه التفاعل. |
| ReservedMask | 38144 | علامات محجوزة للاستخدام في وقت التشغيل فقط. |
| RTSpecialName | 1024 | يجب على وقت التشغيل فحص تشفير الاسم. |
| HasFieldMarshal | 4096 | معلومات التسلسل موجودة. |
| HasDefault | 32768 | القيمة الافتراضية موجودة. |
| HasFieldRVA | 256 | RVA موجود. |

## انظر أيضًا

* النطاق [System::Reflection](../)
* المكتبة [Aspose.Slides](../../)