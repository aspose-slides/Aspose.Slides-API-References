---
title: GetScriptFont()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene el nombre de la fuente asociado a una etiqueta de script específica del tema de la presentación.
type: docs
weight: 92
url: /es/aspose.slides/fonts/getscriptfont/
---
## Fonts::GetScriptFont(System::String) método


Obtiene el nombre de la fuente asociado a una etiqueta de script específica del tema de la presentación.

```cpp
System::String Aspose::Slides::Fonts::GetScriptFont(System::String script) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | El código de script BCP-47 (p. ej., "Latn", "Cyrl", "Jpan") utilizado para identificar un sistema de escritura. |

### Valor devuelto

El nombre de la fuente usada para el script especificado, o **null** si el script no está definido.
## Observaciones



Este ejemplo muestra cómo obtener la fuente asignada al script cirílico en el tema de la presentación. 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## Véase también

* Clase [String](../../../system/string/)
* Clase [Fonts](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)