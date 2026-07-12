---
title: PortionFactory
second_title: Aspose.Slides for Android Java API hivatkozásán keresztül
description: Lehetővé teszi a tesztdarabok létrehozását
type: docs
url: /hu/com.aspose.slides/portionfactory/
---
**Öröklődés:**
java.lang.Object

**Az összes megvalósított interfész:**
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

Lehetővé teszi tesztdarabok létrehozását

--------------------

COM kompatibilitáshoz
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [createPortion()](#createPortion--) | Létrehoz egy üres szövegrészt. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Létrehoz egy szövegrészt a megadott karakterláncból. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Létrehoz egy részt a megadott részadatok felhasználásával. |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```


### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```


Létrehoz egy üres szövegrészt.

**Visszatérési érték:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```


Létrehoz egy szövegrészt a megadott karakterláncból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | java.lang.String | Karakterlánc. |

**Visszatérési érték:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```


Létrehoz egy részt a megadott részadatok felhasználásával.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | A felhasználandó rész. |

**Visszatérési érték:**
[IPortion](../../com.aspose.slides/iportion) - Portion.