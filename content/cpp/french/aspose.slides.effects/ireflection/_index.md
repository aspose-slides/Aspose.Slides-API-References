---
title: IReflection
second_title: Référence API Aspose.Slides pour C++
description: Représente un effet de réflexion.
type: docs
weight: 937
url: /fr/aspose.slides.effects/ireflection/
---
## IReflection classe

Représente un effet de réflexion.

```cpp
class IReflection : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                    public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IReflectionEffectiveData>>
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) rayon. Lire **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Direction de la réflexion. Lire **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Distance de la réflexion. Lire **double**. |
| virtual **float** [get_EndPosAlpha](./get_endposalpha/)() | Spécifie la position finale (le long du gradient alpha) de la valeur alpha finale (pourcentages). Lire **float**. |
| virtual **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() | Opacité finale de la réflexion. (pourcentages). Lire **float**. |
| virtual **float** [get_FadeDirection](./get_fadedirection/)() | Spécifie la direction pour décaler la réflexion. (angle). Lire **float**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Alignement du rectangle. Lire [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Spécifie si la réflexion doit pivoter avec la forme lorsque la forme est pivotée. Lire **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Spécifie le facteur d'échelle horizontal, une mise à l'échelle négative provoque un retournement. (pourcentages) Lire **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Spécifie le facteur d'échelle vertical, une mise à l'échelle négative provoque un retournement. (pourcentages) Lire **double**. |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Spécifie l'angle d'inclinaison horizontal. Lire **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Spécifie l'angle d'inclinaison vertical. Lire **double**. |
| virtual **float** [get_StartPosAlpha](./get_startposalpha/)() | Spécifie la position de départ (le long du gradient alpha) de la valeur alpha de départ (pourcentages). Lire **float**. |
| virtual **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() | Opacité de la réflexion de départ. (pourcentages). Lire **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Obtient les données effectives avec l'héritage appliqué. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Met en œuvre le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, vraiment, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, vraiment, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence l'objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) rayon. Écrire **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | Direction de la réflexion. Écrire **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | Distance de la réflexion. Écrire **double**. |
| virtual void [set_EndPosAlpha](./set_endposalpha/)(**float**) | Spécifie la position finale (le long du gradient alpha) de la valeur alpha finale (pourcentages). Écrire **float**. |
| virtual void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) | Opacité finale de la réflexion. (pourcentages). Écrire **float**. |
| virtual void [set_FadeDirection](./set_fadedirection/)(**float**) | Spécifie la direction pour décaler la réflexion. (angle). Écrire **float**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Alignement du rectangle. Écrire [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Spécifie si la réflexion doit pivoter avec la forme lorsque la forme est pivotée. Écrire **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Spécifie le facteur d'échelle horizontal, une mise à l'échelle négative provoque un retournement. (pourcentages) Écrire **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Spécifie le facteur d'échelle vertical, une mise à l'échelle négative provoque un retournement. (pourcentages) Écrire **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Spécifie l'angle d'inclinaison horizontal. Écrire **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Spécifie l'angle d'inclinaison vertical. Écrire **double**. |
| virtual void [set_StartPosAlpha](./set_startposalpha/)(**float**) | Spécifie la position de départ (le long du gradient alpha) de la valeur alpha de départ (pourcentages). Écrire **float**. |
| virtual void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) | Opacité de la réflexion de départ. (pourcentages). Écrire **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n'th argument de modèle comme pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Met en œuvre le construct typeof([System.Object](../../system/object/)) de C#. |
| void [Unlock](../../system/object/unlock/)() | Met en œuvre le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [IImageTransformOperation](../iimagetransformoperation/)
* Classe [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* Espace de noms [Aspose::Slides::Effects](../)
* Bibliothèque [Aspose.Slides](../../)