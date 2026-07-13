---
title: IColumnCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling kolommen in een tabel voor.
type: docs
url: /nl/com.aspose.slides/icolumncollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

Stelt een verzameling kolommen in een tabel voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert de kolom op de opgegeven index. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Maakt een kopie van de opgegeven sjabloonrij en voegt deze onderaan een tabel in. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Maakt een kopie van de opgegeven sjabloonkolom en voegt deze in op de opgegeven positie in een tabel. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Verwijdert een kolom op de opgegeven positie uit een tabel. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```

Retourneert de kolom op de opgegeven index. Alleen-lezen [IColumn](../../com.aspose.slides/icolumn).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

Maakt een kopie van de opgegeven sjabloonrij en voegt deze onderaan een tabel in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Kolom die als sjabloon wordt gebruikt. |
| withAttachedColumns | boolean | Waar om ook alle kolommen die aan de sjabloonrij zijn gekoppeld te kopiëren. |

**Retour:**
com.aspose.slides.IColumn[] - Toegevoegde kolommen.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

Maakt een kopie van de opgegeven sjabloonkolom en voegt deze in op de opgegeven positie in een tabel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een nieuwe kolom. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Kolom die als sjabloon wordt gebruikt. |
| withAttachedColumns | boolean | Waar om ook alle kolommen die aan de sjabloonkolom zijn gekoppeld te kopiëren. |

**Retour:**
com.aspose.slides.IColumn[] - Ingevoegde kolommen.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

Verwijdert een kolom op de opgegeven positie uit een tabel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| firstColumnIndex | int | Index van een te verwijderen kolom. |
| withAttachedRows | boolean | Waar om ook alle gekoppelde kolommen te verwijderen. |