---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents formatting properties for chart text elements.
type: docs
url: /hu/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

Represents formatting properties for chart text elements.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | Visszaadja vagy beállítja a függőleges rögzítő szöveget egy TextFrame-ben. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Visszaadja vagy beállítja a függőleges rögzítő szöveget egy TextFrame-ben. |
| [getCenterText()](#getCenterText--) | Ha NullableBool.True, akkor a szöveget vízszintesen középre kell helyezni a keretben. |
| [setCenterText(byte value)](#setCenterText-byte-) | Ha NullableBool.True, akkor a szöveget vízszintesen középre kell helyezni a keretben. |
| [getTextVerticalType()](#getTextVerticalType--) | Meghatározza a szöveg tájolását. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Meghatározza a szöveg tájolását. |
| [getMarginLeft()](#getMarginLeft--) | Visszaadja vagy beállítja a bal margót (pontban) egy TextFrame-ben. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Visszaadja vagy beállítja a bal margót (pontban) egy TextFrame-ben. |
| [getMarginRight()](#getMarginRight--) | Visszaadja vagy beállítja a jobb margót (pontban) egy TextFrame-ben. |
| [setMarginRight(double value)](#setMarginRight-double-) | Visszaadja vagy beállítja a jobb margót (pontban) egy TextFrame-ben. |
| [getMarginTop()](#getMarginTop--) | Visszaadja vagy beállítja a felső margót (pontban) egy TextFrame-ben. |
| [setMarginTop(double value)](#setMarginTop-double-) | Visszaadja vagy beállítja a felső margót (pontban) egy TextFrame-ben. |
| [getMarginBottom()](#getMarginBottom--) | Visszaadja vagy beállítja az alsó margót (pontban) egy TextFrame-ben. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Visszaadja vagy beállítja az alsó margót (pontban) egy TextFrame-ben. |
| [getWrapText()](#getWrapText--) | Igaz, ha a szöveg a TextFrame margóinál sortörést kap. |
| [setWrapText(byte value)](#setWrapText-byte-) | Igaz, ha a szöveg a TextFrame margóinál sortörést kap. |
| [getAutofitType()](#getAutofitType--) | Visszaadja vagy beállítja a szöveg automatikus illesztési módját. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Visszaadja vagy beállítja a szöveg automatikus illesztési módját. |
| [getRotationAngle()](#getRotationAngle--) | Megadja a szövegre a keretben alkalmazott egyéni forgatást. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Megadja a szövegre a keretben alkalmazott egyéni forgatást. |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Visszaadja vagy beállítja a függőleges rögzítő szöveget egy TextFrame-ben. Olvasás/írás [TextAnchorType](../../com.aspose.slides/textanchortype).

**Visszatérési érték:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Visszaadja vagy beállítja a függőleges rögzítő szöveget egy TextFrame-ben. Olvasás/írás [TextAnchorType](../../com.aspose.slides/textanchortype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Ha NullableBool.True, akkor a szöveget vízszintesen középre kell helyezni a keretben. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatérési érték:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Ha NullableBool.True, akkor a szöveget vízszintesen középre kell helyezni a keretben. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Meghatározza a szöveg tájolását. A vizuális szövegforgatás értéke ebből a tulajdonságból és a RotationAngle egyéni szögéből származik. Olvasás/írás [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Visszatérési érték:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Meghatározza a szöveg tájolását. A vizuális szövegforgatás értéke ebből a tulajdonságból és a RotationAngle egyéni szögéből származik. Olvasás/írás [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Visszaadja vagy beállítja a bal margót (pontban) egy TextFrame-ben. Ennek a tulajdonságnak a módosítása csak a következő diagramrészletekre lehet hatással: DataLabel és DataLabelFormat (teljes támogatás a PowerPoint 2013-ban; a PowerPoint 2007-ben nincs hatása a megjelenítésre). Olvasás/írás double.

**Visszatérési érték:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Visszaadja vagy beállítja a bal margót (pontban) egy TextFrame-ben. Ennek a tulajdonságnak a módosítása csak a következő diagramrészletekre lehet hatással: DataLabel és DataLabelFormat (teljes támogatás a PowerPoint 2013-ban; a PowerPoint 2007-ben nincs hatása a megjelenítésre). Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Visszaadja vagy beállítja a jobb margót (pontban) egy TextFrame-ben. Ennek a tulajdonságnak a módosítása csak a következő diagramrészletekre lehet hatással: DataLabel és DataLabelFormat (teljes támogatás a PowerPoint 2013-ban; a PowerPoint 2007-ben nincs hatása a megjelenítésre). Olvasás/írás double.

**Visszatérési érték:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Visszaadja vagy beállítja a jobb margót (pontban) egy TextFrame-ben. Ennek a tulajdonságnak a módosítása csak a következő diagramrészletekre lehet hatással: DataLabel és DataLabelFormat (teljes támogatás a PowerPoint 2013-ban; a PowerPoint 2007-ben nincs hatása a megjelenítésre). Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Visszaadja vagy beállítja a felső margót (pontban) egy TextFrame-ben. Ennek a tulajdonságnak a módosítása csak a következő diagramrészletekre lehet hatással: DataLabel és DataLabelFormat (teljes támogatás a PowerPoint 2013-ban; a PowerPoint 2007-ben nincs hatása a megjelenítésre). Olvasás/írás double.

**Visszatérési érték:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Visszaadja vagy beállítja a felső margót (pontban) egy TextFrame-ben. Ennek a tulajdonságnak a módosítása csak a következő diagramrészletekre lehet hatással: DataLabel és DataLabelFormat (teljes támogatás a PowerPoint 2013-ban; a PowerPoint 2007-ben nincs hatása a megjelenítésre). Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Visszaadja vagy beállítja az alsó margót (pontban) egy TextFrame-ben. Ennek a tulajdonságnak a módosítása csak a következő diagramrészletekre lehet hatással: DataLabel és DataLabelFormat (teljes támogatás a PowerPoint 2013-ban; a PowerPoint 2007-ben nincs hatása a megjelenítésre). Olvasás/írás double.

**Visszatérési érték:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Visszaadja vagy beállítja az alsó margót (pontban) egy TextFrame-ben. Ennek a tulajdonságnak a módosítása csak a következő diagramrészletekre lehet hatással: DataLabel és DataLabelFormat (teljes támogatás a PowerPoint 2013-ban; a PowerPoint 2007-ben nincs hatása a megjelenítésre). Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Igaz, ha a szöveg a TextFrame margóinál sortörést kap. Ennek a tulajdonságnak a módosítása csak a következő diagramrészletekre lehet hatással: DataLabel és DataLabelFormat (teljes támogatás a PowerPoint 2007/2013-ban). Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatérési érték:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Igaz, ha a szöveg a TextFrame margóinál sortörést kap. Ennek a tulajdonságnak a módosítása csak a következő diagramrészletekre lehet hatással: DataLabel és DataLabelFormat (teljes támogatás a PowerPoint 2007/2013-ban). Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Visszaadja vagy beállítja a szöveg automatikus illesztési módját. Ennek a tulajdonságnak a módosítása csak a következő diagramrészletekre lehet hatással: DataLabel és DataLabelFormat (teljes támogatás a PowerPoint 2013-ban; a PowerPoint 2007-ben nincs hatása a megjelenítésre). Olvasás/írás [TextAutofitType](../../com.aspose.slides/textautofittype).

**Visszatérési érték:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Visszaadja vagy beállítja a szöveg automatikus illesztési módját. Ennek a tulajdonságnak a módosítása csak a következő diagramrészletekre lehet hatással: DataLabel és DataLabelFormat (teljes támogatás a PowerPoint 2013-ban; a PowerPoint 2007-ben nincs hatása a megjelenítésre). Olvasás/írás [TextAutofitType](../../com.aspose.slides/textautofittype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Megadja a szövegre a keretben alkalmazott egyéni forgatást. Ha nincs megadva, a kísérő alakzat forgatása kerül felhasználásra. Ha meg van adva, akkor ez függetlenül az alakzattól kerül alkalmazásra. Vagyis az alakzat kaphat forgatást a szöveg forgatása mellett is. A vizuális szövegforgatás értéke ebből a tulajdonságból és a TextVerticalType előre definiált függőleges típusából származik. Olvasás/írás float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Visszatérési érték:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Megadja a szövegre a keretben alkalmazott egyéni forgatást. Ha nincs megadva, a kísérő alakzat forgatása kerül felhasználásra. Ha meg van adva, akkor ez függetlenül az alakzattól kerül alkalmazásra. Vagyis az alakzat kaphat forgatást a szöveg forgatása mellett is. A vizuális szövegforgatás értéke ebből a tulajdonságból és a TextVerticalType előre definiált függőleges típusából származik. Olvasás/írás float.

--------------------

> ```
> Tekintse meg azt az esetet, amikor egy alakzatra 90 fokos, óramutató járásával megegyező irányú forgatás van alkalmazva. 
>  Emellett a szövegtest is -90 fokos, óramutató járásával ellentétes irányú forgatással rendelkezik. 
>  Ekkor a keletkezett alakzat forgatottnak tűnik, de benne lévő szöveg úgy jelenik meg, mintha egyáltalán nem lett volna elforgatva. 
```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |