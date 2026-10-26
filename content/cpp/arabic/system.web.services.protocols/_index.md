---
title: "System::Web::Services::Protocols"
second_title: مرجع API لـ Aspose.Slides للغة C++
description: 
type: docs
weight: 1080
url: /ar/system.web.services.protocols/
---
## الفئات

| الفئة | الوصف |
| --- | --- |
| [Details_SoapException](./details_soapexception/) | يمثل الاستثناء الذي يُرمى عندما يتم استدعاء الطريقة عبر SOAP ويحدث خطأ. لا تقم بإنشاء مثيلات من هذه الفئة يدوياً. استخدم فئة SoapException بدلاً من ذلك. لا تقم أبداً بلف مثيلات فئة SoapException داخل [System::SmartPtr](../system/smartptr/). |
| [HttpWebClientProtocol](./httpwebclientprotocol/) | تُستخدم هذه الفئة الأساسية في جميع وكلاء خدمة XML [Web](../system.web/) الذين يستخدمون HTTP. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام العامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أعطال التحقق. احWrap دائمًا هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [InvokeCompletedEventArgs](./invokecompletedeventargs/) | يمرّر مثيل هذه الفئة كمعامل إلى موزع InvokeCompletedEventHandler. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام العامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أعطال التحقق. احWrap دائمًا هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [SoapClientMessage](./soapclientmessage/) | يمثل البيانات في طلب SOAP المرسل أو استجابة SOAP المستلمة. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام العامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أعطال التحقق. احWrap دائمًا هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/) | يحدد أن جميع رسائل SOAP الممرَّرة أو المرتجعة من الطريقة تستخدم تنسيق المستند. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام العامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أعطال التحقق. احWrap دائمًا هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [SoapDocumentServiceAttribute](./soapdocumentserviceattribute/) | يعيّن الصيغة الافتراضية لطلبات واستجابات SOAP. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام العامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أعطال التحقق. احWrap دائمًا هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [SoapHeader](./soapheader/) | يمثل محتوى رأس SOAP. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام العامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أعطال التحقق. احWrap دائمًا هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [SoapHeaderAttribute](./soapheaderattribute/) | يحدد رأس SOAP الذي يمكن لطريقة خدمة XML [Web](../system.web/) أو عميل خدمة XML [Web](../system.web/) معالجته. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام العامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أعطال التحقق. احWrap دائمًا هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [SoapHeaderCollection](./soapheadercollection/) | يحتوي على مجموعة من مثيلات الفئة [SoapHeader](./soapheader/). |
| [SoapHttpClientProtocol](./soaphttpclientprotocol/) | يجب أن ترث خدمات وكيل العميل هذه الفئة عندما يُستخدم SOAP. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام العامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أعطال التحقق. احWrap دائمًا هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [SoapMessage](./soapmessage/) | يمثل رسالة SOAP. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام العامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أعطال التحقق. احWrap دائمًا هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [WebClientProtocol](./webclientprotocol/) | تُستخدم هذه الفئة الأساسية في جميع وكلاء خدمة XML [Web](../system.web/) الذين تم إنشاؤهم باستخدام ASP.NET. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء مثيل من هذا النوع على المكدس أو باستخدام العامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أعطال التحقق. احWrap دائمًا هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدم هذا المؤشر لتمريره إلى الدوال كمعامل. |

## التعدادات

| التعداد | الوصف |
| --- | --- |
| [SoapHeaderDirection](./soapheaderdirection/) | يعدّ اتجاهات رأس SOAP. |
| [SoapMessageStage](./soapmessagestage/) | يعدّ مراحل معالجة رسائل SOAP. |
| [SoapParameterStyle](./soapparameterstyle/) | يعدّ صيغ المعلمات في رسالة SOAP. |
| [SoapProtocolVersion](./soapprotocolversion/) | يعدّ إصدارات SOAP. |
| [SoapServiceRoutingStyle](./soapserviceroutingstyle/) | يعدّ خيارات كيفية توجيه رسالة SOAP إلى خدمة XML [Web](../system.web/). |

## تعريفات النوع

| تعريف النوع | الوصف |
| --- | --- |
| [SoapException](./soapexception/) |  |