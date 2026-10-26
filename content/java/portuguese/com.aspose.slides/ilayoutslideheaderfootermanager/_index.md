---
title: ILayoutSlideHeaderFooterManager
second_title: Referência da API Aspose.Slides para Java
description: Representa o gerenciador que contém o comportamento dos placeholders de rodapé, data e hora, número de página do slide de layout e todos os placeholders filhos.
type: docs
url: /pt/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Representa o gerenciador que contém o comportamento dos placeholders de rodapé do slide de layout, de data e hora, de número de página e de todos os placeholders filhos. Placeholders filhos significam que os placeholders estão contidos em slides dependentes. Slides dependentes usam e dependem do slide de layout.

## Métodos

| Método | Descrição |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Changes layout slide footer placeholder and all child footer placeholders visibility. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Changes layout slide page number placeholder and all child page number placeholders visibility. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Changes layout slide date-time placeholder and all child date-time placeholders visibility. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Sets text to layout slide footer placeholder and all child footer placeholders. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Sets text to layout slide date-time placeholder and all child date-time placeholders. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Altera a visibilidade do placeholder de rodapé do slide de layout e de todos os placeholders de rodapé filhos. Placeholders filhos significam que os placeholders estão contidos em slides dependentes. Slides dependentes usam e dependem do slide mestre.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os placeholders de rodapé visíveis, caso contrário - os oculta. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Altera a visibilidade do placeholder de número de página do slide de layout e de todos os placeholders de número de página filhos. Placeholders filhos significam que os placeholders estão contidos em slides dependentes. Slides dependentes usam e dependem do slide de layout.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os placeholders de número de página visíveis, caso contrário - os oculta. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Altera a visibilidade do placeholder de data e hora do slide de layout e de todos os placeholders de data e hora filhos. Placeholders filhos significam que os placeholders estão contidos em slides dependentes. Slides dependentes usam e dependem do slide de layout.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os placeholders de data e hora visíveis, caso contrário - os oculta. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Define texto no placeholder de rodapé do slide de layout e em todos os placeholders de rodapé filhos. Placeholders filhos significam que os placeholders estão contidos em slides dependentes. Slides dependentes usam e dependem do slide de layout.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto a ser definido. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Define texto no placeholder de data e hora do slide de layout e em todos os placeholders de data e hora filhos. Placeholders filhos significam que os placeholders estão contidos em slides dependentes. Slides dependentes usam e dependem do slide de layout.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto a ser definido. |