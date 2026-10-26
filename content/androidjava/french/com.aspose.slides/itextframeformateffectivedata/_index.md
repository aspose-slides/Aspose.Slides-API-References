---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides pour Android via la référence API Java
description: Objet immuable qui contient les propriétés de formatage effectif du cadre de texte.
type: docs
url: /fr/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

Objet immuable qui contient les propriétés de formatage effectif du cadre de texte.

--------------------

Cette interface est utilisée avec l'interface [ITextFrameFormat](../../com.aspose.slides/itextframeformat) pour renvoyer les valeurs de formatage effectif avec l'héritage appliqué.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Renvoie le style effectif du texte. |
| [getMarginLeft()](#getMarginLeft--) | Renvoie la marge gauche (points) dans un TextFrame. |
| [getMarginRight()](#getMarginRight--) | Renvoie la marge droite (points) dans un TextFrame. |
| [getMarginTop()](#getMarginTop--) | Renvoie la marge supérieure (points) dans un TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Renvoie la marge inférieure (points) dans un TextFrame. |
| [getWrapText()](#getWrapText--) | Renvoie si le texte est renvoyé aux marges du TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Renvoie le texte d'ancrage vertical dans un TextFrame. |
| [getCenterText()](#getCenterText--) | Renvoie si le texte doit être centré horizontalement dans la boîte. |
| [getTextVerticalType()](#getTextVerticalType--) | Renvoie l'orientation du texte. |
| [getAutofitType()](#getAutofitType--) | Renvoie le mode d'ajustement automatique du texte. |
| [getColumnCount()](#getColumnCount--) | Spécifie le nombre de colonnes de texte dans le rectangle englobant. |
| [getColumnSpacing()](#getColumnSpacing--) | Spécifie l'espace entre les colonnes de texte dans la zone de texte (en points). |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```


Renvoie le style effectif du texte. Lecture seule [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**Retour :**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


Renvoie la marge gauche (points) dans un TextFrame. Lecture seule double.

**Retour :**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


Renvoie la marge droite (points) dans un TextFrame. Lecture seule double.

**Retour :**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


Renvoie la marge supérieure (points) dans un TextFrame. Lecture seule double.

**Retour :**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


Renvoie la marge inférieure (points) dans un TextFrame. Lecture seule double.

**Retour :**
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```


Renvoie si le texte est renvoyé aux marges du TextFrame. Lecture seule boolean.

**Retour :**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


Renvoie le texte d'ancrage vertical dans un TextFrame. Lecture seule [TextAnchorType](../../com.aspose.slides/textanchortype).

**Retour :**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```


Renvoie si le texte doit être centré horizontalement dans la boîte. Lecture seule boolean.

**Retour :**
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


Renvoie l'orientation du texte. Lecture seule [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Retour :**
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


Renvoie le mode d'ajustement automatique du texte. Lecture seule [TextAutofitType](../../com.aspose.slides/textautofittype).

**Retour :**
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


Spécifie le nombre de colonnes de texte dans le rectangle englobant. Lecture seule int.

**Retour :**
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```


Spécifie l'espace entre les colonnes de texte dans la zone de texte (en points). Lecture seule float.

**Retour :**
float