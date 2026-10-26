---
title: ISensitivityLabelCollection
second_title: Aspose.Slides pro Java – referenční příručka API
description: Představuje kolekci štítků citlivosti aplikovaných na dokument.
type: docs
url: /cs/com.aspose.slides/isensitivitylabelcollection/
---
**Všechny implementované rozhraní:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

Representuje kolekci štítků citlivosti aplikovaných na dokument.

## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the sensitivity label by index. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Adds the sensitivity label at the end of the collection. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Adds a SensitivityLabel to the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the sensitivity label at the specified index. |
| [clear()](#clear--) | Removes all elements from the collection. |
| [getCount()](#getCount--) | Gets the number of all elements in the collection. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```

Vrací štítek citlivosti podle indexu. Pouze pro čtení [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)

### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

Přidá štítek citlivosti na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| id | java.lang.String | Identifikátor štítku citlivosti. |
| siteId | java.util.UUID | Identifikátor webu Azure Active Directory (Azure AD). |
| isEnabled | boolean | Příznak, který určuje, zda je štítek citlivosti povolen. |
| methodType | int | Metoda přiřazení pro štítek citlivosti. |

**Návratová hodnota:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)

### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```

Přidá objekt SensitivityLabel do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | Objekt SensitivityLabel, který se má přidat na konec kolekce. |

**Návratová hodnota:**
int - Index, na který byl SensitivityLabel přidán.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Odstraní štítek citlivosti na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index štítku citlivosti, který má být smazán. |

### clear() {#clear--}
```
public abstract void clear()
```

Odstraní všechny prvky ze sbírky.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Získá počet všech prvků ve sbírce. Pouze pro čtení int.

**Návratová hodnota:**
int