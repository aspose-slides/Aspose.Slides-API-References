---
title: SetExternalHyperlinkClick()
second_title: Referencia de la API de Aspose.Slides para C++
description: Establecer hipervínculo externo al hacer clic.
type: docs
weight: 1
url: /es/aspose.slides/hyperlinkmanager/setexternalhyperlinkclick/
---
## HyperlinkManager::SetExternalHyperlinkClick(System::String) método

Establecer hipervínculo externo al hacer clic.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetExternalHyperlinkClick(System::String url) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../../hyperlink/) URL. |

## Observaciones

El siguiente código de ejemplo muestra cómo agregar un cuadro de texto con [Hyperlink](../../hyperlink/). 
```cpp
auto pptxPresentation = System::MakeObject<Presentation>();
// Obtiene la primera diapositiva de la presentación
auto slide = pptxPresentation->get_Slides()->idx_get(0);

// Adds an AutoShape object with type set as Rectangle
auto pptxShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 150.0f, 150.0f, 50.0f);
// Accesses the ITextFrame property associated with the AutoShape
pptxShape->AddTextFrame(u"");
auto textFrame = pptxShape->get_TextFrame();
auto portion = textFrame->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);

// Adds some text to the frame
portion->set_Text(u"Aspose.Slides");

// Sets the Hyperlink for the portion text
auto hyperlinkManager = portion->get_PortionFormat()->get_HyperlinkManager();
hyperlinkManager->SetExternalHyperlinkClick(u"http://www.aspose.com");

// Saves the PPTX Presentation
pptxPresentation->Save(u"hLinkPPTX_out.pptx", SaveFormat::Pptx);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IHyperlink](../../ihyperlink/)
* Clase [String](../../../system/string/)
* Clase [HyperlinkManager](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)