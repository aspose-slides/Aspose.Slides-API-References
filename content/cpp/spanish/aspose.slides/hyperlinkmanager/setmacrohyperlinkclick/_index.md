---
title: SetMacroHyperlinkClick()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece un hipervínculo de macro al hacer clic.
type: docs
weight: 79
url: /es/aspose.slides/hyperlinkmanager/setmacrohyperlinkclick/
---
## HyperlinkManager::SetMacroHyperlinkClick(System::String) método


Establece un hipervínculo de macro al hacer clic.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetMacroHyperlinkClick(System::String macroName) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| macroName | [System::String](../../../system/string/) | Nombre de la macro |

### Valor de retorno

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
* Clase [HyperlinkManager](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)