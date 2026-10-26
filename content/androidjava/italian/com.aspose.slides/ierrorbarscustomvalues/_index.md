---
title: IErrorBarsCustomValues
second_title: Riferimento API Java per Aspose.Slides per Android
description: Specifica i valori delle barre di errore.
type: docs
url: /it/com.aspose.slides/ierrorbarscustomvalues/
---```
public interface IErrorBarsCustomValues
```

Specifica i valori delle barre di errore. Deve essere usato solo quando il tipo di valore di Error bars è Custom.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getXMinus()](#getXMinus--) | Specifica il valore della barra di errore nella direzione negativa. |
| [getYMinus()](#getYMinus--) | Specifica il valore della barra di errore nella direzione negativa. |
| [getXPlus()](#getXPlus--) | Specifica il valore della barra di errore nella direzione positiva. |
| [getYPlus()](#getYPlus--) | Specifica il valore della barra di errore nella direzione positiva. |
### getXMinus() {#getXMinus--}
```
public abstract IDoubleChartValue getXMinus()
```

Specifica il valore della barra di errore nella direzione negativa. Disponibile se il tipo di valore di Error bars è Custom e ErrorBarsXFormat è consentito. In qualsiasi altro caso questa proprietà restituisce null. Solo lettura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Restituisce:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public abstract IDoubleChartValue getYMinus()
```

Specifica il valore della barra di errore nella direzione negativa. Disponibile se il tipo di valore di Error bars è Custom e ErrorBarsYFormat è consentito. In qualsiasi altro caso questa proprietà restituisce null. Solo lettura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Restituisce:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public abstract IDoubleChartValue getXPlus()
```

Specifica il valore della barra di errore nella direzione positiva. Disponibile se il tipo di valore di Error bars è Custom e ErrorBarsXFormat è consentito. In qualsiasi altro caso questa proprietà restituisce null. Solo lettura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Restituisce:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public abstract IDoubleChartValue getYPlus()
```

Specifica il valore della barra di errore nella direzione positiva. Disponibile se il tipo di valore di Error bars è Custom e ErrorBarsYFormat è consentito. In qualsiasi altro caso questa proprietà restituisce null. Solo lettura [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Restituisce:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)