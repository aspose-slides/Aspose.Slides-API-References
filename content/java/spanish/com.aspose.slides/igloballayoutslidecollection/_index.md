---
title: IGlobalLayoutSlideCollection
second_title: Referencia de API de Aspose.Slides para Java
description: Representa una colección de todas las diapositivas de diseño en la presentación.
type: docs
url: /es/com.aspose.slides/igloballayoutslidecollection/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

Representa una colección de todas las diapositivas de diseño en la presentación. Extiende la interfaz ILayoutSlideCollection con métodos para agregar/clonar diapositivas de diseño en el contexto de la unión de las colecciones individuales de diapositivas de diseño del maestro.
## Métodos

| Método | Descripción |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Agrega una copia de una diapositiva de diseño especificada a la presentación. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Agrega una copia de una diapositiva de diseño especificada a la presentación. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Agrega una nueva diapositiva de diseño a la presentación. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


Agrega una copia de una diapositiva de diseño especificada a la presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva a clonar.

--------------------

Al clonar un diseño entre presentaciones diferentes, el maestro del diseño también puede clonarse para conservar el formato de origen. Se utiliza un registro interno para rastrear los maestros clonados automáticamente y evitar la creación de múltiples clones del mismo maestro. La clonación manual de maestros no será ni evitada ni registrada. |

**Devuelve:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva añadida.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```


Agrega una copia de una diapositiva de diseño especificada a la presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva a clonar. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositiva maestra para un nuevo diseño.

--------------------

El nuevo diseño se vinculará con el maestro definido en la presentación de destino. Por lo tanto, esto equivale a copiar/pegar con la opción “Use Destination Theme” en PowerPoint. |

**Devuelve:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva añadida.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```


Agrega una nueva diapositiva de diseño a la presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositiva maestra para un nuevo diseño. |
| layoutType | byte | Tipo de diseño para un nuevo diseño. Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nombre para un nuevo diseño. Si el nombre proporcionado ya está en uso se lanzará ArgumentException. Si se pasa un parámetro nulo, el nombre se generará automáticamente en función del tipo de diseño proporcionado (por ejemplo “Title Slide” o “1_Title Slide”, “2_..”, etc.).

--------------------

1) El diseño añadido para el valor SlideLayoutType.Custom de layoutType no contiene marcadores ni formas. 2) El análogo de este método es el método [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) al que se accede con la propiedad ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)). |

**Devuelve:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva añadida.