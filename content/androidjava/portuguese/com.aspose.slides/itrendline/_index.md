---
title: ITrendline
second_title: Aspose.Slides para Android via Referência da API Java
description: Classe representa a linha de tendência da série de gráfico
type: docs
url: /pt/com.aspose.slides/itrendline/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

Classe representa a linha de tendência da série de gráfico
## Métodos

| Método | Descrição |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Obtém ou define o nome da linha de tendência. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Obtém ou define o nome da linha de tendência. |
| [getTrendlineType()](#getTrendlineType--) | Obtém ou define o tipo da linha de tendência. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Obtém ou define o tipo da linha de tendência. |
| [getFormat()](#getFormat--) | Representa o formato da linha de tendência. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Representa o formato da linha de tendência. |
| [getBackward()](#getBackward--) | Especifica o número de categorias (ou unidades em um diagrama de dispersão) que a linha de tendência se estende antes dos dados da série que está sendo analisada. |
| [setBackward(double value)](#setBackward-double-) | Especifica o número de categorias (ou unidades em um diagrama de dispersão) que a linha de tendência se estende antes dos dados da série que está sendo analisada. |
| [getForward()](#getForward--) | Especifica o número de categorias (ou unidades em um diagrama de dispersão) que a linha de tendência se estende após os dados da série que está sendo analisada. |
| [setForward(double value)](#setForward-double-) | Especifica o número de categorias (ou unidades em um diagrama de dispersão) que a linha de tendência se estende após os dados da série que está sendo analisada. |
| [getIntercept()](#getIntercept--) | Especifica o valor onde a linha de tendência cruza o eixo y. |
| [setIntercept(double value)](#setIntercept-double-) | Especifica o valor onde a linha de tendência cruza o eixo y. |
| [getDisplayEquation()](#getDisplayEquation--) | Especifica que a equação da linha de tendência é exibida no gráfico (no mesmo rótulo que o Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Especifica que a equação da linha de tendência é exibida no gráfico (no mesmo rótulo que o Rsquaredvalue). |
| [getOrder()](#getOrder--) | Especifica a ordem da linha de tendência polinomial. |
| [setOrder(byte value)](#setOrder-byte-) | Especifica a ordem da linha de tendência polinomial. |
| [getPeriod()](#getPeriod--) | Especifica o período da linha de tendência para uma linha de tendência de média móvel. |
| [setPeriod(byte value)](#setPeriod-byte-) | Especifica o período da linha de tendência para uma linha de tendência de média móvel. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Especifica que o valor R-squared da linha de tendência é exibido no gráfico (no mesmo rótulo que a equação). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Especifica que o valor R-squared da linha de tendência é exibido no gráfico (no mesmo rótulo que a equação). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Representa a entrada da legenda relacionada a esta linha de tendência Somente leitura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

Obtém ou define o nome da linha de tendência. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

Obtém ou define o nome da linha de tendência. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

Obtém ou define o tipo da linha de tendência. Leitura/Gravação [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Retorna:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

Obtém ou define o tipo da linha de tendência. Leitura/Gravação [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Representa o formato da linha de tendência. Leitura/Gravação [IFormat](../../com.aspose.slides/iformat).

**Retorna:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Representa o formato da linha de tendência. Leitura/Gravação [IFormat](../../com.aspose.slides/iformat).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

Especifica o número de categorias (ou unidades em um diagrama de dispersão) que a linha de tendência se estende antes dos dados da série que está sendo analisada. Em diagramas de dispersão e não-dispersão, o valor deve ser não negativo. Leitura/Gravação double.

**Retorna:**
double
### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

Especifica o número de categorias (ou unidades em um diagrama de dispersão) que a linha de tendência se estende antes dos dados da série que está sendo analisada. Em diagramas de dispersão e não-dispersão, o valor deve ser não negativo. Leitura/Gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public abstract double getForward()
```

Especifica o número de categorias (ou unidades em um diagrama de dispersão) que a linha de tendência se estende após os dados da série que está sendo analisada. Em diagramas de dispersão e não-dispersão, o valor deve ser não negativo. Leitura/Gravação double.

**Retorna:**
double
### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

Especifica o número de categorias (ou unidades em um diagrama de dispersão) que a linha de tendência se estende após os dados da série que está sendo analisada. Em diagramas de dispersão e não-dispersão, o valor deve ser não negativo. Leitura/Gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

Especifica o valor onde a linha de tendência cruza o eixo y. Esta propriedade é suportada apenas quando o tipo de linha de tendência é exp, linear ou poly. Leitura/Gravação double.

**Retorna:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

Especifica o valor onde a linha de tendência cruza o eixo y. Esta propriedade é suportada apenas quando o tipo de linha de tendência é exp, linear ou poly. Leitura/Gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

Especifica que a equação da linha de tendência é exibida no gráfico (no mesmo rótulo que o Rsquaredvalue). Leitura/Gravação boolean.

**Retorna:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

Especifica que a equação da linha de tendência é exibida no gráfico (no mesmo rótulo que o Rsquaredvalue). Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

Especifica a ordem da linha de tendência polinomial. É ignorado para outros tipos de linha de tendência. O valor deve estar entre 2 e 6. Leitura/Gravação byte.

**Retorna:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

Especifica a ordem da linha de tendência polinomial. É ignorado para outros tipos de linha de tendência. O valor deve estar entre 2 e 6. Leitura/Gravação byte.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

Especifica o período da linha de tendência para uma linha de tendência de média móvel. É ignorado para outras variantes de linha de tendência. O valor deve estar entre 2 e 255. Leitura/Gravação byte.

**Retorna:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

Especifica o período da linha de tendência para uma linha de tendência de média móvel. É ignorado para outras variantes de linha de tendência. O valor deve estar entre 2 e 255. Leitura/Gravação byte.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

Especifica que o valor R-squared da linha de tendência é exibido no gráfico (no mesmo rótulo que a equação). Leitura/Gravação boolean.

**Retorna:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

Especifica que o valor R-squared da linha de tendência é exibido no gráfico (no mesmo rótulo que a equação). Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Representa a entrada da legenda relacionada a esta linha de tendência Somente leitura [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Retorna:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)