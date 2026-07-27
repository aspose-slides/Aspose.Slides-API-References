---
title: SetScriptFont()
second_title: Referencia de API de Aspose.Slides para C++
description: Asigna un nombre de fuente a una etiqueta de script específica, lo que define cómo se renderizará el texto de ese script en la presentación.
type: docs
weight: 105
url: /es/aspose.slides/ifonts/setscriptfont/
---
## IFonts::SetScriptFont(System::String, System::String) método


Asigna un nombre de fuente a una etiqueta de script específica, lo que define cómo se renderizará el texto de ese script en la presentación.

```cpp
virtual void Aspose::Slides::IFonts::SetScriptFont(System::String script, System::String fontName)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | El código de script BCP-47 (p. ej., \"Arab\", \"Hebr\", \"Hans\") que identifica el sistema de escritura. |
| fontName | [System::String](../../../system/string/) | El nombre de la fuente que se asignará al script especificado. |
## Observaciones



Este ejemplo muestra cómo establecer la fuente para el script árabe a \"Segoe UI\": 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## Ver también

* Clase [String](../../../system/string/)
* Clase [IFonts](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)