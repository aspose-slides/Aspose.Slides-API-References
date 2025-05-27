---
title: CheckPassword
second_title: Aspose.Sildes para .NET Referencia de API
description: Verifica si una contraseña es correcta para una presentación protegida con contraseña abierta.
type: docs
weight: 50
url: /es/aspose.slides/ipresentationinfo/checkpassword/
---

## Método IPresentationInfo.CheckPassword

Verifica si una contraseña es correcta para una presentación protegida con contraseña abierta.

```csharp
public bool CheckPassword(string password)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| password | String | La contraseña a verificar. |

### Valor de Retorno

True si la presentación está protegida con contraseña abierta y la contraseña es correcta y false en caso contrario.

### Observaciones

Cuando la contraseña es nula o está vacía, este método devuelve false.

### Ejemplos

```csharp
[C#]
IPresentationInfo info = PresentationFactory.Instance.GetPresentationInfo("pres.pptx");
bool isPasswordCorrect = info.CheckPassword("my_password");
```

### Ver También

* interface [IPresentationInfo](../../ipresentationinfo)
* namespace [Aspose.Slides](../../ipresentationinfo)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->