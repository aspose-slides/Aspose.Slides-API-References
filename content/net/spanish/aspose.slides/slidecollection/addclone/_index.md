---
title: AddClone
second_title: Aspose.Sildes for .NET API Reference
description: Agrega una copia de una diapositiva especificada al final de la colección.
type: docs
weight: 50
url: /es/aspose.slides/slidecollection/addclone/
---

## AddClone(ISlide) {#addclone}

Agrega una copia de una diapositiva especificada al final de la colección.

```csharp
public ISlide AddClone(ISlide sourceSlide)
```

| Parámetro     | Tipo   | Descripción             |
|---------------|--------|-------------------------|
| sourceSlide   | ISlide | Diapositiva a clonar.  |

### Valor de Retorno

Nueva diapositiva.

### Observaciones

Al clonar una diapositiva entre diferentes presentaciones, la maestra de la diapositiva también puede ser clonada. Se utiliza un registro interno para seguir automáticamente las maestras clonadas para evitar la creación de múltiples clones de la misma diapositiva maestra. La clonación manual de diapositivas maestras no se prevendrá ni se registrará. Si necesitas más control sobre el proceso de clonación, utiliza [`AddClone`](../addclone) o [`AddClone`](../addclone) para clonar diapositivas, [`AddClone`](../../igloballayoutslidecollection/addclone) o [`AddClone`](../../igloballayoutslidecollection/addclone) para clonar diseños y [`AddClone`](../../imasterslidecollection/addclone) para clonar maestras.

### Ver También

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddClone(ISlide, ISection) {#addclone_3}

Agrega una copia de una diapositiva especificada al final de la sección especificada.

```csharp
public ISlide AddClone(ISlide sourceSlide, ISection section)
```

| Parámetro     | Tipo     | Descripción                |
|---------------|----------|----------------------------|
| sourceSlide   | ISlide   | Diapositiva a clonar.     |
| section       | ISection | Sección para una nueva diapositiva. |

### Valor de Retorno

Nueva diapositiva.

### Excepciones

| excepción                  | condición |
|----------------------------|-----------|
| ArgumentNullException       |           |
| [PptxEditException](../../pptxeditexception) |           |

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

### Ver También

* interface [ISlide](../../islide)
* interface [ISection](../../isection)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddClone(ISlide, ILayoutSlide) {#addclone_1}

Agrega una copia de una diapositiva especificada al final de la colección.

```csharp
public ISlide AddClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

| Parámetro     | Tipo        | Descripción                |
|---------------|-------------|----------------------------|
| sourceSlide   | ISlide      | Diapositiva a clonar.     |
| destLayout    | ILayoutSlide| Diapositiva de diseño para una nueva diapositiva. |

### Valor de Retorno

Nueva diapositiva.

### Ver También

* interface [ISlide](../../islide)
* interface [ILayoutSlide](../../ilayoutslide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddClone(ISlide, IMasterSlide, bool) {#addclone_2}

Agrega una copia de una diapositiva fuente especificada al final de la colección. El diseño apropiado se seleccionará automáticamente de la maestra especificada (el diseño apropiado es el diseño con el mismo Tipo o Nombre que el del diseño de la diapositiva fuente). Si no hay un diseño apropiado, el diseño de la diapositiva fuente será clonado (si allowCloneMissingLayout es true) o se lanzará PptxEditException (si allowCloneMissingLayout es false).

```csharp
public ISlide AddClone(ISlide sourceSlide, IMasterSlide destMaster, bool allowCloneMissingLayout)
```

| Parámetro               | Tipo        | Descripción                                                                                                                                                              |
|-------------------------|-------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| sourceSlide             | ISlide      | Diapositiva a clonar.                                                                                                                                                   |
| destMaster              | IMasterSlide | Diapositiva maestra para una nueva diapositiva.                                                                                                                         |
| allowCloneMissingLayout | Boolean     | Si no hay un diseño apropiado en la maestra especificada, entonces el diseño de la diapositiva fuente será clonado (si allowCloneMissingLayout es true) o se lanzará PptxEditException (si allowCloneMissingLayout es false). |

### Valor de Retorno

Nueva diapositiva.

### Excepciones

| excepción                             | condición                                                                                          |
|---------------------------------------|----------------------------------------------------------------------------------------------------|
| [PptxEditException](../../pptxeditexception) | Lanzado si no hay un diseño apropiado en la maestra especificada y allowCloneMissingLayout es false. |

### Ver También

* interface [ISlide](../../islide)
* interface [IMasterSlide](../../imasterslide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->