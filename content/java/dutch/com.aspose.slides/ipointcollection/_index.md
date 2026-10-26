---
title: IPointCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een collectie van delen voor.
type: docs
url: /nl/com.aspose.slides/ipointcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPointCollection extends System.Collections.Generic.IGenericEnumerable<IPoint>
```

Stelt een collectie van delen voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCount()](#getCount--) | Returns the number of points in the collection. |
| [get_Item(int index)](#get-Item-int-) | Returns a point at the specified index. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Geeft het aantal punten in de collectie terug. Alleen-lezen int.

**Retour:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IPoint get_Item(int index)
```

Geeft een punt op de opgegeven index terug.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van element. |

**Retour:**
[IPoint](../../com.aspose.slides/ipoint) - Het [IPoint](../../com.aspose.slides/ipoint) object.