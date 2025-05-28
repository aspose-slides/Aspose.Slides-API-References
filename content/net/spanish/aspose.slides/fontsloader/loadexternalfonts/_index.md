---
title: LoadExternalFonts
second_title: Aspose.Slides para .NET Referencia de API
description: Agrega carpetas adicionales para buscar fuentes.
type: docs
weight: 40
url: /es/aspose.slides/fontsloader/loadexternalfonts/
---

## FontsLoader.LoadExternalFonts método

Agrega carpetas adicionales para buscar fuentes.

```csharp
public static void LoadExternalFonts(string[] directories)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| directories | String[] | Directorios para leer fuentes adicionales. |

### Ejemplos

El siguiente ejemplo muestra cómo cargar fuentes personalizadas desde .TTF

```csharp
[C#]
// La ruta al directorio de documentos.
string dataDir = "C:\\";
// carpetas para buscar fuentes
String[] folders = new String[] { dataDir };
// Cargar las fuentes del directorio de fuentes personalizadas
FontsLoader.LoadExternalFonts(folders);
// Hacer algún trabajo y realizar la presentación/renderizado de diapositivas
using (Presentation presentation = new Presentation(dataDir + "DefaultFonts.pptx"))
{
    presentation.Save(dataDir + "NewFonts_out.pptx", SaveFormat.Pptx);
	// Limpiar caché de fuentes
	FontsLoader.ClearCache();
}
```

### Véase también

* clase [FontsLoader](../../fontsloader)
* espacio de nombres [Aspose.Slides](../../fontsloader)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->