---
title: MathBlock
second_title: Riferimento API Java di Aspose.Slides per Android
description: Specifica un'istanza di testo matematico contenuta all'interno di un MathParagraph e che inizia su una propria riga.
type: docs
url: /it/com.aspose.slides/mathblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

Specifica un'istanza di testo matematico contenuta all'interno di un MathParagraph e che inizia su una propria riga. Tutte le zone matematiche, comprese equazioni, espressioni, array di equazioni o espressioni e formule, sono rappresentate da un blocco matematico.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MathBlock()](#MathBlock--) | Inizializza una nuova istanza della classe MathBlock. |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | Crea un nuovo blocco matematico e inserisce l'elemento specificato. |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Crea un nuovo blocco matematico e inserisce gli elementi specificati. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCount()](#getCount--) | Restituisce il numero di elementi matematici figlio effettivamente contenuti nella collezione. |
| [get_Item(int index)](#get-Item-int-) | Ottiene o imposta IMathElement all'indice specificato. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | Ottiene o imposta IMathElement all'indice specificato. |
| [isReadOnly()](#isReadOnly--) | Restituisce false perché la collezione di elementi figlio può essere modificata. |
| [getChildren()](#getChildren--) | Ottiene gli elementi figlio |
| [getParent_Immediate()](#getParent-Immediate--) | Restituisce l'oggetto Parent_Immediate. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Aggiunge un elemento matematico alla fine della collezione. |
| [clear()](#clear--) | Rimuove tutti gli elementi dalla collezione. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Determina se la collezione contiene un valore specifico. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Copia nell'array specificato. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Rimuove la prima occorrenza di un oggetto specifico dalla collezione. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore Java per l'intera collezione. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Determina l'indice di un elemento matematico specifico nella collezione. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Inserisce un MathElement nella collezione all'indice specificato. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice specificato della collezione. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Unisce un elemento matematico a questo blocco matematico |
| [join(String mathText)](#join-java.lang.String-) | Unisce un testo matematico a questo blocco matematico |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Unisce un altro blocco matematico a questo |
| [delimit(char separatorCharacter)](#delimit-char-) | Delimita gli elementi figlio con il carattere separatore (senza le parentesi) |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Racchiude gli elementi figlio di questo blocco nei caratteri specificati, come parentesi o altri caratteri, come inquadratura |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Racchiude gli elementi figlio di questo blocco nei caratteri specificati, come parentesi o altri, come inquadratura e li delimita con un carattere separatore |
| [toMathArray()](#toMathArray--) | Posiziona gli elementi figlio in un array verticale |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Salva il contenuto di questo [MathBlock](../../com.aspose.slides/mathblock) come MathML |
### MathBlock() {#MathBlock--}
```
public MathBlock()
```

Inizializza una nuova istanza della classe MathBlock.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```


### MathBlock(IMathElement mathElement) {#MathBlock-com.aspose.slides.IMathElement-}
```
public MathBlock(IMathElement mathElement)
```

Crea un nuovo blocco matematico e inserisce l'elemento specificato.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | L'elemento matematico da inserire nel blocco |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

Crea un nuovo blocco matematico e inserisce gli elementi specificati.

--------------------

> ```
> Example:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Elementi matematici da inserire nel blocco |

### getCount() {#getCount--}
```
public final int getCount()
```

Restituisce il numero di elementi matematici figlio effettivamente contenuti nella collezione. Intero a sola lettura.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**Restituisce:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```

Ottiene o imposta IMathElement all'indice specificato.

--------------------

> ```
> Esempio:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento |

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement) - L'elemento matematico.
### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

Ottiene o imposta IMathElement all'indice specificato.

--------------------

> ```
> Esempio:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento |
| value | [IMathElement](../../com.aspose.slides/imathelement) | L'elemento matematico. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Restituisce false perché la collezione di elementi figlio può essere modificata.

**Restituisce:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Ottiene gli elementi figlio

**Restituisce:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. IDOMObject a sola lettura.

**Restituisce:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

Aggiunge un elemento matematico alla fine della collezione.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | L'IMathElement da aggiungere alla fine della collezione. |
### clear() {#clear--}
```
public final void clear()
```

Rimuove tutti gli elementi dalla collezione.

--------------------

> ```
> Esempio:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.clear();
> ```


### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public final boolean contains(IMathElement item)
```

Determina se la collezione contiene un valore specifico.

--------------------

> ```
> Esempio:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  boolean contains = mathBlock.Contains(plusElement);
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | L'oggetto da individuare nella collezione. |

**Restituisce:**
boolean - true se l'elemento è trovato nella collezione; altrimenti, false.
### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

Copia nell'array specificato.

--------------------

> ```
> Esempio:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[mathBlock.Count];
>  mathBlock.copyTo(destinationArray, 0);
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | [IMathElement[]](../../com.aspose.slides/imathelement) | Array di destinazione. |
| arrayIndex | int | Indice da cui iniziare la copia. |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```

Rimuove la prima occorrenza di un oggetto specifico dalla collezione.

--------------------

> ```
> Esempio:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.Remove(plusElement);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | L'oggetto da rimuovere dalla collezione. |

**Restituisce:**
boolean - true se l'elemento è stato rimosso con successo dalla collezione; altrimenti, false. Questo metodo restituisce anche false se l'elemento non è trovato nella collezione originale.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

Restituisce un iteratore Java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.IEnumerator - Un java.util.Iterator per l'intera collezione.
### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

Determina l'indice di un elemento matematico specifico nella collezione.

--------------------

> ```
> Esempio:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = mathBlock.indexOf(plusElement);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | L'elemento da individuare nella collezione. |

**Restituisce:**
int - L'indice dell'elemento se trovato nella collezione; altrimenti, -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

Inserisce un MathElement nella collezione all'indice specificato.

--------------------

> ```
> Esempio:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero al quale il MathElement deve essere inserito. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Il MathElement da inserire. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove l'elemento all'indice specificato della collezione.

--------------------

> ```
> Esempio:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.removeAt(2);
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento da rimuovere. |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Unisce un elemento matematico a questo blocco matematico

--------------------

> ```
> Esempio:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | L'elemento da unire |

**Restituisce:**
[IMathBlock](../../com.aspose.slides/imathblock) - L'istanza corrente di IMathBlock
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Unisce un testo matematico a questo blocco matematico

--------------------

> ```
> Esempio:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathText | java.lang.String | Testo matematico da unire. |

**Restituisce:**
[IMathBlock](../../com.aspose.slides/imathblock) - Un nuovo IMathBlock contenente questa istanza e l'argomento specificato
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

Unisce un altro blocco matematico a questo

--------------------

> ```
> Esempio:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Il blocco da unire. |

**Restituisce:**
[IMathBlock](../../com.aspose.slides/imathblock) - questo blocco matematico dopo l'unione
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

Delimita gli elementi figlio con il carattere separatore (senza le parentesi)

--------------------

> ```
> Esempio:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| separatorCharacter | char | Carattere separatore |

**Restituisce:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - L'elemento matematico di tipo [IMathDelimiter](../../com.aspose.slides/imathdelimiter)
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Racchiude gli elementi figlio di questo blocco nei caratteri specificati, come parentesi o altri caratteri, come inquadratura

--------------------

> ```
> Esempio:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| beginningCharacter | char | Carattere di inizio (di solito parentesi sinistra) |
| endingCharacter | char | Carattere di fine (di solito parentesi destra) |

**Restituisce:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - L'elemento matematico di tipo [IMathDelimiter](../../com.aspose.slides/imathdelimiter) che include i caratteri specificati come inquadratura
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Racchiude gli elementi figlio di questo blocco nei caratteri specificati, come parentesi o altri, come inquadratura e li delimita con un carattere separatore

--------------------

> ```
> Esempio:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| beginningCharacter | char | Carattere di inizio (di solito parentesi sinistra) |
| endingCharacter | char | Carattere di fine (di solito parentesi destra) |
| separatorCharacter | char | Carattere separatore |

**Restituisce:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - L'elemento matematico di tipo [IMathDelimiter](../../com.aspose.slides/imathdelimiter) che include i caratteri specificati come inquadratura e delimitatore
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Posiziona gli elementi figlio in un array verticale

--------------------

> ```
> Esempio:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```


**Restituisce:**
[IMathArray](../../com.aspose.slides/imatharray) - Nuova istanza di tipo [IMathArray](../../com.aspose.slides/imatharray)
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

Salva il contenuto di questo [MathBlock](../../com.aspose.slides/mathblock) come MathML

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Flusso di destinazione |