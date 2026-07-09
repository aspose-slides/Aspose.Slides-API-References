---
title: ILineFormatEffectiveData
second_title: Référence de l'API Java d'Aspose.Slides pour Android
description: Objet immuable qui contient les propriétés de formatage de ligne effectives.
type: docs
url: /fr/com.aspose.slides/ilineformateffectivedata/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

Objet immuable qui contient les propriétés de formatage de ligne effectives.

--------------------

Cette interface est utilisée conjointement avec l'interface [ILineFormat](../../com.aspose.slides/ilineformat) pour renvoyer les valeurs de formatage effectives avec héritage appliqué.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Renvoie le format de remplissage d'une ligne. |
| [getSketchFormat()](#getSketchFormat--) | Renvoie le format de croquis d'une ligne. |
| [getWidth()](#getWidth--) | Renvoie la largeur d'une ligne. |
| [getDashStyle()](#getDashStyle--) | Renvoie le style de tiret de ligne. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Renvoie le motif de tiret personnalisé. |
| [getCapStyle()](#getCapStyle--) | Renvoie le style de terminaison de ligne. |
| [getStyle()](#getStyle--) | Renvoie le style de ligne. |
| [getAlignment()](#getAlignment--) | Renvoie l'alignement de la ligne. |
| [getJoinStyle()](#getJoinStyle--) | Renvoie le style de jointure des lignes. |
| [getMiterLimit()](#getMiterLimit--) | Renvoie la limite de biseau d'une ligne. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Renvoie le style de pointe de flèche au début d'une ligne. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Renvoie le style de pointe de flèche à la fin d'une ligne. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Renvoie la largeur de la pointe de flèche au début d'une ligne. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Renvoie la largeur de la pointe de flèche à la fin d'une ligne. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Renvoie la longueur de la pointe de flèche au début d'une ligne. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Renvoie la longueur de la pointe de flèche à la fin d'une ligne. |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | Détermine si les deux instances ILineFormatEffectiveData sont égales. |
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```


Renvoie le format de remplissage d'une ligne. Lecture seule [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).

**Renvoie :**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```


Renvoie le format de croquis d'une ligne. Lecture seule [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata).

**Renvoie :**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Renvoie la largeur d'une ligne. Lecture seule double.

**Renvoie :**
double
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```


Renvoie le style de tiret de ligne. Lecture seule [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Renvoie :**
byte
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```


Renvoie le motif de tiret personnalisé. Lecture seule float[].

**Renvoie :**
float[]
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```


Renvoie le style de terminaison de ligne. Lecture seule [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Renvoie :**
byte
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```


Renvoie le style de ligne. Lecture seule [LineStyle](../../com.aspose.slides/linestyle).

**Renvoie :**
byte
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```


Renvoie l'alignement de la ligne. Lecture seule [LineAlignment](../../com.aspose.slides/linealignment).

**Renvoie :**
byte
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```


Renvoie le style de jointure des lignes. Lecture seule [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Renvoie :**
byte
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```


Renvoie la limite de biseau d'une ligne. Lecture seule float.

**Renvoie :**
float
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```


Renvoie le style de pointe de flèche au début d'une ligne. Lecture seule [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Renvoie :**
byte
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```


Renvoie le style de pointe de flèche à la fin d'une ligne. Lecture seule [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Renvoie :**
byte
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```


Renvoie la largeur de la pointe de flèche au début d'une ligne. Lecture seule [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Renvoie :**
byte
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```


Renvoie la largeur de la pointe de flèche à la fin d'une ligne. Lecture seule [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Renvoie :**
byte
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```


Renvoie la longueur de la pointe de flèche au début d'une ligne. Lecture seule [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Renvoie :**
byte
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```


Renvoie la longueur de la pointe de flèche à la fin d'une ligne. Lecture seule [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Renvoie :**
byte
### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```


Détermine si les deux instances ILineFormatEffectiveData sont égales.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | L'ILineFormatEffectiveData à comparer avec l'ILineFormatEffectiveData actuel. |

**Renvoie :**
boolean - **true** si le ILineFormatEffectiveData spécifié est égal au ILineFormatEffectiveData actuel ; sinon, **false**.