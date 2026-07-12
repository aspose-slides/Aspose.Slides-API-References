---
title: IGradientStopCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de pontos de gradiente.
type: docs
url: /pt/com.aspose.slides/igradientstopcollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Representa uma coleção de pontos de gradiente.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retorna o ponto de gradiente pelo índice. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Cria o novo ponto de gradiente e o adiciona ao final da coleção. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Cria o novo ponto de gradiente e o adiciona ao final da coleção. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Cria o novo ponto de gradiente e o adiciona ao final da coleção. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Cria o novo ponto de gradiente e o insere no índice especificado da coleção. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Cria o novo ponto de gradiente e o insere no índice especificado da coleção. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Cria o novo ponto de gradiente e o insere no índice especificado da coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove um ponto de gradiente no índice especificado. |
| [clear()](#clear--) | Remove todos os pontos de gradiente de uma coleção. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
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
public abstract IGradientStop add(float position, Integer color)
```

Cria o novo ponto de gradiente e o adiciona ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| position | float | Posição do novo ponto de gradiente. |
| color | java.lang.Integer | Cor do novo ponto de gradiente. |

**Retorna:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Índice do novo ponto de gradiente na coleção.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

Cria o novo ponto de gradiente e o adiciona ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| position | float | Posição do novo ponto de gradiente. |
| presetColor | int | Cor do novo ponto de gradiente. |

**Retorna:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Índice do novo ponto de gradiente na coleção.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

Cria o novo ponto de gradiente e o adiciona ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| position | float | Posição do novo ponto de gradiente. |
| schemeColor | int | Cor do novo ponto de gradiente. |

**Retorna:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Índice do novo ponto de gradiente na coleção.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public abstract void insert(int index, float position, Integer color)
```

Cria o novo ponto de gradiente e o insere no índice especificado da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice na coleção onde o novo ponto de gradiente será inserido. |
| position | float | Posição do novo ponto de gradiente. |
| color | java.lang.Integer | Cor do novo ponto de gradiente. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

Cria o novo ponto de gradiente e o insere no índice especificado da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice na coleção onde o novo ponto de gradiente será inserido. |
| position | float | Posição do novo ponto de gradiente. |
| presetColor | int | Cor do novo ponto de gradiente. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

Cria o novo ponto de gradiente e o insere no índice especificado da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice na coleção onde o novo ponto de gradiente será inserido. |
| position | float | Posição do novo ponto de gradiente. |
| schemeColor | int | Cor do novo ponto de gradiente. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Remove um ponto de gradiente no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de um ponto de gradiente que deve ser excluído. |

### clear() {#clear--}
```
public abstract void clear()
```

Remove todos os pontos de gradiente de uma coleção.