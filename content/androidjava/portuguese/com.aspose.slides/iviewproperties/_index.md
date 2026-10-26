---
title: IViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Propriedades de visualização de toda a apresentação.
type: docs
url: /pt/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

Propriedades de visualização de toda a apresentação.
## Métodos

| Método | Descrição |
| --- | --- |
| [getLastView()](#getLastView--) | Especifica o modo de visualização que foi usado quando o documento de apresentação foi salvo pela última vez. |
| [setLastView(int value)](#setLastView-int-) | Especifica o modo de visualização que foi usado quando o documento de apresentação foi salvo pela última vez. |
| [getShowComments()](#getShowComments--) | Especifica se os comentários do slide devem ser exibidos. |
| [setShowComments(byte value)](#setShowComments-byte-) | Especifica se os comentários do slide devem ser exibidos. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Especifica propriedades de visualização comuns associadas ao modo de visualização do slide. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Especifica propriedades de visualização comuns associadas ao modo de visualização das notas. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Representa propriedades de visualização normais. |
| [getGridSpacing()](#getGridSpacing--) | Retorna ou define o espaçamento da grade que deve ser usado para a grade subjacente ao documento de apresentação, em pontos. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Retorna ou define o espaçamento da grade que deve ser usado para a grade subjacente ao documento de apresentação, em pontos. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```


Especifica o modo de visualização que foi usado quando o documento de apresentação foi salvo pela última vez. Leitura/Gravação [ViewType](../../com.aspose.slides/viewtype).

**Retorna:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```


Especifica o modo de visualização que foi usado quando o documento de apresentação foi salvo pela última vez. Leitura/Gravação [ViewType](../../com.aspose.slides/viewtype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```


Especifica se os comentários do slide devem ser exibidos. Leitura/Gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Retorna:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```


Especifica se os comentários do slide devem ser exibidos. Leitura/Gravação [NullableBool](../../com.aspose.slides/nullablebool).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```


Especifica propriedades de visualização comuns associadas ao modo de visualização do slide. Somente leitura [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Retorna:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```


Especifica propriedades de visualização comuns associadas ao modo de visualização das notas. Somente leitura [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Retorna:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```


Representa propriedades de visualização normais. A visualização normal consiste em três regiões de conteúdo: o próprio slide, uma região de conteúdo lateral e uma região de conteúdo inferior. Somente leitura [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Retorna:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```


Retorna ou define o espaçamento da grade que deve ser usado para a grade subjacente ao documento de apresentação, em pontos. Leitura/Gravação float.

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
public abstract void setGridSpacing(float value)
```


Retorna ou define o espaçamento da grade que deve ser usado para a grade subjacente ao documento de apresentação, em pontos. Leitura/Gravação float.

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