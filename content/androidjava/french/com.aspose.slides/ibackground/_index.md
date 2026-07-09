---
title: IBackground
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente l'arrière-plan d'une diapositive.
type: docs
url: /fr/com.aspose.slides/ibackground/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
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
| [getStyleIndex()](#getStyleIndex--) | Renvoie un indice du remplissage BackgroundType.Themed dans la collection de thème d'arrière-plan. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Renvoie un indice du remplissage BackgroundType.Themed dans la collection de thème d'arrière-plan. |
| [getEffective()](#getEffective--) | Obtient les données d'arrière-plan effectives avec l'héritage appliqué. |
### getType() {#getType--}
```
public abstract byte getType()
```

Renvoie un type de remplissage d'arrière-plan. Lecture/écriture [BackgroundType](../../com.aspose.slides/backgroundtype).

**Renvoie :**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Renvoie un type de remplissage d'arrière-plan. Lecture/écriture [BackgroundType](../../com.aspose.slides/backgroundtype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Renvoie un FillFormat pour le remplissage BackgroundType.OwnBackground. Lecture seule [IFillFormat](../../com.aspose.slides/ifillformat).

**Renvoie :**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

Renvoie un EffectFormat pour le remplissage BackgroundType.OwnBackground. Lecture seule [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Renvoie :**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```

Renvoie un ColorFormat pour un remplissage BackgroundType.Themed. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```

Renvoie un indice du remplissage BackgroundType.Themed dans la collection de thème d'arrière-plan. 0 signifie aucun remplissage. 1..999 - indice. Lecture/écriture int.

**Renvoie :**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```

Renvoie un indice du remplissage BackgroundType.Themed dans la collection de thème d'arrière-plan. 0 signifie aucun remplissage. 1..999 - indice. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```

Obtient les données d'arrière-plan effectives avec l'héritage appliqué.

**Renvoie :**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - Un [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).