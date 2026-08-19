---
title: CustomXmlPartCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een collectie van aangepaste xml-onderdelen voor.
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
| [get_Item(int index)](#get-Item-int-) | Geeft het element op de opgegeven index terug. |
| [size()](#size--) | Geeft het aantal aangepaste xml-onderdelen in de collectie terug. |
| [add(String xmlString)](#add-java.lang.String-) | Voegt een nieuw aangepast xml-onderdeel toe. |
| [add(byte[] xmlData)](#add-byte---) | Voegt een nieuw aangepast xml-onderdeel toe. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Voegt een nieuw aangepast xml-onderdeel toe. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het aangepaste xml-onderdeel op de opgegeven index. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Verwijdert het eerste voorkomen van een specifiek object uit de collectie. |
| [clear()](#clear--) | Verwijdert alle items uit de collectie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert naar een opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Geeft een waarde terug die aangeeft of de toegang tot de collectie gesynchroniseerd (thread-safe) is. |
| [getSyncRoot()](#getSyncRoot--) | Geeft een synchronatieroot terug. |
| [iterator()](#iterator--) | Geeft een enumerator terug die door de collectie iterereert. |
| [iteratorJava()](#iteratorJava--) | Geeft een java iterator voor de gehele collectie terug. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

Geeft het element op de opgegeven index terug.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het element dat moet worden opgehaald. |

**Retour:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Het element op de opgegeven index.
### size() {#size--}
```
public final int size()
```

Geeft het aantal aangepaste xml-onderdelen in de collectie terug. Read-only int.

**Retour:**
int
### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

Voegt een nieuw aangepast xml-onderdeel toe.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| xmlString | java.lang.String | De xml-string van het nieuwe onderdeel dat moet worden toegevoegd. |

**Retour:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Aangemaakt aangepast xml-onderdeel.
### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

Voegt een nieuw aangepast xml-onderdeel toe.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| xmlData | byte[] | De xml-gegevens van het nieuwe onderdeel dat moet worden toegevoegd. |

**Retour:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Aangemaakt aangepast xml-onderdeel.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

Voegt een nieuw aangepast xml-onderdeel toe.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| inputStream | java.io.InputStream | De inputStream met xml-gegevens van het nieuwe onderdeel dat moet worden toegevoegd. |

**Retour:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Aangemaakt aangepast xml-onderdeel.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert het aangepaste xml-onderdeel op de opgegeven index.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het element dat moet worden verwijderd. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

Verwijdert het eerste voorkomen van een specifiek object uit de collectie.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Het aangepaste xml-onderdeel dat moet worden verwijderd. |

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

Kopieert naar een opgegeven array.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array om naar te kopiëren. |
| index | int | Index om het kopiëren te beginnen. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Geeft een waarde terug die aangeeft of de toegang tot de collectie gesynchroniseerd (thread-safe) is. Read-only boolean.

**Retour:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Geeft een synchronatieroot terug. Read-only Object.

**Retour:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

Geeft een enumerator terug die door de collectie iterereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

Geeft een java iterator voor de gehele collectie terug.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Een java.util.Iterator voor de gehele collectie.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Geeft het Parent_Immediate-object terug. Read-only IDOMObject.

**Retour:**
com.aspose.slides.IDOMObject