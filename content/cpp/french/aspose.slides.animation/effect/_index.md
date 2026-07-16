---
title: Effect
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente un effet d'animation.
type: docs
weight: 118
url: /fr/aspose.slides.animation/effect/
---
## Effect classe

Représente un effet d'animation.

```cpp
class Effect : public Aspose::Slides::Animation::IEffect,
               public Aspose::Slides::IDOMObject
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_AfterAnimationColor](./get_afteranimationcolor/)() override | Définit une couleur d'animation postérieure pour l'effet. Lire [IColorFormat](../../aspose.slides/icolorformat/). |
| [Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/) [get_AfterAnimationType](./get_afteranimationtype/)() override | Définit un type d'animation postérieure pour l'effet. Lire [AfterAnimationType](../afteranimationtype/). |
| [Aspose::Slides::Animation::AnimateTextType](../animatetexttype/) [get_AnimateTextType](./get_animatetexttype/)() override | Définit un type d'animation de texte pour l'effet. Le texte de la forme peut être animé par caractère, par mot ou en une fois. Lire [AnimateTextType](../animatetexttype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\> [get_Behavior](./get_behavior/)(**int32_t**) override | Renvoie le comportement d'animation à l'index spécifié. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\> [get_Behaviors](./get_behaviors/)() override | Renvoie la collection de comportements pour l'effet. Lire [IBehaviorCollection](../ibehaviorcollection/). |
| **float** [get_DelayBetweenTextParts](./get_delaybetweentextparts/)() override | Définit un délai entre les parties du texte animé (mots ou lettres). Une valeur positive indique le pourcentage de la durée de l'effet. Une valeur négative indique le délai en secondes. Lire **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffect](../ieffect/)\> [get_Effect](./get_effect/)(**int32_t**) override | Renvoie l'effet d'une séquence à l'index spécifié. |
| [EffectPresetClassType](../effectpresetclasstype/) [get_PresetClassType](./get_presetclasstype/)() override | Définit la classe de l'effet. Lire [EffectPresetClassType](../effectpresetclasstype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISequence](../isequence/)\> [get_Sequence](./get_sequence/)() override | Renvoie une séquence pour un effet. Lecture seule [ISequence](../isequence/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | Définit le son intégré pour l'effet. Lire [IAudio](../../aspose.slides/iaudio/). |
| **bool** [get_StopPreviousSound](./get_stopprevioussound/)() override | Cet attribut indique si l'effet d'animation arrête le son précédent. Lire **bool**. |
| [EffectSubtype](../effectsubtype/) [get_Subtype](./get_subtype/)() override | Définit le sous-type de l'effet. Lire [EffectSubtype](../effectsubtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [get_TargetShape](./get_targetshape/)() override | Renvoie la forme cible pour l'effet. Lecture seule [IShape](../../aspose.slides/ishape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextAnimation](../itextanimation/)\> [get_TextAnimation](./get_textanimation/)() override | [TextAnimation](../textanimation/) Lecture seule [ITextAnimation](../itextanimation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](./get_timing/)() override | Définit la valeur de synchronisation pour l'effet. Lire [ITiming](../itiming/). |
| [EffectType](../effecttype/) [get_Type](./get_type/)() override | Définit le type de l'effet. Lire [EffectType](../effecttype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie réellement rien, il initialise simplement le nouvel objet et permet la copie de construction des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie réellement rien, il initialise simplement le nouvel objet et permet la copie de construction des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| void [set_AfterAnimationColor](./set_afteranimationcolor/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\>) override | Définit une couleur d'animation postérieure pour l'effet. Écrire [IColorFormat](../../aspose.slides/icolorformat/). |
| void [set_AfterAnimationType](./set_afteranimationtype/)([Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/)) override | Définit un type d'animation postérieure pour l'effet. Écrire [AfterAnimationType](../afteranimationtype/). |
| void [set_AnimateTextType](./set_animatetexttype/)([Aspose::Slides::Animation::AnimateTextType](../animatetexttype/)) override | Définit un type d'animation de texte pour l'effet. Le texte de la forme peut être animé par caractère, par mot ou en une fois. Écrire [AnimateTextType](../animatetexttype/). |
| void [set_Behavior](./set_behavior/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\>) override | Définit le comportement d'animation à l'index spécifié. |
| void [set_Behaviors](./set_behaviors/)([System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\>) override | Renvoie la collection de comportements pour l'effet. Écrire [IBehaviorCollection](../ibehaviorcollection/). |
| void [set_DelayBetweenTextParts](./set_delaybetweentextparts/)(**float**) override | Définit un délai entre les parties du texte animé (mots ou lettres). Une valeur positive indique le pourcentage de la durée de l'effet. Une valeur négative indique le délai en secondes. Écrire **float**. |
| void [set_PresetClassType](./set_presetclasstype/)([EffectPresetClassType](../effectpresetclasstype/)) override | Définit la classe de l'effet. Écrire [EffectPresetClassType](../effectpresetclasstype/). |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | Définit le son intégré pour l'effet. Écrire [IAudio](../../aspose.slides/iaudio/). |
| void [set_StopPreviousSound](./set_stopprevioussound/)(**bool**) override | Cet attribut indique si l'effet d'animation arrête le son précédent. Écrire **bool**. |
| void [set_Subtype](./set_subtype/)([EffectSubtype](../effectsubtype/)) override | Définit le sous-type de l'effet. Écrire [EffectSubtype](../effectsubtype/). |
| void [set_Timing](./set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | Définit la valeur de synchronisation pour l'effet. Écrire [ITiming](../itiming/). |
| void [set_Type](./set_type/)([EffectType](../effecttype/)) override | Définit le type de l'effet. Écrire [EffectType](../effecttype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de changer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir les objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [IEffect](../ieffect/)
* Classe [IDOMObject](../../aspose.slides/idomobject/)
* Espace de noms [Aspose::Slides::Animation](../)
* Bibliothèque [Aspose.Slides](../../)