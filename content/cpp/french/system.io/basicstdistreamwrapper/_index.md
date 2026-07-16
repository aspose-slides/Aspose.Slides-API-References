---
title: BasicSTDIStreamWrapper
second_title: Référence de l'API Aspose.Slides pour C++
description: "Représente un wrapper de type System.IO.Stream pour std::basic_istream et ses objets dérivés. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le passer aux fonctions en argument."
type: docs
weight: 14
url: /fr/system.io/basicstdistreamwrapper/
---
## BasicSTDIStreamWrapper classe

Représente un wrapper de type [System.IO.Stream](../stream/) pour std::basic_istream et ses objets dérivés. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions comme argument.

```cpp
template<typename T,typename>class BasicSTDIStreamWrapper : public virtual System::IO::STDIOStreamWrapperBase<T>
```

## Méthodes

| Méthode | Description |
| --- | --- |
|  [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(std::basic_istream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | Construit une nouvelle instance de [BasicSTDIStreamWrapper](./). |
|  [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(const [BasicSTDIStreamWrapper](./)\&) | Constructeur de copie. Supprimé. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initie une opération de lecture asynchrone. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Initie une opération d'écriture asynchrone. |
| virtual void [Close](../stream/close/)() | Ferme le flux. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Copie des octets vers le flux spécifié. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Copie des octets vers le flux spécifié en utilisant la taille de tampon spécifiée. |
| void [Dispose](../stream/dispose/)() override | Libère toutes les ressources utilisées par l'objet actuel et ferme le flux. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Attend que l'opération de lecture asynchrone spécifiée se termine. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Termine une opération d'écriture asynchrone. Attend que l'opération d'écriture asynchrone spécifiée se termine. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés comme égaux bien que selon IEC 60559:1989 NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés comme égaux bien que selon IEC 60559:1989 NaN ne soit égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| void [Flush](./flush/)() override | Efface les tampons de ce flux et écrit toutes les données tamponnées vers le stockage sous-jacent. Non pris en charge ! |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Vide de façon asynchrone tous les tampons de ce flux, provoque l'écriture de toutes les données tamponnées vers le périphérique sous-jacent et surveille les demandes d'annulation. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Vide de façon asynchrone tous les tampons de ce flux, provoque l'écriture de toutes les données tamponnées vers le périphérique sous-jacent et surveille les demandes d'annulation. |
| **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | Détermine si le flux prend en charge le positionnement. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Obtient une valeur qui détermine si le flux actuel peut expirer. |
| **bool** [get_CanWrite](../stdiostreamwrapperbase/get_canwrite/)() const override | Détermine si le flux prend en charge l'écriture. |
| **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | Renvoie la longueur du flux. |
| **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | Renvoie la position actuelle du flux. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Obtient une valeur, en millisecondes, qui détermine la durée pendant laquelle le flux tentera de lire avant d'expirer. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Obtient une valeur, en millisecondes, qui détermine la durée pendant laquelle le flux tentera d'écrire avant d'expirer. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| [BasicSTDIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDIStreamWrapper](./)\&) | Opérateur d'affectation de copie. Supprimé. |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Opérateur d'affectation de copie. Supprimé. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Si le mode d'enveloppe est binaire, lit le nombre d'octets spécifié depuis le flux, sinon lit le nombre de caractères spécifié et les convertit en type **uint8_t**. Écrit le résultat de la lecture dans le tableau d'octets spécifié. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Lit le nombre d'octets spécifié depuis le flux et les écrit dans le tableau d'octets spécifié. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Lit le nombre d'octets spécifié depuis le flux et les écrit dans le tableau d'octets spécifié. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Lit le nombre d'octets spécifié depuis le flux et les écrit dans la plage d'octets spécifiée. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Lit de façon asynchrone une séquence d'octets depuis le flux actuel, avance la position dans le flux du nombre d'octets lus et surveille les demandes d'annulation. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Lit de façon asynchrone une séquence d'octets depuis le flux actuel, avance la position dans le flux du nombre d'octets lus et surveille les demandes d'annulation. |
| int [ReadByte](./readbyte/)() override | Si le mode d'enveloppe est binaire, lit un seul octet depuis le stockage du dernier caractère décodé, sinon lit un seul caractère depuis le flux et le convertit en type **uint8_t**. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | Information RTTI. |
| **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Définit la position du flux représenté par l'objet actuel. |
| void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | Définit la position du flux. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Définit une valeur qui détermine si le flux actuel peut expirer. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Définit une valeur, en millisecondes, qui détermine la durée pendant laquelle le flux tentera de lire avant d'expirer. |
| void [SetLength](./setlength/)(**int64_t**) override | Définit la longueur du flux représenté par l'objet actuel. Non pris en charge ! |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le nᵉᵗᵉ argument de modèle comme pointeur faible (plutôt que partagé). Permet de passer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Constructeur de copie. Supprimé. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente le construct C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Si le mode d'enveloppe est binaire, écrit dans le flux la sous-plage d'octets spécifiée du tableau d'octets indiqué, sinon convertit la sous-plage d'octets en type char_type puis écrit le résultat dans le flux. Non pris en charge ! |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Écrit la sous-plage d'octets spécifiée du tableau d'octets indiqué dans le flux. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Écrit la sous-plage d'octets spécifiée du tableau d'octets indiqué dans le flux. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Écrit la sous-plage d'octets spécifiée du span d'octets indiqué dans le flux. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Écrit de façon asynchrone une séquence d'octets dans le flux actuel, avance la position actuelle dans ce flux du nombre d'octets écrits et surveille les demandes d'annulation. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Écrit de façon asynchrone une séquence d'octets dans le flux actuel, avance la position actuelle dans ce flux du nombre d'octets écrits et surveille les demandes d'annulation. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | Si le mode d'enveloppe est binaire, écrit dans le flux la valeur entière non signée de 8 bits spécifiée, sinon la convertit en type char_type puis écrit le résultat dans le flux. Non pris en charge ! |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Champs

| Champ | Description |
| --- | --- |
| static [Null](../stream/null/) | Un flux sans stockage sous-jacent. |

## Alias de type

| Alias | Description |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |

## Voir aussi

* Classe [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)
* Espace de noms [System::IO](../)
* Bibliothèque [Aspose.Slides](../../)