---
title: CachedChartValue
second_title: Referência da API Aspose.Slides para Java
description: Representa um valor de gráfico armazenado em cache, por exemplo X, Y, tamanho da bolha ou o valor principal.
type: docs
url: /pt/com.aspose.slides/cachedchartvalue/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
```
public class CachedChartValue implements ICachedChartValue
```

Representa um valor de gráfico armazenado em cache (por exemplo, X, Y, tamanho da bolha ou o valor principal).
## Construtores

| Construtor | Descrição |
| --- | --- |
| [CachedChartValue()](#CachedChartValue--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [toString()](#toString--) | Retorna uma representação em string do valor armazenado em cache. |
| [toDouble()](#toDouble--) | Converte o valor armazenado em cache para double. |
| [getData()](#getData--) | Obtém o objeto de dados armazenado em cache. |
### CachedChartValue() {#CachedChartValue--}
```
public CachedChartValue()
```


### toString() {#toString--}
```
public String toString()
```


Retorna uma representação em string do valor armazenado em cache.

**Retorna:**
java.lang.String
### toDouble() {#toDouble--}
```
public final double toDouble()
```


Converte o valor armazenado em cache para double.

**Retorna:**
double - A representação numérica, ou Double.NaN se Data (\#getData.getData/\#setData(Object).setData(Object)) for nula ou não puder ser convertida para double.
### getData() {#getData--}
```
public final Object getData()
```


Obtém o objeto de dados armazenado em cache. Somente leitura  Object .

**Retorna:**
java.lang.Object