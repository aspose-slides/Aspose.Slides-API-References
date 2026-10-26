---
title: IColumnCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av kolumner i en tabell.
type: docs
url: /sv/com.aspose.slides/icolumncollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

Representerar en samling av kolumner i en tabell.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar kolumnen på det angivna indexet. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Skapar en kopia av den angivna mallraden och infogar den längst ner i en tabell. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Skapar en kopia av den angivna mallkolumnen och infogar den på den angivna positionen i en tabell. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Tar bort en kolumn på den angivna positionen från en tabell. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```

Returnerar kolumnen på det angivna indexet. Skrivskyddad [IColumn](../../com.aspose.slides/icolumn).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

Skapar en kopia av den angivna mallraden och infogar den längst ner i en tabell.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Kolumn som används som mall. |
| withAttachedColumns | boolean | Sant för att även kopiera alla kolumner som är fästa vid mallraden. |

**Returnerar:**
com.aspose.slides.IColumn[] - Tillagda kolumner.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

Skapar en kopia av den angivna mallkolumnen och infogar den på den angivna positionen i en tabell.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för en ny kolumn. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Kolumn som används som mall. |
| withAttachedColumns | boolean | Sant för att även kopiera alla kolumner som är fästa vid mallkolumnen. |

**Returnerar:**
com.aspose.slides.IColumn[] - Infogade kolumner.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

Tar bort en kolumn på den angivna positionen från en tabell.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| firstColumnIndex | int | Index för en kolumn att ta bort. |
| withAttachedRows | boolean | Sant för att även ta bort alla fästa kolumner. |