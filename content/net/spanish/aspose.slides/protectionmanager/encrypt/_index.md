---
title: Encrypt
second_title: Aspose.Sildes for .NET API Reference
description: Encripta la presentación con la contraseña especificada.
type: docs
weight: 80
url: /es/aspose.slides/protectionmanager/encrypt/
---

## ProtectionManager.Encrypt method

Encripta la presentación con la contraseña especificada.

```csharp
public void Encrypt(string encryptionPassword)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| encryptionPassword | String | La contraseña. |

### Ejemplos

El siguiente código de muestra muestra cómo encriptar una presentación de PowerPoint.

```csharp
[C#]
using (Presentation presentation = new Presentation("pres.pptx"))
{
    presentation.ProtectionManager.Encrypt("123123");
    presentation.Save("encrypted-pres.pptx", SaveFormat.Pptx);
}
```

### Ver También

* class [ProtectionManager](../../protectionmanager)
* namespace [Aspose.Slides](../../protectionmanager)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->