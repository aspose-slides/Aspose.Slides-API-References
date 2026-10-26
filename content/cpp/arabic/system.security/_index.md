---
title: "System::Security"
second_title: مرجع API لـ Aspose.Slides للـ C++
description: 
type: docs
weight: 807
url: /ar/system.security/
---
## الفئات

| الفئة | الوصف |
| --- | --- |
| [Details_SecurityException](./details_securityexception/) |  |
| [SecureString](./securestring/) | سلسلة آمنة، تمثل نصًا يجب الحفاظ على سريته. هذا الـ class لا يقوم بتشفير البيانات الداخلية. يجب إنشاء كائنات هذا الـ class فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تُنشئ مثيلًا من هذا النوع على المكدس أو باستخدام operator new، حيث سيتسبب ذلك بأخطاء وقت التشغيل أو أعطال تأكيدية. قم دائمًا بلف هذا الـ class في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [SecureStringMarshal](./securestringmarshal/) | مجموعة من الدوال لتخصيص ونسخ كتل الذاكرة غير المدارة. |
| [SecurityElement](./securityelement/) | نموذج كائن XML لتشفير كائن الأمان. غير مطبق. يجب إنشاء كائنات هذا الـ class فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تُنشئ مثيلًا من هذا النوع على المكدس أو باستخدام operator new، حيث سيتسبب ذلك بأخطاء وقت التشغيل أو أعطال تأكيدية. قم دائمًا بلف هذا الـ class في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |

## الأنواع المعرفية

| الأنواع المعرفية | الوصف |
| --- | --- |
| [SecurityException](./securityexception/) |  |
| [SecureStringPtr](./securestringptr/) | نوع مؤشر [SecureString](./securestring/). |