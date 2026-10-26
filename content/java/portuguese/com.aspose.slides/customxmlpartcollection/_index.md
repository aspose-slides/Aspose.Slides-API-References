---
title: CustomXmlPartCollection
second_title: Referência da API Aspose.Slides para Java
description: Representa uma coleção de partes XML personalizadas.
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

Representa uma coleção de partes XML personalizadas.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retorna o elemento no índice especificado. |
| [size()](#size--) | Retorna a contagem de partes XML personalizadas na coleção. |
| [add(String xmlString)](#add-java.lang.String-) | Adiciona uma nova parte XML personalizada. |
| [add(byte[] xmlData)](#add-byte---) | Adiciona uma nova parte XML personalizada. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Adiciona uma nova parte XML personalizada. |
| [removeAt(int index)](#removeAt-int-) | Remove a parte XML personalizada no índice especificado. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Remove a primeira ocorrência de um objeto específico da coleção. |
| [clear()](#clear--) | Remove todos os itens da coleção. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia para o array especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor indicando se o acesso à coleção está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna uma raiz de sincronização. |
| [iterator()](#iterator--) | Retorna um enumerador que itera pela coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterator java para toda a coleção. |
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

Retorna a contagem de partes XML personalizadas na coleção. Somente leitura int.

**Retorna:**
int

### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

Adiciona uma nova parte XML personalizada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xmlString | java.lang.String | A string XML da nova parte a ser adicionada. |

**Retorna:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Parte XML personalizada criada.

### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

Adiciona uma nova parte XML personalizada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xmlData | byte[] | Os dados XML da nova parte a ser adicionada. |

**Retorna:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Parte XML personalizada criada.

### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

Adiciona uma nova parte XML personalizada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputStream | java.io.InputStream | O InputStream com os dados XML da nova parte a ser adicionada. |

**Retorna:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Parte XML personalizada criada.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Remove a parte XML personalizada no índice especificado.

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
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | A parte XML personalizada a ser removida. |

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

Retorna um valor indicando se o acesso à coleção está sincronizado (thread-safe). Somente leitura boolean.

**Retorna:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retorna uma raiz de sincronização. Somente leitura Object.

**Retorna:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

Retorna um enumerador que itera pela coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Um IGenericEnumerator que pode ser usado para iterar pela coleção.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

Retorna um iterator java para toda a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Um java.util.Iterator para toda a coleção.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject