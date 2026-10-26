---
title: ISensitivityLabelCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling gevoeligheidslabels voor die op het document zijn toegepast.
type: docs
url: /nl/com.aspose.slides/isensitivitylabelcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

Stelt een verzameling gevoeligheidslabels voor die op het document zijn toegepast.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert het gevoeligheidslabel op basis van de index. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Voegt het gevoeligheidslabel toe aan het einde van de collectie. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Voegt een SensitivityLabel toe aan de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het gevoeligheidslabel op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle elementen uit de collectie. |
| [getCount()](#getCount--) | Haalt het aantal elementen in de collectie op. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```


Retourneert het gevoeligheidslabel op basis van de index. Alleen-lezen [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```


Voegt het gevoeligheidslabel toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| id | java.lang.String | De id van het gevoeligheidslabel. |
| siteId | java.util.UUID | De Azure Active Directory (Azure AD) site-identificatie. |
| isEnabled | boolean | Vlag geeft aan of het gevoeligheidslabel is ingeschakeld. |
| methodType | int | De toewijzingsmethode voor het gevoeligheidslabel. |

**Retour:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```


Voegt een SensitivityLabel toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | Het SensitivityLabel-object dat aan het einde van de collectie moet worden toegevoegd. |

**Retour:**
int - De index waarop het SensitivityLabel werd toegevoegd.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Verwijdert het gevoeligheidslabel op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het gevoeligheidslabel dat moet worden verwijderd. |

### clear() {#clear--}
```
public abstract void clear()
```


Verwijdert alle elementen uit de collectie.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Haalt het aantal elementen in de collectie op. Alleen-lezen int .

**Retour:**
int