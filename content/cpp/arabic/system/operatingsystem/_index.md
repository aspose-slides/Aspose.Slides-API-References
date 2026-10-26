---
title: OperatingSystem
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثل نظام تشغيل معين ويوفر معلومات حوله. يجب تخصيص كائنات هذه الفئة باستخدام الدالة System::MakeObject() فقط. لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأنه سيتسبب في أخطاء وقت التشغيل و/أو أخطاء التحقق. دائمًا قم بلف هذه الفئة في مؤشر System::SmartPtr واستخدم هذا المؤشر لتمريره إلى الدوال كوسيطة."
type: docs
weight: 1171
url: /ar/system/operatingsystem/
---
## OperatingSystem فئة

يمثل نظام تشغيل معينًا ويوفر معلومات حوله. يجب تخصيص كائنات هذه الفئة باستخدام دالة [System::MakeObject()](../makeobject/) فقط. لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام المشغل new، لأنه سيتسبب في أخطاء وقت التشغيل و/أو أخطاء التحقق. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كوسيط.

```cpp
class OperatingSystem
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [PlatformID](../platformid/) [get_Platform](./get_platform/)() const | تُعيد معرف المنصة لنظام التشغيل الممثَّل بالكائن الحالي. |
| [String](../string/) [get_ServicePack](./get_servicepack/)() const | تُعيد اسم حزمة الخدمات لنظام التشغيل الممثَّل بالكائن الحالي. |
| const [Version](../version/)\& [get_Version](./get_version/)() const | تُعيد مرجعًا ثابتًا إلى كائن [Version](../version/) يمثل إصدار نظام التشغيل الممثَّل بالكائن الحالي. |
| [String](../string/) [get_VersionString](./get_versionstring/)() const | تُعيد تمثيلًا نصيًا لإصدار نظام التشغيل الممثَّل بالكائن الحالي. |
| static **bool** [IsFreeBSD](./isfreebsd/)() | تشير إلى ما إذا كان التطبيق الحالي يعمل على FreeBSD. |
| static **bool** [IsLinux](./islinux/)() | تشير إلى ما إذا كان التطبيق الحالي يعمل على Linux. |
| static **bool** [IsMacOS](./ismacos/)() | تشير إلى ما إذا كان التطبيق الحالي يعمل على MacOS. |
| static **bool** [IsOSPlatform](./isosplatform/)(const [String](../string/)\&) | تشير إلى ما إذا كان التطبيق الحالي يعمل على المنصة المحددة. |
| static **bool** [IsWindows](./iswindows/)() | تشير إلى ما إذا كان التطبيق الحالي يعمل على [Windows](../../system.windows/). |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&) | إنشاء مثال يمثل نظام تشغيل محدد بمعرّف منصة وإصدار معينين. |
|  [OperatingSystem](./operatingsystem/)([PlatformID](../platformid/), const [Version](../version/)\&, const [String](../string/)\&) | إنشاء مثال يمثل نظام تشغيل محدد بمعرّف منصة وإصدار وحزمة خدمات معينين. |
| [String](../string/) [ToString](./tostring/)() const | تُعيد تمثيلًا نصيًا لإصدار نظام التشغيل الممثَّل بالكائن الحالي. |

## انظر أيضًا

* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)