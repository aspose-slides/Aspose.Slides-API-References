---
title: GetLinesCount()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene el número de líneas en un párrafo.
type: docs
weight: 105
url: /es/aspose.slides/iparagraph/getlinescount/
---
## IParagraph::GetLinesCount() método

Obtiene el número de líneas en un párrafo.

```cpp
virtual int32_t Aspose::Slides::IParagraph::GetLinesCount()=0
```

### Valor de retorno

Recuento de líneas en un párrafo

## Observaciones

Ejemplo:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> sld = pres->get_Slide(0);
System::SharedPtr<IAutoShape> ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
System::SharedPtr<IParagraph> para = ashp->get_TextFrame()->get_Paragraph(0);
System::SharedPtr<IPortion> portion = para->get_Portion(0);
portion->set_Text(u"Aspose Paragraph GetLinesCount() Example");
System::Console::WriteLine(u"Lines Count = {0}", para->GetLinesCount());
```

## Ver también

* Clase [IParagraph](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)