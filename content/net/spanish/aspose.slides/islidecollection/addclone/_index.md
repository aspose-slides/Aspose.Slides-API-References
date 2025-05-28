---
title: AddClone
second_title: Referencia de API de Aspose.Slides para .NET
description: Agrega una copia de una diapositiva especificada al final de la colección.
type: docs
weight: 20
url: /es/aspose.slides/islidecollection/addclone/
---

## AddClone(ISlide) {#addclone}

Agrega una copia de una diapositiva especificada al final de la colección.

```csharp
public ISlide AddClone(ISlide sourceSlide)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceSlide | ISlide | Diapositiva a clonar. |

### Valor de Retorno

Nueva diapositiva.

### Observaciones

Al clonar una diapositiva entre diferentes presentaciones, la maestra de la diapositiva también puede ser clonada. Se utiliza un registro interno para rastrear automáticamente las maestras clonadas y prevenir la creación de múltiples clones de la misma diapositiva maestra. La clonación manual de diapositivas maestras no será ni prevenida ni registrada. Si necesitas más control sobre el proceso de clonación, utiliza [`AddClone`](../addclone) o [`AddClone`](../addclone) para clonar diapositivas, [`AddClone`](../../igloballayoutslidecollection/addclone) o [`AddClone`](../../igloballayoutslidecollection/addclone) para clonar diseños y [`AddClone`](../../imasterslidecollection/addclone) para clonar maestras.

### Véase También

* interface [ISlide](../../islide)
* interface [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddClone(ISlide, ISection) {#addclone_3}

Agrega una copia de una diapositiva especificada al final de la sección especificada.

```csharp
public ISlide AddClone(ISlide sourceSlide, ISection section)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceSlide | ISlide | Diapositiva a clonar. |
| section | ISection | Sección para una nueva diapositiva. |

### Valor de Retorno

Nueva diapositiva.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException |  |
| [PptxEditException](../../pptxeditexception) |  |

### Ejemplos

```csharp
[C#]
using (IPresentation presentation = new Presentation())
{
    presentation.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 200, 50, 300, 100);
    presentation.Sections.AddSection("Sección 1", presentation.Slides[0]);
    
    ISection section2 = presentation.Sections.AppendEmptySection("Sección 2");
    presentation.Slides.AddClone(presentation.Slides[0], section2);
    
    // Ahora la segunda sección contiene una copia de la primera diapositiva.
}
```

### Véase También

* interface [ISlide](../../islide)
* interface [ISection](../../isection)
* interface [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddClone(ISlide, ILayoutSlide) {#addclone_1}

Agrega una copia de una diapositiva especificada al final de la colección.

```csharp
public ISlide AddClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceSlide | ISlide | Diapositiva a clonar. |
| destLayout | ILayoutSlide | Diseño de diapositiva para una nueva diapositiva. |

### Valor de Retorno

Nueva diapositiva.

### Véase También

* interface [ISlide](../../islide)
* interface [ILayoutSlide](../../ilayoutslide)
* interface [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddClone(ISlide, IMasterSlide, bool) {#addclone_2}

Agrega una copia de una diapositiva fuente especificada al final de la colección. Se seleccionará automáticamente el diseño apropiado de la maestra especificada (el diseño apropiado es el diseño con el mismo Tipo o Nombre que el diseño de la diapositiva fuente). Si no hay un diseño apropiado, entonces se clonará el diseño de la diapositiva fuente (si allowCloneMissingLayout es verdadero) o se lanzará `PptxEditException` (si allowCloneMissingLayout es falso).

```csharp
public ISlide AddClone(ISlide sourceSlide, IMasterSlide destMaster, bool allowCloneMissingLayout)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceSlide | ISlide | Diapositiva a clonar. |
| destMaster | IMasterSlide | Diapositiva maestra para una nueva diapositiva. |
| allowCloneMissingLayout | Boolean | Si no hay un diseño apropiado en la maestra especificada, entonces se clonará el diseño de la diapositiva fuente (si allowCloneMissingLayout es verdadero) o se lanzará `PptxEditException` (si allowCloneMissingLayout es falso). |

### Valor de Retorno

Nueva diapositiva.

### Excepciones

| excepción | condición |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Lanzado si no hay un diseño apropiado en la maestra especificada y allowCloneMissingLayout es falso. |

### Véase También

* interface [ISlide](../../islide)
* interface [IMasterSlide](../../imasterslide)
* interface [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->