---
title: ColumnCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling kolumner i en tabell.
type: docs
url: /sv/com.aspose.slides/columncollection/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

Representerar en samling kolumner i en tabell.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [size()](#size--) | Returnerar antalet kolumner i en samling. |
| [get_Item(int index)](#get-Item-int-) | Returnerar kolumnen på det angivna indexet. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Skapar en kopia av den angivna mallraden och infogar den längst ner i en tabell. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Skapar en kopia av den angivna mallkolumnen och infogar den på den angivna positionen i en tabell. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Tar bort en kolumn på den angivna positionen från en tabell. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar alla element från samlingen till den angivna arrayen. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar ett synkroniseringsrot. |
### size() {#size--}
```
public final int size()
```

Returnerar antalet kolumner i en samling. Skrivskyddad int.

**Returnerar:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```

Returnerar kolumnen på det angivna indexet. Skrivskyddad [Column](../../com.aspose.slides/column).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

Skapar en kopia av den angivna mallraden och infogar den längst ner i en tabell.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Kolumn som används som mall. |
| withAttachedColumns | boolean | Sant för att även kopiera alla kolumner som är kopplade till mallraden. |

**Returnerar:**
com.aspose.slides.IColumn[] - Tillagda kolumner.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

Skapar en kopia av den angivna mallkolumnen och infogar den på den angivna positionen i en tabell.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för en ny kolumn. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Kolumn som används som mall. |
| withAttachedColumns | boolean | Sant för att även kopiera alla kolumner som är kopplade till mallkolumnen. |

**Returnerar:**
com.aspose.slides.IColumn[] - Infogade kolumner.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

Tar bort en kolumn på den angivna positionen från en tabell.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstColumnIndex | int | Index för en kolumn att ta bort. |
| withAttachedRows | boolean | Sant för att även ta bort alla kopplade kolumner. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - En java.util.Iterator för hela samlingen.
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