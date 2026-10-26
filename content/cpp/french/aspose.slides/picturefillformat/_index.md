---
title: PictureFillFormat
second_title: Référence API Aspose.Slides pour C++
description: Représente un style de remplissage d'image.
type: docs
weight: 4720
url: /fr/aspose.slides/picturefillformat/
---
## PictureFillFormat classe


Représente un style de remplissage d'image.

```cpp
class PictureFillFormat : public Aspose::Slides::PVIObject,
                          public Aspose::Slides::IPictureFillFormat
```

## Méthodes

| Méthode | Description |
| --- | --- |
| **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) override | Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. Optionnellement, il supprime également les zones recadrées. |
| **bool** [CompressImage](./compressimage/)(**bool**, **float**) override | Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. Optionnellement, il supprime également les zones recadrées. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() override | Supprime les zones recadrées du remplissage [Picture](../picture/). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Compare avec l'objet spécifié. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| **float** [get_CropBottom](./get_cropbottom/)() override | Renvoie le pourcentage de la hauteur réelle de l'image recadrée en bas de l'image. Lecture **float**. |
| **float** [get_CropLeft](./get_cropleft/)() override | Renvoie le pourcentage de la largeur réelle de l'image recadrée à gauche de l'image. Lecture **float**. |
| **float** [get_CropRight](./get_cropright/)() override | Renvoie le pourcentage de la largeur réelle de l'image recadrée à droite de l'image. Lecture **float**. |
| **float** [get_CropTop](./get_croptop/)() override | Renvoie le pourcentage de la hauteur réelle de l'image recadrée en haut de l'image. Lecture **float**. |
| **int32_t** [get_Dpi](./get_dpi/)() override | Renvoie le dpi utilisé pour remplir une image. Lecture **int32_t**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Renvoie l'objet Parent_Immediate. Lecture seule [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Renvoie le parent [IPresentationComponent](../ipresentationcomponent/). Lecture seule [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Renvoie l'image. Lecture seule [ISlidesPicture](../islidespicture/). |
| [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() override | Renvoie le mode de remplissage d'image. Lecture [Slides::PictureFillMode](../picturefillmode/). |
| **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() override | Renvoie le bord inférieur du rectangle de remplissage défini par un décalage en pourcentage depuis le bord inférieur de la boîte englobante de la forme. Un pourcentage positif indique une encoche, un pourcentage négatif indique un débordement. Lecture **float**. |
| **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() override | Renvoie le bord gauche du rectangle de remplissage défini par un décalage en pourcentage depuis le bord gauche de la boîte englobante de la forme. Un pourcentage positif indique une encoche, un pourcentage négatif indique un débordement. Lecture **float**. |
| **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() override | Renvoie le bord droit du rectangle de remplissage défini par un décalage en pourcentage depuis le bord droit de la boîte englobante de la forme. Un pourcentage positif indique une encoche, un pourcentage négatif indique un débordement. Lecture **float**. |
| **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() override | Renvoie le bord supérieur du rectangle de remplissage défini par un décalage en pourcentage depuis le bord supérieur de la boîte englobante de la forme. Un pourcentage positif indique une encoche, un pourcentage négatif indique un débordement. Lecture **float**. |
| [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() override | Renvoie la façon dont la texture est alignée à l'intérieur de la forme. Ce paramètre contrôle le point de départ du motif de texture et la façon dont il se répète sur la forme. Lecture [RectangleAlignment](../rectanglealignment/). |
| [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() override | Retourne la texture autour de son axe horizontal, vertical ou les deux. Lecture [Slides::TileFlip](../tileflip/). |
| **float** [get_TileOffsetX](./get_tileoffsetx/)() override | Renvoie le décalage horizontal de la texture depuis l'origine de la forme en points. Une valeur positive déplace la texture vers la droite, une valeur négative la déplace vers la gauche. Lecture **float**. |
| **float** [get_TileOffsetY](./get_tileoffsety/)() override | Renvoie le décalage vertical de la texture depuis l'origine de la forme en points. Une valeur positive déplace la texture vers le bas, une valeur négative la déplace vers le haut. Lecture **float**. |
| **float** [get_TileScaleX](./get_tilescalex/)() override | Renvoie l'échelle horizontale du remplissage de texture en pourcentage. Lecture **float**. |
| **float** [get_TileScaleY](./get_tilescaley/)() override | Renvoie l'échelle verticale du remplissage de texture en pourcentage. Lecture **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Renvoie le code de hachage. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l’instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en réalité, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence l'objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| void [set_CropBottom](./set_cropbottom/)(**float**) override | Définit le pourcentage de la hauteur réelle de l'image recadrée en bas de l'image. Écrire **float**. |
| void [set_CropLeft](./set_cropleft/)(**float**) override | Définit le pourcentage de la largeur réelle de l'image recadrée à gauche de l'image. Écrire **float**. |
| void [set_CropRight](./set_cropright/)(**float**) override | Définit le pourcentage de la largeur réelle de l'image recadrée à droite de l'image. Écrire **float**. |
| void [set_CropTop](./set_croptop/)(**float**) override | Définit le pourcentage de la hauteur réelle de l'image recadrée en haut de l'image. Écrire **float**. |
| void [set_Dpi](./set_dpi/)(**int32_t**) override | Définit le dpi utilisé pour remplir une image. Écrire **int32_t**. |
| void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) override | Définit le mode de remplissage d'image. Écrire [Slides::PictureFillMode](../picturefillmode/). |
| void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) override | Définit le bord inférieur du rectangle de remplissage défini par un décalage en pourcentage depuis le bord inférieur de la boîte englobante de la forme. Un pourcentage positif indique une encoche, un pourcentage négatif indique un débordement. Écrire **float**. |
| void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) override | Définit le bord gauche du rectangle de remplissage défini par un décalage en pourcentage depuis le bord gauche de la boîte englobante de la forme. Un pourcentage positif indique une encoche, un pourcentage négatif indique un débordement. Écrire **float**. |
| void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) override | Définit le bord droit du rectangle de remplissage défini par un décalage en pourcentage depuis le bord droit de la boîte englobante de la forme. Un pourcentage positif indique une encoche, un pourcentage négatif indique un débordement. Écrire **float**. |
| void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) override | Définit le bord supérieur du rectangle de remplissage défini par un décalage en pourcentage depuis le bord supérieur de la boîte englobante de la forme. Un pourcentage positif indique une encoche, un pourcentage négatif indique un débordement. Écrire **float**. |
| void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) override | Définit la façon dont la texture est alignée à l'intérieur de la forme. Ce paramètre contrôle le point de départ du motif de texture et la façon dont il se répète sur la forme. Écrire [RectangleAlignment](../rectanglealignment/). |
| void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) override | Retourne la texture autour de son axe horizontal, vertical ou les deux. Écrire [Slides::TileFlip](../tileflip/). |
| void [set_TileOffsetX](./set_tileoffsetx/)(**float**) override | Définit le décalage horizontal de la texture depuis l'origine de la forme en points. Une valeur positive déplace la texture vers la droite, une valeur négative la déplace vers la gauche. Écrire **float**. |
| void [set_TileOffsetY](./set_tileoffsety/)(**float**) override | Définit le décalage vertical de la texture depuis l'origine de la forme en points. Une valeur positive déplace la texture vers le bas, une valeur négative la déplace vers le haut. Écrire **float**. |
| void [set_TileScaleX](./set_tilescalex/)(**float**) override | Définit l'échelle horizontale du remplissage de texture en pourcentage. Écrire **float**. |
| void [set_TileScaleY](./set_tilescaley/)(**float**) override | Définit l'échelle verticale du remplissage de texture en pourcentage. Écrire **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le nième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de changer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente le construct typeof([System.Object](../../system/object/)) de C#. |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l’instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |
## Voir aussi

* Classe [PVIObject](../pviobject/)
* Classe [IPictureFillFormat](../ipicturefillformat/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)