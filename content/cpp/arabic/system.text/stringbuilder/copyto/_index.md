---
title: CopyTo()
second_title: مرجع API لأسبوز.سلايدز للغة C++
description: ينسخ بيانات المُنشئ إلى مواضع المصفوفة الحالية.
type: docs
weight: 235
url: /ar/system.text/stringbuilder/copyto/
---
## StringBuilder::CopyTo(int, System::ArrayPtr\<char_t\> const\&, int, int) طريقة

ينسخ بيانات المُنشئ إلى مواضع المصفوفة الحالية.

```cpp
void System::Text::StringBuilder::CopyTo(int sourceIndex, System::ArrayPtr<char_t> const &destination, int destinationIndex, int count)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| sourceIndex | int | [Index](../../../system/index/) في المُنشئ للبدء النسخ منه. |
| destination | [System::ArrayPtr](../../../system/arrayptr/)\<char_t\> const\& | المصفوفة الوجهة. |
| destinationIndex | int | [Index](../../../system/index/) في مصفوفة الوجهة للبدء الإدراج عندها. |
| count | int | عدد الأحرف للنسخ. |

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [StringBuilder](../)
* نطاق [System::Text](../../)
* مكتبة [Aspose.Slides](../../../)