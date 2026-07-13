---
title: SensitivityLabelCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling van gevoeligheidslabels voor die op het document zijn toegepast.
type: docs
url: /nl/com.aspose.slides/sensitivitylabelcollection/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)  
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

Stelt een verzameling van gevoeligheidslabels voor die op het document zijn toegepast.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert het gevoeligheidslabel op basis van de index. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Voegt het gevoeligheidslabel toe aan het einde van de collectie. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Voegt een SensitivityLabel toe aan de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het gevoeligheidslabel op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle elementen uit de collectie. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereren. |
| [getCount()](#getCount--) | Retourneert het aantal elementen in de collectie. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | Kopieert alle elementen van de collectie naar de opgegeven array. |

### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```

Retourneert het gevoeligheidslabel op basis van de index.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Returns:**  
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)

### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

Voegt het gevoeligheidslabel toe aan het einde van de collectie.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| id | java.lang.String | De id van het gevoeligheidslabel. |
| siteId | java.util.UUID | De Azure Active Directory (Azure AD) site-identificatie. |
| isEnabled | boolean | Vlag die aangeeft of het gevoeligheidslabel is ingeschakeld. |
| methodType | int | De toewijzingsmethode voor het gevoeligheidslabel. |

**Returns:**  
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)

### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```

Voegt een SensitivityLabel toe aan de collectie.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | Het SensitivityLabel-object dat aan het einde van de collectie moet worden toegevoegd. |

**Returns:**  
int - De index waarop de SensitivityLabel is toegevoegd.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert het gevoeligheidslabel op de opgegeven index.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het gevoeligheidslabel dat moet worden verwijderd. |

### clear() {#clear--}
```
public final void clear()
```

Verwijdert alle elementen uit de collectie.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```

Retourneert een enumerator die door de collectie itereren.

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - Een  System.Collections.Generic.IEnumerator1  die kan worden gebruikt om door de collectie te itereren.

### getCount() {#getCount--}
```
public final int getCount()
```

Retourneert het aantal elementen in de collectie. Alleen-lezen  int .

**Returns:**  
int

### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```

Kopieert alle elementen van de collectie naar de opgegeven array.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | Doelaray. |
| index | int | Startindex in de doelarray. |