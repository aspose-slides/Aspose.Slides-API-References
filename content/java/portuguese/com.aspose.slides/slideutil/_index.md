---
title: SlideUtil
second_title: Referência da API Aspose.Slides para Java
description: Oferece métodos que ajudam a buscar formas e texto em uma apresentação.
type: docs
url: /pt/com.aspose.slides/slideutil/
---
**Herança:**
java.lang.Object
```
public class SlideUtil
```

Oferece métodos que ajudam a buscar formas e texto em uma apresentação.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | Localiza forma pelo texto alternativo em uma apresentação PPTX. |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | Localiza forma pelo texto alternativo em um slide de uma apresentação PPTX. |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | Procura todas as formas no slide especificado que correspondem ao tipo de placeholder fornecido. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | Altera a posição de todas as formas no slide. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | Altera a posição das formas selecionadas no slide. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | Altera a posição de todas as formas dentro de um grupo de formas. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | Altera a posição das formas selecionadas dentro do grupo de formas. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | Localiza e substitui texto na apresentação com o formato fornecido |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | Localiza e substitui texto na apresentação com o formato fornecido |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | Retorna todos os quadros de texto em um slide em uma apresentação PPTX. |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | Retorna todos os quadros de texto no slide especificado que contêm o texto fornecido. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | Retorna todos os quadros de texto em uma apresentação PPTX. |
| [toSaveFormat(int format)](#toSaveFormat-int-) | Converte um formato de arquivo de origem para o [SaveFormat](../../com.aspose.slides/saveformat) correspondente. |
### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```


### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```


Localiza forma pelo texto alternativo em uma apresentação PPTX.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Apresentação escaneada. |
| altText | java.lang.String | Texto alternativo de uma forma. |

**Retorno:**
[IShape](../../com.aspose.slides/ishape) - Forma ou nulo.
### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```


Localiza forma pelo texto alternativo em um slide em uma apresentação PPTX.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slide escaneado. |
| altText | java.lang.String | Texto alternativo de uma forma. |

**Retorno:**
[IShape](../../com.aspose.slides/ishape) - Forma ou nulo.
### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```


Procura todas as formas no slide especificado que correspondem ao tipo de placeholder fornecido.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | O slide onde buscar as formas. |
| placeholderType | byte | O tipo de placeholder para filtrar as formas. |

**Retorno:**
com.aspose.slides.IShape[] - Um array de objetos [IShape](../../com.aspose.slides/ishape) que correspondem ao tipo de placeholder especificado.
### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```


Altera a posição de todas as formas no slide. Alinha as formas às margens ou à borda do slide ou alinha-as entre si.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| alignmentType | int | Determina qual tipo de alinhamento será aplicado. |
| alignToSlide | boolean | Se true, as formas serão alinhadas em relação às bordas do slide. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slide pai. |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```


Altera a posição das formas selecionadas no slide. Alinha as formas às margens ou à borda do slide ou alinha-as entre si.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| alignmentType | int | Determina qual tipo de alinhamento será aplicado. |
| alignToSlide | boolean | Se true, as formas serão alinhadas em relação às bordas do slide. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slide pai. |
| shapeIndexes | int[] | Índices das formas a serem alinhadas. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```


Altera a posição de todas as formas dentro do grupo de formas. Alinha as formas às margens ou à borda do slide ou alinha-as entre si.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| alignmentType | int | Determina qual tipo de alinhamento será aplicado. |
| alignToSlide | boolean | Se true, as formas serão alinhadas em relação às bordas do slide. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Grupo de formas pai. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```


Altera a posição das formas selecionadas dentro do grupo de formas. Alinha as formas às margens ou à borda do slide ou alinha-as entre si.

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| alignmentType | int | Determina qual tipo de alinhamento será aplicado. |
| alignToSlide | boolean | Se true, as formas serão alinhadas em relação às bordas do slide. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Grupo de formas pai. |
| shapeIndexes | int[] | Índices das formas a serem alinhadas. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```


Localiza e substitui texto na apresentação com o formato fornecido

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Apresentação escaneada. |
| withMasters | boolean | Determina se os slides mestres devem ser escaneados. |
| find | java.lang.String | Valor da string a encontrar. |
| replace | java.lang.String | Valor da string a substituir. Caractere da string encontrada |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```


Localiza e substitui texto na apresentação com o formato fornecido

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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Apresentação escaneada. |
| withMasters | boolean | Determina se os slides mestres devem ser escaneados. |
| find | java.lang.String | Valor da string a encontrar. |
| replace | java.lang.String | Valor da string a substituir. |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | Formato para substituir a porção de texto. Se null, será usado o formato do primeiro caractere da string encontrada |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```


Retorna todos os quadros de texto em um slide em uma apresentação PPTX.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Slide escaneado. |

**Retorno:**
com.aspose.slides.ITextFrame[] - Um array de objetos [TextFrame](../../com.aspose.slides/textframe).

### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```


Retorna todos os quadros de texto no slide especificado que contêm o texto fornecido.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | O slide onde buscar. |
| text | java.lang.String | O texto a ser procurado nos quadros de texto. |
| checkPlaceholderText | boolean | Indica se devem ser incluídos quadros de texto vazios, mas cujo texto placeholder contém o texto pesquisado. |

**Retorno:**
com.aspose.slides.ITextFrame[] - Um array de objetos [ITextFrame](../../com.aspose.slides/itextframe) que contêm o texto especificado.

### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```


Retorna todos os quadros de texto em uma apresentação PPTX.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Apresentação escaneada. |
| withMasters | boolean | Determina se os slides mestres devem ser escaneados. |

**Retorno:**
com.aspose.slides.ITextFrame[] - Um array de objetos [TextFrame](../../com.aspose.slides/textframe).

### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```


Converte um formato de arquivo de origem para o [SaveFormat](../../com.aspose.slides/saveformat) correspondente.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| format | int | O formato de arquivo de origem. |

**Retorno:**
int - O valor [SaveFormat](../../com.aspose.slides/saveformat) correspondente.