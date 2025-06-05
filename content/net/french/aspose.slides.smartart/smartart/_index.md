---
title: SmartArt
second_title: Référence API Aspose.Slides pour .NET
description: Représente un diagramme SmartArt
type: docs
weight: 10290
url: /fr/aspose.slides.smartart/smartart/
---

## Classe SmartArt

Représente un diagramme SmartArt

```csharp
public class SmartArt : GraphicalObject, ISmartArt
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AllNodes](../../aspose.slides.smartart/smartart/allnodes) { get; } | Retourne les collections de tous les nœuds de l'objet SmartArt. Lecture seule [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Retourne ou définit le texte alternatif associé à une forme. Lecture/écriture String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Retourne ou définit le titre du texte alternatif associé à une forme. Lecture/écriture String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La propriété spécifie comment une forme sera rendue en mode d'affichage noir et blanc. Lecture/écriture [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ColorStyle](../../aspose.slides.smartart/smartart/colorstyle) { get; set; } | Retourne ou définit le style de couleur de l'objet SmartArt. Lecture/écriture [`SmartArtColorType`](../smartartcolortype). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Retourne le nombre de sites de connexion sur la forme. Lecture seule Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Retourne les données personnalisées de la forme. Lecture seule [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Retourne l'objet EffectFormat qui contient les effets pixel appliqués à une forme. Remarque : peut retourner null pour certains types de formes qui n'ont pas de propriétés d'effet. Lecture seule [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Retourne l'objet FillFormat qui contient les propriétés de formatage de remplissage pour une forme. Remarque : peut retourner null pour certains types de formes qui n'ont pas de propriétés de remplissage. Lecture seule [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Retourne ou définit les propriétés du cadre de la forme. Lecture/écriture [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Retourne les verrous de la forme. Lecture seule [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Retourne ou définit la hauteur de la forme. Lecture/écriture Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Détermine si la forme est cachée. Lecture/écriture Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Retourne ou définit le lien hypertexte défini pour le clic de la souris. Lecture/écriture [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Retourne le gestionnaire de lien hypertexte. Lecture seule [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Retourne ou définit le lien hypertexte défini pour le survol de la souris. Lecture/écriture [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Obtient ou définit l'option 'Marquer comme décoratif' Lecture/écriture Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Détermine si la forme est regroupée. Lecture seule Boolean. |
| [IsReversed](../../aspose.slides.smartart/smartart/isreversed) { get; set; } | Retourne ou définit l'état du diagramme SmartArt concernant LTR (de gauche à droite) ou RTL (de droite à gauche), si le diagramme prend en charge l'inversion. Lecture/écriture Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Détermine si la forme est un TextHolder_PPT. Lecture seule Boolean. |
| [Layout](../../aspose.slides.smartart/smartart/layout) { get; set; } | Retourne ou définit la disposition de l'objet SmartArt. Lecture/écriture [`SmartArtLayoutType`](../smartartlayouttype). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Retourne l'objet LineFormat qui contient les propriétés de formatage de ligne pour une forme. Remarque : peut retourner null pour certains types de formes qui n'ont pas de propriétés de ligne. Lecture seule [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Retourne ou définit le nom d'une forme. Ne doit pas être null. Utilisez une chaîne vide si nécessaire. Lecture/écriture String. |
| [Nodes](../../aspose.slides.smartart/smartart/nodes) { get; } | Retourne les collections de nœuds racines dans l'objet SmartArt. Lecture seule [`ISmartArtNodeCollection`](../ismartartnodecollection). |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Obtient l'identifiant unique de la forme dans le contexte de la diapositive. Lecture seule UInt32. Voir également [`UniqueId`](../../aspose.slides/shape/uniqueid) pour obtenir l'identifiant unique de la forme dans le contexte de la présentation. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Retourne l'objet GroupShape parent si la forme est regroupée. Sinon, retourne null. Lecture seule [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Retourne le placeholder pour une forme. Retourne null si la forme n'a pas de placeholder. Lecture seule [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Retourne la présentation parent d'une diapositive. Lecture seule [`IPresentation`](../../aspose.slides/ipresentation). |
| [QuickStyle](../../aspose.slides.smartart/smartart/quickstyle) { get; set; } | Retourne ou définit le style rapide de l'objet SmartArt. Lecture/écriture [`SmartArtQuickStyleType`](../smartartquickstyletype). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Retourne ou définit les propriétés du cadre brut de la forme. Lecture/écriture [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Retourne ou définit le nombre de degrés de rotation de la forme spécifiée autour de l'axe z. Une valeur positive indique une rotation dans le sens des aiguilles d'une montre ; une valeur négative indique une rotation dans le sens inverse des aiguilles d'une montre. Lecture/écriture Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Retourne les verrous de la forme. Lecture seule [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 propriétés) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Retourne la diapositive parent d'une forme. Lecture seule [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Retourne l'objet ThreeDFormat qui contient les propriétés d'effet 3D pour une forme. Remarque : peut retourner null pour certains types de formes qui n'ont pas de propriétés 3D. Lecture seule [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Obtient l'identifiant unique de la forme dans le contexte de la présentation. Lecture seule UInt32. Voir également [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid) pour obtenir l'identifiant unique de la forme dans le contexte de la diapositive. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Retourne ou définit la largeur de la forme. Lecture/écriture Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Retourne ou définit la coordonnée x du coin supérieur gauche de la forme. Lecture/écriture Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Retourne ou définit la coordonnée y du coin supérieur gauche de la forme. Lecture/écriture Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Retourne la position d'une forme dans l'ordre z. Shapes[0] retourne la forme au fond de l'ordre z, et Shapes[Shapes.Count - 1] retourne la forme au devant de l'ordre z. Lecture seule Int32. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Ajoute un nouveau placeholder s'il n'y en a pas et définit les propriétés du placeholder à un spécifié. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Retourne une forme de placeholder de base (forme provenant de la disposition et/ou de la diapositive mère dont la forme actuelle est héritée). Un null est retourné si la forme actuelle n'est pas héritée. |
| [GetImage](../../aspose.slides/shape/getimage)() | Retourne la miniature de la forme. Le type de limites de miniature ShapeThumbnailBounds.Shape est utilisé par défaut. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Retourne la miniature de la forme. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Définit que cette forme n'est pas un placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Enregistre le contenu de la forme sous forme de fichier SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Enregistre le contenu de la forme sous forme de fichier SVG. |

### Voir aussi

* classe [GraphicalObject](../../aspose.slides/graphicalobject)
* interface [ISmartArt](../ismartart)
* namespace [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->