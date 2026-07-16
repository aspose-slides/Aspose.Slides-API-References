---
title: Table
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente un tableau sur une diapositive.
type: docs
weight: 5409
url: /fr/aspose.slides/table/
---
## Classe Table

Représente un tableau sur une diapositive.

```cpp
class Table : public Aspose::Slides::GraphicalObject,
              public Aspose::Slides::ITable
```

## Méthodes

| Méthode | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Ajoute un nouveau placeholder s'il n'existe pas et définit les propriétés du placeholder sur un spécifié. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de type C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de type C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Renvoie le texte alternatif associé à une forme. Lire [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Renvoie le titre du texte alternatif associé à une forme. Lire [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | La propriété indique comment une forme sera rendue en mode d'affichage noir et blanc. Lire [Slides::BlackWhiteMode](../blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_Column](./get_column/)(**int32_t**) override | Renvoie une colonne à l'index spécifié. Lecture seule [Aspose::Slides::IColumn](../icolumn/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumnCollection](../icolumncollection/)\> [get_Columns](./get_columns/)() override | Renvoie la collection de colonnes. Lecture seule [IColumnCollection](../icolumncollection/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Renvoie le nombre de sites de connexion sur la forme. Lecture seule **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Renvoie les données personnalisées de la forme. Lecture seule [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Renvoie l'objet [EffectFormat](../effectformat/) qui contient les effets de pixel appliqués à une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés d'effet. Lecture seule [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | Renvoie un objet [TableFormat::get_FillFormat](../tableformat/get_fillformat/) contenant le format de remplissage pour le [Table](./). Lecture seule [IFillFormat](../ifillformat/). |
| **bool** [get_FirstCol](./get_firstcol/)() override | Détermine si la première colonne d'un tableau doit être dessinée avec un format spécial. Lecture **bool**. |
| **bool** [get_FirstRow](./get_firstrow/)() override | Détermine si la première ligne d'un tableau doit être dessinée avec un format spécial. Lecture **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Renvoie les propriétés du cadre de la forme. Lire [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | Renvoie les verrous de la forme. Lecture seule [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | Obtient la hauteur de la forme, mesurée en points. Lecture **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Détermine si la forme est masquée. Lecture **bool**. |
| **bool** [get_HorizontalBanding](./get_horizontalbanding/)() override | Détermine si les lignes paires doivent être dessinées avec un format différent. Lecture **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Renvoie le lien hypertexte défini pour le clic de souris. Lire [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Renvoie le gestionnaire de lien hypertexte. Lecture seule [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Renvoie le lien hypertexte défini pour le survol de la souris. Lire [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Obtient l'option « Mark as decorative » Lecture/écriture **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Détermine si la forme est groupée. Lecture seule **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Détermine si la forme est TextHolder_PPT. Lecture seule **bool**. |
| **bool** [get_LastCol](./get_lastcol/)() override | Détermine si la dernière colonne d'un tableau doit être dessinée avec un format spécial. Lecture **bool**. |
| **bool** [get_LastRow](./get_lastrow/)() override | Détermine si la dernière ligne d'un tableau doit être dessinée avec un format spécial. Lecture **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Renvoie l'objet [LineFormat](../lineformat/) qui contient les propriétés de format de ligne pour une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés de ligne. Lecture seule [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Renvoie le nom d'une forme. Ne doit pas être null. Utilisez une chaîne vide si nécessaire. Lire [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Renvoie un identifiant unique limité à la diapositive qui reste constant pendant la durée de vie de la forme et permet à PowerPoint ou au code d'interopérabilité de référencer la forme de manière fiable depuis n'importe où dans le document. Lecture seule **uint32_t**. Voir aussi [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Renvoie l'objet parent [GroupShape](../groupshape/) si la forme est groupée. Sinon renvoie null. Lecture seule [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Renvoie le placeholder d'une forme. Renvoie null si la forme n'a pas de placeholder. Lecture seule [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Renvoie la présentation parente d'une diapositive. Lecture seule [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Renvoie les propriétés brutes du cadre de la forme. Lire [IShapeFrame](../ishapeframe/). |
| **bool** [get_RightToLeft](./get_righttoleft/)() override | Détermine si le tableau a un ordre de lecture de droite à gauche. Lecture **bool**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | Renvoie le nombre de degrés dont la forme spécifiée est tournée autour de l'axe z. Une valeur positive indique une rotation horaire ; une valeur négative indique une rotation antihoraire. Lecture **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_Row](./get_row/)(**int32_t**) override | Renvoie une ligne à l'index spécifié. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRowCollection](../irowcollection/)\> [get_Rows](./get_rows/)() override | Renvoie la collection de lignes. Lecture seule [IRowCollection](../irowcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Renvoie les verrous de la forme. Lecture seule [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Renvoie la diapositive parente d'une forme. Lecture seule [IBaseSlide](../ibaseslide/). |
| [TableStylePreset](../tablestylepreset/) [get_StylePreset](./get_stylepreset/)() override | Obtient le style de tableau intégré. Lire [TableStylePreset](../tablestylepreset/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITableFormat](../itableformat/)\> [get_TableFormat](./get_tableformat/)() override | Renvoie l'objet [TableFormat](../tableformat/) qui contient les propriétés de format pour ce tableau. Lecture seule [ITableFormat](../itableformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Renvoie l'objet [ThreeDFormat](../threedformat/) qui contient les propriétés d'effet 3D pour une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés 3D. Lecture seule [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Renvoie un identifiant interne limité à la présentation destiné à être utilisé par des modules complémentaires ou autre code. Parce que cette valeur peut être réassignée par l'utilisateur ou programmatiquement, elle ne doit pas être traitée comme une clé unique persistante. Lecture seule **uint32_t**. Voir aussi [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **bool** [get_VerticalBanding](./get_verticalbanding/)() override | Détermine si les colonnes paires doivent être dessinées avec un format différent. Lecture **bool**. |
| **float** [get_Width](../shape/get_width/)() override | Obtient la largeur de la forme, mesurée en points. Lecture **float**. |
| **float** [get_X](../shape/get_x/)() override | Obtient la coordonnée x du coin supérieur gauche de la forme, mesurée en points. Lecture **float**. |
| **float** [get_Y](../shape/get_y/)() override | Obtient la coordonnée y du coin supérieur gauche de la forme, mesurée en points. Lecture **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Renvoie la position d'une forme dans l'ordre Z. Shapes[0] renvoie la forme à l'arrière de l'ordre Z, et Shapes[Shapes.Count - 1] renvoie la forme à l'avant de l'ordre Z. Lecture seule **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Renvoie une forme placeholder de base (forme provenant de la disposition et/ou de la diapositive maîtresse dont la forme actuelle hérite). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Renvoie la vignette de la forme. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) le type de limites de vignette de forme est utilisé par défaut. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Renvoie la vignette de la forme. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Obtient les limites visuelles de la forme calculées à partir de son contenu rendu. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) override | Renvoie la cellule aux index de colonne et de ligne spécifiés. Lecture seule [Cell](../cell/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# « is ». |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [MergeCells](./mergecells/)([System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, **bool**) override | Fusionne les cellules voisines. |
| [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, il initialise simplement le nouvel objet et permet la construction de copies de sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en réalité, il initialise simplement le nouvel objet et permet la construction de copies de sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Définit que cette forme n'est pas un placeholder. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Définit le texte alternatif associé à une forme. Écrire [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Définit le titre du texte alternatif associé à une forme. Écrire [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | La propriété indique comment une forme sera rendue en mode d'affichage noir et blanc. Écrire [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_FirstCol](./set_firstcol/)(**bool**) override | Détermine si la première colonne d'un tableau doit être dessinée avec un format spécial. Écrire **bool**. |
| void [set_FirstRow](./set_firstrow/)(**bool**) override | Détermine si la première ligne d'un tableau doit être dessinée avec un format spécial. Écrire **bool**. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Définit les propriétés du cadre de la forme. Écrire [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Définit la hauteur de la forme, mesurée en points. Écrire **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Détermine si la forme est masquée. Écrire **bool**. |
| void [set_HorizontalBanding](./set_horizontalbanding/)(**bool**) override | Détermine si les lignes paires doivent être dessinées avec un format différent. Écrire **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Définit le lien hypertexte défini pour le clic de souris. Écrire [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Définit le lien hypertexte défini pour le survol de la souris. Écrire [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Définit l'option « Mark as decorative » Lecture/écriture **bool**. |
| void [set_LastCol](./set_lastcol/)(**bool**) override | Détermine si la dernière colonne d'un tableau doit être dessinée avec un format spécial. Écrire **bool**. |
| void [set_LastRow](./set_lastrow/)(**bool**) override | Détermine si la dernière ligne d'un tableau doit être dessinée avec un format spécial. Écrire **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Définit le nom d'une forme. Ne doit pas être null. Utilisez une chaîne vide si nécessaire. Écrire [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Définit les propriétés brutes du cadre de la forme. Écrire [IShapeFrame](../ishapeframe/). |
| void [set_RightToLeft](./set_righttoleft/)(**bool**) override | Détermine si le tableau a un ordre de lecture de droite à gauche. Écrit **bool**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Définit le nombre de degrés dont la forme spécifiée est tournée autour de l'axe z. Une valeur positive indique une rotation horaire ; une valeur négative indique une rotation antihoraire. Écrire **float**. |
| void [set_StylePreset](./set_stylepreset/)([TableStylePreset](../tablestylepreset/)) override | Définit le style de tableau intégré. Écrire [TableStylePreset](../tablestylepreset/). |
| void [set_VerticalBanding](./set_verticalbanding/)(**bool**) override | Détermine si les colonnes paires doivent être dessinées avec un format différent. Écrire **bool**. |
| void [set_Width](../shape/set_width/)(**float**) override | Définit la largeur de la forme, mesurée en points. Écrire **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points. Écrire **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points. Écrire **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le nᵉʳᵉ argument de modèle comme pointeur faible (plutôt que partagé). Permet de passer les pointeurs dans les conteneurs en mode faible. |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\>) override | Définit les propriétés de format de portion définies pour toutes les portions des cellules du tableau. |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormat](../iparagraphformat/)\>) override | Définit les propriétés de format de paragraphe définies pour tous les paragraphes des cellules du tableau. |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormat](../itextframeformat/)\>) override | Définit les propriétés de format de cadre de texte définies pour tous les cadres de texte des cellules du tableau. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagé. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagé. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagé. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faible. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faible. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Enregistre le contenu de [Shape](../shape/) en tant que fichier SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Enregistre le contenu de [Shape](../shape/) en tant que fichier SVG. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [GraphicalObject](../graphicalobject/)
* Classe [ITable](../itable/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)