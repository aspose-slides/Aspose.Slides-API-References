---
title: GroupShape
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente un groupe de formes sur une diapositive.
type: docs
weight: 1197
url: /fr/aspose.slides/groupshape/
---
## GroupShape classe

Représente un groupe de formes sur une diapositive.

```cpp
class GroupShape : public Aspose::Slides::Shape,
                   public Aspose::Slides::IGroupShape
```

## Méthodes

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Ajoute un nouvel espace réservé s’il n’en existe pas et définit les propriétés de l’espace réservé à celles spécifiées. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de type C# où deux NaN sont considérés comme égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de type C# où deux NaN sont considérés comme égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Renvoie le texte alternatif associé à une forme. Lire [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Renvoie le titre du texte alternatif associé à une forme. Lire [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | La propriété spécifie la façon dont une forme sera rendue en mode noir et blanc.. Lire [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Renvoie le nombre de points de connexion sur la forme. Lecture seule **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Renvoie les données personnalisées de la forme. Lecture seule [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Renvoie l’objet [EffectFormat](../effectformat/) qui contient les effets pixels appliqués à une forme. Remarque : peut renvoyer null pour certains types de formes qui n’ont pas de propriétés d’effet. Lecture seule [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Renvoie l’objet [FillFormat](../fillformat/) qui contient les propriétés de formatage de remplissage d’une forme. Remarque : peut renvoyer null pour certains types de formes qui n’ont pas de propriétés de remplissage. Lecture seule [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Renvoie les propriétés du cadre de la forme. Lire [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShapeLock](../igroupshapelock/)\> [get_GroupShapeLock](./get_groupshapelock/)() override | Renvoie les verrous de la forme. Lecture seule [IGroupShapeLock](../igroupshapelock/). |
| **float** [get_Height](../shape/get_height/)() override | Obtient la hauteur de la forme, mesurée en points. Lecture **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Détermine si la forme est masquée. Lecture **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Renvoie le lien hypertexte défini pour le clic de souris. Lire [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Renvoie le gestionnaire de liens hypertexte. Lecture seule [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Renvoie le lien hypertexte défini pour le survol de la souris. Lire [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Obtient l’option 'Mark as decorative' Lecture/écriture **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Détermine si la forme est groupée. Lecture seule **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Détermine si la forme est TextHolder_PPT. Lecture seule **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | Renvoie l’objet [LineFormat](../lineformat/) qui contient les propriétés de formatage de ligne d’une forme. Remarque : renvoie null pour les objets [GroupShape](./) car ils n’ont pas de propriétés de ligne. Lecture seule [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Renvoie le nom d’une forme. Ne doit pas être nul. Utilisez une chaîne vide si nécessaire. Lire [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Renvoie un identifiant unique au niveau de la diapositive qui reste constant pendant la durée de vie de la forme et permet à PowerPoint ou au code d’interop de référencer de façon fiable la forme depuis n’importe où dans le document. Lecture seule **uint32_t**. Voir aussi [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Renvoie l’objet parent [GroupShape](./) si la forme est groupée. Sinon renvoie null. Lecture seule [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Renvoie l’espace réservé d’une forme. Renvoie null si la forme n’a pas d’espace réservé. Lecture seule [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Renvoie la présentation parent d’une diapositive. Lecture seule [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Renvoie les propriétés brutes du cadre de la forme. Lire [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](../shape/get_rotation/)() override | Renvoie le nombre de degrés de rotation de la forme spécifiée autour de l’axe z. Une valeur positive indique une rotation dans le sens horaire ; une valeur négative indique une rotation dans le sens antihoraire. Lecture **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)(**int32_t**) override | Renvoie une forme dans le groupe à l’indice spécifié. Lecture seule [Aspose::Slides::IShape](../ishape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Renvoie les verrous de la forme. Lecture seule [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](./get_shapes/)() override | Renvoie la collection de formes dans le groupe. Lecture seule [IShapeCollection](../ishapecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Renvoie la diapositive parent d’une forme. Lecture seule [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Renvoie l’objet [ThreeDFormat](../threedformat/) qui contient les propriétés d’effet 3D d’une forme. Remarque : peut renvoyer null pour certains types de formes qui n’ont pas de propriétés 3D. Lecture seule [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Renvoie un identifiant interne au niveau de la présentation destiné à être utilisé par des modules complémentaires ou autre code. Comme cette valeur peut être réassignée par l’utilisateur ou programme, elle ne doit pas être considérée comme une clé unique persistante. Lecture seule **uint32_t**. Voir aussi [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | Obtient la largeur de la forme, mesurée en points. Lecture **float**. |
| **float** [get_X](../shape/get_x/)() override | Obtient la coordonnée x du coin supérieur gauche de la forme, mesurée en points. Lecture **float**. |
| **float** [get_Y](../shape/get_y/)() override | Obtient la coordonnée y du coin supérieur gauche de la forme, mesurée en points. Lecture **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Renvoie la position d’une forme dans l’ordre Z. Shapes[0] renvoie la forme au fond de l’ordre Z, et Shapes[Shapes.Count - 1] renvoie la forme à l’avant de l’ordre Z. Lecture seule **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Renvoie une forme d’espace réservé de base (forme provenant de la disposition et/ou de la diapositive maîtresse dont la forme actuelle hérite). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l’objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d’objets personnalisés. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Renvoie la miniature de la forme. Le type de limites de la miniature de forme [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) est utilisé par défaut. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Renvoie la miniature de la forme. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l’objet. Analogue de l’appel C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Obtient les limites visuelles de la forme calculées à partir de son contenu rendu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l’objet représente une instance du type décrit par targetType. Analogue de l’opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l’objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction de copies des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d’affectation. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction de copies des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d’une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Définit que cette forme n’est pas un espace réservé. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Définit le texte alternatif associé à une forme. Écrire [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Définit le titre du texte alternatif associé à une forme. Écrire [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | La propriété spécifie la façon dont une forme sera rendue en mode noir et blanc.. Écrire [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Définit les propriétés du cadre de la forme. Écrire [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Définit la hauteur de la forme, mesurée en points. Écrire **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Détermine si la forme est masquée. Écrire **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Définit le lien hypertexte défini pour le clic de souris. Écrire [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Définit le lien hypertexte défini pour le survol de la souris. Écrire [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Définit l’option 'Mark as decorative' Lecture/écriture **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Définit le nom d’une forme. Ne doit pas être nul. Utilisez une chaîne vide si nécessaire. Écrire [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Définit les propriétés brutes du cadre de la forme. Écrire [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Définit le nombre de degrés de rotation de la forme spécifiée autour de l’axe z. Une valeur positive indique une rotation dans le sens horaire ; une valeur négative indique une rotation dans le sens antihoraire. Écrire **float**. |
| void [set_Width](../shape/set_width/)(**float**) override | Définit la largeur de la forme, mesurée en points. Écrire **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points. Écrire **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points. Écrire **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente le construct typeof([System.Object](../../system/object/)) de C#. |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Enregistre le contenu de [Shape](../shape/) sous forme de fichier SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Enregistre le contenu de [Shape](../shape/) sous forme de fichier SVG. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l’objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [Shape](../shape/)
* Classe [IGroupShape](../igroupshape/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)