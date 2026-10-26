---
title: IGlobalLayoutSlideCollection
second_title: Referencia de API de Aspose.Slides para Android mediante Java
description: Representa una colección de todas las diapositivas de diseño en la presentación.
type: docs
url: /es/com.aspose.slides/igloballayoutslidecollection/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

Representa una colección de todas las diapositivas de diseño en la presentación. Extiende la interfaz ILayoutSlideCollection con métodos para agregar/clonar diapositivas de diseño en el contexto de la unión de las colecciones individuales de diapositivas de diseño del maestro.

## Métodos

| Méthodo | Descripción |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Añade una copia de una diapositiva de diseño especificada a la presentación. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Añade una copia de una diapositiva de diseño especificada a la presentación. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Añade una nueva diapositiva de diseño a la presentación. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Añade una copia de una diapositiva de diseño especificada a la presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva a clonar. |

Cuando se clona un diseño entre presentaciones diferentes, el maestro del diseño también puede clonarse para mantener el formato de origen. Se utiliza un registro interno para rastrear los maestros clonados automáticamente y evitar la creación de múltiples clones del mismo maestro de diapositiva. La clonación manual de maestros no será ni impedida ni registrada.

**Devuelve:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva añadida.

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Añade una copia de una diapositiva de diseño especificada a la presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva a clonar. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositiva maestra para un nuevo diseño. |

El nuevo diseño se vinculará con el maestro definido en la presentación de destino. Es, por tanto, el análogo de copiar/pegar con la opción “Use Destination Theme” en PowerPoint.

**Devuelve:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva añadida.

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Añade una nueva diapositiva de diseño a la presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositiva maestra para un nuevo diseño. |
| layoutType | byte | Tipo de diseño para un nuevo diseño. Tipos de diseño compatibles: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Otros tipos de diseño no son compatibles actualmente: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nombre para un nuevo diseño. Si el nombre proporcionado ya está en uso se lanzará ArgumentException. Si se pasa null, el nombre se generará automáticamente en función del tipo de diseño proporcionado (por ejemplo "Title Slide" o "1_Title Slide", "2_..", etc.). |

1) Se añadió un diseño para el valor SlideLayoutType.Custom de layoutType que no contiene marcadores de posición ni formas. 2) El análogo de este método es el método [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) accesado mediante la propiedad ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).

**Devuelve:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva añadida.