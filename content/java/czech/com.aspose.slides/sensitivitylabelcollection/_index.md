---
title: SensitivityLabelCollection
second_title: Aspose.Slides pro Java API Reference
description: Představuje kolekci citlivostních štítků aplikovaných na dokument.
type: docs
url: /cs/com.aspose.slides/sensitivitylabelcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

Represents a collection of sensitivity labels applied to the document.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací citlivostní štítek podle indexu. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Přidá citlivostní štítek na konec kolekce. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Přidá objekt SensitivityLabel do kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odebere citlivostní štítek na zadaném indexu. |
| [clear()](#clear--) | Odebere všechny položky z kolekce. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [getCount()](#getCount--) | Vrací počet položek v kolekci. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | Zkopíruje všechny položky z kolekce do zadaného pole. |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```


Vrací citlivostní štítek podle indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```


Přidá citlivostní štítek na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| id | java.lang.String | Identifikátor citlivostního štítku. |
| siteId | java.util.UUID | Identifikátor Azure Active Directory (Azure AD) lokality. |
| isEnabled | boolean | Příznak označující, zda je citlivostní štítek povolen. |
| methodType | int | Metoda přiřazení pro citlivostní štítek. |

**Návratová hodnota:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```


Přidá objekt SensitivityLabel do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | Objekt SensitivityLabel, který má být přidán na konec kolekce. |

**Návratová hodnota:**
int - Index, do kterého byl SensitivityLabel přidán.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Odebere citlivostní štítek na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index citlivostního štítku, který má být smazán. |

### clear() {#clear--}
```
public final void clear()
```


Odebere všechny položky z kolekce.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```


Vrací enumerátor, který prochází kolekcí.

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - Objekt System.Collections.Generic.IEnumerator1, který lze použít k iteraci přes kolekci.
### getCount() {#getCount--}
```
public final int getCount()
```


Vrací počet položek v kolekci. Pouze ke čtení  int .

**Návratová hodnota:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```


Zkopíruje všechny položky z kolekce do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | Cílové pole. |
| index | int | Počáteční index v cílovém poli. |