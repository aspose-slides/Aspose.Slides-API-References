---
title: ITabCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de tabs.
type: docs
url: /pt/com.aspose.slides/itabcollection/
---
**Todas as interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

Representa uma coleção de tabs.
## Métodos

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [add(double position, int align)](#add-double-int-) | Adiciona uma Tab à coleção. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Adiciona uma Tab à coleção. |
| [clear()](#clear--) | Remove todos os elementos da coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove o elemento no índice especificado da coleção. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```

Obtém o elemento no índice especificado. Somente leitura [ITab](../../com.aspose.slides/itab).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```

Adiciona uma Tab à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| position | double | Posição da Tab. |
| align | int | Alinhamento da Tab. |

**Retorna:**
[ITab](../../com.aspose.slides/itab) - Tab adicionada.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```

Adiciona uma Tab à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | O objeto Tab a ser adicionado ao final da coleção. |

**Retorna:**
int - O índice no qual a tab foi adicionada.
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