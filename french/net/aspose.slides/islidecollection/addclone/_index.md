---
title: AddClone
second_title: Référence de l'API Aspose.Slides pour .NET
description: Ajoute une copie dune diapositive spécifiée à la fin de la collection.
type: docs
weight: 20
url: /fr/net/aspose.slides/islidecollection/addclone/
---
## AddClone(ISlide) {#addclone}

Ajoute une copie d'une diapositive spécifiée à la fin de la collection.

```csharp
public ISlide AddClone(ISlide sourceSlide)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sourceSlide | ISlide | Faites glisser pour cloner. |

### Return_Value

Nouvelle diapositive.

### Remarques

Lors du clonage d'une diapositive entre différentes présentations, le maître de la diapositive peut également être cloné. Le registre interne est utilisé pour suivre automatiquement les maîtres clonés afin d'empêcher la création de plusieurs clones de la même diapositive maître. Le clonage manuel des diapositives maîtres ne sera ni empêché ni enregistré . Si vous avez besoin de plus de contrôle sur le processus de clonage, utilisez [`AddClone`](../addclone) ou [`AddClone`](../addclone) pour le clonage de diapositives, [`AddClone`](../../igloballayoutslidecollection/addclone) ou [`AddClone`](../../igloballayoutslidecollection/addclone)pour cloner des mises en page et [`AddClone`](../../imasterslidecollection/addclone) pour les maîtres de clonage.

### Voir également

* interface [ISlide](../../islide)
* interface [ISlideCollection](../../islidecollection)
* espace de noms [Aspose.Slides](../../islidecollection)
* Assemblée [Aspose.Slides](../../../)

---

## AddClone(ISlide, ISection) {#addclone_3}

Ajoute une copie d'une diapositive spécifiée à la fin de la section spécifiée.

```csharp
public ISlide AddClone(ISlide sourceSlide, ISection section)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sourceSlide | ISlide | Faites glisser pour cloner. |
| section | ISection | Section pour une nouvelle diapositive. |

### Return_Value

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

### Voir également

* interface [ISlide](../../islide)
* interface [ISection](../../isection)
* interface [ISlideCollection](../../islidecollection)
* espace de noms [Aspose.Slides](../../islidecollection)
* Assemblée [Aspose.Slides](../../../)

---

## AddClone(ISlide, ILayoutSlide) {#addclone_1}

Ajoute une copie d'une diapositive spécifiée à la fin de la collection.

```csharp
public ISlide AddClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sourceSlide | ISlide | Faites glisser pour cloner. |
| destLayout | ILayoutSlide | Diapositive de mise en page pour une nouvelle diapositive. |

### Return_Value

Nouvelle diapositive.

### Voir également

* interface [ISlide](../../islide)
* interface [ILayoutSlide](../../ilayoutslide)
* interface [ISlideCollection](../../islidecollection)
* espace de noms [Aspose.Slides](../../islidecollection)
* Assemblée [Aspose.Slides](../../../)

---

## AddClone(ISlide, IMasterSlide, bool) {#addclone_2}

Ajoute une copie d'une diapositive source spécifiée à la fin de la collection. La mise en page appropriée sera sélectionnée automatiquement à partir du maître spécifié (la mise en page appropriée est la mise en page avec le même type ou nom que de mise en page de la diapositive source). S'il n'y a pas de disposition appropriée, la disposition de la diapositive source sera clonée (si allowCloneMissingLayout est vrai) ou PptxEditException sera levée (si allowCloneMissingLayout est faux).

```csharp
public ISlide AddClone(ISlide sourceSlide, IMasterSlide destMaster, bool allowCloneMissingLayout)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| sourceSlide | ISlide | Faites glisser pour cloner. |
| destMaster | IMasterSlide | Diapositive principale pour une nouvelle diapositive. |
| allowCloneMissingLayout | Boolean | S'il n'y a pas de mise en page appropriée dans le masque spécifié, la mise en page de la diapositive source sera clonée (si allowCloneMissingLayout est vrai) ou PptxEditException sera levée (si allowCloneMissingLayout est faux). |

### Return_Value

Nouvelle diapositive.

### Exceptions

| exception | condition |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Levé s'il n'y a pas de mise en page appropriée dans le maître spécifié et allowCloneMissingLayout est faux. |

### Voir également

* interface [ISlide](../../islide)
* interface [IMasterSlide](../../imasterslide)
* interface [ISlideCollection](../../islidecollection)
* espace de noms [Aspose.Slides](../../islidecollection)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
