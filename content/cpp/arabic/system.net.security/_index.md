---
title: "System::Net::Security"
second_title: "Aspose.Slides لـ C++ دليل API"
description: 
type: docs
weight: 716
url: /ar/system.net.security/
---
## الفئات

| الفئة | الوصف |
| --- | --- |
| [AuthenticatedStream](./authenticatedstream/) | يحتوي على الطرق لتمرير بيانات الاعتماد عبر تدفق. يجب تخصيص كائنات هذه الفئة فقط باستخدام دالة [System::MakeObject()](../system/makeobject/). لا تنشئ مثيلاً من هذا النوع على المكدس أو باستخدام المشغّل new، لأن ذلك سيؤدي إلى أخطاء وقت التشغيل و/أو أخطاء التأكيد. دائماً غلف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [SslStream](./sslstream/) | تدفق يستخدم بروتوكول SSL للمصادقة على الخادم واختياريًا على العميل. |
## التعدادات

| التعداد | الوصف |
| --- | --- |
| [AuthenticationLevel](./authenticationlevel/) | علامات المصادقة الخاصة بـ WebRequest. |
| [SslPolicyErrors](./sslpolicyerrors/) | يسرد أخطاء السياسة الخاصة بـ SSL. |
| [EncryptionPolicy](./encryptionpolicy/) | يسرد سياسات التشفير. |
## تعريفات الأنواع

| تعريف النوع | الوصف |
| --- | --- |
| [RemoteCertificateValidationCallback](./remotecertificatevalidationcallback/) | مفوض مستخدم يستخدم للتحقق من شهادة SSL البعيدة. |
| [LocalCertificateSelectionCallback](./localcertificateselectioncallback/) | مفوض مستخدم يستخدم لاختيار شهادة SSL المحلية. |