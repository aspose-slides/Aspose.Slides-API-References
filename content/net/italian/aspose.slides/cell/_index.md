---
title: Cell
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta una cella di una tabella.
type: docs
weight: 1110
url: /it/aspose.slides/cell/
---
## Classe Cell

Rappresenta una cella di una tabella.

```csharp
public class Cell : ICell
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AnchorCenter](../../aspose.slides/cell/anchorcenter) { get; set; } | Determina se il riquadro di testo è centrato all'interno di una cella. Lettura/scrittura Boolean. |
| [CellFormat](../../aspose.slides/cell/cellformat) { get; } | Restituisce l'oggetto CellFormat che contiene le proprietà di formattazione per questa cella. Solo lettura [`ICellFormat`](../icellformat). |
| [ColSpan](../../aspose.slides/cell/colspan) { get; } | Restituisce il numero di colonne della griglia nella tabella padre che deve essere coperto dalla cella corrente. Questa proprietà consente alle celle di avere l'aspetto di essere unite, poiché coprono i confini verticali di altre celle nella tabella. Solo lettura Int32. |
| [FirstColumn](../../aspose.slides/cell/firstcolumn) { get; } | Restituisce la prima colonna della cella. Solo lettura [`IColumn`](../icolumn). |
| [FirstColumnIndex](../../aspose.slides/cell/firstcolumnindex) { get; } | Restituisce l'indice della prima colonna coperta dalla cella. Solo lettura Int32. |
| [FirstRow](../../aspose.slides/cell/firstrow) { get; } | Restituisce la prima riga della cella. Solo lettura [`IRow`](../irow). |
| [FirstRowIndex](../../aspose.slides/cell/firstrowindex) { get; } | Restituisce l'indice della prima riga coperta dalla cella. Solo lettura Int32. |
| [Height](../../aspose.slides/cell/height) { get; } | Restituisce l'altezza della cella. Solo lettura Double. |
| [IsMergedCell](../../aspose.slides/cell/ismergedcell) { get; } | Restituisce true se la cella è unita con una qualsiasi cella regolata, false altrimenti. Solo lettura Boolean. |
| [MarginBottom](../../aspose.slides/cell/marginbottom) { get; set; } | Restituisce o imposta il margine inferiore in un TextFrame. Lettura/scrittura Double. |
| [MarginLeft](../../aspose.slides/cell/marginleft) { get; set; } | Restituisce o imposta il margine sinistro in un TextFrame. Lettura/scrittura Double. |
| [MarginRight](../../aspose.slides/cell/marginright) { get; set; } | Restituisce o imposta il margine destro in un TextFrame. Lettura/scrittura Double. |
| [MarginTop](../../aspose.slides/cell/margintop) { get; set; } | Restituisce o imposta il margine superiore in un TextFrame. Lettura/scrittura Double. |
| [MinimalHeight](../../aspose.slides/cell/minimalheight) { get; } | Restituisce l'altezza minima di una cella. Questa è la somma delle altezze minime di tutte le righe coperte dalla cella. Solo lettura Double. |
| [OffsetX](../../aspose.slides/cell/offsetx) { get; } | Restituisce la distanza dal lato sinistro di una tabella al lato sinistro di una cella. Solo lettura Double. |
| [OffsetY](../../aspose.slides/cell/offsety) { get; } | Restituisce la distanza dal lato superiore di una tabella al lato superiore di una cella. Solo lettura Double. |
| [Presentation](../../aspose.slides/cell/presentation) { get; } | Restituisce la presentazione padre di una cella. Solo lettura [`IPresentation`](../ipresentation). |
| [RowSpan](../../aspose.slides/cell/rowspan) { get; } | Restituisce il numero di righe che una cella unita copre. Questo è usato in combinazione con l'attributo vMerge su altre celle per specificare la cella iniziale di una fusione orizzontale. Solo lettura Int32. |
| [Slide](../../aspose.slides/cell/slide) { get; } | Restituisce la diapositiva padre di una cella. Solo lettura [`IBaseSlide`](../ibaseslide). |
| [Table](../../aspose.slides/cell/table) { get; } | Restituisce l'oggetto Table padre per una cella. Solo lettura [`ITable`](../itable). |
| [TextAnchorType](../../aspose.slides/cell/textanchortype) { get; set; } | Restituisce o imposta il tipo di ancoraggio del testo. Lettura/scrittura [`TextAnchorType`](../textanchortype). |
| [TextFrame](../../aspose.slides/cell/textframe) { get; } | Restituisce il frame di testo di una cella. Solo lettura [`ITextFrame`](../itextframe). |
| [TextVerticalType](../../aspose.slides/cell/textverticaltype) { get; set; } | Restituisce o imposta il tipo di testo verticale. Lettura/scrittura [`TextVerticalType`](../textverticaltype). |
| [Width](../../aspose.slides/cell/width) { get; } | Restituisce la larghezza della cella. Solo lettura Double. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/cell/splitbycolspan)(int) | Dividi la cella in due celle usando l'indice della colonna. |
| [SplitByHeight](../../aspose.slides/cell/splitbyheight)(double) | Dividi la cella in base all'altezza. |
| [SplitByRowSpan](../../aspose.slides/cell/splitbyrowspan)(int) | Dividi la cella in due celle usando l'indice della riga. |
| [SplitByWidth](../../aspose.slides/cell/splitbywidth)(double) | Dividi la cella in base alla larghezza. |

### Vedi anche

* interfaccia [ICell](../icell)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->