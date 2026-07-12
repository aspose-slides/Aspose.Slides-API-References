---
title: ISectionCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de seções.
type: docs
url: /pt/com.aspose.slides/isectioncollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

Representa uma coleção de seções.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Adiciona nova seção iniciada a partir de um slide específico. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Adiciona seção vazia na posição especificada da coleção. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Remove a seção e os slides contidos na seção. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Remove a seção. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Move a seção e seus slides da coleção para a posição especificada. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Adiciona seção vazia ao final da coleção. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Retorna um índice da seção especificada na coleção. |
| [clear()](#clear--) | Remove todas as seções da coleção. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
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
public abstract ISection addSection(String name, ISlide startedFromSlide)
```

Adiciona nova seção iniciada a partir de um slide específico.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da seção |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Primeiro slide da seção |

**Retorna:**
[ISection](../../com.aspose.slides/isection) - Seção adicionada.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```

Adiciona seção vazia na posição especificada da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da seção |
| index | int | Índice da nova seção. |

**Retorna:**
[ISection](../../com.aspose.slides/isection) - Seção adicionada.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```

Remove a seção e os slides contidos na seção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | A seção a ser removida da coleção. |
### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```

Remove a seção. Os slides contidos na seção serão mesclados na seção anterior.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | A seção a ser removida da coleção. |
### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```

Move a seção e seus slides da coleção para a posição especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Seção a mover. |
| index | int | Índice de destino. |
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```

Adiciona seção vazia ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da seção |

**Retorna:**
[ISection](../../com.aspose.slides/isection) - Seção adicionada.
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```

Retorna um índice da seção especificada na coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Seção a encontrar. |

**Retorna:**
int - Índice da seção ou -1 se a seção não pertencer a esta coleção.
### clear() {#clear--}
```
public abstract void clear()
```

Remove todas as seções da coleção.