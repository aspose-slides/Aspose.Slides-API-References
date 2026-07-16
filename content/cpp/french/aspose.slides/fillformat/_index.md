---
title: FillFormat
second_title: Référence API Aspose.Slides pour C++
description: Représente des options de formatage de remplissage.
type: docs
weight: 885
url: /fr/aspose.slides/fillformat/
---
## classe FillFormat

Représente des options de formatage de remplissage.

```cpp
class FillFormat : public Aspose::Slides::PVIObject,
                   public Aspose::Slides::IFillFormat
```

## Méthodes

| Méthode | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Compare avec l'objet spécifié. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la semantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emule la comparaison de nombres a virgule flottante de style C# où deux NaN sont consideres egaux bien que selon IEC 60559:1989 NaN ne soit egal a aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emule la comparaison de nombres a virgule flottante de style C# où deux NaN sont consideres egaux bien que selon IEC 60559:1989 NaN ne soit egal a aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pour usage interne uniquement. |
| [Aspose::Slides::FillType](../filltype/) [get_FillType](./get_filltype/)() override | Renvoie le type de remplissage. Lire [Slides::FillType](../filltype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGradientFormat](../igradientformat/)\> [get_GradientFormat](./get_gradientformat/)() override | Renvoie le format de remplissage en degrade. Lecture seule [IGradientFormat](../igradientformat/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Renvoie l'objet Parent_Immediate. Lecture seule [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Renvoie le parent [IPresentationComponent](../ipresentationcomponent/). Lecture seule [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPatternFormat](../ipatternformat/)\> [get_PatternFormat](./get_patternformat/)() override | Renvoie le format de remplissage par motif. Lecture seule [IPatternFormat](../ipatternformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFillFormat](./get_picturefillformat/)() override | Renvoie le format de remplissage d'image. Lecture seule [IPictureFillFormat](../ipicturefillformat/). |
| [NullableBool](../nullablebool/) [get_RotateWithShape](./get_rotatewithshape/)() override | Determine si le remplissage doit etre pivote avec la forme. Lire [NullableBool](../nullablebool/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_SolidFillColor](./get_solidfillcolor/)() override | Renvoie la couleur de remplissage. Lecture seule [IColorFormat](../icolorformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de donnees du compteur de references associee a l'objet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [GetEffective](./geteffective/)() override | Obtient les donnees de formatage de remplissage effectif avec l'heritage applique. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Renvoie le code de hachage. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type reel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifie si l'objet represente une instance du type décrit par targetType. Analogue de l'operateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implemente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la methode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalises. |
|  [Object](../../system/object/object/)() | Cree l'objet. Initialise toutes les structures de donnees internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operateur d'affectation. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par reference un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaine et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaines. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de references partagees du nombre specifie. |
| void [set_FillType](./set_filltype/)([Aspose::Slides::FillType](../filltype/)) override | Definit le type de remplissage. Ecrire [Slides::FillType](../filltype/). |
| void [set_RotateWithShape](./set_rotatewithshape/)([NullableBool](../nullablebool/)) override | Determine si le remplissage doit etre pivote avec la forme. Ecrire [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Definissez le n-ème argument de modele comme un pointeur faible (plutot que partage). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de references partagees. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increment le compteur de references partagees. Ne doit pas etre appele directement ; utilisez plutot des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decremente et renvoie le compteur de references partagees. Ne doit pas etre appele directement ; utilisez plutot des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la methode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalises en chaine. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implemente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implemente le deverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increment le compteur de references faibles. Ne doit pas etre appele directement ; utilisez plutot des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decremente le compteur de references faibles. Ne doit pas etre appele directement ; utilisez plutot des pointeurs intelligents ou ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Detruit l'objet. Libere toutes les structures de donnees internes. |
## Voir aussi

* Classe [PVIObject](../pviobject/)
* Classe [IFillFormat](../ifillformat/)
* Espace de noms [Aspose::Slides](../)
* Bibliotheque [Aspose.Slides](../../)