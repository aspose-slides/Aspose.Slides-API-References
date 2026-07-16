---
title: IPictureFillFormat
second_title: Aspose.Slides pour C++ Référence API
description: Représente un style de remplissage d'image.
type: docs
weight: 3225
url: /fr/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat classe


Représente un style de remplissage d'image.

```cpp
class IPictureFillFormat : public Aspose::Slides::IFillParamSource
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) | Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. Optionnellement, cela supprime également les zones recadrées. |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, **float**) | Compresse l'image en réduisant sa taille en fonction de la taille de la forme et de la résolution spécifiée. Optionnellement, cela supprime également les zones recadrées. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() | Supprime les zones recadrées du remplissage [Picture](../picture/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence au style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur au style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés comme égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés comme égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À usage interne uniquement. |
| virtual **float** [get_CropBottom](./get_cropbottom/)() | Renvoie le pourcentage de la hauteur réelle de l'image qui est recadré en bas de l'image. Lecture **float**. |
| virtual **float** [get_CropLeft](./get_cropleft/)() | Renvoie le pourcentage de la largeur réelle de l'image qui est recadré à gauche de l'image. Lecture **float**. |
| virtual **float** [get_CropRight](./get_cropright/)() | Renvoie le pourcentage de la largeur réelle de l'image qui est recadré à droite de l'image. Lecture **float**. |
| virtual **float** [get_CropTop](./get_croptop/)() | Renvoie le pourcentage de la hauteur réelle de l'image qui est recadré en haut de l'image. Lecture **float**. |
| virtual **int32_t** [get_Dpi](./get_dpi/)() | Renvoie le DPI utilisé pour remplir une image. Lecture **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | Renvoie l'image. Lecture seule [ISlidesPicture](../islidespicture/). |
| virtual [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() | Renvoie le mode de remplissage d'image. Lecture [Slides::PictureFillMode](../picturefillmode/). |
| virtual **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() | Renvoie le bord inférieur du rectangle de remplissage défini par un décalage en pourcentage depuis le bord inférieur de la boîte englobante de la forme. Un pourcentage positif indique un retrait, tandis qu'un pourcentage négatif indique un débordement. Lecture **float**. |
| virtual **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() | Renvoie le bord gauche du rectangle de remplissage défini par un décalage en pourcentage depuis le bord gauche de la boîte englobante de la forme. Un pourcentage positif indique un retrait, tandis qu'un pourcentage négatif indique un débordement. Lecture **float**. |
| virtual **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() | Renvoie le bord droit du rectangle de remplissage défini par un décalage en pourcentage depuis le bord droit de la boîte englobante de la forme. Un pourcentage positif indique un retrait, tandis qu'un pourcentage négatif indique un débordement. Lecture **float**. |
| virtual **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() | Renvoie le bord supérieur du rectangle de remplissage défini par un décalage en pourcentage depuis le bord supérieur de la boîte englobante de la forme. Un pourcentage positif indique un retrait, tandis qu'un pourcentage négatif indique un débordement. Lecture **float**. |
| virtual [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() | Renvoie la façon dont la texture est alignée à l'intérieur de la forme. Ce paramètre contrôle le point de départ du motif de texture et la façon dont il se répète sur la forme. Lecture [RectangleAlignment](../rectanglealignment/). |
| virtual [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() | Retourne la tuile de texture autour de son axe horizontal, vertical ou les deux. Lecture [Slides::TileFlip](../tileflip/). |
| virtual **float** [get_TileOffsetX](./get_tileoffsetx/)() | Renvoie le décalage horizontal de la texture par rapport à l'origine de la forme en points. Une valeur positive déplace la texture vers la droite, tandis qu'une valeur négative la déplace vers la gauche. Lecture **float**. |
| virtual **float** [get_TileOffsetY](./get_tileoffsety/)() | Renvoie le décalage vertical de la texture par rapport à l'origine de la forme en points. Une valeur positive déplace la texture vers le bas, tandis qu'une valeur négative la déplace vers le haut. Lecture **float**. |
| virtual **float** [get_TileScaleX](./get_tilescalex/)() | Renvoie l'échelle horizontale du remplissage de texture en pourcentage. Lecture **float**. |
| virtual **float** [get_TileScaleY](./get_tilescaley/)() | Renvoie l'échelle verticale du remplissage de texture en pourcentage. Lecture **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en réalité, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| virtual void [set_CropBottom](./set_cropbottom/)(**float**) | Définit le pourcentage de la hauteur réelle de l'image qui est recadré en bas de l'image. Écriture **float**. |
| virtual void [set_CropLeft](./set_cropleft/)(**float**) | Définit le pourcentage de la largeur réelle de l'image qui est recadré à gauche de l'image. Écriture **float**. |
| virtual void [set_CropRight](./set_cropright/)(**float**) | Définit le pourcentage de la largeur réelle de l'image qui est recadré à droite de l'image. Écriture **float**. |
| virtual void [set_CropTop](./set_croptop/)(**float**) | Définit le pourcentage de la hauteur réelle de l'image qui est recadré en haut de l'image. Écriture **float**. |
| virtual void [set_Dpi](./set_dpi/)(**int32_t**) | Définit le DPI utilisé pour remplir une image. Écriture **int32_t**. |
| virtual void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) | Définit le mode de remplissage d'image. Écriture [Slides::PictureFillMode](../picturefillmode/). |
| virtual void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) | Définit le bord inférieur du rectangle de remplissage défini par un décalage en pourcentage depuis le bord inférieur de la boîte englobante de la forme. Un pourcentage positif indique un retrait, tandis qu'un pourcentage négatif indique un débordement. Écriture **float**. |
| virtual void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) | Définit le bord gauche du rectangle de remplissage défini par un décalage en pourcentage depuis le bord gauche de la boîte englobante de la forme. Un pourcentage positif indique un retrait, tandis qu'un pourcentage négatif indique un débordement. Écriture **float**. |
| virtual void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) | Définit le bord droit du rectangle de remplissage défini par un décalage en pourcentage depuis le bord droit de la boîte englobante de la forme. Un pourcentage positif indique un retrait, tandis qu'un pourcentage négatif indique un débordement. Écriture **float**. |
| virtual void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) | Définit le bord supérieur du rectangle de remplissage défini par un décalage en pourcentage depuis le bord supérieur de la boîte englobante de la forme. Un pourcentage positif indique un retrait, tandis qu'un pourcentage négatif indique un débordement. Écriture **float**. |
| virtual void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) | Définit la façon dont la texture est alignée à l'intérieur de la forme. Ce paramètre contrôle le point de départ du motif de texture et la façon dont il se répète sur la forme. Écriture [RectangleAlignment](../rectanglealignment/). |
| virtual void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) | Retourne la tuile de texture autour de son axe horizontal, vertical ou les deux. Écriture [Slides::TileFlip](../tileflip/). |
| virtual void [set_TileOffsetX](./set_tileoffsetx/)(**float**) | Définit le décalage horizontal de la texture par rapport à l'origine de la forme en points. Une valeur positive déplace la texture vers la droite, tandis qu'une valeur négative la déplace vers la gauche. Écriture **float**. |
| virtual void [set_TileOffsetY](./set_tileoffsety/)(**float**) | Définit le décalage vertical de la texture par rapport à l'origine de la forme en points. Une valeur positive déplace la texture vers le bas, tandis qu'une valeur négative la déplace vers le haut. Écriture **float**. |
| virtual void [set_TileScaleX](./set_tilescalex/)(**float**) | Définit l'échelle horizontale du remplissage de texture en pourcentage. Écriture **float**. |
| virtual void [set_TileScaleY](./set_tilescaley/)(**float**) | Définit l'échelle verticale du remplissage de texture en pourcentage. Écriture **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de changer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet la conversion d'objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |
## Voir aussi

* Classe [IFillParamSource](../ifillparamsource/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)