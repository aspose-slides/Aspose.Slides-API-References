---
title: AddTextFrame()
second_title: Referencia de la API de Aspose.Slides para C++
description: Agrega un nuevo TextFrame a una forma. Si la forma ya tiene TextFrame, simplemente cambia su texto.
type: docs
weight: 66
url: /es/aspose.slides/autoshape/addtextframe/
---
## AutoShape::AddTextFrame(System::String) método

Agrega un nuevo [TextFrame](../../textframe/) a una forma. Si la forma ya tiene [TextFrame](../../textframe/) entonces simplemente cambia su texto.

```cpp
System::SharedPtr<ITextFrame> Aspose::Slides::AutoShape::AddTextFrame(System::String text) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Texto predeterminado para un nuevo [TextFrame](../../textframe/). |
## Observaciones

El siguiente código de ejemplo muestra cómo agregar texto de marca de agua en PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 150.0f, 50.0f);
System::SharedPtr<ITextFrame> watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
```
 El siguiente ejemplo muestra cómo crear un cuadro de texto en [Slide](../../slide/). 
```cpp
// Instancia Presentation
// Obtiene la primera diapositiva de la presentación
// Agrega un AutoShape con el tipo establecido como Rectangle
// Agrega TextFrame al Rectangle
// Accede al marco de texto
// Crea el objeto Paragraph para el marco de texto
// Crea un objeto Portion para el párrafo
// Establece el texto
// Guarda la presentación en disco
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
shape->AddTextFrame(u" ");
auto txtFrame = shape->get_TextFrame();
auto para = txtFrame->get_Paragraphs()->idx_get(0);
auto portion = para->get_Portions()->idx_get(0);
portion->set_Text(u"Aspose TextBox");
pres->Save(u"TextBox_out.pptx", SaveFormat::Pptx);
```
 El siguiente ejemplo muestra cómo agregar una columna en el cuadro de texto. 
```cpp
auto presentation = System::MakeObject<Presentation>();

// Obtiene la primera diapositiva de la presentación
auto slide = presentation->get_Slides()->idx_get(0);
// Agrega un AutoShape con el tipo establecido como Rectangle
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 300.0f, 300.0f);
// Agrega TextFrame al Rectangle
shape->AddTextFrame(System::String(u"All these columns are limited to be within a single text container -- ") +
                    u"you can add or delete text and the new or remaining text automatically adjusts " +
                    u"itself to flow within the container. You cannot have text flow from one container " +
                    u"to other though -- we told you PowerPoint's column options for text are limited!");
// Obtiene el formato de texto del TextFrame
auto format = shape->get_TextFrame()->get_TextFrameFormat();
// Especifica el número de columnas en el TextFrame
format->set_ColumnCount(3);
// Especifica el espaciado entre columnas
format->set_ColumnSpacing(10);
// Guarda la presentación
presentation->Save(u"ColumnCount.pptx", SaveFormat::Pptx);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ITextFrame](../../itextframe/)
* Clase [String](../../../system/string/)
* Clase [AutoShape](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)