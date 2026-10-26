---
title: OuterShadow
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente un effet d'ombre externe.
type: docs
weight: 1041
url: /fr/aspose.slides.effects/outershadow/
---
## OuterShadow classe

Représente un effet d'ombre externe.

```cpp
class OuterShadow : public Aspose::Slides::Effects::IOuterShadow,
                    public Aspose::Slides::Effects::IVisualEffect,
                    public Aspose::Slides::IPVIObject
```

## Méthodes

| Méthode | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Détermine si le [OuterShadow](./) spécifié est égal au [OuterShadow](./) actuel. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) rayon, en points. Valeur par défaut – 0 pt. Lecture **double**. |
| **float** [get_Direction](./get_direction/)() override | Direction de l'ombre, en degrés. Valeur par défaut – 0 ° (de gauche à droite). Lecture **float**. |
| **double** [get_Distance](./get_distance/)() override | Distance de l'ombre à l'objet, en points. Valeur par défaut – 0 pt. Lecture **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Renvoie le [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) parent. Lecture seule [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Alignement du rectangle. Valeur par défaut – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Lecture [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Indique si l'ombre tourne avec la forme. Valeur par défaut – true. Lecture **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Facteur d'échelle horizontal, en pourcentage de la taille d'origine. Une échelle négative provoque un retournement. Valeur par défaut – 100 %. Lecture **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Facteur d'échelle vertical, en pourcentage de la taille d'origine. Une échelle négative provoque un retournement. Valeur par défaut – 100 %. Lecture **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() override | Couleur de l'ombre. Valeur par défaut – noir automatique (dépendant du thème). Lecture seule [IColorFormat](../../aspose.slides/icolorformat/). |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Angle de cisaillement horizontal, en degrés. Valeur par défaut – 0 °. Lecture **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Angle de cisaillement vertical, en degrés. Valeur par défaut – 0 °. Lecture **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Version. Lecture seule **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IOuterShadowEffectiveData](../ioutershadoweffectivedata/)\> [GetEffective](./geteffective/)() override | Obtient les données d'effet d'ombre externe effectif avec l'héritage appliqué. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Fonction de hachage pour un type particulier. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Met en œuvre le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
| [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie en réalité rien, il initialise simplement un nouvel objet et permet la construction de copies de sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'assignation. Ne copie en réalité rien, il initialise simplement un nouvel objet et permet la construction de copies de sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) rayon, en points. Valeur par défaut – 0 pt. Écriture **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Direction de l'ombre, en degrés. Valeur par défaut – 0 ° (de gauche à droite). Écriture **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Distance de l'ombre à l'objet, en points. Valeur par défaut – 0 pt. Écriture **double**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Alignement du rectangle. Valeur par défaut – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Écriture [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Indique si l'ombre tourne avec la forme. Valeur par défaut – true. Écriture **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Facteur d'échelle horizontal, en pourcentage de la taille d'origine. Une échelle négative provoque un retournement. Valeur par défaut – 100 %. Écriture **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Facteur d'échelle vertical, en pourcentage de la taille d'origine. Une échelle négative provoque un retournement. Valeur par défaut – 100 %. Écriture **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Angle de cisaillement horizontal, en degrés. Valeur par défaut – 0 °. Écriture **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Angle de cisaillement vertical, en degrés. Valeur par défaut – 0 °. Écriture **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de passer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Met en œuvre la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Met en œuvre le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [IOuterShadow](../ioutershadow/)
* Classe [IVisualEffect](../ivisualeffect/)
* Classe [IPVIObject](../../aspose.slides/ipviobject/)
* Espace de noms [Aspose::Slides::Effects](../)
* Bibliothèque [Aspose.Slides](../../)