---
title: Details_NotSupportedException
second_title: Référence API Aspose.Slides pour C++
description: "NotSupportedException est levée lorsqu'une méthode invoquée n'est pas prise en charge ou lorsqu'une opération tentée sur un flux n'est pas prise en charge. Ne créez jamais d'instances de cette classe manuellement. Utilisez la classe NotSupportedException à la place. Ne placez jamais les instances de la classe NotSupportedException dans System::SmartPtr."
type: docs
weight: 586
url: /fr/system/details_notsupportedexception/
---
## classe Details_NotSupportedException

NotSupportedException est levée lorsque une méthode invoquée n'est pas prise en charge ou lorsqu'une opération tentée sur un flux n'est pas prise en charge. Ne créez jamais d'instances de cette classe manuellement. Utilisez la classe NotSupportedException à la place. Ne placez jamais les instances de la classe NotSupportedException dans [System::SmartPtr](../smartptr/).

```cpp
class Details_NotSupportedException : public System::Details_SystemException
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pour usage interne uniquement. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Renvoie un dictionnaire avec des données d'exception personnalisées. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Renvoie une valeur entière 32 bits qui est un code HRESULT associé à l'exception représentée par l'objet actuel. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Renvoie une référence à l'objet représentant l'exception interne. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Renvoie la chaîne contenant la description de l'erreur. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Renvoie la chaîne contenant la trace de la pile. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Renvoie la copie de l'objet Exception représentant l'exception la plus interne. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../object/gethashcode/). Permet le hachage d'objets personnalisés. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../object/object/)([Object](../object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, il se contente d'initialiser un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Opérateur d'affectation. Ne copie rien, en réalité, il se contente d'initialiser un nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spécialisation de [Object::ReferenceEquals](../object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Définit le HRESULT, une valeur numérique codée attribuée à une exception spécifique. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de passer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Renvoie la représentation sous forme de chaîne de l'objet actuel. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | Implémente la méthode [what()](../details_exception/what/) qui est appelée par la classe [ExceptionWrapper](../exceptionwrapper/). Malgré le fait que cette classe n'hérite pas de std::exception, les classes dérivées peuvent utiliser les membres protégés/privés pour implémenter leur logique. Déplacer l'implémentation de cette méthode vers le [ExceptionWrapper](../exceptionwrapper/) pourrait casser cette logique. |
| virtual  [~Object](../object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [Details_SystemException](../details_systemexception/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)