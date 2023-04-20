---
title: AddTextFrame()
second_title: Aspose.Slides for C++ API Reference
description: Adds a new TextFrame to a shape. If shape already has TextFrame then simply changes its text.
type: docs
weight: 66
url: /cpp/aspose.slides/autoshape/addtextframe/
---
## AutoShape::AddTextFrame(System::String) method


Adds a new [TextFrame](../../textframe/) to a shape. If shape already has [TextFrame](../../textframe/) then simply changes its text.

```cpp
System::SharedPtr<ITextFrame> Aspose::Slides::AutoShape::AddTextFrame(System::String text) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Default text for a new [TextFrame](../../textframe/). |
## Remarks



The following sample code shows how to add watermark text in PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 150.0f, 50.0f);
System::SharedPtr<ITextFrame> watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
```
 The following example shows how to create Text Box on [Slide](../../slide/). 
```cpp
// Instantiates Presentation
auto pres = System::MakeObject<Presentation>();

// Gets the first slide in the presentation
auto slide = pres->get_Slides()->idx_get(0);
// Adds an AutoShape with type set as Rectangle
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
// Adds TextFrame to the Rectangle
shape->AddTextFrame(u" ");
// Accesses the text frame
auto txtFrame = shape->get_TextFrame();
// Creates the Paragraph object for text frame
auto para = txtFrame->get_Paragraphs()->idx_get(0);
// Creates a Portion object for the paragraph
auto portion = para->get_Portions()->idx_get(0);
// Sets the text
portion->set_Text(u"Aspose TextBox");
// Saves the presentation to disk
pres->Save(u"TextBox_out.pptx", SaveFormat::Pptx);
```
 The following example shows how to add column in Text Box. 
```cpp
auto presentation = System::MakeObject<Presentation>();

// Gets the first slide in the presentation
auto slide = presentation->get_Slides()->idx_get(0);
// Add an AutoShape with type set as Rectangle
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 300.0f, 300.0f);
// Add TextFrame to the Rectangle
shape->AddTextFrame(System::String(u"All these columns are limited to be within a single text container -- ") +
                    u"you can add or delete text and the new or remaining text automatically adjusts " +
                    u"itself to flow within the container. You cannot have text flow from one container " +
                    u"to other though -- we told you PowerPoint's column options for text are limited!");
// Gets the text format of TextFrame
auto format = shape->get_TextFrame()->get_TextFrameFormat();
// Specifies the number of columns in TextFrame
format->set_ColumnCount(3);
// Specifies the spacing between columns
format->set_ColumnSpacing(10);
// Saves the presentation
presentation->Save(u"ColumnCount.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITextFrame](../../itextframe/)
* Class [String](../../../system/string/)
* Class [AutoShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)