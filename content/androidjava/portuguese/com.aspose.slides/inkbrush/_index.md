---
title: InkBrush
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um objeto inkBrush.
type: docs
url: /pt/com.aspose.slides/inkbrush/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

Representa um objeto inkBrush.
## Métodos

| Método | Descrição |
| --- | --- |
| [getColor()](#getColor--) | Obtém ou define a cor do pincel para uma linha. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Obtém ou define a cor do pincel para uma linha. |
| [getSize()](#getSize--) | Obtém ou define o tamanho do pincel para uma linha em pontos. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Obtém ou define o tamanho do pincel para uma linha em pontos. |
| [getInkEffect()](#getInkEffect--) | Obtém o tipo de efeito de tinta (por exemplo, Galaxy, Gold, Silver) que define o estilo visual do traço de tinta. |
### getColor() {#getColor--}
```
public final Integer getColor()
```


Obtém ou define a cor do pincel para uma linha.

--------------------

> ```
> Exemplo:
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
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
```


Obtém ou define a cor do pincel para uma linha.

--------------------

> ```
> Exemplo:
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
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public final SizeF getSize()
```


Obtém ou define o tamanho do pincel para uma linha em pontos.

--------------------

> ```
> Exemplo:
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


**Retorna:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public final void setSize(SizeF value)
```


Obtém ou define o tamanho do pincel para uma linha em pontos.

--------------------

> ```
> Exemplo:
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


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```


Obtém o tipo de efeito de tinta (por exemplo, Galaxy, Gold, Silver) que define o estilo visual do traço de tinta. O valor é analisado a partir da propriedade do pincel "inkEffects". Se nenhum efeito reconhecido for especificado, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) é retornado.

**Retorna:**
int