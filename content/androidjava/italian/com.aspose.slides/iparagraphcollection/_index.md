---
title: IParagraphCollection
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta una raccolta di paragrafi.
type: docs
url: /it/com.aspose.slides/iparagraphcollection/
---
**Tutte le interfacce implementate:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

Rappresenta una raccolta di paragrafi.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'elemento all'indice specificato. |
| [getCount()](#getCount--) | Restituisce il numero di elementi effettivamente contenuti nella raccolta. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Aggiunge un Paragraph alla fine della raccolta. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Aggiunge il contenuto di ParagraphCollection alla fine della raccolta. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Inserisce un Paragraph nella raccolta all'indice specificato. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Inserisce il contenuto di ParagraphCollection nella raccolta all'indice specificato. |
| [clear()](#clear--) | Rimuove tutti gli elementi dalla raccolta. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice specificato della raccolta. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Rimuove la prima occorrenza di un determinato paragrafo. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Aggiunge testo da una stringa HTML specificata alla raccolta. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Aggiunge testo da una stringa HTML specificata alla raccolta. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Converte i paragrafi specificati in HTML e lo restituisce come oggetto String. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```


Restituisce l'elemento all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IParagraph](../../com.aspose.slides/iparagraph)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Restituisce il numero di elementi effettivamente contenuti nella raccolta. Solo lettura int.

**Restituisce:**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```


Aggiunge un Paragraph alla fine della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Il Paragraph da aggiungere alla fine della raccolta. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```


Aggiunge il contenuto di ParagraphCollection alla fine della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | La ParagraphCollection da aggiungere alla fine della raccolta. |

**Restituisce:**
int - L'indice al quale il Paragraph è stato aggiunto o -1 se non c'è nulla da aggiungere.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```


Inserisce un Paragraph nella raccolta all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero al quale inserire il Paragraph. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Il Paragraph da inserire. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```


Inserisce il contenuto di ParagraphCollection nella raccolta all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero al quale inserire i paragrafi. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | I paragrafi da inserire. |

### clear() {#clear--}
```
public abstract void clear()
```


Rimuove tutti gli elementi dalla raccolta.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Rimuove l'elemento all'indice specificato della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero dell'elemento da rimuovere. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```


Rimuove la prima occorrenza di un paragrafo specifico.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Il paragrafo da rimuovere dalla raccolta. |

**Restituisce:**
boolean - true se l'elemento è stato rimosso con successo; altrimenti, false.
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```


Aggiunge testo da una stringa HTML specificata alla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```


Aggiunge testo da una stringa HTML specificata alla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Oggetto callback Resolver che risolve gli URI e recupera gli oggetti referenziati. |
| uri | java.lang.String | URI per aggiungere il documento HTML. Usato per risolvere i collegamenti relativi.

--------------------

Specificare il resolver può potenzialmente introdurre una vulnerabilità. Usare con cautela. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
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