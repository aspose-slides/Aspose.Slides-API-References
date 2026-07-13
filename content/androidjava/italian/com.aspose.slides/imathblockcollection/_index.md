---
title: IMathBlockCollection
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Raccolta di blocchi matematici IMathBlock
type: docs
url: /it/com.aspose.slides/imathblockcollection/
---
**Tutte le interfacce implementate:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

Raccolta di blocchi matematici (IMathBlock)

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
> ```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | Aggiunge IMathBlock alla fine della raccolta. |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | Inserisce IMathBlock nella raccolta all'indice specificato. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | Rimuove la prima occorrenza di un oggetto specifico dalla raccolta. |
| [removeAt(int index)](#removeAt-int-) | Rimuove un elemento all'indice specificato della raccolta. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | Determina se la raccolta contiene un valore specifico. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | Determina l'indice di un IMathBlock specifico nella raccolta. |
| [getCount()](#getCount--) | Ottiene il numero di elementi effettivamente contenuti nella raccolta. |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Ottiene l'elemento all'indice specificato. |
| [clear()](#clear--) | Rimuove tutti gli elementi dalla raccolta. |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

Aggiunge IMathBlock alla fine della raccolta.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Un blocco matematico che verrà aggiunto alla fine della raccolta |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```

Inserisce IMathBlock nella raccolta all'indice specificato.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero al quale un elemento deve essere inserito. |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | L'IMathBlock da inserire. |

### remove(IMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```

Rimuove la prima occorrenza di un oggetto specifico dalla raccolta.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.remove(block);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | L'oggetto da rimuovere dalla raccolta. |

**Restituisce:**
boolean - true se l'elemento è stato rimosso con successo dalla raccolta; altrimenti, false. Questo metodo restituisce false anche se l'elemento non è stato trovato nella raccolta originale.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Rimuove un elemento all'indice specificato della raccolta.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento da rimuovere. |

### contains(IMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```

Determina se la raccolta contiene un valore specifico.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.addd(block);
>  bool contains = blockCollection.contains(block);
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | L'oggetto da individuare nella raccolta. |

**Restituisce:**
boolean - true se l'elemento è trovato nella raccolta; altrimenti, false.
### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

Determina l'indice di un IMathBlock specifico nella raccolta.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | L'elemento da individuare nella raccolta. |

**Restituisce:**
int - L'indice dell'elemento se trovato nella raccolta; altrimenti, -1.
### getCount() {#getCount--}
```
public abstract int getCount()
```

Ottiene il numero di elementi effettivamente contenuti nella raccolta. int di sola lettura.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**Restituisce:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```

Ottiene l'elemento all'indice specificato. [IMathBlock](../../com.aspose.slides/imathblock) di sola lettura.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento da ottenere. |

**Restituisce:**
[IMathBlock](../../com.aspose.slides/imathblock) - Il blocco di un testo matematico.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```

Ottiene l'elemento all'indice specificato. [IMathBlock](../../com.aspose.slides/imathblock) di sola lettura.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento da impostare. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | Il blocco di un testo matematico. |

### clear() {#clear--}
```
public abstract void clear()
```

Rimuove tutti gli elementi dalla raccolta.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```