---
title: DigitalSignatures
second_title: Référence de l'API Aspose.Slides pour .NET
description: Renvoie la collection de signatures utilisées pour signer la présentation. Lecture seule IDigitalSignatureCollectionaspose.slides/idigitalsignaturecollection.
type: docs
weight: 80
url: /fr/aspose.slides/presentation/digitalsignatures/
---

## Propriété Presentation.DigitalSignatures

Renvoie la collection de signatures utilisées pour signer la présentation. Lecture seule [`IDigitalSignatureCollection`](../../idigitalsignaturecollection).

```csharp
public IDigitalSignatureCollection DigitalSignatures { get; }
```

### Exemples

```csharp
[C#]
using (Presentation pres = new Presentation("SomePresentationSigned.pptx"))
{
    if (pres.DigitalSignatures.Count > 0)
    {
        bool allSignaturesAreValid = true;

        Console.WriteLine("Signatures utilisées pour signer la présentation : ");
        foreach (DigitalSignature signature in pres.DigitalSignatures)
        {
            Console.WriteLine(signature.Certificate.SubjectName.Name + ", "
                    + signature.SignTime.ToString("yyyy-MM-dd HH:mm") + " -- " + (signature.IsValid ? "VALIDE" : "INVALIDE"));
            allSignaturesAreValid &= signature.IsValid;
        }

        if (allSignaturesAreValid)
            Console.WriteLine("La présentation est authentique, toutes les signatures sont valides.");
        else
            Console.WriteLine("La présentation a été modifiée depuis la signature.");
    }
}
```

### Voir Aussi

* interface [`IDigitalSignatureCollection`](../../idigitalsignaturecollection)
* classe [`Presentation`](../../presentation)
* espace de noms [`Aspose.Slides`](../../presentation)
* assembly [`Aspose.Slides`](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour Aspose.Slides.dll -->