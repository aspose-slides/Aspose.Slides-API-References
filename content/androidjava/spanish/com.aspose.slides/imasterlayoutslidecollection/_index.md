---
title: IMasterLayoutSlideCollection
second_title: Referencia de API Java de Aspose.Slides para Android
description: Representa una colección de todas las diapositivas de diseño de la diapositiva maestra definida.
type: docs
url: /es/com.aspose.slides/imasterlayoutslidecollection/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

Representa una colección de todas las layout slides de la master slide definida. Extiende la interfaz ILayoutSlideCollection con métodos para añadir/insertar/eliminar/clonar layout slides en el contexto de las colecciones individuales de layout slides de la master.

## Métodos

| Método | Descripción |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Añade una copia de una layout slide especificada al final de la colección. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Inserta una copia de una layout slide especificada en la posición especificada de la colección. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Añade una nueva layout slide al final de la colección. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Inserta una nueva layout slide en la posición especificada de la colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina el elemento en el índice especificado de la colección. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Mueve la layout slide de la colección a la posición especificada. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Añade una copia de una layout slide especificada al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva a clonar. |

--------------------

1) El nuevo layout se vinculará con la master slide padre para esta colección de layout slides. Por lo tanto, es análogo a copiar/pegar con la opción "Use Destination Theme" en PowerPoint. 2) Un análogo de este método es el método [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) accesado mediante la propiedad [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides). 

**Devuelve:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva añadida.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Inserta una copia de una layout slide especificada en la posición especificada de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la nueva diapositiva. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva a clonar. |

--------------------

El nuevo layout se vinculará con la master slide padre para esta colección de layout slides. Por lo tanto, es análogo a copiar/pegar con la opción "Use Destination Theme" en PowerPoint. 

**Devuelve:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva insertada.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```

Añade una nueva layout slide al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| layoutType | byte | Tipo de layout para un nuevo layout. Tipos de layout compatibles: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Otros tipos de layout no son compatibles ahora: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nombre para un nuevo layout. Si el nombre proporcionado ya está en uso se lanzará ArgumentException. Si se pasa un parámetro nulo, el nombre se generará automáticamente en función del tipo de layout proporcionado (por ejemplo "Title Slide" o "1_Title Slide", "2_..", etc.). |

--------------------

1) Se añadió un layout para el valor SlideLayoutType.Custom de layoutType que no contiene marcadores de posición ni formas. 2) Un análogo de este método es el método [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) accesado mediante la propiedad [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides). 

**Devuelve:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva añadida.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Inserta una nueva layout slide en la posición especificada de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la nueva diapositiva. |
| layoutType | byte | Tipo de layout para un nuevo layout. Tipos de layout compatibles: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Otros tipos de layout no son compatibles ahora: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nombre para un nuevo layout. Si el nombre proporcionado ya está en uso se lanzará ArgumentException. Si se pasa un parámetro nulo, el nombre se generará automáticamente en función del tipo de layout proporcionado (por ejemplo "Title Slide" o "1_Title Slide", "2_..", etc.). |

--------------------

Se insertó un layout para el valor SlideLayoutType.Custom de layoutType que no contiene marcadores de posición ni formas. 

**Devuelve:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva insertada.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Elimina el elemento en el índice especificado de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento a eliminar. |

--------------------

1) Para evitar que se lance PptxEditException, compruebe la propiedad HasDependingSlides del layout antes. 2) También puede usar el método [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) para simplificar el código. 

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

Mueve la layout slide de la colección a la posición especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice objetivo. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva a mover. |