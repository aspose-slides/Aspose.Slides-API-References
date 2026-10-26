---
title: IParagraphCollection
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa uma coleção de parágrafos.
type: docs
url: /pt/com.aspose.slides/iparagraphcollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

Representa uma coleção de parágrafos.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [getCount()](#getCount--) | Obtém o número de elementos realmente contidos na coleção. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Adiciona um Paragraph ao final da coleção. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Adiciona o conteúdo de ParagraphCollection ao final da coleção. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Insere um Paragraph na coleção no índice especificado. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Insere o conteúdo de ParagraphCollection na coleção no índice especificado. |
| [clear()](#clear--) | Remove todos os elementos da coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove o elemento no índice especificado da coleção. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Remove a primeira ocorrência de um parágrafo específico. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Adiciona texto de uma string HTML especificada à coleção. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Adiciona texto de uma string HTML especificada à coleção. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Converte os parágrafos especificados para HTML e o retorna como objeto String. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```

Obtém o elemento no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IParagraph](../../com.aspose.slides/iparagraph)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Obtém o número de elementos realmente contidos na coleção. Somente leitura int.

**Retorna:**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```

Adiciona um Paragraph ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | O Paragraph a ser adicionado ao final da coleção. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```

Adiciona o conteúdo de ParagraphCollection ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | O ParagraphCollection a ser adicionado ao final da coleção. |

**Retorna:**
int - O índice no qual o Paragraph foi adicionado ou -1 se não houver nada a adicionar.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```

Insere um Paragraph na coleção no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual o Paragraph deve ser inserido. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | O Paragraph a inserir. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```

Insere o conteúdo de ParagraphCollection na coleção no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual os parágrafos devem ser inseridos. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Os parágrafos a serem inseridos. |

### clear() {#clear--}
```
public abstract void clear()
```

Remove todos os elementos da coleção.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Remove o elemento no índice especificado da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do elemento a ser removido. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```

Remove a primeira ocorrência de um parágrafo específico.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | O parágrafo a ser removido da coleção. |

**Retorna:**
boolean - true se o item foi removido com sucesso; caso contrário, false.
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```

Adiciona texto de uma string HTML especificada à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Adiciona texto de uma string HTML especificada à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objeto de callback Resolver que resolve URIs e busca objetos referenciados. |
| uri | java.lang.String | URI para adicionar documento HTML. Usado para resolver links relativos.

--------------------

Especificar o resolver pode potencialmente introduzir uma vulnerabilidade. Use com cautela. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Converte os parágrafos especificados para HTML e o retorna como objeto String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| firstParagraphIndex | int | Índice do primeiro parágrafo int |
| paragraphsCount | int | Contagem de parágrafos int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Opções de conversão [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Retorna:**
java.lang.String - HTML gerado.