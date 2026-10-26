---
title: Shape
second_title: Aspose.Sildes pour PHP via la référence de l'API Java
description: 
type: docs
url: /fr/aspose.slides/shape/
---
## Classe Shape

  Représente une forme sur une diapositive.
 
### addPlaceholder {#addPlaceholder}

| Nom | Description |
| --- | --- |
| addPlaceholder ([Placeholder](../placeholder)) | Ajoute un nouvel espace réservé s'il n'existe pas et définit les propriétés de l'espace réservé à un spécifié. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| placeholderToCopyFrom | [Placeholder](../placeholder) | Espace réservé dont le contenu est copié. |

**Retour :**
[Placeholder](../placeholder)

---

### getAlternativeText {#getAlternativeText}

| Nom | Description |
| --- | --- |
| getAlternativeText () | Renvoie ou définit le texte alternatif associé à une forme. Lecture/écriture String. |

**Retour :**
String

---

### getAlternativeTextTitle {#getAlternativeTextTitle}

| Nom | Description |
| --- | --- |
| getAlternativeTextTitle () | Renvoie ou définit le titre du texte alternatif associé à une forme. Lecture/écriture String. |

**Retour :**
String

---

### getBasePlaceholder {#getBasePlaceholder}

| Nom | Description |
| --- | --- |
| getBasePlaceholder () | Renvoie une forme d'espace réservé de base (forme provenant de la disposition et/ou de la diapositive principale dont la forme actuelle est héritée). Retourne null si la forme actuelle n'est pas héritée. |

**Retour :**
[GraphicalObject](../graphicalobject), [Connector](../connector), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [SummaryZoomFrame](../summaryzoomframe), [GeometryShape](../geometryshape), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [PictureFrame](../pictureframe), [SectionZoomFrame](../sectionzoomframe), [Chart](../chart), [AudioFrame](../audioframe), [ZoomObject](../zoomobject), [LegacyDiagram](../legacydiagram)

---

### getBlackWhiteMode {#getBlackWhiteMode}

| Nom | Description |
| --- | --- |
| getBlackWhiteMode () | Propriété spécifiant comment une forme sera rendue en mode noir et blanc. Lecture/écriture BlackWhiteMode. |

**Retour :**
byte

---

### getConnectionSiteCount {#getConnectionSiteCount}

| Nom | Description |
| --- | --- |
| getConnectionSiteCount () | Renvoie le nombre de sites de connexion sur la forme. Lecture seule int. |

**Retour :**
int

---

### getCustomData {#getCustomData}

| Nom | Description |
| --- | --- |
| getCustomData () | Renvoie les données personnalisées de la forme. Lecture seule ICustomData. |

**Retour :**
[CustomData](../customdata)

---

### getEffectFormat {#getEffectFormat}

| Nom | Description |
| --- | --- |
| getEffectFormat () | Renvoie l'objet EffectFormat qui contient les effets de pixels appliqués à une forme. Remarque : peut retourner null pour certains types de formes qui n'ont pas de propriétés d'effet. Lecture seule IEffectFormat. |

**Retour :**
[EffectFormat](../effectformat)

---

### getFillFormat {#getFillFormat}

| Nom | Description |
| --- | --- |
| getFillFormat () | Renvoie l'objet FillFormat qui contient les propriétés de remplissage d'une forme. Remarque : peut retourner null pour certains types de formes qui n'ont pas de propriétés de remplissage. Lecture seule IFillFormat. |

**Retour :**
[FillFormat](../fillformat)

---

### getFrame {#getFrame}

| Nom | Description |
| --- | --- |
| getFrame () | Renvoie ou définit les propriétés du cadre de la forme. Lecture/écriture IShapeFrame. La valeur de chaque propriété de l'instance IShapeFrame renvoyée n'est pas indéfinie (n'est pas NaN ou NotDefined). La valeur de chaque propriété de l'instance IShapeFrame assignée doit être définie (ne doit pas être NaN ou NotDefined). Vous pouvez affecter des valeurs indéfinies aux propriétés de l'instance RawFrame. |

**Retour :**
[ShapeFrame](../shapeframe)

---

### getHeight {#getHeight}

| Nom | Description |
| --- | --- |
| getHeight () | Obtient ou définit la hauteur de la forme, mesurée en points. Lecture/écriture float. La valeur retournée est toujours définie et n'est jamais Float.NaN. La valeur assignée doit également être définie ; affectez Float.NaN uniquement aux propriétés d'une instance RawFrame. |

**Retour :**
float

---

### getHidden {#getHidden}

| Nom | Description |
| --- | --- |
| getHidden () | Détermine si la forme est masquée. Lecture/écriture boolean. |

**Retour :**
boolean

---

### getHyperlinkClick {#getHyperlinkClick}

| Nom | Description |
| --- | --- |
| getHyperlinkClick () | Renvoie ou définit le lien hypertexte défini pour le clic de la souris. Lecture/écriture IHyperlink. |

**Retour :**
[Hyperlink](../hyperlink)

---

### getHyperlinkManager {#getHyperlinkManager}

| Nom | Description |
| --- | --- |
| getHyperlinkManager () | Renvoie le gestionnaire de liens hypertexte. Lecture seule IHyperlinkManager. |

**Retour :**
[HyperlinkManager](../hyperlinkmanager)

---

### getHyperlinkMouseOver {#getHyperlinkMouseOver}

| Nom | Description |
| --- | --- |
| getHyperlinkMouseOver () | Renvoie ou définit le lien hypertexte défini pour le survol de la souris. Lecture/écriture IHyperlink. |

**Retour :**
[Hyperlink](../hyperlink)

---

### getImage {#getImage}

| Nom | Description |
| --- | --- |
| getImage () | Renvoie la vignette de la forme. Le type ShapeThumbnailBounds.Shape est utilisé par défaut pour les limites de la vignette. |

**Retour :**
IImage

---

### getImage {#getImage}

| Nom | Description |
| --- | --- |
| getImage (int, float, float) | Renvoie la vignette de la forme. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| bounds | int | Type des limites de la vignette de forme. |
| scaleX | float | Échelle X |
| scaleY | float | Échelle Y |

**Retour :**
IImage

---

### getLineFormat {#getLineFormat}

| Nom | Description |
| --- | --- |
| getLineFormat () | Renvoie l'objet LineFormat qui contient les propriétés de format de ligne d'une forme. Remarque : peut retourner null pour certains types de formes qui n'ont pas de propriétés de ligne. Lecture seule ILineFormat. |

**Retour :**
[LineFormat](../lineformat)

---

### getName {#getName}

| Nom | Description |
| --- | --- |
| getName () | Renvoie ou définit le nom d'une forme. Doit être non nul. Utilisez une chaîne vide si nécessaire. Lecture/écriture String. |

**Retour :**
String

---

### getOfficeInteropShapeId {#getOfficeInteropShapeId}

| Nom | Description |
| --- | --- |
| getOfficeInteropShapeId () | Renvoie un identifiant unique limité à la diapositive qui reste constant pendant toute la durée de vie de la forme et permet à PowerPoint ou à du code d'interopérabilité de référencer la forme de manière fiable depuis n'importe où dans le document. Lecture seule long. Voir aussi #getUniqueId. |

**Retour :**
long

---

### getParentGroup {#getParentGroup}

| Nom | Description |
| --- | --- |
| getParentGroup () | Renvoie l'objet GroupShape parent si la forme est groupée. Sinon retourne null. Lecture seule IGroupShape. La propriété #isGrouped détermine si la forme est groupée. |

**Retour :**
[GroupShape](../groupshape)

---

### getPlaceholder {#getPlaceholder}

| Nom | Description |
| --- | --- |
| getPlaceholder () | Renvoie l'espace réservé d'une forme. Retourne null si la forme n'a pas d'espace réservé. Lecture seule IPlaceholder. |

**Retour :**
[Placeholder](../placeholder)

---

### getPresentation {#getPresentation}

| Nom | Description |
| --- | --- |
| getPresentation () | Renvoie la présentation parente d'une diapositive. Lecture seule IPresentation. |

**Retour :**
[Presentation](../presentation)

---

### getRawFrame {#getRawFrame}

| Nom | Description |
| --- | --- |
| getRawFrame () | Renvoie ou définit les propriétés brutes du cadre de la forme. Lecture/écriture IShapeFrame. |

**Retour :**
[ShapeFrame](../shapeframe)

---

### getRotation {#getRotation}

| Nom | Description |
| --- | --- |
| getRotation () | Renvoie ou définit le nombre de degrés dont la forme spécifiée est pivotée autour de l'axe z. Une valeur positive indique une rotation horaire ; une valeur négative indique une rotation antihoraire. Lecture/écriture float. La valeur retournée est toujours définie (n'est pas Float.NaN). La valeur assignée doit être définie (pas Float.NaN). Vous pouvez affecter des valeurs indéfinies aux propriétés d'une instance RawFrame. |

**Retour :**
float

---

### getShapeLock {#getShapeLock}

| Nom | Description |
| --- | --- |
| getShapeLock () | Renvoie les verrous de la forme. Lecture seule IBaseShapeLock. |

**Retour :**
[GraphicalObjectLock](../graphicalobjectlock), [ConnectorLock](../connectorlock), [AutoShapeLock](../autoshapelock), [PictureFrameLock](../pictureframelock), [BaseShapeLock](../baseshapelock), [GroupShapeLock](../groupshapelock)

---

### getSlide {#getSlide}

| Nom | Description |
| --- | --- |
| getSlide () | Renvoie la diapositive parente d'une forme. Lecture seule IBaseSlide. |

**Retour :**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)

---

### getThreeDFormat {#getThreeDFormat}

| Nom | Description |
| --- | --- |
| getThreeDFormat () | Renvoie l'objet ThreeDFormat qui contient les propriétés d'effet 3D d'une forme. Remarque : peut retourner null pour certains types de formes qui n'ont pas de propriétés 3D. Lecture seule IThreeDFormat. |

**Retour :**
[ThreeDFormat](../threedformat)

---

### getUniqueId {#getUniqueId}

| Nom | Description |
| --- | --- |
| getUniqueId () | Renvoie un identifiant interne limité à la présentation destiné à être utilisé par des compléments ou autre code. Comme cette valeur peut être réassignée par l'utilisateur ou programmatiquement, elle ne doit pas être considérée comme une clé unique persistante. Lecture seule long. Voir aussi #getOfficeInteropShapeId. |

**Retour :**
long

---

### getVisualBounds {#getVisualBounds}

| Nom | Description |
| --- | --- |
| getVisualBounds () | Obtient les limites visuelles de la forme calculées à partir de son contenu rendu. |

**Retour :**
Rectangle2D.Float

---

### getWidth {#getWidth}

| Nom | Description |
| --- | --- |
| getWidth () | Obtient ou définit la largeur de la forme, mesurée en points. Lecture/écriture float. La valeur retournée est toujours définie et n'est jamais Float.NaN. La valeur assignée doit également être définie ; affectez Float.NaN uniquement aux propriétés d'une instance RawFrame. |

**Retour :**
float

---

### getX {#getX}

| Nom | Description |
| --- | --- |
| getX () | Obtient ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points. Lecture/écriture float. La valeur retournée est toujours définie et n'est jamais Float.NaN. La valeur assignée doit également être définie ; affectez Float.NaN uniquement aux propriétés d'une instance RawFrame. |

**Retour :**
float

---

### getY {#getY}

| Nom | Description |
| --- | --- |
| getY () | Obtient ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points. Lecture/écriture float. La valeur retournée est toujours définie et n'est jamais Float.NaN. La valeur assignée doit également être définie ; affectez Float.NaN uniquement aux propriétés d'une instance RawFrame. |

**Retour :**
float

---

### getZOrderPosition {#getZOrderPosition}

| Nom | Description |
| --- | --- |
| getZOrderPosition () | Renvoie la position d'une forme dans l'ordre Z. Shapes[0] renvoie la forme la plus en arrière de l'ordre Z, et Shapes[Shapes.Count - 1] renvoie la forme la plus en avant de l'ordre Z. Lecture seule int. |

**Retour :**
int

---

### isDecorative {#isDecorative}

| Nom | Description |
| --- | --- |
| isDecorative () | Obtient ou définit l'option « Marquer comme décoratif ». Lecture/écriture boolean. |

**Retour :**
boolean

---

### isGrouped {#isGrouped}

| Nom | Description |
| --- | --- |
| isGrouped () | Détermine si la forme est groupée. Lecture seule boolean. La propriété #getParentGroup renvoie l'objet GroupShape parent si la forme est groupée. |

**Retour :**
boolean

---

### isTextHolder {#isTextHolder}

| Nom | Description |
| --- | --- |
| isTextHolder () | Détermine si la forme est TextHolder_PPT. Lecture seule boolean. |

**Retour :**
boolean

---

### removePlaceholder {#removePlaceholder}

| Nom | Description |
| --- | --- |
| removePlaceholder () | Définit que cette forme n'est pas un espace réservé. |

**Retour :**
void

---

### setAlternativeText {#setAlternativeText}

| Nom | Description |
| --- | --- |
| setAlternativeText (String) | Renvoie ou définit le texte alternatif associé à une forme. Lecture/écriture String. |

**Retour :**
void

---

### setAlternativeTextTitle {#setAlternativeTextTitle}

| Nom | Description |
| --- | --- |
| setAlternativeTextTitle (String) | Renvoie ou définit le titre du texte alternatif associé à une forme. Lecture/écriture String. |

**Retour :**
void

---

### setBlackWhiteMode {#setBlackWhiteMode}

| Nom | Description |
| --- | --- |
| setBlackWhiteMode (byte) | Propriété spécifiant comment une forme sera rendue en mode noir et blanc. Lecture/écriture BlackWhiteMode. |

**Retour :**
void

---

### setDecorative {#setDecorative}

| Nom | Description |
| --- | --- |
| setDecorative (boolean) | Obtient ou définit l'option « Marquer comme décoratif ». Lecture/écriture boolean. |

**Retour :**
void

---

### setFrame {#setFrame}

| Nom | Description |
| --- | --- |
| setFrame ([ShapeFrame](../shapeframe)) | Renvoie ou définit les propriétés du cadre de la forme. Lecture/écriture IShapeFrame. La valeur de chaque propriété de l'instance IShapeFrame renvoyée n'est pas indéfinie (n'est pas NaN ou NotDefined). La valeur de chaque propriété de l'instance IShapeFrame assignée doit être définie (ne doit pas être NaN ou NotDefined). Vous pouvez affecter des valeurs indéfinies aux propriétés de l'instance RawFrame. |

**Retour :**
void

---

### setHeight {#setHeight}

| Nom | Description |
| --- | --- |
| setHeight (float) | Obtient ou définit la hauteur de la forme, mesurée en points. Lecture/écriture float. La valeur retournée est toujours définie et n'est jamais Float.NaN. La valeur assignée doit également être définie ; affectez Float.NaN uniquement aux propriétés d'une instance RawFrame. |

**Retour :**
void

---

### setHidden {#setHidden}

| Nom | Description |
| --- | --- |
| setHidden (boolean) | Détermine si la forme est masquée. Lecture/écriture boolean. |

**Retour :**
void

---

### setHyperlinkClick {#setHyperlinkClick}

| Nom | Description |
| --- | --- |
| setHyperlinkClick ([Hyperlink](../hyperlink)) | Renvoie ou définit le lien hypertexte défini pour le clic de la souris. Lecture/écriture IHyperlink. |

**Retour :**
void

---

### setHyperlinkMouseOver {#setHyperlinkMouseOver}

| Nom | Description |
| --- | --- |
| setHyperlinkMouseOver ([Hyperlink](../hyperlink)) | Renvoie ou définit le lien hypertexte défini pour le survol de la souris. Lecture/écriture IHyperlink. |

**Retour :**
void

---

### setName {#setName}

| Nom | Description |
| --- | --- |
| setName (String) | Renvoie ou définit le nom d'une forme. Doit être non nul. Utilisez une chaîne vide si nécessaire. Lecture/écriture String. |

**Retour :**
void

---

### setRawFrame {#setRawFrame}

| Nom | Description |
| --- | --- |
| setRawFrame ([ShapeFrame](../shapeframe)) | Renvoie ou définit les propriétés brutes du cadre de la forme. Lecture/écriture IShapeFrame. |

**Retour :**
void

---

### setRotation {#setRotation}

| Nom | Description |
| --- | --- |
| setRotation (float) | Renvoie ou définit le nombre de degrés dont la forme spécifiée est pivotée autour de l'axe z. Une valeur positive indique une rotation horaire ; une valeur négative indique une rotation antihoraire. Lecture/écriture float. La valeur retournée est toujours définie (n'est pas Float.NaN). La valeur assignée doit être définie (pas Float.NaN). Vous pouvez affecter des valeurs indéfinies aux propriétés d'une instance RawFrame. |

**Retour :**
void

---

### setWidth {#setWidth}

| Nom | Description |
| --- | --- |
| setWidth (float) | Obtient ou définit la largeur de la forme, mesurée en points. Lecture/écriture float. La valeur retournée est toujours définie et n'est jamais Float.NaN. La valeur assignée doit également être définie ; affectez Float.NaN uniquement aux propriétés d'une instance RawFrame. |

**Retour :**
void

---

### setX {#setX}

| Nom | Description |
| --- | --- |
| setX (float) | Obtient ou définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points. Lecture/écriture float. La valeur retournée est toujours définie et n'est jamais Float.NaN. La valeur assignée doit également être définie ; affectez Float.NaN uniquement aux propriétés d'une instance RawFrame. |

**Retour :**
void

---

### setY {#setY}

| Nom | Description |
| --- | --- |
| setY (float) | Obtient ou définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points. Lecture/écriture float. La valeur retournée est toujours définie et n'est jamais Float.NaN. La valeur assignée doit également être définie ; affectez Float.NaN uniquement aux propriétés d'une instance RawFrame. |

**Retour :**
void

---

### writeAsSvg {#writeAsSvg}

| Nom | Description |
| --- | --- |
| writeAsSvg (OutputStream) | Enregistre le contenu de la forme sous forme de fichier SVG. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux cible |

**Retour :**
void

---

### writeAsSvg {#writeAsSvg}

| Nom | Description |
| --- | --- |
| writeAsSvg (OutputStream, [SVGOptions](../svgoptions)) | Enregistre le contenu de la forme sous forme de fichier SVG. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Flux cible |
| svgOptions | [SVGOptions](../svgoptions) | Options de génération SVG |

**Retour :**
void

---