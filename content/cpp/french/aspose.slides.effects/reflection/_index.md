---
title: Reflection
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente un effet de réflexion.
type: docs
weight: 1067
url: /fr/aspose.slides.effects/reflection/
---
## Classe Reflection

Représente un [Reflection](./) effet.

```cpp
class Reflection : public Aspose::Slides::Effects::IReflection,
                   public Aspose::Slides::Effects::IVisualEffect,
                   public Aspose::Slides::IPVIObject
```

## Méthodes

| Méthode | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Détermine si le [Reflection](./) spécifié est égal au [Reflection](./) actuel. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique [Object.Equals](../../system/object/equals/) de C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) rayon. Lecture **double**. |
| **float** [get_Direction](./get_direction/)() override | Direction de la réflexion. Lecture **float**. |
| **double** [get_Distance](./get_distance/)() override | Distance de la réflexion. Lecture **double**. |
| **float** [get_EndPosAlpha](./get_endposalpha/)() override | Spécifie la position finale (le long de la rampe de gradient alpha) de la valeur alpha finale (pourcentages). Lecture **float**. |
| **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() override | Opacité finale de la réflexion. (pourcentages). Lecture **float**. |
| **float** [get_FadeDirection](./get_fadedirection/)() override | Spécifie la direction pour décaler la réflexion. (angle). Lecture **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Renvoie le parent [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). Lecture seule [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Alignement du rectangle. Lecture [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Spécifie si la réflexion doit tourner avec la forme lorsque la forme est tournée. Lecture **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Spécifie le facteur d'échelle horizontal, un facteur négatif provoque un retournement. (pourcentages) Lecture **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Spécifie le facteur d'échelle vertical, un facteur négatif provoque un retournement. (pourcentages) Lecture **double**. |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Spécifie l'angle de cisaillement horizontal. Lecture **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Spécifie l'angle de cisaillement vertical. Lecture **double**. |
| **float** [get_StartPosAlpha](./get_startposalpha/)() override | Spécifie la position de départ (le long de la rampe de gradient alpha) de la valeur alpha de départ (pourcentages). Lecture **float**. |
| **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() override | Opacité de départ de la réflexion. (pourcentages). Lecture **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Version. Lecture seule **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IReflectionEffectiveData](../ireflectioneffectivedata/)\> [GetEffective](./geteffective/)() override | Obtient les données d'effet [Reflection](./) effectives avec l'héritage appliqué. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Sert de fonction de hachage pour un type particulier. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet de cloner des types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence l'objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) rayon. Écriture **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Direction de la réflexion. Écriture **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Distance de la réflexion. Écriture **double**. |
| void [set_EndPosAlpha](./set_endposalpha/)(**float**) override | Spécifie la position finale (le long de la rampe de gradient alpha) de la valeur alpha finale (pourcentages). Écriture **float**. |
| void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) override | Opacité finale de la réflexion. (pourcentages). Écriture **float**. |
| void [set_FadeDirection](./set_fadedirection/)(**float**) override | Spécifie la direction pour décaler la réflexion. (angle). Écriture **float**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Alignement du rectangle. Écriture [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Spécifie si la réflexion doit tourner avec la forme lorsque la forme est tournée. Écriture **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Spécifie le facteur d'échelle horizontal, un facteur négatif provoque un retournement. (pourcentages) Écriture **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Spécifie le facteur d'échelle vertical, un facteur négatif provoque un retournement. (pourcentages) Écriture **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Spécifie l'angle de cisaillement horizontal. Écriture **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Spécifie l'angle de cisaillement vertical. Écriture **double**. |
| void [set_StartPosAlpha](./set_startposalpha/)(**float**) override | Spécifie la position de départ (le long de la rampe de gradient alpha) de la valeur alpha de départ (pourcentages). Écriture **float**. |
| void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) override | Opacité de départ de la réflexion. (pourcentages). Écriture **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de changer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [IReflection](../ireflection/)
* Classe [IVisualEffect](../ivisualeffect/)
* Classe [IPVIObject](../../aspose.slides/ipviobject/)
* Espace de noms [Aspose::Slides::Effects](../)
* Bibliothèque [Aspose.Slides](../../)