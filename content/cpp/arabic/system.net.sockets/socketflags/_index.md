---
title: SocketFlags
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يوفر قيمًا ثابتة لرسائل المقبس.
type: docs
weight: 222
url: /ar/system.net.sockets/socketflags/
---
## SocketFlags عدد

يوفر قيمًا ثابتة لرسائل المقبس.

```cpp
enum class SocketFlags
```

### Values

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | 0 | لا توجد أية أعلام مستخدمة لهذا الاستدعاء. |
| OutOfBand | 1 | يتم معالجة البيانات خارج النطاق. |
| Peek | 2 | الإطلاع على رسالة واردة. |
| DontRoute | 4 | إرسال رسالة دون استخدام جداول التوجيه. |
| Truncated | 256 | الرسالة كبيرة جدًا لتناسب المخزن المؤقت المحدد. تم قطعها. |
| ControlDataTruncated | 512 | بيانات التحكم أكبر من ٦٤ كيلوبايت ولا تناسب المخزن المؤقت الداخلي. تم قطعها. |
| Broadcast | 1024 | حزمة بث. |
| Multicast | 2048 | حزمة متعدد البث. |
| Partial | 32768 | رسالة تم إرسالها أو استلامها جزئيًا. |

## انظر أيضًا

* مساحة الأسماء [System::Net::Sockets](../)
* مكتبة [Aspose.Slides](../../)