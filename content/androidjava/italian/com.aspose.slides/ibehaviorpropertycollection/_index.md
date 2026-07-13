---
title: IBehaviorPropertyCollection
second_title: Riferimento API Aspose.Slides per Android tramite Java
description: Rappresenta le proprietà di temporizzazione per il comportamento dell'effetto.
type: docs
url: /it/com.aspose.slides/ibehaviorpropertycollection/
---
**Tutte le interfacce implementate:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

Rappresenta le proprietà di temporizzazione per il comportamento dell'effetto.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | Aggiunge una nuova proprietà alla raccolta. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Determina l'indice di un elemento specifico per valore della proprietà nella List. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Inserisce una nuova proprietà (con il valore della proprietà specificato) nella raccolta all'indice specificato. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Rimuove la proprietà specificata dalla raccolta. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Determina se il [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valore specifico. |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```

Aggiunge una nuova proprietà alla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| propertyValue | java.lang.String | Valore della proprietà da aggiungere. |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```

Determina l'indice di un elemento specifico per valore della proprietà nella List.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| propertyValue | java.lang.String | valore della proprietà |

**Restituisce:**
int - L'indice della proprietà con il valore specificato
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```

Inserisce una nuova proprietà (con il valore della proprietà specificato) nella raccolta all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dove deve essere inserita una nuova proprietà. |
| propertyValue | java.lang.String | Valore della proprietà da aggiungere. |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```

Rimuove la proprietà specificata dalla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| propertyValue | java.lang.String | Valore della proprietà da rimuovere. |

**Restituisce:**
boolean - True if a property removed successfully boolean
### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

Determina se il [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valore specifico.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| propertyValue | java.lang.String | Valore della proprietà da individuare in [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Restituisce:**
boolean - true se propertyValue è trovato in [IGenericCollection](../../com.aspose.slides/igenericcollection); altrimenti, false.