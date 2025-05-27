---
title: CheckWriteProtection
second_title: Referencia de API de Aspose.Slides para .NET
description: Verifica si una contraseña para modificar es correcta para una presentación protegida contra escritura.
type: docs
weight: 60
url: /es/aspose.slides/presentationinfo/checkwriteprotection/
---

## Método PresentationInfo.CheckWriteProtection

Verifica si una contraseña para modificar es correcta para una presentación protegida contra escritura.

```csharp
public bool CheckWriteProtection(string password)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| password | String | La contraseña a verificar. |

### Valor de Retorno

Verdadero si la presentación está protegida contra escritura y la contraseña es correcta. Falso en caso contrario.

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException |  |

### Comentarios

1. Debes verificar la propiedad [`IsWriteProtected`](../iswriteprotected) antes de llamar a este método. 2. Cuando la contraseña es nula o está vacía, este método devuelve falso.

### Ejemplos

```csharp
[C#]
IPresentationInfo info = PresentationFactory.Instance.GetPresentationInfo(presentationFilePath);
if (info.IsWriteProtected == NullableBool.True)
{
    bool isWriteProtectedByPassword = info.CheckWriteProtection("my_password");
}
```

### Véase También

* class [PresentationInfo](../../presentationinfo)
* namespace [Aspose.Slides](../../presentationinfo)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->