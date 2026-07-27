---
title: RemoveScriptFont()
second_title: Referencia de API de Aspose.Slides para C++
description: Elimina la configuración de fuente asociada con una etiqueta de script específica de la colección de fuentes del tema.
type: docs
weight: 118
url: /es/aspose.slides/ifonts/removescriptfont/
---
## IFonts::RemoveScriptFont(System::String) método


Elimina la configuración de fuente asociada con una etiqueta de script específica de la colección de fuentes del tema.

```cpp
virtual void Aspose::Slides::IFonts::RemoveScriptFont(System::String script)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | El código de script BCP-47 cuya configuración de fuente debe eliminarse. |
## Observaciones



Este ejemplo muestra cómo eliminar el mapeo de fuentes para el script hebreo: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## Ver también

* Clase [String](../../../system/string/)
* Clase [IFonts](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)