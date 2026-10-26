---
title: BehaviorPropertyCollection
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta le proprietà di temporizzazione per il comportamento dell'effetto.
type: docs
url: /it/com.aspose.slides/behaviorpropertycollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

Rappresenta le proprietà di temporizzazione per il comportamento dell'effetto.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [size()](#size--) | Restituisce il numero di proprietà memorizzate nella collezione. |
| [isReadOnly()](#isReadOnly--) | Restituisce un valore che indica se il [IGenericCollection](../../com.aspose.slides/igenericcollection) è di sola lettura. |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | Aggiunge una nuova proprietà alla collezione. |
| [add(String propertyValue)](#add-java.lang.String-) | Aggiunge una nuova proprietà alla collezione. |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | Determina l'indice di un elemento specifico nella List. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Determina l'indice di un elemento specifico per valore di proprietà nella List. |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | Inserisce una nuova proprietà nella collezione all'indice specificato. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Inserisce una nuova proprietà (con il valore di proprietà specificato) nella collezione all'indice specificato. |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | Copia gli elementi del [IGenericCollection](../../com.aspose.slides/igenericcollection) in un array, iniziando da un indice di array specifico. |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | Rimuove la proprietà specificata dalla collezione. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Rimuove la proprietà specificata dalla collezione. |
| [removeAt(int index)](#removeAt-int-) | Rimuove la proprietà all'indice specificato. |
| [clear()](#clear--) | Rimuove tutte le proprietà dalla collezione. |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | Determina se il [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valore specifico. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Determina se il [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valore specifico. |
| [get_Item(int index)](#get-Item-int-) | Restituisce una proprietà all'indice specificato. |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | Imposta una proprietà all'indice specificato. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera collezione. |

### size() {#size--}
```
public final int size()
```

Restituisce il numero di proprietà memorizzate nella collezione. Read-only int.

**Restituisce:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Restituisce un valore che indica se il [IGenericCollection](../../com.aspose.slides/igenericcollection) è di sola lettura. Read-only boolean.

**Restituisce:**
boolean - true se il [IGenericCollection](../../com.aspose.slides/igenericcollection) è di sola lettura; altrimenti, false.

### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```

Aggiunge una nuova proprietà alla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Proprietà da aggiungere. |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```

Aggiunge una nuova proprietà alla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| propertyValue | java.lang.String | Valore della proprietà da aggiungere. |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```

Determina l'indice di un elemento specifico nella List.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | L'oggetto da individuare nella List. |

**Restituisce:**
int - L'indice dell'item se trovato nella lista; altrimenti, -1.

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```

Determina l'indice di un elemento specifico per valore di proprietà nella List.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| propertyValue | java.lang.String | valore della proprietà |

**Restituisce:**
int - L'indice della proprietà con il valore specificato

### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```

Inserisce una nuova proprietà nella collezione all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dove deve essere inserita la nuova proprietà. |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Proprietà da aggiungere. |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```

Inserisce una nuova proprietà (con il valore di proprietà specificato) nella collezione all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dove deve essere inserita la nuova proprietà. |
| propertyValue | java.lang.String | Valore della proprietà da aggiungere. |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```

Copia gli elementi del [IGenericCollection](../../com.aspose.slides/igenericcollection) in un Array, iniziando da un indice di Array specifico.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | L'Array monodimensionale destinazione degli elementi copiati da [IGenericCollection](../../com.aspose.slides/igenericcollection). L'Array deve avere indicizzazione a base zero. |
| arrayIndex | int | L'indice a base zero nell'array da cui inizia la copia. |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```

Rimuove la proprietà specificata dalla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Proprietà da rimuovere. |

**Restituisce:**
boolean

### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```

Rimuove la proprietà specificata dalla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| propertyValue | java.lang.String | Valore della proprietà da rimuovere. |

**Restituisce:**
boolean

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove la proprietà all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della proprietà che deve essere cancellata. |

### clear() {#clear--}
```
public final void clear()
```

Rimuove tutte le proprietà dalla collezione.

### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```

Determina se il [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valore specifico.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | La proprietà da individuare nel [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Restituisce:**
boolean - true se l'item è trovato nel [IGenericCollection](../../com.aspose.slides/igenericcollection); altrimenti, false.

### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```

Determina se il [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valore specifico.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| propertyValue | java.lang.String | Valore della proprietà da individuare nel [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Restituisce:**
boolean - true se propertyValue è trovato nel [IGenericCollection](../../com.aspose.slides/igenericcollection); altrimenti, false.

### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```

Restituisce una proprietà all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della proprietà da restituire. |

**Restituisce:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - Proprietà del comportamento di animazione.

### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```

Imposta una proprietà all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della proprietà da restituire. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```

Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - Un IGenericEnumerator che può essere utilizzato per iterare attraverso la collezione.

### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Restituisce:**
int

### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Restituisce:**
boolean

### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Restituisce:**
boolean

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```

Restituisce un iteratore java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - Un java.util.Iterator per l'intera collezione.