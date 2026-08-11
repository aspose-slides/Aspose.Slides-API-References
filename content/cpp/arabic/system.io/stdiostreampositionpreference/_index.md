---
title: STDIOStreamPositionPreference
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يحدد أي موضع في الدفق هو المفضل باعتباره موضع القراءة والكتابة المشترك عندما يكون std::basic_iostream وتوابعه لديها مواضع قراءة وكتابة مختلفة عند إنشاء الـ wrapper."
type: docs
weight: 586
url: /ar/system.io/stdiostreampositionpreference/
---
## STDIOStreamPositionPreference enum

يحدد أي موضع في الدفق هو المفضل باعتباره موضع القراءة والكتابة المشترك عندما يكون لديك std::basic_iostream وتوابعها ذات مواضع قراءة وكتابة مختلفة عند إنشاء الـ wrapper.

```cpp
enum class STDIOStreamPositionPreference
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Zero | 0 | موضع الصفر سيُعيّن كموضع القراءة والكتابة. |
| ReadPosition | 1 | موضع gptr سيُعيّن كموضع القراءة والكتابة. |
| WritePosition | 2 | موضع pptr سيُعيّن كموضع القراءة والكتابة. |

## انظر أيضًا

* النطاق [System::IO](../)
* المكتبة [Aspose.Slides](../../)