---
title: SetLicense
second_title: Referencia de API de Aspose.Slides para .NET
description: Licencia el componente.
type: docs
weight: 40
url: /es/aspose.slides/license/setlicense/
---

## SetLicense(string) {#setlicense_1}

Licencia el componente.

```csharp
public void SetLicense(string licenseName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| licenseName | String | Puede ser un nombre de archivo completo o corto o el nombre de un recurso incrustado. Use una cadena vacía para cambiar al modo de evaluación. |

### Observaciones

Intenta encontrar la licencia en las siguientes ubicaciones:

1. Ruta explícita.

2. La carpeta del ensamblaje del componente.

3. La carpeta del ensamblaje que llama al cliente.

4. La carpeta del ensamblaje de entrada.

5. Un recurso incrustado en el ensamblaje que llama al cliente.

**Nota:** En el .NET Compact Framework, intenta encontrar la licencia solo en estas ubicaciones:

1. Ruta explícita.

2. Un recurso incrustado en el ensamblaje que llama al cliente.

### Ejemplos

En este ejemplo, se intentará encontrar un archivo de licencia llamado MyLicense.lic en la carpeta que contiene el componente, en la carpeta que contiene el ensamblaje que llama, en la carpeta del ensamblaje de entrada y luego en los recursos incrustados del ensamblaje que llama.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

### Ver También

* clase [License](../../license)
* espacio de nombres [Aspose.Slides](../../license)
* ensamblado [Aspose.Slides](../../../)

---

## SetLicense(Stream) {#setlicense}

Licencia el componente.

```csharp
public void SetLicense(Stream stream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Un flujo que contiene la licencia. |

### Observaciones

Use este método para cargar una licencia desde un flujo.

### Ejemplos

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### Ver También

* clase [License](../../license)
* espacio de nombres [Aspose.Slides](../../license)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->