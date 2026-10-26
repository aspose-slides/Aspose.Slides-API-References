---
title: WriteShapeEnd()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يتم الاستدعاء قبل رسم الشكل. يتم الاستدعاء مرة واحدة لكل شكل. إذا كتبت هذه الدالة أي شيء إلى المُولد، سيتوقف توليد صورة الشريحة الحالية، وسيتم إدراج مقتطف HTML المضاف وستبدأ صورة جديدة فوق السابقة.
type: docs
weight: 66
url: /ar/aspose.slides.export/ihtmlformattingcontroller/writeshapeend/
---
## IHtmlFormattingController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) طريقة

تم الاستدعاء قبل رسم الشكل. يتم الاستدعاء مرة واحدة لكل شكل. إذا كتبت هذه الدالة أي شيء إلى المُولد، سيتوقف توليد صورة الشريحة الحالية، وسيتم إدراج مقتطف HTML المضاف وستبدأ صورة جديدة فوق السابقة.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | كائن الإخراج. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) الذي يُعرض أخيرًا. |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IHtmlGenerator](../../ihtmlgenerator/)
* Class [IShape](../../../aspose.slides/ishape/)
* Class [IHtmlFormattingController](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)