---
title: GetScriptFont()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene el nombre de la fuente asociado a una etiqueta de script específica del tema de la presentación.
type: docs
weight: 92
url: /es/aspose.slides/ifonts/getscriptfont/
---
## IFonts::GetScriptFont(System::String) método


Obtiene el nombre de la fuente asociado a una etiqueta de script específica del tema de la presentación.

```cpp
virtual System::String Aspose::Slides::IFonts::GetScriptFont(System::String script)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | El código de script BCP-47 (p. ej., \"Latn\", \"Cyrl\", \"Jpan\") usado para identificar un sistema de escritura. |

### Return Value

El nombre de la fuente utilizada para el script especificado, o **null** si el script no está definido.

## Remarks



Este ejemplo muestra cómo recuperar la fuente asignada al script Cirílico en el tema de la presentación. 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## See Also

* Clase [String](../../../system/string/)
* Clase [IFonts](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)