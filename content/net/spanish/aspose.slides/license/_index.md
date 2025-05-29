---
title: Licencia
second_title: Referencia de API de Aspose.Slides para .NET
description: Proporciona métodos para licenciar el componente.
type: docs
weight: 7440
url: /es/aspose.slides/license/
---

## Clase License

Proporciona métodos para licenciar el componente.

```csharp
public class License : ILicense
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [License](license)() | Inicializa una nueva instancia de esta clase. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [IsLicensed](../../aspose.slides/license/islicensed)() | Verifica si la licencia se aplica al componente |
| [ResetLicense](../../aspose.slides/license/resetlicense)() | Restablece la licencia |
| [SetLicense](../../aspose.slides/license/setlicense#setlicense)(Stream) | Licencia el componente. |
| [SetLicense](../../aspose.slides/license/setlicense#setlicense_1)(string) | Licencia el componente. |

### Ejemplos

En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic en la carpeta que contiene el componente, en la carpeta que contiene el ensamblado que llama, en la carpeta del ensamblado de entrada y luego en los recursos incrustados del ensamblado que llama.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Ver También

* interfaz [ILicense](../ilicense)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->