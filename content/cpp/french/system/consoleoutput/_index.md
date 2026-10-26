---
title: ConsoleOutput
second_title: Référence API Aspose.Slides pour C++
description: "Représente le flux de sortie standard. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction System::MakeObject() . Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument."
type: docs
weight: 209
url: /fr/system/consoleoutput/
---
## ConsoleOutput classe

Représente le flux de sortie standard. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument.

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual void [Close](../../system.io/textwriter/close/)() | Ferme le flux et libère les ressources acquises. |
| void [Dispose](../../system.io/textwriter/dispose/)() override | Libère toutes les ressources utilisées par l'objet actuel et ferme le flux sous-jacent. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison à virgule flottante à la C# où deux NaN sont considérés égaux bien que selon IEC 60559:1989 le NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison à virgule flottante à la C# où deux NaN sont considérés égaux bien que selon IEC 60559:1989 le NaN ne soit égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| virtual void [Flush](../../system.io/textwriter/flush/)() | Vide le contenu du tampon vers le flux sous-jacent. |
| [SharedPtr](../sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Retourne toujours l'encodage ASCII. |
| virtual [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\> [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() const | Retourne l'objet [IFormatProvider](../iformatprovider/) actuellement utilisé. |
| [IFormatProviderPtr](../iformatproviderptr/) [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() | Retourne l'objet [IFormatProvider](../iformatprovider/) actuellement utilisé. |
| virtual [System::String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() const | Retourne une chaîne de terminaison de ligne. |
| [String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() | Retourne une chaîne de terminaison de ligne. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../object/object/)([Object](../object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, il se contente d'initialiser un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Opérateur d’affectation. Ne copie rien, en réalité, il se contente d'initialiser un nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spécialisation de [Object::ReferenceEquals](../object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| virtual void [set_NewLine](../../system.io/textwriter/set_newline/)(const [System::String](../string/)\&) | Définit une chaîne de terminaison de ligne. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de passer les pointeurs des conteneurs en mode faible. |
| int [SharedCount](../object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implémente la construction C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [Write](./write/)(**bool**) override | Émet la représentation sous forme de chaîne de la valeur booléenne spécifiée vers le flux de sortie représenté par l'objet actuel. |
| void [Write](./write/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Émet la représentation sous forme de chaîne de l'objet spécifié vers le flux de sortie représenté par l'objet actuel. |
| void [Write](./write/)(char_t) override | Émet la valeur de caractère spécifiée vers le flux de sortie représenté par l'objet actuel. |
| void [Write](./write/)([Decimal](../decimal/)) override | Émet la représentation sous forme de chaîne de la valeur [Decimal](../decimal/) vers le flux de sortie représenté par l'objet actuel. |
| void [Write](./write/)(**double**) override | Émet la représentation sous forme de chaîne de la valeur à virgule flottante double précision vers le flux de sortie représenté par l'objet actuel. |
| void [Write](./write/)(**int32_t**) override | Émet la représentation sous forme de chaîne de la valeur entière 32 bits vers le flux de sortie représenté par l'objet actuel. |
| void [Write](./write/)(**int64_t**) override | Émet la représentation sous forme de chaîne de la valeur entière 64 bits vers le flux de sortie représenté par l'objet actuel. |
| void [Write](./write/)(**float**) override | Émet la représentation sous forme de chaîne de la valeur à virgule flottante simple précision vers le flux de sortie représenté par l'objet actuel. |
| void [Write](./write/)(const [String](../string/)\&) override | Émet l'objet chaîne spécifié vers le flux de sortie représenté par l'objet actuel. |
| void [Write](./write/)(**uint32_t**) override | Émet la représentation sous forme de chaîne de la valeur entière non signée 32 bits vers le flux de sortie représenté par l'objet actuel. |
| void [Write](./write/)(**uint64_t**) override | Émet la représentation sous forme de chaîne de la valeur entière non signée 64 bits vers le flux de sortie représenté par l'objet actuel. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Émet la représentation sous forme de chaîne du tableau de caractères spécifié vers le flux de sortie représenté par l'objet actuel. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Émet la représentation sous forme de chaîne d'une plage de valeurs du tableau de caractères spécifié vers le flux de sortie représenté par l'objet actuel. |
| void [Write](./write/)(const char_t *) override | Émet la chaîne C spécifiée vers le flux de sortie représenté par l'objet actuel. |
| void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) override | Émet la représentation sous forme de chaîne de l'objet [TypeInfo](../typeinfo/) spécifié vers le flux de sortie représenté par l'objet actuel. |
| void [Write](./write/)(const char *) |  |
| virtual void [Write](../../system.io/textwriter/write/)(int) | Écrit la représentation sous forme de chaîne de la valeur entière 32 bits spécifiée dans le flux. |
| void [Write](../../system.io/textwriter/write/)(const [String](../string/)\&, const TArgs\&...) | Écrit les valeurs spécifiées formatées selon le format indiqué dans le flux. |
| void [WriteLine](./writeline/)() override | Émet le terminateur de ligne actuel vers le flux de sortie représenté par l'objet actuel. |
| void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Émet la représentation sous forme de chaîne de l'objet spécifié suivie du terminateur de ligne actuel vers le flux de sortie représenté par l'objet actuel. |
| void [WriteLine](./writeline/)(**bool**) override | Émet la représentation sous forme de chaîne de la valeur booléenne spécifiée suivie du terminateur de ligne actuel vers le flux de sortie représenté par l'objet actuel. |
| void [WriteLine](./writeline/)(char_t) override | Émet la valeur de caractère spécifiée suivie du terminateur de ligne actuel vers le flux de sortie représenté par l'objet actuel. |
| void [WriteLine](./writeline/)([Decimal](../decimal/)) override | Émet la représentation sous forme de chaîne de la valeur [Decimal](../decimal/) suivie du terminateur de ligne actuel vers le flux de sortie représenté par l'objet actuel. |
| void [WriteLine](./writeline/)(**double**) override | Émet la représentation sous forme de chaîne de la valeur à virgule flottante double précision suivie du terminateur de ligne actuel vers le flux de sortie représenté par l'objet actuel. |
| void [WriteLine](./writeline/)(int) override | Émet la représentation sous forme de chaîne de la valeur entière 32 bits suivie du terminateur de ligne actuel vers le flux de sortie représenté par l'objet actuel. |
| void [WriteLine](./writeline/)(**int64_t**) override | Émet la représentation sous forme de chaîne de la valeur entière 64 bits suivie du terminateur de ligne actuel vers le flux de sortie représenté par l'objet actuel. |
| void [WriteLine](./writeline/)(**float**) override | Émet la représentation sous forme de chaîne de la valeur à virgule flottante simple précision suivie du terminateur de ligne actuel vers le flux de sortie représenté par l'objet actuel. |
| void [WriteLine](./writeline/)(const [String](../string/)\&) override | Émet l'objet chaîne spécifié suivi du terminateur de ligne actuel vers le flux de sortie représenté par l'objet actuel. |
| void [WriteLine](./writeline/)(**uint32_t**) override | Émet la représentation sous forme de chaîne de la valeur entière non signée 32 bits suivie du terminateur de ligne actuel vers le flux de sortie représenté par l'objet actuel. |
| void [WriteLine](./writeline/)(**uint64_t**) override | Émet la représentation sous forme de chaîne de la valeur entière non signée 64 bits suivie du terminateur de ligne actuel vers le flux de sortie représenté par l'objet actuel. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Émet la représentation sous forme de chaîne du tableau de caractères spécifié suivi du terminateur de ligne actuel vers le flux de sortie représenté par l'objet actuel. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Émet la représentation sous forme de chaîne d'une plage de valeurs du tableau de caractères spécifié suivie du terminateur de ligne actuel vers le flux de sortie représenté par l'objet actuel. |
| void [WriteLine](./writeline/)(const char_t *) override | Émet la chaîne C spécifiée suivie du terminateur de ligne actuel vers le flux de sortie représenté par l'objet actuel. |
| void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) override | Émet la représentation sous forme de chaîne de l'objet [TypeInfo](../typeinfo/) spécifié suivi du terminateur de ligne actuel vers le flux de sortie représenté par l'objet actuel. |
| void [WriteLine](./writeline/)(const char *) |  |
| void [WriteLine](../../system.io/textwriter/writeline/)(const [String](../string/)\&, const TArgs\&...) | Écrit les valeurs spécifiées formatées selon le format indiqué suivies des caractères de terminaison de ligne dans le flux. |
| virtual  [~Object](../object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |
| virtual  [~TextWriter](../../system.io/textwriter/~textwriter/)() | Destructeur. |
## Voir aussi

* Classe [TextWriter](../../system.io/textwriter/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)