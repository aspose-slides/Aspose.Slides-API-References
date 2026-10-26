---
title: IMasterSlideHeaderFooterManager
second_title: Referência da API Aspose.Slides para Java
description: Representa o gerenciador que mantém o comportamento dos placeholders de rodapé, data e hora, número de página do slide mestre e de todos os placeholders filhos.
type: docs
url: /pt/com.aspose.slides/imasterslideheaderfootermanager/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Representa o gerenciador que mantém o comportamento do placeholder de rodapé do slide mestre, do placeholder de data e hora, do placeholder de número de página e de todos os placeholders filhos. Placeholders filhos significam que os placeholders estão contidos em slides de layout dependentes e slides dependentes. Slides de layout dependentes e slides usam e dependem do slide mestre.
## Métodos

| Método | Descrição |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Altera a visibilidade do placeholder de rodapé do slide mestre e de todos os placeholders de rodapé filhos. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Altera a visibilidade do placeholder de número de página do slide mestre e de todos os placeholders de número de página filhos. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Altera a visibilidade do placeholder de data e hora do slide mestre e de todos os placeholders de data e hora filhos. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Define o texto no placeholder de rodapé do slide mestre e em todos os placeholders de rodapé filhos. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Define o texto no placeholder de data e hora do slide mestre e em todos os placeholders de data e hora filhos. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Altera a visibilidade do placeholder de rodapé do slide mestre e de todos os placeholders de rodapé filhos. Placeholders filhos significam que os placeholders estão contidos em slides de layout dependentes e slides dependentes. Slides de layout dependentes e slides usam e dependem do slide mestre.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os placeholders de rodapé visíveis, caso contrário - os oculta. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Altera a visibilidade do placeholder de número de página do slide mestre e de todos os placeholders de número de página filhos. Placeholders filhos significam que os placeholders estão contidos em slides de layout dependentes e slides dependentes. Slides de layout dependentes e slides usam e dependem do slide mestre.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os placeholders de número de página visíveis, caso contrário - os oculta. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Altera a visibilidade do placeholder de data e hora do slide mestre e de todos os placeholders de data e hora filhos. Placeholders filhos significam que os placeholders estão contidos em slides de layout dependentes e slides dependentes. Slides de layout dependentes e slides usam e dependem do slide mestre.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os placeholders de data e hora visíveis, caso contrário - os oculta. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Define o texto no placeholder de rodapé do slide mestre e em todos os placeholders de rodapé filhos. Placeholders filhos significam que os placeholders estão contidos em slides de layout dependentes e slides dependentes. Slides de layout dependentes e slides usam e dependem do slide mestre.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto a ser definido. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Define o texto no placeholder de data e hora do slide mestre e em todos os placeholders de data e hora filhos. Placeholders filhos significam que os placeholders estão contidos em slides de layout dependentes e slides dependentes. Slides de layout dependentes e slides usam e dependem do slide mestre.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto a ser definido. |