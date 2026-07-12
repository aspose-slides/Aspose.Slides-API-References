---
title: ICaptionsCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção das legendas fechadas.
type: docs
url: /pt/com.aspose.slides/icaptionscollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

Representa uma coleção das legendas fechadas.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retorna as legendas fechadas no índice especificado. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Adiciona legendas fechadas WebVTT ao final da coleção. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Adiciona legendas fechadas WebVTT ao final da coleção a partir de um stream. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Remove as legendas fechadas especificadas da coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove as legendas fechadas no índice especificado. |
| [clear()](#clear--) | Remove todas as legendas fechadas da coleção. |
| [getCount()](#getCount--) | Retorna o número de elementos na coleção. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```


Retorna as legendas fechadas no índice especificado. Somente leitura [ICaptions](../../com.aspose.slides/icaptions).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public abstract ICaptions add(String label, String filePath)
```


Adiciona legendas fechadas WebVTT ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| label | java.lang.String | O rótulo das legendas fechadas. |
| filePath | java.lang.String | O caminho para o arquivo WebVTT. |

**Retorna:**
[ICaptions](../../com.aspose.slides/icaptions) - A instância [ICaptions](../../com.aspose.slides/icaptions) adicionada.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```


Adiciona legendas fechadas WebVTT ao final da coleção a partir de um stream.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| label | java.lang.String | O rótulo das legendas fechadas. |
| stream | java.io.InputStream | O stream de entrada contendo dados em formato WebVTT. |

**Retorna:**
[ICaptions](../../com.aspose.slides/icaptions) - A instância [ICaptions](../../com.aspose.slides/icaptions) adicionada.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```


Remove as legendas fechadas especificadas da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | As legendas fechadas a serem removidas. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Remove as legendas fechadas no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice das legendas fechadas a remover. |

### clear() {#clear--}
```
public abstract void clear()
```


Remove todas as legendas fechadas da coleção.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Retorna o número de elementos na coleção. Somente leitura  int .

**Retorna:**
int