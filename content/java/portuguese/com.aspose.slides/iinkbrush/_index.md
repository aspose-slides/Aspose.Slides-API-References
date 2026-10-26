---
title: IInkBrush
second_title: Aspose.Slides for Java API Reference
description: Representa o pincel de traço.
type: docs
url: /pt/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Representa o pincel de traço.
## Métodos

| Método | Descrição |
| --- | --- |
| [getColor()](#getColor--) | Obtém ou define a cor do pincel para uma linha. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Obtém ou define a cor do pincel para uma linha. |
| [getSize()](#getSize--) | Obtém ou define o tamanho do pincel para uma linha em pontos. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Obtém ou define o tamanho do pincel para uma linha em pontos. |
| [getInkEffect()](#getInkEffect--) | Obtém o tipo de efeito de tinta (por exemplo, Galaxy, Gold, Silver) que define o estilo visual do traço de tinta. |
### getColor() {#getColor--}
```
public abstract Color getColor()
```


Obtém ou define a cor do pincel para uma linha.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Color brushColor = brush.getColor();
>      brush.setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```


Obtém ou define a cor do pincel para uma linha.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Color brushColor = brush.getColor();
>      brush.setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.awt.Color |  |

### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```


Obtém ou define o tamanho do pincel para uma linha em pontos.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
java.awt.geom.Dimension2D
### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public abstract void setSize(Dimension2D value)
```


Obtém ou define o tamanho do pincel para uma linha em pontos.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |

### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```


Obtém o tipo de efeito de tinta (por exemplo, Galaxy, Gold, Silver) que define o estilo visual do traço de tinta. O valor é analisado a partir da propriedade do pincel "inkEffects". Se nenhum efeito reconhecido for especificado, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) é retornado.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      Ink ink = (Ink) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkBrush brush = ink.getTraces()[0].getBrush();
>      System.out.println("InkEffects = " + brush.getInkEffect());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
int