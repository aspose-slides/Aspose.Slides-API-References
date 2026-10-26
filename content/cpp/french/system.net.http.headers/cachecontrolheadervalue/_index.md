---
title: CacheControlHeaderValue
second_title: Référence API Aspose.Slides pour C++
description: "Représente une valeur de l'en-tête 'Cache-Control'. Les objets de cette classe doivent être alloués uniquement à l'aide de la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des défauts d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument."
type: docs
weight: 14
url: /fr/system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue classe

Représente une valeur de l'en-tête 'Cache-Control'. Les objets de cette classe ne doivent être alloués qu'à l'aide de la fonction [System::MakeObject()](../../system/makeobject/). Ne jamais créer d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des défauts d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument.

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## Méthodes

| Méthode | Description |
| --- | --- |
|  [CacheControlHeaderValue](./cachecontrolheadervalue/)() | Construit une nouvelle instance. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres flottants de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres flottants de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À usage interne uniquement. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Extensions](./get_extensions/)() | Renvoie la collection des jetons d'extension de cache. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxAge](./get_maxage/)() | Obtient la valeur d'âge maximal en secondes qui détermine la durée pendant laquelle le client acceptera une réponse. |
| **bool** [get_MaxStale](./get_maxstale/)() | Obtient la valeur qui détermine si le client acceptera les réponses expirées. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxStaleLimit](./get_maxstalelimit/)() | Obtient la valeur en secondes qui détermine la durée pendant laquelle le client acceptera les réponses expirées. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MinFresh](./get_minfresh/)() | Obtient la valeur qui détermine la durée de fraîcheur. |
| **bool** [get_MustRevalidate](./get_mustrevalidate/)() | Obtient la valeur qui détermine si le serveur exige une revalidation d'une entrée de cache lorsqu'elle devient obsolète. |
| **bool** [get_NoCache](./get_nocache/)() | Obtient la valeur qui détermine si le client acceptera une réponse en cache. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_NoCacheHeaders](./get_nocacheheaders/)() | Obtient la collection des noms de champ dans la directive 'no-cache' de l'en-tête 'Cache-Control'. |
| **bool** [get_NoStore](./get_nostore/)() | Obtient la valeur qui détermine si un cache ne doit stocker aucune partie d'une requête ou d'une réponse HTTP. |
| **bool** [get_NoTransform](./get_notransform/)() | Obtient la valeur qui détermine si un cache ou un proxy ne doit modifier aucune partie du corps de l'entité. |
| **bool** [get_OnlyIfCached](./get_onlyifcached/)() | Obtient la valeur qui détermine si le client doit n'utiliser que des entrées en cache. |
| **bool** [get_Private](./get_private/)() | Obtient la valeur qui détermine si le message de réponse HTTP ou sa partie est destiné à un seul utilisateur et ne doit pas être mis en cache par un cache partagé. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_PrivateHeaders](./get_privateheaders/)() | Obtient la collection des noms de champ dans la directive 'private' de l'en-tête 'Cache-Control'. |
| **bool** [get_ProxyRevalidate](./get_proxyrevalidate/)() | Obtient la valeur qui détermine si le serveur exige une revalidation d'une entrée de cache lorsqu'elle devient obsolète pour les caches d'agents utilisateurs partagés. |
| **bool** [get_Public](./get_public/)() | Obtient la valeur qui détermine si une réponse HTTP peut être mise en cache par n'importe quel cache. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_SharedMaxAge](./get_sharedmaxage/)() | Obtient la valeur d'âge maximal partagé en secondes qui remplace la directive 'max-age' dans l'en-tête 'Cache-Control' ou l'en-tête 'Expires' pour un cache partagé. |
| static **int32_t** [GetCacheControlLength](./getcachecontrollength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Convertit une chaîne passée depuis l'index spécifié en une instance de la classe [CacheControlHeaderValue](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie en fait rien, il initialise simplement un nouvel objet et permet la construction de copies des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie en fait rien, il initialise simplement un nouvel objet et permet la construction de copies des sous-classes. |
| static [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Convertit une chaîne passée en une instance de la classe [CacheControlHeaderValue](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| void [set_MaxAge](./set_maxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Définit la valeur d'âge maximal en secondes qui détermine la durée pendant laquelle le client acceptera une réponse. |
| void [set_MaxStale](./set_maxstale/)(**bool**) | Définit la valeur qui détermine si le client acceptera les réponses expirées. |
| void [set_MaxStaleLimit](./set_maxstalelimit/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Définit la valeur en secondes qui détermine la durée pendant laquelle le client acceptera les réponses expirées. |
| void [set_MinFresh](./set_minfresh/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Définit la valeur qui détermine la durée de fraîcheur. |
| void [set_MustRevalidate](./set_mustrevalidate/)(**bool**) | Définit la valeur qui détermine si le serveur exige une revalidation d'une entrée de cache lorsqu'elle devient obsolète. |
| void [set_NoCache](./set_nocache/)(**bool**) | Définit la valeur qui détermine si le client acceptera une réponse en cache. |
| void [set_NoStore](./set_nostore/)(**bool**) | Définit la valeur qui détermine si un cache ne doit stocker aucune partie d'une requête ou d'une réponse HTTP. |
| void [set_NoTransform](./set_notransform/)(**bool**) | Définit la valeur qui détermine si un cache ou un proxy ne doit modifier aucune partie du corps de l'entité. |
| void [set_OnlyIfCached](./set_onlyifcached/)(**bool**) | Définit la valeur qui détermine si le client doit n'utiliser que des entrées en cache. |
| void [set_Private](./set_private/)(**bool**) | Définit la valeur qui détermine si le message de réponse HTTP ou sa partie est destiné à un seul utilisateur et ne doit pas être mis en cache par un cache partagé. |
| void [set_ProxyRevalidate](./set_proxyrevalidate/)(**bool**) | Définit la valeur qui détermine si le serveur exige une revalidation d'une entrée de cache lorsqu'elle devient obsolète pour les caches d'agents utilisateurs partagés. |
| void [set_Public](./set_public/)(**bool**) | Définit la valeur qui détermine si une réponse HTTP peut être mise en cache par n'importe quel cache. |
| void [set_SharedMaxAge](./set_sharedmaxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Définit la valeur d'âge maximal partagé en secondes qui remplace la directive 'max-age' dans l'en-tête 'Cache-Control' ou l'en-tête 'Expires' pour un cache partagé. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de passer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne devrait pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne devrait pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet la conversion d'objets personnalisés en chaîne. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Tente de convertir une chaîne passée en une instance de la classe [CacheControlHeaderValue](./). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne devrait pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne devrait pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [ICloneable](../../system/icloneable/)
* Espace de noms [System::Net::Http::Headers](../)
* Bibliothèque [Aspose.Slides](../../)