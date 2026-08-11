---
title: WriteShapeEnd()
second_title: Aspose.Slides مرجع API للغة C++
description: يتم استدعاؤه قبل عرض الشكل. يتم استدعاؤه مرة واحدة لكل شكل. إذا كتبت هذه الدالة أي شيء إلى generator، سيتم الانتهاء من توليد صورة الشريحة الحالية، وسيتم إدراج جزء HTML المضاف وسيتم بدء صورة جديدة فوق السابقة.
type: docs
weight: 79
url: /ar/aspose.slides.export/embedallfontshtmlcontroller/writeshapeend/
---
## EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) طريقة

يتم الاستدعاء قبل عرض الشكل. يتم الاستدعاء مرة واحدة لكل شكل. إذا كتبت هذه الدالة أي شيء إلى generator، سيتم إنهاء توليد صورة الشريحة الحالية، سيتم إدراج جزء html المضاف وسيتم بدء صورة جديدة فوق السابقة.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | كائن الإخراج. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) التي يتم عرضها أخيراً. |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IHtmlGenerator](../../ihtmlgenerator/)
* فئة [IShape](../../../aspose.slides/ishape/)
* فئة [EmbedAllFontsHtmlController](../)
* مساحة اسم [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)