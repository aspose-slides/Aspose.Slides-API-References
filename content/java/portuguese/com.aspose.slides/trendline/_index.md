---
title: Trendline
second_title: Referência da API Aspose.Slides para Java
description: Classe representa linha de tendência da série de gráfico
type: docs
url: /pt/com.aspose.slides/trendline/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

A classe representa a linha de tendência da série de gráfico
## Métodos

| Método | Descrição |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Obtém ou define o nome da linha de tendência. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Obtém ou define o nome da linha de tendência. |
| [getTrendlineType()](#getTrendlineType--) | Obtém ou define o tipo da linha de tendência. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Obtém ou define o tipo da linha de tendência. |
| [getFormat()](#getFormat--) | Representa o formato da linha de tendência. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Representa o formato da linha de tendência. |
| [getBackward()](#getBackward--) | Especifica o número de categorias (ou unidades em um gráfico de dispersão) que a linha de tendência se estende antes dos dados da série que está sendo tendida. |
| [setBackward(double value)](#setBackward-double-) | Especifica o número de categorias (ou unidades em um gráfico de dispersão) que a linha de tendência se estende antes dos dados da série que está sendo tendida. |
| [getForward()](#getForward--) | Especifica o número de categorias (ou unidades em um gráfico de dispersão) que a linha de tendência se estende após os dados da série que está sendo tendida. |
| [setForward(double value)](#setForward-double-) | Especifica o número de categorias (ou unidades em um gráfico de dispersão) que a linha de tendência se estende após os dados da série que está sendo tendida. |
| [getIntercept()](#getIntercept--) | Especifica o valor onde a linha de tendência cruza o eixo y. |
| [setIntercept(double value)](#setIntercept-double-) | Especifica o valor onde a linha de tendência cruza o eixo y. |
| [getDisplayEquation()](#getDisplayEquation--) | Especifica que a equação da linha de tendência é exibida no gráfico (no mesmo rótulo que o Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Especifica que a equação da linha de tendência é exibida no gráfico (no mesmo rótulo que o Rsquaredvalue). |
| [getOrder()](#getOrder--) | Especifica a ordem da linha de tendência polinomial. |
| [setOrder(byte value)](#setOrder-byte-) | Especifica a ordem da linha de tendência polinomial. |
| [getPeriod()](#getPeriod--) | Especifica o período da linha de tendência para uma linha de tendência de média móvel. |
| [setPeriod(byte value)](#setPeriod-byte-) | Especifica o período da linha de tendência para uma linha de tendência de média móvel. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Especifica que o valor R-quadrado da linha de tendência é exibido no gráfico (no mesmo rótulo que a equação). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Especifica que o valor R-quadrado da linha de tendência é exibido no gráfico (no mesmo rótulo que a equação). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Representa a entrada da legenda relacionada a esta linha de tendência Somente leitura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicializa TextFrameForOverriding com o texto no parâmetro "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Pode conter um texto formatado rico. |
| [getTextFormat()](#getTextFormat--) | Retorna o formato do texto. |
| [getChart()](#getChart--) | Retorna o gráfico pai. |
| [getSlide()](#getSlide--) | Retorna o slide pai de um FillFormat. |
| [getPresentation()](#getPresentation--) | Retorna a apresentação pai de um FillFormat. |
### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

Obtém ou define o nome da linha de tendência. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

Obtém ou define o nome da linha de tendência. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

Obtém ou define o tipo da linha de tendência. Leitura/Gravação [TrendlineType](../../com.aspose.slides/trendlinetype).

**Retorna:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

Obtém ou define o tipo da linha de tendência. Leitura/Gravação [TrendlineType](../../com.aspose.slides/trendlinetype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Representa o formato da linha de tendência. Leitura/Gravação [IFormat](../../com.aspose.slides/iformat).

**Retorna:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Representa o formato da linha de tendência. Leitura/Gravação [IFormat](../../com.aspose.slides/iformat).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public final double getBackward()
```

Especifica o número de categorias (ou unidades em um gráfico de dispersão) que a linha de tendência se estende antes dos dados da série que está sendo tendida. Em gráficos de dispersão e não-dispersão, o valor deve ser qualquer valor não-negativo. Leitura/Gravação double.

**Retorna:**
double
### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

Especifica o número de categorias (ou unidades em um gráfico de dispersão) que a linha de tendência se estende antes dos dados da série que está sendo tendida. Em gráficos de dispersão e não-dispersão, o valor deve ser qualquer valor não-negativo. Leitura/Gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public final double getForward()
```

Especifica o número de categorias (ou unidades em um gráfico de dispersão) que a linha de tendência se estende após os dados da série que está sendo tendida. Em gráficos de dispersão e não-dispersão, o valor deve ser qualquer valor não-negativo. Leitura/Gravação double.

**Retorna:**
double
### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

Especifica o número de categorias (ou unidades em um gráfico de dispersão) que a linha de tendência se estende após os dados da série que está sendo tendida. Em gráficos de dispersão e não-dispersão, o valor deve ser qualquer valor não-negativo. Leitura/Gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

Especifica o valor onde a linha de tendência cruza o eixo y. Essa propriedade é suportada apenas quando o tipo da linha de tendência é exp, linear ou poly. Leitura/Gravação double.

**Retorna:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

Especifica o valor onde a linha de tendência cruza o eixo y. Essa propriedade é suportada apenas quando o tipo da linha de tendência é exp, linear ou poly. Leitura/Gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

Especifica que a equação da linha de tendência é exibida no gráfico (no mesmo rótulo que o Rsquaredvalue). Leitura/Gravação boolean.

**Retorna:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

Especifica que a equação da linha de tendência é exibida no gráfico (no mesmo rótulo que o Rsquaredvalue). Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public final byte getOrder()
```

Especifica a ordem da linha de tendência polinomial. É ignorada para outros tipos de linha de tendência. O valor deve estar entre 2 e 6. Leitura/Gravação byte.

**Retorna:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

Especifica a ordem da linha de tendência polinomial. É ignorada para outros tipos de linha de tendência. O valor deve estar entre 2 e 6. Leitura/Gravação byte.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

Especifica o período da linha de tendência para uma linha de tendência de média móvel. É ignorado para outras variantes de linha de tendência. O valor deve estar entre 2 e 255. Leitura/Gravação byte.

**Retorna:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

Especifica o período da linha de tendência para uma linha de tendência de média móvel. É ignorado para outras variantes de linha de tendência. O valor deve estar entre 2 e 255. Leitura/Gravação byte.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

Especifica que o valor R-quadrado da linha de tendência é exibido no gráfico (no mesmo rótulo que a equação). Leitura/Gravação boolean.

**Retorna:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

Especifica que o valor R-quadrado da linha de tendência é exibido no gráfico (no mesmo rótulo que a equação). Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Representa a entrada da legenda relacionada a esta linha de tendência Somente leitura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Retorna:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Inicializa TextFrameForOverriding com o texto no parâmetro "text". Se TextFrameForOverriding já estiver inicializado, simplesmente altera seu texto.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto para um novo TextFrameForOverriding. |

**Retorna:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Pode conter um texto formatado rico. Se esta propriedade não for nula, esse valor de texto formatado substitui o texto auto-gerado da etiqueta de dados. Texto auto-gerado da etiqueta de dados significa texto gerenciado pelas propriedades ShowSeriesName, ShowValue, … e formatado com a propriedade TextFormatManager.TextFormat. Somente leitura [ITextFrame](../../com.aspose.slides/itextframe).

**Retorna:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Retorna o formato do texto. Somente leitura [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Retorna:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

Retorna o gráfico pai. Somente leitura [IChart](../../com.aspose.slides/ichart).

**Retorna:**
[IChart](../../com.aspose.slides/ichart)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retorna o slide pai de um FillFormat. Somente leitura [BaseSlide](../../com.aspose.slides/baseslide).

**Retorna:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retorna a apresentação pai de um FillFormat. Somente leitura [IPresentation](../../com.aspose.slides/ipresentation).

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation)