---
title: ColumnCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling kolommen in een tabel voor.
type: docs
url: /nl/com.aspose.slides/columncollection/
---
**Erfenis:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

Stelt een verzameling kolommen in een tabel voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [size()](#size--) | Geeft het aantal kolommen in de collectie terug. |
| [get_Item(int index)](#get-Item-int-) | Geeft de kolom op de opgegeven index terug. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Maakt een kopie van de opgegeven sjabloonrij en voegt deze onderaan een tabel in. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Maakt een kopie van de opgegeven sjabloonkollom en voegt deze op de opgegeven positie in een tabel in. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Verwijdert een kolom op de opgegeven positie uit een tabel. |
| [iterator()](#iterator--) | Geeft een enumerator terug die door de collectie iterereert. |
| [iteratorJava()](#iteratorJava--) | Geeft een java-iterator terug voor de volledige collectie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen van de collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Geeft een waarde terug die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Geeft een synchronisatiewortel terug. |
### size() {#size--}
```
public final int size()
```


Geeft het aantal kolommen in de collectie terug. Alleen-lezen int.

**Geeft terug:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```


Geeft de kolom op de opgegeven index terug. Alleen-lezen [Column](../../com.aspose.slides/column).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Geeft terug:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```


Maakt een kopie van de opgegeven sjabloonrij en voegt deze onderaan een tabel in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Kolom die als sjabloon wordt gebruikt. |
| withAttachedColumns | boolean | Waarbij alle aan de sjabloonrij gekoppelde kolommen ook worden gekopieerd. |

**Geeft terug:**
com.aspose.slides.IColumn[] - Toegevoegde kolommen.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```


Maakt een kopie van de opgegeven sjabloonkollom en voegt deze op de opgegeven positie in een tabel in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een nieuwe kolom. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Kolom die als sjabloon wordt gebruikt. |
| withAttachedColumns | boolean | Waarbij alle aan de sjabloonkollom gekoppelde kolommen ook worden gekopieerd. |

**Geeft terug:**
com.aspose.slides.IColumn[] - Ingevoegde kolommen.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```


Verwijdert een kolom op de opgegeven positie uit een tabel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| firstColumnIndex | int | Index van een te verwijderen kolom. |
| withAttachedRows | boolean | Waarbij alle gekoppelde kolommen ook worden verwijderd. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```


Geeft een enumerator terug die door de collectie iterereert.

**Geeft terug:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```


Geeft een java-iterator terug voor de volledige collectie.

**Geeft terug:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - Een java.util.Iterator voor de volledige collectie.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopieert alle elementen van de collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doel-array. |
| index | int | Beginindex in de doel-array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Geeft een waarde terug die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). Alleen-lezen boolean.

**Geeft terug:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Geeft een synchronisatiewortel terug. Alleen-lezen Object.

**Geeft terug:**
java.lang.Object