---
title: IDrawingGuidesCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Stelt een verzameling van de aanpasbare tekengidsen voor.
type: docs
url: /nl/com.aspose.slides/idrawingguidescollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

Stelt een verzameling van de aanpasbare tekengidsen voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert de tekengids op index. |
| [add(byte orientation, float position)](#add-byte-float-) | Voegt de tekengids toe aan het einde van de verzameling. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert de tekengids op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle elementen uit de verzameling. |
| [getCount()](#getCount--) | Haalt het aantal van alle elementen in de verzameling op. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```

Retourneert de tekengids op index. Alleen-lezen [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```

Voegt de tekengids toe aan het einde van de verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| orientation | byte | Oriëntatie van de tekengids. |
| position | float | Positie van de tekengids in punten. |

**Retour:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert de tekengids op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van de tekengids die verwijderd moet worden. |

### clear() {#clear--}
```
public abstract void clear()
```

Verwijdert alle elementen uit de verzameling.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Haalt het aantal van alle elementen in de verzameling op. Alleen-lezen int.

**Retour:**
int