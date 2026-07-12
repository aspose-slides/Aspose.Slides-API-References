---
title: INormalViewProperties
second_title: Aspose.Slides para Android via Java API Reference
description: Representa as propriedades da visualização normal.
type: docs
url: /pt/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

Representa as propriedades da visualização normal. A visualização normal consiste em três regiões de conteúdo: o slide em si, uma região de conteúdo lateral e uma região de conteúdo inferior.
## Métodos

| Método | Descrição |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Especifica se o aplicativo deve mostrar ícones ao exibir conteúdo de esquema em qualquer das regiões de conteúdo do modo de visualização normal. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Especifica se o aplicativo deve mostrar ícones ao exibir conteúdo de esquema em qualquer das regiões de conteúdo do modo de visualização normal. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Especifica se o divisor vertical deve travar em um estado minimizado quando a região lateral for suficientemente pequena. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Especifica se o divisor vertical deve travar em um estado minimizado quando a região lateral for suficientemente pequena. |
| [getVerticalBarState()](#getVerticalBarState--) | Especifica o estado em que a barra do divisor vertical deve ser exibida. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Especifica o estado em que a barra do divisor vertical deve ser exibida. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Especifica o estado em que a barra do divisor horizontal deve ser exibida. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Especifica o estado em que a barra do divisor horizontal deve ser exibida. |
| [getPreferSingleView()](#getPreferSingleView--) | Especifica se o usuário prefere ver uma única região de conteúdo em tela cheia em vez da visualização normal padrão com três regiões de conteúdo. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Especifica se o usuário prefere ver uma única região de conteúdo em tela cheia em vez da visualização normal padrão com três regiões de conteúdo. |
| [getRestoredLeft()](#getRestoredLeft--) | Este elemento especifica o dimensionamento da região de conteúdo lateral da visualização normal, quando a região está em um tamanho restaurado variável (nem minimizado nem maximizado). |
| [getRestoredTop()](#getRestoredTop--) | Este elemento especifica o dimensionamento da região superior do slide da visualização normal, quando a região está em um tamanho restaurado variável (nem minimizado nem maximizado). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

Especifica se o aplicativo deve mostrar ícones ao exibir conteúdo de esquema em qualquer das regiões de conteúdo do modo de visualização normal. Leitura/gravação boolean.

**Retorna:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

Especifica se o aplicativo deve mostrar ícones ao exibir conteúdo de esquema em qualquer das regiões de conteúdo do modo de visualização normal. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

Especifica se o divisor vertical deve travar em um estado minimizado quando a região lateral for suficientemente pequena. Leitura/gravação boolean.

**Retorna:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

Especifica se o divisor vertical deve travar em um estado minimizado quando a região lateral for suficientemente pequena. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

Especifica o estado em que a barra do divisor vertical deve ser exibida. Uma barra do divisor vertical separa o slide da região de conteúdo lateral.

**Retorna:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

Especifica o estado em que a barra do divisor vertical deve ser exibida. Uma barra do divisor vertical separa o slide da região de conteúdo lateral.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

Especifica o estado em que a barra do divisor horizontal deve ser exibida. Uma barra do divisor horizontal separa o slide da região de conteúdo abaixo do slide.

**Retorna:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

Especifica o estado em que a barra do divisor horizontal deve ser exibida. Uma barra do divisor horizontal separa o slide da região de conteúdo abaixo do slide.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

Especifica se o usuário prefere ver uma única região de conteúdo em tela cheia em vez da visualização normal padrão com três regiões de conteúdo. Se ativado, o aplicativo pode escolher exibir uma das regiões de conteúdo em toda a janela. Leitura/gravação boolean.

**Retorna:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

Especifica se o usuário prefere ver uma única região de conteúdo em tela cheia em vez da visualização normal padrão com três regiões de conteúdo. Se ativado, o aplicativo pode escolher exibir uma das regiões de conteúdo em toda a janela. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

Este elemento especifica o dimensionamento da região de conteúdo lateral da visualização normal, quando a região está em um tamanho restaurado variável (nem minimizado nem maximizado). Somente leitura [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Retorna:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

Este elemento especifica o dimensionamento da região superior do slide da visualização normal, quando a região está em um tamanho restaurado variável (nem minimizado nem maximizado). Somente leitura [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Retorna:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)