---
title: SpreadsheetOptions
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar alternativ som kan användas för att specificera ytterligare kalkylbladsbeteende.
type: docs
url: /sv/com.aspose.slides/spreadsheetoptions/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
```
public class SpreadsheetOptions implements ISpreadsheetOptions
```

Representerar alternativ som kan användas för att specificera ytterligare kalkylbladsbeteende.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | Initierar en ny instans av klassen [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Hämtar eller anger föredragen kulturinformation för att beräkna vissa funktioner avsedda för språk som använder dubbelbyte-teckenuppsättningen (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Hämtar eller anger föredragen kulturinformation för att beräkna vissa funktioner avsedda för språk som använder dubbelbyte-teckenuppsättningen (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Om datakällan för diagrammet är en extern arbetsbok och den inte är tillgänglig, kommer den att återställas från diagramcachen. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Om datakällan för diagrammet är en extern arbetsbok och den inte är tillgänglig, kommer den att återställas från diagramcachen. |
### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```

Initierar en ny instans av klassen [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions).

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```

Hämtar eller anger föredragen kulturinformation för att beräkna vissa funktioner avsedda för språk som använder dubbelbyte-teckenuppsättningen (DBCS).

**Returnerar:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```

Hämtar eller anger föredragen kulturinformation för att beräkna vissa funktioner avsedda för språk som använder dubbelbyte-teckenuppsättningen (DBCS).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```

Om datakällan för diagrammet är en extern arbetsbok och den inte är tillgänglig, kommer den att återställas från diagramcachen.

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
public final void setRecoverWorkbookFromChartCache(boolean value)
```

Om datakällan för diagrammet är en extern arbetsbok och den inte är tillgänglig, kommer den att återställas från diagramcachen.

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