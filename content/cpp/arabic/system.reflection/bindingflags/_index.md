---
title: BindingFlags
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد الأعضاء وأنماط البحث عن الأنواع والربط.
type: docs
weight: 157
url: /ar/system.reflection/bindingflags/
---
## BindingFlags تعداد

يحدد الأعضاء وأنماط البحث عن الأنواع والربط.

```cpp
enum class BindingFlags
```

### القيم

| Name | Value | Description |
| --- | --- | --- |
| Default | 0 | لا خيارات خاصة. |
| IgnoreCase | 1 | تجاهل حالة الأحرف في الاسم عند البحث عن العنصر. |
| DeclaredOnly | 2 | البحث فقط عن الأعضاء المعلن عنها في النوع وليس في الأنواع الأساسية. |
| Instance | 4 | البحث عبر الأعضاء الكائنية. |
| Static | 8 | البحث عبر الأعضاء الساكنة. |
| Public | 16 | البحث عبر الأعضاء العامة. |
| NonPublic | 32 | البحث عبر الأعضاء غير العامة. |
| FlattenHierarchy | 64 | البحث عبر الأعضاء الساكنة العامة والمحمية للنوع الأساسي. |
| InvokeMethod | 256 | ينفذ الطريقة. |
| CreateInstance | 512 | ينشئ نسخة من النوع المنعكس. |
| GetField | 1024 | يحصل على قيمة الحقل. |
| SetField | 2048 | يضبط قيمة الحقل. |
| GetProperty | 4096 | يحصل على قيمة الخاصية. |
| SetProperty | 8192 | يضبط قيمة الخاصية. |
| PutDispProperty | 16384 | يضع خاصية COM. |
| PutRefDispProperty | 32768 | يضع خاصية مرجعية COM. |
| ExactBinding | 65536 | يجب أن يكون ربط النوع دقيقًا، دون أي تغييرات في النوع. |
| SuppressChangeType | 131072 | غير مدعوم. |
| OptionalParamBinding | 262144 | يختار التحميل الزائد بناءً على عدد الوسائط. |
| IgnoreReturn | 16777216 | يتجاهل قيمة الإرجاع لتفاعل COM. |

## انظر أيضًا

* نطاق [System::Reflection](../)
* مكتبة [Aspose.Slides](../../)