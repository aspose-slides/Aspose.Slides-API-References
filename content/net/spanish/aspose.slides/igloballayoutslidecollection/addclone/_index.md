---
title: AddClone
second_title: Referencia de la API de Aspose.Slides para .NET
description: Agrega una copia de una diapositiva de diseño especificada a la presentación.
type: docs
weight: 30
url: /es/aspose.slides/igloballayoutslidecollection/addclone/
---
## AddClone(ILayoutSlide) {#addclone}

Agrega una copia de una diapositiva de diseño especificada a la presentación.

```csharp
public ILayoutSlide AddClone(ILayoutSlide sourceLayout)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sourceLayout | ILayoutSlide | Deslice para clonar. |

### Valor_devuelto

Diapositiva añadida.

### Observaciones

Cuando se clona un diseño entre diferentes presentaciones, el maestro del diseño también se puede clonar para mantener el formato de origen. El registro interno se utiliza para realizar un seguimiento de los maestros clonados automáticamente para evitar la creación de múltiples clones de la misma diapositiva maestra. La clonación manual de las diapositivas maestras será ni impedido ni registrado.

### Ver también

* interface [ILayoutSlide](../../ilayoutslide)
* interface [IGlobalLayoutSlideCollection](../../igloballayoutslidecollection)
* espacio de nombres [Aspose.Slides](../../igloballayoutslidecollection)
* asamblea [Aspose.Slides](../../../)

---

## AddClone(ILayoutSlide, IMasterSlide) {#addclone_1}

Agrega una copia de una diapositiva de diseño especificada a la presentación.

```csharp
public ILayoutSlide AddClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sourceLayout | ILayoutSlide | Deslice para clonar. |
| destMaster | IMasterSlide | Diapositiva maestra para un nuevo diseño. |

### Valor_devuelto

Diapositiva añadida.

### Observaciones

El nuevo diseño se vinculará con el maestro definido en la presentación de destino. Así que esto es análogo a copiar/pegar con la opción "Usar tema de destino" en PowerPoint.

### Ver también

* interface [ILayoutSlide](../../ilayoutslide)
* interface [IMasterSlide](../../imasterslide)
* interface [IGlobalLayoutSlideCollection](../../igloballayoutslidecollection)
* espacio de nombres [Aspose.Slides](../../igloballayoutslidecollection)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
