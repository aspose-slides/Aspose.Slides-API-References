---
title: StringBuilder
second_title: Référence de l'API Aspose.Slides pour C++
description: "Tampon pour accumuler une chaîne partie par partie. Ce type peut être alloué soit sur la pile en tant que type valeur, soit sur le tas en utilisant la fonction System::MakeObject(). Une fois l'objet alloué, ne mélangez jamais ces deux cas d'utilisation : avoir des pointeurs SmartPtr vers des objets alloués sur la pile est strictement interdit."
type: docs
weight: 326
url: /fr/system.text/stringbuilder/
---
## StringBuilder classe

[Buffer](../../system/buffer/) pour accumuler des parties de chaîne une par une. Ce type peut être alloué soit sur la pile comme type valeur, soit sur le tas en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Une fois l'objet alloué, ne mélangez jamais ces deux cas d'utilisation : avoir des pointeurs [SmartPtr](../../system/smartptr/) vers des objets alloués sur la pile est strictement interdit.

```cpp
class StringBuilder : public System::Object
```

## Méthodes

| Méthode | Description |
| --- | --- |
| [StringBuilder](./) * [Append](./append/)(char_t) | Ajoute un caractère au constructeur. |
| [StringBuilder](./) * [Append](./append/)(char_t, int) | Ajoute des caractères au constructeur. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Ajoute un tableau de caractères au constructeur. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Ajoute une tranche de tableau de caractères au constructeur. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&) | Ajoute une chaîne au constructeur. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&, int, int) | Ajoute une tranche de chaîne au constructeur. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<T\>\&) | Ajoute la représentation sous forme de chaîne de l'objet au constructeur. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<[StringBuilder](./)\>\&) | Ajoute le contenu du constructeur au constructeur. |
| [StringBuilder](./) * [Append](./append/)(**float**) | Ajoute une valeur à virgule flottante au constructeur. |
| [StringBuilder](./) * [Append](./append/)(**double**) | Ajoute une valeur à virgule flottante au constructeur. |
| [StringBuilder](./) * [Append](./append/)(int) | Ajoute une valeur entière au constructeur. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Append](./append/)(T) | Ajoute une valeur arithmétique au constructeur. |
| std::enable_if\<std::is_enum\<E\>::value, [StringBuilder](./) *\>::type [Append](./append/)(E) | Ajoute la représentation sous forme de chaîne d'une valeur d'énumération au constructeur. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [String](../../system/string/)\&, const TArgs\&...) | Annexe une chaîne formatée au constructeur. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\>\&, const [String](../../system/string/)\&, const TArgs\&...) | Annexe une chaîne formatée au constructeur. |
| [StringBuilder](./) * [AppendLine](./appendline/)() | Annexe le caractère de nouvelle ligne au constructeur. |
| [StringBuilder](./) * [AppendLine](./appendline/)(const [String](../../system/string/)\&) | Annexe une chaîne suivie du caractère de nouvelle ligne au constructeur. |
| [StringBuilder](./) * [Clear](./clear/)() | Supprime tous les caractères du constructeur. |
| void [CopyTo](./copyto/)(int, [System::ArrayPtr](../../system/arrayptr/)\<char_t\> const\&, int, int) | Copie les données du constructeur dans les positions existantes du tableau. |
| **int32_t** [EnsureCapacity](./ensurecapacity/)(**int32_t**) | Garantit que la capacité de cette instance de [System.Text.StringBuilder](./) est au moins la valeur spécifiée. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence à la manière de C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur à la manière de C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| int [get_Capacity](./get_capacity/)() const | Obtient la capacité actuelle du constructeur de chaîne. |
| int [get_Length](./get_length/)() const | Obtient la longueur de la chaîne actuellement dans le constructeur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| char_t [idx_get](./idx_get/)(int) const | Obtient le caractère à la position spécifiée. |
| void [idx_set](./idx_set/)(int, char_t) | Définit le caractère à la position spécifiée. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [String](../../system/string/)\&) | Insère une chaîne à la position fixe du constructeur. |
| [StringBuilder](./) * [Insert](./insert/)(**int32_t**, const [String](../../system/string/)\&, **int32_t**) | Insère une chaîne répétée à la position fixe du constructeur. |
| [StringBuilder](./) * [Insert](./insert/)(int, char_t) | Insère un caractère à la position fixe du constructeur. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Insère des caractères à la position fixe du constructeur. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Insert](./insert/)(int, T) | Insère une valeur à la position fixe du constructeur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction de copies des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction de copies des sous-classes. |
| char_t [operator[]](./operator[]/)(int) const | Obtient le caractère à la position spécifiée. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| [StringBuilder](./) * [Remove](./remove/)(int, int) | Supprime un fragment du constructeur. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Remplace une sous-chaine via le constructeur. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | Remplace une sous-chaine via la plage du constructeur. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t) | Remplace un caractère via le constructeur. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t, int, int) | Remplace un caractère via la plage du constructeur. |
| void [set_Capacity](./set_capacity/)(int) | Définit la capacité actuelle du constructeur de chaîne. |
| void [set_Length](./set_length/)(int) | Tronque ou étend le constructeur de chaîne à la longueur spécifiée. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de passer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
|  [StringBuilder](./stringbuilder/)() | Constructeur. |
|  [StringBuilder](./stringbuilder/)(int) | Constructeur. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&) | Constructeur. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int) | Constructeur. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int, int, int) | Constructeur. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Obtient la chaîne actuellement contenue dans le constructeur. |
| [String](../../system/string/) [ToString](./tostring/)(int, int) const | Obtient la sous-chaine actuellement contenue dans le constructeur. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente le construct C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |
|  [~StringBuilder](./~stringbuilder/)() | Destructeur. |

## Voir aussi

* Classe [Object](../../system/object/)
* Espace de noms [System::Text](../)
* Bibliothèque [Aspose.Slides](../../)