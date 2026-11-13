---
title: ICachedChartValue
second_title: Aspose.Slides for Java API Reference
description: Represents a cached chart value e.g. X Y bubble size or the main value.
type: docs
url: /tr/com.aspose.slides/icachedchartvalue/
---```
public interface ICachedChartValue
```

Önbelleğe alınmış bir grafik değerini temsil eder (ör. X, Y, balon boyutu veya ana değer).
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getData()](#getData--) | Önbelleğe alınmış veri nesnesini alır. |
| [toDouble()](#toDouble--) | Önbelleğe alınmış değeri double'a dönüştürür. |
### getData() {#getData--}
```
public abstract Object getData()
```

Önbelleğe alınmış veri nesnesini alır. Salt-okunur  Object .

**Döndürür:**  
java.lang.Object
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Önbelleğe alınmış değeri double'a dönüştürür.

**Döndürür:**  
double - Sayısal temsil, veya Data (\#getData.getData) null ise ya da double'a dönüştürülemezse Double.NaN.