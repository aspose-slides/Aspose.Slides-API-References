---
title: ISmartArtNode class
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.smartart/ismartartnode/
---
## ISmartArtNode classe

Rappresenta un nodo di un diagramma SmartArt.

Il tipo ISmartArtNode espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`child_nodes`](/slides/python-net/it/aspose.slides.smartart/ismartartnode/child_nodes/) | Restituisce le raccolte di tutti i nodi figlio del nodo corrente.<br/>            Sola lettura [`ISmartArtNodeCollection`](/slides/python-net/it/aspose.slides.smartart/ismartartnodecollection). |
| [`shapes`](/slides/python-net/it/aspose.slides.smartart/ismartartnode/shapes/) | Restituisce le raccolte di tutte le forme associate al nodo.<br/>            Sola lettura [`ISmartArtShapeCollection`](/slides/python-net/it/aspose.slides.smartart/ismartartshapecollection). |
| [`text_frame`](/slides/python-net/it/aspose.slides.smartart/ismartartnode/text_frame/) | Restituisce o imposta il testo del nodo.<br/>            Sola lettura [`ITextFrame`](/slides/python-net/it/aspose.slides/itextframe). |
| [`is_assistant`](/slides/python-net/it/aspose.slides.smartart/ismartartnode/is_assistant/) | Restituisce o imposta il nodo come assistente.<br/>            Lettura/scrittura **bool**. |
| [`level`](/slides/python-net/it/aspose.slides.smartart/ismartartnode/level/) | Restituisce il livello di annidamento del nodo.<br/>            Sola lettura **int**. |
| [`bullet_fill_format`](/slides/python-net/it/aspose.slides.smartart/ismartartnode/bullet_fill_format/) | Restituisce l'oggetto FillFormat che contiene le proprietà di formattazione di riempimento per un pallino di nodo.<br/>            Nota: può restituire None per alcuni tipi di layout SmartArt che non forniscono pallini per i nodi.<br/>            Sola lettura [`IFillFormat`](/slides/python-net/it/aspose.slides/ifillformat). |
| [`position`](/slides/python-net/it/aspose.slides.smartart/ismartartnode/position/) | Restituisce o imposta la posizione a indice zero del nodo tra i nodi fratelli.<br/>            Lettura/scrittura **int**. |
| [`is_hidden`](/slides/python-net/it/aspose.slides.smartart/ismartartnode/is_hidden/) | Restituisce true se questo nodo è un nodo nascosto nel modello dati.<br/>            Sola lettura **bool**. |
| [`organization_chart_layout`](/slides/python-net/it/aspose.slides.smartart/ismartartnode/organization_chart_layout/) | Restituisce o imposta il tipo di layout del diagramma organizzativo associato al nodo corrente.<br/>            Lettura/scrittura [`OrganizationChartLayoutType`](/slides/python-net/it/aspose.slides.smartart/organizationchartlayouttype). |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`remove(self)`](/slides/python-net/it/aspose.slides.smartart/ismartartnode/remove/#) | Rimuove il nodo corrente. |


### Vedi anche
* modulo [`aspose.slides.smartart`](/slides/python-net/it/aspose.slides.smartart)
* libreria [`Aspose.Slides`](/slides/python-net)