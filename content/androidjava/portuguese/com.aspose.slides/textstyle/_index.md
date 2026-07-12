---
title: TextStyle
second_title: Aspose.Slides para Android via Referência da API Java
description: Esta classe contém as propriedades de formatação de estilo de texto.
type: docs
url: /pt/com.aspose.slides/textstyle/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ITextStyle](../../com.aspose.slides/itextstyle), com.aspose.slides.IStyleColorOwner
```
public final class TextStyle extends PVIObject implements ITextStyle, IStyleColorOwner
```

Esta classe contém as propriedades de formatação de estilo de texto.
## Métodos

| Método | Descrição |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLevel(int index)](#getLevel-int-) | Se o nível de estilo existir, retorna-o; caso contrário, retorna null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Propriedades padrão do parágrafo. |
| [getEffective()](#getEffective--) | Obtém os dados de formatação de estilo de texto efetiva com a herança aplicada. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versão. Long somente leitura.

**Retorna:**
long
### getLevel(int index) {#getLevel-int-}
```
public final IParagraphFormat getLevel(int index)
```


Se o nível de estilo existir, retorna-o; caso contrário, retorna null.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice baseado em zero do nível. Deve estar no intervalo 0..8. |

**Retorna:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Formatação do nível [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public final IParagraphFormat getDefaultParagraphFormat()
```


Propriedades padrão do parágrafo. Somente leitura [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Retorna:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public final ITextStyleEffectiveData getEffective()
```


Obtém os dados de formatação de estilo de texto efetiva com a herança aplicada.

--------------------

> ```
> This example demonstrates getting some of effective text style properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextStyleEffectiveData effectiveTextStyle = shape.getTextFrame().getTextFrameFormat().getTextStyle().getEffective();
>      for (int i = 0; i <= 8; i++)
>      {
>          IParagraphFormatEffectiveData effectiveStyleLevel = effectiveTextStyle.getLevel(i);
>          System.out.println("= Effective paragraph formatting for style level #" + i + " =");
>          System.out.println("Depth: " + effectiveStyleLevel.getDepth());
>          System.out.println("Indent: " + effectiveStyleLevel.getIndent());
>          System.out.println("Alignment: " + effectiveStyleLevel.getAlignment());
>          System.out.println("Font alignment: " + effectiveStyleLevel.getFontAlignment());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Um [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).