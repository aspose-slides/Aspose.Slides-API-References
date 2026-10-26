---
title: IInkBrush
second_title: Aspose.Slides for Android via Java API Reference
description: Representa um pincel de traço.
type: docs
url: /pt/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Representa um pincel de traço.
## Methods

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Obtém ou define a cor do pincel para uma linha. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Obtém ou define a cor do pincel para uma linha. |
| [getSize()](#getSize--) | Obtém ou define o tamanho do pincel para uma linha em pontos. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Obtém ou define o tamanho do pincel para uma linha em pontos. |
| [getInkEffect()](#getInkEffect--) | Obtém o tipo de efeito de tinta (por exemplo, Galaxy, Gold, Silver) que define o estilo visual da pincelada. |
### getColor() {#getColor--}
```
public abstract Integer getColor()
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

**Returns:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public abstract SizeF getSize()
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
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public abstract void setSize(SizeF value)
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
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |

### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```


Obtém o tipo de efeito de tinta (por exemplo, Galaxy, Gold, Silver) que define o estilo visual da pincelada. O valor é analisado a partir da propriedade do pincel "inkEffects". Se nenhum efeito reconhecido for especificado, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) é retornado.

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

**Returns:**
int