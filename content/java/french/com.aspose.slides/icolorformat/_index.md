---
title: IColorFormat
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une couleur utilisée dans une présentation.
type: docs
url: /fr/com.aspose.slides/icolorformat/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

Représente une couleur utilisée dans une présentation.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getColorType()](#getColorType--) | Renvoie ou définit la méthode de définition de la couleur. |
| [setColorType(int value)](#setColorType-int-) | Renvoie ou définit la méthode de définition de la couleur. |
| [getColor()](#getColor--) | Renvoie la couleur résultante (avec toutes les transformations de couleur appliquées). |
| [setColor(Color value)](#setColor-java.awt.Color-) | Renvoie la couleur résultante (avec toutes les transformations de couleur appliquées). |
| [getPresetColor()](#getPresetColor--) | Renvoie ou définit la couleur prédéfinie. |
| [setPresetColor(int value)](#setPresetColor-int-) | Renvoie ou définit la couleur prédéfinie. |
| [getSystemColor()](#getSystemColor--) | Renvoie ou définit la couleur identifiée par la table des couleurs système. |
| [setSystemColor(int value)](#setSystemColor-int-) | Renvoie ou définit la couleur identifiée par la table des couleurs système. |
| [getSchemeColor()](#getSchemeColor--) | Renvoie ou définit la couleur identifiée par un schéma de couleurs. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Renvoie ou définit la couleur identifiée par un schéma de couleurs. |
| [getR()](#getR--) | Renvoie ou définit le composant rouge d’une couleur. |
| [setR(byte value)](#setR-byte-) | Renvoie ou définit le composant rouge d’une couleur. |
| [getG()](#getG--) | Renvoie ou définit le composant vert d’une couleur. |
| [setG(byte value)](#setG-byte-) | Renvoie ou définit le composant vert d’une couleur. |
| [getB()](#getB--) | Renvoie ou définit le composant bleu d’une couleur. |
| [setB(byte value)](#setB-byte-) | Renvoie ou définit le composant bleu d’une couleur. |
| [getFloatR()](#getFloatR--) | Renvoie ou définit le composant rouge d’une couleur. |
| [setFloatR(float value)](#setFloatR-float-) | Renvoie ou définit le composant rouge d’une couleur. |
| [getFloatG()](#getFloatG--) | Renvoie ou définit le composant vert d’une couleur. |
| [setFloatG(float value)](#setFloatG-float-) | Renvoie ou définit le composant vert d’une couleur. |
| [getFloatB()](#getFloatB--) | Renvoie ou définit le composant bleu d’une couleur. |
| [setFloatB(float value)](#setFloatB-float-) | Renvoie ou définit le composant bleu d’une couleur. |
| [getHue()](#getHue--) | Renvoie ou définit le composant teinte d’une couleur en représentation HSL. |
| [setHue(float value)](#setHue-float-) | Renvoie ou définit le composant teinte d’une couleur en représentation HSL. |
| [getSaturation()](#getSaturation--) | Renvoie ou définit le composant saturation d’une couleur en représentation HSL. |
| [setSaturation(float value)](#setSaturation-float-) | Renvoie ou définit le composant saturation d’une couleur en représentation HSL. |
| [getLuminance()](#getLuminance--) | Renvoie ou définit le composant luminance d’une couleur en représentation HSL. |
| [setLuminance(float value)](#setLuminance-float-) | Renvoie ou définit le composant luminance d’une couleur en représentation HSL. |
| [getColorTransform()](#getColorTransform--) | Renvoie la collection des transformations de couleur appliquées à une couleur. |
| [toString(int format)](#toString-int-) | Renvoie une String qui représente le format de couleur actuel. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Copier le format de couleur depuis "color". |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

Renvoie ou définit la méthode de définition de la couleur. Lecture/écriture [ColorType](../../com.aspose.slides/colortype).

**Retour :**
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

Renvoie ou définit la méthode de définition de la couleur. Lecture/écriture [ColorType](../../com.aspose.slides/colortype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public abstract Color getColor()
```

Renvoie la couleur résultante (avec toutes les transformations de couleur appliquées). Définit les couleurs RGB et supprime toutes les transformations de couleur. Lecture/écriture java.awt.Color.

**Retour :**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

Renvoie la couleur résultante (avec toutes les transformations de couleur appliquées). Définit les couleurs RGB et supprime toutes les transformations de couleur. Lecture/écriture java.awt.Color.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

Renvoie ou définit la couleur prédéfinie. Lecture/écriture [PresetColor](../../com.aspose.slides/presetcolor).

**Retour :**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

Renvoie ou définit la couleur prédéfinie. Lecture/écriture [PresetColor](../../com.aspose.slides/presetcolor).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

Renvoie ou définit la couleur identifiée par la table des couleurs système. Lecture/écriture [SystemColor](../../com.aspose.slides/systemcolor).

**Retour :**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

Renvoie ou définit la couleur identifiée par la table des couleurs système. Lecture/écriture [SystemColor](../../com.aspose.slides/systemcolor).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

Renvoie ou définit la couleur identifiée par un schéma de couleurs. Lecture/écriture [SchemeColor](../../com.aspose.slides/schemecolor).

**Retour :**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

Renvoie ou définit la couleur identifiée par un schéma de couleurs. Lecture/écriture [SchemeColor](../../com.aspose.slides/schemecolor).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public abstract byte getR()
```

Renvoie ou définit le composant rouge d’une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture byte.

**Retour :**
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

Renvoie ou définit le composant rouge d’une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture byte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public abstract byte getG()
```

Renvoie ou définit le composant vert d’une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture byte.

**Retour :**
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

Renvoie ou définit le composant vert d’une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture byte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public abstract byte getB()
```

Renvoie ou définit le composant bleu d’une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture byte.

**Retour :**
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

Renvoie ou définit le composant bleu d’une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture byte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

Renvoie ou définit le composant rouge d’une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture float.

**Retour :**
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

Renvoie ou définit le composant rouge d’une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

Renvoie ou définit le composant vert d’une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture float.

**Retour :**
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

Renvoie ou définit le composant vert d’une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

Renvoie ou définit le composant bleu d’une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture float.

**Retour :**
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

Renvoie ou définit le composant bleu d’une couleur. Toutes les transformations de couleur sont ignorées. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public abstract float getHue()
```

Renvoie ou définit le composant teinte d’une couleur en représentation HSL. Toutes les transformations de couleur sont ignorées. Lecture/écriture float.

**Retour :**
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

Renvoie ou définit le composant teinte d’une couleur en représentation HSL. Toutes les transformations de couleur sont ignorées. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

Renvoie ou définit le composant saturation d’une couleur en représentation HSL. Toutes les transformations de couleur sont ignorées. Lecture/écriture float.

**Retour :**
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

Renvoie ou définit le composant saturation d’une couleur en représentation HSL. Toutes les transformations de couleur sont ignorées. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

Renvoie ou définit le composant luminance d’une couleur en représentation HSL. Toutes les transformations de couleur sont ignorées. Lecture/écriture float.

**Retour :**
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

Renvoie ou définit le composant luminance d’une couleur en représentation HSL. Toutes les transformations de couleur sont ignorées. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

Renvoie la collection des transformations de couleur appliquées à une couleur. Lecture seule [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Retour :**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

Renvoie une chaîne qui représente le format de couleur actuel.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| format | int | Un type de format de chaîne de couleur. |

**Retour :**
java.lang.String - Une chaîne qui représente le format de couleur actuel.
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

Copier le format de couleur depuis "color".

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Color [IColorFormat](../../com.aspose.slides/icolorformat) |