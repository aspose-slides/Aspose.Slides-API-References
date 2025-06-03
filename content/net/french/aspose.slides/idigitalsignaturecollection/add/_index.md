---
title: Add
second_title: Référence API Aspose.Slides pour .NET
description: Ajoute la signature à la fin de la collection.
type: docs
weight: 20
url: /fr/aspose.slides/idigitalsignaturecollection/add/
---

## Méthode IDigitalSignatureCollection.Add

Ajoute la signature à la fin de la collection.

```csharp
public void Add(IDigitalSignature digitalSignature)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| digitalSignature | IDigitalSignature | Signature à ajouter. |

### Exemples

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    DigitalSignature signature = new DigitalSignature("testsignature1.pfx", @"testpass1");
    signature.Comments = "Test de signature numérique Aspose.Slides.";
    pres.DigitalSignatures.Add(signature);
    pres.Save("SomePresentationSigned.pptx", SaveFormat.Pptx);
}
```

### Voir Aussi

* interface [IDigitalSignature](../../idigitalsignature)
* interface [IDigitalSignatureCollection](../../idigitalsignaturecollection)
* namespace [Aspose.Slides](../../idigitalsignaturecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: généré par xmldocmd pour Aspose.Slides.dll -->