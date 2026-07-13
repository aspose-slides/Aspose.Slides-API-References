---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides pro Android přes referenci Java API
description: Reprezentuje časové vlastnosti pro chování efektu.
type: docs
url: /cs/com.aspose.slides/ibehaviorpropertycollection/
---
**Všechny implementované rozhraní:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

Reprezentuje časové vlastnosti pro chování efektu.
## Metody

| Metoda | Popis |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | Přidá novou vlastnost do kolekce. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Určuje index konkrétní položky podle hodnoty vlastnosti v seznamu. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Vloží novou vlastnost (s určenou hodnotou vlastnosti) do kolekce na zadaném indexu. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Odstraní určenou vlastnost z kolekce. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu. |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```

Přidá novou vlastnost do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| propertyValue | java.lang.String | Hodnota vlastnosti, která se má přidat. |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```

Určuje index konkrétní položky podle hodnoty vlastnosti v seznamu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| propertyValue | java.lang.String | hodnota vlastnosti |

**Vrací:**
int - Index vlastnosti s určenou hodnotou
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```

Vloží novou vlastnost (s určenou hodnotou vlastnosti) do kolekce na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index, kde má být nová vlastnost vložena. |
| propertyValue | java.lang.String | Hodnota vlastnosti, která se má přidat. |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```

Odstraní určenou vlastnost z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| propertyValue | java.lang.String | Hodnota vlastnosti, která se má odstranit. |

**Vrací:**
boolean - True pokud byla vlastnost úspěšně odstraněna boolean
### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| propertyValue | java.lang.String | Hodnota vlastnosti, kterou je třeba najít v [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Vrací:**
boolean - true pokud je propertyValue nalezen v [IGenericCollection](../../com.aspose.slides/igenericcollection); jinak false.