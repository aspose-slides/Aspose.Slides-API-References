---
title: StreamWriter
second_title: Référence API Aspose.Slides pour C++
description: "Représente un écrivain qui écrit des caractères dans un flux d'octets. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument."
type: docs
weight: 391
url: /fr/system.io/streamwriter/
---
## StreamWriter classe

Represents a writer that writes characters to a byte stream. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StreamWriter : public System::IO::TextWriter
```

## Méthodes

| Méthode | Description |
| --- | --- |
| void [Close](./close/)() override | Ferme le flux et libère les ressources acquises. |
| void [Dispose](./dispose/)() override | Libère toutes les ressources utilisées par l'objet actuel et ferme le flux sous-jacent. |
| virtual void [Dispose](./dispose/)(**bool**) | Libère toutes les ressources utilisées par l'objet actuel et ferme le flux sous-jacent. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante C# où deux NaN sont considérés égaux bien que selon IEC 60559:1989 le NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante C# où deux NaN sont considérés égaux bien que selon IEC 60559:1989 le NaN ne soit égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| void [Flush](./flush/)() override | Vide le contenu du tampon vers le flux sous-jacent puis vide le flux sous-jacent. |
| **bool** [get_AutoFlush](./get_autoflush/)() const | Renvoie une valeur indiquant si le [StreamWriter](./) vide les données vers le flux sous-jacent chaque fois que la méthode [StreamWriter::Write](./write/) est appelée. |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | Renvoie un pointeur partagé vers un objet qui représente le flux sous-jacent. |
| [EncodingPtr](../../system/encodingptr/) [get_Encoding](./get_encoding/)() override | Renvoie le codage actuellement utilisé. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Renvoie l'objet [IFormatProvider](../../system/iformatprovider/) actuellement utilisé. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Renvoie l'objet [IFormatProvider](../../system/iformatprovider/) actuellement utilisé. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Renvoie une chaîne de terminaison de ligne. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Renvoie une chaîne de terminaison de ligne. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, vraiment, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, vraiment, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| void [set_AutoFlush](./set_autoflush/)(**bool**) | Renvoie une valeur qui spécifie si le [StreamWriter](./) doit vider les données vers le flux sous-jacent chaque fois que la méthode [StreamWriter::Write](./write/) est appelée. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Définit une chaîne de terminaison de ligne. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le nᵉième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de passer les pointeurs des conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Construit une instance de l'objet [StreamWriter](./) qui écrit des caractères vers le flux sous-jacent spécifié en utilisant l'encodage UTF-8 et un tampon de taille par défaut de 1024 octets. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Construit une instance de l'objet [StreamWriter](./) qui écrit des caractères vers le flux sous-jacent spécifié en utilisant l'encodage spécifié et un tampon de taille par défaut de 1024 octets. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, int, **bool**) | Construit une instance de l'objet [StreamWriter](./) qui écrit des caractères vers le flux sous-jacent spécifié en utilisant l'encodage spécifié et un tampon de la taille spécifiée. Un paramètre indique si le flux sous-jacent doit être fermé lorsque l'objet [StreamWriter](./) est libéré. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&) | Construit une instance de l'objet [StreamWriter](./) qui écrit des caractères dans le fichier spécifié en utilisant l'encodage UTF-8 et un tampon de taille par défaut de 1024 octets. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&) | Construit une instance de l'objet [StreamWriter](./) qui écrit des caractères dans le fichier spécifié en utilisant l'encodage spécifié et un tampon de taille par défaut de 1024 octets. Un paramètre indique si les données doivent être ajoutées au fichier ou si le fichier doit être écrasé. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&, int) | Construit une instance de l'objet [StreamWriter](./) qui écrit des caractères dans le fichier spécifié en utilisant l'encodage spécifié et la taille du tampon. Un paramètre indique si les données doivent être ajoutées au fichier ou si le fichier doit être écrasé. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [Write](./write/)(char_t) override | Écrit le caractère spécifié dans le flux. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Écrit la chaîne spécifiée dans le flux. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Écrit la représentation sous forme de chaîne de l'objet spécifié dans le flux. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Écrit tous les caractères du tableau spécifié dans le flux. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Écrit la sous-plage spécifiée de caractères UTF-16 du tableau de caractères spécifié dans le flux. |
| void [Write](./write/)(const char_t *) override | Écrit la chaîne C spécifiée dans le flux. |
| void [Write](./write/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Écrit la représentation sous forme de chaîne de l'objet spécifié dans le flux. |
| virtual void [Write](../textwriter/write/)(**bool**) | Écrit la représentation sous forme de chaîne de la valeur booléenne spécifiée dans le flux. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Écrit la représentation sous forme de chaîne de l'objet [Decimal](../../system/decimal/) spécifié dans le flux. |
| virtual void [Write](../textwriter/write/)(**double**) | Écrit la représentation sous forme de chaîne de la valeur en virgule flottante double-précision spécifiée dans le flux. |
| virtual void [Write](../textwriter/write/)(int) | Écrit la représentation sous forme de chaîne de la valeur entière 32-bits spécifiée dans le flux. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Écrit la représentation sous forme de chaîne de la valeur entière 64-bits spécifiée dans le flux. |
| virtual void [Write](../textwriter/write/)(**float**) | Écrit la représentation sous forme de chaîne de la valeur en virgule flottante simple précision spécifiée dans le flux. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Écrit la représentation sous forme de chaîne de la valeur entière non signée 32-bits spécifiée dans le flux. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Écrit la représentation sous forme de chaîne de la valeur entière non signée 64-bits spécifiée dans le flux. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Écrit la représentation sous forme de chaîne de l'objet [TypeInfo](../../system/typeinfo/) spécifié dans le flux. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Écrit les valeurs spécifiées formatées selon le format spécifié dans le flux. |
| void [WriteLine](./writeline/)() override | Écrit les caractères de terminaison de ligne dans le flux. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&) override | Écrit la chaîne spécifiée suivie des caractères de terminaison de ligne dans le flux. |
| void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Écrit la représentation sous forme de chaîne de l'objet spécifié suivie des caractères de terminaison de ligne dans le flux. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Écrit tous les caractères du tableau spécifié suivis des caractères de terminaison de ligne dans le flux. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Écrit la sous-plage spécifiée de caractères UTF-16 du tableau de caractères spécifié suivie des caractères de terminaison de ligne dans le flux. |
| void [WriteLine](./writeline/)(const char_t *) override | Écrit la chaîne C spécifiée suivie des caractères de terminaison de ligne dans le flux. |
| void [WriteLine](./writeline/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Écrit la représentation sous forme de chaîne de l'objet spécifié suivie des caractères de terminaison de ligne dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Écrit la représentation sous forme de chaîne de la valeur booléenne spécifiée suivie des caractères de terminaison de ligne dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Écrit le caractère spécifié suivi des caractères de terminaison de ligne dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Écrit la représentation sous forme de chaîne de l'objet [Decimal](../../system/decimal/) spécifié suivie des caractères de terminaison de ligne dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Écrit la représentation sous forme de chaîne de la valeur en virgule flottante double-précision spécifiée suivie des caractères de terminaison de ligne dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Écrit la représentation sous forme de chaîne de la valeur entière 32-bits spécifiée suivie des caractères de terminaison de ligne dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Écrit la représentation sous forme de chaîne de la valeur entière 64-bits spécifiée suivie des caractères de terminaison de ligne dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Écrit la représentation sous forme de chaîne de la valeur en virgule flottante simple précision spécifiée suivie des caractères de terminaison de ligne dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Écrit la représentation sous forme de chaîne de la valeur entière non signée 32-bits spécifiée suivie des caractères de terminaison de ligne dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Écrit la représentation sous forme de chaîne de la valeur entière non signée 64-bits spécifiée suivie des caractères de terminaison de ligne dans le flux. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Écrit la représentation sous forme de chaîne de l'objet [TypeInfo](../../system/typeinfo/) spécifié suivie des caractères de terminaison de ligne dans le flux. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Écrit les valeurs spécifiées formatées selon le format spécifié suivies des caractères de terminaison de ligne dans le flux. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |
|  [~StreamWriter](./~streamwriter/)() | Destructeur. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Destructeur. |

## Voir aussi

* Classe [TextWriter](../textwriter/)
* Espace de noms [System::IO](../)
* Bibliothèque [Aspose.Slides](../../)