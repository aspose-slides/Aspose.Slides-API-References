---
title: SensitivityLabelCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje kolekci štítků citlivosti aplikovaných na dokument.
type: docs
url: /cs/com.aspose.slides/sensitivitylabelcollection/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

Reprezentuje kolekci štítků citlivosti aplikovaných na dokument.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací štítek citlivosti podle indexu. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Přidá štítek citlivosti na konec kolekce. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Přidá objekt SensitivityLabel do kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní štítek citlivosti na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechny prvky z kolekce. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [getCount()](#getCount--) | Vrací počet prvků v kolekci. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | Zkopíruje všechny prvky z kolekce do zadaného pole. |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```


Vrací štítek citlivosti podle indexu.

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


Přidá štítek citlivosti na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| id | java.lang.String | Identifikátor štítku citlivosti. |
| siteId | java.util.UUID | Identifikátor webu Azure Active Directory (Azure AD). |
| isEnabled | boolean | Příznak označuje, zda je štítek citlivosti povolen. |
| methodType | int | Metoda přiřazení pro štítek citlivosti. |

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
int - Index, na kterém byl SensitivityLabel přidán.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Odstraní štítek citlivosti na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index štítku citlivosti, který má být smazán. |

### clear() {#clear--}
```
public final void clear()
```


Odstraní všechny prvky z kolekce.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```


Vrací enumerátor, který prochází kolekcí.

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - A  System.Collections.Generic.IEnumerator1  který lze použít k iteraci přes kolekci.
### getCount() {#getCount--}
```
public final int getCount()
```


Vrací počet prvků v kolekci. Pouze pro čtení  int .

**Návratová hodnota:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```


Zkopíruje všechny prvky z kolekce do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | Cílové pole. |
| index | int | Počáteční index v cílovém poli. |