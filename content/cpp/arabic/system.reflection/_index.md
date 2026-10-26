---
title: "System::Reflection"
second_title: مرجع API لـ Aspose.Slides للغة C++
description: 
type: docs
weight: 755
url: /ar/system.reflection/
---
## الفئات

| الفئة | الوصف |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) فئة تصف التجميع. الدعم محدود لأن القواعد تختلف كثيرًا بين C# و C++. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../system/makeobject/) فقط. لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [AssemblyName](./assemblyname/) | يحدد اسم التجميع. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../system/makeobject/) فقط. لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | كائن أحادي لتسجيل النوع في التجميع الجاري التنفيذ. |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | نوع أساسي للكائنات الأحادية لتسجيل النوع في التجميع الجاري التنفيذ. |
| [ConstructorInfo](./constructorinfo/) | يوفر الوصول إلى بيانات تعريف المُنشئ. |
| [Details_ReflectionTypeLoadException](./details_reflectiontypeloadexception/) | يتم إلقاء استثناء ReflectionTypeLoadException بواسطة طريقة Module.GetTypes إذا فشل تحميل أي من الفئات في وحدة. لا تقم بإنشاء مثيلات هذه الفئة يدويًا. استخدم فئة ReflectionTypeLoadException بدلاً من ذلك. لا تقم بلف مثيلات فئة ReflectionTypeLoadException في [System::SmartPtr](../system/smartptr/). |
| [Details_TargetInvocationException](./details_targetinvocationexception/) | يتم إلقاء استثناء TargetInvocationException بواسطة الطرق التي تُستدعى عبر الانعكاس. لا تقم بإنشاء مثيلات هذه الفئة يدويًا. استخدم فئة TargetInvocationException بدلاً من ذلك. لا تقم بلف مثيلات فئة TargetInvocationException في [System::SmartPtr](../system/smartptr/). |
| [FieldInfo](./fieldinfo/) | يكتشف خصائص الحقل ويوفر الوصول إلى بيانات تعريف الحقل. |
| [MemberInfo](./memberinfo/) | يوفر معلومات الانعكاس عن الأعضاء. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../system/makeobject/) فقط. لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [MethodBase](./methodbase/) | معلومات أساسية عن الطريقة. يجب تخصيص كائنات هذه الفئة باستخدام الدالة [System::MakeObject()](../system/makeobject/) فقط. لا تقم بإنشاء مثال من هذا النوع على المكدس أو باستخدام العامل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. دائمًا قم بلف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [MethodInfo](./methodinfo/) | يمثل معلومات عن طريقة الفئة. |
| [PropertyInfo](./propertyinfo/) | يمثل معلومات الخاصية. |
## التعدادات

| التعداد | الوصف |
| --- | --- |
| [BindingFlags](./bindingflags/) | يعرف الأعضاء وأنماط البحث عن الأنواع والربط. |
| [FieldAttributes](./fieldattributes/) | خصائص الحقل المنعكسة. |
| [MemberTypes](./membertypes/) | يحدد كل نوع من الأعضاء. |
## تعريفات الأنواع

| نوع التعريف | الوصف |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | يتم إلقاء استثناء ReflectionTypeLoadException بواسطة طريقة Module.GetTypes إذا فشل تحميل أي من الفئات في وحدة. لا تقم بلف مثيلات فئة ReflectionTypeLoadException في [System::SmartPtr](../system/smartptr/). |
| [TargetInvocationException](./targetinvocationexception/) | يتم إلقاء استثناء TargetInvocationException بواسطة الطرق التي تُستدعى عبر الانعكاس. لا تقم بلف مثيلات فئة TargetInvocationException في [System::SmartPtr](../system/smartptr/). |