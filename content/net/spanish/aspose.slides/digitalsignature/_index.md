---
title: DigitalSignature
second_title: Referencia de API de Aspose.Slides para .NET
description: Firma digital en archivo firmado.
type: docs
weight: 2680
url: /es/aspose.slides/digitalsignature/
---

## Clase DigitalSignature

Firma digital en archivo firmado.

```csharp
public class DigitalSignature : IDigitalSignature
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DigitalSignature](digitalsignature#constructor)(X509Certificate2) | Crea un nuevo objeto DigitalSignature con el certificado especificado. |
| [DigitalSignature](digitalsignature#constructor_1)(string, string) | Crea un nuevo objeto DigitalSignature con la ruta del archivo del certificado especificado y la contraseña. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Certificate](../../aspose.slides/digitalsignature/certificate) { get; } | Objeto de certificado que se utilizó para firmar el documento. Solo lectura X509Certificate2. |
| [Comments](../../aspose.slides/digitalsignature/comments) { get; set; } | El propósito de la firma. Lectura/escritura String. |
| [IsValid](../../aspose.slides/digitalsignature/isvalid) { get; } | Si esta firma digital es válida y el documento no ha sido alterado, este valor será verdadero. Solo lectura Boolean. |
| [SignTime](../../aspose.slides/digitalsignature/signtime) { get; } | La hora en que fue firmado el documento. Solo lectura DateTime. |

### Ejemplos

El siguiente ejemplo demuestra cómo añadir una firma digital de un certificado PFX en una Presentación de PowerPoint.

```csharp
[C#]
// Inicializar instancia de Presentación
using (Presentation pres = new Presentation())
{
    // Crear objeto DigitalSignature con archivo PFX y contraseña PFX
    DigitalSignature signature = new DigitalSignature("testsignature1.pfx", @"testpass1");
    // Comentar nueva firma digital
    signature.Comments = "Prueba de firma digital de Aspose.Slides.";
    // Añadir firma digital a la presentación
    pres.DigitalSignatures.Add(signature);
    // Guardar presentación
    pres.Save("SomePresentationSigned.pptx", SaveFormat.Pptx);
}
```

El siguiente código de muestra demuestra cómo validar la firma digital de una Presentación de PowerPoint.

```csharp
[C#]
// Inicializar instancia de Presentación
using (Presentation pres = new Presentation("SomePresentationSigned.pptx"))
{
    if (pres.DigitalSignatures.Count < 0)
    {
        bool allSignaturesAreValid = true;
        Console.WriteLine("Firmas utilizadas para firmar la presentación: ");
        // Verificar si todas las firmas digitales son válidas
        foreach (DigitalSignature signature in pres.DigitalSignatures)
        {
            Console.WriteLine(signature.Certificate.SubjectName.Name + ", "
                    + signature.SignTime.ToString("yyyy-MM-dd HH:mm") + " -- " + (signature.IsValid ? "VÁLIDA" : "INVALIDA"));
            allSignaturesAreValid &= signature.IsValid;
        }
        if (allSignaturesAreValid)
            Console.WriteLine("La presentación es genuina, todas las firmas son válidas.");
        else
            Console.WriteLine("La presentación ha sido modificada desde la firma.");
    }
}
```

### Ver También

* interface [IDigitalSignature](../idigitalsignature)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->