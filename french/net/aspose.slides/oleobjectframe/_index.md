---
title: OleObjectFrame
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente un objet OLE sur une diapositive.
type: docs
weight: 8530
url: /fr/net/aspose.slides/oleobjectframe/
---
## OleObjectFrame class

Représente un objet OLE sur une diapositive.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Renvoie ou définit le texte alternatif associé à une forme. Lecture/écritureString . |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Renvoie ou définit le titre du texte alternatif associé à une forme. Lecture/écritureString . |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | Permet d'obtenir l'interface IGraphicalObject de base. Lecture seule[`IGraphicalObject`](../igraphicalobject) . |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La propriété spécifie comment une forme sera rendue en mode d'affichage en noir et blanc.. Lecture/écriture[`BlackWhiteMode`](../blackwhitemode) . |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Renvoie le nombre de sites de connexion sur la forme. Lecture seuleInt32 . |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Renvoie les données personnalisées de la forme. Lecture seule[`ICustomData`](../icustomdata) . |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Renvoie l'objet EffectFormat qui contient les effets de pixel appliqués à une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés d'effet. Lecture seule[`IEffectFormat`](../ieffectformat) . |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | Obtient ou définit des informations sur les données intégrées OLE. Lecture/écriture[`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo) . |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | Renvoie le nom de fichier de l'objet OLE intégré |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | Renvoie le chemin de l'objet OLE intégré |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Renvoie l'objet FillFormat qui contient les propriétés de formatage de remplissage pour une forme. Remarque : peut renvoyer la valeur null pour certains types de formes qui n'ont pas de propriétés de remplissage. Lecture seule[`IFillFormat`](../ifillformat) . |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Renvoie ou définit les propriétés du cadre de forme. Lecture/écriture[`IShapeFrame`](../ishapeframe) . |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Renvoie les verrous de la forme. Lecture seule[`IGraphicalObjectLock`](../igraphicalobjectlock) . |
| [Height](../../aspose.slides/shape/height) { get; set; } | Renvoie ou définit la hauteur de la forme. Lecture/écritureSingle . |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Détermine si la forme est masquée. Lecture/écritureBoolean . |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Renvoie ou définit le lien hypertexte défini pour le clic de souris. Lecture/écriture[`IHyperlink`](../ihyperlink) . |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Renvoie le gestionnaire de liens hypertexte. Lecture seule[`IHyperlinkManager`](../ihyperlinkmanager) . |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Renvoie ou définit le lien hypertexte défini pour le survol de la souris. Lecture/écriture[`IHyperlink`](../ihyperlink) . |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Détermine si la forme est groupée. Lecture seuleBoolean . |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | Détermine si un objet est visible sous forme d'icône. Lecture/écritureBoolean . |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | Détermine si un objet est lié à un fichier externe. Lecture seuleBoolean . |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Détermine si la forme est TextHolder_PPT. Lecture seuleBoolean . |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Renvoie l'objet LineFormat qui contient les propriétés de mise en forme des lignes pour une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés de ligne. Lecture seule[`ILineFormat`](../ilineformat) . |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | Renvoie le chemin complet vers un fichier lié. Le nom de fichier court sera utilisé. Lecture seuleString . |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | Renvoie le chemin complet vers un fichier lié. Le nom de fichier long sera utilisé. Lecture/écritureString . |
| [Name](../../aspose.slides/shape/name) { get; set; } | Renvoie ou définit le nom d'une forme. Doit être non nul. Utilisez une valeur de chaîne vide si nécessaire. Lecture/écritureString . |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | Renvoie ou définit le nom d'un objet. Lecture/écritureString . |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | Renvoie le ProgID d'un objet. Lecture seuleString . |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Obtient un identifiant de forme unique dans la portée de la diapositive. Lecture seuleUInt32 . Voir aussi[`UniqueId`](../shape/uniqueid) pour obtenir un identifiant de forme unique dans la portée de la présentation. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Renvoie l'objet GroupShape parent si la forme est groupée. Sinon renvoie null. Lecture seule[`IGroupShape`](../igroupshape) . |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Renvoie l'espace réservé pour une forme. Renvoie null si la forme n'a pas d'espace réservé. Lecture seule[`IPlaceholder`](../iplaceholder) . |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Renvoie la présentation parent d'une diapositive. Lecture seule[`IPresentation`](../ipresentation) . |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Renvoie ou définit les propriétés du cadre de forme brute. Lecture/écriture[`IShapeFrame`](../ishapeframe) . |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour de l'axe z. Une valeur positive indique une rotation dans le sens des aiguilles d'une montre ; une valeur négative indique une rotation dans le sens inverse des aiguilles d'une montre. Lecture/écritureSingle . |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Renvoie les verrous de la forme. Lecture seule[`IGraphicalObjectLock`](../igraphicalobjectlock) . (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Renvoie la diapositive parent d'une forme. Lecture seule[`IBaseSlide`](../ibaseslide) . |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | Renvoie l'objet de propriétés de remplissage d'image OleObject. Lecture seule[`IPictureFillFormat`](../ipicturefillformat) . |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | Renvoie ou définit le titre de l'icône OleObject. Lecture/écritureString . |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Renvoie l'objet ThreeDFormat qui applique les propriétés d'effet 3D à une forme. Remarque : peut renvoyer la valeur null pour certains types de formes qui n'ont pas de propriétés 3D. Lecture seule[`IThreeDFormat`](../ithreedformat) . |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Obtient un identifiant de forme unique dans la portée de la présentation. Lecture seuleUInt32 . Voir aussi[`OfficeInteropShapeId`](../shape/officeinteropshapeid) pour obtenir un identifiant de forme unique dans la portée de la diapositive. |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | Détermine si l'objet incorporé lié est automatiquement mis à jour lorsque la présentation est ouverte ou imprimée. Lecture/écritureBoolean . |
| [Width](../../aspose.slides/shape/width) { get; set; } | Renvoie ou définit la largeur de la forme. Lecture/écritureSingle . |
| [X](../../aspose.slides/shape/x) { get; set; } | Renvoie ou définit la coordonnée x du coin supérieur gauche de la forme. Lecture/écritureSingle . |
| [Y](../../aspose.slides/shape/y) { get; set; } | Renvoie ou définit la coordonnée y du coin supérieur gauche de la forme. Lecture/écritureSingle . |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Renvoie la position d'une forme dans l'ordre z. Shapes[0] renvoie la forme à l'arrière de l'ordre z, et Shapes[Shapes.Count - 1] renvoie la forme à l'avant de l'ordre z- commande. Lecture seuleInt32 . |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Ajoute un nouvel espace réservé s'il n'y en a pas et définit les propriétés de l'espace réservé sur celles spécifiées. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)() | Renvoie la miniature de la forme. ShapeThumbnailBounds.Le type de limite de la miniature de la forme est utilisé par défaut. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)(ShapeThumbnailBounds, float, float) | Renvoie la vignette de la forme. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Définit que cette forme n'est pas un espace réservé. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | Définit les informations sur les données intégrées OLE.  Cette méthode modifie les propriétés de l'objet pour refléter les nouvelles données et définit l'indicateur IsObjectLink sur false, indiquant que l'objet OLE est intégré. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Enregistre le contenu de Shape en tant que fichier SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Enregistre le contenu de Shape en tant que fichier SVG. |

### Voir également

* class [GraphicalObject](../graphicalobject)
* interface [IOleObjectFrame](../ioleobjectframe)
* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
