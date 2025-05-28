---
title: AddClone
second_title: Referencia de la API de Aspose.Slides para .NET
description: Agrega una copia de una diapositiva específica al final de la colección.
type: docs
weight: 20
url: /es/aspose.slides/islidecollection/addclone/
---
## AddClone(ISlide) {#addclone}

Agrega una copia de una diapositiva específica al final de la colección.

```csharp
public ISlide AddClone(ISlide sourceSlide)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sourceSlide | ISlide | Deslice para clonar. |

### Valor_devuelto

Nuevo tobogán.

### Observaciones

Al clonar una diapositiva entre diferentes presentaciones, la diapositiva maestra también se puede clonar. El registro interno se utiliza para rastrear automáticamente las diapositivas maestras clonadas para evitar la creación de múltiples clones de la misma diapositiva maestra. La clonación manual de diapositivas maestras no se evitará ni se registrará . Si necesita más control sobre el proceso de clonación use [`AddClone`](../addclone) o [`AddClone`](../addclone) para clonar portaobjetos, [`AddClone`](../../igloballayoutslidecollection/addclone) o [`AddClone`](../../igloballayoutslidecollection/addclone)para clonar diseños y [`AddClone`](../../imasterslidecollection/addclone) para clonar maestros.

### Ver también

* interface [ISlide](../../islide)
* interface [ISlideCollection](../../islidecollection)
* espacio de nombres [Aspose.Slides](../../islidecollection)
* asamblea [Aspose.Slides](../../../)

---

## AddClone(ISlide, ISection) {#addclone_3}

Agrega una copia de una diapositiva especificada al final de la sección especificada.

```csharp
public ISlide AddClone(ISlide sourceSlide, ISection section)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sourceSlide | ISlide | Deslice para clonar. |
| section | ISection | Sección para una nueva diapositiva. |

### Valor_devuelto

Nuevo tobogán.

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
    presentation.Sections.AddSection("Section 1", presentation.Slides[0]);
    
    ISection section2 = presentation.Sections.AppendEmptySection("Section 2");
    presentation.Slides.AddClone(presentation.Slides[0], section2);
    
    // Ahora la segunda sección contiene una copia de la primera diapositiva.
}
```

### Ver también

* interface [ISlide](../../islide)
* interface [ISection](../../isection)
* interface [ISlideCollection](../../islidecollection)
* espacio de nombres [Aspose.Slides](../../islidecollection)
* asamblea [Aspose.Slides](../../../)

---

## AddClone(ISlide, ILayoutSlide) {#addclone_1}

Agrega una copia de una diapositiva específica al final de la colección.

```csharp
public ISlide AddClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sourceSlide | ISlide | Deslice para clonar. |
| destLayout | ILayoutSlide | Diseño de diapositiva para una nueva diapositiva. |

### Valor_devuelto

Nuevo tobogán.

### Ver también

* interface [ISlide](../../islide)
* interface [ILayoutSlide](../../ilayoutslide)
* interface [ISlideCollection](../../islidecollection)
* espacio de nombres [Aspose.Slides](../../islidecollection)
* asamblea [Aspose.Slides](../../../)

---

## AddClone(ISlide, IMasterSlide, bool) {#addclone_2}

Agrega una copia de una diapositiva de origen especificada al final de la colección. El diseño adecuado se seleccionará automáticamente del patrón especificado (el diseño apropiado es el diseño con el mismo tipo o nombre que del diseño de la diapositiva de origen). Si no hay un diseño adecuado, se clonará el diseño de la diapositiva de origen (si allowCloneMissingLayout es verdadero) o se generará una excepción PptxEditException (si allowCloneMissingLayout es falso).

```csharp
public ISlide AddClone(ISlide sourceSlide, IMasterSlide destMaster, bool allowCloneMissingLayout)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sourceSlide | ISlide | Deslice para clonar. |
| destMaster | IMasterSlide | Diapositiva maestra para una nueva diapositiva. |
| allowCloneMissingLayout | Boolean | Si no hay un diseño adecuado en el patrón especificado, se clonará el diseño de la diapositiva de origen (si allowCloneMissingLayout es verdadero) o se lanzará PptxEditException (si allowCloneMissingLayout es falso). |

### Valor_devuelto

Nuevo tobogán.

### Excepciones

| excepción | condición |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Lanzado si no hay un diseño apropiado en el maestro especificado y allowCloneMissingLayout es falso. |

### Ver también

* interface [ISlide](../../islide)
* interface [IMasterSlide](../../imasterslide)
* interface [ISlideCollection](../../islidecollection)
* espacio de nombres [Aspose.Slides](../../islidecollection)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
