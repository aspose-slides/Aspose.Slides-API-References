---
title: InsertClone
second_title: Referencia de API de Aspose.Sildes para .NET
description: Inserta una copia de una diapositiva especificada en la posición especificada de la colección.
type: docs
weight: 120
url: /es/aspose.slides/slidecollection/insertclone/
---

## InsertClone(int, ISlide) {#insertclone}

Inserta una copia de una diapositiva especificada en la posición especificada de la colección.

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | Índice de la nueva diapositiva. |
| sourceSlide | ISlide | Diapositiva a clonar. |

### Valor de retorno

Diapositiva insertada.

### Observaciones

Al clonar una diapositiva entre diferentes presentaciones, el maestro de la diapositiva también puede ser clonado. Se utiliza un registro interno para rastrear automáticamente los maestros clonados para evitar la creación de múltiples clones del mismo maestro de diapositiva. La clonación manual de maestros de diapositivas no será evitada ni registrada. Si necesita más control sobre el proceso de clonación, use [`InsertClone`](../insertclone) o [`InsertClone`](../insertclone) para clonar diapositivas y [`AddClone`](../../imasterslidecollection/addclone) para clonar maestros.

### Ejemplos

El siguiente ejemplo muestra cómo clonar en otra posición dentro de la presentación.

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

El siguiente ejemplo muestra cómo clonar en otra posición dentro de la presentación.

```csharp
[C#]
// Instanciar la clase Presentation para cargar el archivo de presentación de origen
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

### Ver también

* interfaz [ISlide](../../islide)
* clase [SlideCollection](../../slidecollection)
* espacio de nombres [Aspose.Slides](../../slidecollection)
* ensamblaje [Aspose.Slides](../../../)

---

## InsertClone(int, ISlide, ILayoutSlide) {#insertclone_1}

Inserta una copia de una diapositiva especificada en la posición especificada de la colección.

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | Índice de la nueva diapositiva. |
| sourceSlide | ISlide | Diapositiva a clonar. |
| destLayout | ILayoutSlide | Diapositiva de diseño para una nueva diapositiva. |

### Valor de retorno

Diapositiva insertada.

### Ver también

* interfaz [ISlide](../../islide)
* interfaz [ILayoutSlide](../../ilayoutslide)
* clase [SlideCollection](../../slidecollection)
* espacio de nombres [Aspose.Slides](../../slidecollection)
* ensamblaje [Aspose.Slides](../../../)

---

## InsertClone(int, ISlide, IMasterSlide, bool) {#insertclone_2}

Inserta una copia de una diapositiva de origen especificada en la posición especificada de la colección. Se seleccionará automáticamente el diseño apropiado del maestro especificado (el diseño apropiado es el diseño con el mismo Tipo o Nombre que el diseño de la diapositiva de origen). Si no hay un diseño apropiado, entonces se clonará el diseño de la diapositiva de origen (si allowCloneMissingLayout es verdadero) o se lanzará PptxEditException (si allowCloneMissingLayout es falso).

```csharp
public ISlide InsertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, 
    bool allowCloneMissingLayout)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | Índice de la nueva diapositiva. |
| sourceSlide | ISlide | Diapositiva a clonar. |
| destMaster | IMasterSlide | Maestro de diapositiva para una nueva diapositiva. |
| allowCloneMissingLayout | Boolean | Si no hay un diseño apropiado en el maestro especificado, entonces se clonará el diseño de la diapositiva de origen (si allowCloneMissingLayout es verdadero) o se lanzará PptxEditException (si allowCloneMissingLayout es falso). |

### Valor de retorno

Diapositiva insertada.

### Excepciones

| excepción | condición |
| --- | --- |
| [PptxEditException](../../pptxeditexception) | Lanzado si no hay un diseño apropiado en el maestro especificado y allowCloneMissingLayout es falso. |

### Ver también

* interfaz [ISlide](../../islide)
* interfaz [IMasterSlide](../../imasterslide)
* clase [SlideCollection](../../slidecollection)
* espacio de nombres [Aspose.Slides](../../slidecollection)
* ensamblaje [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->