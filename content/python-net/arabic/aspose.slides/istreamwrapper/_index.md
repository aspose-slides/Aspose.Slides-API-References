---
title: IStreamWrapper class
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/istreamwrapper/
---
## IStreamWrapper فئة

مغلف Aspose.IO.Stream لواجهة COM.

نوع IStreamWrapper يعرض الأعضاء التالية:

## الخصائص

| خاصية | الوصف |
| :- | :- |
| [`stream`](/slides/python-net/ar/aspose.slides/istreamwrapper/stream/) | يحصل على تدفق.<br/>            قراءة-فقط **io.RawIOBase**. |
| [`can_read`](/slides/python-net/ar/aspose.slides/istreamwrapper/can_read/) | يحصل على قيمة تشير إلى ما إذا كان التدفق الحالي يدعم القراءة.<br/>            قراءة-فقط **bool**. |
| [`can_seek`](/slides/python-net/ar/aspose.slides/istreamwrapper/can_seek/) | يحصل على قيمة تشير إلى ما إذا كان التدفق الحالي يدعم التنقل.<br/>            قراءة-فقط **bool**. |
| [`can_write`](/slides/python-net/ar/aspose.slides/istreamwrapper/can_write/) | يحصل على قيمة تشير إلى ما إذا كان التدفق الحالي يدعم الكتابة.<br/>            قراءة-فقط **bool**. |
| [`length`](/slides/python-net/ar/aspose.slides/istreamwrapper/length/) | يحصل على الطول بالبايتات للتدفق.<br/>            قراءة-فقط **int**. |
| [`position`](/slides/python-net/ar/aspose.slides/istreamwrapper/position/) | يحصل على الموضع داخل التدفق الحالي.<br/>            قراءة-فقط **int**. |

## الطرق

| طريقة | الوصف |
| :- | :- |
| [`close(self)`](/slides/python-net/ar/aspose.slides/istreamwrapper/close/#) | يغلق التدفق الحالي ويحرر أي موارد. |
| [`flush(self)`](/slides/python-net/ar/aspose.slides/istreamwrapper/flush/#) | يمسح جميع المخازن المؤقتة لهذا التدفق ويتسبب في كتابة أي بيانات مخزنة مؤقتًا إلى الجهاز الأساسي. |
| [`read(self, buffer, offset, count)`](/slides/python-net/ar/aspose.slides/istreamwrapper/read/#bytes-int-int) | يقرأ تسلسلًا من البايتات من التدفق الحالي ويقَدّم الموضع داخل التدفق بعدد البايتات المقروءة. |
| [`read_byte(self)`](/slides/python-net/ar/aspose.slides/istreamwrapper/read_byte/#) | يقرأ بايتًا من التدفق ويقَدّم الموضع داخل التدفق بايتًا واحدًا، أو يُعيد -1 إذا كان في نهاية التدفق. |
| [`seek(self, offset, origin)`](/slides/python-net/ar/aspose.slides/istreamwrapper/seek/#int-systemioseekorigin) | يضبط الموضع داخل التدفق الحالي |
| [`write(self, buffer, offset, count)`](/slides/python-net/ar/aspose.slides/istreamwrapper/write/#bytes-int-int) | يكتب تسلسلًا من البايتات إلى التدفق الحالي ويقَدّم الموضع الحالي داخل هذا التدفق بعدد البايتات المكتوبة. |
| [`write_byte(self, value)`](/slides/python-net/ar/aspose.slides/istreamwrapper/write_byte/#int) | يكتب بايتًا إلى الموضع الحالي في التدفق ويقَدّم الموضع داخل التدفق بايتًا واحدًا. |

### انظر أيضًا
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)