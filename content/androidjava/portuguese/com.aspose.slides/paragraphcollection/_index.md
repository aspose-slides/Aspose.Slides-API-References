---
title: ParagraphCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de parágrafos.
type: docs
url: /pt/com.aspose.slides/paragraphcollection/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

Representa uma coleção de Paragraph.
## Métodos

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Obtém o número de elementos realmente contidos na coleção. |
| [isReadOnly()](#isReadOnly--) | Obtém um valor que indica se o [IGenericCollection](../../com.aspose.slides/igenericcollection) é somente leitura. |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Adiciona um Paragraph ao final da coleção. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Adiciona o conteúdo de ParagraphCollection ao final da coleção. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | Determina o índice de um item específico na List. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Insere um Paragraph na coleção no índice especificado. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Insere o conteúdo de ParagraphCollection na coleção no índice especificado. |
| [clear()](#clear--) | Remove todos os elementos da coleção. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | Determina se o [IGenericCollection](../../com.aspose.slides/igenericcollection) contém um valor específico. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | Copies the elements of the [IGenericCollection](../../com.aspose.slides/igenericcollection) to an Array, starting at a particular Array index. |
| [removeAt(int index)](#removeAt-int-) | Remove o elemento no índice especificado da coleção. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Remove a primeira ocorrência de um objeto específico do [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Retorna um enumerador que itera sobre a coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para a coleção inteira. |
| [getSlide()](#getSlide--) | Retorna o slide pai de uma coleção de paragraphs. |
| [getPresentation()](#getPresentation--) | Retorna a apresentação pai de uma coleção de paragraphs. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Adiciona texto de uma string html especificada à coleção. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Adiciona texto de uma string html especificada à coleção. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Converte os paragraphs especificados para HTML e o retorna como objeto String. |

### getCount() {#getCount--}
```
public final int getCount()
```

Obtém o número de elementos realmente contidos na coleção. Somente leitura int.

**Retorna:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Obtém um valor que indica se o [IGenericCollection](../../com.aspose.slides/igenericcollection) é somente leitura. Somente leitura boolean.

**Retorna:**
boolean - verdadeiro se o [IGenericCollection](../../com.aspose.slides/igenericcollection) for somente leitura; caso contrário, falso.

### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```

Obtém o elemento no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IParagraph](../../com.aspose.slides/iparagraph)

### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```

Adiciona um Paragraph ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | O Paragraph a ser adicionado ao final da coleção. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```

Adiciona o conteúdo de ParagraphCollection ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | O ParagraphCollection a ser adicionado ao final da coleção. |

**Retorna:**
int - O índice no qual o Paragraph foi adicionado ou -1 se não houver nada a adicionar.

### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```

Determina o índice de um item específico na List.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | O objeto a ser localizado na List. |

**Retorna:**
int - O índice do item se encontrado na lista; caso contrário, -1.

### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```

Insere um Paragraph na coleção no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual o Paragraph deve ser inserido. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | O Paragraph a ser inserido. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```

Insere o conteúdo de ParagraphCollection na coleção no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual os paragraphs devem ser inseridos. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Os paragraphs a serem inseridos. |

### clear() {#clear--}
```
public final void clear()
```

Remove todos os elementos da coleção.

### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```

Determina se o [IGenericCollection](../../com.aspose.slides/igenericcollection) contém um valor específico.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | O objeto a ser localizado no [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retorna:**
boolean - verdadeiro se o item for encontrado no [IGenericCollection](../../com.aspose.slides/igenericcollection); caso contrário, falso.

### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```

Copia os elementos do [IGenericCollection](../../com.aspose.slides/igenericcollection) para um Array, começando em um índice específico do Array.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | O Array unidimensional que é o destino dos elementos copiados de [IGenericCollection](../../com.aspose.slides/igenericcollection). O Array deve ter indexação baseada em zero. |
| arrayIndex | int | O índice baseado em zero no array onde a cópia começa. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Remove o elemento no índice especificado da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do elemento a ser removido. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```

Remove a primeira ocorrência de um objeto específico do [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | O objeto a ser removido do [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retorna:**
boolean - verdadeiro se o item foi removido com sucesso do [IGenericCollection](../../com.aspose.slides/igenericcollection); caso contrário, falso. Este método também retorna falso se o item não for encontrado no [IGenericCollection](../../com.aspose.slides/igenericcollection) original.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```

Retorna um enumerador que itera sobre a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```

Retorna um iterador java para a coleção inteira.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - An java.util.Iterator for the entire collection.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retorna o slide pai de uma coleção de paragraphs. Somente leitura [BaseSlide](../../com.aspose.slides/baseslide).

**Retorna:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retorna a apresentação pai de uma coleção de paragraphs. Somente leitura [IPresentation](../../com.aspose.slides/ipresentation).

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation)

### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```

Adiciona texto de uma string html especificada à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Adiciona texto de uma string html especificada à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objeto de callback de resolvedor que resolve URIs e busca objetos referenciados. |
| uri | java.lang.String | URI para adicionar o documento HTML. Usado para resolver links relativos.

--------------------

Especificar o resolvedor pode potencialmente introduzir uma vulnerabilidade. Use com cautela. |

### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Converte os paragraphs especificados para HTML e o retorna como objeto String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| firstParagraphIndex | int | Primeiro índice de parágrafo int |
| paragraphsCount | int | Contagem de parágrafos int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Opções de conversão [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Retorna:**
java.lang.String - HTML gerado.