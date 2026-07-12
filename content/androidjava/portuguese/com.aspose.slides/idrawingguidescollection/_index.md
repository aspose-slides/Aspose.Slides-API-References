---
title: IDrawingGuidesCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção dos guias de desenho ajustáveis.
type: docs
url: /pt/com.aspose.slides/idrawingguidescollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

Representa uma coleção dos guias de desenho ajustáveis.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retorna o guia de desenho por índice. |
| [add(byte orientation, float position)](#add-byte-float-) | Adiciona o guia de desenho ao final da coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove o guia de desenho no índice especificado. |
| [clear()](#clear--) | Remove todos os elementos da coleção. |
| [getCount()](#getCount--) | Obtém o número de todos os elementos na coleção. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```


Retorna o guia de desenho por índice. Somente leitura [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```


Adiciona o guia de desenho ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| orientation | byte | Orientação do guia de desenho. |
| position | float | Posição do guia de desenho em pontos. |

**Retorna:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Remove o guia de desenho no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do guia de desenho que deve ser excluído. |

### clear() {#clear--}
```
public abstract void clear()
```


Remove todos os elementos da coleção.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Obtém o número de todos os elementos na coleção. Somente leitura int.

**Retorna:**
int