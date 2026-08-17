---
title: IChartTitle
second_title: Referência da API Aspose.Slides para Java
description: Representa as propriedades do título do gráfico.
type: docs
url: /pt/com.aspose.slides/icharttitle/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

Representa as propriedades do título do gráfico.
## Métodos

| Método | Descrição |
| --- | --- |
| [getOverlay()](#getOverlay--) | Determina se outros elementos do gráfico podem sobrepor o título. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Determina se outros elementos do gráfico podem sobrepor o título. |
| [getFormat()](#getFormat--) | Retorna os estilos de preenchimento, linha e efeito de um título. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Determina se outros elementos do gráfico podem sobrepor o título. Leitura/gravação boolean.

**Retorna:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Determina se outros elementos do gráfico podem sobrepor o título. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Retorna os estilos de preenchimento, linha e efeito de um título. Somente leitura [IFormat](../../com.aspose.slides/iformat).

**Retorna:**
[IFormat](../../com.aspose.slides/iformat)