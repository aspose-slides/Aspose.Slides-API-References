---
title: IThreeDFormat
second_title: Référence API Aspose.Slides pour C++
description: Représente les propriétés 3-D.
type: docs
weight: 4161
url: /fr/aspose.slides/ithreedformat/
---
## IThreeDFormat classe

Représente les propriétés 3-D.

```cpp
class IThreeDFormat : public Aspose::Slides::IThreeDParamSource
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeBevel](../ishapebevel/)\> [get_BevelBottom](./get_bevelbottom/)() | Renvoie le type d'un biseau 3D inférieur. Lecture seule [IShapeBevel](../ishapebevel/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeBevel](../ishapebevel/)\> [get_BevelTop](./get_beveltop/)() | Renvoie le type d'un biseau 3D supérieur. Lecture seule [IShapeBevel](../ishapebevel/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICamera](../icamera/)\> [get_Camera](./get_camera/)() | Renvoie les paramètres d'une caméra. Lecture seule [ICamera](../icamera/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_ContourColor](./get_contourcolor/)() | Renvoie la couleur d'un contour. Lecture seule [IColorFormat](../icolorformat/). |
| virtual **double** [get_ContourWidth](./get_contourwidth/)() | Renvoie la largeur d'un contour 3D. Lecture **double**. |
| virtual **double** [get_Depth](./get_depth/)() | Renvoie la profondeur d'une forme 3D. Lecture **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_ExtrusionColor](./get_extrusioncolor/)() | Renvoie la couleur d'une extrusion. Lecture seule [IColorFormat](../icolorformat/). |
| virtual **double** [get_ExtrusionHeight](./get_extrusionheight/)() | Renvoie la hauteur d'un effet d'extrusion. Lecture **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILightRig](../ilightrig/)\> [get_LightRig](./get_lightrig/)() | Renvoie le type d'une lumière. Lecture seule [ILightRig](../ilightrig/). |
| virtual [MaterialPresetType](../materialpresettype/) [get_Material](./get_material/)() | Renvoie le type d'un matériau. Lecture [MaterialPresetType](../materialpresettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormatEffectiveData](../ithreedformateffectivedata/)\> [GetEffective](./geteffective/)() | Obtient les données de formatage 3-D effectives avec l'héritage appliqué. |
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
| virtual void [set_ContourWidth](./set_contourwidth/)(**double**) | Définit la largeur d'un contour 3D. Écriture **double**. |
| virtual void [set_Depth](./set_depth/)(**double**) | Définit la profondeur d'une forme 3D. Écriture **double**. |
| virtual void [set_ExtrusionHeight](./set_extrusionheight/)(**double**) | Définit la hauteur d'un effet d'extrusion. Écriture **double**. |
| virtual void [set_Material](./set_material/)([MaterialPresetType](../materialpresettype/)) | Définit le type d'un matériau. Écriture [MaterialPresetType](../materialpresettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n'th argument modèle en tant que pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [IThreeDParamSource](../ithreedparamsource/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)