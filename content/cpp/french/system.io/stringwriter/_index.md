---
title: StringWriter
second_title: Référence de l'API Aspose.Slides pour C++
description: "Implémente un TextWriter qui écrit des informations dans une chaîne. Les objets de cette classe ne doivent être alloués qu'à l'aide de la fonction System::MakeObject() . Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument."
type: docs
weight: 417
url: /fr/system.io/stringwriter/
---
## StringWriter classe


Implémente un [TextWriter](../textwriter/) qui écrit des informations dans une chaîne. Les objets de cette classe doivent être alloués uniquement à l'aide de la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument.

```cpp
class StringWriter : public System::IO::TextWriter
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual void [Close](../textwriter/close/)() | Ferme le flux et libère les ressources acquises. |
| void [Dispose](../textwriter/dispose/)() override | Libère toutes les ressources utilisées par l'objet actuel et ferme le flux sous-jacent. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émulé la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés comme égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émulé la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés comme égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| virtual void [Flush](../textwriter/flush/)() | Vide le contenu du tampon vers le flux sous-jacent. |
| [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Renvoie l'encodage actuellement utilisé. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Renvoie l'objet [IFormatProvider](../../system/iformatprovider/) actuellement utilisé. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Renvoie l'objet [IFormatProvider](../../system/iformatprovider/) actuellement utilisé. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Renvoie une chaîne de terminaison de ligne. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Renvoie une chaîne de terminaison de ligne. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage des objets personnalisés. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\> [GetStringBuilder](./getstringbuilder/)() | Renvoie le StringBuilder actuellement utilisé. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
| [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie en fait rien, il initialise simplement un nouvel objet et permet la construction de copies des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie en fait rien, il initialise simplement un nouvel objet et permet la construction de copies des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Définit une chaîne de terminaison de ligne. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Construit une nouvelle instance de [StringWriter](./) en utilisant le StringBuilder spécifié et [IFormatProvider](../../system/iformatprovider/). |
| [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Construit une nouvelle instance de [StringWriter](./) en utilisant le StringBuilder spécifié et [IFormatProvider](../../system/iformatprovider/) de la culture actuelle. |
| [StringWriter](./stringwriter/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Construit une nouvelle instance de [StringWriter](./) en utilisant le [IFormatProvider](../../system/iformatprovider/) spécifié. |
| [StringWriter](./stringwriter/)() | Construit une nouvelle instance de [StringWriter](./) en utilisant [IFormatProvider](../../system/iformatprovider/) de la culture actuelle. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Renvoie la chaîne sous-jacent. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| void [Write](./write/)(char_t) override | Écrit le caractère spécifié dans le flux. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Écrit la sous-plage spécifiée de caractères du tableau de caractères spécifié dans le flux. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Écrit la chaîne spécifiée dans le flux. |
| virtual void [Write](../textwriter/write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Écrit la représentation sous forme de chaîne de l'objet spécifié dans le flux. |
| virtual void [Write](../textwriter/write/)(**bool**) | Écrit la représentation sous forme de chaîne de la valeur booléenne spécifiée dans le flux. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Écrit la représentation sous forme de chaîne de l'objet [Decimal](../../system/decimal/) spécifié dans le flux. |
| virtual void [Write](../textwriter/write/)(**double**) | Écrit la représentation sous forme de chaîne de la valeur flottante double-précision spécifiée dans le flux. |
| virtual void [Write](../textwriter/write/)(int) | Écrit la représentation sous forme de chaîne de la valeur entière 32 bits spécifiée dans le flux. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Écrit la représentation sous forme de chaîne de la valeur entière 64 bits spécifiée dans le flux. |
| virtual void [Write](../textwriter/write/)(**float**) | Écrit la représentation sous forme de chaîne de la valeur flottante simple précision spécifiée dans le flux. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Écrit la représentation sous forme de chaîne de la valeur entière non signée 32 bits spécifiée dans le flux. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Écrit la représentation sous forme de chaîne de la valeur entière non signée 64 bits spécifiée dans le flux. |
| virtual void [Write](../textwriter/write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Écrit tous les caractères du tableau spécifié dans le flux. |
| virtual void [Write](../textwriter/write/)(const char_t *) | Écrit la chaîne C spécifiée dans le flux. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Écrit la représentation sous forme de chaîne de l'objet [TypeInfo](../../system/typeinfo/) spécifié dans le flux. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Écrit les valeurs spécifiées formatées selon le format indiqué dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)() | Écrit les caractères de terminaison de ligne dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Écrit la représentation sous forme de chaîne de l'objet spécifié suivie des caractères de terminaison de ligne dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Écrit la représentation sous forme de chaîne de la valeur booléenne spécifiée suivie des caractères de terminaison de ligne dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Écrit le caractère spécifié suivi des caractères de terminaison de ligne dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Écrit la représentation sous forme de chaîne de l'objet [Decimal](../../system/decimal/) spécifié suivie des caractères de terminaison de ligne dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Écrit la représentation sous forme de chaîne de la valeur double-précision spécifiée suivie des caractères de terminaison de ligne dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Écrit la représentation sous forme de chaîne de la valeur entière 32 bits spécifiée suivie des caractères de terminaison de ligne dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Écrit la représentation sous forme de chaîne de la valeur entière 64 bits spécifiée suivie des caractères de terminaison de ligne dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Écrit la représentation sous forme de chaîne de la valeur flottante simple précision spécifiée suivie des caractères de terminaison de ligne dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&) | Écrit la chaîne spécifiée suivie des caractères de terminaison de ligne dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Écrit la représentation sous forme de chaîne de la valeur entière non signée 32 bits spécifiée suivie des caractères de terminaison de ligne dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Écrit la représentation sous forme de chaîne de la valeur entière non signée 64 bits spécifiée suivie des caractères de terminaison de ligne dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Écrit tous les caractères du tableau spécifié suivis des caractères de terminaison de ligne dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Écrit la sous-plage spécifiée de caractères UTF-16 du tableau de caractères spécifié suivie des caractères de terminaison de ligne dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)(const char_t *) | Écrit la chaîne C spécifiée suivie des caractères de terminaison de ligne dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Écrit la représentation sous forme de chaîne de l'objet [TypeInfo](../../system/typeinfo/) spécifié suivie des caractères de terminaison de ligne dans le flux. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Écrit les valeurs spécifiées formatées selon le format indiqué suivies des caractères de terminaison de ligne dans le flux. |
| virtual [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |
| virtual [~TextWriter](../textwriter/~textwriter/)() | Destructeur. |
## Voir aussi

* Classe [TextWriter](../textwriter/)
* Espace de noms [System::IO](../)
* Bibliothèque [Aspose.Slides](../../)