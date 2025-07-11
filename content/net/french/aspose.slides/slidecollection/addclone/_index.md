---
title: AddClone
second_title: Aspose.Slides pour .NET Référence API
description: Ajoute une copie d'une diapositive spécifiée à la fin de la collection.
type: docs
weight: 50
url: /fr/aspose.slides/slidecollection/addclone/
---

## AddClone(ISlide) {#addclone}

Ajoute une copie d'une diapositive spécifiée à la fin de la collection.

```csharp
public ISlide AddClone(ISlide sourceSlide)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceSlide | ISlide | Diapositive à cloner. |

### Valeur de retour

Nouvelle diapositive.

### Remarques

Lors du clonage d'une diapositive entre différentes présentations, le maître de la diapositive peut également être cloné. Un registre interne est utilisé pour suivre automatiquement les maîtres clonés afin d'éviter la création de plusieurs clones de la même diapositive maître. Le clonage manuel des diapositives maître ne sera ni empêché ni enregistré. Si vous avez besoin de plus de contrôle sur le processus de clonage, utilisez [`AddClone`](../addclone) ou [`AddClone`](../addclone) pour cloner des diapositives, [`AddClone`](../../igloballayoutslidecollection/addclone) ou [`AddClone`](../../igloballayoutslidecollection/addclone) pour cloner des dispositions et [`AddClone`](../../imasterslidecollection/addclone) pour cloner des maîtres.

### Voir aussi

* interface [ISlide](../../islide)
* classe [SlideCollection](../../slidecollection)
* espace de noms [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddClone(ISlide, ISection) {#addclone_3}

Ajoute une copie d'une diapositive spécifiée à la fin de la section spécifiée.

```csharp
public ISlide AddClone(ISlide sourceSlide, ISection section)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceSlide | ISlide | Diapositive à cloner. |
| section | ISection | Section pour une nouvelle diapositive. |

### Valeur de retour

Nouvelle diapositive.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException |  |
| [PptxEditException](../../pptxeditexception) |  |

### Exemples

```csharp
[C#]
using (IPresentation presentation = new Presentation())
{
    presentation.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 50, 300, 100);
    presentation.Sections.AddSection("Section 1", presentation.Slides[0]);
    
    ISection section2 = presentation.Sections.AppendEmptySection("Section 2");
    presentation.Slides.AddClone(presentation.Slides[0], section2);
    
    // Maintenant, la deuxième section contient une copie de la première diapositive.
}
```

### Voir aussi

* interface [ISlide](../../islide)
* interface [ISection](../../isection)
* classe [SlideCollection](../../slidecollection)
* espace de noms [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddClone(ISlide, ILayoutSlide) {#addclone_1}

Ajoute une copie d'une diapositive spécifiée à la fin de la collection.

```csharp
public ISlide AddClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceSlide | ISlide | Diapositive à cloner. |
| destLayout | ILayoutSlide | Diapositive de mise en page pour une nouvelle diapositive. |

### Valeur de retour

Nouvelle diapositive.

### Voir aussi

* interface [ISlide](../../islide)
* interface [ILayoutSlide](../../ilayoutslide)
* classe [SlideCollection](../../slidecollection)
* espace de noms [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddClone(ISlide, IMasterSlide, bool) {#addclone_2}

Ajoute une copie d'une diapositive source spécifiée à la fin de la collection. La mise en page appropriée sera sélectionnée automatiquement à partir du maître spécifié (la mise en page appropriée est celle ayant le même type ou le même nom que la mise en page de la diapositive source). S'il n'y a pas de mise en page appropriée, alors la mise en page de la diapositive source sera clonée (si allowCloneMissingLayout est vrai) ou une PptxEditException sera levée (si allowCloneMissingLayout est faux).

```csharp
public ISlide AddClone(ISlide sourceSlide, IMasterSlide destMaster, bool allowCloneMissingLayout)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceSlide | ISlide | Diapositive à cloner. |
| destMaster | IMasterSlide | Diapositive maître pour une nouvelle diapositive. |
| allowCloneMissingLayout | Boolean | S'il n'y a pas de mise en page appropriée dans le maître spécifié, alors la mise en page de la diapositive source sera clonée (si allowCloneMissingLayout est vrai) ou une PptxEditException sera levée (si allowCloneMissingLayout est faux). |

### Valeur de retour

Nouvelle diapositive.

### Exceptions

| exception | condition |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Levée si aucune mise en page appropriée n'est trouvée dans le maître spécifié et si allowCloneMissingLayout est faux. |

### Voir aussi

* interface [ISlide](../../islide)
* interface [IMasterSlide](../../imasterslide)
* classe [SlideCollection](../../slidecollection)
* espace de noms [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->