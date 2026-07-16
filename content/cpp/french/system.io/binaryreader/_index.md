---
title: BinaryReader
second_title: Référence de l'API Aspose.Slides pour C++
description: "Représente un lecteur qui lit les types de données primitifs sous forme de données binaires dans un encodage particulier. Les objets de cette classe doivent être alloués uniquement à l'aide de la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument."
type: docs
weight: 92
url: /fr/system.io/binaryreader/
---
## BinaryReader classe

Représente un lecteur qui lit les types de données primitifs en tant que données binaires dans un encodage particulier. Les objets de cette classe ne doivent être alloués qu'à l'aide de la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument.

```cpp
class BinaryReader : public System::IDisposable
```

## Méthodes

| Méthode | Description |
| --- | --- |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Construit une instance de la classe [BinaryReader](./) qui lit les données du flux spécifié en utilisant l’encodage UTF-8. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Construit une instance de la classe [BinaryReader](./) qui lit les données du flux spécifié en utilisant l’encodage spécifié. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&, **bool**) | Construit une instance de la classe [BinaryReader](./) qui lit les données du flux spécifié en utilisant l’encodage spécifié. |
| virtual void [Close](./close/)() | Ferme l’objet [BinaryReader](./) actuel ainsi que le flux d’entrée sous-jacent. |
| void [Dispose](./dispose/)() override | Libère toutes les ressources utilisées par l’objet actuel et ferme le flux sous-jacent. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À usage interne uniquement. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() | Retourne le flux d’entrée. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l’objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d’objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l’objet. Analogue de l’appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l’objet représente une instance du type décrit par targetType. Analogue de l’opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l’objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, il se contente d’initialiser le nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d’affectation. Ne copie rien, en réalité, il se contente d’initialiser le nouvel objet et permet la construction par copie des sous-classes. |
| virtual int [PeekChar](./peekchar/)() | Lit un seul caractère du flux d’entrée sans modifier le curseur de lecture du flux. |
| virtual int [Read](./read/)() | Lit un seul caractère du flux d’entrée. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Lit le nombre spécifié d’octets du flux d’entrée et les écrit dans le tableau d’octets spécifié. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Lit le nombre spécifié de caractères du flux d’entrée, les convertit en encodage UTF-16 et écrit les caractères UTF-16 résultants dans le tableau de caractères spécifié à partir de la position indiquée. |
| virtual **bool** [ReadBoolean](./readboolean/)() | Lit un seul octet du flux d’entrée et renvoie sa représentation booléenne. |
| virtual **uint8_t** [ReadByte](./readbyte/)() | Lit un seul octet du flux d’entrée. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadBytes](./readbytes/)(int) | Lit le nombre spécifié d’octets du flux d’entrée. |
| virtual char_t [ReadChar](./readchar/)() | Lit un seul caractère du flux d’entrée. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [ReadChars](./readchars/)(int) | Lit le nombre spécifié de caractères du flux d’entrée et les renvoie en encodage UTF-16. |
| virtual [Decimal](../../system/decimal/) [ReadDecimal](./readdecimal/)() | NON IMPLÉMENTÉ. |
| virtual **double** [ReadDouble](./readdouble/)() | Lit 8 octets du flux d’entrée et les renvoie sous forme de valeur à virgule flottante double précision. |
| virtual **int16_t** [ReadInt16](./readint16/)() | Lit 2 octets du flux d’entrée et les renvoie sous forme de valeur entière 16 bits. |
| virtual int [ReadInt32](./readint32/)() | Lit 4 octets du flux d’entrée et les renvoie sous forme de valeur entière 32 bits. |
| virtual **int64_t** [ReadInt64](./readint64/)() | Lit 8 octets du flux d’entrée et les renvoie sous forme de valeur entière 64 bits. |
| virtual **int8_t** [ReadSByte](./readsbyte/)() | Lit un seul octet du flux d’entrée et le renvoie sous forme de valeur entière signée 8 bits. |
| virtual **float** [ReadSingle](./readsingle/)() | Lit 4 octets du flux d’entrée et les renvoie sous forme de valeur à virgule flottante simple précision. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | Lit une chaîne du flux actuel. La chaîne est précédée de la longueur, encodée sous forme d’entier sur sept bits à la fois. |
| virtual **uint16_t** [ReadUInt16](./readuint16/)() | Lit 2 octets du flux d’entrée et les renvoie sous forme de valeur entière non signée 16 bits. |
| virtual **uint32_t** [ReadUInt32](./readuint32/)() | Lit 4 octets du flux d’entrée et les renvoie sous forme de valeur entière non signée 32 bits. |
| virtual **uint64_t** [ReadUInt64](./readuint64/)() | Lit 8 octets du flux d’entrée et les renvoie sous forme de valeur entière non signée 64 bits. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence l’objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d’une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs vers le mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet la conversion d’objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual  [~BinaryReader](./~binaryreader/)() | Destructeur. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l’objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [IDisposable](../../system/idisposable/)
* Espace de noms [System::IO](../)
* Bibliothèque [Aspose.Slides](../../)