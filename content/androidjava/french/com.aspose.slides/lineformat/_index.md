---
title: LineFormat
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente le format d'une ligne.
type: docs
url: /fr/com.aspose.slides/lineformat/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**  
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)  
```
public final class LineFormat extends PVIObject implements ILineFormat
```

Représente le format d'une ligne.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | Renvoie **true** si le format de ligne n'est pas défini (venant d'être créé, valeur par défaut). |
| [getFillFormat()](#getFillFormat--) | Renvoie le format de remplissage d'une ligne. |
| [getSketchFormat()](#getSketchFormat--) | Renvoie le format de croquis d'une ligne. |
| [getWidth()](#getWidth--) | Renvoie ou définit la largeur d'une ligne. |
| [setWidth(double value)](#setWidth-double-) | Renvoie ou définit la largeur d'une ligne. |
| [getDashStyle()](#getDashStyle--) | Renvoie ou définit le style de tiret de la ligne. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Renvoie ou définit le style de tiret de la ligne. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Renvoie ou définit le motif de tiret personnalisé. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Renvoie ou définit le motif de tiret personnalisé. |
| [getCapStyle()](#getCapStyle--) | Renvoie ou définit le style de bout de ligne. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Renvoie ou définit le style de bout de ligne. |
| [getStyle()](#getStyle--) | Renvoie ou définit le style de ligne. |
| [setStyle(byte value)](#setStyle-byte-) | Renvoie ou définit le style de ligne. |
| [getAlignment()](#getAlignment--) | Renvoie ou définit l'alignement de la ligne. |
| [setAlignment(byte value)](#setAlignment-byte-) | Renvoie ou définit l'alignement de la ligne. |
| [getJoinStyle()](#getJoinStyle--) | Renvoie ou définit le style de jointure des lignes. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Renvoie ou définit le style de jointure des lignes. |
| [getMiterLimit()](#getMiterLimit--) | Renvoie ou définit la limite d'onglet d'une ligne. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Renvoie ou définit la limite d'onglet d'une ligne. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Renvoie ou définit le style de pointe de flèche au début d'une ligne. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Renvoie ou définit le style de pointe de flèche au début d'une ligne. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Renvoie ou définit le style de pointe de flèche à la fin d'une ligne. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Renvoie ou définit le style de pointe de flèche à la fin d'une ligne. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Renvoie ou définit la largeur de la pointe de flèche au début d'une ligne. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Renvoie ou définit la largeur de la pointe de flèche au début d'une ligne. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Renvoie ou définit la largeur de la pointe de flèche à la fin d'une ligne. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Renvoie ou définit la largeur de la pointe de flèche à la fin d'une ligne. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Renvoie ou définit la longueur de la pointe de flèche au début d'une ligne. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Renvoie ou définit la longueur de la pointe de flèche au début d'une ligne. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Renvoie ou définit la longueur de la pointe de flèche à la fin d'une ligne. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Renvoie ou définit la longueur de la pointe de flèche à la fin d'une ligne. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Détermine si les deux instances de LineFormat sont égales. |
| [getEffective()](#getEffective--) | Obtient les données de formatage de ligne effectives avec l'héritage appliqué. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Lecture seule long.

**Retour:**  
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Compare avec l'objet spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Retour:**  
boolean

### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```

Renvoie **true** si le format de ligne n'est pas défini (venant d'être créé, valeur par défaut). Lecture seule  boolean .

**Retour:**  
boolean

### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```

Renvoie le format de remplissage d'une ligne. Lecture seule [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Retour:**  
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```

Renvoie le format de croquis d'une ligne. Lecture seule [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Retour:**  
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public final double getWidth()
```

Renvoie ou définit la largeur d'une ligne. Lecture/écriture  double .

**Retour:**  
double

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

Renvoie ou définit la largeur d'une ligne. Lecture/écriture  double .

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```

Renvoie ou définit le style de tiret de la ligne. Lecture/écriture [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Retour:**  
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```

Renvoie ou définit le style de tiret de la ligne. Lecture/écriture [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```

Renvoie ou définit le motif de tiret personnalisé. Lecture/écriture  float[] .

**Retour:**  
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```

Renvoie ou définit le motif de tiret personnalisé. Lecture/écriture  float[] .

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```

Renvoie ou définit le style de bout de ligne. Lecture/écriture [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Retour:**  
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```

Renvoie ou définit le style de bout de ligne. Lecture/écriture [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public final byte getStyle()
```

Renvoie ou définit le style de ligne. Lecture/écriture [LineStyle](../../com.aspose.slides/linestyle).

**Retour:**  
byte

### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```

Renvoie ou définit le style de ligne. Lecture/écriture [LineStyle](../../com.aspose.slides/linestyle).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```

Renvoie ou définit l'alignement de la ligne. Lecture/écriture [LineAlignment](../../com.aspose.slides/linealignment).

**Retour:**  
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```

Renvoie ou définit l'alignement de la ligne. Lecture/écriture [LineAlignment](../../com.aspose.slides/linealignment).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```

Renvoie ou définit le style de jointure des lignes. Lecture/écriture [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Retour:**  
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```

Renvoie ou définit le style de jointure des lignes. Lecture/écriture [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```

Renvoie ou définit la limite d'onglet d'une ligne. Lecture/écriture  float .

**Retour:**  
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```

Renvoie ou définit la limite d'onglet d'une ligne. Lecture/écriture  float .

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```

Renvoie ou définit le style de pointe de flèche au début d'une ligne. Lecture/écriture [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Retour:**  
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```

Renvoie ou définit le style de pointe de flèche au début d'une ligne. Lecture/écriture [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```

Renvoie ou définit le style de pointe de flèche à la fin d'une ligne. Lecture/écriture [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Retour:**  
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```

Renvoie ou définit le style de pointe de flèche à la fin d'une ligne. Lecture/écriture [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```

Renvoie ou définit la largeur de la pointe de flèche au début d'une ligne. Lecture/écriture [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Retour:**  
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```

Renvoie ou définit la largeur de la pointe de flèche au début d'une ligne. Lecture/écriture [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```

Renvoie ou définit la largeur de la pointe de flèche à la fin d'une ligne. Lecture/écriture [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Retour:**  
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```

Renvoie ou définit la largeur de la pointe de flèche à la fin d'une ligne. Lecture/écriture [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```

Renvoie ou définit la longueur de la pointe de flèche au début d'une ligne. Lecture/écriture [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Retour:**  
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```

Renvoie ou définit la longueur de la pointe de flèche au début d'une ligne. Lecture/écriture [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```

Renvoie ou définit la longueur de la pointe de flèche à la fin d'une ligne. Lecture/écriture [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Retour:**  
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```

Renvoie ou définit la longueur de la pointe de flèche à la fin d'une ligne. Lecture/écriture [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```

Détermine si les deux instances de LineFormat sont égales.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | Le LineFormat à comparer avec le LineFormat actuel. |

**Retour:**  
boolean - **true** si le LineFormat spécifié est égal au LineFormat actuel ; sinon, **false**.

### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```

Obtient les données de formatage de ligne effectives avec l'héritage appliqué.

--------------------

> ```
> This example demonstrates getting shape's effective line format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	ILineFormatEffectiveData effectiveLineFormat = pres.getSlides().get_Item(0).getShapes().get_Item(0).getLineFormat().getEffective();
>  	System.out.println("Style: " + effectiveLineFormat.getStyle());
>  	System.out.println("Width: " + effectiveLineFormat.getWidth());
>  	System.out.println("Fill type: " + effectiveLineFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Retour:**  
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - Un [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).