---
title: RootDirectoryClsid
second_title: Aspose.Slides para .NET API Reference
description: Representa el GUID CLSID de la clase de objeto que se almacena en la entrada del directorio raíz. Puede usarse para la activación COM de la aplicación del documento. El valor predeterminado es 64818D11-4F9B-11CF-86EA-00AA00B929E8, que corresponde a Microsoft Powerpoint.Slide.8.
type: docs
weight: 20
url: /es/aspose.slides.export/pptoptions/rootdirectoryclsid/
---

## Propiedad PptOptions.RootDirectoryClsid

Representa el GUID de clase de objeto (CLSID) que se almacena en la entrada del directorio raíz. Puede usarse para la activación COM de la aplicación del documento. El valor predeterminado es '64818D11-4F9B-11CF-86EA-00AA00B929E8', que corresponde a 'Microsoft Powerpoint.Slide.8'.

```csharp
public Guid RootDirectoryClsid { get; set; }
```

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    PptOptions pptOptions = new PptOptions();
    
    /// establecer CLSID en 'Microsoft Powerpoint.Show.8'
    pptOptions.RootDirectoryClsid = new Guid("64818D10-4F9B-11CF-86EA-00AA00B929E8");
    
    pres.Save("pres.ppt", SaveFormat.Ppt, pptOptions);
}
```

### Ver También

* clase [PptOptions](../../pptoptions)
* espacio de nombres [Aspose.Slides.Export](../../pptoptions)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->