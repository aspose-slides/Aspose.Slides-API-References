---
title: GlobalLayoutSlideCollection
second_title: Referencia de API de Aspose.Slides para Java
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

Representa una colección de todas las diapositivas de diseño en la presentación. Extiende la clase LayoutSlideCollection con métodos para agregar/clonar diapositivas de diseño en el contexto de la unión de las colecciones individuales de diapositivas de diseño del maestro.

## Métodos

| Método | Descripción |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Añade una copia de una diapositiva de diseño especificada a la presentación. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Añade una copia de una diapositiva de diseño especificada a la presentación. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Añade una nueva diapositiva de diseño a la presentación. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Añade una copia de una diapositiva de diseño especificada a la presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva a clonar. |

--------------------

Al clonar un diseño entre presentaciones diferentes, el maestro del diseño también puede clonarse para conservar el formato de origen. Se utiliza un registro interno para rastrear los maestros clonados automáticamente y evitar la creación de múltiples copias del mismo maestro. La clonación manual de maestros no será ni impedida ni registrada.

**Devuelve:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva añadida.

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Añade una copia de una diapositiva de diseño especificada a la presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva a clonar. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Maestro de diapositiva para el nuevo diseño. |

--------------------

1) El nuevo diseño se enlazará con el maestro definido en la presentación de destino. Por lo tanto, es análogo a copiar/pegar con la opción «Usar tema de destino» en PowerPoint. 2) Un método análogo a este es el método [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) accesado mediante la propiedad ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).

**Devuelve:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva añadida.

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Añade una nueva diapositiva de diseño a la presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Maestro de diapositiva para el nuevo diseño. |
| layoutType | byte | Tipo de diseño para el nuevo diseño. Tipos de diseño compatibles: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Otros tipos de diseño no son compatibles actualmente: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nombre para el nuevo diseño. Si el nombre proporcionado ya está en uso se lanzará una ArgumentException. Si se pasa un parámetro nulo, el nombre se generará automáticamente según el tipo de diseño proporcionado (por ejemplo, “Title Slide” o “1_Title Slide”, “2_…”, etc.). |

--------------------

1) El diseño añadido para el valor SlideLayoutType.Custom de layoutType no contiene marcadores de posición ni formas. 2) Un método análogo a este es el método [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) accesado mediante la propiedad ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).

**Devuelve:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva añadida.