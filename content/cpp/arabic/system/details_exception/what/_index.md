---
title: what()
second_title: Aspose.Slides لـ C++ مرجع واجهة برمجة التطبيقات
description: "تنفذ طريقة what() التي يتم استدعاؤها من قبل فئة ExceptionWrapper. على الرغم من أن هذه الفئة ليست مشتقة من std::exception، يمكن للفئات المشتقة استخدام الأعضاء protected/private لتنفيذ منطقتها. نقل تنفيذ هذه الطريقة إلى ExceptionWrapper قد يخلّ بهذا المنطق."
type: docs
weight: 105
url: /ar/system/details_exception/what/
---
## Details_Exception::what() const طريقة

تنفذ طريقة [what()](./) التي يتم استدعاؤها من قبل فئة [ExceptionWrapper](../../exceptionwrapper/). على الرغم من أن هذه الفئة ليست مشتقة من std::exception، إلا أن الفئات المشتقة يمكنها استخدام الأعضاء protected/private لتنفيذ منطقتها. نقل تنفيذ هذه الطريقة إلى [ExceptionWrapper](../../exceptionwrapper/) قد يخلّ بهذا المنطق.

```cpp
virtual const char * System::Details_Exception::what() const noexcept
```

### قيمة الإرجاع

وصف الاستثناء.

## انظر أيضًا

* فئة [Details_Exception](../)
* مساحة اسم [System](../../)
* مكتبة [Aspose.Slides](../../../)