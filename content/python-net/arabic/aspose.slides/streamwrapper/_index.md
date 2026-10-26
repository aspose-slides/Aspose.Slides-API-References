---
title: StreamWrapper class
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/streamwrapper/
---
## فئة StreamWrapper

Aspose.IO.Stream wrapper لواجهة COM.

نوع StreamWrapper يعرض الأعضاء التالية:

## الخصائص

| خاصية | الوصف |
| :- | :- |
| [`stream`](/slides/python-net/ar/aspose.slides/streamwrapper/stream/) | يحصل على تدفق.<br/>            للقراءة فقط **io.RawIOBase**. |
| [`can_read`](/slides/python-net/ar/aspose.slides/streamwrapper/can_read/) | يحصل على قيمة تشير إلى ما إذا كان التدفق الحالي يدعم القراءة.<br/>            للقراءة فقط **bool**. |
| [`can_seek`](/slides/python-net/ar/aspose.slides/streamwrapper/can_seek/) | يحصل على قيمة تشير إلى ما إذا كان التدفق الحالي يدعم الانتقال.<br/>            للقراءة فقط **bool**. |
| [`can_write`](/slides/python-net/ar/aspose.slides/streamwrapper/can_write/) | يحصل على قيمة تشير إلى ما إذا كان التدفق الحالي يدعم الكتابة.<br/>            للقراءة فقط **bool**. |
| [`length`](/slides/python-net/ar/aspose.slides/streamwrapper/length/) | يحصل على طول التدفق بالبايت.<br/>            للقراءة فقط **int**. |
| [`position`](/slides/python-net/ar/aspose.slides/streamwrapper/position/) | يحصل أو يعيّن الموضع داخل التدفق الحالي.<br/>            للقراءة فقط **int**. |

## الطرق

| طريقة | الوصف |
| :- | :- |
| [`close(self)`](/slides/python-net/ar/aspose.slides/streamwrapper/close/#) | يغلق التدفق الحالي ويحرّر أي موارد. |
| [`flush(self)`](/slides/python-net/ar/aspose.slides/streamwrapper/flush/#) | يمسح جميع المخازن المؤقتة لهذا التدفق ويتسبب في كتابة أي بيانات مخزّنة إلى الجهاز الأساسي. |
| [`read(self, buffer, offset, count)`](/slides/python-net/ar/aspose.slides/streamwrapper/read/#bytes-int-int) | يقرأ تسلسلًا من البايتات من التدفق الحالي ويقدّم الموضع داخل التدفق بعدد البايتات المقروءة. |
| [`read_byte(self)`](/slides/python-net/ar/aspose.slides/streamwrapper/read_byte/#) | يقرأ بايتًا من التدفق ويقدّم الموضع داخل التدفق بايتًا واحدًا، أو يُرجع -1 إذا كان عند نهاية التدفق. |
| [`seek(self, offset, origin)`](/slides/python-net/ar/aspose.slides/streamwrapper/seek/#int-systemioseekorigin) | يعيّن الموضع داخل التدفق الحالي |
| [`write(self, buffer, offset, count)`](/slides/python-net/ar/aspose.slides/streamwrapper/write/#bytes-int-int) | يكتب تسلسلًا من البايتات إلى التدفق الحالي ويقدّم الموضع الحالي داخل هذا التدفق بعدد البايتات المكتوبة. |
| [`write_byte(self, value)`](/slides/python-net/ar/aspose.slides/streamwrapper/write_byte/#int) | يكتب بايتًا إلى الموضع الحالي في التدفق ويقدّم الموضع داخل التدفق بايتًا واحدًا. |

### راجع أيضًا
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)