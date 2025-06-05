---
title: CheckPassword
second_title: Aspose.Sildes para .NET Referencia de la API
description: Verifica si una contraseña es correcta para una presentación protegida con contraseña abierta.
type: docs
weight: 50
url: /es/aspose.slides/presentationinfo/checkpassword/
---

## PresentationInfo.CheckPassword método

Verifica si una contraseña es correcta para una presentación protegida con contraseña abierta.

```csharp
public bool CheckPassword(string password)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| password | String | La contraseña a verificar. |

### Valor de Retorno

True si la presentación está protegida con contraseña abierta y la contraseña es correcta, y false en caso contrario.

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException |  |
| NotSupportedException |  |

### Observaciones

Cuando la contraseña es nula o está vacía, este método devuelve false.

### Ejemplos

```csharp
[C#]
IPresentationInfo info = PresentationFactory.Instance.GetPresentationInfo(presentationFilePath);
bool isPasswordCorrect = info.CheckPassword("my_password");
```

### Véase También

* clase [PresentationInfo](../../presentationinfo)
* espacio de nombres [Aspose.Slides](../../presentationinfo)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->