---
title: LayoutSlideHeaderFooterManager
second_title: Referência da API Aspose.Slides para Java
description: Representa o gerenciador que contém o comportamento dos placeholders de rodapé, data/hora, número de página do slide de layout e todos os placeholders filhos.
type: docs
url: /pt/com.aspose.slides/layoutslideheaderfootermanager/
---
**Herança:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
```
public final class LayoutSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements ILayoutSlideHeaderFooterManager
```

Representa o gerenciador que contém o comportamento dos placeholders de rodapé do slide de layout, data/hora, número de página e todos os placeholders filhos. Placeholders filhos significam que os placeholders estão contidos em slides dependentes. Slides dependentes utilizam e dependem do slide de layout.

## Métodos

| Método | Descrição |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Altera a visibilidade do placeholder de rodapé do slide de layout e de todos os placeholders de rodapé filhos. Placeholders filhos significam que os placeholders estão contidos em slides dependentes. Slides dependentes utilizam e dependem do slide mestre. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Altera a visibilidade do placeholder de número de página do slide de layout e de todos os placeholders de número de página filhos. Placeholders filhos significam que os placeholders estão contidos em slides dependentes. Slides dependentes utilizam e dependem do slide de layout. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Altera a visibilidade do placeholder de data/hora do slide de layout e de todos os placeholders de data/hora filhos. Placeholders filhos significam que os placeholders estão contidos em slides dependentes. Slides dependentes utilizam e dependem do slide de layout. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Define o texto no placeholder de rodapé do slide de layout e em todos os placeholders de rodapé filhos. Placeholders filhos significam que os placeholders estão contidos em slides dependentes. Slides dependentes utilizam e dependem do slide de layout. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Define o texto no placeholder de data/hora do slide de layout e em todos os placeholders de data/hora filhos. Placeholders filhos significam que os placeholders estão contidos em slides dependentes. Slides dependentes utilizam e dependem do slide de layout. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Altera a visibilidade do placeholder de rodapé do slide de layout e de todos os placeholders de rodapé filhos. Placeholders filhos significam que os placeholders estão contidos em slides dependentes. Slides dependentes utilizam e dependem do slide mestre.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os placeholders de rodapé visíveis, caso contrário - os oculta. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Altera a visibilidade do placeholder de número de página do slide de layout e de todos os placeholders de número de página filhos. Placeholders filhos significam que os placeholders estão contidos em slides dependentes. Slides dependentes utilizam e dependem do slide de layout.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os placeholders de número de página visíveis, caso contrário - os oculta. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Altera a visibilidade do placeholder de data/hora do slide de layout e de todos os placeholders de data/hora filhos. Placeholders filhos significam que os placeholders estão contidos em slides dependentes. Slides dependentes utilizam e dependem do slide de layout.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os placeholders de data/hora visíveis, caso contrário - os oculta. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Define o texto no placeholder de rodapé do slide de layout e em todos os placeholders de rodapé filhos. Placeholders filhos significam que os placeholders estão contidos em slides dependentes. Slides dependentes utilizam e dependem do slide de layout.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto a ser definido. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Define o texto no placeholder de data/hora do slide de layout e em todos os placeholders de data/hora filhos. Placeholders filhos significam que os placeholders estão contidos em slides dependentes. Slides dependentes utilizam e dependem do slide de layout.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto a ser definido. |