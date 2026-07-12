---
title: ICustomXmlPartCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa a coleção de partes xml personalizadas.
type: docs
url: /pt/com.aspose.slides/icustomxmlpartcollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

Representa a coleção de partes xml personalizadas.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retorna o elemento no índice especificado. |
| [add(byte[] xmlData)](#add-byte---) | Adiciona uma nova parte xml personalizada. |
| [add(String xmlString)](#add-java.lang.String-) | Adiciona uma nova parte xml personalizada. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Adiciona uma nova parte xml personalizada. |
| [removeAt(int index)](#removeAt-int-) | Remove a parte xml personalizada no índice especificado. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Remove a primeira ocorrência de um objeto específico da coleção. |
| [clear()](#clear--) | Remove todos os itens da coleção. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```

Retorna o elemento no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do elemento a ser obtido. |

**Retorna:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - O elemento no índice especificado.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```

Adiciona uma nova parte xml personalizada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xmlData | byte[] | Os dados xml da nova parte a ser adicionada. |

**Retorna:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Parte xml personalizada criada.
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```

Adiciona uma nova parte xml personalizada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xmlString | java.lang.String | A string xml da nova parte a ser adicionada. |

**Retorna:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Parte xml personalizada criada.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
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
public abstract void removeAt(int index)
```

Remove a parte xml personalizada no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do elemento a ser removido. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
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
public abstract void clear()
```

Remove todos os itens da coleção.