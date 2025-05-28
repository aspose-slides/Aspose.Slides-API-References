---
title: ILicense
second_title: Aspose.Slides para .NET Referencia de API
description: Proporciona métodos para licenciar el componente.
type: docs
weight: 6060
url: /es/aspose.slides/ilicense/
---

## Interfaz ILicense

Proporciona métodos para licenciar el componente.

```csharp
public interface ILicense
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [IsLicensed](../../aspose.slides/ilicense/islicensed)() | Verifica si la licencia se aplica al componente |
| [ResetLicense](../../aspose.slides/ilicense/resetlicense)() | Restablece la licencia |
| [SetLicense](../../aspose.slides/ilicense/setlicense#setlicense)(Stream) | Licencia el componente. |
| [SetLicense](../../aspose.slides/ilicense/setlicense#setlicense_1)(string) | Licencia el componente. |

### Ejemplos

En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic en la carpeta que contiene el componente, en la carpeta que contiene el ensamblado que realiza la llamada, en la carpeta del ensamblado de entrada y luego en los recursos incrustados del ensamblado que realiza la llamada.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Véase también

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->