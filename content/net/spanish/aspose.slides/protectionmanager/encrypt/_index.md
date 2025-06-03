---
title: Encrypt
second_title: Referencia de API de Aspose.Slides para .NET
description: Cifra la presentación con la contraseña especificada.
type: docs
weight: 80
url: /es/aspose.slides/protectionmanager/encrypt/
---

## Método ProtectionManager.Encrypt

Cifra la presentación con la contraseña especificada.

```csharp
public void Encrypt(string encryptionPassword)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encryptionPassword | String | La contraseña. |

### Ejemplos

El siguiente código de muestra muestra cómo cifrar una presentación de PowerPoint.

```csharp
[C#]
using (Presentation presentation = new Presentation("pres.pptx"))
{
    presentation.ProtectionManager.Encrypt("123123");
    presentation.Save("encrypted-pres.pptx", SaveFormat.Pptx);
}
```

### Ver También

* clase [ProtectionManager](../../protectionmanager)
* espacio de nombres [Aspose.Slides](../../protectionmanager)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->