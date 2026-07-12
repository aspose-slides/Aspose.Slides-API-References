---
title: TagCollection
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa a coleção de tags, pares de strings definidos pelo usuário
type: docs
url: /pt/com.aspose.slides/tagcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)
```
public final class TagCollection implements ITagCollection
```

Representa a coleção de tags (pares de strings definidos pelo usuário)

--------------------

> ```
> The following example shows how to add a tag to a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ITagCollection tags = pres.getCustomData().getTags();
>      pres.getCustomData().getTags().add("MyTag", "My Tag Value");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Métodos

| Method | Description |
| --- | --- |
| [size()](#size--) | Retorna o número de tags na coleção. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Adiciona uma nova tag à coleção. |
| [remove(String name)](#remove-java.lang.String-) | Remove a tag com um nome especificado da coleção. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Retorna o índice baseado em zero da chave especificada na coleção. |
| [contains(String name)](#contains-java.lang.String-) | Determina se a coleção contém um nome específico. |
| [removeAt(int index)](#removeAt-int-) | Remove a tag no índice especificado. |
| [clear()](#clear--) | Remove todas as tags da coleção. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Retorna o valor de uma tag no índice especificado. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Retorna a chave de uma tag no índice especificado. |
| [getNamesOfTags()](#getNamesOfTags--) | Retorna os nomes das tags. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Retorna ou define um par chave e valor de uma tag. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Retorna ou define um par chave e valor de uma tag. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos os elementos da coleção para o array especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor indicando se o acesso à coleção é sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna uma raiz de sincronização. |
| [iterator()](#iterator--) | Retorna um enumerador que itera pela coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterator java para toda a coleção. |
### size() {#size--}
```
public final int size()
```


Retorna o número de tags na coleção. int somente leitura.

**Retorna:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```


Adiciona uma nova tag à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | O nome da tag. |
| value | java.lang.String | O valor da tag. |

**Retorna:**
int - O índice da tag adicionada.
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```


Remove a tag com um nome especificado da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | O nome da tag a remover. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```


Retorna o índice baseado em zero da chave especificada na coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | O nome a localizar na coleção. |

**Retorna:**
int - O índice baseado em zero da chave, se a chave for encontrada na coleção; caso contrário, -1.
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```


Determina se a coleção contém um nome específico.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | A chave a localizar. |

**Retorna:**
boolean - Verdadeiro se a coleção contém uma tag com a chave especificada; caso contrário, falso.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Remove a tag no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero da tag a remover. |
### clear() {#clear--}
```
public final void clear()
```


Remove todas as tags da coleção.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```


Retorna o valor de uma tag no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice da tag a retornar. |

**Retorna:**
java.lang.String - Valor de uma tag.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```


Retorna a chave de uma tag no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice da tag a retornar. |

**Retorna:**
java.lang.String - Chave de uma tag.
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```


Retorna os nomes das tags.

**Retorna:**
java.lang.String[] - Nomes das tags.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```


Retorna ou define um par chave e valor de uma tag.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Chave de uma tag. |

**Retorna:**
java.lang.String - Valor de uma tag.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```


Retorna ou define um par chave e valor de uma tag.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Chave de uma tag. |
| value | java.lang.String |  |
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia todos os elementos da coleção para o array especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array a ser preenchido. |
| index | int | Posição inicial no array de destino. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Retorna um valor indicando se o acesso à coleção é sincronizado (thread-safe). boolean somente leitura.

**Retorna:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Retorna uma raiz de sincronização. Object somente leitura.

**Retorna:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```


Retorna um enumerador que itera pela coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```


Retorna um iterator java para toda a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.