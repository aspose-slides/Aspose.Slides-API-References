---
title: ITableFormat
second_title: Aspose.Slides for Java API Reference
description: Represents format of a table.
type: docs
url: /hu/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

A táblázat formátumát képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Egy tábla kitöltési tulajdonság objektumot ad vissza. |
| [getTransparency()](#getTransparency--) | A kitöltő szín átlátszóságát adja vissza vagy állítja be. |
| [setTransparency(float value)](#setTransparency-float-) | A kitöltő szín átlátszóságát adja vissza vagy állítja be. |
| [getEffective()](#getEffective--) | Az öröklődéssel és alkalmazott táblastílusokkal rendelkező hatékony táblázatformázási tulajdonságokat adja vissza. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Egy tábla kitöltési tulajdonság objektumot ad vissza. Csak olvasható [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatér:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

A kitöltő szín átlátszóságát adja vissza vagy állítja be. Olvasás/írás  float .

**Visszatér:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

A kitöltő szín átlátszóságát adja vissza vagy állítja be. Olvasás/írás  float .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```

Az öröklődéssel és alkalmazott táblastílusokkal rendelkező hatékony táblázatformázási tulajdonságokat adja vissza.

**Visszatér:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - A [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).