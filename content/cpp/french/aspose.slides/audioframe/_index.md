---
title: AudioFrame
second_title: Référence API Aspose.Slides pour C++
description: Représente un clip audio sur une diapositive.
type: docs
weight: 53
url: /fr/aspose.slides/audioframe/
---
## AudioFrame classe

Représente un clip audio sur une diapositive.

```cpp
class AudioFrame : public Aspose::Slides::PictureFrame,
                   public Aspose::Slides::IAudioFrame
```

## Méthodes

| Méthode | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Ajoute un nouvel espace réservé s'il n'existe pas et définit les propriétés de l'espace réservé sur un spécifié. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | Crée et renvoie un tableau des éléments de la forme. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres flottants à la C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, le NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres flottants double à la C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, le NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | Renvoie la valeur d'ajustement d'une forme à l'index spécifié. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | Renvoie une collection des valeurs d'ajustement d'une forme. Lecture seule [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Renvoie le texte alternatif associé à une forme. Lecture [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Renvoie le titre du texte alternatif associé à une forme. Lecture [System::String](../../system/string/). |
| **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() override | Renvoie le dernier indice de piste Lecture **int32_t**. |
| **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() override | Renvoie le temps du dernier piste. Lecture **int32_t**. |
| **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() override | Renvoie l'indice de piste de départ. Lecture **int32_t**. |
| **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() override | Renvoie le temps de piste de départ. Lecture **int32_t**. |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | La propriété spécifie comment une forme sera rendue en mode d'affichage noir et blanc. Lecture [Slides::BlackWhiteMode](../blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() override | Obtient la collection des sous-titres fermés associés à l'audio frame. Cette propriété est en lecture seule et renvoie un [ICaptionsCollection](../icaptionscollection/) contenant toutes les pistes de sous-titres. |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Renvoie le nombre de points de connexion sur la forme. Lecture seule **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Renvoie les données personnalisées de la forme. Lecture seule [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Renvoie l'objet [EffectFormat](../effectformat/) qui contient les effets pixel appliqués à une forme. Note : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés d'effet. Lecture seule [IEffectFormat](../ieffectformat/). |
| **bool** [get_Embedded](./get_embedded/)() override | Détermine si un son est intégré dans une présentation. Lecture seule **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() override | Renvoie l'objet audio intégré. Lecture [IAudio](../iaudio/). |
| **float** [get_FadeInDuration](./get_fadeinduration/)() override | Spécifie la durée en millisecondes du fondu entrant initial du média. Lecture **float**. |
| **float** [get_FadeOutDuration](./get_fadeoutduration/)() override | Spécifie la durée en millisecondes du fondu sortant final du média. Lecture **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Renvoie l'objet [FillFormat](../fillformat/) qui contient les propriétés de formatage de remplissage pour une forme. Note : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés de remplissage. Lecture seule [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Renvoie les propriétés du cadre de forme. Lecture [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | Obtient la hauteur de la forme, mesurée en points. Lecture **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Détermine si la forme est cachée. Lecture **bool**. |
| **bool** [get_HideAtShowing](./get_hideatshowing/)() override | Détermine si un [AudioFrame](./) est caché. Lecture **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Renvoie le lien hypertexte défini pour le clic de souris. Lecture [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Renvoie le gestionnaire de lien hypertexte. Lecture seule [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Renvoie le lien hypertexte défini pour le survol de la souris. Lecture [IHyperlink](../ihyperlink/). |
| **bool** [get_IsCameo](../pictureframe/get_iscameo/)() | Détermine si le [PictureFrame](../pictureframe/) est un objet Cameo ou non. Lecture seule **bool**. |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Obtient l'option 'Marquer comme décoratif' Lecture/écriture **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Détermine si la forme est groupée. Lecture seule **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Détermine si la forme est TextHolder_PPT. Lecture seule **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Renvoie l'objet [LineFormat](../lineformat/) qui contient les propriétés de formatage de ligne pour une forme. Note : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés de ligne. Lecture seule [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | Renvoie le nom d'un fichier audio lié à un [AudioFrame](./). Lecture [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Renvoie le nom d'une forme. Ne doit pas être nul. Utilisez une chaîne vide si nécessaire. Lecture [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Renvoie un identifiant unique scoped à la diapositive qui reste constant pendant la durée de vie de la forme et permet à PowerPoint ou au code d'interop de référencer de manière fiable la forme depuis n'importe où dans le document. Lecture seule **uint32_t**. Voir aussi [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Renvoie l'objet parent [GroupShape](../groupshape/) si la forme est groupée. Sinon, renvoie null. Lecture seule [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../pictureframe/get_pictureformat/)() override | Renvoie l'objet [PictureFillFormat](../picturefillformat/) pour un cadre image. Lecture seule [IPictureFillFormat](../ipicturefillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../pictureframe/get_pictureframelock/)() override | Renvoie les verrous de la forme. Lecture seule [IPictureFrameLock](../ipictureframelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Renvoie l'espace réservé pour une forme. Renvoie null si la forme n'a pas d'espace réservé. Lecture seule [IPlaceholder](../iplaceholder/). |
| **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() override | Détermine si l'audio est lu à travers les diapositives. Lecture **bool**. |
| **bool** [get_PlayLoopMode](./get_playloopmode/)() override | Détermine si un audio est en boucle. Lecture **bool**. |
| [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() override | Renvoie le mode de lecture audio. Lecture [AudioPlayModePreset](../audioplaymodepreset/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Renvoie la présentation parente d'une diapositive. Lecture seule [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Renvoie les propriétés brutes du cadre de forme. Lecture [IShapeFrame](../ishapeframe/). |
| **float** [get_RelativeScaleHeight](../pictureframe/get_relativescaleheight/)() override | Renvoie l'échelle de la hauteur (relative à la taille originale de l'image) du cadre image. La valeur 1,0 correspond à 100 %. Lecture **float**. |
| **float** [get_RelativeScaleWidth](../pictureframe/get_relativescalewidth/)() override | Renvoie l'échelle de la largeur (relative à la taille originale de l'image) du cadre image. La valeur 1,0 correspond à 100 %. Lecture **float**. |
| **bool** [get_RewindAudio](./get_rewindaudio/)() override | Détermine si l'audio est automatiquement rembobiné au début après lecture. Lecture **bool**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | Renvoie le nombre de degrés dont la forme spécifiée est pivotée autour de l'axe z. Une valeur positive indique une rotation horaire ; une valeur négative indique une rotation antihoraire. Lecture **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Renvoie les verrous de la forme. Lecture seule [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | Renvoie l'objet de style de la forme. Lecture seule [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../pictureframe/get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Renvoie la diapositive parente d'une forme. Lecture seule [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Renvoie l'objet [ThreeDFormat](../threedformat/) qui contient les propriétés d'effet 3D pour une forme. Note : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés 3D. Lecture seule [IThreeDFormat](../ithreedformat/). |
| **float** [get_TrimFromEnd](./get_trimfromend/)() override | Spécifie la durée à retirer de la fin du média pendant la lecture, en millisecondes. Lecture **float**. |
| **float** [get_TrimFromStart](./get_trimfromstart/)() override | Spécifie la durée à retirer du début du média pendant la lecture, en millisecondes. Lecture **float**. |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Renvoie un identifiant interne, scoped à la présentation, destiné à être utilisé par les add-ins ou autre code. Comme cette valeur peut être réassignée par l'utilisateur ou par programme, elle ne doit pas être considérée comme une clé persistante unique. Lecture seule **uint32_t**. Voir aussi [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() override | Renvoie le volume audio. Lecture [AudioVolumeMode](../audiovolumemode/). |
| **float** [get_VolumeValue](./get_volumevalue/)() override | Renvoie le volume audio en pourcentages. Lecture **float**. |
| **float** [get_Width](../shape/get_width/)() override | Obtient la largeur de la forme, mesurée en points. Lecture **float**. |
| **float** [get_X](../shape/get_x/)() override | Obtient la coordonnée x du coin supérieur gauche de la forme, mesurée en points. Lecture **float**. |
| **float** [get_Y](../shape/get_y/)() override | Obtient la coordonnée y du coin supérieur gauche de la forme, mesurée en points. Lecture **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Renvoie la position d'une forme dans l'ordre Z. Shapes[0] renvoie la forme à l'arrière de l'ordre Z, et Shapes[Shapes.Count - 1] renvoie la forme à l'avant de l'ordre Z. Lecture seule **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Renvoie une forme d'espace réservé basique (forme provenant de la disposition et/ou de la diapositive maître dont la forme actuelle hérite). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | Renvoie la copie du chemin de la forme géométrique. Les coordonnées sont relatives au coin supérieur gauche de la forme. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage des objets personnalisés. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Renvoie la miniature de la forme. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) shape thumbnail bounds type is used by default. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Renvoie la miniature de la forme. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Obtient les limites visuelles de la forme calculées à partir de son contenu rendu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, il initialise simplement un nouvel objet et permet la construction de copies des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en réalité, il initialise simplement un nouvel objet et permet la construction de copies des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de la chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Définit que cette forme n'est pas un espace réservé. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Définit le texte alternatif associé à une forme. Écriture [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Définit le titre du texte alternatif associé à une forme. Écriture [System::String](../../system/string/). |
| void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) override | Définit un indice de piste final Écriture **int32_t**. |
| void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) override | Définit le temps du dernier piste. Écriture **int32_t**. |
| void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) override | Définit un indice de piste de départ. Écriture **int32_t**. |
| void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) override | Définit le temps de piste de départ. Écriture **int32_t**. |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | La propriété spécifie comment une forme sera rendue en mode d'affichage noir et blanc. Écriture [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | Définit l'objet audio intégré. Écriture [IAudio](../iaudio/). |
| void [set_FadeInDuration](./set_fadeinduration/)(**float**) override | Spécifie la durée en millisecondes du fondu entrant initial du média. Écriture **float**. |
| void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) override | Spécifie la durée en millisecondes du fondu sortant final du média. Écriture **float**. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Définit les propriétés du cadre de forme. Écriture [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Définit la hauteur de la forme, mesurée en points. Écriture **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Détermine si la forme est cachée. Écriture **bool**. |
| void [set_HideAtShowing](./set_hideatshowing/)(**bool**) override | Détermine si un [AudioFrame](./) est caché. Écriture **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Définit le lien hypertexte défini pour le clic de souris. Écriture [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Définit le lien hypertexte défini pour le survol de la souris. Écriture [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Définit l'option 'Marquer comme décoratif' Lecture/écriture **bool**. |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | Définit le nom d'un fichier audio lié à un [AudioFrame](./). Écriture [System::String](../../system/string/). |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Définit le nom d'une forme. Ne doit pas être nul. Utilisez une chaîne vide si nécessaire. Écriture [System::String](../../system/string/). |
| void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) override | Détermine si l'audio est lu à travers les diapositives. Écriture **bool**. |
| void [set_PlayLoopMode](./set_playloopmode/)(**bool**) override | Détermine si un audio est en boucle. Écriture **bool**. |
| void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) override | Définit le mode de lecture audio. Écriture [AudioPlayModePreset](../audioplaymodepreset/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Définit les propriétés brutes du cadre de forme. Écriture [IShapeFrame](../ishapeframe/). |
| void [set_RelativeScaleHeight](../pictureframe/set_relativescaleheight/)(**float**) override | Définit l'échelle de la hauteur (relative à la taille originale de l'image) du cadre image. La valeur 1,0 correspond à 100 %. Écriture **float**. |
| void [set_RelativeScaleWidth](../pictureframe/set_relativescalewidth/)(**float**) override | Définit l'échelle de la largeur (relative à la taille originale de l'image) du cadre image. La valeur 1,0 correspond à 100 %. Écriture **float**. |
| void [set_RewindAudio](./set_rewindaudio/)(**bool**) override | Détermine si l'audio est automatiquement rembobiné au début après lecture. Écriture **bool**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Définit le nombre de degrés dont la forme spécifiée est pivotée autour de l'axe z. Une valeur positive indique une rotation horaire ; une valeur négative indique une rotation antihoraire. Écriture **float**. |
| void [set_ShapeType](../pictureframe/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_TrimFromEnd](./set_trimfromend/)(**float**) override | Spécifie la durée à retirer de la fin du média pendant la lecture, en millisecondes. Écriture **float**. |
| void [set_TrimFromStart](./set_trimfromstart/)(**float**) override | Spécifie la durée à retirer du début du média pendant la lecture, en millisecondes. Écriture **float**. |
| void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) override | Définit le volume audio. Écriture [AudioVolumeMode](../audiovolumemode/). |
| void [set_VolumeValue](./set_volumevalue/)(**float**) override | Définit le volume audio en pourcentages. Écriture **float**. |
| void [set_Width](../shape/set_width/)(**float**) override | Définit la largeur de la forme, mesurée en points. Écriture **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Définit la coordonnée x du coin supérieur gauche de la forme, mesurée en points. Écriture **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Définit la coordonnée y du coin supérieur gauche de la forme, mesurée en points. Écriture **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | Met à jour la géométrie de la forme à partir de l'objet [IGeometryPath](../igeometrypath/). Les coordonnées doivent être relatives au coin supérieur gauche de la forme. Change le type de la forme ([ShapeType](../shapetype/)) en [ShapeType::Custom](../shapetype/). |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | Met à jour la géométrie de la forme à partir d'un tableau de [IGeometryPath](../igeometrypath/). Les coordonnées doivent être relatives au coin supérieur gauche de la forme. Change le type de la forme ([ShapeType](../shapetype/)) en [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Enregistre le contenu de [Shape](../shape/) en fichier SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Enregistre le contenu de [Shape](../shape/) en fichier SVG. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Remarques

Les exemples suivants montrent comment modifier les [Audio](../audio/) Play Options.
```cpp
auto pres = System::MakeObject<Presentation>(u"AudioFrameEmbed_out.pptx");

// Obtient la forme AudioFrame
System::SharedPtr<AudioFrame> audioFrame = System::ExplicitCast<AudioFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
// Définit le mode de lecture sur lecture au clic
audioFrame->set_PlayMode(AudioPlayModePreset::OnClick);
// Définit le volume à Bas
audioFrame->set_Volume(AudioVolumeMode::Low);
// Définit l'audio pour être lu sur toutes les diapositives
audioFrame->set_PlayAcrossSlides(true);
// Désactive la boucle pour l'audio
audioFrame->set_PlayLoopMode(false);
// Masque l'AudioFrame pendant le diaporama
audioFrame->set_HideAtShowing(true);
// Rembobine l'audio au début après la lecture
audioFrame->set_RewindAudio(true);
// Enregistre le fichier PowerPoint sur le disque
pres->Save(u"AudioFrameEmbed_changed.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Classe [PictureFrame](../pictureframe/)
* Classe [IAudioFrame](../iaudioframe/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)