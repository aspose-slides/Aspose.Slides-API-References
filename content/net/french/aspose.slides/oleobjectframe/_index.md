---
title: OleObjectFrame
second_title: Référence API Aspose.Slides pour .NET
description: Représente un objet OLE sur une diapositive.
type: docs
weight: 8960
url: /fr/aspose.slides/oleobjectframe/
---

## Classe CadreObjetOLE

Représente un objet OLE sur une diapositive.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Renvoie ou définit le texte alternatif associé à une forme. Lecture/écriture String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Renvoie ou définit le titre du texte alternatif associé à une forme. Lecture/écriture String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | Permet d'obtenir l'interface de base IGraphicalObject. Lecture seule [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La propriété spécifie comment une forme sera rendue en mode d'affichage noir et blanc. Lecture/écriture [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Renvoie le nombre de sites de connexion sur la forme. Lecture seule Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Renvoie les données personnalisées de la forme. Lecture seule [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Renvoie l'objet EffectFormat qui contient les effets de pixel appliqués à une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés d'effet. Lecture seule [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | Obtient ou définit des informations sur les données OLE intégrées. Lecture/écriture [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | Renvoie le nom de fichier de l'objet OLE intégré |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | Renvoie le chemin de l'objet OLE intégré |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Renvoie l'objet FillFormat qui contient les propriétés de formatage de remplissage pour une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés de remplissage. Lecture seule [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Renvoie ou définit les propriétés du cadre de la forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Renvoie les verrous de la forme. Lecture seule [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Renvoie ou définit la hauteur de la forme. Lecture/écriture Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Détermine si la forme est cachée. Lecture/écriture Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Renvoie ou définit le lien hypertexte défini pour un clic de souris. Lecture/écriture [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Renvoie le gestionnaire de lien hypertexte. Lecture seule [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Renvoie ou définit le lien hypertexte défini pour le survol de souris. Lecture/écriture [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Obtient ou définit l'option 'Marquer comme décoratif' Lecture/écriture Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Détermine si la forme est groupée. Lecture seule Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | Détermine si un objet est visible en tant qu'icône. Lecture/écriture Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | Détermine si un objet est lié à un fichier externe. Lecture seule Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Détermine si la forme est un TextHolder_PPT. Lecture seule Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Renvoie l'objet LineFormat qui contient les propriétés de formatage de ligne pour une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés de ligne. Lecture seule [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | Renvoie le chemin complet vers un fichier lié. Un nom de fichier court sera utilisé. Lecture seule String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | Renvoie le chemin complet vers un fichier lié. Un nom de fichier long sera utilisé. Lecture/écriture String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | Renvoie le chemin relatif vers un fichier lié s'il est présent, sinon renvoie une chaîne vide. Lecture seule String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Renvoie ou définit le nom d'une forme. Ne doit pas être null. Utilisez une valeur de chaîne vide si nécessaire. Lecture/écriture String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | Renvoie ou définit le nom d'un objet. Lecture/écriture String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | Renvoie le ProgID d'un objet. Lecture seule String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Obtient l'identifiant unique de la forme dans le cadre de la diapositive. Lecture seule UInt32. Voir aussi [`UniqueId`](../shape/uniqueid) pour obtenir l'identifiant unique de la forme dans le cadre de la présentation. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Renvoie l'objet GroupShape parent si la forme est groupée. Sinon, renvoie null. Lecture seule [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Renvoie le placeholder pour une forme. Renvoie null si la forme n'a pas de placeholder. Lecture seule [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Renvoie la présentation parente d'une diapositive. Lecture seule [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Renvoie ou définit les propriétés du cadre brut de la forme. Lecture/écriture [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Renvoie ou définit le nombre de degrés auxquels la forme spécifiée est tournée autour de l'axe z. Une valeur positive indique une rotation dans le sens des aiguilles d'une montre ; une valeur négative indique une rotation dans le sens inverse des aiguilles d'une montre. Lecture/écriture Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Renvoie les verrous de la forme. Lecture seule [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 propriétés) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Renvoie la diapositive parente d'une forme. Lecture seule [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | Renvoie les propriétés de remplissage d'image de l'OleObject. Lecture seule [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | Renvoie ou définit le titre de l'icône OleObject. Lecture/écriture String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Renvoie l'objet ThreeDFormat qui contient les propriétés d'effet 3D pour une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés 3D. Lecture seule [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Obtient l'identifiant unique de la forme dans le cadre de la présentation. Lecture seule UInt32. Voir aussi [`OfficeInteropShapeId`](../shape/officeinteropshapeid) pour obtenir l'identifiant unique de la forme dans le cadre de la diapositive. |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | Détermine si l'objet intégré lié est automatiquement mis à jour lors de l'ouverture ou de l'impression de la présentation. Lecture/écriture Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Renvoie ou définit la largeur de la forme. Lecture/écriture Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Renvoie ou définit la coordonnée x du coin supérieur gauche de la forme. Lecture/écriture Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Renvoie ou définit la coordonnée y du coin supérieur gauche de la forme. Lecture/écriture Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Renvoie la position d'une forme dans l'ordre z. Shapes[0] renvoie la forme à l'arrière de l'ordre z, et Shapes[Shapes.Count - 1] renvoie la forme à l'avant de l'ordre z. Lecture seule Int32. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Ajoute un nouveau placeholder s'il n'y en a pas et définit les propriétés du placeholder à un spécifié. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Renvoie une forme de placeholder de base (forme provenant de la mise en page et/ou de la diapositive maître dont la forme actuelle hérite). Un null est renvoyé si la forme actuelle n'est pas héritée. |
| [GetImage](../../aspose.slides/shape/getimage)() | Renvoie la miniatures de la forme. Le type de limites ShapeThumbnailBounds.Shape est utilisé par défaut. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Renvoie la miniature de la forme. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Définit que cette forme n'est pas un placeholder. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | Définit des informations sur les données OLE intégrées. Cette méthode modifie les propriétés de l'objet pour refléter les nouvelles données et définit le drapeau IsObjectLink sur false, indiquant que l'objet OLE est intégré. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Enregistre le contenu de la forme en tant que fichier SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Enregistre le contenu de la forme en tant que fichier SVG. |

### Exemples

L'exemple suivant montre comment accéder aux cadres d'objet OLE.

```csharp
[C#]
// Charge le PPTX dans un objet présentation
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // Accède à la première diapositive
    ISlide sld = pres.Slides[0];
    // Cast la forme en CadreObjetOLE
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // Lit l'objet OLE et l'écrit sur le disque
    if (oleObjectFrame != null)
    {
        // Obtient les données du fichier intégré
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // Obtient l'extension du fichier intégré
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

### Voir Aussi

* class [GraphicalObject](../graphicalobject)
* interface [IOleObjectFrame](../ioleobjectframe)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->