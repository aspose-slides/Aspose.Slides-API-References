---
title: ICustomXmlPartCollection
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje kolekcję niestandardowych części XML.
type: docs
url: /pl/com.aspose.slides/icustomxmlpartcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

Reprezentuje kolekcję niestandardowych części XML.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca element pod podanym indeksem. |
| [add(byte[] xmlData)](#add-byte---) | Dodaje nową niestandardową część XML. |
| [add(String xmlString)](#add-java.lang.String-) | Dodaje nową niestandardową część XML. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Dodaje nową niestandardową część XML. |
| [removeAt(int index)](#removeAt-int-) | Usuwa niestandardową część XML pod podanym indeksem. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Usuwa pierwsze wystąpienie określonego obiektu z kolekcji. |
| [clear()](#clear--) | Usuwa wszystkie elementy z kolekcji. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```

Zwraca element pod podanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks elementu zaczynający się od zera. |

**Zwraca:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Element pod podanym indeksem.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```

Dodaje nową niestandardową część XML.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| xmlData | byte[] | Dane XML nowej części, które mają być dodane. |

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
| xmlString | java.lang.String | Ciąg XML nowej części, który ma być dodany. |

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
| inputStream | java.io.InputStream | Strumień wejściowy z danymi XML nowej części, które mają być dodane. |

**Zwraca:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Utworzona niestandardowa część XML.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Usuwa niestandardową część XML pod podanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks elementu zaczynający się od zera, który ma zostać usunięty. |
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