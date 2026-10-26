---
title: IBaseSlideHeaderFooterManager
second_title: Referência da API Aspose.Slides para Java
description: Representa o gerenciador que contém o comportamento dos placeholders de rodapé, data e hora e número de página para todos os tipos de slide.
type: docs
url: /pt/com.aspose.slides/ibaseslideheaderfootermanager/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

Representa o gerenciador que contém o comportamento dos placeholders de rodapé, data e hora, número de página para todos os tipos de slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | Obtém valor indicando que um placeholder de rodapé está presente. |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | Obtém valor indicando que um placeholder de número de página está presente. |
| [isDateTimeVisible()](#isDateTimeVisible--) | Obtém valor indicando que um placeholder de data e hora está presente. |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | Altera a visibilidade do placeholder de rodapé do slide. |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | Altera a visibilidade do placeholder de número de página do slide. |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | Altera a visibilidade do placeholder de data e hora do slide. |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | Define o texto no placeholder de rodapé do slide. |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | Define o texto no placeholder de data e hora do slide. |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```

Obtém valor indicando que um placeholder de rodapé está presente. Leitura booleana.

**Retorna:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```

Obtém valor indicando que um placeholder de número de página está presente. Leitura booleana.

**Retorna:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```

Obtém valor indicando que um placeholder de data e hora está presente. Leitura booleana.

**Retorna:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```

Altera a visibilidade do placeholder de rodapé do slide.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna o placeholder de rodapé visível, caso contrário - o oculta. |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

Altera a visibilidade do placeholder de número de página do slide.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna o placeholder de número de página visível, caso contrário - o oculta. |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

Altera a visibilidade do placeholder de data e hora do slide.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| isVisible | boolean | true - torna o placeholder de data e hora visível, caso contrário - o oculta. |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```

Define o texto no placeholder de rodapé do slide.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto a ser definido. |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```

Define o texto no placeholder de data e hora do slide.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto a ser definido. |