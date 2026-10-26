---
title: WebExceptionStatus
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتعداد رموز الحالة لفئة WebException.
type: docs
weight: 651
url: /ar/system.net/webexceptionstatus/
---
## WebExceptionStatus عدد

يقوم بتعداد رموز الحالة لفئة WebException.

```cpp
enum class WebExceptionStatus
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Success | 0 | لم تحدث أي أخطاء. |
| NameResolutionFailure | 1 | لم يتمكن خدمة حل الاسم من حل اسم المضيف. |
| ConnectFailure | 2 | لم يتمكن نقطة الخدمة البعيدة من التواصل على مستوى النقل. |
| ReceiveFailure | 3 | لم يتم استقبال استجابة كاملة من الخادم البعيد. |
| SendFailure | 4 | لم يتم إرسال طلب كامل إلى الخادم البعيد. |
| PipelineFailure | 5 | كان الطلب طلبًا متسلسلًا وتم إغلاق الاتصال قبل استلام الاستجابة. |
| RequestCanceled | 6 | تم إلغاء الطلب أو حدث خطأ غير قابل للتصنيف. |
| ProtocolError | 7 | كانت الاستجابة المستلمة من الخادم كاملة لكنها أشارت إلى خطأ على مستوى البروتوكول. |
| ConnectionClosed | 8 | تم إغلاق الاتصال قبل أوانه. |
| TrustFailure | 9 | لم يمكن التحقق من صحة شهادة الخادم. |
| SecureChannelFailure | 10 | حدث خطأ أثناء إنشاء اتصال باستخدام SSL. |
| ServerProtocolViolation | 11 | لم تكن استجابة الخادم استجابة HTTP صالحة. |
| KeepAliveFailure | 12 | تم إغلاق الاتصال لطلب يحدد رأس 'Keep-Alive' بشكل غير متوقع. |
| Pending | 13 | هناك طلب غير متزامن داخلي في انتظار. |
| Timeout | 14 | لم يتم تلقي استجابة خلال فترة المهلة للطلب. |
| ProxyNameResolutionFailure | 15 | لم يتمكن خدمة حل الاسم من حل اسم المضيف الوكيل. |
| UnknownError | 16 | حدث استثناء من نوع غير معروف. |
| MessageLengthLimitExceeded | 17 | تم تلقي رسالة تجاوزت الحد المحدد. |
| CacheEntryNotFound | 18 | لم يتم العثور على إدخال الذاكرة المؤقتة المحدد. |
| RequestProhibitedByCachePolicy | 19 | لم يسمح بسياسة الذاكرة المؤقتة لهذا الطلب. |
| RequestProhibitedByProxy | 20 | لم يسمح الوكيل بهذا الطلب. |

## انظر أيضًا

* النطاق [System::Net](../)
* المكتبة [Aspose.Slides](../../)