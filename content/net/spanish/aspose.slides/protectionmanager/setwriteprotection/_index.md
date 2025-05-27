---
title: SetWriteProtection
second_title: Referencia de API de Aspose.Slides para .NET
description: Establecer protección contra escritura para esta presentación con la contraseña especificada.
type: docs
weight: 110
url: /es/aspose.slides/protectionmanager/setwriteprotection/
---

## Método ProtectionManager.SetWriteProtection

Establecer protección contra escritura para esta presentación con la contraseña especificada.

```csharp
public void SetWriteProtection(string password)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| password | String | La contraseña. |

### Ejemplos

El siguiente código de muestra muestra cómo establecer una protección contra escritura en una presentación.

```csharp
[C#]
using (Presentation presentation = new Presentation("pres.pptx"))
{
    presentation.ProtectionManager.SetWriteProtection("123123");
    presentation.Save("write-protected-pres.pptx", SaveFormat.Pptx);
}
```

### Véase también

* clase [ProtectionManager](../../protectionmanager)
* espacio de nombres [Aspose.Slides](../../protectionmanager)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->