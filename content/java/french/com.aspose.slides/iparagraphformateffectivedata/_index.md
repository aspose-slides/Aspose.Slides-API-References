---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Objet immuable qui contient les propriétés de mise en forme de paragraphe effectives.
type: docs
url: /fr/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

Objet immuable qui contient les propriétés de mise en forme de paragraphe effectives.

--------------------

Cette interface est utilisée conjointement avec l'interface [IParagraphFormat](../../com.aspose.slides/iparagraphformat) pour renvoyer les valeurs de mise en forme effectives avec l'héritage appliqué.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBullet()](#getBullet--) | Renvoie un format de puce d'un paragraphe. |
| [getDepth()](#getDepth--) | Renvoie la profondeur d'un paragraphe. |
| [getAlignment()](#getAlignment--) | Renvoie l'alignement du texte dans un paragraphe. |
| [getSpaceWithin()](#getSpaceWithin--) | Renvoie la quantité d'espace entre les lignes de base dans un paragraphe. |
| [getSpaceBefore()](#getSpaceBefore--) | Renvoie la quantité d'espace avant la première ligne d'un paragraphe. |
| [getSpaceAfter()](#getSpaceAfter--) | Renvoie la quantité d'espace après la dernière ligne d'un paragraphe. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Détermine si le saut de ligne d'Asie de l'Est est utilisé dans un paragraphe. |
| [getRightToLeft()](#getRightToLeft--) | Détermine si l'écriture de droite à gauche est utilisée dans un paragraphe. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Détermine si le saut de ligne latin est utilisé dans un paragraphe. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Détermine si la ponctuation suspendue est utilisée dans un paragraphe. |
| [getMarginLeft()](#getMarginLeft--) | Renvoie la marge gauche dans un paragraphe. |
| [getMarginRight()](#getMarginRight--) | Renvoie la marge droite dans un paragraphe. |
| [getIndent()](#getIndent--) | Renvoie le retrait de première ligne/retrait suspendu du paragraphe. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Renvoie la taille de tabulation par défaut. |
| [getTabs()](#getTabs--) | Renvoie les tabulations d'un paragraphe. |
| [getFontAlignment()](#getFontAlignment--) | Renvoie l'alignement de police dans un paragraphe. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Renvoie le format de portion par défaut d'un paragraphe. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```

Renvoie un format de puce d'un paragraphe. Lecture seule [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**Retour :**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Renvoie la profondeur d'un paragraphe. Lecture seule short.

**Retour :**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Renvoie l'alignement du texte dans un paragraphe. Lecture seule [TextAlignment](../../com.aspose.slides/textalignment).

**Retour :**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Renvoie la quantité d'espace entre les lignes de base dans un paragraphe. Lecture seule float.

**Retour :**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Renvoie la quantité d'espace avant la première ligne d'un paragraphe. Lecture seule float.

**Retour :**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Renvoie la quantité d'espace après la dernière ligne d'un paragraphe. Lecture seule float.

**Retour :**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```

Détermine si le saut de ligne d'Asie de l'Est est utilisé dans un paragraphe. Lecture seule boolean.

**Retour :**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Détermine si l'écriture de droite à gauche est utilisée dans un paragraphe. Lecture seule boolean.

**Retour :**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```

Détermine si le saut de ligne latin est utilisé dans un paragraphe. Lecture seule boolean.

**Retour :**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```

Détermine si la ponctuation suspendue est utilisée dans un paragraphe. Lecture seule boolean.

**Retour :**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Renvoie la marge gauche dans un paragraphe. Lecture seule float.

**Retour :**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Renvoie la marge droite dans un paragraphe. Lecture seule float.

**Retour :**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Renvoie le retrait de première ligne/retrait suspendu du paragraphe. Le retrait suspendu peut être défini avec des valeurs négatives. Lecture seule float.

**Retour :**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Renvoie la taille de tabulation par défaut. Lecture seule float.

**Retour :**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```

Renvoie les tabulations d'un paragraphe. Lecture seule ITabEffectiveData[].

**Retour :**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Renvoie l'alignement de police dans un paragraphe. Lecture seule [FontAlignment](../../com.aspose.slides/fontalignment).

**Retour :**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```

Renvoie le format de portion par défaut d'un paragraphe. Lecture seule [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**Retour :**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)