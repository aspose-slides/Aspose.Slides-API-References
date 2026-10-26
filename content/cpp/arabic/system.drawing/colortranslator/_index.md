---
title: ColorTranslator
second_title: مرجع API Aspose.Slides لـ C++
description: "يقوم بتنفيذ تحويلات اللون. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم أبداً بإنشاء مثيل من هذا النوع على المكدس أو باستخدام معامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أخطاء التأكيد. احرص دائماً على تغليف هذه الفئة بمؤشر System::SmartPtr واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل."
type: docs
weight: 66
url: /ar/system.drawing/colortranslator/
---
## ColorTranslator فئة

يقوم بتنفيذ تحويلات اللون. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../../system/makeobject/) فقط. لا تقم أبداً بإنشاء مثيل من هذا النوع على المكدس أو باستخدام معامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أخطاء التأكيد. احرص دائماً على تغليف هذه الفئة بمؤشر [System::SmartPtr](../../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل.

```cpp
class ColorTranslator
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| static [Color](../color/) [FromHtml](./fromhtml/)(const [System::String](../../system/string/)\&) | يحويل تمثيل اللون HTML المحدد إلى الكائن [Color](../color/) المكافئ. |
| static [Color](../color/) [FromWin32](./fromwin32/)(int) | يحويل اللون [Windows](../../system.windows/) المحدد إلى الكائن [Color](../color/) المكافئ. |
| static [String](../../system/string/) [ToHtml](./tohtml/)(const [Color](../color/)\&) | يحويل الكائن [Color](../color/) المحدد إلى التمثيل النصي للون HTML المكافئ. |

## انظر أيضًا

* نطاق [System::Drawing](../)
* مكتبة [Aspose.Slides](../../)