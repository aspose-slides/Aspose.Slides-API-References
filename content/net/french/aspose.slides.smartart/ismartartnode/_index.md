---  
title: ISmartArtNode
second_title: Aspose.Slides pour la référence API .NET  
description: Représente un nœud d'un diagramme SmartArt.
type: docs  
weight: 10240  
url: /fr/aspose.slides.smartart/ismartartnode/
---  

## Interface ISmartArtNode  

Représente un nœud d'un diagramme SmartArt.  

```csharp  
public interface ISmartArtNode  
```  

## Propriétés  

| Nom | Description |  
| --- | --- |  
| [BulletFillFormat](../../aspose.slides.smartart/ismartartnode/bulletfillformat) { get; } | Renvoie l'objet FillFormat qui contient les propriétés de formatage de remplissage pour une puce de nœud. Remarque : peut renvoyer null pour certains types de mise en page SmartArt qui ne fournissent pas de puces pour les nœuds. Lecture seule [`IFillFormat`](../../aspose.slides/ifillformat). |  
| [ChildNodes](../../aspose.slides.smartart/ismartartnode/childnodes) { get; } | Renvoie les collections de tous les nœuds enfants du nœud actuel. Lecture seule [`ISmartArtNodeCollection`](../ismartartnodecollection). |  
| [IsAssistant](../../aspose.slides.smartart/ismartartnode/isassistant) { get; set; } | Renvoie ou définit le nœud comme assistant. Écriture/lecture Booléen. |  
| [IsHidden](../../aspose.slides.smartart/ismartartnode/ishidden) { get; } | Renvoie true si ce nœud est un nœud caché dans le modèle de données. Lecture seule Booléen. |  
| [Level](../../aspose.slides.smartart/ismartartnode/level) { get; } | Renvoie le niveau d'imbrication du nœud. Lecture seule Int32. |  
| [OrganizationChartLayout](../../aspose.slides.smartart/ismartartnode/organizationchartlayout) { get; set; } | Renvoie ou définit le type de mise en page de l'organigramme associé au nœud actuel. Écriture/lecture [`OrganizationChartLayoutType`](../organizationchartlayouttype). |  
| [Position](../../aspose.slides.smartart/ismartartnode/position) { get; set; } | Renvoie ou définit la position de base zéro du nœud parmi les nœuds frères. Écriture/lecture Int32. |  
| [Shapes](../../aspose.slides.smartart/ismartartnode/shapes) { get; } | Renvoie les collections de toutes les formes associées au nœud. Lecture seule [`ISmartArtShapeCollection`](../ismartartshapecollection). |  
| [TextFrame](../../aspose.slides.smartart/ismartartnode/textframe) { get; } | Renvoie ou définit le texte du nœud. Lecture seule [`ITextFrame`](../../aspose.slides/itextframe). |  

## Méthodes  

| Nom | Description |  
| --- | --- |  
| [Remove](../../aspose.slides.smartart/ismartartnode/remove)() | Supprime le nœud actuel. |  

### Voir aussi  

* espace de noms [Aspose.Slides.SmartArt](../../aspose.slides.smartart)  
* assembly [Aspose.Slides](../../)  

<!-- NE PAS ÉDITER : généré par xmldocmd pour Aspose.Slides.dll -->  