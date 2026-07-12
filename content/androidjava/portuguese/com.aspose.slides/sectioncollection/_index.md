---
title: SectionCollection
second_title: Referência da API Java para Aspose.Slides para Android
description: Representa uma coleção de seções.
type: docs
url: /pt/com.aspose.slides/sectioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

Representa uma coleção de seções.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Adiciona uma seção de slides iniciada a partir de um slide específico. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Adiciona uma seção vazia ao final da coleção. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Adiciona uma seção vazia à posição especificada da coleção. |
| [size()](#size--) | Obtém o número de elementos realmente contidos na coleção. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Retorna um índice da seção especificada na coleção. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Remove a seção e os slides contidos na seção. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Remove a seção. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Move a seção e seus slides da coleção para a posição especificada. |
| [clear()](#clear--) | Remove todas as seções da coleção. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia a coleção inteira para o array especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor que indica se o acesso à coleção está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna uma raiz de sincronização. |
| [iterator()](#iterator--) | Retorna um enumerador que itera pela coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterator java para a coleção inteira. |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

Obtém o elemento no índice especificado. Somente leitura [ISection](../../com.aspose.slides/isection).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```

Adiciona uma seção de slides iniciada a partir de um slide específico.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da seção |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Primeiro slide da seção |

**Retorna:**
[ISection](../../com.aspose.slides/isection) - Seção adicionada.
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```

Adiciona uma seção vazia ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da seção |

**Retorna:**
[ISection](../../com.aspose.slides/isection) - Seção adicionada.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```

Adiciona uma seção vazia à posição especificada da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da seção |
| index | int | Índice da nova seção. |

**Retorna:**
[ISection](../../com.aspose.slides/isection) - Seção adicionada.
### size() {#size--}
```
public final int size()
```

Obtém o número de elementos realmente contidos na coleção. Somente leitura int.

**Retorna:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

Retorna um índice da seção especificada na coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Seção a encontrar. |

**Retorna:**
int - Índice de uma seção ou -1 se a seção não pertencer a esta coleção.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

Remove a seção e os slides contidos na seção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | A seção a ser removida da coleção. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

Remove a seção. Os slides contidos na seção serão mesclados na seção anterior.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | A seção a ser removida da coleção. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

Move a seção e seus slides da coleção para a posição especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Seção a mover. |
| index | int | Índice de destino. |

### clear() {#clear--}
```
public final void clear()
```

Remove todas as seções da coleção.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia a coleção inteira para o array especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino |
| index | int | ÍNDICE no array de destino. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retorna um valor que indica se o acesso à coleção está sincronizado (thread-safe). Somente leitura boolean.

**Retorna:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retorna uma raiz de sincronização. Somente leitura Object.

**Retorna:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

Retorna um enumerador que itera pela coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Um IGenericEnumerator que pode ser usado para iterar pela coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

Retorna um iterator java para a coleção inteira.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Um java.util.Iterator para a coleção inteira.