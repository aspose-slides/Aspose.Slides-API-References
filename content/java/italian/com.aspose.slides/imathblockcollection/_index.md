---
title: IMathBlockCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Raccolta di blocchi matematici IMathBlock
type: docs
url: /it/com.aspose.slides/imathblockcollection/
---
**Tutte le interfacce implementate:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

Collezione di blocchi matematici (IMathBlock)

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
> ```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | Aggiunge IMathBlock alla fine della collezione. |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | Inserisce IMathBlock nella collezione all'indice specificato. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | Rimuove la prima occorrenza di un oggetto specifico dalla collezione. |
| [removeAt(int index)](#removeAt-int-) | Rimuove un elemento all'indice specificato della collezione. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | Determina se la collezione contiene un valore specifico. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | Determina l'indice di un IMathBlock specifico nella collezione. |
| [getCount()](#getCount--) | Ottiene il numero di elementi effettivamente contenuti nella collezione. |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Ottiene l'elemento all'indice specificato. |
| [clear()](#clear--) | Rimuove tutti gli elementi dalla collezione. |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

Aggiunge IMathBlock alla fine della collezione.

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
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Un blocco matematico che sarà aggiunto alla fine della collezione |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```

Inserisce IMathBlock nella collezione all'indice specificato.

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

Rimuove la prima occorrenza di un oggetto specifico dalla collezione.

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
| item | [IMathBlock](../../com.aspose.slides/imathblock) | L'oggetto da rimuovere dalla collezione. |

**Restituisce:**
boolean - true se l'elemento è stato rimosso con successo dalla collezione; altrimenti, false. Questo metodo restituisce anche false se l'elemento non è presente nella collezione originale.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Rimuove un elemento all'indice specificato della collezione.

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

Determina se la collezione contiene un valore specifico.

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
| item | [IMathBlock](../../com.aspose.slides/imathblock) | L'oggetto da individuare nella collezione. |

**Restituisce:**
boolean - true se l'elemento è trovato nella collezione; altrimenti, false.
### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

Determina l'indice di un IMathBlock specifico nella collezione.

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
| item | [IMathBlock](../../com.aspose.slides/imathblock) | L'elemento da individuare nella collezione. |

**Restituisce:**
int - L'indice dell'elemento se trovato nella collezione; altrimenti, -1.
### getCount() {#getCount--}
```
public abstract int getCount()
```

Ottiene il numero di elementi effettivamente contenuti nella collezione. Solo lettura int.

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

Ottiene l'elemento all'indice specificato. Solo lettura [IMathBlock](../../com.aspose.slides/imathblock).

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

Ottiene l'elemento all'indice specificato. Solo lettura [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Esempio:
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

Rimuove tutti gli elementi dalla collezione.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```