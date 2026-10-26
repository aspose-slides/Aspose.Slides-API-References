---
title: IMathElementCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una raccolta di elementi matematici MathElement.
type: docs
url: /it/com.aspose.slides/imathelementcollection/
---
**Tutte le interfacce implementate:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

Rappresenta una raccolta di elementi matematici (MathElement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
> ```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [getCount()](#getCount--) | Ottiene il numero di elementi effettivamente contenuti nella raccolta. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Aggiunge un elemento matematico alla fine della raccolta. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Determina l'indice di uno specifico elemento matematico nella raccolta. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Inserisce un elemento matematico nella raccolta all'indice specificato. |
| [clear()](#clear--) | Rimuove tutti gli elementi dalla raccolta. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Determina se la raccolta contiene un valore specifico. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Rimuove la prima occorrenza di un oggetto specifico dalla raccolta. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice specificato della raccolta. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Copia nell'array specificato. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```


Ottiene l'elemento all'indice specificato. Sola lettura [IMathElement](../../com.aspose.slides/imathelement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = collection.get_Item(0);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice a base zero dell'elemento da ottenere |

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Ottiene il numero di elementi effettivamente contenuti nella raccolta. Sola lettura int.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  int count = collection.getCount();
> ```

**Restituisce:**
int
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public abstract void add(IMathElement item)
```


Aggiunge un elemento matematico alla fine della raccolta.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.add(new MathematicalText("+"));
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | L'IMathElement da aggiungere alla fine della raccolta. |

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public abstract int indexOf(IMathElement item)
```


Determina l'indice di uno specifico elemento matematico nella raccolta.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = collection.indexOf(plusElement);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | L'elemento da individuare nella raccolta. |

**Restituisce:**
int - L'indice dell'elemento se trovato nella raccolta; altrimenti, -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```


Inserisce un elemento matematico nella raccolta all'indice specificato.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice a base zero al quale l'IMathElement deve essere inserito. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | L'IMathElement da inserire. |

### clear() {#clear--}
```
public abstract void clear()
```


Rimuove tutti gli elementi dalla raccolta.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public abstract boolean contains(IMathElement item)
```


Determina se la raccolta contiene un valore specifico.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  bool contains = collection.contains(plusElement);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | L'oggetto da individuare nella raccolta. |

**Restituisce:**
boolean - true se l'elemento è trovato nella raccolta; altrimenti, false.
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public abstract boolean remove(IMathElement item)
```


Rimuove la prima occorrenza di un oggetto specifico dalla raccolta.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.remove(plusElement);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | L'oggetto da rimuovere dalla raccolta. |

**Restituisce:**
boolean - true se l'oggetto è stato rimosso con successo dalla raccolta; altrimenti, false. Questo metodo restituisce anche false se l'oggetto non è stato trovato nella raccolta originale.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Rimuove l'elemento all'indice specificato della raccolta.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.removeAt(2);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice a base zero dell'elemento da rimuovere. |

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public abstract void copyTo(IMathElement[] array, int arrayIndex)
```


Copia nell'array specificato.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[collection.Count];
>  collection.copyTo(destinationArray, 0);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Array di destinazione. |
| arrayIndex | int | Indice da cui iniziare la copia. |