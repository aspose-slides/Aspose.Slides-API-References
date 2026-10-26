---
title: CustomXmlPartCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa a coleção de partes xml personalizadas.
type: docs
url: /pt/com.aspose.slides/customxmlpartcollection/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

Representa a coleção de partes xml personalizadas.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the element at the specified index. |
| [size()](#size--) | Returns count of custom xml parts in the collection. |
| [add(String xmlString)](#add-java.lang.String-) | Adds new custom xml part. |
| [add(byte[] xmlData)](#add-byte---) | Adds new custom xml part. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Adds new custom xml part. |
| [removeAt(int index)](#removeAt-int-) | Removes custom xml part at the specified index. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Removes the first occurrence of a specific object from the collection. |
| [clear()](#clear--) | Removes all items from the collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copy to specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

Retorna o elemento no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do elemento a ser obtido. |

**Retorna:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - O elemento no índice especificado.
### size() {#size--}
```
public final int size()
```

Retorna a contagem de partes xml personalizadas na coleção. int somente leitura.

**Retorna:**
int
### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

Adiciona uma nova parte xml personalizada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xmlString | java.lang.String | A string xml da nova parte a ser adicionada. |

**Retorna:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Parte xml personalizada criada.
### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

Adiciona uma nova parte xml personalizada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xmlData | byte[] | Os dados xml da nova parte a ser adicionada. |

**Retorna:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Parte xml personalizada criada.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

Adiciona uma nova parte xml personalizada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | java.io.InputStream | O InputStream com os dados xml da nova parte a ser adicionada. |

**Retorna:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Parte xml personalizada criada.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Remove a parte xml personalizada no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do elemento a ser removido. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

Remove a primeira ocorrência de um objeto específico da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | A parte xml personalizada a ser removida. |

**Retorna:**
boolean - true se o item for removido com sucesso; caso contrário, false.
### clear() {#clear--}
```
public final void clear()
```

Remove todos os itens da coleção.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia para o array especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array para o qual copiar. |
| index | int | Índice para iniciar a cópia. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retorna um valor que indica se o acesso à coleção está sincronizado (thread-safe). boolean somente leitura.

**Retorna:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retorna a raiz de sincronização. Object somente leitura.

**Retorna:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

Retorna um enumerador que itera sobre a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Um IGenericEnumerator que pode ser usado para iterar sobre a coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

Retorna um java iterator para a coleção inteira.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Um java.util.Iterator para a coleção inteira.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna o objeto Parent_Immediate. IDOMObject somente leitura.

**Retorna:**
com.aspose.slides.IDOMObject