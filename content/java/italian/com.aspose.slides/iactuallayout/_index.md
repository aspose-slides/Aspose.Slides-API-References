---
title: IActualLayout
second_title: Riferimento API Aspose.Slides per Java
description: Specifica la posizione effettiva di un elemento del grafico.
type: docs
url: /it/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

Specifica la posizione effettiva di un elemento del grafico.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getActualX()](#getActualX--) | Specifica la posizione x effettiva (sinistra) dell'elemento del grafico rispetto all'angolo superiore sinistro del grafico. |
| [getActualY()](#getActualY--) | Specifica la parte superiore effettiva dell'elemento del grafico rispetto all'angolo superiore sinistro del grafico. |
| [getActualWidth()](#getActualWidth--) | Specifica la larghezza effettiva dell'elemento del grafico. |
| [getActualHeight()](#getActualHeight--) | Specifica l'altezza effettiva dell'elemento del grafico. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```

Specifică la posizione x effettiva (sinistra) dell'elemento del grafico rispetto all'angolo superiore sinistro del grafico. Chiama il metodo IChart.ValidateChartLayout() prima per ottenere i valori effettivi. Leggi float.

**Restituisce:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```

Specifică la parte superiore effettiva dell'elemento del grafico rispetto all'angolo superiore sinistro del grafico. Chiama il metodo IChart.ValidateChartLayout() prima per ottenere i valori effettivi. Leggi float.

**Restituisce:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```

Specifică la larghezza effettiva dell'elemento del grafico. Chiama il metodo IChart.ValidateChartLayout() prima per ottenere i valori effettivi. Leggi float.

**Restituisce:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```

Specifică l'altezza effettiva dell'elemento del grafico. Chiama il metodo IChart.ValidateChartLayout() prima per ottenere i valori effettivi. Leggi float.

**Restituisce:**
float