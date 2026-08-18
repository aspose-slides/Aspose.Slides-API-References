---
title: MasterLayoutSlideCollection
second_title: Referencia de API de Aspose.Slides for Java
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
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Adds a copy of a specified layout slide to the end of the collection. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Inserts a copy of a specified layout slide to specified position of the collection. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Adds a new layout slide to the end of the collection. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Inserts a new layout slide to specified position of the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the collection. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Moves layout slide from the collection to the specified position. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Agrega una copia de una diapositiva de diseño especificada al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva a clonar. |

--------------------

1) El nuevo diseño se vinculará con la diapositiva maestra principal de esta colección de diapositivas de diseño. Por lo tanto, es análogo a copiar/pegar con la opción "Use Destination Theme" en PowerPoint. 2) Análogo a este método es el método [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) al que se accede mediante la propiedad ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

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
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva a clonar. |

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
| layoutType | byte | Tipo de diseño para un nuevo diseño. Tipos de diseño compatibles: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Otros tipos de diseño no son compatibles actualmente: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nombre para un nuevo diseño. Si el nombre proporcionado ya está en uso se lanzará ArgumentException. Si se pasa un parámetro nulo, el nombre se generará automáticamente en función del tipo de diseño proporcionado (por ejemplo "Title Slide" o "1_Title Slide", "2_..", etc.). |

--------------------

1) Se agregó un diseño para el valor SlideLayoutType.Custom de layoutType que no contiene marcadores de posición ni formas. 2) Análogo a este método es el método [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) al que se accede mediante la propiedad ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

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
| layoutType | byte | Tipo de diseño para un nuevo diseño. Tipos de diseño compatibles: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Otros tipos de diseño no son compatibles actualmente: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nombre para un nuevo diseño. Si el nombre proporcionado ya está en uso se lanzará ArgumentException. Si se pasa un parámetro nulo, el nombre se generará automáticamente en función del tipo de diseño proporcionado (por ejemplo "Title Slide" o "1_Title Slide", "2_..", etc.). |

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
| index | int | El índice basado en cero del elemento a eliminar. |

--------------------

1) Para evitar que se lance la excepción PptxEditException, compruebe la propiedad HasDependingSlides del diseño antes. 2) También puede usar el método [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) para simplificar el código.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

Mueve la diapositiva de diseño de la colección a la posición especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de destino. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva a mover. |