---
title: Add
second_title: Referencia de API de Aspose.Slides para .NET
description: Agrega la firma al final de la colección.
type: docs
weight: 20
url: /es/aspose.slides/idigitalsignaturecollection/add/
---

## Método IDigitalSignatureCollection.Add

Agrega la firma al final de la colección.

```csharp
public void Add(IDigitalSignature digitalSignature)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| digitalSignature | IDigitalSignature | Firma a agregar. |

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    DigitalSignature signature = new DigitalSignature("testsignature1.pfx", @"testpass1");
    signature.Comments = "Aspose.Slides digital signing test.";
    pres.DigitalSignatures.Add(signature);
    pres.Save("SomePresentationSigned.pptx", SaveFormat.Pptx);
}
```

### Ver también

* interfaz [IDigitalSignature](../../idigitalsignature)
* interfaz [IDigitalSignatureCollection](../../idigitalsignaturecollection)
* espacio de nombres [Aspose.Slides](../../idigitalsignaturecollection)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->