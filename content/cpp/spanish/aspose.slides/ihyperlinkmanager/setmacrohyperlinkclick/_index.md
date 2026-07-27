---
title: SetMacroHyperlinkClick()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece un hipervínculo macro al hacer clic.
type: docs
weight: 79
url: /es/aspose.slides/ihyperlinkmanager/setmacrohyperlinkclick/
---
## IHyperlinkManager::SetMacroHyperlinkClick(System::String) método

Establece un hipervínculo macro al hacer clic.

```cpp
virtual System::SharedPtr<IHyperlink> Aspose::Slides::IHyperlinkManager::SetMacroHyperlinkClick(System::String macroName)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Nombre del macro |

### Valor devuelto

[Hyperlink](../../hyperlink/) object [IHyperlink](../../ihyperlink/)
## Observaciones



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

System::SharedPtr<IAutoShape> shape = presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::BlankButton, 20.0f, 20.0f, 80.0f, 30.0f);
shape->get_HyperlinkManager()->SetMacroHyperlinkClick(u"MacroName");
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IHyperlink](../../ihyperlink/)
* Clase [String](../../../system/string/)
* Clase [IHyperlinkManager](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)