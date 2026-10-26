---
title: ICustomXmlPartCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie van aangepaste xml-onderdelen voor.
type: docs
url: /nl/com.aspose.slides/icustomxmlpartcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

Stelt een collectie van aangepaste xml-onderdelen voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert het element op de opgegeven index. |
| [add(byte[] xmlData)](#add-byte---) | Voegt een nieuw aangepast xml-onderdeel toe. |
| [add(String xmlString)](#add-java.lang.String-) | Voegt een nieuw aangepast xml-onderdeel toe. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Voegt een nieuw aangepast xml-onderdeel toe. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert aangepast xml-onderdeel op de opgegeven index. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Verwijdert het eerste voorkomen van een specifiek object uit de collectie. |
| [clear()](#clear--) | Verwijdert alle items uit de collectie. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```


Retourneert het element op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het op te halen element. |

**Returns:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Het element op de opgegeven index.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```


Voegt een nieuw aangepast xml-onderdeel toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xmlData | byte[] | De xml-gegevens van het nieuwe onderdeel dat moet worden toegevoegd. |

**Returns:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Aangemaakt aangepast xml-onderdeel.
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```


Voegt een nieuw aangepast xml-onderdeel toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xmlString | java.lang.String | De xml-string van het nieuwe onderdeel dat moet worden toegevoegd. |

**Returns:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Aangemaakt aangepast xml-onderdeel.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```


Voegt een nieuw aangepast xml-onderdeel toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputStream | java.io.InputStream | De inputStream met xml-gegevens van het nieuwe onderdeel dat moet worden toegevoegd. |

**Returns:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Aangemaakt aangepast xml-onderdeel.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Verwijdert aangepast xml-onderdeel op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het te verwijderen element. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```


Verwijdert het eerste voorkomen van een specifiek object uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Het aangepaste xml-onderdeel dat moet worden verwijderd. |

**Returns:**
boolean - true als item succesvol is verwijderd; anders false.
### clear() {#clear--}
```
public abstract void clear()
```


Verwijdert alle items uit de collectie.