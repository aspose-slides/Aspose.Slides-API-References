---
title: IPortionFactory
second_title: Aspose.Slides Java API referencia
description: Lehetővé teszi teszt részletek létrehozását
type: docs
url: /hu/com.aspose.slides/iportionfactory/
---
```
public interface IPortionFactory
```

Lehetővé teszi teszt részletek létrehozását

--------------------

COM kompatibilitásért
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [createPortion()](#createPortion--) | Üres szövegrészt hoz létre. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Szövegrészt hoz létre a megadott karakterláncból. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Részletet hoz létre a megadott részletadatok felhasználásával. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```

Üres szövegrészt hoz létre.

**Visszatér:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```

Szövegrészt hoz létre a megadott karakterláncból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | java.lang.String | Karakterlánc. |

**Visszatér:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```

Részletet hoz létre a megadott részletadatok felhasználásával.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | Használni kívánt részlet. |

**Visszatér:**
[IPortion](../../com.aspose.slides/iportion) - Portion.