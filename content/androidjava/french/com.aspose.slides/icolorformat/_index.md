---
title: IColorFormat
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente une couleur utilisée dans une présentation.
type: docs
url: /fr/com.aspose.slides/icolorformat/
---
**Toutes les interfaces implémentées:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

Représente une couleur utilisée dans une présentation.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getColorType()](#getColorType--) | Retourne ou définit la méthode de définition de couleur. |
| [setColorType(int value)](#setColorType-int-) | Retourne ou définit la méthode de définition de couleur. |
| [getColor()](#getColor--) | Retourne la couleur résultante (avec toutes les transformations de couleur appliquées). |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Retourne la couleur résultante (avec toutes les transformations de couleur appliquées). |
| [getPresetColor()](#getPresetColor--) | Retourne ou définit le préréglage de couleur. |
| [setPresetColor(int value)](#setPresetColor-int-) | Retourne ou définit le préréglage de couleur. |
| [getSystemColor()](#getSystemColor--) | Retourne ou définit la couleur identifiée par la table des couleurs système. |
| [setSystemColor(int value)](#setSystemColor-int-) | Retourne ou définit la couleur identifiée par la table des couleurs système. |
| [getSchemeColor()](#getSchemeColor--) | Retourne ou définit la couleur identifiée par un jeu de couleurs. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Retourne ou définit la couleur identifiée par un jeu de couleurs. |
| [getR()](#getR--) | Retourne ou définit le composant rouge d’une couleur. |
| [setR(byte value)](#setR-byte-) | Retourne ou définit le composant rouge d’une couleur. |
| [getG()](#getG--) | Retourne ou définit le composant vert d’une couleur. |
| [setG(byte value)](#setG-byte-) | Retourne ou définit le composant vert d’une couleur. |
| [getB()](#getB--) | Retourne ou définit le composant bleu d’une couleur. |
| [setB(byte value)](#setB-byte-) | Retourne ou définit le composant bleu d’une couleur. |
| [getFloatR()](#getFloatR--) | Retourne ou définit le composant rouge d’une couleur. |
| [setFloatR(float value)](#setFloatR-float-) | Retourne ou définit le composant rouge d’une couleur. |
| [getFloatG()](#getFloatG--) | Retourne ou définit le composant vert d’une couleur. |
| [setFloatG(float value)](#setFloatG-float-) | Retourne ou définit le composant vert d’une couleur. |
| [getFloatB()](#getFloatB--) | Retourne ou définit le composant bleu d’une couleur. |
| [setFloatB(float value)](#setFloatB-float-) | Retourne ou définit le composant bleu d’une couleur. |
| [getHue()](#getHue--) | Retourne ou définit le composant teinte d’une couleur en représentation HSL. |
| [setHue(float value)](#setHue-float-) | Retourne ou définit le composant teinte d’une couleur en représentation HSL. |
| [getSaturation()](#getSaturation--) | Retourne ou définit le composant saturation d’une couleur en représentation HSL. |
| [setSaturation(float value)](#setSaturation-float-) | Retourne ou définit le composant saturation d’une couleur en représentation HSL. |
| [getLuminance()](#getLuminance--) | Retourne ou définit le composant luminance d’une couleur en représentation HSL. |
| [setLuminance(float value)](#setLuminance-float-) | Retourne ou définit le composant luminance d’une couleur en représentation HSL. |
| [getColorTransform()](#getColorTransform--) | Retourne la collection des transformations de couleur appliquées à une couleur. |
| [toString(int format)](#toString-int-) | Retourne une chaîne qui représente le format actuel de la couleur. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Copie le format de couleur depuis "color". |

### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

Retourne ou définit la méthode de définition de couleur. Lecture/écriture [ColorType](../../com.aspose.slides/colortype).

**Retourne:**
int

### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

Retourne ou définit la méthode de définition de couleur. Lecture/écriture [ColorType](../../com.aspose.slides/colortype).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public abstract Integer getColor()
```

Retourne la couleur résultante (avec toutes les transformations de couleur appliquées). Définit les couleurs RVB et supprime toutes les transformations de couleur. Lecture/écriture java.lang.Integer.

**Retourne:**
java.lang.Integer

### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

Retourne la couleur résultante (avec toutes les transformations de couleur appliquées). Définit les couleurs RVB et supprime toutes les transformations de couleur. Lecture/écriture java.lang.Integer.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

Retourne ou définit le préréglage de couleur. Lecture/écriture [PresetColor](../../com.aspose.slides/presetcolor).

**Retourne:**
int

### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

Retourne ou définit le préréglage de couleur. Lecture/écriture [PresetColor](../../com.aspose.slides/presetcolor).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

Retourne ou définit la couleur identifiée par la table des couleurs système. Lecture/écriture [SystemColor](../../com.aspose.slides/systemcolor).

**Retourne:**
int

### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

Retourne ou définit la couleur identifiée par la table des couleurs système. Lecture/écriture [SystemColor](../../com.aspose.slides/systemcolor).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

Retourne ou définit la couleur identifiée par un jeu de couleurs. Lecture/écriture [SchemeColor](../../com.aspose.slides/schemecolor).

**Retourne:**
int

### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

Retourne ou définit la couleur identifiée par un jeu de couleurs. Lecture/écriture [SchemeColor](../../com.aspose.slides/schemecolor).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public abstract byte getR()
```

Retourne ou définit le composant rouge d’une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture byte.

**Retourne:**
byte

### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

Retourne ou définit le composant rouge d’une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture byte.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public abstract byte getG()
```

Retourne ou définit le composant vert d’une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture byte.

**Retourne:**
byte

### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

Retourne ou définit le composant vert d’une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture byte.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public abstract byte getB()
```

Retourne ou définit le composant bleu d’une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture byte.

**Retourne:**
byte

### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

Retourne ou définit le composant bleu d’une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture byte.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

Retourne ou définit le composant rouge d’une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture float.

**Retourne:**
float

### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

Retourne ou définit le composant rouge d’une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture float.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

Retourne ou définit le composant vert d’une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture float.

**Retourne:**
float

### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

Retourne ou définit le composant vert d’une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture float.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

Retourne ou définit le composant bleu d’une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture float.

**Retourne:**
float

### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

Retourne ou définit le composant bleu d’une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture float.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public abstract float getHue()
```

Retourne ou définit le composant teinte d’une couleur en représentation HSL. Toutes les transformations de couleur sont ignorées. Lecture/écriture float.

**Retourne:**
float

### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

Retourne ou définit le composant teinte d’une couleur en représentation HSL. Toutes les transformations de couleur sont ignorées. Lecture/écriture float.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

Retourne ou définit le composant saturation d’une couleur en représentation HSL. Toutes les transformations de couleur sont ignorées. Lecture/écriture float.

**Retourne:**
float

### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

Retourne ou définit le composant saturation d’une couleur en représentation HSL. Toutes les transformations de couleur sont ignorées. Lecture/écriture float.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

Retourne ou définit le composant luminance d’une couleur en représentation HSL. Toutes les transformations de couleur sont ignorées. Lecture/écriture float.

**Retourne:**
float

### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

Retourne ou définit le composant luminance d’une couleur en représentation HSL. Toutes les transformations de couleur sont ignorées. Lecture/écriture float.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

Retourne la collection des transformations de couleur appliquées à une couleur. Lecture seule [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Retourne:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)

### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

Retourne une chaîne qui représente le format actuel de la couleur.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| format | int | Un type de format de chaîne de couleur. |

**Retourne:**
java.lang.String - Une chaîne qui représente le format actuel de la couleur.

### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

Copie le format de couleur depuis "color".

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Couleur [IColorFormat](../../com.aspose.slides/icolorformat) |