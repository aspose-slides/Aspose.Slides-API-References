---
title: SlideUtil
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Ofrece métodos que ayudan a buscar formas y texto en una presentación.
type: docs
url: /es/com.aspose.slides/slideutil/
---
**Inheritance:**
java.lang.Object
```
public class SlideUtil
```

Ofrece métodos que ayudan a buscar formas y texto en una presentación.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | Find shape by alternative text in a PPTX presentation. |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | Find shape by alternative text on a slide in a PPTX presentation. |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | Searches for all shapes on the specified slide that match the given placeholder type. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | Changes the placement of all shapes on the slide. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | Changes the placement of selected shapes on the slide. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | Changes the placement of all shapes within group shape. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | Changes the placement of selected shapes within group shape. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | Finds and replaces text in presentation with given format |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | Finds and replaces text in presentation with given format |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | Returns all text frames on a slide in a PPTX presentation. |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | Returns all text frames on the specified slide that contain the given text. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | Returns all text frames in a PPTX presentation. |
| [toSaveFormat(int format)](#toSaveFormat-int-) | Converts a source file format to the corresponding [SaveFormat](../../com.aspose.slides/saveformat). |

### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```

### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```

Encuentra la forma por texto alternativo en una presentación PPTX.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Presentación escaneada. |
| altText | java.lang.String | Texto alternativo de una forma. |

**Devuelve:**
[IShape](../../com.aspose.slides/ishape) - Shape o nulo.

### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```

Encuentra la forma por texto alternativo en una diapositiva de una presentación PPTX.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Diapositiva escaneada. |
| altText | java.lang.String | Texto alternativo de una forma. |

**Devuelve:**
[IShape](../../com.aspose.slides/ishape) - Shape o nulo.

### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```

Busca todas las formas en la diapositiva especificada que coincidan con el tipo de marcador de posición proporcionado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | La diapositiva donde buscar formas. |
| placeholderType | byte | El tipo de marcador de posición por el cual filtrar las formas. |

**Devuelve:**
com.aspose.slides.IShape[] - Una matriz de [IShape](../../com.aspose.slides/ishape) objetos que coinciden con el tipo de marcador de posición especificado.

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```

Cambia la posición de todas las formas en la diapositiva. Alinea las formas a los márgenes o al borde de la diapositiva o las alinea entre sí.

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

Cambia la posición de las formas seleccionadas en la diapositiva. Alinea las formas a los márgenes o al borde de la diapositiva o las alinea entre sí.

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

Cambia la posición de todas las formas dentro del grupo. Alinea las formas a los márgenes o al borde de la diapositiva o las alinea entre sí.

--------------------

> ```
> Example:
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
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Grupo de forma principal. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```

Cambia la posición de las formas seleccionadas dentro del grupo. Alinea las formas a los márgenes o al borde de la diapositiva o las alinea entre sí.

--------------------

> ```
> Example:
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
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Grupo de forma principal. |
| shapeIndexes | int[] | Índices de las formas que se alinearán. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```

Encuentra y reemplaza texto en la presentación con el formato dado.

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

Encuentra y reemplaza texto en la presentación con el formato dado.

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
| format | [PortionFormat](../../com.aspose.slides/portionformat) | Formato para el fragmento de texto que se reemplaza. Si es null se usará el formato del primer carácter de la cadena encontrada |

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
com.aspose.slides.ITextFrame[] - Matriz de [TextFrame](../../com.aspose.slides/textframe) objetos.

### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```

Devuelve todos los marcos de texto en la diapositiva especificada que contengan el texto proporcionado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | La diapositiva donde buscar. |
| text | java.lang.String | El texto a buscar dentro de los marcos de texto. |
| checkPlaceholderText | boolean | Indica si se deben incluir los marcos de texto vacíos cuyo texto de marcador de posición contenga el texto buscado. |

**Devuelve:**
com.aspose.slides.ITextFrame[] - Una matriz de [ITextFrame](../../com.aspose.slides/itextframe) objetos que contienen el texto especificado.

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
com.aspose.slides.ITextFrame[] - Matriz de [TextFrame](../../com.aspose.slides/textframe) objetos.

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