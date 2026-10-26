---
title: IRowCollection
second_title: Aspose.Slides voor Android via Java API Referentie
description: Stelt een verzameling tabelrijen voor.
type: docs
url: /nl/com.aspose.slides/irowcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

Stelt een verzameling tabelrijen voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Maakt een kopie van de opgegeven sjabloonrij en voegt deze toe aan de onderkant van een tabel. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Maakt een kopie van de opgegeven sjabloonrij en voegt deze in op de opgegeven positie in een tabel. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Verwijdert een rij op de opgegeven positie uit een tabel. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```

Haalt het element op op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```

Maakt een kopie van de opgegeven sjabloonrij en voegt deze toe aan de onderkant van een tabel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Rij die wordt gebruikt als sjabloon. |
| withAttachedRows | boolean | Waarbij ook alle aan de sjabloonrij gekoppelde rijen worden gekopieerd. |

**Retour:**
com.aspose.slides.IRow[] - Toegevoegde rijen.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

Maakt een kopie van de opgegeven sjabloonrij en voegt deze in op de opgegeven positie in een tabel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een nieuwe rij. |
| templ | [IRow](../../com.aspose.slides/irow) | Rij die wordt gebruikt als sjabloon. |
| withAttachedRows | boolean | Waarbij ook alle aan de sjabloonrij gekoppelde rijen worden gekopieerd. |

**Retour:**
com.aspose.slides.IRow[] - Ingevoegde rijen.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```

Verwijdert een rij op de opgegeven positie uit een tabel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| firstRowIndex | int | Index van een rij die moet worden verwijderd. |
| withAttachedRows | boolean | Waarbij ook alle gekoppelde rijen worden verwijderd. |