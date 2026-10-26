---
title: NormalViewProperties
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa as propriedades da visualização normal.
type: docs
url: /pt/com.aspose.slides/normalviewproperties/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
```
public class NormalViewProperties implements INormalViewProperties
```

Representa as propriedades da visualização normal. A visualização normal consiste em três regiões de conteúdo: o próprio slide, uma região de conteúdo lateral e uma região de conteúdo inferior.

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //Instanciar um objeto de apresentação que representa um arquivo de apresentação
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      pres.getViewProperties().getNormalViewProperties().setHorizontalBarState(SplitterBarStateType.Restored);
>      pres.getViewProperties().getNormalViewProperties().setVerticalBarState(SplitterBarStateType.Maximized);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setAutoAdjust(true);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setDimensionSize(80);
>      pres.getViewProperties().getNormalViewProperties().setShowOutlineIcons(true);
>      pres.save("presentation_normal_view_state.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Métodos

| Método | Descrição |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Especifica se o aplicativo deve exibir ícones ao exibir conteúdo de contorno em qualquer das regiões de conteúdo do modo de visualização normal. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Especifica se o aplicativo deve exibir ícones ao exibir conteúdo de contorno em qualquer das regiões de conteúdo do modo de visualização normal. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Especifica se o divisor vertical deve encaixar em um estado minimizado quando a região lateral é suficientemente pequena. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Especifica se o divisor vertical deve encaixar em um estado minimizado quando a região lateral é suficientemente pequena. |
| [getVerticalBarState()](#getVerticalBarState--) | Especifica o estado em que a barra do divisor vertical deve ser exibida. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Especifica o estado em que a barra do divisor vertical deve ser exibida. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Especifica o estado em que a barra do divisor horizontal deve ser exibida. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Especifica o estado em que a barra do divisor horizontal deve ser exibida. |
| [getPreferSingleView()](#getPreferSingleView--) | Especifica se o usuário prefere ver uma região de conteúdo único em tela cheia em vez da visualização normal padrão com três regiões de conteúdo. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Especifica se o usuário prefere ver uma região de conteúdo único em tela cheia em vez da visualização normal padrão com três regiões de conteúdo. |
| [getRestoredLeft()](#getRestoredLeft--) | Este elemento especifica o dimensionamento da região de conteúdo lateral da visualização normal, quando a região tem um tamanho restaurado variável (nem minimizado nem maximizado). |
| [getRestoredTop()](#getRestoredTop--) | Este elemento especifica o dimensionamento da região superior do slide da visualização normal, quando a região tem um tamanho restaurado variável (nem minimizado nem maximizado). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

Especifica se o aplicativo deve exibir ícones ao exibir conteúdo de contorno em qualquer das regiões de conteúdo do modo de visualização normal. Leitura/gravação booleano.

**Retorna:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

Especifica se o aplicativo deve exibir ícones ao exibir conteúdo de contorno em qualquer das regiões de conteúdo do modo de visualização normal. Leitura/gravação booleano.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

Especifica se o divisor vertical deve encaixar em um estado minimizado quando a região lateral é suficientemente pequena. Leitura/gravação booleano.

**Retorna:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

Especifica se o divisor vertical deve encaixar em um estado minimizado quando a região lateral é suficientemente pequena. Leitura/gravação booleano.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

Especifica o estado em que a barra do divisor vertical deve ser exibida. Uma barra do divisor vertical separa o slide da região de conteúdo lateral.

**Retorna:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

Especifica o estado em que a barra do divisor vertical deve ser exibida. Uma barra do divisor vertical separa o slide da região de conteúdo lateral.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

Especifica o estado em que a barra do divisor horizontal deve ser exibida. Uma barra do divisor horizontal separa o slide da região de conteúdo abaixo do slide.

**Retorna:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

Especifica o estado em que a barra do divisor horizontal deve ser exibida. Uma barra do divisor horizontal separa o slide da região de conteúdo abaixo do slide.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

Especifica se o usuário prefere ver uma região de conteúdo único em tela cheia em vez da visualização normal padrão com três regiões de conteúdo. Se habilitado, o aplicativo pode escolher exibir uma das regiões de conteúdo em toda a janela. Leitura/gravação booleano.

**Retorna:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

Especifica se o usuário prefere ver uma região de conteúdo único em tela cheia em vez da visualização normal padrão com três regiões de conteúdo. Se habilitado, o aplicativo pode escolher exibir uma das regiões de conteúdo em toda a janela. Leitura/gravação booleano.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

Este elemento especifica o dimensionamento da região de conteúdo lateral da visualização normal, quando a região tem um tamanho restaurado variável (nem minimizado nem maximizado). Somente leitura [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Retorna:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

Este elemento especifica o dimensionamento da região superior do slide da visualização normal, quando a região tem um tamanho restaurado variável (nem minimizado nem maximizado). Somente leitura [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Retorna:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)