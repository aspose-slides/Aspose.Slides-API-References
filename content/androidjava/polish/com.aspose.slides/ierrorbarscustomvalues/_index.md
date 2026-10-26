---
title: IErrorBarsCustomValues
second_title: Aspose.Slides for Android via Java API Reference
description: Specifies the errors bar values.
type: docs
url: /pl/com.aspose.slides/ierrorbarscustomvalues/
---```
public interface IErrorBarsCustomValues
```

Określa wartości pasków błędów. Powinno być używane tylko wtedy, gdy typ wartości pasków błędów jest Custom.
## Metody

| Metoda | Opis |
| --- | --- |
| [getXMinus()](#getXMinus--) | Określa wartość paska błędu w kierunku ujemnym. |
| [getYMinus()](#getYMinus--) | Określa wartość paska błędu w kierunku ujemnym. |
| [getXPlus()](#getXPlus--) | Określa wartość paska błędu w kierunku dodatnim. |
| [getYPlus()](#getYPlus--) | Określa wartość paska błędu w kierunku dodatnim. |
### getXMinus() {#getXMinus--}
```
public abstract IDoubleChartValue getXMinus()
```

Określa wartość paska błędu w kierunku ujemnym. Dostępny, jeśli typ wartości pasków błędów jest Custom i ErrorBarsXFormat jest dozwolony. W każdym innym przypadku ta właściwość zwraca null. Tylko do odczytu [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Zwraca:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public abstract IDoubleChartValue getYMinus()
```

Określa wartość paska błędu w kierunku ujemnym. Dostępny, jeśli typ wartości pasków błędów jest Custom i ErrorBarsYFormat jest dozwolony. W każdym innym przypadku ta właściwość zwraca null. Tylko do odczytu [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Zwraca:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public abstract IDoubleChartValue getXPlus()
```

Określa wartość paska błędu w kierunku dodatnim. Dostępny, jeśli typ wartości pasków błędów jest Custom i ErrorBarsXFormat jest dozwolony. W każdym innym przypadku ta właściwość zwraca null. Tylko do odczytu [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Zwraca:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public abstract IDoubleChartValue getYPlus()
```

Określa wartość paska błędu w kierunku dodatnim. Dostępny, jeśli typ wartości pasków błędów jest Custom i ErrorBarsYFormat jest dozwolony. W każdym innym przypadku ta właściwość zwraca null. Tylko do odczytu [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Zwraca:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)