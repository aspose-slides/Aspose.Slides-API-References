---
title: ITableFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents format of a table.
type: docs
url: /hu/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

A táblázat formátumát reprezentálja.
## Metódusok

| Módszer | Leírás |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Visszaad egy táblázat kitöltési tulajdonság objektumot. |
| [getTransparency()](#getTransparency--) | Lekéri vagy beállítja a kitöltési szín átlátszóságát. |
| [setTransparency(float value)](#setTransparency-float-) | Lekéri vagy beállítja a kitöltési szín átlátszóságát. |
| [getEffective()](#getEffective--) | Lekéri a hatékony táblázatformázási tulajdonságokat öröklődéssel és táblastílusok alkalmazásával. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Visszaad egy táblázat kitöltési tulajdonság objektumot. Csak olvasható [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatérési érték:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Lekéri vagy beállítja a kitöltési szín átlátszóságát. Olvasás/írás  float .

**Visszatérési érték:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Lekéri vagy beállítja a kitöltési szín átlátszóságát. Olvasás/írás  float .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```


Lekéri a hatékony táblázatformázási tulajdonságokat öröklődéssel és táblastílusok alkalmazásával.

**Visszatérési érték:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - A [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).