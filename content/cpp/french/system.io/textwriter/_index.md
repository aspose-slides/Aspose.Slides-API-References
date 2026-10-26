---
title: TextWriter
second_title: "Référence de l'API Aspose.Slides pour C++"
description: "Une classe de base pour les classes qui représentent des écrivains écrivant des séquences de caractères vers différentes destinations. Les objets de cette classe ne doivent être alloués qu'à l'aide de la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des violations d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument."
type: docs
weight: 443
url: /fr/system.io/textwriter/
---
## TextWriter classe

Une classe de base pour les classes qui représentent des écrivains qui écrivent des séquences de caractères vers différentes destinations. Les objets de cette classe ne doivent être alloués qu'à l'aide de la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument.

```cpp
class TextWriter : public System::IDisposable
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual void [Close](./close/)() | Ferme le flux et libère les ressources acquises. |
| void [Dispose](./dispose/)() override | Libère toutes les ressources utilisées par l'objet actuel et ferme le flux sous-jacent. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| virtual void [Flush](./flush/)() | Vide le contenu du tampon vers le flux sous-jacent. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Renvoie l'encodage actuellement utilisé. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](./get_formatprovider/)() const | Renvoie l'objet [IFormatProvider](../../system/iformatprovider/) actuellement utilisé. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](./get_formatprovider/)() | Renvoie l'objet [IFormatProvider](../../system/iformatprovider/) actuellement utilisé. |
| virtual [System::String](../../system/string/) [get_NewLine](./get_newline/)() const | Renvoie une chaîne terminatrice de ligne. |
| [String](../../system/string/) [get_NewLine](./get_newline/)() | Renvoie une chaîne terminatrice de ligne. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
| [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| virtual void [set_NewLine](./set_newline/)(const [System::String](../../system/string/)\&) | Définit une chaîne terminatrice de ligne. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de passer les pointeurs des conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Écrit la représentation chaîne de l'objet spécifié dans le flux. |
| virtual void [Write](./write/)(**bool**) | Écrit la représentation chaîne de la valeur booléenne spécifiée dans le flux. |
| virtual void [Write](./write/)(char_t) | Écrit le caractère spécifié dans le flux. |
| virtual void [Write](./write/)([Decimal](../../system/decimal/)) | Écrit la représentation chaîne de l'objet [Decimal](../../system/decimal/) spécifié dans le flux. |
| virtual void [Write](./write/)(**double**) | Écrit la représentation chaîne de la valeur à double précision spécifiée dans le flux. |
| virtual void [Write](./write/)(int) | Écrit la représentation chaîne de la valeur entière 32 bits spécifiée dans le flux. |
| virtual void [Write](./write/)(**int64_t**) | Écrit la représentation chaîne de la valeur entière 64 bits spécifiée dans le flux. |
| virtual void [Write](./write/)(**float**) | Écrit la représentation chaîne de la valeur à simple précision spécifiée dans le flux. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | Écrit la chaîne spécifiée dans le flux. |
| virtual void [Write](./write/)(**uint32_t**) | Écrit la représentation chaîne de la valeur entière non signée 32 bits spécifiée dans le flux. |
| virtual void [Write](./write/)(**uint64_t**) | Écrit la représentation chaîne de la valeur entière non signée 64 bits spécifiée dans le flux. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Écrit tous les caractères du tableau spécifié dans le flux. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Écrit la sous-plage spécifiée de caractères UTF-16 du tableau de caractères spécifié dans le flux. |
| virtual void [Write](./write/)(const char_t *) | Écrit la c-string spécifiée dans le flux. |
| virtual void [Write](./write/)(const [TypeInfo](../../system/typeinfo/)\&) | Écrit la représentation chaîne de l'objet [TypeInfo](../../system/typeinfo/) spécifié dans le flux. |
| void [Write](./write/)(const [String](../../system/string/)\&, const TArgs\&...) | Écrit les valeurs spécifiées formatées selon le format indiqué dans le flux. |
| virtual void [WriteLine](./writeline/)() | Écrit les caractères terminateurs de ligne dans le flux. |
| virtual void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Écrit la représentation chaîne de l'objet spécifié suivie des caractères terminateurs de ligne dans le flux. |
| virtual void [WriteLine](./writeline/)(**bool**) | Écrit la représentation chaîne de la valeur booléenne spécifiée suivie des caractères terminateurs de ligne dans le flux. |
| virtual void [WriteLine](./writeline/)(char_t) | Écrit le caractère spécifié suivi des caractères terminateurs de ligne dans le flux. |
| virtual void [WriteLine](./writeline/)([Decimal](../../system/decimal/)) | Écrit la représentation chaîne de l'objet [Decimal](../../system/decimal/) spécifié suivie des caractères terminateurs de ligne dans le flux. |
| virtual void [WriteLine](./writeline/)(**double**) | Écrit la représentation chaîne de la valeur à double précision spécifiée suivie des caractères terminateurs de ligne dans le flux. |
| virtual void [WriteLine](./writeline/)(int) | Écrit la représentation chaîne de la valeur entière 32 bits spécifiée suivie des caractères terminateurs de ligne dans le flux. |
| virtual void [WriteLine](./writeline/)(**int64_t**) | Écrit la représentation chaîne de la valeur entière 64 bits spécifiée suivie des caractères terminateurs de ligne dans le flux. |
| virtual void [WriteLine](./writeline/)(**float**) | Écrit la représentation chaîne de la valeur à simple précision spécifiée suivie des caractères terminateurs de ligne dans le flux. |
| virtual void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Écrit la chaîne spécifiée suivie des caractères terminateurs de ligne dans le flux. |
| virtual void [WriteLine](./writeline/)(**uint32_t**) | Écrit la représentation chaîne de la valeur entière non signée 32 bits spécifiée suivie des caractères terminateurs de ligne dans le flux. |
| virtual void [WriteLine](./writeline/)(**uint64_t**) | Écrit la représentation chaîne de la valeur entière non signée 64 bits spécifiée suivie des caractères terminateurs de ligne dans le flux. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Écrit tous les caractères du tableau spécifié suivis des caractères terminateurs de ligne dans le flux. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Écrit la sous-plage spécifiée de caractères UTF-16 du tableau de caractères spécifié suivie des caractères terminateurs de ligne dans le flux. |
| virtual void [WriteLine](./writeline/)(const char_t *) | Écrit la c-string spécifiée suivie des caractères terminateurs de ligne dans le flux. |
| virtual void [WriteLine](./writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Écrit la représentation chaîne de l'objet [TypeInfo](../../system/typeinfo/) spécifié suivie des caractères terminateurs de ligne dans le flux. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Écrit les valeurs spécifiées formatées selon le format indiqué suivies des caractères terminateurs de ligne dans le flux. |
| virtual [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |
| virtual [~TextWriter](./~textwriter/)() | Destructeur. |

## Définitions de type

| Alias de type | Description |
| --- | --- |
| [Ptr](./ptr/) | Un alias pour un pointeur partagé vers cette classe. |

## Voir aussi

* Classe [IDisposable](../../system/idisposable/)
* Espace de noms [System::IO](../)
* Bibliothèque [Aspose.Slides](../../)