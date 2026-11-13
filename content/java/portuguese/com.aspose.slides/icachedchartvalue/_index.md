---
title: ICachedChartValue
second_title: Aspose.Slides para Java Referência da API
description: Representa um valor de gráfico em cache, por exemplo X, Y, tamanho da bolha ou o valor principal.
type: docs
url: /pt/com.aspose.slides/icachedchartvalue/
---```
public interface ICachedChartValue
```

Representa um valor de gráfico em cache (por exemplo, X, Y, tamanho da bolha ou o valor principal).
## Métodos

| Método | Descrição |
| --- | --- |
| [getData()](#getData--) | Obtém o objeto de dados em cache. |
| [toDouble()](#toDouble--) | Converte o valor em cache para double. |
### getData() {#getData--}
```
public abstract Object getData()
```


Obtém o objeto de dados em cache. Somente leitura  Object .

**Retorna:**
java.lang.Object
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Converte o valor em cache para double.

**Retorna:**
double - A representação numérica, ou Double.NaN se Data (\#getData.getData) for nula ou não puder ser convertida para double.