---
title: IPortionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Lehetővé teszi teszt részek létrehozását
type: docs
url: /hu/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

Lehetővé teszi teszt részek létrehozását

--------------------

COM kompatibilitáshoz
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [createPortion()](#createPortion--) | Üres szövegrészt hoz létre. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Szövegrészt hoz létre a megadott karakterláncból. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Létrehoz egy részt a megadott részadat használatával. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```

Üres szövegrészt hoz létre.

**Visszatérési érték:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```

Szövegrészt hoz létre a megadott karakterláncból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | java.lang.String | String. |

**Visszatérési érték:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```

Létrehoz egy részt a megadott részadat használatával.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Használandó rész. |

**Visszatérési érték:**
[IPortion](../../com.aspose.slides/iportion) - Portion.