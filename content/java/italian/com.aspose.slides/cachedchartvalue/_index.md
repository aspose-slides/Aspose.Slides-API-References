---
title: CachedChartValue
second_title: Riferimento API Aspose.Slides per Java
description: Rappresenta un valore di grafico memorizzato nella cache, ad es. X, Y, dimensione della bolla o il valore principale.
type: docs
url: /it/com.aspose.slides/cachedchartvalue/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
```
public class CachedChartValue implements ICachedChartValue
```

Rappresenta un valore di grafico memorizzato nella cache (ad es., X, Y, dimensione bolla o il valore principale).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CachedChartValue()](#CachedChartValue--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [toString()](#toString--) | Restituisce una rappresentazione stringa del valore memorizzato nella cache. |
| [toDouble()](#toDouble--) | Converte il valore memorizzato nella cache in un double. |
| [getData()](#getData--) | Ottiene l'oggetto dati memorizzato nella cache. |
### CachedChartValue() {#CachedChartValue--}
```
public CachedChartValue()
```


### toString() {#toString--}
```
public String toString()
```


Restituisce una rappresentazione stringa del valore memorizzato nella cache.

**Restituisce:**
java.lang.String
### toDouble() {#toDouble--}
```
public final double toDouble()
```


Converte il valore memorizzato nella cache in un double.

**Restituisce:**
double - La rappresentazione numerica, o Double.NaN se Data (\#getData.getData/\#setData(Object).setData(Object)) è nulla o non può essere convertita in un double.
### getData() {#getData--}
```
public final Object getData()
```


Ottiene l'oggetto dati memorizzato nella cache. Sola lettura  Object .

**Restituisce:**
java.lang.Object