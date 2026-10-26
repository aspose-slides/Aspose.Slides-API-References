---
title: IImageTransformOperationFactory
second_title: Référence de l'API Aspose.Slides pour C++
description: Permet de créer des instances d'effets d'image
type: docs
weight: 755
url: /fr/aspose.slides.effects/iimagetransformoperationfactory/
---
## IImageTransformOperationFactory classe


Permet de créer des instances d'effets d'image

```cpp
class IImageTransformOperationFactory : public virtual System::Object
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaBiLevel](../ialphabilevel/)\> [CreateAlphaBiLevel](./createalphabilevel/)(**float**) | Crée un effet Alpha [BiLevel](../bilevel/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaFloor](../ialphafloor/)\> [CreateAlphaFloor](./createalphafloor/)() | Crée un effet Alpha floor. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaInverse](../ialphainverse/)\> [CreateAlphaInverse](./createalphainverse/)() | Crée un effet Alpha inverse. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaModulate](../ialphamodulate/)\> [CreateAlphaModulate](./createalphamodulate/)() | Crée un effet Alpha modulate. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaModulateFixed](../ialphamodulatefixed/)\> [CreateAlphaModulateFixed](./createalphamodulatefixed/)(**float**) | Crée un effet Alpha modulate fixed. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaReplace](../ialphareplace/)\> [CreateAlphaReplace](./createalphareplace/)(**float**) | Crée un effet Alpha replace. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAlphaCeiling](../ialphaceiling/)\> [CreateAlphCeiling](./createalphceiling/)() | Crée un effet Alpha Ceiling. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBiLevel](../ibilevel/)\> [CreateBiLevel](./createbilevel/)(**float**) | Crée un effet [BiLevel](../bilevel/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBlur](../iblur/)\> [CreateBlur](./createblur/)(**double**, **bool**) | Crée un effet [Blur](../blur/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorChange](../icolorchange/)\> [CreateColorChange](./createcolorchange/)() | Crée un effet Color change. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorReplace](../icolorreplace/)\> [CreateColorReplace](./createcolorreplace/)() | Crée un effet Color replace. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDuotone](../iduotone/)\> [CreateDuotone](./createduotone/)() | Crée un effet [Duotone](../duotone/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillOverlay](../ifilloverlay/)\> [CreateFillOverlay](./createfilloverlay/)() | Crée un effet Fill overlay. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGrayScale](../igrayscale/)\> [CreateGrayScale](./creategrayscale/)() | Crée un effet Gray scale. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHSL](../ihsl/)\> [CreateHSL](./createhsl/)(**float**, **float**, **float**) | Crée un effet Hue Saturation [Luminance](../luminance/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILuminance](../iluminance/)\> [CreateLuminance](./createluminance/)(**float**, **float**) | Crée un effet [Luminance](../luminance/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITint](../itint/)\> [CreateTint](./createtint/)(**float**, **float**) | Crée un effet [Tint](../tint/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence au style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur au style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres flottants au style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres flottants au style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l’objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l’objet. Analogue de l’appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l’objet représente une instance du type décrit par targetType. Analogue de l’opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l’objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, vraiment, il initialise simplement le nouvel objet et permet de copier les sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d’affectation. Ne copie rien, vraiment, il initialise simplement le nouvel objet et permet de copier les sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence l’objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d’une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et retourne le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet la conversion d’objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente le construct typeof([System.Object](../../system/object/)) de C#. |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l’objet. Libère toutes les structures de données internes. |

## Remarques


Pour l'interface COM. 

## Voir aussi

* Classe [Object](../../system/object/)
* Espace de noms [Aspose::Slides::Effects](../)
* Bibliothèque [Aspose.Slides](../../)