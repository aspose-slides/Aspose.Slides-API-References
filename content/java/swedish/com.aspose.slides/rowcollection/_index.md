---
title: RowCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av tabellrader.
type: docs
url: /sv/com.aspose.slides/rowcollection/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

Representerar en samling av tabellrader.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [size()](#size--) | Hämtar antalet rader som faktiskt finns i samlingen. |
| [get_Item(int index)](#get-Item-int-) | Returnerar raden på det angivna indexet. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Skapar en kopia av den angivna mallraden och infogar den längst ner i en tabell. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Skapar en kopia av den angivna mallraden och infogar den på den angivna positionen i en tabell. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Tar bort en rad på den angivna positionen från en tabell. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar alla element från samlingen till den angivna arrayen. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar ett synkroniseringsrot. |
### size() {#size--}
```
public final int size()
```


Hämtar antalet rader som faktiskt finns i samlingen. Skrivskyddad int.

**Returnerar:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```


Returnerar raden på det angivna indexet. Skrivskyddad [Row](../../com.aspose.slides/row).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```


Skapar en kopia av den angivna mallraden och infogar den längst ner i en tabell.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Rad som används som mall. |
| withAttachedRows | boolean | Sant för att också kopiera alla rader som är bifogade till mallraden. |

**Returnerar:**
com.aspose.slides.IRow[] - Tillagda rader.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


Skapar en kopia av den angivna mallraden och infogar den på den angivna positionen i en tabell.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för en ny rad. |
| templ | [IRow](../../com.aspose.slides/irow) | Rad som används som mall. |
| withAttachedRows | boolean | Sant för att också kopiera alla rader som är bifogade till mallraden. |

**Returnerar:**
com.aspose.slides.IRow[] - Infogade rader.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```


Tar bort en rad på den angivna positionen från en tabell.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstRowIndex | int | Index för en rad att ta bort. |
| withAttachedRows | boolean | Sant för att också ta bort alla bifogade rader. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```


Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```


Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - En java.util.Iterator för hela samlingen.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopierar alla element från samlingen till den angivna arrayen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Målarray. |
| index | int | Startindex i målarrayen. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). Skrivskyddad boolean.

**Returnerar:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Returnerar ett synkroniseringsrot. Skrivskyddad Object.

**Returnerar:**
java.lang.Object