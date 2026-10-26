---
title: IOuterShadow
second_title: "Référence de l'API Aspose.Slides pour C++"
description: "Représente un effet d'ombre externe."
type: docs
weight: 885
url: /fr/aspose.slides.effects/ioutershadow/
---
## IOuterShadow classe


Représente un effet d'ombre externe.

```cpp
class IOuterShadow : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                     public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IOuterShadowEffectiveData>>
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) rayon, en points. Valeur par défaut \\u2013 0 pt. Lecture **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Direction de l'ombre, en degrés. Valeur par défaut \\u2013 0 \\u00B0 (de gauche à droite). Lecture **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Distance de l'ombre à l'objet, en points. Valeur par défaut \\u2013 0 pt. Lecture **double**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Alignement du rectangle. Valeur par défaut \\u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Lecture [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Indique si l'ombre tourne avec la forme. Valeur par défaut \\u2013 true. Lecture **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Facteur d'échelle horizontal, en pourcentage de la taille originale. Un facteur négatif entraîne un renversement. Valeur par défaut \\u2013 100 %. Lecture **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Facteur d'échelle vertical, en pourcentage de la taille originale. Un facteur négatif entraîne un renversement. Valeur par défaut \\u2013 100 %. Lecture **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() | Couleur de l'ombre. Valeur par défaut \\u2013 noir automatique (dépendant du thème). Lecture seule [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Angle de cisaillement horizontal, en degrés. Valeur par défaut \\u2013 0 \\u00B0. Lecture **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Angle de cisaillement vertical, en degrés. Valeur par défaut \\u2013 0 \\u00B0. Lecture **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associé à l'objet. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Obtient les données effectives avec l'héritage appliqué. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) rayon, en points. Valeur par défaut \\u2013 0 pt. Écriture **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | Direction de l'ombre, en degrés. Valeur par défaut \\u2013 0 \\u00B0 (de gauche à droite). Écriture **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | Distance de l'ombre à l'objet, en points. Valeur par défaut \\u2013 0 pt. Écriture **double**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Alignement du rectangle. Valeur par défaut \\u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Écriture [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Indique si l'ombre tourne avec la forme. Valeur par défaut \\u2013 true. Écriture **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Facteur d'échelle horizontal, en pourcentage de la taille originale. Un facteur négatif entraîne un renversement. Valeur par défaut \\u2013 100 %. Écriture **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Facteur d'échelle vertical, en pourcentage de la taille originale. Un facteur négatif entraîne un renversement. Valeur par défaut \\u2013 100 %. Écriture **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Angle de cisaillement horizontal, en degrés. Valeur par défaut \\u2013 0 \\u00B0. Écriture **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Angle de cisaillement vertical, en degrés. Valeur par défaut \\u2013 0 \\u00B0. Écriture **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le nᵉ argument de modèle comme un pointeur faible (plutôt que partagé). Permet le basculement des pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet la conversion d'objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Class [IImageTransformOperation](../iimagetransformoperation/)
* Class [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* Namespace [Aspose::Slides::Effects](../)
* Library [Aspose.Slides](../../)