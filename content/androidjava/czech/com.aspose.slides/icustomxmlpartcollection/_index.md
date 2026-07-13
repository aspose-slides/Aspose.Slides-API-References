---
title: ICustomXmlPartCollection
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Představuje kolekci vlastních xml částí.
type: docs
url: /cs/com.aspose.slides/icustomxmlpartcollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

Představuje kolekci vlastních xml částí.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací prvek na zadaném indexu. |
| [add(byte[] xmlData)](#add-byte---) | Přidá novou vlastní xml část. |
| [add(String xmlString)](#add-java.lang.String-) | Přidá novou vlastní xml část. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Přidá novou vlastní xml část. |
| [removeAt(int index)](#removeAt-int-) | Odstraní vlastní xml část na zadaném indexu. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Odstraní první výskyt konkrétního objektu z kolekce. |
| [clear()](#clear--) | Odstraní všechny položky z kolekce. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```

Vrací prvek na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index prvku, který se má získat. |

**Návratová hodnota:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Prvek na zadaném indexu.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```

Přidá novou vlastní xml část.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xmlData | byte[] | XML data nového části, která má být přidána. |

**Návratová hodnota:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Vytvořená vlastní xml část.
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```

Přidá novou vlastní xml část.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| xmlString | java.lang.String | XML řetězec nové části, který má být přidán. |

**Návratová hodnota:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Vytvořená vlastní xml část.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```

Přidá novou vlastní xml část.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| inputStream | java.io.InputStream | InputStream s XML daty nové části, který má být přidán. |

**Návratová hodnota:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Vytvořená vlastní xml část.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Odstraní vlastní xml část na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index prvku, který se má odstranit. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```

Odstraní první výskyt konkrétního objektu z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | Vlastní xml část, která se má odstranit. |

**Návratová hodnota:**
boolean - true, pokud byl prvek úspěšně odstraněn; jinak false.
### clear() {#clear--}
```
public abstract void clear()
```

Odstraní všechny položky z kolekce.