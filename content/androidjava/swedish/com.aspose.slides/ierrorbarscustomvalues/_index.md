---
title: IErrorBarsCustomValues
second_title: Aspose.Slides for Android via Java API Reference
description: Specifies the errors bar values.
type: docs
url: /sv/com.aspose.slides/ierrorbarscustomvalues/
---```
public interface IErrorBarsCustomValues
```

Anger värdena för felstaplar. Den ska endast användas när felstaplarna har värdetypen Custom.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getXMinus()](#getXMinus--) | Anger felstapelsvärdet i negativ riktning. |
| [getYMinus()](#getYMinus--) | Anger felstapelsvärdet i negativ riktning. |
| [getXPlus()](#getXPlus--) | Anger felstapelsvärdet i positiv riktning. |
| [getYPlus()](#getYPlus--) | Anger felstapelsvärdet i positiv riktning. |
### getXMinus() {#getXMinus--}
```
public abstract IDoubleChartValue getXMinus()
```

Anger felstapelsvärdet i negativ riktning. Tillgänglig om felstaplarnas värdetyp är Custom och ErrorBarsXFormat är tillåtet. I alla andra fall returnerar denna egenskap null. Skrivskyddad [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returnerar:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public abstract IDoubleChartValue getYMinus()
```

Anger felstapelsvärdet i negativ riktning. Tillgänglig om felstaplarnas värdetyp är Custom och ErrorBarsYFormat är tillåtet. I alla andra fall returnerar denna egenskap null. Skrivskyddad [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returnerar:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public abstract IDoubleChartValue getXPlus()
```

Anger felstapelsvärdet i positiv riktning. Tillgänglig om felstaplarnas värdetyp är Custom och ErrorBarsXFormat är tillåtet. I alla andra fall returnerar denna egenskap null. Skrivskyddad [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returnerar:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public abstract IDoubleChartValue getYPlus()
```

Anger felstapelsvärdet i positiv riktning. Tillgänglig om felstaplarnas värdetyp är Custom och ErrorBarsYFormat är tillåtet. I alla andra fall returnerar denna egenskap null. Skrivskyddad [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Returnerar:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)