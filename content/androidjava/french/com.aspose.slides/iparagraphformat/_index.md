---
title: IParagraphFormat
second_title: Aspose.Slides for Android via Java API Reference
description: This class contains the paragraph formatting properties.
type: docs
url: /fr/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

Cette classe contient les propriétés de formatage de paragraphe. Contrairement à [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata), toutes les propriétés de cette classe sont modifiables.

--------------------

Cette classe est utilisée pour renvoyer et manipuler les propriétés de formatage de paragraphe définies pour le paragraphe particulier. Cela signifie qu'aucun héritage n'est appliqué lors de la récupération des valeurs, de sorte que dans la plupart des cas vous obtiendrez des valeurs signifiant « indéfini ».

Afin d'obtenir les valeurs de paramètres de formatage effectifs, y compris hérités, vous devez utiliser la méthode [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) qui renvoie une instance [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

## Méthodes

| Méthode | Description |
| --- | --- |
| [getBullet()](#getBullet--) | Renvoie le format de puce du paragraphe. |
| [getDepth()](#getDepth--) | Renvoie ou définit la profondeur du paragraphe. |
| [setDepth(short value)](#setDepth-short-) | Renvoie ou définit la profondeur du paragraphe. |
| [getAlignment()](#getAlignment--) | Renvoie ou définit l'alignement du texte dans un paragraphe sans héritage. |
| [setAlignment(int value)](#setAlignment-int-) | Renvoie ou définit l'alignement du texte dans un paragraphe sans héritage. |
| [getSpaceWithin()](#getSpaceWithin--) | Renvoie ou définit la quantité d'espace entre les lignes de base dans un paragraphe. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Renvoie ou définit la quantité d'espace entre les lignes de base dans un paragraphe. |
| [getSpaceBefore()](#getSpaceBefore--) | Renvoie ou définit la quantité d'espace avant la première ligne d'un paragraphe sans héritage. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Renvoie ou définit la quantité d'espace avant la première ligne d'un paragraphe sans héritage. |
| [getSpaceAfter()](#getSpaceAfter--) | Renvoie ou définit la quantité d'espace après la dernière ligne d'un paragraphe sans héritage. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Renvoie ou définit la quantité d'espace après la dernière ligne d'un paragraphe sans héritage. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Détermine si le saut de ligne asiatique est utilisé dans un paragraphe. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Détermine si le saut de ligne asiatique est utilisé dans un paragraphe. |
| [getRightToLeft()](#getRightToLeft--) | Détermine si l'écriture de droite à gauche est utilisée dans un paragraphe. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Détermine si l'écriture de droite à gauche est utilisée dans un paragraphe. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Détermine si le saut de ligne latin est utilisé dans un paragraphe. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Détermine si le saut de ligne latin est utilisé dans un paragraphe. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Détermine si la ponctuation suspendue est utilisée dans un paragraphe. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Détermine si la ponctuation suspendue est utilisée dans un paragraphe. |
| [getMarginLeft()](#getMarginLeft--) | Renvoie ou définit la marge gauche dans un paragraphe sans héritage. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Renvoie ou définit la marge gauche dans un paragraphe sans héritage. |
| [getMarginRight()](#getMarginRight--) | Renvoie ou définit la marge droite dans un paragraphe sans héritage. |
| [setMarginRight(float value)](#setMarginRight-float-) | Renvoie ou définit la marge droite dans un paragraphe sans héritage. |
| [getIndent()](#getIndent--) | Renvoie ou définit le retrait de première ligne / retrait suspendu du paragraphe sans héritage. |
| [setIndent(float value)](#setIndent-float-) | Renvoie ou définit le retrait de première ligne / retrait suspendu du paragraphe sans héritage. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Renvoie ou définit la taille d'onglet par défaut sans héritage. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Renvoie ou définit la taille d'onglet par défaut sans héritage. |
| [getTabs()](#getTabs--) | Renvoie les tabulations d'un paragraphe. |
| [getFontAlignment()](#getFontAlignment--) | Renvoie ou définit l'alignement de police dans un paragraphe sans héritage. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Renvoie ou définit l'alignement de police dans un paragraphe sans héritage. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Renvoie le format de portion par défaut d'un paragraphe. |
| [getEffective()](#getEffective--) | Obtient les données de formatage de paragraphe effectives avec l'héritage appliqué. |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

Renvoie le format de puce du paragraphe. Lecture seule [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Retour :**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Renvoie ou définit la profondeur du paragraphe. La valeur 0 signifie valeur indéfinie. Lecture/écriture short.

**Retour :**
short

### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

Renvoie ou définit la profondeur du paragraphe. La valeur 0 signifie valeur indéfinie. Lecture/écriture short.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Renvoie ou définit l'alignement du texte dans un paragraphe sans héritage. Lecture/écriture [TextAlignment](../../com.aspose.slides/textalignment).

**Retour :**
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

Renvoie ou définit l'alignement du texte dans un paragraphe sans héritage. Lecture/écriture [TextAlignment](../../com.aspose.slides/textalignment).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Renvoie ou définit la quantité d'espace entre les lignes de base dans un paragraphe. Une valeur positive signifie un pourcentage, une valeur négative la taille en points. Aucun héritage appliqué. Lecture/écriture float.

**Retour :**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

Renvoie ou définit la quantité d'espace entre les lignes de base dans un paragraphe. Une valeur positive signifie un pourcentage, une valeur négative la taille en points. Aucun héritage appliqué. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Renvoie ou définit la quantité d'espace avant la première ligne d'un paragraphe sans héritage. Une valeur positive indique le pourcentage de la taille de la police que l'espace blanc doit occuper. Une valeur négative indique la taille de l'espace blanc en points. Lecture/écriture float.

**Retour :**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

Renvoie ou définit la quantité d'espace avant la première ligne d'un paragraphe sans héritage. Une valeur positive indique le pourcentage de la taille de la police que l'espace blanc doit occuper. Une valeur négative indique la taille de l'espace blanc en points. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Renvoie ou définit la quantité d'espace après la dernière ligne d'un paragraphe sans héritage. Une valeur positive indique le pourcentage de la taille de la police que l'espace blanc doit occuper. Une valeur négative indique la taille de l'espace blanc en points. Lecture/écriture float.

**Retour :**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

Renvoie ou définit la quantité d'espace après la dernière ligne d'un paragraphe sans héritage. Une valeur positive indique le pourcentage de la taille de la police que l'espace blanc doit occuper. Une valeur négative indique la taille de l'espace blanc en points. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

Détermine si le saut de ligne asiatique est utilisé dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Retour :**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

Détermine si le saut de ligne asiatique est utilisé dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

Détermine si l'écriture de droite à gauche est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Retour :**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

Détermine si l'écriture de droite à gauche est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

Détermine si le saut de ligne latin est utilisé dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Retour :**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

Détermine si le saut de ligne latin est utilisé dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

Détermine si la ponctuation suspendue est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Retour :**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

Détermine si la ponctuation suspendue est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Renvoie ou définit la marge gauche dans un paragraphe sans héritage. Lecture/écriture float.

**Retour :**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

Renvoie ou définit la marge gauche dans un paragraphe sans héritage. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Renvoie ou définit la marge droite dans un paragraphe sans héritage. Lecture/écriture float.

**Retour :**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

Renvoie ou définit la marge droite dans un paragraphe sans héritage. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Renvoie ou définit le retrait de première ligne / retrait suspendu du paragraphe sans héritage. Le retrait suspendu peut être défini avec des valeurs négatives. Lecture/écriture float.

**Retour :**
float

### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

Renvoie ou définit le retrait de première ligne / retrait suspendu du paragraphe sans héritage. Le retrait suspendu peut être défini avec des valeurs négatives. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Renvoie ou définit la taille d'onglet par défaut sans héritage. Lecture/écriture float.

**Retour :**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

Renvoie ou définit la taille d'onglet par défaut sans héritage. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

Renvoie les tabulations d'un paragraphe. Aucun héritage appliqué. Lecture seule [ITabCollection](../../com.aspose.slides/itabcollection).

**Retour :**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Renvoie ou définit un alignement de police dans un paragraphe sans héritage. Lecture/écriture [FontAlignment](../../com.aspose.slides/fontalignment).

**Retour :**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

Renvoie ou définit un alignement de police dans un paragraphe sans héritage. Lecture/écriture [FontAlignment](../../com.aspose.slides/fontalignment).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

Renvoie le format de portion par défaut d'un paragraphe. Aucun héritage appliqué. Lecture seule [IPortionFormat](../../com.aspose.slides/iportionformat).

**Retour :**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

Obtient les données de formatage de paragraphe effectives avec l'héritage appliqué.

**Retour :**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).