---
title: CaptionsCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de legendas fechadas.
type: docs
url: /pt/com.aspose.slides/captionscollection/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

Representa uma coleção de legendas fechadas.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retorna as legendas fechadas no índice especificado. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Adiciona legendas fechadas WebVTT ao final da coleção. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Adiciona legendas fechadas WebVTT ao final da coleção a partir de um fluxo. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Remove as legendas fechadas especificadas da coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove as legendas fechadas no índice especificado. |
| [clear()](#clear--) | Remove todas as legendas fechadas da coleção. |
| [getCount()](#getCount--) | Retorna o número de elementos na coleção. |
| [iterator()](#iterator--) | Retorna um enumerador que itera através da coleção. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
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
public final ICaptions add(String label, String filePath)
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
public final ICaptions add(String label, InputStream stream)
```

Adiciona legendas fechadas WebVTT ao final da coleção a partir de um fluxo.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| label | java.lang.String | O rótulo das legendas fechadas. |
| stream | java.io.InputStream | O fluxo de entrada contendo dados no formato WebVTT. |

**Retorna:**
[ICaptions](../../com.aspose.slides/icaptions) - A instância [ICaptions](../../com.aspose.slides/icaptions) adicionada.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```

Remove as legendas fechadas especificadas da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | As legendas fechadas a serem removidas. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Remove as legendas fechadas no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice das legendas fechadas a serem removidas. |

### clear() {#clear--}
```
public final void clear()
```

Remove todas as legendas fechadas da coleção.

### getCount() {#getCount--}
```
public final int getCount()
```

Retorna o número de elementos na coleção. Somente leitura  int .

**Retorna:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```

Retorna um enumerador que itera através da coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - Um  System.Collections.Generic.IEnumerator1  que pode ser usado para iterar através da coleção.