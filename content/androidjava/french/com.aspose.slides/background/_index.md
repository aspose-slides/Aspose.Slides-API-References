---
title: Background
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente l'arrière-plan d'une diapositive.
type: docs
url: /fr/com.aspose.slides/background/
---
**Héritage:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Toutes les interfaces implémentées:**
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

Représente l'arrière-plan d'une diapositive.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getType()](#getType--) | Renvoie un type de remplissage d'arrière-plan. |
| [setType(byte value)](#setType-byte-) | Renvoie un type de remplissage d'arrière-plan. |
| [getFillFormat()](#getFillFormat--) | Renvoie un FillFormat pour le remplissage BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | Renvoie un EffectFormat pour le remplissage BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | Renvoie un ColorFormat pour un remplissage BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | Renvoie un index du remplissage BackgroundType.Themed dans la collection de thèmes d'arrière-plan. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Renvoie un index du remplissage BackgroundType.Themed dans la collection de thèmes d'arrière-plan. |
| [getEffective()](#getEffective--) | Récupère les données d'arrière-plan effectives avec l'héritage appliqué. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Renvoie la diapositive parente d'une forme. |
| [getPresentation()](#getPresentation--) | Renvoie la présentation parente d'une diapositive. |
### getType() {#getType--}
```
public final byte getType()
```

Renvoie un type de remplissage d'arrière-plan. Lecture/écriture [BackgroundType](../../com.aspose.slides/backgroundtype).

**Renvoie :**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

Renvoie un type de remplissage d'arrière-plan. Lecture/écriture [BackgroundType](../../com.aspose.slides/backgroundtype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Renvoie un FillFormat pour le remplissage BackgroundType.OwnBackground. Lecture seule [IFillFormat](../../com.aspose.slides/ifillformat).

**Renvoie :**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Renvoie un EffectFormat pour le remplissage BackgroundType.OwnBackground. Lecture seule [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Renvoie :**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```

Renvoie un ColorFormat pour un remplissage BackgroundType.Themed. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```

Renvoie un index du remplissage BackgroundType.Themed dans la collection de thèmes d'arrière-plan. 0 signifie aucun remplissage. 1..999 - index. Lecture/écriture int.

**Renvoie :**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```

Renvoie un index du remplissage BackgroundType.Themed dans la collection de thèmes d'arrière-plan. 0 signifie aucun remplissage. 1..999 - index. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```

Récupère les données d'arrière-plan effectives avec l'héritage appliqué.

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

**Returns:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Read-only long.

**Returns:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```

Returns the parent slide of a shape. Read-only [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Returns:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()

Renvoie la présentation parente d'une diapositive. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Renvoie :**
[Presentation](../../com.aspose.slides/presentation)