---
title: IRowCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een collectie van tabelrijen voor.
type: docs
url: /nl/com.aspose.slides/irowcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

Stelt een collectie van tabelrijen voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Maakt een kopie van de opgegeven sjabloonrij en voegt deze onderaan een tabel in. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Maakt een kopie van de opgegeven sjabloonrij en voegt deze in op de opgegeven positie in een tabel. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Verwijdert een rij op de opgegeven positie uit een tabel. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```

Haalt het element op op de opgegeven index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retourwaarde:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```

Maakt een kopie van de opgegeven sjabloonrij en voegt deze onderaan een tabel in.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Rij die als sjabloon wordt gebruikt. |
| withAttachedRows | boolean | True om ook alle rijen die aan de sjabloonrij gekoppeld zijn te kopiëren. |

**Retourwaarde:**
com.aspose.slides.IRow[] - Added rows.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

Maakt een kopie van de opgegeven sjabloonrij en voegt deze in op de opgegeven positie in een tabel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index van een nieuwe rij. |
| templ | [IRow](../../com.aspose.slides/irow) | Rij die als sjabloon wordt gebruikt. |
| withAttachedRows | boolean | True om ook alle rijen die aan de sjabloonrij gekoppeld zijn te kopiëren. |

**Retourwaarde:**
com.aspose.slides.IRow[] - Inserted rows.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```

Verwijdert een rij op de opgegeven positie uit een tabel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstRowIndex | int | Index van een te verwijderen rij. |
| withAttachedRows | boolean | True om ook alle gekoppelde rijen te verwijderen. |