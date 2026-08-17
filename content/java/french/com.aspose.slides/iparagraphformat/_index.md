---
title: IParagraphFormat
second_title: Aspose.Slides for Java API Reference
description: This class contains the paragraph formatting properties.
type: docs
url: /fr/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

Cette classe contient les propriétés de mise en forme du paragraphe. Contrairement à [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata), toutes les propriétés de cette classe sont modifiables.

--------------------

Cette classe est utilisée pour renvoyer et manipuler les propriétés de mise en forme du paragraphe définies pour le paragraphe particulier. Cela signifie qu’aucune héritage n’est appliqué lors de l’obtention des valeurs, de sorte que dans la majorité des cas vous obtiendrez des valeurs signifiant « indéfini ».

Pour obtenir les valeurs des paramètres de mise en forme effectifs, y compris l’héritage, vous devez utiliser la méthode [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective) qui renvoie une instance [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBullet()](#getBullet--) | Renvoie le format de puce du paragraphe. |
| [getDepth()](#getDepth--) | Renvoie ou définit la profondeur du paragraphe. |
| [setDepth(short value)](#setDepth-short-) | Renvoie ou définit la profondeur du paragraphe. |
| [getAlignment()](#getAlignment--) | Renvoie ou définit l’alignement du texte dans un paragraphe sans héritage. |
| [setAlignment(int value)](#setAlignment-int-) | Renvoie ou définit l’alignement du texte dans un paragraphe sans héritage. |
| [getSpaceWithin()](#getSpaceWithin--) | Renvoie ou définit l’espacement entre les lignes de base dans un paragraphe. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Renvoie ou définit l’espacement entre les lignes de base dans un paragraphe. |
| [getSpaceBefore()](#getSpaceBefore--) | Renvoie ou définit l’espacement avant la première ligne dans un paragraphe sans héritage. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Renvoie ou définit l’espacement avant la première ligne dans un paragraphe sans héritage. |
| [getSpaceAfter()](#getSpaceAfter--) | Renvoie ou définit l’espacement après la dernière ligne dans un paragraphe sans héritage. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Renvoie ou définit l’espacement après la dernière ligne dans un paragraphe sans héritage. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Détermine si la coupure de ligne asiatique de l’Est est utilisée dans un paragraphe. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Détermine si la coupure de ligne asiatique de l’Est est utilisée dans un paragraphe. |
| [getRightToLeft()](#getRightToLeft--) | Détermine si l’écriture de droite à gauche est utilisée dans un paragraphe. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Détermine si l’écriture de droite à gauche est utilisée dans un paragraphe. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Détermine si la coupure de ligne latine est utilisée dans un paragraphe. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Détermine si la coupure de ligne latine est utilisée dans un paragraphe. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Détermine si la ponctuation suspendue est utilisée dans un paragraphe. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Détermine si la ponctuation suspendue est utilisée dans un paragraphe. |
| [getMarginLeft()](#getMarginLeft--) | Renvoie ou définit la marge gauche dans un paragraphe sans héritage. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Renvoie ou définit la marge gauche dans un paragraphe sans héritage. |
| [getMarginRight()](#getMarginRight--) | Renvoie ou définit la marge droite dans un paragraphe sans héritage. |
| [setMarginRight(float value)](#setMarginRight-float-) | Renvoie ou définit la marge droite dans un paragraphe sans héritage. |
| [getIndent()](#getIndent--) | Renvoie ou définit le retrait de première ligne/pendant de paragraphe sans héritage. |
| [setIndent(float value)](#setIndent-float-) | Renvoie ou définit le retrait de première ligne/pendant de paragraphe sans héritage. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Renvoie ou définit la taille de tabulation par défaut sans héritage. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Renvoie ou définit la taille de tabulation par défaut sans héritage. |
| [getTabs()](#getTabs--) | Renvoie les tabulations d’un paragraphe. |
| [getFontAlignment()](#getFontAlignment--) | Renvoie ou définit l’alignement de police dans un paragraphe sans héritage. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Renvoie ou définit l’alignement de police dans un paragraphe sans héritage. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Renvoie le format de portion par défaut d’un paragraphe. |
| [getEffective()](#getEffective--) | Obtient les données de mise en forme du paragraphe effectives avec l’héritage appliqué. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

Renvoie le format de puce du paragraphe. Lecture seule [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Renvoie :**
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Renvoie ou définit la profondeur du paragraphe. La valeur 0 signifie valeur indéfinie. Lecture/écriture short.

**Renvoie :**
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

Renvoie ou définit l’alignement du texte dans un paragraphe sans héritage. Lecture/écriture [TextAlignment](../../com.aspose.slides/textalignment).

**Renvoie :**
int
### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

Renvoie ou définit l’alignement du texte dans un paragraphe sans héritage. Lecture/écriture [TextAlignment](../../com.aspose.slides/textalignment).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Renvoie ou définit l’espacement entre les lignes de base dans un paragraphe. Une valeur positive signifie un pourcentage, négative – taille en points. Aucun héritage appliqué. Lecture/écriture float.

**Renvoie :**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

Renvoie ou définit l’espacement entre les lignes de base dans un paragraphe. Une valeur positive signifie un pourcentage, négative – taille en points. Aucun héritage appliqué. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Renvoie ou définit l’espacement avant la première ligne dans un paragraphe sans héritage. Une valeur positive spécifie le pourcentage de la taille de police que l’espace blanc doit occuper. Une valeur négative spécifie la taille de l’espace blanc en points. Lecture/écriture float.

**Renvoie :**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

Renvoie ou définit l’espacement avant la première ligne dans un paragraphe sans héritage. Une valeur positive spécifie le pourcentage de la taille de police que l’espace blanc doit occuper. Une valeur négative spécifie la taille de l’espace blanc en points. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Renvoie ou définit l’espacement après la dernière ligne dans un paragraphe sans héritage. Une valeur positive spécifie le pourcentage de la taille de police que l’espace blanc doit occuper. Une valeur négative spécifie la taille de l’espace blanc en points. Lecture/écriture float.

**Renvoie :**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

Renvoie ou définit l’espacement après la dernière ligne dans un paragraphe sans héritage. Une valeur positive spécifie le pourcentage de la taille de police que l’espace blanc doit occuper. Une valeur négative spécifie la taille de l’espace blanc en points. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

Détermine si la coupure de ligne asiatique de l’Est est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

Détermine si la coupure de ligne asiatique de l’Est est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

Détermine si l’écriture de droite à gauche est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

Détermine si l’écriture de droite à gauche est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

Détermine si la coupure de ligne latine est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

Détermine si la coupure de ligne latine est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

Détermine si la ponctuation suspendue est utilisée dans un paragraphe. Aucun héritage appliqué. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
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

**Renvoie :**
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

**Renvoie :**
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

Renvoie ou définit le retrait de première ligne/pendant du paragraphe sans héritage. Le retrait pendant peut être défini avec des valeurs négatives. Lecture/écriture float.

**Renvoie :**
float
### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

Renvoie ou définit le retrait de première ligne/pendant du paragraphe sans héritage. Le retrait pendant peut être défini avec des valeurs négatives. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Renvoie ou définit la taille de tabulation par défaut sans héritage. Lecture/écriture float.

**Renvoie :**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

Renvoie ou définit la taille de tabulation par défaut sans héritage. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

Renvoie les tabulations d’un paragraphe. Aucun héritage appliqué. Lecture seule [ITabCollection](../../com.aspose.slides/itabcollection).

**Renvoie :**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Renvoie ou définit l’alignement de police dans un paragraphe sans héritage. Lecture/écriture [FontAlignment](../../com.aspose.slides/fontalignment).

**Renvoie :**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

Renvoie ou définit l’alignement de police dans un paragraphe sans héritage. Lecture/écriture [FontAlignment](../../com.aspose.slides/fontalignment).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

Renvoie le format de portion par défaut d’un paragraphe. Aucun héritage appliqué. Lecture seule [IPortionFormat](../../com.aspose.slides/iportionformat).

**Renvoie :**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

Obtient les données de mise en forme du paragraphe effectives avec l’héritage appliqué.

**Renvoie :**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).