---
title: CustomXmlPartCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling van aangepaste xml-onderdelen voor.
type: docs
url: /nl/com.aspose.slides/customxmlpartcollection/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

Stelt een collectie van aangepaste xml-onderdelen voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert het element op de opgegeven index. |
| [size()](#size--) | Retourneert het aantal aangepaste xml-onderdelen in de collectie. |
| [add(String xmlString)](#add-java.lang.String-) | Voegt een nieuw aangepast xml-onderdeel toe. |
| [add(byte[] xmlData)](#add-byte---) | Voegt een nieuw aangepast xml-onderdeel toe. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Voegt een nieuw aangepast xml-onderdeel toe. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert aangepast xml-onderdeel op de opgegeven index. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Verwijdert de eerste voorkoming van een specifiek object uit de collectie. |
| [clear()](#clear--) | Verwijdert alle items uit de collectie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieer naar gespecificeerde array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-veilig). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatiewortel. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige collectie. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

Retourneert het element op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het op te halen element. |

**Retour:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Het element op de opgegeven index.
### size() {#size--}
```
public final int size()
```

Retourneert het aantal aangepaste xml-onderdelen in de collectie. Alleen-lezen int.

**Retour:**
int
### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

Voegt een nieuw aangepast xml-onderdeel toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xmlString | java.lang.String | De xml-string van het nieuw toe te voegen onderdeel. |

**Retour:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Aangemaakt aangepast xml-onderdeel.
### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

Voegt een nieuw aangepast xml-onderdeel toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xmlData | byte[] | De xml-data van het nieuw toe te voegen onderdeel. |

**Retour:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Aangemaakt aangepast xml-onderdeel.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

Voegt een nieuw aangepast xml-onderdeel toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputStream | java.io.InputStream | De inputStream met xml-data van het nieuw toe te voegen onderdeel. |

**Retour:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Aangemaakt aangepast xml-onderdeel.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert aangepast xml-onderdeel op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het te verwijderen element. |
### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

Verwijdert de eerste voorkoming van een specifiek object uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Het aangepaste xml-onderdeel om te verwijderen. |

**Retour:**
boolean - true als het item succesvol is verwijderd; anders false.
### clear() {#clear--}
```
public final void clear()
```

Verwijdert alle items uit de collectie.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopieer naar gespecificeerde array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array waarnaar gekopieerd moet worden. |
| index | int | Index waarop begonnen wordt met kopiëren. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-veilig). Alleen-lezen boolean.

**Retour:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retourneert een synchronisatiewortel. Alleen-lezen Object.

**Retour:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

Retourneert een enumerator die door de collectie iterereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

Retourneert een java-iterator voor de volledige collectie.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Een java.util.Iterator voor de volledige collectie.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert Parent_Immediate object. Alleen-lezen IDOMObject.

**Retour:**
com.aspose.slides.IDOMObject