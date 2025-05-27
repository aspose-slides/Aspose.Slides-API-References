---
title: InsertClone
second_title: Référence de l'API Aspose.Sildes pour .NET
description: Insère une copie d'une diapositive spécifiée à la position spécifiée de la collection.
type: docs
weight: 120
url: /fr/aspose.slides/slidecollection/insertclone/
---

## InsertClone(int, ISlide) {#insertclone}

Insère une copie d'une diapositive spécifiée à la position spécifiée de la collection.

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | Index de la nouvelle diapositive. |
| sourceSlide | ISlide | Diapositive à cloner. |

### Valeur de retour

Diapositive insérée.

### Remarques

Lors du clonage d'une diapositive entre différentes présentations, le master de la diapositive peut également être cloné. Un registre interne est utilisé pour suivre automatiquement les masters clonés afin d'éviter la création de plusieurs clones de la même diapositive maître. Le clonage manuel de diapositives maîtres ne sera ni empêché ni enregistré. Si vous avez besoin de plus de contrôle sur le processus de clonage, utilisez [`InsertClone`](../insertclone) ou [`InsertClone`](../insertclone) pour cloner des diapositives et [`AddClone`](../../imasterslidecollection/addclone) pour cloner des masters.

### Exemples

L'exemple suivant montre comment cloner à une autre position dans la Présentation.

```csharp
[C#]
// Instancier la classe Presentation qui représente un fichier de présentation
using (Presentation pres = new Presentation("CloneWithInSamePresentation.pptx"))
{
    // Cloner la diapositive souhaitée à la fin de la collection de diapositives dans la même présentation
    ISlideCollection slds = pres.Slides;
    // Cloner la diapositive souhaitée à l'index spécifié dans la même présentation
    slds.InsertClone(2, pres.Slides[1]);
    // Écrire la présentation modifiée sur disque
    pres.Save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
}
```

L'exemple suivant montre comment cloner à une autre position dans la Présentation.

```csharp
[C#]
// Instancier la classe Presentation pour charger le fichier de présentation source
using (Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx"))
{
    // Instancier la classe Presentation pour le PPTX de destination (où la diapositive doit être clonée)
    using (Presentation destPres = new Presentation())
    {
        ISlideCollection slds = destPres.Slides;
        slds.InsertClone(2, srcPres.Slides[0]);
        // Écrire la présentation de destination sur disque
        destPres.Save("Aspose2_out.pptx", SaveFormat.Pptx);
    }
}
```

### Voir Aussi

* interface [ISlide](../../islide)
* classe [SlideCollection](../../slidecollection)
* espace de noms [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertClone(int, ISlide, ILayoutSlide) {#insertclone_1}

Insère une copie d'une diapositive spécifiée à la position spécifiée de la collection.

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | Index de la nouvelle diapositive. |
| sourceSlide | ISlide | Diapositive à cloner. |
| destLayout | ILayoutSlide | Diapositive de mise en page pour une nouvelle diapositive. |

### Valeur de retour

Diapositive insérée.

### Voir Aussi

* interface [ISlide](../../islide)
* interface [ILayoutSlide](../../ilayoutslide)
* classe [SlideCollection](../../slidecollection)
* espace de noms [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertClone(int, ISlide, IMasterSlide, bool) {#insertclone_2}

Insère une copie d'une diapositive source spécifiée à la position spécifiée de la collection. La mise en page appropriée sera sélectionnée automatiquement à partir du master spécifié (la mise en page appropriée est celle ayant le même Type ou Nom que la mise en page de la diapositive source). S'il n'y a pas de mise en page appropriée, la mise en page de la diapositive source sera clonée (si allowCloneMissingLayout est vrai) ou une PptxEditException sera levée (si allowCloneMissingLayout est faux).

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, 
    bool allowCloneMissingLayout)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | Index de la nouvelle diapositive. |
| sourceSlide | ISlide | Diapositive à cloner. |
| destMaster | IMasterSlide | Diapositive maître pour une nouvelle diapositive. |
| allowCloneMissingLayout | Boolean | S'il n'y a pas de mise en page appropriée dans le master spécifié, la mise en page de la diapositive source sera clonée (si allowCloneMissingLayout est vrai) ou une PptxEditException sera levée (si allowCloneMissingLayout est faux). |

### Valeur de retour

Diapositive insérée.

### Exceptions

| exception | condition |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Levée s'il n'y a pas de mise en page appropriée dans le master spécifié et que allowCloneMissingLayout est faux. |

### Voir Aussi

* interface [ISlide](../../islide)
* interface [IMasterSlide](../../imasterslide)
* classe [SlideCollection](../../slidecollection)
* espace de noms [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->