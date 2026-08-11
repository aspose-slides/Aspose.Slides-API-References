---
title: WriteShapeStart()
second_title: Aspose.Slides للغة C++ مرجع API
description: يتم استدعاؤه قبل عرض الشكل. يُستدعى مرة واحدة لكل شكل. إذا كتبت هذه الدالة أي شيء إلى generator، سيتم إنهاء إنشاء صورة الشريحة الحالية، وإدراج مقطع HTML المضاف، وستبدأ صورة جديدة فوق السابقة.
type: docs
weight: 66
url: /ar/aspose.slides.export/embedallfontshtmlcontroller/writeshapestart/
---
## EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) طريقة

يتم استدعاؤه قبل عرض الشكل. يتم استدعاؤه مرة واحدة لكل شكل. إذا كتبت هذه الدالة أي شيء إلى generator، سيتم إنهاء إنشاء صورة الشريحة الحالية، وإدراج مقطع html المضاف، وستبدأ صورة جديدة فوق السابقة.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | كائن الإخراج. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) الذي على وشك العرض. |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IHtmlGenerator](../../ihtmlgenerator/)
* فئة [IShape](../../../aspose.slides/ishape/)
* فئة [EmbedAllFontsHtmlController](../)
* مساحة اسم [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)