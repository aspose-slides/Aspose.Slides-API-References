---
title: SectionCollection
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa una colección de secciones.
type: docs
weight: 9490
url: /es/aspose.slides/sectioncollection/
---

## Clase SectionCollection

Representa una colección de secciones.

```csharp
public sealed class SectionCollection : DomObject<Presentation>, ISectionCollection
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.slides/sectioncollection/count) { get; } | Obtiene el número de elementos que realmente contiene la colección. Solo lectura Int32. |
| [IsSynchronized](../../aspose.slides/sectioncollection/issynchronized) { get; } | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). Solo lectura Boolean. |
| [Item](../../aspose.slides/sectioncollection/item) { get; } | Obtiene el elemento en el índice especificado. Solo lectura [`ISection`](../isection). |
| [SyncRoot](../../aspose.slides/sectioncollection/syncroot) { get; } | Devuelve una raíz de sincronización. Solo lectura Object. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddEmptySection](../../aspose.slides/sectioncollection/addemptysection)(string, int) | Agrega una sección vacía en la posición especificada de la colección. |
| [AddSection](../../aspose.slides/sectioncollection/addsection)(string, ISlide) | Agrega una sección de diapositivas que comienza desde una diapositiva específica. |
| [AppendEmptySection](../../aspose.slides/sectioncollection/appendemptysection)(string) | Agrega una sección vacía al final de la colección. |
| [Clear](../../aspose.slides/sectioncollection/clear)() | Elimina todas las secciones de la colección. |
| [CopyTo](../../aspose.slides/sectioncollection/copyto)(Array, int) | Copia toda la colección al array especificado. |
| [GetEnumerator](../../aspose.slides/sectioncollection/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [IndexOf](../../aspose.slides/sectioncollection/indexof)(ISection) | Devuelve un índice de la sección especificada en la colección. |
| [RemoveSection](../../aspose.slides/sectioncollection/removesection)(ISection) | Elimina la sección. Las diapositivas contenidas en la sección se fusionarán en la sección anterior. |
| [RemoveSectionWithSlides](../../aspose.slides/sectioncollection/removesectionwithslides)(ISection) | Elimina la sección y las diapositivas contenidas en la sección. |
| [ReorderSectionWithSlides](../../aspose.slides/sectioncollection/reordersectionwithslides)(ISection, int) | Mueve la sección y sus diapositivas de la colección a la posición especificada. |

### Ver También

* clase [DomObject&lt;TParent&gt;](../domobject-1)
* clase [Presentation](../presentation)
* interfaz [ISectionCollection](../isectioncollection)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->