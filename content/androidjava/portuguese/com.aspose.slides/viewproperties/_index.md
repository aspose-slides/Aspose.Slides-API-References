---
title: ViewProperties
second_title: Aspose.Slides para Android via Referência da API Java
description: Propriedades de visualização de toda a apresentação.
type: docs
url: /pt/com.aspose.slides/viewproperties/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

Propriedades de visualização de toda a apresentação.
## Métodos

| Método | Descrição |
| --- | --- |
| [getLastView()](#getLastView--) | Especifica o modo de visualização que foi usado quando o documento de apresentação foi salvo pela última vez. |
| [setLastView(int value)](#setLastView-int-) | Especifica o modo de visualização que foi usado quando o documento de apresentação foi salvo pela última vez. |
| [getShowComments()](#getShowComments--) | Especifica se os comentários do slide devem ser exibidos. |
| [setShowComments(byte value)](#setShowComments-byte-) | Especifica se os comentários do slide devem ser exibidos. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Representa propriedades de visualização normal. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Especifica propriedades de visualização comuns associadas ao modo de visualização de slide. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Especifica propriedades de visualização comuns associadas ao modo de visualização de notas. |
| [getGridSpacing()](#getGridSpacing--) | Retorna ou define o espaçamento da grade que deve ser usado para a grade subjacente ao documento de apresentação, em pontos. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Retorna ou define o espaçamento da grade que deve ser usado para a grade subjacente ao documento de apresentação, em pontos. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getLastView() {#getLastView--}
```
public final int getLastView()
```

Especifica o modo de visualização que foi usado quando o documento de apresentação foi salvo pela última vez. Leitura/gravação [ViewType](../../com.aspose.slides/viewtype).

**Retorna:**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

Especifica o modo de visualização que foi usado quando o documento de apresentação foi salvo pela última vez. Leitura/gravação [ViewType](../../com.aspose.slides/viewtype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

Especifica se os comentários do slide devem ser exibidos. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

Especifica se os comentários do slide devem ser exibidos. Leitura/gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

Representa propriedades de visualização normal. A visualização normal consiste em três regiões de conteúdo: o próprio slide, uma região de conteúdo lateral e uma região de conteúdo inferior. Somente leitura [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Retorna:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

Especifica propriedades de visualização comuns associadas ao modo de visualização de slide. Somente leitura [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Retorna:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

Especifica propriedades de visualização comuns associadas ao modo de visualização de notas. Somente leitura [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Retorna:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

Retorna ou define o espaçamento da grade que deve ser usado para a grade subjacente ao documento de apresentação, em pontos. Leitura/gravação float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

O valor do espaçamento da grade deve ser um número positivo. O intervalo típico varia de 1 mm (2.8349607 pontos) a 2 polegadas (144 pontos).

**Retorna:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```

Retorna ou define o espaçamento da grade que deve ser usado para a grade subjacente ao documento de apresentação, em pontos. Leitura/gravação float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

O valor do espaçamento da grade deve ser um número positivo. O intervalo típico varia de 1 mm (2.8349607 pontos) a 2 polegadas (144 pontos).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject