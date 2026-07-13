---
title: RowCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie van tabelrijen voor.
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

Stelt een collectie van tabelrijen voor.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [size()](#size--) | Haalt het aantal rijen op dat daadwerkelijk in de collectie aanwezig is. |
| [get_Item(int index)](#get-Item-int-) | Retourneert de rij op de opgegeven index. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Maakt een kopie van de opgegeven sjabloonrij en voegt deze toe aan de onderkant van een tabel. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Maakt een kopie van de opgegeven sjabloonrij en voegt deze in op de opgegeven positie in een tabel. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Verwijdert een rij op de opgegeven positie uit een tabel. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de gehele collectie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen uit de collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatiewortel. |

### size() {#size--}
```
public final int size()
```

Haalt het aantal rijen op dat daadwerkelijk in de collectie aanwezig is. Alleen-lezen int.

**Retour:**
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

**Retour:**
[IRow](../../com.aspose.slides/irow)

### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```

Maakt een kopie van de opgegeven sjabloonrij en voegt deze toe aan de onderkant van een tabel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Rij die als sjabloon wordt gebruikt. |
| withAttachedRows | boolean | True om ook alle aan de sjabloonrij gekoppelde rijen te kopiëren. |

**Retour:**
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
| withAttachedRows | boolean | True om ook alle aan de sjabloonrij gekoppelde rijen te kopiëren. |

**Retour:**
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
| withAttachedRows | boolean | True om ook alle gekoppelde rijen te verwijderen. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```

Retourneert een enumerator die door de collectie iterereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```

Retourneert een java-iterator voor de gehele collectie.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - Een java.util.Iterator voor de gehele collectie.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopieert alle elementen uit de collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doelarray. |
| index | int | Begindex in de doelarray. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). Alleen-lezen boolean.

**Retour:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retourneert een synchronisatiewortel. Alleen-lezen Object.

**Retour:**
java.lang.Object