---
title: IErrorBarsCustomValues
second_title: Aspose.Slides for Java API Reference
description: Anger felstaplarnas värden.
type: docs
url: /sv/com.aspose.slides/ierrorbarscustomvalues/
---```
public interface IErrorBarsCustomValues
```

Anger felstaplarnas värden. Den ska endast användas när felstaplarnas värdetyp är Custom.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getXMinus()](#getXMinus--) | Anger felstapeln värde i den negativa riktningen. |
| [getYMinus()](#getYMinus--) | Anger felstapeln värde i den negativa riktningen. |
| [getXPlus()](#getXPlus--) | Anger felstapeln värde i den positiva riktningen. |
| [getYPlus()](#getYPlus--) | Anger felstapeln värde i den positiva riktningen. |
### getXMinus() {#getXMinus--}
```
public abstract IDoubleChartValue getXMinus()
```


Anger felstapeln värde i den negativa riktningen. Tillgänglig om felstaplarnas värdetyp är Custom och ErrorBarsXFormat är tillåtet. I alla andra fall returnerar denna egenskap null. Skrivskyddad [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returnerar:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public abstract IDoubleChartValue getYMinus()
```


Anger felstapeln värde i den negativa riktningen. Tillgänglig om felstaplarnas värdetyp är Custom och ErrorBarsYFormat är tillåtet. I alla andra fall returnerar denna egenskap null. Skrivskyddad [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returnerar:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public abstract IDoubleChartValue getXPlus()
```


Anger felstapeln värde i den positiva riktningen. Tillgänglig om felstaplarnas värdetyp är Custom och ErrorBarsXFormat är tillåtet. I alla andra fall returnerar denna egenskap null. Skrivskyddad [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returnerar:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public abstract IDoubleChartValue getYPlus()
```


Anger felstapeln värde i den positiva riktningen. Tillgänglig om felstaplarnas värdetyp är Custom och ErrorBarsYFormat är tillåtet. I alla andra fall returnerar denna egenskap null. Skrivskyddad [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returnerar:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)