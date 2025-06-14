---  
title: GetSummarySection
second_title: Aspose.Slides für .NET API Referenz  
description: Gibt das Summary Zoom Section-Element für den angegebenen Abschnitt zurück.
type: docs
weight: 90  
url: /de/aspose.slides/summaryzoomsectioncollection/getsummarysection/
---  

## SummaryZoomSectionCollection.GetSummarySection-Methode  

Gibt das Summary Zoom Section-Element für den angegebenen Abschnitt zurück.  

```csharp  
public ISummaryZoomSection GetSummarySection(ISection section)  
```  

| Parameter | Typ | Beschreibung |  
| --- | --- | --- |  
| section | ISection | Abschnitt, um [`ISection`](../../isection) zu finden |  

### Rückgabewert  

[`ISummaryZoomSection`](../../isummaryzoomsection) oder null, wenn die Sammlung kein Element für den Abschnitt enthält.  

### Beispiele  

Das Beispiel zeigt, wie man das Summary Zoom Section-Element anhand des Indexes erhält:  

```csharp  
[C#]  
using (Presentation pres = new Presentation("pres.pptx"))  
{  
    ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame) pres.Slides[1].Shapes[0];  
    ISummaryZoomSectionCollection collection = zoomFrame.SummaryZoomCollection;  
    ISummaryZoomSection selectedObject = collection.GetSummarySection(pres.Sections[2]);  
}  
```  

### Siehe Auch  

* interface [ISummaryZoomSection](../../isummaryzoomsection)  
* interface [ISection](../../isection)  
* class [SummaryZoomSectionCollection](../../summaryzoomsectioncollection)  
* namespace [Aspose.Slides](../../summaryzoomsectioncollection)  
* assembly [Aspose.Slides](../../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  