---
title: ICellFormat
second_title: Aspose.Slides for Java API Reference
description: A táblázat cellájának formátumát képviseli.
type: docs
url: /hu/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

A táblázat cellájának formátumát képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Visszaad egy cella kitöltési tulajdonság objektumot. |
| [getBorderLeft()](#getBorderLeft--) | Visszaad egy bal szegély vonal tulajdonság objektumot. |
| [getBorderTop()](#getBorderTop--) | Visszaad egy felső szegély vonal tulajdonság objektumot. |
| [getBorderRight()](#getBorderRight--) | Visszaad egy jobb szegély vonal tulajdonság objektumot. |
| [getBorderBottom()](#getBorderBottom--) | Visszaad egy alsó szegély vonal tulajdonság objektumot. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Visszaad egy bal felső sarokból jobb alsó sarokba haladó átló tulajdonság objektumot. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Visszaad egy bal alsó sarokból jobb felső sarokba haladó átló tulajdonság objektumot. |
| [getTransparency()](#getTransparency--) | Lekéri vagy beállítja a kitöltőszín átlátszóságát. |
| [setTransparency(float value)](#setTransparency-float-) | Lekéri vagy beállítja a kitöltőszín átlátszóságát. |
| [getEffective()](#getEffective--) | Lekéri a hatékony táblacella formázási tulajdonságokat öröklődéssel és alkalmazott táblastílusokkal. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Visszaad egy cella kitöltési tulajdonság objektumot. Csak olvasható [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatér:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```


Visszaad egy bal szegély vonal tulajdonság objektumot. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszatér:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```


Visszaad egy felső szegély vonal tulajdonság objektumot. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszatér:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```


Visszaad egy jobb szegély vonal tulajdonság objektumot. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszatér:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```


Visszaad egy alsó szegély vonal tulajdonság objektumot. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszatér:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```


Visszaad egy bal felső sarokból jobb alsó sarokba haladó átló tulajdonság objektumot. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszatér:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```


Visszaad egy bal alsó sarokból jobb felső sarokba haladó átló tulajdonság objektumot. Csak olvasható [ILineFormat](../../com.aspose.slides/ilineformat).

**Visszatér:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Lekéri vagy beállítja a kitöltőszín átlátszóságát. Olvasás/írás  float .

**Visszatér:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Lekéri vagy beállítja a kitöltőszín átlátszóságát. Olvasás/írás  float .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```


Lekéri a hatékony táblacella formázási tulajdonságokat öröklődéssel és alkalmazott táblastílusokkal.

**Visszatér:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).