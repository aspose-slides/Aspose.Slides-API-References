---
title: InsertClone
second_title: Referencia de API de Aspose.Slides para .NET
description: Inserta una copia de una diapositiva especificada en la posición especificada de la colección.
type: docs
weight: 120
url: /es/aspose.slides/slidecollection/insertclone/
---

## InsertClone(int, ISlide) {#insertclone}

Inserta una copia de una diapositiva especificada en la posición especificada de la colección.

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | Índice de la nueva diapositiva. |
| sourceSlide | ISlide | Diapositiva a clonar. |

### Valor de Retorno

Diapositiva insertada.

### Observaciones

Al clonar una diapositiva entre diferentes presentaciones, el máster de la diapositiva también puede ser clonado. Se utiliza un registro interno para rastrear automáticamente los másters clonados para prevenir la creación de múltiples clones de la misma diapositiva máster. La clonación manual de diapositivas máster no será ni prevenida ni registrada. Si necesitas más control sobre el proceso de clonación, usa [`InsertClone`](../insertclone) o [`InsertClone`](../insertclone) para clonar diapositivas y [`AddClone`](../../imasterslidecollection/addclone) para clonar másters.

### Ejemplos

El siguiente ejemplo muestra cómo clonar en otra posición dentro de la Presentación.

```csharp
[C#]
// Instanciar la clase Presentation que representa un archivo de presentación
using (Presentation pres = new Presentation("CloneWithInSamePresentation.pptx"))
{
    // Clonar la diapositiva deseada al final de la colección de diapositivas en la misma presentación
    ISlideCollection slds = pres.Slides;
    // Clonar la diapositiva deseada en el índice especificado en la misma presentación
    slds.InsertClone(2, pres.Slides[1]);
    // Escribir la presentación modificada en el disco
    pres.Save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
}
```

El siguiente ejemplo muestra cómo clonar en otra posición dentro de la Presentación.

```csharp
[C#]
// Instanciar la clase Presentation para cargar el archivo de presentación fuente
using (Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx"))
{
    // Instanciar la clase Presentation para el destino PPTX (donde se clonará la diapositiva)
    using (Presentation destPres = new Presentation())
    {
        ISlideCollection slds = destPres.Slides;
        slds.InsertClone(2, srcPres.Slides[0]);
        // Escribir la presentación de destino en el disco
        destPres.Save("Aspose2_out.pptx", SaveFormat.Pptx);
    }
}
```

### Ver También

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertClone(int, ISlide, ILayoutSlide) {#insertclone_1}

Inserta una copia de una diapositiva especificada en la posición especificada de la colección.

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | Índice de la nueva diapositiva. |
| sourceSlide | ISlide | Diapositiva a clonar. |
| destLayout | ILayoutSlide | Diseño de la diapositiva para una nueva diapositiva. |

### Valor de Retorno

Diapositiva insertada.

### Ver También

* interface [ISlide](../../islide)
* interface [ILayoutSlide](../../ilayoutslide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertClone(int, ISlide, IMasterSlide, bool) {#insertclone_2}

Inserta una copia de una diapositiva fuente especificada en la posición especificada de la colección. Se seleccionará automáticamente el diseño apropiado del máster especificado (el diseño apropiado es el diseño con el mismo Tipo o Nombre que el diseño de la diapositiva fuente). Si no hay un diseño apropiado, entonces se clonará el diseño de la diapositiva fuente (si allowCloneMissingLayout es verdadero) o se lanzará una PptxEditException (si allowCloneMissingLayout es falso).

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, 
    bool allowCloneMissingLayout)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | Índice de la nueva diapositiva. |
| sourceSlide | ISlide | Diapositiva a clonar. |
| destMaster | IMasterSlide | Diapositiva máster para una nueva diapositiva. |
| allowCloneMissingLayout | Boolean | Si no hay un diseño apropiado en el máster especificado, entonces se clonará el diseño de la diapositiva fuente (si allowCloneMissingLayout es verdadero) o se lanzará una PptxEditException (si allowCloneMissingLayout es falso). |

### Valor de Retorno

Diapositiva insertada.

### Excepciones

| excepción | condición |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Lanzado si no hay un diseño apropiado en el máster especificado y allowCloneMissingLayout es falso. |

### Ver También

* interface [ISlide](../../islide)
* interface [IMasterSlide](../../imasterslide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->