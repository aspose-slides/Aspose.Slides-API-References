---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Representerar alternativ som kan användas för att specificera ytterligare kalkylbladsbeteende.
type: docs
url: /sv/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

Representerar alternativ som kan användas för att specificera ytterligare kalkylbladsbeteende.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Hämtar eller anger föredragen kulturinformation för beräkning av vissa funktioner avsedda för språk som använder dubbelbyte-teckenuppsättningen (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Hämtar eller anger föredragen kulturinformation för beräkning av vissa funktioner avsedda för språk som använder dubbelbyte-teckenuppsättningen (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Om datakällan för diagrammet är en extern arbetsbok och den inte är tillgänglig, återställs den från diagramcachen. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Om datakällan för diagrammet är en extern arbetsbok och den inte är tillgänglig, återställs den från diagramcachen. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```

Hämtar eller anger föredragen kulturinformation för beräkning av vissa funktioner avsedda för språk som använder dubbelbyte-teckenuppsättningen (DBCS).

**Returnerar:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```

Hämtar eller anger föredragen kulturinformation för beräkning av vissa funktioner avsedda för språk som använder dubbelbyte-teckenuppsättningen (DBCS).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.Locale |  |
### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```

Om datakällan för diagrammet är en extern arbetsbok och den inte är tillgänglig, återställs den från diagramcachen.

--------------------

> ```
> Example:
>   
>   SpreadsheetOptions spreadOptions = new SpreadsheetOptions();
>   spreadOptions.setRecoverWorkbookFromChartCache(true);
> 
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setSpreadsheetOptions(spreadOptions);
> 
>   Presentation pres = new Presentation("Presentation.pptx", loadOptions);
>   try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartDataWorkbook recoveredWorkbook = chart.getChartData().getChartDataWorkbook();
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**Returnerar:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```

Om datakällan för diagrammet är en extern arbetsbok och den inte är tillgänglig, återställs den från diagramcachen.

--------------------

> ```
> Example:
>   
>   SpreadsheetOptions spreadOptions = new SpreadsheetOptions();
>   spreadOptions.setRecoverWorkbookFromChartCache(true);
> 
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setSpreadsheetOptions(spreadOptions);
> 
>   Presentation pres = new Presentation("Presentation.pptx", loadOptions);
>   try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartDataWorkbook recoveredWorkbook = chart.getChartData().getChartDataWorkbook();
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |