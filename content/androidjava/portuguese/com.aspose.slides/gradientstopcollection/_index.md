---
title: GradientStopCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de pontos de gradiente.
type: docs
url: /pt/com.aspose.slides/gradientstopcollection/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

Representa uma coleção de pontos de gradiente.
## Métodos

| Método | Descrição |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | Retorna o número de pontos de gradiente em uma coleção. |
| [get_Item(int index)](#get-Item-int-) | Retorna o ponto de gradiente pelo índice. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Cria um novo ponto de gradiente e o adiciona ao final da coleção. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Cria um novo ponto de gradiente e o adiciona ao final da coleção. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Cria um novo ponto de gradiente e o adiciona ao final da coleção. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Cria um novo ponto de gradiente e o insere no índice especificado da coleção. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Cria um novo ponto de gradiente e o insere no índice especificado da coleção. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Cria um novo ponto de gradiente e o insere no índice especificado da coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove um ponto de gradiente no índice especificado. |
| [clear()](#clear--) | Remove todos os pontos de gradiente de uma coleção. |
| [iterator()](#iterator--) | Retorna um enumerador que itera através da coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para a coleção inteira. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos os elementos da coleção para a matriz especificada. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor que indica se o acesso à coleção é sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna uma raiz de sincronização. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versão. Somente leitura long.

**Retorna:**
long
### size() {#size--}
```
public final int size()
```


Retorna o número de pontos de gradiente em uma coleção. Somente leitura int.

**Retorna:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```


Retorna o ponto de gradiente pelo índice.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public final IGradientStop add(float position, Integer color)
```


Cria um novo ponto de gradiente e o adiciona ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| position | float | Posição do novo ponto de gradiente. |
| color | java.lang.Integer | Cor do novo ponto de gradiente. |

**Retorna:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Índice do novo ponto de gradiente na coleção.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```


Cria um novo ponto de gradiente e o adiciona ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| position | float | Posição do novo ponto de gradiente. |
| presetColor | int | Cor do novo ponto de gradiente. |

**Retorna:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Índice do novo ponto de gradiente na coleção.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```


Cria um novo ponto de gradiente e o adiciona ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| position | float | Posição do novo ponto de gradiente. |
| schemeColor | int | Cor do novo ponto de gradiente. |

**Retorna:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Índice do novo ponto de gradiente na coleção.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public final void insert(int index, float position, Integer color)
```


Cria um novo ponto de gradiente e o insere no índice especificado da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice na coleção onde o novo ponto de gradiente será inserido. |
| position | float | Posição do novo ponto de gradiente. |
| color | java.lang.Integer | Cor do novo ponto de gradiente. |
### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```


Cria um novo ponto de gradiente e o insere no índice especificado da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice na coleção onde o novo ponto de gradiente será inserido. |
| position | float | Posição do novo ponto de gradiente. |
| presetColor | int | Cor do novo ponto de gradiente. |
### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```


Cria um novo ponto de gradiente e o insere no índice especificado da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice na coleção onde o novo ponto de gradiente será inserido. |
| position | float | Posição do novo ponto de gradiente. |
| schemeColor | int | Cor do novo ponto de gradiente. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Remove um ponto de gradiente no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de um ponto de gradiente que deve ser excluído. |
### clear() {#clear--}
```
public final void clear()
```


Remove todos os pontos de gradiente de uma coleção.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```


Retorna um enumerador que itera através da coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Um IGenericEnumerator que pode ser usado para iterar através da coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```


Retorna um iterador java para a coleção inteira.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Um java.util.Iterator para a coleção inteira.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia todos os elementos da coleção para a matriz especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Matriz de destino. |
| index | int | Índice inicial na matriz de destino. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Retorna um valor que indica se o acesso à coleção é sincronizado (thread-safe). Somente leitura boolean.

**Retorna:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Retorna uma raiz de sincronização. Somente leitura Object.

**Retorna:**
java.lang.Object