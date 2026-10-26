---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa o gerenciador que mantém o comportamento dos marcadores de rodapé, data e hora, número de página do slide mestre e de todos os marcadores filhos.
type: docs
url: /pt/com.aspose.slides/imasterslideheaderfootermanager/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Representa o gerenciador que contém o comportamento do marcador de rodapé do slide mestre, marcadores de data e hora, número de página e todos os marcadores filhos. Marcadores filhos significam que os marcadores estão contidos em slides de layout dependentes e em slides dependentes. Slides de layout dependentes e slides utilizam e dependem do slide mestre.
## Métodos

| Método | Descrição |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Altera a visibilidade do marcador de rodapé do slide mestre e de todos os marcadores de rodapé filhos. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Altera a visibilidade do marcador de número de página do slide mestre e de todos os marcadores de número de página filhos. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Altera a visibilidade do marcador de data e hora do slide mestre e de todos os marcadores de data e hora filhos. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Define o texto do marcador de rodapé do slide mestre e de todos os marcadores de rodapé filhos. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Define o texto do marcador de data e hora do slide mestre e de todos os marcadores de data e hora filhos. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Altera a visibilidade do marcador de rodapé do slide mestre e de todos os marcadores de rodapé filhos. Marcadores filhos significam que os marcadores estão contidos em slides de layout dependentes e em slides dependentes. Slides de layout dependentes e slides utilizam e dependem do slide mestre.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os marcadores de rodapé visíveis, caso contrário - os oculta. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Altera a visibilidade do marcador de número de página do slide mestre e de todos os marcadores de número de página filhos. Marcadores filhos significam que os marcadores estão contidos em slides de layout dependentes e em slides dependentes. Slides de layout dependentes e slides utilizam e dependem do slide mestre.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os marcadores de número de página visíveis, caso contrário - os oculta. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Altera a visibilidade do marcador de data e hora do slide mestre e de todos os marcadores de data e hora filhos. Marcadores filhos significam que os marcadores estão contidos em slides de layout dependentes e em slides dependentes. Slides de layout dependentes e slides utilizam e dependem do slide mestre.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os marcadores de data e hora visíveis, caso contrário - os oculta. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Define o texto do marcador de rodapé do slide mestre e de todos os marcadores de rodapé filhos. Marcadores filhos significam que os marcadores estão contidos em slides de layout dependentes e em slides dependentes. Slides de layout dependentes e slides utilizam e dependem do slide mestre.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto a ser definido. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Define o texto do marcador de data e hora do slide mestre e de todos os marcadores de data e hora filhos. Marcadores filhos significam que os marcadores estão contidos em slides de layout dependentes e em slides dependentes. Slides de layout dependentes e slides utilizam e dependem do slide mestre.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto a ser definido. |