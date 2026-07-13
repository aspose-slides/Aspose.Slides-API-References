---
title: ICustomXmlPartCollection
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Reprezentuje kolekcję niestandardowych części XML.
type: docs
url: /pl/com.aspose.slides/icustomxmlpartcollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

Representuje kolekcję niestandardowych części XML.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the element at the specified index. |
| [add(byte[] xmlData)](#add-byte---) | Adds new custom xml part. |
| [add(String xmlString)](#add-java.lang.String-) | Adds new custom xml part. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Adds new custom xml part. |
| [removeAt(int index)](#removeAt-int-) | Removes custom xml part at the specified index. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Removes the first occurrence of a specific object from the collection. |
| [clear()](#clear--) | Removes all items from the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```

Zwraca element o określonym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu do pobrania. |

**Zwraca:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Element o określonym indeksie.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```

Dodaje nową niestandardową część XML.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xmlData | byte[] | Dane XML nowej części do dodania. |

**Zwraca:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Utworzona niestandardowa część XML.
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```

Dodaje nową niestandardową część XML.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xmlString | java.lang.String | Ciąg znaków XML nowej części do dodania. |

**Zwraca:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Utworzona niestandardowa część XML.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```

Dodaje nową niestandardową część XML.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| inputStream | java.io.InputStream | Strumień wejściowy z danymi XML nowej części do dodania. |

**Zwraca:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Utworzona niestandardowa część XML.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Usuwa niestandardową część XML o określonym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu do usunięcia. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```

Usuwa pierwsze wystąpienie określonego obiektu z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Niestandardowa część XML do usunięcia. |

**Zwraca:**
boolean - true jeśli element został pomyślnie usunięty; w przeciwnym razie false.
### clear() {#clear--}
```
public abstract void clear()
```

Usuwa wszystkie elementy z kolekcji.