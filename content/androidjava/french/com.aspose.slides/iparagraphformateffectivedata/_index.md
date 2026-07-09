---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides pour Android via la référence API Java
description: Objet immuable qui contient les propriétés de formatage de paragraphe effectif.
type: docs
url: /fr/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

Objet immuable qui contient les propriétés de formatage de paragraphe effectif.

--------------------

Cette interface est utilisée conjointement avec l'interface [IParagraphFormat](../../com.aspose.slides/iparagraphformat) pour renvoyer les valeurs de formatage effectif avec l'héritage appliqué.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBullet()](#getBullet--) | Renvoie un format de puce d'un paragraphe. |
| [getDepth()](#getDepth--) | Renvoie la profondeur d'un paragraphe. |
| [getAlignment()](#getAlignment--) | Renvoie l'alignement du texte dans un paragraphe. |
| [getSpaceWithin()](#getSpaceWithin--) | Renvoie la quantité d'espace entre les lignes de base dans un paragraphe. |
| [getSpaceBefore()](#getSpaceBefore--) | Renvoie la quantité d'espace avant la première ligne d'un paragraphe. |
| [getSpaceAfter()](#getSpaceAfter--) | Renvoie la quantité d'espace après la dernière ligne d'un paragraphe. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Détermine si le saut de ligne asiatique est utilisé dans un paragraphe. |
| [getRightToLeft()](#getRightToLeft--) | Détermine si l'écriture de droite à gauche est utilisée dans un paragraphe. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Détermine si le saut de ligne latin est utilisé dans un paragraphe. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Détermine si la ponctuation suspendue est utilisée dans un paragraphe. |
| [getMarginLeft()](#getMarginLeft--) | Renvoie la marge gauche dans un paragraphe. |
| [getMarginRight()](#getMarginRight--) | Renvoie la marge droite dans un paragraphe. |
| [getIndent()](#getIndent--) | Renvoie le retrait de première ligne/pendant d'un paragraphe. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Renvoie la taille de tabulation par défaut. |
| [getTabs()](#getTabs--) | Renvoie les tabulations d'un paragraphe. |
| [getFontAlignment()](#getFontAlignment--) | Renvoie un alignement de police dans un paragraphe. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Renvoie le format de portion par défaut d'un paragraphe. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```

Renvoie un format de puce d'un paragraphe. Lecture seule [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**Renvoie :**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Renvoie la profondeur d'un paragraphe. Lecture seule short.

**Renvoie :**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Renvoie l'alignement du texte dans un paragraphe. Lecture seule [TextAlignment](../../com.aspose.slides/textalignment).

**Renvoie :**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Renvoie la quantité d'espace entre les lignes de base dans un paragraphe. Lecture seule float.

**Renvoie :**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Renvoie la quantité d'espace avant la première ligne d'un paragraphe. Lecture seule float.

**Renvoie :**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Renvoie la quantité d'espace après la dernière ligne d'un paragraphe. Lecture seule float.

**Renvoie :**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```

Détermine si le saut de ligne asiatique est utilisé dans un paragraphe. Lecture seule boolean.

**Renvoie :**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Détermine si l'écriture de droite à gauche est utilisée dans un paragraphe. Lecture seule boolean.

**Renvoie :**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```

Détermine si le saut de ligne latin est utilisé dans un paragraphe. Lecture seule boolean.

**Renvoie :**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```

Détermine si la ponctuation suspendue est utilisée dans un paragraphe. Lecture seule boolean.

**Renvoie :**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Renvoie la marge gauche dans un paragraphe. Lecture seule float.

**Renvoie :**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Renvoie la marge droite dans un paragraphe. Lecture seule float.

**Renvoie :**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Renvoie le retrait de première ligne/pendant d'un paragraphe. Le retrait pendant peut être défini avec des valeurs négatives. Lecture seule float.

**Renvoie :**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Renvoie la taille de tabulation par défaut. Lecture seule float.

**Renvoie :**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```

Renvoie les tabulations d'un paragraphe. Lecture seule ITabEffectiveData[].

**Renvoie :**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Renvoie un alignement de police dans un paragraphe. Lecture seule [FontAlignment](../../com.aspose.slides/fontalignment).

**Renvoie :**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```

Renvoie le format de portion par défaut d'un paragraphe. Lecture seule [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**Renvoie :**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)