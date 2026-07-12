---
title: ICellFormat
second_title: Aspose.Slides for Android via Java API Reference
description: A táblázatcella formátumát képviseli.
type: docs
url: /hu/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

A táblázatcella formátumát képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Returns a cell fill properties object. |
| [getBorderLeft()](#getBorderLeft--) | Returns a left border line properties object. |
| [getBorderTop()](#getBorderTop--) | Returns a top border line properties object. |
| [getBorderRight()](#getBorderRight--) | Returns a right border line properties object. |
| [getBorderBottom()](#getBorderBottom--) | Returns a bottom border line properties object. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Returns a top-left to bottom-right diagonal line properties object. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Returns a bottom-left to top-right diagonal line properties object. |
| [getTransparency()](#getTransparency--) | Gets or sets the transparency of the fill color. |
| [setTransparency(float value)](#setTransparency-float-) | Gets or sets the transparency of the fill color. |
| [getEffective()](#getEffective--) | Gets effective table cell formatting properties with inheritance and table styles applied. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Visszaad egy cella kitöltési tulajdonságok objektumot. **Csak olvasható** [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatér:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```

Visszaad egy bal szegélyvonalt tulajdonságok objektumot. **Csak olvasható** [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszatér:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```

Visszaad egy felső szegélyvonalt tulajdonságok objektumot. **Csak olvasható** [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszatér:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```

Visszaad egy jobb szegélyvonalt tulajdonságok objektumot. **Csak olvasható** [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszatér:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```

Visszaad egy alsó szegélyvonalt tulajdonságok objektumot. **Csak olvasható** [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszatér:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```

Visszaad egy bal felső-jobb alsó átlós vonal tulajdonságok objektumot. **Csak olvasható** [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszatér:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```

Visszaad egy bal alsó-jobb felső átlós vonal tulajdonságok objektumot. **Csak olvasható** [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszatér:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

A kitöltés szín átlátszóságát adja vissza vagy állítja be. **Olvasás/írás**  float .

**Visszatér:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

A kitöltés szín átlátszóságát adja vissza vagy állítja be. **Olvasás/írás**  float .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```

A táblázatcella hatékony formázási tulajdonságait adja vissza a öröklődés és a táblázatstílusok alkalmazásával.

**Visszatér:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - Egy [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).