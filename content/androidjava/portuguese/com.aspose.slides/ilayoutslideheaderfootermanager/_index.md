---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa o gerenciador que contém o comportamento dos marcadores de posição de rodapé, data/hora e número de página do slide de layout e de todos os marcadores de posição filhos.
type: docs
url: /pt/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Representa o gerenciador que contém o comportamento dos marcadores de posição de rodapé, data/hora e número de página do slide de layout e de todos os marcadores de posição filhos. Marcadores de posição filhos significam que os marcadores de posição estão contidos em slides dependentes. Slides dependentes usam e dependem do slide de layout.
## Métodos

| Método | Descrição |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Altera a visibilidade do marcador de posição de rodapé do slide de layout e de todos os marcadores de posição de rodapé filhos. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Altera a visibilidade do marcador de posição de número de página do slide de layout e de todos os marcadores de posição de número de página filhos. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Altera a visibilidade do marcador de posição de data/hora do slide de layout e de todos os marcadores de posição de data/hora filhos. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Define o texto do marcador de posição de rodapé do slide de layout e de todos os marcadores de posição de rodapé filhos. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Define o texto do marcador de posição de data/hora do slide de layout e de todos os marcadores de posição de data/hora filhos. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Altera a visibilidade do marcador de posição de rodapé do slide de layout e de todos os marcadores de posição de rodapé filhos. Marcadores de posição filhos significam que os marcadores de posição estão contidos em slides dependentes. Slides dependentes usam e dependem do slide mestre.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os marcadores de posição de rodapé visíveis, caso contrário - os oculta. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Altera a visibilidade do marcador de posição de número de página do slide de layout e de todos os marcadores de posição de número de página filhos. Marcadores de posição filhos significam que os marcadores de posição estão contidos em slides dependentes. Slides dependentes usam e dependem do slide de layout.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os marcadores de posição de número de página visíveis, caso contrário - os oculta. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Altera a visibilidade do marcador de posição de data/hora do slide de layout e de todos os marcadores de posição de data/hora filhos. Marcadores de posição filhos significam que os marcadores de posição estão contidos em slides dependentes. Slides dependentes usam e dependem do slide de layout.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os marcadores de posição de data/hora visíveis, caso contrário - os oculta. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Define o texto do marcador de posição de rodapé do slide de layout e de todos os marcadores de posição de rodapé filhos. Marcadores de posição filhos significam que os marcadores de posição estão contidos em slides dependentes. Slides dependentes usam e dependem do slide de layout.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto a ser definido. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Define o texto do marcador de posição de data/hora do slide de layout e de todos os marcadores de posição de data/hora filhos. Marcadores de posição filhos significam que os marcadores de posição estão contidos em slides dependentes. Slides dependentes usam e dependem do slide de layout.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto a ser definido. |