---
title: RemoveScriptFont()
second_title: Referencia de la API de Aspose.Slides para C++
description: Elimina la configuración de fuente asociada a una etiqueta de script específica de la colección de fuentes del tema.
type: docs
weight: 118
url: /es/aspose.slides/fonts/removescriptfont/
---
## Fonts::RemoveScriptFont(System::String) método


Elimina la configuración de fuente asociada a una etiqueta de script específica de la colección de fuentes del tema.

```cpp
void Aspose::Slides::Fonts::RemoveScriptFont(System::String script) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | El código de script BCP-47 cuya configuración de fuente debe eliminarse. |
## Observaciones



Este ejemplo muestra cómo eliminar la asignación de fuente para el script hebreo: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## Ver también

* Clase [String](../../../system/string/)
* Clase [Fonts](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)