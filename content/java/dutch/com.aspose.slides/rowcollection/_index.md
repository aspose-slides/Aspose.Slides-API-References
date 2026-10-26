---
title: RowCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een tabelrijverzameling voor.
type: docs
url: /nl/com.aspose.slides/rowcollection/
---
**Erfenis:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

Stelt een tabelrijverzameling voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [size()](#size--) | Retourneert het aantal rijen dat werkelijk in de collectie zit. |
| [get_Item(int index)](#get-Item-int-) | Retourneert de rij op de opgegeven index. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Maakt een kopie van de opgegeven sjabloonrij en voegt deze onderaan een tabel in. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Maakt een kopie van de opgegeven sjabloonrij en voegt deze in op de opgegeven positie in een tabel. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Verwijdert een rij op de opgegeven positie uit een tabel. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een Java-iterator voor de volledige collectie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen uit de collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatiewortel. |
### size() {#size--}
```
public final int size()
```


Haalt het aantal rijen op dat daadwerkelijk in de collectie aanwezig is. Alleen-lezen int.

**Retourneert:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```


Retourneert de rij op de opgegeven index. Alleen-lezen [Row](../../com.aspose.slides/row).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourneert:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```


Maakt een kopie van de opgegeven sjabloonrij en voegt deze onderaan een tabel in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Rij die als sjabloon wordt gebruikt. |
| withAttachedRows | boolean | Waarbij alle aan de sjabloonrij gekoppelde rijen ook worden gekopieerd. |

**Retourneert:**
com.aspose.slides.IRow[] - Toegevoegde rijen.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


Maakt een kopie van de opgegeven sjabloonrij en voegt deze in op de opgegeven positie in een tabel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een nieuwe rij. |
| templ | [IRow](../../com.aspose.slides/irow) | Rij die als sjabloon wordt gebruikt. |
| withAttachedRows | boolean | Waarbij alle aan de sjabloonrij gekoppelde rijen ook worden gekopieerd. |

**Retourneert:**
com.aspose.slides.IRow[] - Ingevoegde rijen.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```


Verwijdert een rij op de opgegeven positie uit een tabel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| firstRowIndex | int | Index van een rij om te verwijderen. |
| withAttachedRows | boolean | Waarbij alle gekoppelde rijen ook worden verwijderd. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```


Retourneert een enumerator die door de collectie itereert.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```


Retourneert een Java-iterator voor de volledige collectie.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - Een java.util.Iterator voor de volledige collectie.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopieert alle elementen uit de collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doelarray. |
| index | int | Startindex in de doelarray. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). Alleen-lezen boolean.

**Retourneert:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Retourneert een synchronisatiewortel. Alleen-lezen Object.

**Retourneert:**
java.lang.Object