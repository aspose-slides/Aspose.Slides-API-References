---
title: InsertClone
second_title: Referencia de API de Aspose.Slides para .NET
description: Inserta una copia de una diapositiva maestra especificada en la posición especificada de la colección. Las diapositivas de diseño vinculadas también se copiarán.
type: docs
weight: 80
url: /es/aspose.slides/masterslidecollection/insertclone/
---

## Método MasterSlideCollection.InsertClone

Inserta una copia de una diapositiva maestra especificada en la posición especificada de la colección. Las diapositivas de diseño vinculadas también se copiarán.

```csharp
public IMasterSlide InsertClone(int index, IMasterSlide sourceMaster)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | Índice de la nueva diapositiva. |
| sourceMaster | IMasterSlide | Diapositiva a clonar. |

### Valor de retorno

Diapositiva maestra insertada.

### Ejemplos

El siguiente ejemplo muestra cómo clonar una diapositiva maestra en otra presentación de PowerPoint.

```csharp
[C#]
// Instanciar la clase Presentation para cargar el archivo de presentación de origen
using (Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx"))
{
    // Instanciar la clase Presentation para la presentación de destino (donde se clonará la diapositiva)
    using (Presentation destPres = new Presentation())
    {
        // Instanciar ISlide desde la colección de diapositivas en la presentación de origen junto con
        // la diapositiva maestra
        ISlide SourceSlide = srcPres.Slides[0];
        IMasterSlide SourceMaster = SourceSlide.LayoutSlide.MasterSlide;
		// Obtener las diapositivas maestras de la presentación de destino
        IMasterSlideCollection masters = destPres.Masters;
        // Clonar la diapositiva maestra deseada de la presentación de origen a la colección de maestras en la
        // presentación de destino
        IMasterSlide iSlide = masters.AddClone(SourceMaster);
        // Colección de diapositivas en la presentación de destino
        ISlideCollection slds = destPres.Slides;
		// Clonar la diapositiva de origen a la colección de diapositivas de destino.
        slds.AddClone(SourceSlide, iSlide, true);
        // Guardar la presentación de destino en el disco
        destPres.Save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
    }
}
```

### Ver también

* interfaz [IMasterSlide](../../imasterslide)
* clase [MasterSlideCollection](../../masterslidecollection)
* espacio de nombres [Aspose.Slides](../../masterslidecollection)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->