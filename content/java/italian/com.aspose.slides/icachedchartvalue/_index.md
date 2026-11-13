---
title: ICachedChartValue
second_title: Aspose.Slides for Java API Reference
description: Rappresenta un valore di grafico memorizzato nella cache, ad esempio X, Y, dimensione della bolla o il valore principale.
type: docs
url: /it/com.aspose.slides/icachedchartvalue/
---```
public interface ICachedChartValue
```

Rappresenta un valore di grafico memorizzato nella cache (ad esempio X, Y, dimensione della bolla o il valore principale).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getData()](#getData--) | Ottiene l'oggetto dati memorizzato nella cache. |
| [toDouble()](#toDouble--) | Converte il valore memorizzato nella cache in un double. |
### getData() {#getData--}
```
public abstract Object getData()
```


Ottiene l'oggetto dati memorizzato nella cache. Solo lettura  Object .

**Restituisce:**
java.lang.Object
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Converte il valore memorizzato nella cache in un double.

**Restituisce:**
double - La rappresentazione numerica, oppure Double.NaN se Data (\#getData.getData) è null o non può essere convertita in un double.