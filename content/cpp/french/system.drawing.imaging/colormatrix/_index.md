---
title: ColorMatrix
second_title: Référence de l'API Aspose.Slides pour C++
description: "Représente une matrice 5x5 contenant les coordonnées de l'espace couleur RGBAW. Les objets de cette classe doivent être alloués uniquement à l'aide de la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument."
type: docs
weight: 27
url: /fr/system.drawing.imaging/colormatrix/
---
## ColorMatrix classe

Représente une matrice 5×5 qui contient les coordonnées pour l’espace couleur RGBAW. Les objets de cette classe doivent être alloués uniquement à l’aide de la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d’instance de ce type sur la pile ou en utilisant l’opérateur new, car cela entraînera des erreurs d’exécution et/ou des défauts d’assertion. Enveloppez toujours cette classe dans le pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu’argument.

```cpp
class ColorMatrix : public System::Object
```

## Méthodes

| Méthode | Description |
| --- | --- |
|  [ColorMatrix](./colormatrix/)() | Construit une nouvelle instance de la classe [ColorMatrix](./) et l'initialise avec les valeurs de la matrice identité. |
|  [ColorMatrix](./colormatrix/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::ArrayPtr](../../system/arrayptr/)\<**float**\>\>\&) | Construit une nouvelle instance de la classe [ColorMatrix](./) et l'initialise avec les valeurs spécifiées. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| **float** [get_Matrix00](./get_matrix00/)() const | Renvoie une valeur à la ligne 0 et à la colonne 0. |
| **float** [get_Matrix01](./get_matrix01/)() const | Renvoie une valeur à la ligne 0 et à la colonne 1. |
| **float** [get_Matrix02](./get_matrix02/)() const | Renvoie une valeur à la ligne 0 et à la colonne 2. |
| **float** [get_Matrix03](./get_matrix03/)() const | Renvoie une valeur à la ligne 0 et à la colonne 3. |
| **float** [get_Matrix04](./get_matrix04/)() const | Renvoie une valeur à la ligne 0 et à la colonne 4. |
| **float** [get_Matrix10](./get_matrix10/)() const | Renvoie une valeur à la ligne 1 et à la colonne 0. |
| **float** [get_Matrix11](./get_matrix11/)() const | Renvoie une valeur à la ligne 1 et à la colonne 1. |
| **float** [get_Matrix12](./get_matrix12/)() const | Renvoie une valeur à la ligne 1 et à la colonne 2. |
| **float** [get_Matrix13](./get_matrix13/)() const | Renvoie une valeur à la ligne 1 et à la colonne 3. |
| **float** [get_Matrix14](./get_matrix14/)() const | Renvoie une valeur à la ligne 1 et à la colonne 4. |
| **float** [get_Matrix20](./get_matrix20/)() const | Renvoie une valeur à la ligne 2 et à la colonne 0. |
| **float** [get_Matrix21](./get_matrix21/)() const | Renvoie une valeur à la ligne 2 et à la colonne 1. |
| **float** [get_Matrix22](./get_matrix22/)() const | Renvoie une valeur à la ligne 2 et à la colonne 2. |
| **float** [get_Matrix23](./get_matrix23/)() const | Renvoie une valeur à la ligne 2 et à la colonne 3. |
| **float** [get_Matrix24](./get_matrix24/)() const | Renvoie une valeur à la ligne 2 et à la colonne 4. |
| **float** [get_Matrix30](./get_matrix30/)() const | Renvoie une valeur à la ligne 3 et à la colonne 0. |
| **float** [get_Matrix31](./get_matrix31/)() const | Renvoie une valeur à la ligne 3 et à la colonne 1. |
| **float** [get_Matrix32](./get_matrix32/)() const | Renvoie une valeur à la ligne 3 et à la colonne 2. |
| **float** [get_Matrix33](./get_matrix33/)() const | Renvoie une valeur à la ligne 3 et à la colonne 3. |
| **float** [get_Matrix34](./get_matrix34/)() const | Renvoie une valeur à la ligne 3 et à la colonne 4. |
| **float** [get_Matrix40](./get_matrix40/)() const | Renvoie une valeur à la ligne 4 et à la colonne 0. |
| **float** [get_Matrix41](./get_matrix41/)() const | Renvoie une valeur à la ligne 4 et à la colonne 1. |
| **float** [get_Matrix42](./get_matrix42/)() const | Renvoie une valeur à la ligne 4 et à la colonne 2. |
| **float** [get_Matrix43](./get_matrix43/)() const | Renvoie une valeur à la ligne 4 et à la colonne 3. |
| **float** [get_Matrix44](./get_matrix44/)() const | Renvoie une valeur à la ligne 4 et à la colonne 4. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| **float** [idx_get](./idx_get/)(int, int) | Renvoie une valeur à la ligne et à la colonne spécifiées. |
| **float** [idx_set](./idx_set/)(int, int, **float**) | Définit la valeur spécifiée à l'emplacement indiqué dans la matrice. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien en réalité, il initialise simplement un nouvel objet et permet la copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d’affectation. Ne copie rien en réalité, il initialise simplement un nouvel objet et permet la copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence l'objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| void [set_Matrix00](./set_matrix00/)(**float**) | Définit une valeur à la ligne 0 et à la colonne 0. |
| void [set_Matrix01](./set_matrix01/)(**float**) | Définit une valeur à la ligne 0 et à la colonne 1. |
| void [set_Matrix02](./set_matrix02/)(**float**) | Définit une valeur à la ligne 0 et à la colonne 2. |
| void [set_Matrix03](./set_matrix03/)(**float**) | Définit une valeur à la ligne 0 et à la colonne 3. |
| void [set_Matrix04](./set_matrix04/)(**float**) | Définit une valeur à la ligne 0 et à la colonne 4. |
| void [set_Matrix10](./set_matrix10/)(**float**) | Définit une valeur à la ligne 1 et à la colonne 0. |
| void [set_Matrix11](./set_matrix11/)(**float**) | Définit une valeur à la ligne 1 et à la colonne 1. |
| void [set_Matrix12](./set_matrix12/)(**float**) | Définit une valeur à la ligne 1 et à la colonne 2. |
| void [set_Matrix13](./set_matrix13/)(**float**) | Définit une valeur à la ligne 1 et à la colonne 3. |
| void [set_Matrix14](./set_matrix14/)(**float**) | Définit une valeur à la ligne 1 et à la colonne 4. |
| void [set_Matrix20](./set_matrix20/)(**float**) | Définit une valeur à la ligne 2 et à la colonne 0. |
| void [set_Matrix21](./set_matrix21/)(**float**) | Définit une valeur à la ligne 2 et à la colonne 1. |
| void [set_Matrix22](./set_matrix22/)(**float**) | Définit une valeur à la ligne 2 et à la colonne 2. |
| void [set_Matrix23](./set_matrix23/)(**float**) | Définit une valeur à la ligne 2 et à la colonne 3. |
| void [set_Matrix24](./set_matrix24/)(**float**) | Définit une valeur à la ligne 2 et à la colonne 4. |
| void [set_Matrix30](./set_matrix30/)(**float**) | Définit une valeur à la ligne 3 et à la colonne 0. |
| void [set_Matrix31](./set_matrix31/)(**float**) | Définit une valeur à la ligne 3 et à la colonne 1. |
| void [set_Matrix32](./set_matrix32/)(**float**) | Définit une valeur à la ligne 3 et à la colonne 2. |
| void [set_Matrix33](./set_matrix33/)(**float**) | Définit une valeur à la ligne 3 et à la colonne 3. |
| void [set_Matrix34](./set_matrix34/)(**float**) | Définit une valeur à la ligne 3 et à la colonne 4. |
| void [set_Matrix40](./set_matrix40/)(**float**) | Définit une valeur à la ligne 4 et à la colonne 0. |
| void [set_Matrix41](./set_matrix41/)(**float**) | Définit une valeur à la ligne 4 et à la colonne 1. |
| void [set_Matrix42](./set_matrix42/)(**float**) | Définit une valeur à la ligne 4 et à la colonne 2. |
| void [set_Matrix43](./set_matrix43/)(**float**) | Définit une valeur à la ligne 4 et à la colonne 3. |
| void [set_Matrix44](./set_matrix44/)(**float**) | Définit une valeur à la ligne 4 et à la colonne 4. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir les objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente le construct C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |
## Voir aussi

* Classe [Object](../../system/object/)
* Espace de noms [System::Drawing::Imaging](../)
* Bibliothèque [Aspose.Slides](../../)