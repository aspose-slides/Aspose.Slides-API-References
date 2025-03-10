---
title: ILicense
second_title: Referencia de la API de Aspose.Slides para .NET
description: Proporciona métodos para licenciar el componente.
type: docs
weight: 5700
url: /es/aspose.slides/ilicense/
---
## ILicense interface

Proporciona métodos para licenciar el componente.

```csharp
public interface ILicense
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ResetLicense](../../aspose.slides/ilicense/resetlicense)() | Restablecer la licencia |
| [SetLicense](../../aspose.slides/ilicense/setlicense#setlicense)(Stream) | Licencia el componente. |
| [SetLicense](../../aspose.slides/ilicense/setlicense#setlicense_1)(string) | Licencia el componente. |

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

### Ver también

* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
