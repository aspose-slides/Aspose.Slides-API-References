---
title: Guardar
second_title: Referencia de la API de Aspose.Slides para .NET
description: Guarda el archivo de salida en la ruta dada.
type: docs
weight: 10
url: /es/aspose.slides.export.web/ioutputsaver/save/
---

## Método IOutputSaver.Save

Guarda el archivo de salida en la ruta dada.

```csharp
public void Save(string path, IOutputFile outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | String | Ruta para guardar el archivo. |
| outputFile | IOutputFile | Archivo de salida. |

### Ejemplos

Ejemplo de implementación de FileStream para guardar:

```csharp
[C#]
public void Save(string path, IOutputFile outputFile)
{
    using (FileStream stream = new FileStream(path, FileMode.Create))
    {
        outputFile.Write(stream);
    }
}
```

### Véase también

* interfaz [IOutputFile](../../ioutputfile)
* interfaz [IOutputSaver](../../ioutputsaver)
* espacio de nombres [Aspose.Slides.Export.Web](../../ioutputsaver)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->