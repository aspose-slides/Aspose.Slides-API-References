---
title: ITagCollection
second_title: Referência da API Aspose.Slides para Java
description: Representa a coleção de etiquetas de pares de strings definidos pelo usuário
type: docs
url: /pt/com.aspose.slides/itagcollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

Representa a coleção de etiquetas (pares de strings definidos pelo usuário)
## Métodos

| Método | Descrição |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Adiciona uma nova etiqueta à coleção. |
| [remove(String name)](#remove-java.lang.String-) | Remove a etiqueta com um nome especificado da coleção. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Retorna o índice baseado em zero da chave especificada na coleção. |
| [contains(String name)](#contains-java.lang.String-) | Determina se a coleção contém um nome específico. |
| [removeAt(int index)](#removeAt-int-) | Remove a etiqueta no índice especificado. |
| [clear()](#clear--) | Remove todas as etiquetas da coleção. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Retorna o valor de uma etiqueta no índice especificado. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Retorna a chave de uma etiqueta no índice especificado. |
| [getNamesOfTags()](#getNamesOfTags--) | Retorna os nomes das etiquetas. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Retorna ou define um par de chave e valor de uma etiqueta. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Retorna ou define um par de chave e valor de uma etiqueta. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```

Adiciona uma nova etiqueta à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | O nome da etiqueta. |
| value | java.lang.String | O valor da etiqueta. |

**Retorna:**
int - O índice da etiqueta adicionada.
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

Remove a etiqueta com um nome especificado da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | O nome da etiqueta a remover. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
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
public abstract boolean contains(String name)
```

Determina se a coleção contém um nome específico.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | A chave a localizar. |

**Retorna:**
boolean - True se a coleção contém uma etiqueta com a chave especificada; caso contrário, false.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Remove a etiqueta no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero da etiqueta a remover. |
### clear() {#clear--}
```
public abstract void clear()
```

Remove todas as etiquetas da coleção.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```

Retorna o valor de uma etiqueta no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de uma etiqueta para retornar. |

**Retorna:**
java.lang.String - Valor de uma etiqueta.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```

Retorna a chave de uma etiqueta no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de uma etiqueta para retornar. |

**Retorna:**
java.lang.String - Chave de uma etiqueta.
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```

Retorna os nomes das etiquetas.

**Retorna:**
java.lang.String[] - Nomes das etiquetas.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

Retorna ou define um par de chave e valor de uma etiqueta.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Chave de uma etiqueta. |

**Retorna:**
java.lang.String - Valor de uma etiqueta.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

Retorna ou define um par de chave e valor de uma etiqueta.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Chave de uma etiqueta. |
| value | java.lang.String |  |