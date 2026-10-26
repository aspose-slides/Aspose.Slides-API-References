---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides para Android a través de la referencia de API de Java
description: Representa una colección de todas las diapositivas de diseño de la diapositiva maestra definida.
type: docs
url: /es/com.aspose.slides/masterlayoutslidecollection/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Todas las interfaces implementadas:**
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

Representa una colección de todas las diapositivas de diseño de la diapositiva maestra definida. Extiende la clase LayoutSlideCollection con métodos para agregar/insertar/eliminar/clonar/reordenar diapositivas de diseño en el contexto de las colecciones individuales de diapositivas de diseño de la maestra.
## Métodos

| Método | Descripción |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Agrega una copia de una diapositiva de diseño especificada al final de la colección. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Inserta una copia de una diapositiva de diseño especificada en la posición especificada de la colección. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Agrega una nueva diapositiva de diseño al final de la colección. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Inserta una nueva diapositiva de diseño en la posición especificada de la colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina el elemento en el índice especificado de la colección. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Mueve la diapositiva de diseño de la colección a la posición especificada. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Agrega una copia de una diapositiva de diseño especificada al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva a clonar.

--------------------

1) El nuevo diseño se vinculará con la diapositiva maestra principal de esta colección de diapositivas de diseño. Por lo tanto, es análogo a copiar/pegar con la opción "Use Destination Theme" en PowerPoint. 2) Un análogo de este método es el método [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) accedido mediante la propiedad ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Devuelve:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva agregada.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Inserta una copia de una diapositiva de diseño especificada en la posición especificada de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la nueva diapositiva. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva a clonar.

--------------------

El nuevo diseño se vinculará con la diapositiva maestra principal de esta colección de diapositivas de diseño. Por lo tanto, es análogo a copiar/pegar con la opción "Use Destination Theme" en PowerPoint.

**Devuelve:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva insertada.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

Agrega una nueva diapositiva de diseño al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| layoutType | byte | Tipo de diseño para un nuevo diseño. Tipos de diseño admitidos: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Otros tipos de diseño no son compatibles ahora: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nombre para un nuevo diseño. Si el nombre proporcionado ya está en uso se lanzará una ArgumentException. Si se pasa un parámetro null, el nombre se generará automáticamente en función del tipo de diseño proporcionado (por ejemplo "Title Slide" o "1\_Title Slide", "2\_..", etc.).

--------------------

1) Se añadió un diseño para el valor SlideLayoutType.Custom de layoutType que no contiene marcadores de posición ni formas. 2) Un análogo de este método es el método [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) accedido mediante la propiedad ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Devuelve:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva agregada.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Inserta una nueva diapositiva de diseño en la posición especificada de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la nueva diapositiva. |
| layoutType | byte | Tipo de diseño para un nuevo diseño. Tipos de diseño admitidos: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Otros tipos de diseño no son compatibles ahora: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nombre para un nuevo diseño. Si el nombre proporcionado ya está en uso se lanzará una ArgumentException. Si se pasa un parámetro null, el nombre se generará automáticamente en función del tipo de diseño proporcionado (por ejemplo "Title Slide" o "1\_Title Slide", "2\_..", etc.).

--------------------

Se insertó un diseño para el valor SlideLayoutType.Custom de layoutType que no contiene marcadores de posición ni formas.

**Devuelve:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva insertada.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Elimina el elemento en el índice especificado de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento a eliminar.

--------------------

1) Para evitar lanzar la PptxEditException, verifique la propiedad HasDependingSlides del diseño antes. 2) También puede utilizar el método [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) para simplificar el código.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

Mueve la diapositiva de diseño de la colección a la posición especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de destino. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva a mover.