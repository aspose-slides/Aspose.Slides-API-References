---
title: Contraseña
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene o establece la contraseña. Cadena de lectura/escritura.
type: docs
weight: 120
url: /es/aspose.slides/loadoptions/password/
---

## Propiedad LoadOptions.Password

Obtiene o establece la contraseña. Cadena de lectura/escritura.

```csharp
public string Password { get; set; }
```

### Valor de la Propiedad

La contraseña.

### Ejemplos

El siguiente código de ejemplo muestra cómo abrir una presentación de PowerPoint protegida por contraseña.

```csharp
[C#]
	LoadOptions loadOptions = new LoadOptions {Password = "YOUR_PASSWORD"};
	using (Presentation presentation = new Presentation("pres.pptx", loadOptions))
	{
	  // trabajar con la presentación descifrada
	}
```

### Ver También

* clase [LoadOptions](../../loadoptions)
* espacio de nombres [Aspose.Slides](../../loadoptions)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->