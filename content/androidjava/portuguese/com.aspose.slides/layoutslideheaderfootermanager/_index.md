---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides para Android via Referência de API Java
description: Representa o gerenciador que mantém o comportamento dos marcadores de rodapé, data/hora e número de página do slide de layout e de todos os marcadores filhos.
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

Representa o gerenciador que contém o comportamento dos marcadores de rodapé de slide de layout, data/hora e número de página, além de todos os marcadores filhos. Marcadores filhos significam que os marcadores estão contidos em slides dependentes. Slides dependentes usam e dependem do slide de layout.

## Métodos

| Método | Descrição |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Altera a visibilidade do marcador de rodapé do slide de layout e de todos os marcadores de rodapé filhos. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Altera a visibilidade do marcador de número de página do slide de layout e de todos os marcadores de número de página filhos. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Altera a visibilidade do marcador de data/hora do slide de layout e de todos os marcadores de data/hora filhos. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Define o texto no marcador de rodapé do slide de layout e em todos os marcadores de rodapé filhos. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Define o texto no marcador de data/hora do slide de layout e em todos os marcadores de data/hora filhos. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Altera a visibilidade do marcador de rodapé do slide de layout e de todos os marcadores de rodapé filhos. Marcadores filhos significam que os marcadores estão contidos em slides dependentes. Slides dependentes usam e dependem do slide mestre.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os marcadores de rodapé visíveis, caso contrário - os oculta. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Altera a visibilidade do marcador de número de página do slide de layout e de todos os marcadores de número de página filhos. Marcadores filhos significam que os marcadores estão contidos em slides dependentes. Slides dependentes usam e dependem do slide de layout.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os marcadores de número de página visíveis, caso contrário - os oculta. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Altera a visibilidade do marcador de data/hora do slide de layout e de todos os marcadores de data/hora filhos. Marcadores filhos significam que os marcadores estão contidos em slides dependentes. Slides dependentes usam e dependem do slide de layout.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna os marcadores de data/hora visíveis, caso contrário - os oculta. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Define o texto no marcador de rodapé do slide de layout e em todos os marcadores de rodapé filhos. Marcadores filhos significam que os marcadores estão contidos em slides dependentes. Slides dependentes usam e dependem do slide de layout.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto a ser definido. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Define o texto no marcador de data/hora do slide de layout e em todos os marcadores de data/hora filhos. Marcadores filhos significam que os marcadores estão contidos em slides dependentes. Slides dependentes usam e dependem do slide de layout.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto a ser definido. |