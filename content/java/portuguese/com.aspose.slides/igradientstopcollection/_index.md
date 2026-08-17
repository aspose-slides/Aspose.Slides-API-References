---
title: IGradientStopCollection
second_title: Aspose.Slides para Java Referência da API
description: Representa uma coleção de paradas de gradiente.
type: docs
url: /pt/com.aspose.slides/igradientstopcollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Representa uma coleção de paradas de gradiente.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retorna a parada de gradiente por índice. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | Cria a nova parada de gradiente e a adiciona ao final da coleção. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Cria a nova parada de gradiente e a adiciona ao final da coleção. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Cria a nova parada de gradiente e a adiciona ao final da coleção. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | Cria a nova parada de gradiente e a insere no índice especificado da coleção. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Cria a nova parada de gradiente e a insere no índice especificado da coleção. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Cria a nova parada de gradiente e a insere no índice especificado da coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove uma parada de gradiente no índice especificado. |
| [clear()](#clear--) | Remove todas as paradas de gradiente de uma coleção. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

Retorna a parada de gradiente por índice.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Color color) {#add-float-java.awt.Color-}
```
public abstract IGradientStop add(float position, Color color)
```

Cria a nova parada de gradiente e a adiciona ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| position | float | Posição da nova parada de gradiente. |
| color | java.awt.Color | Cor da nova parada de gradiente. |

**Retorna:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Índice da nova parada de gradiente na coleção.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

Cria a nova parada de gradiente e a adiciona ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| position | float | Posição da nova parada de gradiente. |
| presetColor | int | Cor da nova parada de gradiente. |

**Retorna:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Índice da nova parada de gradiente na coleção.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

Cria a nova parada de gradiente e a adiciona ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| position | float | Posição da nova parada de gradiente. |
| schemeColor | int | Cor da nova parada de gradiente. |

**Retorna:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Índice da nova parada de gradiente na coleção.
### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public abstract void insert(int index, float position, Color color)
```

Cria a nova parada de gradiente e a insere no índice especificado da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice na coleção onde a nova parada de gradiente será inserida. |
| position | float | Posição da nova parada de gradiente. |
| color | java.awt.Color | Cor da nova parada de gradiente. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

Cria a nova parada de gradiente e a insere no índice especificado da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice na coleção onde a nova parada de gradiente será inserida. |
| position | float | Posição da nova parada de gradiente. |
| presetColor | int | Cor da nova parada de gradiente. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

Cria a nova parada de gradiente e a insere no índice especificado da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice na coleção onde a nova parada de gradiente será inserida. |
| position | float | Posição da nova parada de gradiente. |
| schemeColor | int | Cor da nova parada de gradiente. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Remove uma parada de gradiente no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de uma parada de gradiente que deve ser excluída. |

### clear() {#clear--}
```
public abstract void clear()
```

Remove todas as paradas de gradiente de uma coleção.