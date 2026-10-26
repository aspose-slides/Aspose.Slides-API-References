---
title: ParagraphCollection
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta una collezione di paragrafi.
type: docs
url: /it/com.aspose.slides/paragraphcollection/
---
**Ereditarietà:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le Interfacce Implementate:**
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

Rappresenta una collezione di paragrafi.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCount()](#getCount--) | Restituisce il numero di elementi effettivamente contenuti nella collezione. |
| [isReadOnly()](#isReadOnly--) | Restituisce un valore che indica se il [IGenericCollection](../../com.aspose.slides/igenericcollection) è di sola lettura. |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'elemento all'indice specificato. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Aggiunge un Paragraph alla fine della collezione. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Aggiunge un contenuto di ParagraphCollection alla fine della collezione. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | Determina l'indice di un elemento specifico nella List. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Inserisce un Paragraph nella collezione all'indice specificato. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Inserisce un contenuto di ParagraphCollection nella collezione all'indice specificato. |
| [clear()](#clear--) | Rimuove tutti gli elementi dalla collezione. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | Determina se il [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valore specifico. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | Copia gli elementi di [IGenericCollection](../../com.aspose.slides/igenericcollection) in un Array, iniziando da un determinato indice dell'Array. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice specificato della collezione. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Rimuove la prima occorrenza di un oggetto specifico da [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iterator java per l'intera collezione. |
| [getSlide()](#getSlide--) | Restituisce la slide padre di una collezione di paragrafi. |
| [getPresentation()](#getPresentation--) | Restituisce la presentazione padre di una collezione di paragrafi. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Aggiunge testo da una stringa html specificata alla collezione. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Aggiunge testo da una stringa html specificata alla collezione. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Converte i paragrafi specificati in HTML e lo restituisce come oggetto String. |
### getCount() {#getCount--}
```
public final int getCount()
```

Restituisce il numero di elementi effettivamente contenuti nella collezione. Solo lettura int.

**Restituisce:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Restituisce un valore che indica se il [IGenericCollection](../../com.aspose.slides/igenericcollection) è di sola lettura. Solo lettura boolean.

**Restituisce:**
boolean - true se il [IGenericCollection](../../com.aspose.slides/igenericcollection) è di sola lettura; altrimenti, false.
### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```

Restituisce l'elemento all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IParagraph](../../com.aspose.slides/iparagraph)
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```

Aggiunge un Paragraph alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Il Paragraph da aggiungere alla fine della collezione. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```

Aggiunge un contenuto di ParagraphCollection alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Il ParagraphCollection da aggiungere alla fine della collezione. |

**Restituisce:**
int - L'indice al quale il Paragraph è stato aggiunto o -1 se non c'è nulla da aggiungere.
### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```

Determina l'indice di un elemento specifico nella List.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | L'oggetto da individuare nella List. |

**Restituisce:**
int - L'indice dell'elemento se trovato nella lista; altrimenti, -1.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```

Inserisce un Paragraph nella collezione all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero al quale inserire il Paragraph. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Il Paragraph da inserire. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```

Inserisce un contenuto di ParagraphCollection nella collezione all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero al quale i paragrafi dovrebbero essere inseriti. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | I paragrafi da inserire. |

### clear() {#clear--}
```
public final void clear()
```

Rimuove tutti gli elementi dalla collezione.

### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```

Determina se il [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valore specifico.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | L'oggetto da individuare nel [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Restituisce:**
boolean - true se l'elemento è trovato nel [IGenericCollection](../../com.aspose.slides/igenericcollection); altrimenti, false.
### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```

Copia gli elementi di [IGenericCollection](../../com.aspose.slides/igenericcollection) in un Array, iniziando da un determinato indice dell'Array.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | L'Array monodimensionale che è la destinazione degli elementi copiati da [IGenericCollection](../../com.aspose.slides/igenericcollection). L'Array deve avere indicizzazione basata su zero. |
| arrayIndex | int | L'indice basato su zero nell'array a partire dal quale inizia la copia. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove l'elemento all'indice specificato della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento da rimuovere. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```

Rimuove la prima occorrenza di un oggetto specifico da [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | L'oggetto da rimuovere dal [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Restituisce:**
boolean - true se l'elemento è stato rimosso con successo da [IGenericCollection](../../com.aspose.slides/igenericcollection); altrimenti, false. Questo metodo restituisce anche false se l'elemento non viene trovato nell'originale [IGenericCollection](../../com.aspose.slides/igenericcollection).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```

Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```

Restituisce un iterator java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - Un java.util.Iterator per l'intera collezione.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Restituisce la slide padre di una collezione di paragrafi. Solo lettura [BaseSlide](../../com.aspose.slides/baseslide).

**Restituisce:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Restituisce la presentazione padre di una collezione di paragrafi. Solo lettura [IPresentation](../../com.aspose.slides/ipresentation).

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation)
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```

Aggiunge testo da una stringa html specificata alla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Aggiunge testo da una stringa html specificata alla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Oggetto di callback Resolver che risolve gli URI e recupera gli oggetti referenziati. |
| uri | java.lang.String | URI per aggiungere il documento HTML. Usato per risolvere i link relativi.

--------------------

Specificare il resolver può potenzialmente introdurre una vulnerabilità. Usare con cautela. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Converte i paragrafi specificati in HTML e lo restituisce come oggetto String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstParagraphIndex | int | Indice del primo paragrafo int |
| paragraphsCount | int | Numero di paragrafi int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Opzioni di conversione [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Restituisce:**
java.lang.String - HTML generato.