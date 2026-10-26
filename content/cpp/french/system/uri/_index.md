---
title: Uri
second_title: Référence API Aspose.Slides pour C++
description: "Identificateur de ressource uniforme. Les objets de cette classe doivent être alloués uniquement à l'aide de la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des défauts d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument."
type: docs
weight: 1366
url: /fr/system/uri/
---
## Uri classe

Identificateur de ressource uniforme. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des défauts d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument.

```cpp
class Uri : public System::Object
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static [UriHostNameType](../urihostnametype/) [CheckHostName](./checkhostname/)([String](../string/)) | Détermine le type du nom d'hôte spécifié. |
| static **bool** [CheckSchemeName](./checkschemename/)(const [String](../string/)\&) | Détermine si le schéma spécifié est valide. |
| static **int32_t** [Compare](./compare/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [UriComponents](../uricomponents/), [UriFormat](../uriformat/), [StringComparison](../stringcomparison/)) | Compare les objets [Uri](./) spécifiés en utilisant les règles de comparaison spécifiées. |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override | Détermine si les URI représentés par l'objet actuel et l'objet spécifié sont égaux. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés comme égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés comme égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| static [String](../string/) [EscapeDataString](./escapedatastring/)(const [String](../string/)\&) | Convertit une chaîne en sa représentation échappée. |
| static [String](../string/) [EscapeUriString](./escapeuristring/)(const [String](../string/)\&) | Convertit une chaîne URI en sa représentation échappée. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| static **int32_t** [FromHex](./fromhex/)(char16_t) | Obtient la valeur décimale d'un chiffre hexadécimal. |
| [String](../string/) [get_AbsolutePath](./get_absolutepath/)() const | Renvoie le chemin absolu de l'URI. |
| [String](../string/) [get_AbsoluteUri](./get_absoluteuri/)() const | Renvoie l'URI absolu. |
| [String](../string/) [get_Authority](./get_authority/)() const | Renvoie le nom d'hôte et le numéro de port d'un serveur. |
| [String](../string/) [get_DnsSafeHost](./get_dnssafehost/)() const | Renvoie un nom d'hôte non échappé. |
| [String](../string/) [get_Fragment](./get_fragment/)() const | Renvoie le fragment URI échappé. |
| [String](../string/) [get_Host](./get_host/)() const | Renvoie le nom d'hôte. |
| [UriHostNameType](../urihostnametype/) [get_HostNameType](./get_hostnametype/)() const | Renvoie le type de nom d'hôte. |
| [String](../string/) [get_IdnHost](./get_idnhost/)() const | Renvoie un nom de domaine international (IDN) de l'hôte. |
| **bool** [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | Détermine si l'URI représenté par l'objet actuel est absolu. |
| **bool** [get_IsDefaultPort](./get_isdefaultport/)() const | Détermine si l'URI représenté par l'objet actuel possède le port par défaut pour le schéma de l'URI. |
| **bool** [get_IsFile](./get_isfile/)() const | Détermine si l'URI représenté par l'objet actuel est un fichier. |
| **bool** [get_IsLoopback](./get_isloopback/)() const | Détermine si l'URI représenté par l'objet actuel fait référence à un hôte local. |
| **bool** [get_IsUnc](./get_isunc/)() const | Détermine si l'URI représenté par l'objet actuel est un chemin UNC. |
| [String](../string/) [get_LocalPath](./get_localpath/)() const | Renvoie la représentation du système d'exploitation du nom de fichier référencé par l'URI représenté par l'objet actuel. |
| [String](../string/) [get_OriginalString](./get_originalstring/)() const | Renvoie la chaîne URI qui a été passée au constructeur lors de la création de l'objet actuel. |
| [String](../string/) [get_PathAndQuery](./get_pathandquery/)() const | Renvoie le chemin absolu et les composants de requête de l'URI représenté par l'objet actuel, séparés par un point d'interrogation (?). |
| **int32_t** [get_Port](./get_port/)() const | Renvoie le numéro de port de l'URI représenté par l'objet actuel. |
| [String](../string/) [get_Query](./get_query/)() const | Renvoie les informations de requête incluses dans l'URI représenté par l'objet actuel. |
| [String](../string/) [get_Scheme](./get_scheme/)() const | Renvoie le schéma de l'URI représenté par l'objet actuel. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [get_Segments](./get_segments/)() const | Renvoie un tableau de chaînes contenant les segments de chemin de l'URI représenté par l'objet actuel. |
| **bool** [get_UserEscaped](./get_userescaped/)() const | Détermine si la chaîne URI passée au constructeur de l'objet actuel était complètement échappée. |
| [String](../string/) [get_UserInfo](./get_userinfo/)() const | Renvoie un nom d'utilisateur, un mot de passe et d'autres informations d'utilisateur associées à l'URI représenté par l'objet actuel. |
| [String](../string/) [GetComponents](./getcomponents/)([UriComponents](../uricomponents/), [UriFormat](../uriformat/)) const | Renvoie les composants spécifiés de l'URI représenté par l'objet actuel en utilisant l'échappement spécifié. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Obtient le code de hachage de l'URI. |
| [String](../string/) [GetLeftPart](./getleftpart/)([UriPartial](../uripartial/)) | Renvoie la portion spécifiée de l'URI représentée par l'objet actuel. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../object/gettype/). |
| static [String](../string/) [HexEscape](./hexescape/)(char16_t) | Renvoie l'équivalent hexadécimal du caractère spécifié. |
| static char16_t [HexUnescape](./hexunescape/)(const [String](../string/)\&, **int32_t**\&) | Convertit la représentation hexadécimale spécifiée d'un caractère en caractère. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| **bool** [IsBaseOf](./isbaseof/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) const | Détermine si l'URI représenté par l'objet [Uri](./) actuel est une base de l'URI représenté par l'objet [Uri](./) spécifié. |
| static **bool** [IsHexDigit](./ishexdigit/)(char16_t) | Détermine si le caractère spécifié représente un chiffre hexadécimal valide. |
| static **bool** [IsHexEncoding](./ishexencoding/)(const [String](../string/)\&, **int32_t**) | Détermine si un caractère dans la chaîne spécifiée à la position indiquée est encodé en hexadécimal. |
| **bool** [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | Indique si la chaîne utilisée pour construire ce [Uri](./) était bien formée et n'a pas besoin d'être davantage échappée. |
| static **bool** [IsWellFormedUriString](./iswellformeduristring/)(const [String](../string/)\&, [UriKind](../urikind/)) | Détermine si la chaîne spécifiée est un URI bien formé. |
| void [Lock](../object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../lockcontext/). |
| [String](../string/) [MakeRelative](./makerelative/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Détermine la différence entre deux instances [Uri](./). |
| [SharedPtr](../sharedptr/)\<[Uri](./)\> [MakeRelativeUri](./makerelativeuri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Détermine la différence entre les URI représentés par l'objet actuel et l'objet [Uri](./) spécifié. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../object/object/)([Object](../object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet la copie des sous-classes. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Opérateur d'affectation. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet la copie des sous-classes. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spécialisation de [Object::ReferenceEquals](../object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de passer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| [String](../string/) [ToString](./tostring/)() const override | Renvoie la représentation sous forme de chaîne de l'URI représenté par l'objet actuel. |
| static **bool** [TryCreate](./trycreate/)(const [String](../string/)\&, [UriKind](../urikind/), [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Construit un objet [Uri](./) qui représente l'URI spécifié ; un argument indique le type d'URI. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Construit un objet [Uri](./) à partir de l'objet [Uri](./) spécifié représentant l'URI de base et de la représentation chaîne de l'URI relative. |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Construit un objet [Uri](./) à partir des URI de base et relatifs spécifiés. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implémente la construction C# typeof([System.Object](../object/)). |
| static [String](../string/) [UnescapeDataString](./unescapedatastring/)(const [String](../string/)\&) | Défait l'échappement de la chaîne échappée spécifiée. |
| void [Unlock](../object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../lockcontext/). |
|  [Uri](./uri/)(const [String](../string/)\&) | Construit un objet [Uri](./) qui représente l'URI spécifié. |
|  [Uri](./uri/)(const [String](../string/)\&, **bool**) | Construit un objet [Uri](./) qui représente l'URI spécifié ; un argument indique si l'URI doit être échappé. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, **bool**) | Construit un objet [Uri](./) à partir de l'objet [Uri](./) spécifié représentant l'URI de base et de la représentation chaîne de l'URI relative ; un argument indique si l'URI doit être échappé. |
|  [Uri](./uri/)(const [String](../string/)\&, [UriKind](../urikind/)) | Construit un objet [Uri](./) qui représente l'URI spécifié ; un argument indique le type d'URI. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&) | Construit un objet [Uri](./) à partir des URI de base et relatifs spécifiés. |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | Construit un objet [Uri](./) à partir des URI de base et relatifs spécifiés. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Champs

| Champ | Description |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | Spécifie les caractères qui séparent le schéma du protocole de communication de la partie adresse du [Uri](./). |
| static [UriSchemeFile](./urischemefile/) | Spécifie que le [Uri](./) est un pointeur vers un fichier. |
| static [UriSchemeFtp](./urischemeftp/) | Spécifie que le [Uri](./) est accessible via le protocole FTP. |
| static [UriSchemeGopher](./urischemegopher/) | Spécifie que le [Uri](./) est accessible via le protocole Gopher. |
| static [UriSchemeHttp](./urischemehttp/) | Spécifie que le [Uri](./) est accessible via le protocole HTTP. |
| static [UriSchemeHttps](./urischemehttps/) | Spécifie que le [Uri](./) est accessible via le protocole HTTPS. |
| static [UriSchemeMailto](./urischememailto/) | Spécifie que le [Uri](./) est une adresse e-mail et est accessible via le protocole SMTP. |
| static [UriSchemeNetPipe](./urischemenetpipe/) | Spécifie que le [Uri](./) est accessible via le schéma NetPipe utilisé par [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNetTcp](./urischemenettcp/) | Spécifie que le [Uri](./) est accessible via le schéma NetTcp utilisé par [Windows](../../system.windows/) Communication Foundation. |
| static [UriSchemeNews](./urischemenews/) | Spécifie que le [Uri](./) est un groupe de discussion Internet et est accessible via le protocole NNTP. |
| static [UriSchemeNntp](./urischemenntp/) | Spécifie que le [Uri](./) est un groupe de discussion Internet et est accessible via le protocole NNTP. |

## Remarques



```cpp
#include "system/smart_ptr.h"
#include "system/uri.h"
#include <iostream>

int main()
{
  const auto uri = System::MakeObject<System::Uri>(u"https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/");

std::cout <<
  "AbsolutePath: " << uri->get_AbsolutePath() << std::endl <<
  "AbsoluteUri: " << uri->get_AbsoluteUri() << std::endl <<
  "Authority: " << uri->get_Authority() << std::endl <<
  "DnsSafeHost: " << uri->get_DnsSafeHost() << std::endl <<
  "Fragment: " << uri->get_Fragment() << std::endl <<
  "Host: " << uri->get_Host() << std::endl <<
  "IdnHost: " << uri->get_IdnHost() << std::endl <<
  "LocalPath: " << uri->get_LocalPath() << std::endl <<
  "OriginalString: " << uri->get_OriginalString() << std::endl <<
  "PathAndQuery: " << uri->get_PathAndQuery() << std::endl <<
  "Port: " << uri->get_Port() << std::endl <<
  "Query: " << uri->get_Query() << std::endl <<
  "Scheme: " << uri->get_Scheme() << std::endl;

  return 0;
}
/*
Cet exemple de code produit la sortie suivante:
AbsolutePath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
AbsoluteUri: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Authority: docs.codeporting.com
DnsSafeHost: docs.codeporting.com
Fragment:
Host: docs.codeporting.com
IdnHost: docs.codeporting.com
LocalPath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
OriginalString: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
PathAndQuery: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Port: 443
Query:
Scheme: https
*/
```

## Voir aussi

* Classe [Object](../object/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)