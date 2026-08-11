---
title: AddTextFrame()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بإضافة TextFrame جديد إلى شكل. إذا كان الشكل يحتوي بالفعل على TextFrame فهو يغيّر نصه ببساطة.
type: docs
weight: 66
url: /ar/aspose.slides/autoshape/addtextframe/
---
## AutoShape::AddTextFrame(System::String) طريقة

يضيف [TextFrame](../../textframe/) جديدًا إلى الشكل. إذا كان الشكل يحتوي بالفعل على [TextFrame](../../textframe/) فسيتم تعديل نصه ببساطة.

```cpp
System::SharedPtr<ITextFrame> Aspose::Slides::AutoShape::AddTextFrame(System::String text) override
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | النص الافتراضي لـ [TextFrame](../../textframe/) الجديد. |
## ملاحظات

يعرض رمز العينة التالي كيفية إضافة نص علامة مائية في PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 150.0f, 50.0f);
System::SharedPtr<ITextFrame> watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
```
 يظهر المثال التالي كيفية إنشاء مربع نص على [Slide](../../slide/). 
```cpp
// ينشئ كائن Presentation
auto pres = System::MakeObject<Presentation>();

// يحصل على الشريحة الأولى في العرض التقديمي
auto slide = pres->get_Slides()->idx_get(0);
// يضيف AutoShape مع تعيين النوع كـ Rectangle
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
// يضيف TextFrame إلى المستطيل
shape->AddTextFrame(u" ");
// يصل إلى إطار النص
auto txtFrame = shape->get_TextFrame();
// ينشئ كائن Paragraph لإطار النص
auto para = txtFrame->get_Paragraphs()->idx_get(0);
// ينشئ كائن Portion للفقرة
auto portion = para->get_Portions()->idx_get(0);
// يحدد النص
portion->set_Text(u"Aspose TextBox");
// يحفظ العرض التقديمي إلى القرص
pres->Save(u"TextBox_out.pptx", SaveFormat::Pptx);
```
 يظهر المثال التالي كيفية إضافة عمود في مربع النص. 
```cpp
auto presentation = System::MakeObject<Presentation>();

// يحصل على الشريحة الأولى في العرض التقديمي
auto slide = presentation->get_Slides()->idx_get(0);
// يضيف AutoShape مع تعيين النوع كـ Rectangle
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 300.0f, 300.0f);
// يضيف TextFrame إلى المستطيل
shape->AddTextFrame(System::String(u"All these columns are limited to be within a single text container -- ") +
                    u"you can add or delete text and the new or remaining text automatically adjusts " +
                    u"itself to flow within the container. You cannot have text flow from one container " +
                    u"to other though -- we told you PowerPoint's column options for text are limited!");
// يحصل على تنسيق النص في TextFrame
auto format = shape->get_TextFrame()->get_TextFrameFormat();
// يحدد عدد الأعمدة في TextFrame
format->set_ColumnCount(3);
// يحدد المسافة بين الأعمدة
format->set_ColumnSpacing(10);
// يحفظ العرض التقديمي
presentation->Save(u"ColumnCount.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITextFrame](../../itextframe/)
* Class [String](../../../system/string/)
* Class [AutoShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)