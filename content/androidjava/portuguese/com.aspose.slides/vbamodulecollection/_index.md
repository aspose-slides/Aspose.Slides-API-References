---
title: VbaModuleCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de módulos de um Projeto VBA.
type: docs
url: /pt/com.aspose.slides/vbamodulecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
```
public final class VbaModuleCollection implements IVbaModuleCollection
```

Representa uma coleção de módulos de um Projeto VBA.
## Métodos

| Método | Descrição |
| --- | --- |
| [size()](#size--) | Obtém o número de elementos realmente contidos na coleção. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Remove a primeira ocorrência de um objeto específico da coleção. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Adiciona um novo módulo vazio ao Projeto VBA. |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [iterator()](#iterator--) | Retorna um enumerador que itera sobre a coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para toda a coleção. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos os elementos da coleção para o array especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor indicando se o acesso à coleção é sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna uma raiz de sincronização. |
### size() {#size--}
```
public final int size()
```


Obtém o número de elementos realmente contidos na coleção. Somente leitura int.

**Retorna:**
int
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public final void remove(IVbaModule value)
```


Remove a primeira ocorrência de um objeto específico da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | O módulo a ser removido da coleção. |

### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public final IVbaModule addEmptyModule(String name)
```


Adiciona um novo módulo vazio ao Projeto VBA.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome do módulo |

**Retorna:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Módulo adicionado.
### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```


Obtém o elemento no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```


Retorna um enumerador que itera sobre a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - Um IGenericEnumerator que pode ser usado para iterar sobre a coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```


Retorna um iterador java para toda a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - Um java.util.Iterator para toda a coleção.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia todos os elementos da coleção para o array especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino. |
| index | int | Índice inicial no array de destino. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Retorna um valor indicando se o acesso à coleção é sincronizado (thread-safe). Somente leitura boolean.

**Retorna:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Retorna uma raiz de sincronização. Somente leitura Object.

**Retorna:**
java.lang.Object