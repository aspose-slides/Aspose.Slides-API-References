---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Java API Reference
description: Represents formatting properties for chart text elements.
type: docs
url: /hu/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

A diagram szövegeleminek formázási tulajdonságait képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | Visszaadja vagy beállítja a függőleges rögzítő szöveget egy TextFrame-ben. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Visszaadja vagy beállítja a függőleges rögzítő szöveget egy TextFrame-ben. |
| [getCenterText()](#getCenterText--) | Ha NullableBool.True, akkor a szöveget vízszintesen középre kell igazítani a keretben. |
| [setCenterText(byte value)](#setCenterText-byte-) | Ha NullableBool.True, akkor a szöveget vízszintesen középre kell igazítani a keretben. |
| [getTextVerticalType()](#getTextVerticalType--) | Meghatározza a szöveg tájolását. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Meghatározza a szöveg tájolását. |
| [getMarginLeft()](#getMarginLeft--) | Visszaadja vagy beállítja a bal margót (pont) egy TextFrame-ben. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Visszaadja vagy beállítja a bal margót (pont) egy TextFrame-ben. |
| [getMarginRight()](#getMarginRight--) | Visszaadja vagy beállítja a jobb margót (pont) egy TextFrame-ben. |
| [setMarginRight(double value)](#setMarginRight-double-) | Visszaadja vagy beállítja a jobb margót (pont) egy TextFrame-ben. |
| [getMarginTop()](#getMarginTop--) | Visszaadja vagy beállítja a felső margót (pont) egy TextFrame-ben. |
| [setMarginTop(double value)](#setMarginTop-double-) | Visszaadja vagy beállítja a felső margót (pont) egy TextFrame-ben. |
| [getMarginBottom()](#getMarginBottom--) | Visszaadja vagy beállítja az alsó margót (pont) egy TextFrame-ben. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Visszaadja vagy beállítja az alsó margót (pont) egy TextFrame-ben. |
| [getWrapText()](#getWrapText--) | Igaz, ha a szöveg a TextFrame margóinál sortörésre kerül. |
| [setWrapText(byte value)](#setWrapText-byte-) | Igaz, ha a szöveg a TextFrame margóinál sortörésre kerül. |
| [getAutofitType()](#getAutofitType--) | Visszaadja vagy beállítja a szöveg automatikus illesztési módját. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Visszaadja vagy beállítja a szöveg automatikus illesztési módját. |
| [getRotationAngle()](#getRotationAngle--) | Megadja az egyéni forgatást, amely a szövegre alkalmazva van a keretben. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Megadja az egyéni forgatást, amely a szövegre alkalmazva van a keretben. |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


Visszaadja vagy beállítja a függőleges rögzítő szöveget egy TextFrame-ben. Olvasás/írás [TextAnchorType](../../com.aspose.slides/textanchortype).

**Visszatér:**  
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


Ha NullableBool.True, akkor a szöveget vízszintesen középre kell igazítani a keretben. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**  
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```


Ha NullableBool.True, akkor a szöveget vízszintesen középre kell igazítani a keretben. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


Meghatározza a szöveg tájolását. A vizuális szövegforgatás eredő értéke ebből a tulajdonságból és a RotationAngle tulajdonság egyéni szögéből származik. Olvasás/írás [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Visszatér:**  
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```


Meghatározza a szöveg tájolását. A vizuális szövegforgatás eredő értéke ebből a tulajdonságból és a RotationAngle tulajdonság egyéni szögéből származik. Olvasás/írás [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


Visszaadja vagy beállítja a bal margót (pont) egy TextFrame-ben. Ennek a tulajdonságnak a módosítása csak bizonyos diagramrészeken, például a DataLabel és a DataLabelFormat esetén (teljes támogatás PowerPoint 2013-ban; PowerPoint 2007-ben nincs hatása a megjelenítésre) befolyással lehet. Olvasás/írás double.

**Visszatér:**  
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```


Visszaadja vagy beállítja a bal margót (pont) egy TextFrame-ben. Ennek a tulajdonságnak a módosítása csak bizonyos diagramrészeken, például a DataLabel és a DataLabelFormat esetén (teljes támogatás PowerPoint 2013-ban; PowerPoint 2007-ben nincs hatása a megjelenítésre) befolyással lehet. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


Visszaadja vagy beállítja a jobb margót (pont) egy TextFrame-ben. Ennek a tulajdonságnak a módosítása csak bizonyos diagramrészeken, például a DataLabel és a DataLabelFormat esetén (teljes támogatás PowerPoint 2013-ban; PowerPoint 2007-ben nincs hatása a megjelenítésre) befolyással lehet. Olvasás/írás double.

**Visszatér:**  
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```


Visszaadja vagy beállítja a jobb margót (pont) egy TextFrame-ben. Ennek a tulajdonságnak a módosítása csak bizonyos diagramrészeken, például a DataLabel és a DataLabelFormat esetén (teljes támogatás PowerPoint 2013-ban; PowerPoint 2007-ben nincs hatása a megjelenítésre) befolyással lehet. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


Visszaadja vagy beállítja a felső margót (pont) egy TextFrame-ben. Ennek a tulajdonságnak a módosítása csak bizonyos diagramrészeken, például a DataLabel és a DataLabelFormat esetén (teljes támogatás PowerPoint 2013-ban; PowerPoint 2007-ben nincs hatása a megjelenítésre) befolyással lehet. Olvasás/írás double.

**Visszatér:**  
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```


Visszaadja vagy beállítja a felső margót (pont) egy TextFrame-ben. Ennek a tulajdonságnak a módosítása csak bizonyos diagramrészeken, például a DataLabel és a DataLabelFormat esetén (teljes támogatás PowerPoint 2013-ban; PowerPoint 2007-ben nincs hatása a megjelenítésre) befolyással lehet. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


Visszaadja vagy beállítja az alsó margót (pont) egy TextFrame-ben. Ennek a tulajdonságnak a módosítása csak bizonyos diagramrészeken, például a DataLabel és a DataLabelFormat esetén (teljes támogatás PowerPoint 2013-ban; PowerPoint 2007-ben nincs hatása a megjelenítésre) befolyással lehet. Olvasás/írás double.

**Visszatér:**  
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```


Visszaadja vagy beállítja az alsó margót (pont) egy TextFrame-ben. Ennek a tulajdonságnak a módosítása csak bizonyos diagramrészeken, például a DataLabel és a DataLabelFormat esetén (teljes támogatás PowerPoint 2013-ban; PowerPoint 2007-ben nincs hatása a megjelenítésre) befolyással lehet. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```


Igaz, ha a szöveg a TextFrame margóinál sortörésre kerül. Ennek a tulajdonságnak a módosítása csak bizonyos diagramrészeken, például a DataLabel és a DataLabelFormat esetén (teljes támogatás PowerPoint 2007/2013) befolyással lehet. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**  
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```


Igaz, ha a szöveg a TextFrame margóinál sortörésre kerül. Ennek a tulajdonságnak a módosítása csak bizonyos diagramrészeken, például a DataLabel és a DataLabelFormat esetén (teljes támogatás PowerPoint 2007/2013) befolyással lehet. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


Visszaadja vagy beállítja a szöveg automatikus illesztési módját. Ennek a tulajdonságnak a módosítása csak bizonyos diagramrészeken, például a DataLabel és a DataLabelFormat esetén (teljes támogatás PowerPoint 2013-ban; PowerPoint 2007-ben nincs hatása a megjelenítésre) befolyással lehet. Olvasás/írás [TextAutofitType](../../com.aspose.slides/textautofittype).

**Visszatér:**  
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```


Visszaadja vagy beállítja a szöveg automatikus illesztési módját. Ennek a tulajdonságnak a módosítása csak bizonyos diagramrészeken, például a DataLabel és a DataLabelFormat esetén (teljes támogatás PowerPoint 2013-ban; PowerPoint 2007-ben nincs hatása a megjelenítésre) befolyással lehet. Olvasás/írás [TextAutofitType](../../com.aspose.slides/textautofittype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```


Megadja az egyéni forgatást, amely a szövegre alkalmazva van a keretben. Ha nincs megadva, a kísérő alakzat forgatása lesz használva. Ha meg van adva, akkor ez függetlenül az alakzattól alkalmazandó. Azaz az alakzat rendelkezhet forgatással, mely kiegészíti a szöveg saját forgatását. A vizuális szövegforgatás eredő értéke ebből a tulajdonságból és a TextVerticalType előre definiált függőleges típusából származik. Olvasás/írás float.

--------------------

> ```
> Vegyük figyelembe azt az esetet, amikor egy alakzatra 90 fokos óramutató járásával megegyező irányú forgatás van alkalmazva. 
>  Ezen felül a szövegtörzs magára -90 fokos 
>  óramutató járásával ellentétes irányú alkalmazva. Ezután a keletkező alakzat úgy tűnik, hogy 
>  forgott, de a benne lévő szöveg úgy jelenik meg, mintha egyáltalán nem lett volna elfordítva. 
```

**Visszatér:**  
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```


Megadja az egyéni forgatást, amely a szövegre alkalmazva van a keretben. Ha nincs megadva, a kísérő alakzat forgatása lesz használva. Ha meg van adva, akkor ez függetlenül az alakzattól alkalmazandó. Azaz az alakzat rendelkezhet forgatással, mely kiegészíti a szöveg saját forgatását. A vizuális szövegforgatás eredő értéke ebből a tulajdonságból és a TextVerticalType előre definiált függőleges típusából származik. Olvasás/írás float.

--------------------

> ```
> Vegyük figyelembe azt az esetet, amikor egy alakzatra 90 fokos óramutató járásával megegyező irányú forgatás van alkalmazva. 
>  Ezen felül a szövegtörzs magára -90 fokos óramutató járásával ellentétes irányú alkalmazva. 
>  Ezután a keletkező alakzat úgy tűnik, hogy
>  forgott, de a benne lévő szöveg úgy jelenik meg, mintha egyáltalán nem lett volna elfordítva.
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |