---
title: ColumnCollection
second_title: Aspose.Slides voor Java API-referentie
description: Representeert een verzameling kolommen in een tabel.
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
| [size()](#size--) | Retourneert het aantal kolommen in een verzameling. |
| [get_Item(int index)](#get-Item-int-) | Retourneert de kolom op de opgegeven index. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Maakt een kopie van de opgegeven sjabloonrij en voegt deze onderaan een tabel in. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Maakt een kopie van de opgegeven sjabloonkolom en voegt deze op de opgegeven positie in een tabel in. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Verwijdert een kolom op de opgegeven positie uit een tabel. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de verzameling itereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige verzameling. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen van de verzameling naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de verzameling gesynchroniseerd is (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatie-wortel. |
### size() {#size--}
```
public final int size()
```


Retourneert het aantal kolommen in een verzameling. Alleen-lezen int.

**Retour:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```


Retourneert de kolom op de opgegeven index. Alleen-lezen [Column](../../com.aspose.slides/column).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```


Maakt een kopie van de opgegeven sjabloonrij en voegt deze onderaan een tabel in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Kolom die wordt gebruikt als sjabloon. |
| withAttachedColumns | boolean | Waar om ook alle kolommen die aan de sjabloonrij zijn gekoppeld te kopiëren. |

**Retour:**
com.aspose.slides.IColumn[] - Toegevoegde kolommen.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```


Maakt een kopie van de opgegeven sjabloonkolom en voegt deze op de opgegeven positie in een tabel in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een nieuwe kolom. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Kolom die wordt gebruikt als sjabloon. |
| withAttachedColumns | boolean | Waar om ook alle kolommen die aan de sjabloonkolom zijn gekoppeld te kopiëren. |

**Retour:**
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
| withAttachedRows | boolean | Waar om ook alle gekoppelde kolommen te verwijderen. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```


Retourneert een enumerator die door de verzameling itereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - Een IGenericEnumerator die kan worden gebruikt om door de verzameling te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```


Retourneert een java-iterator voor de volledige verzameling.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - Een java.util.Iterator voor de volledige verzameling.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopieert alle elementen van de verzameling naar de opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doel-array. |
| index | int | Startindex in de doel-array. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Retourneert een waarde die aangeeft of de toegang tot de verzameling gesynchroniseerd is (thread-safe). Alleen-lezen boolean.

**Retour:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Retourneert een synchronisatie-wortel. Alleen-lezen Object.

**Retour:**
java.lang.Object