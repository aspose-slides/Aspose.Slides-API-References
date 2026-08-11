---
title: "System::Net::Http"
second_title: Aspose.Slides للغة C++ دليل واجهة برمجة التطبيقات
description: 
type: docs
weight: 677
url: /ar/system.net.http/
---
## الفئات

| الفئة | الوصف |
| --- | --- |
| [ByteArrayContent](./bytearraycontent/) | يمثل محتوى HTTP كمصفوفة بايت. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أخطاء التأكيد. يجب دائمًا تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [Details_HttpRequestException](./details_httprequestexception/) | فئة الاستثناء الأساسية يتم رميها من قبل الفئات [HttpClient](./httpclient/) و [HttpMessageHandler](./httpmessagehandler/). لا تقم بإنشاء نسخ من هذه الفئة يدويًا. استخدم فئة HttpRequestException بدلاً منها. لا تقم أبدًا بتغليف نسخ فئة HttpRequestException في [System::SmartPtr](../system/smartptr/). |
| [HttpClient](./httpclient/) | يمثل الفئة الأساسية لعميل HTTP لإرسال الطلبات وتلقي الاستجابات. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أخطاء التأكيد. يجب دائمًا تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [HttpClientHandler](./httpclienthandler/) | يمثل معالج الرسائل الافتراضي المستخدم من قبل الفئة [HttpClient](./httpclient/). يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أخطاء التأكيد. يجب دائمًا تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [HttpContent](./httpcontent/) | يمثل محتوى كيان HTTP. يجب تخصيص [Object](../system/object/) من هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أخطاء التأكيد. يجب دائمًا تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [HttpMessageHandler](./httpmessagehandler/) | يمثل النوع الأساسي لمعالجات رسائل HTTP. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أخطاء التأكيد. يجب دائمًا تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [HttpMessageInvoker](./httpmessageinvoker/) | يسمح للتطبيقات باستدعاء طريقة Send على سلسلة معالجات HTTP. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أخطاء التأكيد. يجب دائمًا تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [HttpMethod](./httpmethod/) | يمثل طريقة HTTP. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أخطاء التأكيد. يجب دائمًا تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [HttpRequestMessage](./httprequestmessage/) | يمثل رسالة طلب HTTP. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أخطاء التأكيد. يجب دائمًا تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [HttpResponseMessage](./httpresponsemessage/) | يمثل رسالة استجابة HTTP. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أخطاء التأكيد. يجب دائمًا تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل. |
| [HttpUtilities](./httputilities/) | يحتوي على طرق المساعدة. |
| [StringContent](./stringcontent/) | يمثل محتوى HTTP كسلسلة نصية. يجب تخصيص كائنات هذه الفئة فقط باستخدام الدالة [System::MakeObject()](../system/makeobject/). لا تقم بإنشاء نسخة من هذا النوع على المكدس أو باستخدام عامل new، حيث سيؤدي ذلك إلى أخطاء وقت التشغيل أو أخطاء التأكيد. يجب دائمًا تغليف هذه الفئة في مؤشر [System::SmartPtr](../system/smartptr/) واستخدام هذا المؤشر لتمريره إلى الدوال كمعامل. |

## الدوال

| الدالة | الوصف |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |
| **bool** [operator!=](./operator_not_equal/)([System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>, [System::SharedPtr](../system/sharedptr/)\<[HttpMethod](./httpmethod/)\>) |  |

## التعدادات

| التعداد | الوصف |
| --- | --- |
| [HttpCompletionOption](./httpcompletionoption/) | يشير إلى الوقت الذي يجب فيه إكمال عملية [HttpClient](./httpclient/). |
| [HttpParseResult](./httpparseresult/) | يشير إلى نتيجة التحليل. |

## تعريفات الأنواع

| تعريف النوع | الوصف |
| --- | --- |
| [HttpRequestException](./httprequestexception/) |  |