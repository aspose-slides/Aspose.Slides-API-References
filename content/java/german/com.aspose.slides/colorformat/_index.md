---
title: ColorFormat
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine in einer Präsentation verwendete Farbe dar.
type: docs
url: /de/com.aspose.slides/colorformat/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IColorFormat](../../com.aspose.slides/icolorformat)
```
public final class ColorFormat extends PVIObject implements IColorFormat
```

Stellt eine in einer Präsentation verwendete Farbe dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColorType()](#getColorType--) | Gibt die Farbdefinitionsmethode zurück oder legt sie fest. |
| [setColorType(int value)](#setColorType-int-) | Gibt die Farbdefinitionsmethode zurück oder legt sie fest. |
| [getColor()](#getColor--) | Gibt die resultierende Farbe zurück (mit allen Farbtransformationen angewendet). |
| [setColor(Color value)](#setColor-java.awt.Color-) | Gibt die resultierende Farbe zurück (mit allen Farbtransformationen angewendet). |
| [getPresetColor()](#getPresetColor--) | Gibt die Farbvoreinstellung zurück oder legt sie fest. |
| [setPresetColor(int value)](#setPresetColor-int-) | Gibt die Farbvoreinstellung zurück oder legt sie fest. |
| [getSystemColor()](#getSystemColor--) | Gibt die Farbe zurück, die durch die Systemfarbtabelle identifiziert wird, oder legt sie fest. |
| [setSystemColor(int value)](#setSystemColor-int-) | Gibt die Farbe zurück, die durch die Systemfarbtabelle identifiziert wird, oder legt sie fest. |
| [getSchemeColor()](#getSchemeColor--) | Gibt die Farbe zurück, die durch ein Farbschema identifiziert wird, oder legt sie fest. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Gibt die Farbe zurück, die durch ein Farbschema identifiziert wird, oder legt sie fest. |
| [getR()](#getR--) | Gibt die Rotkomponente einer Farbe zurück oder legt sie fest. |
| [setR(byte value)](#setR-byte-) | Gibt die Rotkomponente einer Farbe zurück oder legt sie fest. |
| [getG()](#getG--) | Gibt die Grünkomponente einer Farbe zurück oder legt sie fest. |
| [setG(byte value)](#setG-byte-) | Gibt die Grünkomponente einer Farbe zurück oder legt sie fest. |
| [getB()](#getB--) | Gibt die Blaukomponente einer Farbe zurück oder legt sie fest. |
| [setB(byte value)](#setB-byte-) | Gibt die Blaukomponente einer Farbe zurück oder legt sie fest. |
| [getFloatR()](#getFloatR--) | Gibt die Rotkomponente einer Farbe zurück oder legt sie fest. |
| [setFloatR(float value)](#setFloatR-float-) | Gibt die Rotkomponente einer Farbe zurück oder legt sie fest. |
| [getFloatG()](#getFloatG--) | Gibt die Grünkomponente einer Farbe zurück oder legt sie fest. |
| [setFloatG(float value)](#setFloatG-float-) | Gibt die Grünkomponente einer Farbe zurück oder legt sie fest. |
| [getFloatB()](#getFloatB--) | Gibt die Blaukomponente einer Farbe zurück oder legt sie fest. |
| [setFloatB(float value)](#setFloatB-float-) | Gibt die Blaukomponente einer Farbe zurück oder legt sie fest. |
| [getHue()](#getHue--) | Gibt die Farbtonkomponente einer Farbe in HSL-Darstellung zurück oder legt sie fest. |
| [setHue(float value)](#setHue-float-) | Gibt die Farbtonkomponente einer Farbe in HSL-Darstellung zurück oder legt sie fest. |
| [getSaturation()](#getSaturation--) | Gibt die Sättigungskomponente einer Farbe in HSL-Darstellung zurück oder legt sie fest. |
| [setSaturation(float value)](#setSaturation-float-) | Gibt die Sättigungskomponente einer Farbe in HSL-Darstellung zurück oder legt sie fest. |
| [getLuminance()](#getLuminance--) | Gibt die Luminanzkomponente einer Farbe in HSL-Darstellung zurück oder legt sie fest. |
| [setLuminance(float value)](#setLuminance-float-) | Gibt die Luminanzkomponente einer Farbe in HSL-Darstellung zurück oder legt sie fest. |
| [getColorTransform()](#getColorTransform--) | Gibt die Sammlung von Farbtransformationen zurück, die auf eine Farbe angewendet wurden. |
| [toString(int format)](#toString-int-) | Gibt einen String zurück, der das aktuelle Farbformat darstellt. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Kopiert das Farbformat von "color". |
| [equals(Object obj)](#equals-java.lang.Object-) | Prüft die Gleichheit mit dem angegebenen Objekt. |
| [hashCode()](#hashCode--) | Gibt den Hashcode zurück. |
| [getVersion()](#getVersion--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |

### getColorType() {#getColorType--}
```
public final int getColorType()
```

Gibt die Farbdefinitionsmethode zurück oder legt sie fest. Lesen/Schreiben [ColorType](../../com.aspose.slides/colortype).

**Rückgabe:**
int

### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```

Gibt die Farbdefinitionsmethode zurück oder legt sie fest. Lesen/Schreiben [ColorType](../../com.aspose.slides/colortype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public final Color getColor()
```

Gibt die resultierende Farbe zurück (mit allen Farbtransformationen angewendet). Setzt RGB-Farben und löscht alle Farbtransformationen. Lesen/Schreiben java.awt.Color.

**Rückgabe:**
java.awt.Color

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```

Gibt die resultierende Farbe zurück (mit allen Farbtransformationen angewendet). Setzt RGB-Farben und löscht alle Farbtransformationen. Lesen/Schreiben java.awt.Color.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.awt.Color |  |

### getPresetColor() {#getPresetColor--}
```
public final int getPresetColor()
```

Gibt die Farbvoreinstellung zurück oder legt sie fest. Lesen/Schreiben [PresetColor](../../com.aspose.slides/presetcolor).

**Rückgabe:**
int

### setPresetColor(int value) {#setPresetColor-int-}
```
public final void setPresetColor(int value)
```

Gibt die Farbvoreinstellung zurück oder legt sie fest. Lesen/Schreiben [PresetColor](../../com.aspose.slides/presetcolor).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public final int getSystemColor()
```

Gibt die Farbe zurück, die durch die Systemfarbtabelle identifiziert wird, oder legt sie fest. Lesen/Schreiben [SystemColor](../../com.aspose.slides/systemcolor).

**Rückgabe:**
int

### setSystemColor(int value) {#setSystemColor-int-}
```
public final void setSystemColor(int value)
```

Gibt die Farbe zurück, die durch die Systemfarbtabelle identifiziert wird, oder legt sie fest. Lesen/Schreiben [SystemColor](../../com.aspose.slides/systemcolor).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public final int getSchemeColor()
```

Gibt die Farbe zurück, die durch ein Farbschema identifiziert wird, oder legt sie fest. Lesen/Schreiben [SchemeColor](../../com.aspose.slides/schemecolor).

**Rückgabe:**
int

### setSchemeColor(int value) {#setSchemeColor-int-}
```
public final void setSchemeColor(int value)
```

Gibt die Farbe zurück, die durch ein Farbschema identifiziert wird, oder legt sie fest. Lesen/Schreiben [SchemeColor](../../com.aspose.slides/schemecolor).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public final byte getR()
```

Gibt die Rotkomponente einer Farbe zurück oder legt sie fest. Alle Farbtransformationen werden ignoriert. Lesen/Schreiben  byte .

**Rückgabe:**
byte

### setR(byte value) {#setR-byte-}
```
public final void setR(byte value)
```

Gibt die Rotkomponente einer Farbe zurück oder legt sie fest. Alle Farbtransformationen werden ignoriert. Lesen/Schreiben  byte .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public final byte getG()
```

Gibt die Grünkomponente einer Farbe zurück oder legt sie fest. Alle Farbtransformationen werden ignoriert.

**Rückgabe:**
byte

### setG(byte value) {#setG-byte-}
```
public final void setG(byte value)
```

Gibt die Grünkomponente einer Farbe zurück oder legt sie fest. Alle Farbtransformationen werden ignoriert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public final byte getB()
```

Gibt die Blaukomponente einer Farbe zurück oder legt sie fest. Alle Farbtransformationen werden ignoriert. Lesen/Schreiben  byte .

**Rückgabe:**
byte

### setB(byte value) {#setB-byte-}
```
public final void setB(byte value)
```

Gibt die Blaukomponente einer Farbe zurück oder legt sie fest. Alle Farbtransformationen werden ignoriert. Lesen/Schreiben  byte .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public final float getFloatR()
```

Gibt die Rotkomponente einer Farbe zurück oder legt sie fest. Alle Farbtransformationen werden ignoriert. Lesen/Schreiben  float .

**Rückgabe:**
float

### setFloatR(float value) {#setFloatR-float-}
```
public final void setFloatR(float value)
```

Gibt die Rotkomponente einer Farbe zurück oder legt sie fest. Alle Farbtransformationen werden ignoriert. Lesen/Schreiben  float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public final float getFloatG()
```

Gibt die Grünkomponente einer Farbe zurück oder legt sie fest. Alle Farbtransformationen werden ignoriert. Lesen/Schreiben  float .

**Rückgabe:**
float

### setFloatG(float value) {#setFloatG-float-}
```
public final void setFloatG(float value)
```

Gibt die Grünkomponente einer Farbe zurück oder legt sie fest. Alle Farbtransformationen werden ignoriert. Lesen/Schreiben  float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public final float getFloatB()
```

Gibt die Blaukomponente einer Farbe zurück oder legt sie fest. Alle Farbtransformationen werden ignoriert. Lesen/Schreiben  float .

**Rückgabe:**
float

### setFloatB(float value) {#setFloatB-float-}
```
public final void setFloatB(float value)
```

Gibt die Blaukomponente einer Farbe zurück oder legt sie fest. Alle Farbtransformationen werden ignoriert. Lesen/Schreiben  float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public final float getHue()
```

Gibt die Farbtonkomponente einer Farbe in HSL-Darstellung zurück oder legt sie fest. Alle Farbtransformationen werden ignoriert. Lesen/Schreiben  float .

**Rückgabe:**
float

### setHue(float value) {#setHue-float-}
```
public final void setHue(float value)
```

Gibt die Farbtonkomponente einer Farbe in HSL-Darstellung zurück oder legt sie fest. Alle Farbtransformationen werden ignoriert. Lesen/Schreiben  float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public final float getSaturation()
```

Gibt die Sättigungskomponente einer Farbe in HSL-Darstellung zurück oder legt sie fest. Alle Farbtransformationen werden ignoriert. Lesen/Schreiben  float .

**Rückgabe:**
float

### setSaturation(float value) {#setSaturation-float-}
```
public final void setSaturation(float value)
```

Gibt die Sättigungskomponente einer Farbe in HSL-Darstellung zurück oder legt sie fest. Alle Farbtransformationen werden ignoriert. Lesen/Schreiben  float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public final float getLuminance()
```

Gibt die Luminanzkomponente einer Farbe in HSL-Darstellung zurück oder legt sie fest. Alle Farbtransformationen werden ignoriert. Lesen/Schreiben  float .

**Rückgabe:**
float

### setLuminance(float value) {#setLuminance-float-}
```
public final void setLuminance(float value)
```

Gibt die Luminanzkomponente einer Farbe in HSL-Darstellung zurück oder legt sie fest. Alle Farbtransformationen werden ignoriert. Lesen/Schreiben  float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public final IColorOperationCollection getColorTransform()
```

Gibt die Sammlung von Farbtransformationen zurück, die auf eine Farbe angewendet wurden. Nur-Lesen [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Rückgabe:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)

### toString(int format) {#toString-int-}
```
public final String toString(int format)
```

Gibt einen String zurück, der das aktuelle Farbformat darstellt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | int | Ein Typ des Farbstring-Formats. |

**Rückgabe:**
java.lang.String - Ein String, der das aktuelle Farbformat darstellt.

### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public final void copyFrom(IColorFormat color)
```

Kopiert das Farbformat von "color".

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Prüft die Gleichheit mit dem angegebenen Objekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Objekt. |

**Rückgabe:**
boolean - True if objects are equal, otherwise false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Gibt den Hashcode zurück.

**Rückgabe:**
int - Hash code.

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur-Lesen long.

**Rückgabe:**
long

### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public final ISlideComponent getParent_ISlideComponent()
```

**Rückgabe:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Gibt das übergeordnete IPresentationComponent zurück. Nur-Lesen [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Rückgabe:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)