---
title: ZoomFrame
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente un objet Slide Zoom dans une diapositive.
type: docs
weight: 5578
url: /fr/aspose.slides/zoomframe/
---
## ZoomFrame classe

Représente un objet Zoom [Slide](../slide/) dans une diapositive.

```cpp
class ZoomFrame : public Aspose::Slides::ZoomObject,
                  public Aspose::Slides::IZoomFrame
```

## Méthodes

| Méthode | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Ajoute un nouveau espace réservé s’il n’en existe pas et définit les propriétés de l’espace réservé sur celui spécifié. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique [Object.Equals](../../system/object/equals/) de C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres flottants de type C# où deux NaN sont considérés égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de type C# où deux NaN sont considérés égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Renvoie le texte alternatif associé à une forme. Lire [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Renvoie le titre du texte alternatif associé à une forme. Lire [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | La propriété spécifie comment une forme sera rendue en mode d’affichage noir et blanc. Lire [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Renvoie le nombre de points de connexion de la forme. Lecture seule **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Renvoie les données personnalisées de la forme. Lecture seule [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Renvoie l’objet [EffectFormat](../effectformat/) qui contient les effets de pixel appliqués à une forme. Remarque : peut renvoyer null pour certains types de formes qui n’ont pas de propriétés d’effet. Lecture seule [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Renvoie l’objet [FillFormat](../fillformat/) qui contient les propriétés de formatage de remplissage d’une forme. Remarque : peut renvoyer null pour certains types de formes qui n’ont pas de propriétés de remplissage. Lecture seule [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Renvoie les propriétés du cadre de la forme. Lire [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | Renvoie les verrous de la forme. Lecture seule [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | Obtient la hauteur de la forme, mesurée en points. Lecture **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Détermine si la forme est masquée. Lecture **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Renvoie le lien hypertexte défini pour le clic de souris. Lire [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Renvoie le gestionnaire de liens hypertexte. Lecture seule [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Renvoie le lien hypertexte défini pour le survol de la souris. Lire [IHyperlink](../ihyperlink/). |
| [ZoomImageType](../zoomimagetype/) [get_ImageType](../zoomobject/get_imagetype/)() override | Obtient le type d’image d’un objet zoom. Lire [ZoomImageType](../zoomimagetype/). Valeur par défaut : Preview |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Obtient l’option « Mark as decorative ». Lecture/écriture **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Détermine si la forme est groupée. Lecture seule **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Détermine si la forme est TextHolder_PPT. Lecture seule **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Renvoie l’objet [LineFormat](../lineformat/) qui contient les propriétés de formatage des lignes d’une forme. Remarque : peut renvoyer null pour certains types de formes qui n’ont pas de propriétés de ligne. Lecture seule [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Renvoie le nom d’une forme. Ne doit pas être null. Utilisez une chaîne vide si nécessaire. Lire [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Renvoie un identifiant unique à l’échelle de la diapositive qui reste constant pendant la durée de vie de la forme et permet à PowerPoint ou au code d’interopérabilité de référencer la forme de façon fiable depuis n’importe quel endroit du document. Lecture seule **uint32_t**. Voir aussi [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Renvoie l’objet parent [GroupShape](../groupshape/) si la forme est groupée. Sinon, renvoie null. Lecture seule [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Renvoie l’espace réservé d’une forme. Renvoie null si la forme n’a pas d’espace réservé. Lecture seule [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Renvoie la présentation parent d’une diapositive. Lecture seule [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Renvoie les propriétés brutes du cadre de forme. Lire [IShapeFrame](../ishapeframe/). |
| **bool** [get_ReturnToParent](../zoomobject/get_returntoparent/)() override | Obtient le comportement de navigation dans le diaporama. Lecture **bool**. Valeur par défaut : false |
| **float** [get_Rotation](../shape/get_rotation/)() override | Renvoie le nombre de degrés de rotation de la forme spécifiée autour de l’axe z. Une valeur positive indique une rotation horaire ; une valeur négative indique une rotation antihoraire. Lecture **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Renvoie les verrous de la forme. Lecture seule [IBaseShapeLock](../ibaseshapelock/). |
| **bool** [get_ShowBackground](../zoomobject/get_showbackground/)() override | Obtient la valeur indiquant si le Zoom utilisera l’arrière-plan de la diapositive de destination. Lecture **bool**. Valeur par défaut : true |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Renvoie la diapositive parent d’une forme. Lecture seule [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() override | Obtient l’objet diapositive auquel l’objet Zoom [Slide](../slide/) est lié. Lire [ISlide](../islide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Renvoie l’objet [ThreeDFormat](../threedformat/) contenant les propriétés d’effet 3D d’une forme. Remarque : peut renvoyer null pour certains types de formes qui n’ont pas de propriétés 3D. Lecture seule [IThreeDFormat](../ithreedformat/). |
| **float** [get_TransitionDuration](../zoomobject/get_transitionduration/)() override | Obtient la durée de la transition entre Zoom et la diapositive. Lecture **float**. Valeur par défaut : 1.0f |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Renvoie un identifiant interne, à l’échelle de la présentation, destiné à être utilisé par les add-ins ou autre code. Comme cette valeur peut être réassignée par l’utilisateur ou programmatiquement, elle ne doit pas être considérée comme une clé unique persistante. Lecture seule **uint32_t**. Voir aussi [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | Obtient la largeur de la forme, mesurée en points. Lecture **float**. |
| **float** [get_X](../shape/get_x/)() override | Obtient la coordonnée x du coin supérieur gauche de la forme, mesurée en points. Lecture **float**. |
| **float** [get_Y](../shape/get_y/)() override | Obtient la coordonnée y du coin supérieur gauche de la forme, mesurée en points. Lecture **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../zoomobject/get_zoomimage/)() override | Obtient l’image pour l’objet zoom. Lire [IPPImage](../ippimage/). |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Renvoie la position d’une forme dans l’ordre Z. Shapes[0] renvoie la forme au fond de l’ordre Z, et Shapes[Shapes.Count - 1] renvoie la forme à l’avant de l’ordre Z. Lecture seule **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Renvoie une forme d’espace réservé de base (forme provenant de la disposition et/ou de la diapositive maître dont la forme actuelle hérite). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l’objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d’objets personnalisés. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Renvoie la vignette de la forme. Le type de limites de vignette de forme [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) est utilisé par défaut. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Renvoie la vignette de la forme. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l’objet. Analogue de l’appel C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Obtient les limites visuelles de la forme calculées à partir de son contenu rendu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l’objet représente une instance du type décrit par targetType. Analogue de l’opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l’objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d’affectation. Ne copie rien, en réalité, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d’une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Définit que cette forme n’est pas un espace réservé. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Définit le texte alternatif associé à une forme. Écrire [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Définit le titre du texte alternatif associé à une forme. Écrire [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | La propriété spécifie comment une forme sera rendue en mode d’affichage noir et blanc. Écrire [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Définit les propriétés du cadre de la forme. Écrire [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Définit la hauteur de la forme, mesurée en points. Écrire **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Définit si la forme est masquée. Écrire **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Définit le lien hypertexte défini pour le clic de souris. Écrire [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Définit le lien hypertexte défini pour le survol de la souris. Écrire [IHyperlink](../ihyperlink/). |
| void [set_ImageType](../zoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) override | Définit le type d’image d’un objet zoom. Écrire [ZoomImageType](../zoomimagetype/). Valeur par défaut : Preview |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Définit l’option « Mark as decorative ». Lecture/écriture **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Définit le nom d’une forme. Ne doit pas être null. Utilisez une chaîne vide si nécessaire. Écrire [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Définit les propriétés brutes du cadre de forme. Écrire [IShapeFrame](../ishapeframe/). |
| void [set_ReturnToParent](../zoomobject/set_returntoparent/)(**bool**) override | Définit le comportement de navigation dans le diaporama. Écrire **bool**. Valeur par défaut : false |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Définit le nombre de degrés de rotation de la forme spécifiée autour de l’axe z. Une valeur positive indique une rotation horaire ; une valeur négative indique une rotation antihoraire. Écrire **float**. |
| void [set_ShowBackground](../zoomobject/set_showbackground/)(**bool**) override | Définit la valeur indiquant si le Zoom utilisera l’arrière-plan de la diapositive de destination. Écrire **bool**. Valeur par défaut : true |
| void [set_TargetSlide](./set_targetslide/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | Définit l’objet diapositive auquel l’objet Zoom [Slide](../slide/) est lié. Écrire [ISlide](../islide/). |
| void [set_TransitionDuration](../zoomobject/set_transitionduration/)(**float**) override | Définit la durée de la transition entre Zoom et la diapositive. Écrire **float**. Valeur par défaut : 1.0f |
| void [set_Width](../shape/set_width/)(**float**) override | Définit la largeur de la forme, mesurée en points. Écrire **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points. Écrire **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points. Écrire **float**. |
| void [set_ZoomImage](../zoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | Définit l’image pour l’objet zoom. Écrire [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Enregistre le contenu de [Shape](../shape/) en fichier SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Enregistre le contenu de [Shape](../shape/) en fichier SVG. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l’objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [ZoomObject](../zoomobject/)
* Classe [IZoomFrame](../izoomframe/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)