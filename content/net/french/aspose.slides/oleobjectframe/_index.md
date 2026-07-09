---
title: OleObjectFrame
second_title: Référence API Aspose.Slides pour .NET
description: Représente un objet OLE sur une diapositive.
type: docs
weight: 9230
url: /fr/aspose.slides/oleobjectframe/
---
## classe OleObjectFrame

Représente un objet OLE sur une diapositive.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Renvoie ou définit le texte alternatif associé à une forme. Lecture/écriture String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Renvoie ou définit le titre du texte alternatif associé à une forme. Lecture/écriture String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | Permet d'obtenir l'interface de base IGraphicalObject. Lecture seule [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La propriété indique comment une forme sera affichée en mode noir et blanc. Lecture/écriture [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Renvoie le nombre de points de connexion sur la forme. Lecture seule Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Renvoie les données personnalisées de la forme. Lecture seule [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Renvoie l'objet EffectFormat qui contient les effets pixélisés appliqués à une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés d'effet. Lecture seule [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | Obtient ou définit les informations sur les données OLE embarquées. Lecture/écriture [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | Renvoie le nom de fichier de l'objet OLE embarqué |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | Renvoie le chemin de l'objet OLE embarqué |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Renvoie l'objet FillFormat qui contient les propriétés de remplissage d'une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés de remplissage. Lecture seule [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Renvoie ou définit les propriétés du cadre de forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Renvoie les verrous de la forme. Lecture seule [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Obtient ou définit la hauteur de la forme, mesurée en points. Lecture/écriture Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Détermine si la forme est masquée. Lecture/écriture Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Renvoie ou définit le lien hypertexte défini pour le clic de souris. Lecture/écriture [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Renvoie le gestionnaire de lien hypertexte. Lecture seule [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Renvoie ou définit le lien hypertexte défini pour le survol de la souris. Lecture/écriture [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Obtient ou définit l'option 'Mark as decorative'. Lecture/écriture Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Détermine si la forme est groupée. Lecture seule Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | Détermine si un objet est visible sous forme d'icône. Lecture/écriture Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | Détermine si un objet est lié à un fichier externe. Lecture seule Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Détermine si la forme est TextHolder_PPT. Lecture seule Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Renvoie l'objet LineFormat qui contient les propriétés de format de ligne d'une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés de ligne. Lecture seule [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | Renvoie le chemin complet d'un fichier lié. Le nom de fichier court sera utilisé. Lecture seule String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | Renvoie le chemin complet d'un fichier lié. Le nom de fichier long sera utilisé. Lecture/écriture String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | Renvoie le chemin relatif d'un fichier lié s'il existe, sinon renvoie une chaîne vide. Lecture seule String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Renvoie ou définit le nom d'une forme. Ne doit pas être nul. Utilisez une chaîne vide si nécessaire. Lecture/écriture String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | Renvoie ou définit le nom d'un objet. Lecture/écriture String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | Renvoie le ProgID d'un objet. Lecture seule String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Renvoie un identifiant unique limité à la diapositive qui reste constant pendant la durée de vie de la forme et permet à PowerPoint ou au code d'interopérabilité de référencer de manière fiable la forme depuis n'importe où dans le document. Lecture seule UInt32. Voir aussi [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Renvoie l'objet GroupShape parent si la forme est groupée. Sinon renvoie null. Lecture seule [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Renvoie l'espace réservé d'une forme. Renvoie null si la forme n'a pas d'espace réservé. Lecture seule [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Renvoie la présentation parente d'une diapositive. Lecture seule [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Renvoie ou définit les propriétés du cadre brut de forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Renvoie ou définit le nombre de degrés de rotation de la forme spécifiée autour de l'axe z. Une valeur positive indique une rotation horaire ; une valeur négative indique une rotation antihoraire. Lecture/écriture Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Renvoie les verrous de la forme. Lecture seule [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 propriétés) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Renvoie la diapositive parente d'une forme. Lecture seule [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | Renvoie l'objet des propriétés de remplissage d'image OleObject. Lecture seule [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | Renvoie ou définit le titre de l'icône OleObject. Lecture/écriture String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Renvoie l'objet ThreeDFormat qui contient les propriétés d'effet 3D pour une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés 3D. Lecture seule [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Renvoie un identifiant interne limité à la présentation destiné à être utilisé par des add-ins ou autre code. Étant donné que cette valeur peut être réassignée par l'utilisateur ou programmatiquement, elle ne doit pas être considérée comme une clé unique persistante. Lecture seule UInt32. Voir aussi [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | Détermine si l'objet embarqué lié est mis à jour automatiquement lorsque la présentation est ouverte ou imprimée. Lecture/écriture Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Obtient ou définit la largeur de la forme, mesurée en points. Lecture/écriture Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Obtient ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points. Lecture/écriture Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Obtient ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points. Lecture/écriture Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Renvoie la position d'une forme dans l'ordre Z. Shapes[0] renvoie la forme à l'arrière de l'ordre Z, et Shapes[Shapes.Count - 1] renvoie la forme à l'avant de l'ordre Z. Lecture seule Int32. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Ajoute un nouvel espace réservé s'il n'existe pas et définit les propriétés de l'espace réservé à un spécifié. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Renvoie une forme d'espace réservé de base (forme provenant de la disposition et/ou de la diapositive maître dont la forme actuelle hérite). Retourne null si la forme actuelle n'hérite pas. |
| [GetImage](../../aspose.slides/shape/getimage)() | Renvoie la miniature de la forme. Le type ShapeThumbnailBounds.Shape est utilisé par défaut pour les limites de la miniature. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Renvoie la miniature de la forme. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Obtient les limites visuelles de la forme calculées à partir de son contenu rendu. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Définit que cette forme n'est pas un espace réservé. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | Définit les informations sur les données OLE embarquées. Cette méthode modifie les propriétés de l'objet pour refléter les nouvelles données et définit le drapeau IsObjectLink sur false, indiquant que l'objet OLE est embarqué. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Enregistre le contenu de la forme en fichier SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Enregistre le contenu de la forme en fichier SVG. |

### Exemples

L'exemple suivant montre comment accéder aux cadres d'objets OLE.

```csharp
[C#]
// Charge le fichier PPTX dans un objet présentation
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // Accède à la première diapositive
    ISlide sld = pres.Slides[0];
    // Convertit la forme en OleObjectFrame
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // Lit l'objet OLE et l'écrit sur le disque
    if (oleObjectFrame != null)
    {
        // Obtient les données du fichier embarqué
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // Obtient l'extension du fichier embarqué
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // Crée un chemin pour enregistrer le fichier extrait
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // Enregistre les données extraites
        using (FileStream fstr = new FileStream(extractedPath, FileMode.Create, FileAccess.Write))
        {
            fstr.Write(data, 0, data.Length);
        }
    }
}
```

### Voir aussi

* classe [GraphicalObject](../graphicalobject)
* interface [IOleObjectFrame](../ioleobjectframe)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->