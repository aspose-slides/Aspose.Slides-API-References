---
title: ICell
second_title: Aspose.Sildes per .NET Riferimento API
description: Rappresenta una cella in una tabella.
type: docs
weight: 5450
url: /it/aspose.slides/icell/
---
## ICell interfaccia

Rappresenta una cella in una tabella.

```csharp
public interface ICell : ISlideComponent
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AnchorCenter](../../aspose.slides/icell/anchorcenter) { get; set; } | Determina se il riquadro di testo è centrato all'interno di una cella. Lettura/scrittura Boolean. |
| [AsISlideComponent](../../aspose.slides/icell/asislidecomponent) { get; } | Consente di ottenere l'interfaccia base ISlideComponent. Sola lettura [`ISlideComponent`](../islidecomponent). |
| [CellFormat](../../aspose.slides/icell/cellformat) { get; } | Restituisce l'oggetto CellFormat che contiene le proprietà di formattazione per questa cella. Sola lettura [`ICellFormat`](../icellformat). |
| [ColSpan](../../aspose.slides/icell/colspan) { get; } | Restituisce il numero di colonne della griglia nella tabella padre che devono essere coperte dalla cella corrente. Questa proprietà consente alle celle di apparire unite, poiché si estendono sui confini verticali di altre celle nella tabella. Sola lettura Int32. |
| [FirstColumn](../../aspose.slides/icell/firstcolumn) { get; } | Ottiene la prima colonna della cella. Sola lettura [`IColumn`](../icolumn). |
| [FirstColumnIndex](../../aspose.slides/icell/firstcolumnindex) { get; } | Restituisce l'indice della prima colonna coperta dalla cella. Sola lettura Int32. |
| [FirstRow](../../aspose.slides/icell/firstrow) { get; } | Ottiene la prima riga della cella. Sola lettura [`IRow`](../irow). |
| [FirstRowIndex](../../aspose.slides/icell/firstrowindex) { get; } | Restituisce l'indice della prima riga coperta dalla cella. Sola lettura Int32. |
| [Height](../../aspose.slides/icell/height) { get; } | Restituisce l'altezza della cella. Sola lettura Double. |
| [IsMergedCell](../../aspose.slides/icell/ismergedcell) { get; } | Restituisce true se la cella è unita a qualche cella regolata, false altrimenti. Sola lettura Boolean. |
| [MarginBottom](../../aspose.slides/icell/marginbottom) { get; set; } | Restituisce o imposta il margine inferiore in un TextFrame. Lettura/scrittura Double. |
| [MarginLeft](../../aspose.slides/icell/marginleft) { get; set; } | Restituisce o imposta il margine sinistro in un TextFrame. Lettura/scrittura Double. |
| [MarginRight](../../aspose.slides/icell/marginright) { get; set; } | Restituisce o imposta il margine destro in un TextFrame. Lettura/scrittura Double. |
| [MarginTop](../../aspose.slides/icell/margintop) { get; set; } | Restituisce o imposta il margine superiore in un TextFrame. Lettura/scrittura Double. |
| [MinimalHeight](../../aspose.slides/icell/minimalheight) { get; } | Restituisce l'altezza minima di una cella. Questa è la somma delle altezze minime di tutte le righe coperte dalla cella. Sola lettura Double. |
| [OffsetX](../../aspose.slides/icell/offsetx) { get; } | Restituisce la distanza dal lato sinistro di una tabella al lato sinistro di una cella. Sola lettura Double. |
| [OffsetY](../../aspose.slides/icell/offsety) { get; } | Restituisce la distanza dal lato superiore di una tabella al lato superiore di una cella. Sola lettura Double. |
| [RowSpan](../../aspose.slides/icell/rowspan) { get; } | Restituisce il numero di righe che una cella unita copre. Questo viene usato in combinazione con l'attributo vMerge su altre celle per specificare la cella iniziale di un'unione orizzontale. Sola lettura Int32. |
| [Table](../../aspose.slides/icell/table) { get; } | Restituisce l'oggetto Table padre per una cella. Sola lettura [`ITable`](../itable). |
| [TextAnchorType](../../aspose.slides/icell/textanchortype) { get; set; } | Restituisce o imposta il tipo di ancoraggio del testo. Lettura/scrittura [`TextAnchorType`](../textanchortype). |
| [TextFrame](../../aspose.slides/icell/textframe) { get; } | Restituisce il frame di testo di una cella. Sola lettura [`ITextFrame`](../itextframe). |
| [TextVerticalType](../../aspose.slides/icell/textverticaltype) { get; set; } | Restituisce o imposta il tipo di testo verticale. Lettura/scrittura [`TextVerticalType`](../textverticaltype). |
| [Width](../../aspose.slides/icell/width) { get; } | Restituisce la larghezza della cella. Sola lettura Double. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/icell/splitbycolspan)(int) | Divide la cella in due celle per indice di colonna. |
| [SplitByHeight](../../aspose.slides/icell/splitbyheight)(double) | Divide la cella per altezza. |
| [SplitByRowSpan](../../aspose.slides/icell/splitbyrowspan)(int) | Divide la cella in due celle per indice di riga. |
| [SplitByWidth](../../aspose.slides/icell/splitbywidth)(double) | Divide la cella per larghezza. |

### Vedi anche

* interfaccia [ISlideComponent](../islidecomponent)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->