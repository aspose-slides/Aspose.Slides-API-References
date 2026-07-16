---
title: IEffectFormat
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente les propriétés d'effet de la forme.
type: docs
weight: 2029
url: /fr/aspose.slides/ieffectformat/
---
## IEffectFormat classe

Représente les propriétés d'effet de la forme.

```cpp
class IEffectFormat : public Aspose::Slides::IEffectParamSource
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual void [DisableBlurEffect](./disableblureffect/)() | Désactive l'effet de flou. |
| virtual void [DisableFillOverlayEffect](./disablefilloverlayeffect/)() | Désactive l'effet de remplissage superposé. |
| virtual void [DisableGlowEffect](./disablegloweffect/)() | Désactive l'effet de lueur. |
| virtual void [DisableInnerShadowEffect](./disableinnershadoweffect/)() | Désactive l'effet d'ombre interne. |
| virtual void [DisableOuterShadowEffect](./disableoutershadoweffect/)() | Désactive l'effet d'ombre externe. |
| virtual void [DisablePresetShadowEffect](./disablepresetshadoweffect/)() | Désactive l'effet d'ombre prédéfini. |
| virtual void [DisableReflectionEffect](./disablereflectioneffect/)() | Désactive l'effet de réflexion. |
| virtual void [DisableSoftEdgeEffect](./disablesoftedgeeffect/)() | Désactive l'effet de bord doux. |
| virtual void [EnableFillOverlayEffect](./enablefilloverlayeffect/)() | Active l'effet de remplissage superposé. |
| virtual void [EnableGlowEffect](./enablegloweffect/)() | Active l'effet de lueur. |
| virtual void [EnableInnerShadowEffect](./enableinnershadoweffect/)() | Active l'effet d'ombre interne. |
| virtual void [EnableOuterShadowEffect](./enableoutershadoweffect/)() | Active l'effet d'ombre externe. |
| virtual void [EnablePresetShadowEffect](./enablepresetshadoweffect/)() | Active l'effet d'ombres prédéfinies. |
| virtual void [EnableReflectionEffect](./enablereflectioneffect/)() | Active l'effet de réflexion. |
| virtual void [EnableSoftEdgeEffect](./enablesoftedgeeffect/)() | Active l'effet de bord doux. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de type C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, le NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de type C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, le NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\> [get_BlurEffect](./get_blureffect/)() | Blur effect. Read [Effects::IBlur](../../aspose.slides.effects/iblur/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\> [get_FillOverlayEffect](./get_filloverlayeffect/)() | Fill overlay effect. Read [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\> [get_GlowEffect](./get_gloweffect/)() | Glow effect. Read [Effects::IGlow](../../aspose.slides.effects/iglow/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\> [get_InnerShadowEffect](./get_innershadoweffect/)() | Inner shadow. Read [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/). |
| virtual **bool** [get_IsNoEffects](./get_isnoeffects/)() | Renvoie true si tous les effets sont désactivés (comme un objet [EffectFormat](../effectformat/) nouvellement créé, par défaut). Lecture seule **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\> [get_OuterShadowEffect](./get_outershadoweffect/)() | Outer shadow. Read [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\> [get_PresetShadowEffect](./get_presetshadoweffect/)() | Preset shadow. Read [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\> [get_ReflectionEffect](./get_reflectioneffect/)() | Reflection. Read [Effects::IReflection](../../aspose.slides.effects/ireflection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\> [get_SoftEdgeEffect](./get_softedgeeffect/)() | Soft edge. Read [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [GetEffective](./geteffective/)() | Obtient les données de formatage d'effet effectif avec l'héritage appliqué. |
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
| virtual void [set_BlurEffect](./set_blureffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\>) | Blur effect. Write [Effects::IBlur](../../aspose.slides.effects/iblur/). |
| virtual void [set_FillOverlayEffect](./set_filloverlayeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\>) | Fill overlay effect. Write [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/). |
| virtual void [set_GlowEffect](./set_gloweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\>) | Glow effect. Write [Effects::IGlow](../../aspose.slides.effects/iglow/). |
| virtual void [set_InnerShadowEffect](./set_innershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\>) | Inner shadow. Write [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/). |
| virtual void [set_OuterShadowEffect](./set_outershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\>) | Outer shadow. Write [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/). |
| virtual void [set_PresetShadowEffect](./set_presetshadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\>) | Preset shadow. Write [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/). |
| virtual void [set_ReflectionEffect](./set_reflectioneffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\>) | Reflection. Write [Effects::IReflection](../../aspose.slides.effects/ireflection/). |
| virtual void [set_SoftEdgeEffect](./set_softedgeeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\>) | Soft edge. Write [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/). |
| virtual void [SetBlurEffect](./setblureffect/)(**double**, **bool**) | Définit l'effet de flou. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Autorise le passage des pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [IEffectParamSource](../ieffectparamsource/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)