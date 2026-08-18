---
title: SlideUtil
second_title: Referencia de API de Aspose.Slides para Java
description: Ofrece métodos que ayudan a buscar formas y texto en una presentación.
type: docs
url: /es/com.aspose.slides/slideutil/
---
**Herencia:**
java.lang.Object
```
public class SlideUtil
```

Offer methods which help to search shapes and text in a presentation.
## Constructors

| Constructor | Descripción |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |
## Methods

| Método | Descripción |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | Buscar forma por texto alternativo en una presentación PPTX. |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | Buscar forma por texto alternativo en una diapositiva de una presentación PPTX. |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | Busca todas las formas en la diapositiva especificada que coincidan con el tipo de marcador de posición dado. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | Cambia la ubicación de todas las formas en la diapositiva. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | Cambia la ubicación de las formas seleccionadas en la diapositiva. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | Cambia la ubicación de todas las formas dentro del grupo de formas. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | Cambia la ubicación de las formas seleccionadas dentro del grupo de formas. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | Busca y reemplaza texto en la presentación con el formato dado. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | Busca y reemplaza texto en la presentación con el formato dado. |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | Devuelve todos los marcos de texto en una diapositiva de una presentación PPTX. |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | Devuelve todos los marcos de texto en la diapositiva especificada que contienen el texto dado. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | Devuelve todos los marcos de texto en una presentación PPTX. |
| [toSaveFormat(int format)](#toSaveFormat-int-) | Convierte un formato de archivo fuente al [SaveFormat](../../com.aspose.slides/saveformat) correspondiente. |
### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```


### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```

Busca forma por texto alternativo en una presentación PPTX.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Presentación escaneada. |
| altText | java.lang.String | Texto alternativo de una forma. |

**Devuelve:**
[IShape](../../com.aspose.slides/ishape) - Shape o null.
### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```

Busca forma por texto alternativo en una diapositiva de una presentación PPTX.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Diapositiva escaneada. |
| altText | java.lang.String | Texto alternativo de una forma. |

**Devuelve:**
[IShape](../../com.aspose.slides/ishape) - Shape o null.
### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```

Busca todas las formas en la diapositiva especificada que coincidan con el tipo de marcador de posición dado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | La diapositiva donde buscar formas. |
| placeholderType | byte | El tipo de marcador de posición por el cual filtrar las formas. |

**Devuelve:**
com.aspose.slides.IShape[] - una matriz de objetos [IShape](../../com.aspose.slides/ishape) que coinciden con el tipo de marcador de posición especificado.
### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```

Cambia la ubicación de todas las formas en la diapositiva. Alinea las formas a los márgenes o al borde de la diapositiva o las alinea entre sí.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignBottom, true, pres.getSlides().get_Item(0));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alignmentType | int | Determina qué tipo de alineación se aplicará. |
| alignToSlide | boolean | Si es true, las formas se alinearán respecto a los bordes de la diapositiva. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Diapositiva principal. |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```

Cambia la ubicación de las formas seleccionadas en la diapositiva. Alinea las formas a los márgenes o al borde de la diapositiva o las alinea entre sí.

--------------------

> ```
> Example:
>   
>   Presentation pres = new Presentation("pres.pptx");
>   try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape1 = slide.getShapes().get_Item(0);
>      IShape shape2 = slide.getShapes().get_Item(1);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignBottom, false, pres.getSlides().get_Item(0), new int[]
>      {
>          slide.getShapes().indexOf(shape1),
>          slide.getShapes().indexOf(shape2)
>      });
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alignmentType | int | Determina qué tipo de alineación se aplicará. |
| alignToSlide | boolean | Si es true, las formas se alinearán respecto a los bordes de la diapositiva. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Diapositiva principal. |
| shapeIndexes | int[] | Índices de las formas que se alinearán. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```

Cambia la ubicación de todas las formas dentro del grupo de formas. Alinea las formas a los márgenes o al borde de la diapositiva o las alinea entre sí.

--------------------

> ```
> Ejemplo:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape) slide.getShapes().get_Item(0));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alignmentType | int | Determina qué tipo de alineación se aplicará. |
| alignToSlide | boolean | Si es true, las formas se alinearán respecto a los bordes de la diapositiva. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Grupo de formas principal. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```

Cambia la ubicación de las formas seleccionadas dentro del grupo de formas. Alinea las formas a los márgenes o al borde de la diapositiva o las alinea entre sí.

--------------------

> ```
> Ejemplo:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.getShapes().get_Item(0), new int[] { 0, 2 });
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alignmentType | int | Determina qué tipo de alineación se aplicará. |
| alignToSlide | boolean | Si es true, las formas se alinearán respecto a los bordes de la diapositiva. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Grupo de formas principal. |
| shapeIndexes | int[] | Índices de las formas que se alinearán. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```

Busca y reemplaza texto en la presentación con el formato dado.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PortionFormat format = new PortionFormat();
>      format.setFontHeight(24f);
>      format.setFontItalic(NullableBool.True);
>      format.getFillFormat().setFillType(FillType.Solid);
>      format.getFillFormat().getSolidFillColor().setColor(Color.RED);
> 
>      SlideUtil.findAndReplaceText(pres, true, "[this block] ", "my text ", format);
>      pres.save("replaced.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentación escaneada. |
| withMasters | boolean | Determina si se deben escanear las diapositivas maestras. |
| find | java.lang.String | Valor de cadena a buscar. |
| replace | java.lang.String | Valor de cadena para reemplazar. carácter de la cadena encontrada |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```

Busca y reemplaza texto en la presentación con el formato dado.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PortionFormat format = new PortionFormat();
>      format.setFontHeight(24f);
>      format.setFontItalic(NullableBool.True);
>      format.getFillFormat().setFillType(FillType.Solid);
>      format.getFillFormat().getSolidFillColor().setColor(Color.RED);
> 
>      SlideUtil.findAndReplaceText(pres, true, "[this block] ", "my text ", format);
>      pres.save("replaced.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentación escaneada. |
| withMasters | boolean | Determina si se deben escanear las diapositivas maestras. |
| find | java.lang.String | Valor de cadena a buscar. |
| replace | java.lang.String | Valor de cadena para reemplazar. |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | Formato para reemplazar la porción de texto. Si es null se usará el formato del primer carácter de la cadena encontrada |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```

Devuelve todos los marcos de texto en una diapositiva de una presentación PPTX.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Diapositiva escaneada. |

**Devuelve:**
com.aspose.slides.ITextFrame[] - Matriz de objetos [TextFrame](../../com.aspose.slides/textframe).
### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```

Devuelve todos los marcos de texto en la diapositiva especificada que contienen el texto dado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | La diapositiva a buscar. |
| text | java.lang.String | El texto a buscar dentro de los marcos de texto. |
| checkPlaceholderText | boolean | Indica si se deben incluir los marcos de texto que están vacíos, pero cuyo texto de marcador de posición contiene el texto buscado. |

**Devuelve:**
com.aspose.slides.ITextFrame[] - Matriz de objetos [ITextFrame](../../com.aspose.slides/itextframe) que contienen el texto especificado.
### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```

Devuelve todos los marcos de texto en una presentación PPTX.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Presentación escaneada. |
| withMasters | boolean | Determina si se deben escanear las diapositivas maestras. |

**Devuelve:**
com.aspose.slides.ITextFrame[] - Matriz de objetos [TextFrame](../../com.aspose.slides/textframe).
### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```

Convierte un formato de archivo fuente al [SaveFormat](../../com.aspose.slides/saveformat) correspondiente.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| format | int | El formato de archivo fuente. |

**Devuelve:**
int - El valor [SaveFormat](../../com.aspose.slides/saveformat) correspondiente.