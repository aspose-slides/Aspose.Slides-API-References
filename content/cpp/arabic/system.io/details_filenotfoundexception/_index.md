---
title: Details_FileNotFoundException
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "الاستثناء الذي يُرمى عندما تفشل محاولة الوصول إلى ملف غير موجود على القرص. لا تقم بإنشاء كائنات من هذه الفئة يدويًا. استخدم فئة FileNotFoundException بدلاً من ذلك. لا تقم بلف كائنات فئة FileNotFoundException داخل System::SmartPtr."
type: docs
weight: 183
url: /ar/system.io/details_filenotfoundexception/
---
## Details_FileNotFoundException فئة

الاستثناء الذي يُرمى عندما تفشل محاولة الوصول إلى ملف غير موجود على القرص. لا تقم بإنشاء كائنات من هذه الفئة يدويًا. استخدم فئة FileNotFoundException بدلاً من ذلك. لا تقم بلف كائنات فئة FileNotFoundException داخل [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_FileNotFoundException : public System::Details_ExceptionWithFilename<Details_IOException>
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| virtual [String](../../system/string/) [get_FileName](../../system/details_exceptionwithfilename/get_filename/)() const | يحصل على اسم الملف الذي تسبب في حدوث هذا الاستثناء. |
| [String](../../system/string/) [get_Message](../../system/details_exceptionwithfilename/get_message/)() const override |  |
| [String](../../system/string/) [ToString](../../system/details_exceptionwithfilename/tostring/)() const override |  |

## انظر أيضًا

* فئة [Details_ExceptionWithFilename](../../system/details_exceptionwithfilename/)
* مساحة الأسماء [System::IO](../)
* مكتبة [Aspose.Slides](../../)