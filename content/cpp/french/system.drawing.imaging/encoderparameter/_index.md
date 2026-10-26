---
title: EncoderParameter
second_title: Référence API Aspose.Slides pour C++
description: "Servit de conteneur utilisé pour transmettre des valeurs à un encodeur d'image. Les objets de cette classe ne doivent être alloués qu'à l'aide de la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument."
type: docs
weight: 66
url: /fr/system.drawing.imaging/encoderparameter/
---
## EncoderParameter classe


Serves as a container used to pass values to an image encoder. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EncoderParameter : public System::Object
```

## Méthodes

| Méthode | Description |
| --- | --- |
|  [EncoderParameter](./encoderparameter/)() | Construit une nouvelle instance de la classe [EncoderParameter](./). |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **uint8_t**, **bool**) | Construit une nouvelle instance de la classe [EncoderParameter](./). |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int16_t**) | Construit une nouvelle instance de la classe [EncoderParameter](./). |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int64_t**) | Construit une nouvelle instance de la classe [EncoderParameter](./). |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int32_t**) | Construit une nouvelle instance de la classe [EncoderParameter](./). |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int32_t**, **int32_t**) | Construit une nouvelle instance de la classe [EncoderParameter](./) qui représente une fraction. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int64_t**, **int64_t**) | Construit une nouvelle instance de la classe [EncoderParameter](./) qui représente une plage de valeurs entières. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, **int32_t**, **int32_t**, **int32_t**, **int32_t**) | Construit une nouvelle instance de la classe [EncoderParameter](./) qui représente une plage de fractions. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [String](../../system/string/)\&) | Construit une nouvelle instance de la classe [EncoderParameter](./). |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **bool**) | Construit une nouvelle instance de la classe [EncoderParameter](./) qui représente un tableau de valeurs. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int16_t**\>\&) | Construit une nouvelle instance de la classe [EncoderParameter](./) qui représente un tableau de valeurs. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int64_t**\>\&) | Construit une nouvelle instance de la classe [EncoderParameter](./) qui représente un tableau de valeurs. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&) | Construit une nouvelle instance de la classe [EncoderParameter](./) qui représente un tableau de fractions. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int64_t**\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int64_t**\>\&) | Construit une nouvelle instance de la classe [EncoderParameter](./) qui représente un tableau de plages d'entiers. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&, const [ArrayPtr](../../system/arrayptr/)\<**int32_t**\>\&) | Construit une nouvelle instance de la classe [EncoderParameter](./) qui représente un tableau de plages de fractions. |
|  [EncoderParameter](./encoderparameter/)(const [SharedPtr](../../system/sharedptr/)\<[Encoder](../encoder/)\>\&, int, [EncoderParameterValueType](../encoderparametervaluetype/), void *) | Construit une nouvelle instance de la classe [EncoderParameter](./) qui représente le nombre spécifié de valeurs du type spécifié lus depuis le tampon indiqué. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pour un usage interne uniquement. |
| [EncoderPtr](../encoderptr/) [get_Encoder](./get_encoder/)() const | Renvoie l'objet [Encoder](../encoder/) associé à l'objet [EncoderParameter](./) actuel. |
| int [get_NumberOfValues](./get_numberofvalues/)() const | Renvoie le nombre de valeurs représentées par l'objet actuel. |
| [EncoderParameterValueType](../encoderparametervaluetype/) [get_Type](./get_type/)() const | Renvoie le type des valeurs représentées par l'objet actuel. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie réellement rien, il initialise simplement le nouvel objet et permet la construction de copies des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie réellement rien, il initialise simplement le nouvel objet et permet la construction de copies des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if\<![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence l'objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du montant spécifié. |
| void [set_Encoder](./set_encoder/)(const [EncoderPtr](../encoderptr/)\&) | Associe l'objet [Encoder](../encoder/) spécifié à l'objet [EncoderParameter](./) actuel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
|  [~EncoderParameter](./~encoderparameter/)() | Destructeur. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |
## Voir aussi

* Classe [Object](../../system/object/)
* Espace de noms [System::Drawing::Imaging](../)
* Bibliothèque [Aspose.Slides](../../)