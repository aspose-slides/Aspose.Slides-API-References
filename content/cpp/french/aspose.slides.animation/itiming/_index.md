---
title: ITiming
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente le timing d'animation.
type: docs
weight: 443
url: /fr/aspose.slides.animation/itiming/
---
## ITiming classe

Représente le timing d'animation.

```cpp
class ITiming : public virtual System::Object
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence au style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur au style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de type C# où deux NaN sont considérés égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de type C# où deux NaN sont considérés égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| virtual **float** [get_Accelerate](./get_accelerate/)() | Décrit le pourcentage de l'effet d'accélération de la durée. Lire **float**. |
| virtual **bool** [get_AutoReverse](./get_autoreverse/)() | Décrit s'il faut lire automatiquement l'animation en sens inverse après l'avoir lue dans le sens avant. Lire **bool**. |
| virtual **float** [get_Decelerate](./get_decelerate/)() | Décrit le pourcentage de l'effet de décélération de la durée. Lire **float**. |
| virtual **float** [get_Duration](./get_duration/)() | Décrit la durée de l'effet d'animation. Lire **float**. |
| virtual **float** [get_RepeatCount](./get_repeatcount/)() | Décrit le nombre de fois que l'effet doit se répéter. Lire **float**. |
| virtual **float** [get_RepeatDuration](./get_repeatduration/)() | Décrit le nombre de fois que l'effet doit se répéter. Lire **float**. |
| virtual **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() | Cet attribut spécifie si l'effet se répètera jusqu'à la fin de la diapositive. Lire **bool**. |
| virtual **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() | Cet attribut spécifie si l'effet se répètera jusqu'au prochain clic. Lire **bool**. |
| virtual [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() | Spécifie si un effet doit redémarrer après son achèvement. Lire [EffectRestartType](../effectrestarttype/). |
| virtual **bool** [get_Rewind](./get_rewind/)() | Cet attribut spécifie si l'effet reviendra en arrière une fois la lecture terminée. Lire **bool**. |
| virtual **float** [get_Speed](./get_speed/)() | Spécifie le pourcentage d'accélération (ou de ralentissement) du timing. Lire **float**. |
| virtual **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() | Décrit le temps de retard après le déclencheur. Lire **float**. |
| virtual [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() | Décrit le type de déclencheur. Lire [EffectTriggerType](../effecttriggertype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, il se contente d'initialiser un nouvel objet et permet la construction par copie de sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'assignation. Ne copie rien, en réalité, il se contente d'initialiser un nouvel objet et permet la construction par copie de sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence l'objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| virtual void [set_Accelerate](./set_accelerate/)(**float**) | Décrit le pourcentage de l'effet d'accélération de la durée. Écrire **float**. |
| virtual void [set_AutoReverse](./set_autoreverse/)(**bool**) | Décrit s'il faut lire automatiquement l'animation en sens inverse après l'avoir lue dans le sens avant. Écrire **bool**. |
| virtual void [set_Decelerate](./set_decelerate/)(**float**) | Décrit le pourcentage de l'effet de décélération de la durée. Écrire **float**. |
| virtual void [set_Duration](./set_duration/)(**float**) | Décrit la durée de l'effet d'animation. Écrire **float**. |
| virtual void [set_RepeatCount](./set_repeatcount/)(**float**) | Décrit le nombre de fois que l'effet doit se répéter. Écrire **float**. |
| virtual void [set_RepeatDuration](./set_repeatduration/)(**float**) | Décrit le nombre de fois que l'effet doit se répéter. Écrire **float**. |
| virtual void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) | Cet attribut spécifie si l'effet se répètera jusqu'à la fin de la diapositive. Écrire **bool**. |
| virtual void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) | Cet attribut spécifie si l'effet se répètera jusqu'au prochain clic. Écrire **bool**. |
| virtual void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) | Spécifie si un effet doit redémarrer après son achèvement. Écrire [EffectRestartType](../effectrestarttype/). |
| virtual void [set_Rewind](./set_rewind/)(**bool**) | Cet attribut spécifie si l'effet reviendra en arrière une fois la lecture terminée. Écrire **bool**. |
| virtual void [set_Speed](./set_speed/)(**float**) | Spécifie le pourcentage d'accélération (ou de ralentissement) du timing. Écrire **float**. |
| virtual void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) | Décrit le temps de retard après le déclencheur. Écrire **float**. |
| virtual void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) | Décrit le type de déclencheur. Écrire [EffectTriggerType](../effecttriggertype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
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

* Classe [Object](../../system/object/)
* Espace de noms [Aspose::Slides::Animation](../)
* Bibliothèque [Aspose.Slides](../../)