---
title: IChartTextBlockFormat
second_title: Aspose.Slides pour Android via API Java
description: Représente les propriétés de mise en forme des éléments de texte du graphique.
type: docs
url: /fr/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

Représente les propriétés de mise en forme des éléments de texte du graphique.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | Returns or sets vertical anchor text in a TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Returns or sets vertical anchor text in a TextFrame. |
| [getCenterText()](#getCenterText--) | If NullableBool.True then text should be centered in box horizontally. |
| [setCenterText(byte value)](#setCenterText-byte-) | If NullableBool.True then text should be centered in box horizontally. |
| [getTextVerticalType()](#getTextVerticalType--) | Determines text orientation. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Determines text orientation. |
| [getMarginLeft()](#getMarginLeft--) | Returns or sets the left margin (points) in a TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Returns or sets the left margin (points) in a TextFrame. |
| [getMarginRight()](#getMarginRight--) | Returns or sets the right margin (points) in a TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Returns or sets the right margin (points) in a TextFrame. |
| [getMarginTop()](#getMarginTop--) | Returns or sets the top margin (points) in a TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Returns or sets the top margin (points) in a TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Returns or sets the bottom margin (points) in a TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Returns or sets the bottom margin (points) in a TextFrame. |
| [getWrapText()](#getWrapText--) | True if text is wrapped at TextFrame's margins. |
| [setWrapText(byte value)](#setWrapText-byte-) | True if text is wrapped at TextFrame's margins. |
| [getAutofitType()](#getAutofitType--) | Returns or sets text's autofit mode. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Returns or sets text's autofit mode. |
| [getRotationAngle()](#getRotationAngle--) | Specifies the custom rotation that is being applied to the text within the bounding box. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Specifies the custom rotation that is being applied to the text within the bounding box. |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Renvoie ou définit le texte d’ancrage vertical dans un TextFrame. Lecture/écriture [TextAnchorType](../../com.aspose.slides/textanchortype).

**Renvoie :**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Renvoie ou définit le texte d’ancrage vertical dans un TextFrame. Lecture/écriture [TextAnchorType](../../com.aspose.slides/textanchortype).

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Si NullableBool.True, le texte doit être centré horizontalement dans la boîte. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Si NullableBool.True, le texte doit être centré horizontalement dans la boîte. Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Détermine l’orientation du texte. La valeur finale de rotation visuelle du texte résulte de cette propriété et de l’angle personnalisé de la propriété RotationAngle. Lecture/écriture [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Renvoie :**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Détermine l’orientation du texte. La valeur finale de rotation visuelle du texte résulte de cette propriété et de l’angle personnalisé de la propriété RotationAngle. Lecture/écriture [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Renvoie ou définit la marge gauche (points) dans un TextFrame. La modification de cette propriété n’influence que certaines parties du graphique : DataLabel et DataLabelFormat (support complet dans PowerPoint 2013 ; dans PowerPoint 2007 il n’y a aucun effet sur le rendu). Lecture/écriture double.

**Renvoie :**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Renvoie ou définit la marge gauche (points) dans un TextFrame. La modification de cette propriété n’influence que certaines parties du graphique : DataLabel et DataLabelFormat (support complet dans PowerPoint 2013 ; dans PowerPoint 2007 il n’y a aucun effet sur le rendu). Lecture/écriture double.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Renvoie ou définit la marge droite (points) dans un TextFrame. La modification de cette propriété n’influence que certaines parties du graphique : DataLabel et DataLabelFormat (support complet dans PowerPoint 2013 ; dans PowerPoint 2007 il n’y a aucun effet sur le rendu). Lecture/écriture double.

**Renvoie :**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Renvoie ou définit la marge droite (points) dans un TextFrame. La modification de cette propriété n’influence que certaines parties du graphique : DataLabel et DataLabelFormat (support complet dans PowerPoint 2013 ; dans PowerPoint 2007 il n’y a aucun effet sur le rendu). Lecture/écriture double.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Renvoie ou définit la marge supérieure (points) dans un TextFrame. La modification de cette propriété n’influence que certaines parties du graphique : DataLabel et DataLabelFormat (support complet dans PowerPoint 2013 ; dans PowerPoint 2007 il n’y a aucun effet sur le rendu). Lecture/écriture double.

**Renvoie :**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Renvoie ou définit la marge supérieure (points) dans un TextFrame. La modification de cette propriété n’influence que certaines parties du graphique : DataLabel et DataLabelFormat (support complet dans PowerPoint 2013 ; dans PowerPoint 2007 il n’y a aucun effet sur le rendu). Lecture/écriture double.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Renvoie ou définit la marge inférieure (points) dans un TextFrame. La modification de cette propriété n’influence que certaines parties du graphique : DataLabel et DataLabelFormat (support complet dans PowerPoint 2013 ; dans PowerPoint 2007 il n’y a aucun effet sur le rendu). Lecture/écriture double.

**Renvoie :**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Renvoie ou définit la marge inférieure (points) dans un TextFrame. La modification de cette propriété n’influence que certaines parties du graphique : DataLabel et DataLabelFormat (support complet dans PowerPoint 2013 ; dans PowerPoint 2007 il n’y a aucun effet sur le rendu). Lecture/écriture double.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Vrai si le texte est renvoyé aux marges du TextFrame. La modification de cette propriété n’influence que certaines parties du graphique : DataLabel et DataLabelFormat (support complet dans PowerPoint 2007/2013). Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Renvoie :**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Vrai si le texte est renvoyé aux marges du TextFrame. La modification de cette propriété n’influence que certaines parties du graphique : DataLabel et DataLabelFormat (support complet dans PowerPoint 2007/2013). Lecture/écriture [NullableBool](../../com.aspose.slides/nullablebool).

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Renvoie ou définit le mode d’ajustement automatique du texte. La modification de cette propriété n’influence que certaines parties du graphique : DataLabel et DataLabelFormat (support complet dans PowerPoint 2013 ; dans PowerPoint 2007 il n’y a aucun effet sur le rendu). Lecture/écriture [TextAutofitType](../../com.aspose.slides/textautofittype).

**Renvoie :**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Renvoie ou définit le mode d’ajustement automatique du texte. La modification de cette propriété n’influence que certaines parties du graphique : DataLabel et DataLabelFormat (support complet dans PowerPoint 2013 ; dans PowerPoint 2007 il n’y a aucun effet sur le rendu). Lecture/écriture [TextAutofitType](../../com.aspose.slides/textautofittype).

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Spécifie la rotation personnalisée appliquée au texte à l’intérieur de la boîte englobante. Si elle n’est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, elle est appliquée de façon indépendante de la forme. Ainsi, la forme peut avoir une rotation en plus de la rotation propre du texte. La valeur finale de rotation visuelle du texte résulte de cette propriété et du type vertical prédéfini de la propriété TextVerticalType. Lecture/écriture float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Returns:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)

Spécifie la rotation personnalisée appliquée au texte à l’intérieur de la boîte englobante. Si elle n’est pas spécifiée, la rotation de la forme associée est utilisée. Si elle est spécifiée, elle est appliquée de façon indépendante de la forme. Ainsi, la forme peut avoir une rotation en plus de la rotation propre du texte. La valeur finale de rotation visuelle du texte résulte de cette propriété et du type vertical prédéfini de la propriété TextVerticalType. Lecture/écriture float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |