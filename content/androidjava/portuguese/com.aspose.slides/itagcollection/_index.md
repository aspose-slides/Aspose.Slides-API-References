---
title: ITagCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa a coleção de tags, pares de strings definidos pelo usuário
type: docs
url: /pt/com.aspose.slides/itagcollection/
---
**Todas as interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

Representa a coleção de tags (pares de strings definidos pelo usuário)
## Métodos

| Method | Description |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Adiciona uma nova tag à coleção. |
| [remove(String name)](#remove-java.lang.String-) | Remove a tag com um nome especificado da coleção. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Retorna o índice baseado em zero da chave especificada na coleção. |
| [contains(String name)](#contains-java.lang.String-) | Determina se a coleção contém um nome específico. |
| [removeAt(int index)](#removeAt-int-) | Remove a tag no índice especificado. |
| [clear()](#clear--) | Remove todas as tags da coleção. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Retorna o valor de uma tag no índice especificado. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Retorna a chave de uma tag no índice especificado. |
| [getNamesOfTags()](#getNamesOfTags--) | Retorna os nomes das tags. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Retorna ou define um par chave-valor de uma tag. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Retorna ou define um par chave-valor de uma tag. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```

Adiciona uma nova tag à coleção.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | O nome da tag. |
| value | java.lang.String | O valor da tag. |

**Retorna:**
int - O índice da tag adicionada.
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

Remove a tag com um nome especificado da coleção.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | O nome da tag a ser removida. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```

Retorna o índice baseado em zero da chave especificada na coleção.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | O nome a ser localizado na coleção. |

**Retorna:**
int - O índice baseado em zero da chave, se a chave for encontrada na coleção; caso contrário, -1.
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```

Determina se a coleção contém um nome específico.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | A chave a ser localizada. |

**Retorna:**
boolean - true se a coleção contém uma tag com a chave especificada; caso contrário, false.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Remove a tag no índice especificado.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | O índice baseado em zero da tag a ser removida. |
### clear() {#clear--}
```
public abstract void clear()
```

Remove todas as tags da coleção.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```

Retorna o valor de uma tag no índice especificado.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Índice de uma tag a ser retornado. |

**Retorna:**
java.lang.String - Valor de uma tag.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```

Retorna a chave de uma tag no índice especificado.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Índice de uma tag a ser retornado. |

**Retorna:**
java.lang.String - Chave de uma tag.
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```

Retorna os nomes das tags.

**Retorna:**
java.lang.String[] - Nomes das tags.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

Retorna ou define um par chave-valor de uma tag.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Chave de uma tag. |

**Retorna:**
java.lang.String - Valor de uma tag.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

Retorna ou define um par chave-valor de uma tag.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Chave de uma tag. |
| value | java.lang.String |  |