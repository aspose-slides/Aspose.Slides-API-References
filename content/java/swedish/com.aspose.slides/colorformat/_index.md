---
title: ColorFormat
second_title: Aspose.Slides för Java API-referens
description: Representerar en färg som används i en presentation.
type: docs
url: /sv/com.aspose.slides/colorformat/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IColorFormat](../../com.aspose.slides/icolorformat)
```
public final class ColorFormat extends PVIObject implements IColorFormat
```

Representerar en färg som används i en presentation.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getColorType()](#getColorType--) | Returnerar eller anger färgdefinitionsmetoden. |
| [setColorType(int value)](#setColorType-int-) | Returnerar eller anger färgdefinitionsmetoden. |
| [getColor()](#getColor--) | Returnerar den resulterande färgen (med alla färgtransformationer tillämpade). |
| [setColor(Color value)](#setColor-java.awt.Color-) | Returnerar den resulterande färgen (med alla färgtransformationer tillämpade). |
| [getPresetColor()](#getPresetColor--) | Returnerar eller anger förinställd färg. |
| [setPresetColor(int value)](#setPresetColor-int-) | Returnerar eller anger förinställd färg. |
| [getSystemColor()](#getSystemColor--) | Returnerar eller anger färgen identifierad av systemfärgtabellen. |
| [setSystemColor(int value)](#setSystemColor-int-) | Returnerar eller anger färgen identifierad av systemfärgtabellen. |
| [getSchemeColor()](#getSchemeColor--) | Returnerar eller anger färgen identifierad av ett färgschema. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Returnerar eller anger färgen identifierad av ett färgschema. |
| [getR()](#getR--) | Returnerar eller anger den röda komponenten i en färg. |
| [setR(byte value)](#setR-byte-) | Returnerar eller anger den röda komponenten i en färg. |
| [getG()](#getG--) | Returnerar eller anger den gröna komponenten i en färg. |
| [setG(byte value)](#setG-byte-) | Returnerar eller anger den gröna komponenten i en färg. |
| [getB()](#getB--) | Returnerar eller anger den blå komponenten i en färg. |
| [setB(byte value)](#setB-byte-) | Returnerar eller anger den blå komponenten i en färg. |
| [getFloatR()](#getFloatR--) | Returnerar eller anger den röda komponenten i en färg. |
| [setFloatR(float value)](#setFloatR-float-) | Returnerar eller anger den röda komponenten i en färg. |
| [getFloatG()](#getFloatG--) | Returnerar eller anger den gröna komponenten i en färg. |
| [setFloatG(float value)](#setFloatG-float-) | Returnerar eller anger den gröna komponenten i en färg. |
| [getFloatB()](#getFloatB--) | Returnerar eller anger den blå komponenten i en färg. |
| [setFloatB(float value)](#setFloatB-float-) | Returnerar eller anger den blå komponenten i en färg. |
| [getHue()](#getHue--) | Returnerar eller anger nyanskomponenten i en färg i HSL-representation. |
| [setHue(float value)](#setHue-float-) | Returnerar eller anger nyanskomponenten i en färg i HSL-representation. |
| [getSaturation()](#getSaturation--) | Returnerar eller anger mättnadskomponenten i en färg i HSL-representation. |
| [setSaturation(float value)](#setSaturation-float-) | Returnerar eller anger mättnadskomponenten i en färg i HSL-representation. |
| [getLuminance()](#getLuminance--) | Returnerar eller anger luminanskomponenten i en färg i HSL-representation. |
| [setLuminance(float value)](#setLuminance-float-) | Returnerar eller anger luminanskomponenten i en färg i HSL-representation. |
| [getColorTransform()](#getColorTransform--) | Returnerar samlingen av färgtransformationer som tillämpats på en färg. |
| [toString(int format)](#toString-int-) | Returnerar en String som representerar det aktuella färgformatet. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Kopiera färgformat från "color". |
| [equals(Object obj)](#equals-java.lang.Object-) | Kontrollerar likhet med angivet objekt. |
| [hashCode()](#hashCode--) | Returnerar hashkod. |
| [getVersion()](#getVersion--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |

### getColorType() {#getColorType--}
```
public final int getColorType()
```

Returnerar eller anger färgdefinitionsmetoden. Läs/skriv [ColorType](../../com.aspose.slides/colortype).

**Returnerar:**
int

### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```

Returnerar eller anger färgdefinitionsmetoden. Läs/skriv [ColorType](../../com.aspose.slides/colortype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public final Color getColor()
```

Returnerar den resulterande färgen (med alla färgtransformationer tillämpade). Ställer in RGB-färger och rensar alla färgtransformationer. Läs/skriv java.awt.Color.

**Returnerar:**
java.awt.Color

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```

Returnerar den resulterande färgen (med alla färgtransformationer tillämpade). Ställer in RGB-färger och rensar alla färgtransformationer. Läs/skriv java.awt.Color.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.awt.Color |  |

### getPresetColor() {#getPresetColor--}
```
public final int getPresetColor()
```

Returnerar eller anger förinställd färg. Läs/skriv [PresetColor](../../com.aspose.slides/presetcolor).

**Returnerar:**
int

### setPresetColor(int value) {#setPresetColor-int-}
```
public final void setPresetColor(int value)
```

Returnerar eller anger förinställd färg. Läs/skriv [PresetColor](../../com.aspose.slides/presetcolor).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public final int getSystemColor()
```

Returnerar eller anger färgen identifierad av systemfärgtabellen. Läs/skriv [SystemColor](../../com.aspose.slides/systemcolor).

**Returnerar:**
int

### setSystemColor(int value) {#setSystemColor-int-}
```
public final void setSystemColor(int value)
```

Returnerar eller anger färgen identifierad av systemfärgtabellen. Läs/skriv [SystemColor](../../com.aspose.slides/systemcolor).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public final int getSchemeColor()
```

Returnerar eller anger färgen identifierad av ett färgschema. Läs/skriv [SchemeColor](../../com.aspose.slides/schemecolor).

**Returnerar:**
int

### setSchemeColor(int value) {#setSchemeColor-int-}
```
public final void setSchemeColor(int value)
```

Returnerar eller anger färgen identifierad av ett färgschema. Läs/skriv [SchemeColor](../../com.aspose.slides/schemecolor).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public final byte getR()
```

Returnerar eller anger den röda komponenten i en färg. Alla färgtransformationer ignoreras. Läs/skriv  byte .

**Returnerar:**
byte

### setR(byte value) {#setR-byte-}
```
public final void setR(byte value)
```

Returnerar eller anger den röda komponenten i en färg. Alla färgtransformationer ignoreras. Läs/skriv  byte .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public final byte getG()
```

Returnerar eller anger den gröna komponenten i en färg. Alla färgtransformationer ignoreras.

**Returnerar:**
byte

### setG(byte value) {#setG-byte-}
```
public final void setG(byte value)
```

Returnerar eller anger den gröna komponenten i en färg. Alla färgtransformationer ignoreras.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public final byte getB()
```

Returnerar eller anger den blå komponenten i en färg. Alla färgtransformationer ignoreras. Läs/skriv  byte .

**Returnerar:**
byte

### setB(byte value) {#setB-byte-}
```
public final void setB(byte value)
```

Returnerar eller anger den blå komponenten i en färg. Alla färgtransformationer ignoreras. Läs/skriv  byte .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public final float getFloatR()
```

Returnerar eller anger den röda komponenten i en färg. Alla färgtransformationer ignoreras. Läs/skriv  float .

**Returnerar:**
float

### setFloatR(float value) {#setFloatR-float-}
```
public final void setFloatR(float value)
```

Returnerar eller anger den röda komponenten i en färg. Alla färgtransformationer ignoreras. Läs/skriv  float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public final float getFloatG()
```

Returnerar eller anger den gröna komponenten i en färg. Alla färgtransformationer ignoreras. Läs/skriv  float .

**Returnerar:**
float

### setFloatG(float value) {#setFloatG-float-}
```
public final void setFloatG(float value)
```

Returnerar eller anger den gröna komponenten i en färg. Alla färgtransformationer ignoreras. Läs/skriv  float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public final float getFloatB()
```

Returnerar eller anger den blå komponenten i en färg. Alla färgtransformationer ignoreras. Läs/skriv  float .

**Returnerar:**
float

### setFloatB(float value) {#setFloatB-float-}
```
public final void setFloatB(float value)
```

Returnerar eller anger den blå komponenten i en färg. Alla färgtransformationer ignoreras. Läs/skriv  float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public final float getHue()
```

Returnerar eller anger nyanskomponenten i en färg i HSL-representation. Alla färgtransformationer ignoreras. Läs/skriv  float .

**Returnerar:**
float

### setHue(float value) {#setHue-float-}
```
public final void setHue(float value)
```

Returnerar eller anger nyanskomponenten i en färg i HSL-representation. Alla färgtransformationer ignoreras. Läs/skriv  float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public final float getSaturation()
```

Returnerar eller anger mättnadskomponenten i en färg i HSL-representation. Alla färgtransformationer ignoreras. Läs/skriv  float .

**Returnerar:**
float

### setSaturation(float value) {#setSaturation-float-}
```
public final void setSaturation(float value)
```

Returnerar eller anger mättnadskomponenten i en färg i HSL-representation. Alla färgtransformationer ignoreras. Läs/skriv  float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public final float getLuminance()
```

Returnerar eller anger luminanskomponenten i en färg i HSL-representation. Alla färgtransformationer ignoreras. Läs/skriv  float .

**Returnerar:**
float

### setLuminance(float value) {#setLuminance-float-}
```
public final void setLuminance(float value)
```

Returnerar eller anger luminanskomponenten i en färg i HSL-representation. Alla färgtransformationer ignoreras. Läs/skriv  float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public final IColorOperationCollection getColorTransform()
```

Returnerar samlingen av färgtransformationer som tillämpats på en färg. Endast läsning [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Returnerar:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)

### toString(int format) {#toString-int-}
```
public final String toString(int format)
```

Returnerar en String som representerar det aktuella färgformatet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | int | En typ av färgsträngformat. |

**Returnerar:**
java.lang.String - En sträng som representerar det aktuella färgformatet.

### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public final void copyFrom(IColorFormat color)
```

Kopiera färgformat från "color".

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Kontrollerar likhet med angivet objekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objekt. |

**Returnerar:**
boolean - Sant om objekten är lika, annars falskt.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Returnerar hashkod.

**Returnerar:**
int - Hashkod.

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Endast läsning long.

**Returnerar:**
long

### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public final ISlideComponent getParent_ISlideComponent()
```

**Returnerar:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Returnerar föräldern IPresentationComponent. Endast läsning [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Returnerar:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)