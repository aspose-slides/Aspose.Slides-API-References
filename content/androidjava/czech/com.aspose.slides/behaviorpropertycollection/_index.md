---
title: BehaviorPropertyCollection
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje časové vlastnosti pro chování efektu.
type: docs
url: /cs/com.aspose.slides/behaviorpropertycollection/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

Reprezentuje časové vlastnosti pro chování efektu.
## Metody

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Vrací počet vlastností uložených v kolekci. |
| [isReadOnly()](#isReadOnly--) | Získá hodnotu udávající, zda je [IGenericCollection](../../com.aspose.slides/igenericcollection) pouze pro čtení. |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | Přidá novou vlastnost do kolekce. |
| [add(String propertyValue)](#add-java.lang.String-) | Přidá novou vlastnost do kolekce. |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | Určuje index konkrétní položky v seznamu. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Určuje index konkrétní položky podle hodnoty vlastnosti v seznamu. |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | Vloží novou vlastnost do kolekce na zadaném indexu. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Vloží novou vlastnost (s určenou hodnotou vlastnosti) do kolekce na zadaném indexu. |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | Kopíruje prvky [IGenericCollection](../../com.aspose.slides/igenericcollection) do pole, počínaje konkrétním indexem pole. |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | Odstraní zadanou vlastnost z kolekce. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Odstraní zadanou vlastnost z kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní vlastnost na zadaném indexu. |
| [clear()](#clear--) | Odstraní všechny vlastnosti z kolekce. |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu. |
| [get_Item(int index)](#get-Item-int-) | Vrací vlastnost na zadaném indexu. |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | Nastaví vlastnost na zadaném indexu. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
### size() {#size--}
```
public final int size()
```


Vrací počet vlastností uložených v kolekci. Pouze pro čtení int.

**Vrací:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Získá hodnotu udávající, zda je [IGenericCollection](../../com.aspose.slides/igenericcollection) pouze pro čtení. Pouze pro čtení boolean.

**Vrací:**
boolean - true, pokud je [IGenericCollection](../../com.aspose.slides/igenericcollection) pouze pro čtení; jinak false.
### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```


Přidá novou vlastnost do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Vlastnost, která se má přidat. |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```


Přidá novou vlastnost do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| propertyValue | java.lang.String | Hodnota vlastnosti, která se má přidat. |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```


Určuje index konkrétní položky v seznamu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Objekt, který se má v seznamu najít. |

**Vrací:**
int - Index položky, pokud je v seznamu nalezena; jinak -1.
### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```


Určuje index konkrétní položky podle hodnoty vlastnosti v seznamu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| propertyValue | java.lang.String | hodnota vlastnosti |

**Vrací:**
int - Index vlastnosti s určenou hodnotou
### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```


Vloží novou vlastnost do kolekce na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index, kde má být nová vlastnost vložena. |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Vlastnost, která se má přidat. |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```


Vloží novou vlastnost (s určenou hodnotou vlastnosti) do kolekce na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index, kde má být nová vlastnost vložena. |
| propertyValue | java.lang.String | Hodnota vlastnosti, která se má přidat. |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```


Kopíruje prvky [IGenericCollection](../../com.aspose.slides/igenericcollection) do pole, počínaje konkrétním indexem pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | Jednorozměrné pole, kam jsou kopírovány prvky z [IGenericCollection](../../com.aspose.slides/igenericcollection). Pole musí mít indexování od nuly. |
| arrayIndex | int | Index v poli začínající od nuly, od kterého se kopírování zahajuje. |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```


Odstraní zadanou vlastnost z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Vlastnost, která se má odstranit. |

**Vrací:**
boolean
### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```


Odstraní zadanou vlastnost z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| propertyValue | java.lang.String | Hodnota vlastnosti, která se má odstranit. |

**Vrací:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Odstraní vlastnost na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index vlastnosti, která má být smazána. |

### clear() {#clear--}
```
public final void clear()
```


Odstraní všechny vlastnosti z kolekce.

### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```


Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Vlastnost, která se má v [IGenericCollection](../../com.aspose.slides/igenericcollection) vyhledat. |

**Vrací:**
boolean - true, pokud je položka nalezena v [IGenericCollection](../../com.aspose.slides/igenericcollection); jinak false.
### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```


Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| propertyValue | java.lang.String | Hodnota vlastnosti, která se má vyhledat v [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Vrací:**
boolean - true, pokud je propertyValue nalezen v [IGenericCollection](../../com.aspose.slides/igenericcollection); jinak false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```


Vrací vlastnost na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index vlastnosti, která se má vrátit. |

**Vrací:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - Vlastnost chování animace.
### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```


Nastaví vlastnost na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index vlastnosti, která se má vrátit. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```


Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```




**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Vrací:**
int
### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```




**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```




**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```




**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Vrací:**
boolean
### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```




**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```




**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Vrací:**
boolean
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```


Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - java.util.Iterator pro celou kolekci.