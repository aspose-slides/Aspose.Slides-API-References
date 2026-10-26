---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Java API Reference
description: Représente les propriétés de mise en forme pour les éléments de texte du graphique.
type: docs
url: /fr/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

Représente les propriétés de mise en forme pour les éléments de texte du graphique.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | Renvoie ou définit le texte d'ancrage vertical dans un TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Renvoie ou définit le texte d'ancrage vertical dans un TextFrame. |
| [getCenterText()](#getCenterText--) | Si NullableBool.True, le texte doit être centré horizontalement dans la zone. |
| [setCenterText(byte value)](#setCenterText-byte-) | Si NullableBool.True, le texte doit être centré horizontalement dans la zone. |
| [getTextVerticalType()](#getTextVerticalType--) | Détermine l'orientation du texte. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Détermine l'orientation du texte. |
| [getMarginLeft()](#getMarginLeft--) | Renvoie ou définit la marge gauche (points) dans un TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Renvoie ou définit la marge gauche (points) dans un TextFrame. |
| [getMarginRight()](#getMarginRight--) | Renvoie ou définit la marge droite (points) dans un TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Renvoie ou définit la marge droite (points) dans un TextFrame. |
| [getMarginTop()](#getMarginTop--) | Renvoie ou définit la marge supérieure (points) dans un TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Renvoie ou définit la marge supérieure (points) dans un TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Renvoie ou définit la marge inférieure (points) dans un TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Renvoie ou définit la marge inférieure (points) dans un TextFrame. |
| [getWrapText()](#getWrapText--) | Vrai si le texte est renvoyé à la ligne aux marges du TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | Vrai si le texte est renvoyé à la ligne aux marges du TextFrame. |
| [getAutofitType()](#getAutofitType--) | Renvoie ou définit le mode d'ajustement automatique du texte. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Renvoie ou définit le mode d'ajustement automatique du texte. |
| [getRotationAngle()](#getRotationAngle--) | Spécifie la rotation personnalisée appliquée au texte à l'intérieur de la boîte englobante. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Spécifie la rotation personnalisée appliquée au texte à l'intérieur de la boîte englobante. |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Renvoie ou définit le texte d'ancrage vertical dans un TextFrame. Lecture/écriture [TextAnchorType](../../com.aspose.slides/textanchortype).

**Retourne :**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Renvoie ou définit le texte d'ancrage vertical dans un TextFrame. Lecture/écriture [TextAnchorType](../../com.aspose.slides/textanchortype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Si NullableBool.True, le texte doit être centré horizontalement dans la zone. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Retourne :**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Si NullableBool.True, le texte doit être centré horizontalement dans la zone. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
``` 
public abstract byte getTextVerticalType()
```

Détermine l'orientation du texte. La valeur résultante de la rotation visuelle du texte résumée à partir de cette propriété et de l'angle personnalisé dans la propriété RotationAngle. Lecture/écriture [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Retourne :**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Détermine l'orientation du texte. La valeur résultante de la rotation visuelle du texte résumée à partir de cette propriété et de l'angle personnalisé dans la propriété RotationAngle. Lecture/écriture [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Renvoie ou définit la marge gauche (points) dans un TextFrame. Modifier cette propriété peut produire une certaine influence uniquement sur les parties du graphique suivantes : DataLabel et DataLabelFormat (prise en charge complète dans PowerPoint 2013 ; dans PowerPoint 2007, aucun effet sur le rendu). Lecture/écriture double.

**Retourne :**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Renvoie ou définit la marge gauche (points) dans un TextFrame. Modifier cette propriété peut produire une certaine influence uniquement sur les parties du graphique suivantes : DataLabel et DataLabelFormat (prise en charge complète dans PowerPoint 2013 ; dans PowerPoint 2007, aucun effet sur le rendu). Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Renvoie ou définit la marge droite (points) dans un TextFrame. Modifier cette propriété peut produire une certaine influence uniquement sur les parties du graphique suivantes : DataLabel et DataLabelFormat (prise en charge complète dans PowerPoint 2013 ; dans PowerPoint 2007, aucun effet sur le rendu). Lecture/écriture double.

**Retourne :**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Renvoie ou définit la marge droite (points) dans un TextFrame. Modifier cette propriété peut produire une certaine influence uniquement sur les parties du graphique suivantes : DataLabel et DataLabelFormat (prise en charge complète dans PowerPoint 2013 ; dans PowerPoint 2007, aucun effet sur le rendu). Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Renvoie ou définit la marge supérieure (points) dans un TextFrame. Modifier cette propriété peut produire une certaine influence uniquement sur les parties du graphique suivantes : DataLabel et DataLabelFormat (prise en charge complète dans PowerPoint 2013 ; dans PowerPoint 2007, aucun effet sur le rendu). Lecture/écriture double.

**Retourne :**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Renvoie ou définit la marge supérieure (points) dans un TextFrame. Modifier cette propriété peut produire une certaine influence uniquement sur les parties du graphique suivantes : DataLabel et DataLabelFormat (prise en charge complète dans PowerPoint 2013 ; dans PowerPoint 2007, aucun effet sur le rendu). Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Renvoie ou définit la marge inférieure (points) dans un TextFrame. Modifier cette propriété peut produire une certaine influence uniquement sur les parties du graphique suivantes : DataLabel et DataLabelFormat (prise en charge complète dans PowerPoint 2013 ; dans PowerPoint 2007, aucun effet sur le rendu). Lecture/écriture double.

**Retourne :**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Renvoie ou définit la marge inférieure (points) dans un TextFrame. Modifier cette propriété peut produire une certaine influence uniquement sur les parties du graphique suivantes : DataLabel et DataLabelFormat (prise en charge complète dans PowerPoint 2013 ; dans PowerPoint 2007, aucun effet sur le rendu). Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Vrai si le texte est renvoyé à la ligne aux marges du TextFrame. Modifier cette propriété peut produire une certaine influence uniquement sur les parties du graphique suivantes : DataLabel et DataLabelFormat (prise en charge complète dans PowerPoint 2007/2013). Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Retourne :**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Vrai si le texte est renvoyé à la ligne aux marges du TextFrame. Modifier cette propriété peut produire une certaine influence uniquement sur les parties du graphique suivantes : DataLabel et DataLabelFormat (prise en charge complète dans PowerPoint 2007/2013). Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Renvoie ou définit le mode d'ajustement automatique du texte. Modifier cette propriété peut produire une certaine influence uniquement sur les parties du graphique suivantes : DataLabel et DataLabelFormat (prise en charge complète dans PowerPoint 2013 ; dans PowerPoint 2007, aucun effet sur le rendu). Lecture/écriture [TextAutofitType](../../com.aspose.slides/textautofittype).

**Retourne :**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Renvoie ou définit le mode d'ajustement automatique du texte. Modifier cette propriété peut produire une certaine influence uniquement sur les parties du graphique suivantes : DataLabel et DataLabelFormat (prise en charge complète dans PowerPoint 2013 ; dans PowerPoint 2007, aucun effet sur le rendu). Lecture/écriture [TextAutofitType](../../com.aspose.slides/textautofittype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Spécifie la rotation personnalisée appliquée au texte à l'intérieur de la boîte englobante. Si elle n'est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, elle est appliquée indépendamment de la forme. Ainsi, la forme peut avoir une rotation appliquée en plus de la rotation appliquée au texte lui-même. La valeur résultante de la rotation visuelle du texte résumée à partir de cette propriété et du type vertical prédéterminé dans la propriété TextVerticalType. Lecture/écriture float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Retourne :**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Spécifie la rotation personnalisée appliquée au texte à l'intérieur de la boîte englobante. Si elle n'est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, elle est appliquée indépendamment de la forme. Ainsi, la forme peut avoir une rotation appliquée en plus de la rotation appliquée au texte lui-même. La valeur résultante de la rotation visuelle du texte résumée à partir de cette propriété et du type vertical prédéterminé dans la propriété TextVerticalType. Lecture/écriture float.

--------------------

> ```
> Considérez le cas où une forme a une rotation de 90 degrés dans le sens des aiguilles d'une montre appliquée à celle-ci. 
>  En plus de cela, le corps du texte lui-même a une rotation de -90 degrés 
>  dans le sens inverse des aiguilles d'une montre appliquée à celle-ci. Alors la forme résultante semblerait 
>  être tournée mais le texte à l'intérieur semblerait ne pas avoir été du tout tourné.
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |