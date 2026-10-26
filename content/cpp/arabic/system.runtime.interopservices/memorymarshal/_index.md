---
title: MemoryMarshal
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يُقدِّم تنفيذ تجسير الذاكرة. للتوافق مع الشيفرة المترجمة فقط، لأن لا يُدعَم أي شيفرة مُدارة على جانب C++. هذا نوع ثابت لا يحتوي على خدمات كائنات. يجب ألا تقوم بإنشاء أي كائنات منه بأي وسيلة.
type: docs
weight: 27
url: /ar/system.runtime.interopservices/memorymarshal/
---
## MemoryMarshal فئة

يوفر تنفيذ تجسير الذاكرة. للتوافق مع الشيفرة المترجمة فقط، حيث لا يتم دعم الشيفرة المُدارة على جانب C++. هذا نوع ثابت لا يحتوي على خدمات كائنات. يجب ألا تقوم بإنشاء أي كائنات منه بأي طريقة.

```cpp
class MemoryMarshal
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| static [Span](../../system/span/)\<**uint8_t**\> [AsBytes](./asbytes/)(const [Span](../../system/span/)\<T\>\&) | يقوم بتحويل [Span](../../system/span/) من نوع أساسي واحد T إلى [Span](../../system/span/) من البايتات. |
| static [Span](../../system/span/)\<TTo\> [Cast](./cast/)(const [Span](../../system/span/)\<TFrom\>\&) | يقوم بتحويل [Span](../../system/span/) من نوع أساسي واحد TFrom إلى نوع أساسي آخر TTo. |

## انظر أيضاً

* النطاق [System::Runtime::InteropServices](../)
* المكتبة [Aspose.Slides](../../)