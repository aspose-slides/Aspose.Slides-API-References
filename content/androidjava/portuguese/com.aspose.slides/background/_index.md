---
title: Background
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa o plano de fundo de um slide.
type: docs
url: /pt/com.aspose.slides/background/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

Representa o plano de fundo de um slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [getType()](#getType--) | Retorna um tipo de preenchimento de fundo. |
| [setType(byte value)](#setType-byte-) | Retorna um tipo de preenchimento de fundo. |
| [getFillFormat()](#getFillFormat--) | Retorna um FillFormat para o preenchimento BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | Retorna um EffectFormat para o preenchimento BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | Retorna um ColorFormat para um preenchimento BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | Retorna um índice de preenchimento BackgroundType.Themed na coleção de temas de fundo. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Retorna um índice de preenchimento BackgroundType.Themed na coleção de temas de fundo. |
| [getEffective()](#getEffective--) | Obtém dados de fundo eficazes com a herança aplicada. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Retorna o slide pai de uma forma. |
| [getPresentation()](#getPresentation--) | Retorna a apresentação pai de um slide. |
### getType() {#getType--}
```
public final byte getType()
```

Retorna um tipo de preenchimento de fundo. Leitura/gravação [BackgroundType](../../com.aspose.slides/backgroundtype).

**Retorna:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

Retorna um tipo de preenchimento de fundo. Leitura/gravação [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Retorna um FillFormat para o preenchimento BackgroundType.OwnBackground. Somente leitura [IFillFormat](../../com.aspose.slides/ifillformat).

**Retorna:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Retorna um EffectFormat para o preenchimento BackgroundType.OwnBackground. Somente leitura [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Retorna:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```

Retorna um ColorFormat para um preenchimento BackgroundType.Themed. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```

Retorna um índice de preenchimento BackgroundType.Themed na coleção de temas de fundo. 0 significa sem preenchimento. 1..999 - índice. Leitura/gravação int.

**Retorna:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```

Retorna um índice de preenchimento BackgroundType.Themed na coleção de temas de fundo. 0 significa sem preenchimento. 1..999 - índice. Leitura/gravação int.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```

Obtém dados de fundo eficazes com a herança aplicada.

--------------------

> ```
> This example demonstrates getting effective background properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IBackgroundEffectiveData effectiveBackground = pres.getSlides().get_Item(0).getBackground().getEffective();
>  	System.out.println("Background fill type: " + effectiveBackground.getFillFormat().getFillType());
>  	System.out.println("Any effects applied: " + !effectiveBackground.getEffectFormat().isNoEffects());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versão. Somente leitura long.

**Retorna:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```

Retorna o slide pai de uma forma. Somente leitura [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Retorna:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```

Retorna a apresentação pai de um slide. Somente leitura [IPresentation](../../com.aspose.slides/ipresentation).

**Retorna:**
[Presentation](../../com.aspose.slides/presentation)