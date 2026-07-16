---
title: NumberFormatInfo
second_title: Référence de l'API Aspose.Slides pour C++
description: "Contient des informations sur la façon de formater les nombres. Les opérations de définition ne sont activées que sur des objets non en lecture seule. Les objets de cette classe doivent être alloués uniquement à l'aide de la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument."
type: docs
weight: 248
url: /fr/system.globalization/numberformatinfo/
---
## NumberFormatInfo classe

Contient des informations sur la façon de formater les nombres. Les opérations de définition ne sont activées que sur des objets non en lecture seule. Les objets de cette classe ne doivent être alloués qu’en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d’instance de ce type sur la pile ou en utilisant l’opérateur new, car cela entraînera des erreurs d’exécution et/ou des fautes d’assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu’argument.

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## Méthodes

| Méthode | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Clone les informations de format. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence au style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur au style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À usage interne uniquement. |
| int [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | Obtient le nombre de chiffres décimaux de la monnaie. |
| [String](../../system/string/) [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | Obtient le séparateur décimal de la monnaie. |
| [String](../../system/string/) [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | Obtient le séparateur de groupe de la monnaie. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | Obtient le nombre de chiffres décimaux de la monnaie par groupe. |
| int [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | Obtient le modèle de négatif de la monnaie. |
| int [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | Obtient le modèle de positif de la monnaie. |
| [String](../../system/string/) [get_CurrencySymbol](./get_currencysymbol/)() const | Obtient le symbole de la monnaie. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | Obtient les informations de format de nombre définies par la culture du thread actuel. |
| [DigitShapes](../digitshapes/) [get_DigitSubstitution](./get_digitsubstitution/)() const | Obtient une valeur qui spécifie comment afficher la forme d’un chiffre. |
| static const [NumberFormatInfoPtr](../numberformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | Obtient les informations de format de nombre définies par la culture invariante. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Vérifie si le format est en lecture seule. |
| [String](../../system/string/) [get_NaNSymbol](./get_nansymbol/)() const | Obtient le symbole Not-a-Number. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_NativeDigits](./get_nativedigits/)() const | Obtient les symboles des chiffres (de 0 à 9). |
| [String](../../system/string/) [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | Obtient le symbole de l’infini négatif. |
| [String](../../system/string/) [get_NegativeSign](./get_negativesign/)() const | Obtient le signe négatif. |
| int [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | Obtient le nombre de chiffres décimaux. |
| [String](../../system/string/) [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | Obtient le séparateur décimal. |
| [String](../../system/string/) [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | Obtient le séparateur de groupe de nombre. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_NumberGroupSizes](./get_numbergroupsizes/)() const | Obtient le nombre de chiffres par groupe. |
| int [get_NumberNegativePattern](./get_numbernegativepattern/)() const | Obtient le modèle négatif du nombre. |
| int [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | Obtient le nombre de décimales dans les valeurs en pourcentage. |
| [String](../../system/string/) [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | Obtient le séparateur décimal dans les valeurs en pourcentage. |
| [String](../../system/string/) [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | Obtient le séparateur de groupe dans les valeurs en pourcentage. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_PercentGroupSizes](./get_percentgroupsizes/)() const | Obtient le nombre de chiffres par groupe de valeur en pourcentage. |
| int [get_PercentNegativePattern](./get_percentnegativepattern/)() const | Obtient le modèle négatif du pourcentage. |
| int [get_PercentPositivePattern](./get_percentpositivepattern/)() const | Obtient le modèle positif du pourcentage. |
| [String](../../system/string/) [get_PercentSymbol](./get_percentsymbol/)() const | Obtient le symbole de pourcentage. |
| [String](../../system/string/) [get_PerMilleSymbol](./get_permillesymbol/)() const | Obtient le symbole per-mille. |
| [String](../../system/string/) [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | Obtient le symbole de l’infini positif. |
| [String](../../system/string/) [get_PositiveSign](./get_positivesign/)() const | Obtient le signe positif. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l’objet. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Obtient le formateur d’un type spécifique. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d’objets personnalisés. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Obtient le formateur associé au fournisseur de format. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l’objet. Analogue de l’appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l’objet représente une instance du type décrit par targetType. Analogue de l’opérateur C# 'is'. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [NumberFormatInfo](./numberformatinfo/)() | Constructeur par défaut (invariant [NumberFormatInfo](./)). |
|  [Object](../../system/object/object/)() | Crée l’objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [NumberFormatInfo](./)\& [operator=](./operator_equal/)(const [NumberFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d’affectation. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [ReadOnly](./readonly/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | Obtient la version en lecture seule du formateur. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d’une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| void [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | Définit le nombre de chiffres décimaux de la monnaie. |
| void [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const [String](../../system/string/)\&) | Définit le séparateur décimal de la monnaie. |
| void [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const [String](../../system/string/)\&) | Définit le séparateur de groupe de la monnaie. |
| void [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Définit le nombre de chiffres décimaux de la monnaie par groupe. |
| void [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | Définit le modèle négatif de la monnaie. |
| void [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | Définit le modèle positif de la monnaie. |
| void [set_CurrencySymbol](./set_currencysymbol/)(const [String](../../system/string/)\&) | Définit le symbole de la monnaie. |
| void [set_DigitSubstitution](./set_digitsubstitution/)([DigitShapes](../digitshapes/)) | Définit une valeur qui spécifie comment afficher la forme d’un chiffre. |
| void [set_NaNSymbol](./set_nansymbol/)(const [String](../../system/string/)\&) | Définit le symbole Not-a-Number. |
| void [set_NativeDigits](./set_nativedigits/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Définit les symboles des chiffres (de 0 à 9). |
| void [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const [String](../../system/string/)\&) | Définit le symbole d’infini négatif. |
| void [set_NegativeSign](./set_negativesign/)(const [String](../../system/string/)\&) | Définit le signe négatif. |
| void [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | Définit le nombre de chiffres décimaux. |
| void [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const [String](../../system/string/)\&) | Définit le séparateur décimal. |
| void [set_NumberGroupSeparator](./set_numbergroupseparator/)(const [String](../../system/string/)\&) | Définit le séparateur de groupe de nombre. |
| void [set_NumberGroupSizes](./set_numbergroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Définit le nombre de chiffres par groupe. |
| void [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | Définit le modèle négatif du nombre. |
| void [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | Définit le nombre de décimales dans les valeurs en pourcentage. |
| void [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const [String](../../system/string/)\&) | Définit le séparateur décimal dans les valeurs en pourcentage. |
| void [set_PercentGroupSeparator](./set_percentgroupseparator/)(const [String](../../system/string/)\&) | Définit le séparateur de groupe dans les valeurs en pourcentage. |
| void [set_PercentGroupSizes](./set_percentgroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Définit le nombre de chiffres par groupe de valeur en pourcentage. |
| void [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | Définit le modèle négatif du pourcentage. |
| void [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | Définit le modèle positif du pourcentage. |
| void [set_PercentSymbol](./set_percentsymbol/)(const [String](../../system/string/)\&) | Définit le symbole de pourcentage. |
| void [set_PerMilleSymbol](./set_permillesymbol/)(const [String](../../system/string/)\&) | Définit le symbole per-mille. |
| void [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const [String](../../system/string/)\&) | Définit le symbole d’infini positif. |
| void [set_PositiveSign](./set_positivesign/)(const [String](../../system/string/)\&) | Définit le signe positif. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de changer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l’objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [Object](../../system/object/)
* Classe [IFormatProvider](../../system/iformatprovider/)
* Classe [ICloneable](../../system/icloneable/)
* Espace de noms [System::Globalization](../)
* Bibliothèque [Aspose.Slides](../../)