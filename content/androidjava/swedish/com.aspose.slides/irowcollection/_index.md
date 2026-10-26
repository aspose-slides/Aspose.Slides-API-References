---
title: IRowCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av tabellrader.
type: docs
url: /sv/com.aspose.slides/irowcollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

Representerar en samling av tabellrader.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Skapar en kopia av den angivna mallraden och infogar den längst ner i en tabell. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Skapar en kopia av den angivna mallraden och infogar den på den angivna positionen i en tabell. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Tar bort en rad på den angivna positionen från en tabell. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```


Hämtar elementet på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```


Skapar en kopia av den angivna mallraden och infogar den längst ner i en tabell.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Rad som används som mall. |
| withAttachedRows | boolean | Sant för att även kopiera alla rader som är fästa vid mallraden. |

**Returnerar:**
com.aspose.slides.IRow[] - Tillagda rader.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


Skapar en kopia av den angivna mallraden och infogar den på den angivna positionen i en tabell.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för en ny rad. |
| templ | [IRow](../../com.aspose.slides/irow) | Rad som används som mall. |
| withAttachedRows | boolean | Sant för att även kopiera alla rader som är fästa vid mallraden. |

**Returnerar:**
com.aspose.slides.IRow[] - Infogade rader.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```


Tar bort en rad på den angivna positionen från en tabell.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstRowIndex | int | Index för en rad att ta bort. |
| withAttachedRows | boolean | Sant för att även ta bort alla fästa rader. |