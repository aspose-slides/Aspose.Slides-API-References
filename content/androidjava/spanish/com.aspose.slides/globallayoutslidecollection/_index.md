---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides para Android vía Referencia de API Java
description: Representa una colección de todas las diapositivas de diseño en la presentación.
type: docs
url: /es/com.aspose.slides/globallayoutslidecollection/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Todas las interfaces implementadas:**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

Representa una colección de todas las diapositivas de diseño en la presentación. Extiende la clase LayoutSlideCollection con métodos para agregar/clonar diapositivas de diseño en el contexto de la unión de las colecciones individuales de diapositivas maestras de diseño.
## Métodos

| Método | Descripción |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Agrega una copia de una diapositiva de diseño especificada a la presentación. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Agrega una copia de una diapositiva de diseño especificada a la presentación. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Agrega una nueva diapositiva de diseño a la presentación. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


Agrega una copia de una diapositiva de diseño especificada a la presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva a clonar.

--------------------

Al clonar un diseño entre diferentes presentaciones, la maestra del diseño también puede clonarse para conservar el formato de origen. Se utiliza un registro interno para rastrear las maestras clonadas automáticamente y evitar la creación de múltiples copias de la misma diapositiva maestra. La clonación manual de diapositivas maestras no será ni impedida ni registrada. |

**Devuelve:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva añadida.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```


Agrega una copia de una diapositiva de diseño especificada a la presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva a clonar. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositiva maestra para un nuevo diseño.

--------------------

1) El nuevo diseño se vinculará con la maestra definida en la presentación de destino. Por lo tanto, es análogo a copiar/pegar con la opción "Usar tema de destino" en PowerPoint. 2) Análogo de este método es el método [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) accedido con la propiedad ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)). |

**Devuelve:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva añadida.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```


Agrega una nueva diapositiva de diseño a la presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositiva maestra para un nuevo diseño. |
| layoutType | byte | Tipo de diseño para un nuevo diseño. Tipos de diseño compatibles: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Otros tipos de diseño no son compatibles ahora: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nombre para un nuevo diseño. Si el nombre proporcionado ya está en uso, se lanzará ArgumentException. Si se pasa un parámetro nulo, el nombre se generará automáticamente en función del tipo de diseño proporcionado (por ejemplo "Title Slide" o "1_Title Slide", "2_..", etc.).

--------------------

1) Se añadió un diseño para el valor SlideLayoutType.Custom de layoutType, que no contiene marcadores de posición ni formas. 2) Análogo de este método es el método [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) accedido con la propiedad ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)). |

**Devuelve:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva añadida.