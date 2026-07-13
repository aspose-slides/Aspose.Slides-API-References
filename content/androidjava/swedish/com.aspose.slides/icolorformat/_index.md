---
title: IColorFormat
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en färg som används i en presentation.
type: docs
url: /sv/com.aspose.slides/icolorformat/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

Representerar en färg som används i en presentation.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getColorType()](#getColorType--) | Returnerar eller anger färgdefinitionsmetoden. |
| [setColorType(int value)](#setColorType-int-) | Returnerar eller anger färgdefinitionsmetoden. |
| [getColor()](#getColor--) | Returnerar resulterande färg (med alla färgtransformeringar tillämpade). |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Returnerar resulterande färg (med alla färgtransformeringar tillämpade). |
| [getPresetColor()](#getPresetColor--) | Returnerar eller anger färgförinställning. |
| [setPresetColor(int value)](#setPresetColor-int-) | Returnerar eller anger färgförinställning. |
| [getSystemColor()](#getSystemColor--) | Returnerar eller anger färgen som identifieras av systemets färgtabell. |
| [setSystemColor(int value)](#setSystemColor-int-) | Returnerar eller anger färgen som identifieras av systemets färgtabell. |
| [getSchemeColor()](#getSchemeColor--) | Returnerar eller anger färgen som identifieras av ett färgschema. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Returnerar eller anger färgen som identifieras av ett färgschema. |
| [getR()](#getR--) | Returnerar eller anger den röda komponenten i en färg. |
| [setR(byte value)](#setR-byte-) | Returnerar eller anger den röda komponenten i en färg. |
| [getG()](#getG--) | Returnerar eller anger den gröna komponenten i en färg. |
| [setG(byte value)](#setG-byte-) | Returnerar eller anger den gröna komponenten i en färg. |
| [getB()](#getB--) | Returnerar eller anger den blåa komponenten i en färg. |
| [setB(byte value)](#setB-byte-) | Returnerar eller anger den blåa komponenten i en färg. |
| [getFloatR()](#getFloatR--) | Returnerar eller anger den röda komponenten i en färg. |
| [setFloatR(float value)](#setFloatR-float-) | Returnerar eller anger den röda komponenten i en färg. |
| [getFloatG()](#getFloatG--) | Returnerar eller anger den gröna komponenten i en färg. |
| [setFloatG(float value)](#setFloatG-float-) | Returnerar eller anger den gröna komponenten i en färg. |
| [getFloatB()](#getFloatB--) | Returnerar eller anger den blåa komponenten i en färg. |
| [setFloatB(float value)](#setFloatB-float-) | Returnerar eller anger den blåa komponenten i en färg. |
| [getHue()](#getHue--) | Returnerar eller anger nyansen för en färg i HSL-representation. |
| [setHue(float value)](#setHue-float-) | Returnerar eller anger nyansen för en färg i HSL-representation. |
| [getSaturation()](#getSaturation--) | Returnerar eller anger mättnadskomponenten för en färg i HSL-representation. |
| [setSaturation(float value)](#setSaturation-float-) | Returnerar eller anger mättnadskomponenten för en färg i HSL-representation. |
| [getLuminance()](#getLuminance--) | Returnerar eller anger luminanskomponenten för en färg i HSL-representation. |
| [setLuminance(float value)](#setLuminance-float-) | Returnerar eller anger luminanskomponenten för en färg i HSL-representation. |
| [getColorTransform()](#getColorTransform--) | Returnerar samlingen av färgtransformeringar som tillämpats på en färg. |
| [toString(int format)](#toString-int-) | Returnerar en sträng som representerar det aktuella färgformatet. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Kopiera färgformat från "color". |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

Returnerar eller anger färgdefinitionsmetoden. Läs/skriv [ColorType](../../com.aspose.slides/colortype).

**Returnerar:**
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

Returnerar eller anger färgdefinitionsmetoden. Läs/skriv [ColorType](../../com.aspose.slides/colortype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getColor() {#getColor--}
```
public abstract Integer getColor()
```

Returnerar resulterande färg (med alla färgtransformeringar tillämpade). Sätter RGB-färger och rensar alla färgtransformeringar. Läs/skriv java.lang.Integer.

**Returnerar:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

Returnerar resulterande färg (med alla färgtransformeringar tillämpade). Sätter RGB-färger och rensar alla färgtransformeringar. Läs/skriv java.lang.Integer.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.Integer |  |
### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

Returnerar eller anger färgförinställning. Läs/skriv [PresetColor](../../com.aspose.slides/presetcolor).

**Returnerar:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

Returnerar eller anger färgförinställning. Läs/skriv [PresetColor](../../com.aspose.slides/presetcolor).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

Returnerar eller anger färgen som identifieras av systemets färgtabell. Läs/skriv [SystemColor](../../com.aspose.slides/systemcolor).

**Returnerar:**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

Returnerar eller anger färgen som identifieras av systemets färgtabell. Läs/skriv [SystemColor](../../com.aspose.slides/systemcolor).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

Returnerar eller anger färgen som identifieras av ett färgschema. Läs/skriv [SchemeColor](../../com.aspose.slides/schemecolor).

**Returnerar:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

Returnerar eller anger färgen som identifieras av ett färgschema. Läs/skriv [SchemeColor](../../com.aspose.slides/schemecolor).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getR() {#getR--}
```
public abstract byte getR()
```

Returnerar eller anger den röda komponenten i en färg. Alla färgtransformeringar ignoreras. Läs/skriv byte.

**Returnerar:**
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

Returnerar eller anger den röda komponenten i en färg. Alla färgtransformeringar ignoreras. Läs/skriv byte.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getG() {#getG--}
```
public abstract byte getG()
```

Returnerar eller anger den gröna komponenten i en färg. Alla färgtransformeringar ignoreras. Läs/skriv byte.

**Returnerar:**
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

Returnerar eller anger den gröna komponenten i en färg. Alla färgtransformeringar ignoreras. Läs/skriv byte.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getB() {#getB--}
```
public abstract byte getB()
```

Returnerar eller anger den blåa komponenten i en färg. Alla färgtransformeringar ignoreras. Läs/skriv byte.

**Returnerar:**
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

Returnerar eller anger den blåa komponenten i en färg. Alla färgtransformeringar ignoreras. Läs/skriv byte.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

Returnerar eller anger den röda komponenten i en färg. Alla färgtransformeringar ignoreras. Läs/skriv float.

**Returnerar:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

Returnerar eller anger den röda komponenten i en färg. Alla färgtransformeringar ignoreras. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

Returnerar eller anger den gröna komponenten i en färg. Alla färgtransformeringar ignoreras. Läs/skriv float.

**Returnerar:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

Returnerar eller anger den gröna komponenten i en färg. Alla färgtransformeringar ignoreras. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

Returnerar eller anger den blåa komponenten i en färg. Alla färgtransformeringar ignoreras. Läs/skriv float.

**Returnerar:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

Returnerar eller anger den blåa komponenten i en färg. Alla färgtransformeringar ignoreras. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getHue() {#getHue--}
```
public abstract float getHue()
```

Returnerar eller anger nyansen för en färg i HSL-representation. Alla färgtransformeringar ignoreras. Läs/skriv float.

**Returnerar:**
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

Returnerar eller anger nyansen för en färg i HSL-representation. Alla färgtransformeringar ignoreras. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

Returnerar eller anger mättnadskomponenten för en färg i HSL-representation. Alla färgtransformeringar ignoreras. Läs/skriv float.

**Returnerar:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

Returnerar eller anger mättnadskomponenten för en färg i HSL-representation. Alla färgtransformeringar ignoreras. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

Returnerar eller anger luminanskomponenten för en färg i HSL-representation. Alla färgtransformeringar ignoreras. Läs/skriv float.

**Returnerar:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

Returnerar eller anger luminanskomponenten för en färg i HSL-representation. Alla färgtransformeringar ignoreras. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

Returnerar samlingen av färgtransformeringar som tillämpats på en färg. Skrivskyddad [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Returnerar:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

Returnerar en sträng som representerar det aktuella färgformatet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | int | En typ av färgsträngformat. |

**Returnerar:**
java.lang.String - En sträng som representerar det aktuella färgformatet.
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

Kopiera färgformat från "color".

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Color [IColorFormat](../../com.aspose.slides/icolorformat) |