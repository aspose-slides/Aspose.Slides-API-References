---
title: AddClone
second_title: Aspose.Sildes para .NET Referencia de API
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

### Comentarios

Al clonar una diapositiva entre diferentes presentaciones, el maestra de la diapositiva también puede ser clonado. Se utiliza un registro interno para rastrear automáticamente los maestrías clonadas y evitar la creación de múltiples clones de la misma diapositiva maestra. La clonación manual de diapositivas maestras no será ni prevenido ni registrado. Si necesitas más control sobre el proceso de clonación, usa [`AddClone`](../addclone) o [`AddClone`](../addclone) para clonar diapositivas, [`AddClone`](../../igloballayoutslidecollection/addclone) o [`AddClone`](../../igloballayoutslidecollection/addclone) para clonar diseños y [`AddClone`](../../imasterslidecollection/addclone) para clonar maestros.

### También Vea

* interfaz [ISlide](../../islide)
* interfaz [ISlideCollection](../../islidecollection)
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
    presentation.Sections.AddSection("Section 1", presentation.Slides[0]);
    
    ISection section2 = presentation.Sections.AppendEmptySection("Section 2");
    presentation.Slides.AddClone(presentation.Slides[0], section2);
    
    // Ahora la segunda sección contiene una copia de la primera diapositiva.
}
```

### También Vea

* interfaz [ISlide](../../islide)
* interfaz [ISection](../../isection)
* interfaz [ISlideCollection](../../islidecollection)
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
| destLayout | ILayoutSlide | Diapositiva de diseño para una nueva diapositiva. |

### Valor de Retorno

Nueva diapositiva.

### También Vea

* interfaz [ISlide](../../islide)
* interfaz [ILayoutSlide](../../ilayoutslide)
* interfaz [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddClone(ISlide, IMasterSlide, bool) {#addclone_2}

Agrega una copia de una diapositiva de origen especificada al final de la colección. El diseño apropiado será seleccionado automáticamente del maestro especificado (el diseño apropiado es el diseño con el mismo Tipo o Nombre que el del diseño de la diapositiva de origen). Si no hay un diseño apropiado, entonces se clonará el diseño de la diapositiva de origen (si allowCloneMissingLayout es verdadero) o se lanzará una PptxEditException (si allowCloneMissingLayout es falso).

```csharp
public ISlide AddClone(ISlide sourceSlide, IMasterSlide destMaster, bool allowCloneMissingLayout)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceSlide | ISlide | Diapositiva a clonar. |
| destMaster | IMasterSlide | Diapositiva maestra para una nueva diapositiva. |
| allowCloneMissingLayout | Boolean | Si no hay un diseño apropiado en el maestro especificado, se clonará el diseño de la diapositiva de origen (si allowCloneMissingLayout es verdadero) o se lanzará una PptxEditException (si allowCloneMissingLayout es falso). |

### Valor de Retorno

Nueva diapositiva.

### Excepciones

| excepción | condición |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Lanzado si no hay un diseño apropiado en el maestro especificado y allowCloneMissingLayout es falso. |

### También Vea

* interfaz [ISlide](../../islide)
* interfaz [IMasterSlide](../../imasterslide)
* interfaz [ISlideCollection](../../islidecollection)
* namespace [Aspose.Slides](../../islidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->