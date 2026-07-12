---
title: ITrendlineCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de TrendlineEx
type: docs
url: /pt/com.aspose.slides/itrendlinecollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

Representa uma coleção de TrendlineEx
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [getCount()](#getCount--) | Obtém o número de elementos realmente contidos na coleção. |
| [add(int trendlineType)](#add-int-) | Adiciona o novo Trendline ao final de uma coleção e o retorna. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Remove o valor especificado. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```

Obtém o elemento no índice especificado. Somente leitura [ITrendline](../../com.aspose.slides/itrendline).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Obtém o número de elementos realmente contidos na coleção. Somente leitura int.

**Retorna:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```

Adiciona o novo Trendline ao final de uma coleção e o retorna.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| trendlineType | int | Tipo de Trendline [TrendlineType](../../com.aspose.slides/trendlinetype) |

**Retorna:**
[ITrendline](../../com.aspose.slides/itrendline) - Novo Trendline [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```

Remove o valor especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | Trendline a remover [ITrendline](../../com.aspose.slides/itrendline) |