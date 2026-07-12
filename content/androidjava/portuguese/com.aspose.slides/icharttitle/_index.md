---
title: IChartTitle
second_title: Aspose.Slides para Android via Referência de API Java
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
| [getOverlay()](#getOverlay--) | Determines whether other chart elements shall be allowed to overlap title. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Determines whether other chart elements shall be allowed to overlap title. |
| [getFormat()](#getFormat--) | Returns the fill, line, effect styles of a title. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Determina se outros elementos do gráfico poderão sobrepor o título. Leitura/escrita boolean.

**Returns:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Determina se outros elementos do gráfico poderão sobrepor o título. Leitura/escrita boolean.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Retorna os estilos de preenchimento, linha e efeito de um título. Somente leitura [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)