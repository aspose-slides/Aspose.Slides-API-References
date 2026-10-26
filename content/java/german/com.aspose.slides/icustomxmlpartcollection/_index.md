---
title: ICustomXmlPartCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Sammlung von benutzerdefinierten XML-Teilen dar.
type: docs
url: /de/com.aspose.slides/icustomxmlpartcollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

Stellt eine Sammlung von benutzerdefinierten XML-Teilen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt das Element am angegebenen Index zurück. |
| [add(byte[] xmlData)](#add-byte---) | Fügt einen neuen benutzerdefinierten XML-Teil hinzu. |
| [add(String xmlString)](#add-java.lang.String-) | Fügt einen neuen benutzerdefinierten XML-Teil hinzu. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Fügt einen neuen benutzerdefinierten XML-Teil hinzu. |
| [removeAt(int index)](#removeAt-int-) | Entfernt den benutzerdefinierten XML-Teil am angegebenen Index. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```


Gibt das Element am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu holenden Elements. |

**Rückgabewert:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Das Element am angegebenen Index.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```


Fügt einen neuen benutzerdefinierten XML-Teil hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmlData | byte[] | Die XML-Daten des neuen hinzuzufügenden Teils. |

**Rückgabewert:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Erstellter benutzerdefinierter XML-Teil.
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```


Fügt einen neuen benutzerdefinierten XML-Teil hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xmlString | java.lang.String | Der XML-String des neuen hinzuzufügenden Teils. |

**Rückgabewert:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Erstellter benutzerdefinierter XML-Teil.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```


Fügt einen neuen benutzerdefinierten XML-Teil hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | java.io.InputStream | Der InputStream mit den XML-Daten des neuen hinzuzufügenden Teils. |

**Rückgabewert:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Erstellter benutzerdefinierter XML-Teil.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Entfernt den benutzerdefinierten XML-Teil am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements. |
### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```


Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Der zu entfernende benutzerdefinierte XML-Teil. |

**Rückgabewert:**
boolean - true wenn das Element erfolgreich entfernt wurde; andernfalls false.
### clear() {#clear--}
```
public abstract void clear()
```


Entfernt alle Elemente aus der Sammlung.