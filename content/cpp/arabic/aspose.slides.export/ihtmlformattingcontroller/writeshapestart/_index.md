---
title: WriteShapeStart()
second_title: مرجع API Aspose.Slides للغة C++
description: يتم استدعاؤه قبل تصيير الشكل. يُستدعى مرة واحدة لكل شكل. إذا قامت هذه الدالة بكتابة أي شيء إلى المولد، سيتم إنهاء توليد صورة الشريحة الحالية، وإدراج الجزء المضاف من HTML، وسيبدأ صورة جديدة فوق السابقة.
type: docs
weight: 53
url: /ar/aspose.slides.export/ihtmlformattingcontroller/writeshapestart/
---
## IHtmlFormattingController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) طريقة


يتم استدعاؤه قبل تصيير الشكل. يُستدعى مرة واحدة لكل شكل. إذا قامت هذه الدالة بكتابة أي شيء إلى المولد، سيتم إنهاء توليد صورة الشريحة الحالية، وإدراج الجزء المضاف من HTML، وسيبدأ صورة جديدة فوق السابقة.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | كائن الإخراج. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) الذي على وشك أن يتم تصييره. |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IHtmlGenerator](../../ihtmlgenerator/)
* فئة [IShape](../../../aspose.slides/ishape/)
* فئة [IHtmlFormattingController](../)
* مساحة اسم [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)