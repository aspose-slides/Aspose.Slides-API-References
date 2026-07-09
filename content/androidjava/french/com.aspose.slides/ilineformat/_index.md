---
title: ILineFormat
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente le format d'une ligne.
type: docs
url: /fr/com.aspose.slides/ilineformat/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

Représente le format d'une ligne.
## Méthodes

| Méthode | Description |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | Renvoie true si le format de ligne n'est pas défini (tel qu'il vient d'être créé, par défaut). |
| [getFillFormat()](#getFillFormat--) | Renvoie le format de remplissage d'une ligne. |
| [getSketchFormat()](#getSketchFormat--) | Renvoie le format de croquis d'une ligne. |
| [getWidth()](#getWidth--) | Renvoie ou définit la largeur d'une ligne. |
| [setWidth(double value)](#setWidth-double-) | Renvoie ou définit la largeur d'une ligne. |
| [getDashStyle()](#getDashStyle--) | Renvoie ou définit le style de tirets de la ligne. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Renvoie ou définit le style de tirets de la ligne. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Renvoie ou définit le motif de tirets personnalisé. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Renvoie ou définit le motif de tirets personnalisé. |
| [getCapStyle()](#getCapStyle--) | Renvoie ou définit le style d'extrémité de ligne. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Renvoie ou définit le style d'extrémité de ligne. |
| [getStyle()](#getStyle--) | Renvoie ou définit le style de ligne. |
| [setStyle(byte value)](#setStyle-byte-) | Renvoie ou définit le style de ligne. |
| [getAlignment()](#getAlignment--) | Renvoie ou définit l'alignement de la ligne. |
| [setAlignment(byte value)](#setAlignment-byte-) | Renvoie ou définit l'alignement de la ligne. |
| [getJoinStyle()](#getJoinStyle--) | Renvoie ou définit le style de jointure des lignes. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Renvoie ou définit le style de jointure des lignes. |
| [getMiterLimit()](#getMiterLimit--) | Renvoie ou définit la limite d'onglet d'une ligne. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Renvoie ou définit la limite d'onglet d'une ligne. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Renvoie ou définit le style de tête de flèche au début d'une ligne. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Renvoie ou définit le style de tête de flèche au début d'une ligne. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Renvoie ou définit le style de tête de flèche à la fin d'une ligne. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Renvoie ou définit le style de tête de flèche à la fin d'une ligne. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Renvoie ou définit la largeur de la tête de flèche au début d'une ligne. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Renvoie ou définit la largeur de la tête de flèche au début d'une ligne. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Renvoie ou définit la largeur de la tête de flèche à la fin d'une ligne. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Renvoie ou définit la largeur de la tête de flèche à la fin d'une ligne. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Renvoie ou définit la longueur de la tête de flèche au début d'une ligne. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Renvoie ou définit la longueur de la tête de flèche au début d'une ligne. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Renvoie ou définit la longueur de la tête de flèche à la fin d'une ligne. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Renvoie ou définit la longueur de la tête de flèche à la fin d'une ligne. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Détermine si les deux instances de LineFormat sont égales. |
| [getEffective()](#getEffective--) | Obtient les données de formatage de ligne effectives avec l'héritage appliqué. |

### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

Renvoie true si le format de ligne n'est pas défini (tel qu'il vient d'être créé, par défaut). Booléen en lecture seule.

**Renvoie :**
boolean

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

Renvoie le format de remplissage d'une ligne. Lecture seule [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Renvoie :**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

Renvoie le format de croquis d'une ligne. Lecture seule [ISketchFormat](../../com.aspose.slides/isketchformat).

**Renvoie :**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Renvoie ou définit la largeur d'une ligne. Lecture/écriture double.

**Renvoie :**
double

### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Renvoie ou définit la largeur d'une ligne. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

Renvoie ou définit le style de tirets de la ligne. Lecture/écriture [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Renvoie :**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

Renvoie ou définit le style de tirets de la ligne. Lecture/écriture [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

Renvoie ou définit le motif de tirets personnalisé. Lecture/écriture float[].

**Renvoie :**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

Renvoie ou définit le motif de tirets personnalisé. Lecture/écriture float[].

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

Renvoie ou définit le style d'extrémité de ligne. Lecture/écriture [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Renvoie :**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

Renvoie ou définit le style d'extrémité de ligne. Lecture/écriture [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

Renvoie ou définit le style de ligne. Lecture/écriture [LineStyle](../../com.aspose.slides/linestyle).

**Renvoie :**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

Renvoie ou définit le style de ligne. Lecture/écriture [LineStyle](../../com.aspose.slides/linestyle).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

Renvoie ou définit l'alignement de la ligne. Lecture/écriture [LineAlignment](../../com.aspose.slides/linealignment).

**Renvoie :**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

Renvoie ou définit l'alignement de la ligne. Lecture/écriture [LineAlignment](../../com.aspose.slides/linealignment).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

Renvoie ou définit le style de jointure des lignes. Lecture/écriture [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Renvoie :**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

Renvoie ou définit le style de jointure des lignes. Lecture/écriture [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

Renvoie ou définit la limite d'onglet d'une ligne. Lecture/écriture float.

**Renvoie :**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

Renvoie ou définit la limite d'onglet d'une ligne. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

Renvoie ou définit le style de tête de flèche au début d'une ligne. Lecture/écriture [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Renvoie :**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

Renvoie ou définit le style de tête de flèche au début d'une ligne. Lecture/écriture [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

Renvoie ou définit le style de tête de flèche à la fin d'une ligne. Lecture/écriture [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Renvoie :**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

Renvoie ou définit le style de tête de flèche à la fin d'une ligne. Lecture/écriture [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

Renvoie ou définit la largeur de la tête de flèche au début d'une ligne. Lecture/écriture [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Renvoie :**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

Renvoie ou définit la largeur de la tête de flèche au début d'une ligne. Lecture/écriture [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

Renvoie ou définit la largeur de la tête de flèche à la fin d'une ligne. Lecture/écriture [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Renvoie :**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

Renvoie ou définit la largeur de la tête de flèche à la fin d'une ligne. Lecture/écriture [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

Renvoie ou définit la longueur de la tête de flèche au début d'une ligne. Lecture/écriture [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Renvoie :**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

Renvoie ou définit la longueur de la tête de flèche au début d'une ligne. Lecture/écriture [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

Renvoie ou définit la longueur de la tête de flèche à la fin d'une ligne. Lecture/écriture [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Renvoie :**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

Renvoie ou définit la longueur de la tête de flèche à la fin d'une ligne. Lecture/écriture [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```

Détermine si les deux instances de LineFormat sont égales.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | Le LineFormat à comparer avec le LineFormat actuel. |

**Renvoie :**
boolean - **true** si le LineFormat spécifié est égal au LineFormat actuel ; sinon, **false**.

### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

Obtient les données de formatage de ligne effectives avec l'héritage appliqué.

**Renvoie :**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - Un [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).