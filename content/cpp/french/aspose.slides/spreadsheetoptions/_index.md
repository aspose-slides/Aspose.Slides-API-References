---
title: SpreadsheetOptions
second_title: Référence API Aspose.Slides pour C++
description: Représente les options pouvant être utilisées pour spécifier un comportement supplémentaire des feuilles de calcul.
type: docs
weight: 5266
url: /fr/aspose.slides/spreadsheetoptions/
---
## SpreadsheetOptions classe

Représente les options pouvant être utilisées pour spécifier un comportement supplémentaire des feuilles de calcul.

```cpp
class SpreadsheetOptions : public Aspose::Slides::ISpreadsheetOptions
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emule la comparaison de nombres a virgule flottante de style C# où deux NaN sont consideres egaux même si, selon la norme IEC 60559:1989, NaN n'est egal a aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emule la comparaison de nombres a virgule flottante de style C# où deux NaN sont consideres egaux même si, selon la norme IEC 60559:1989, NaN n'est egal a aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | A des fins internes uniquement. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\> [get_PreferredCulture](./get_preferredculture/)() override | Obtient les informations de culture preferees pour calculer certaines fonctions destinees a etre utilisees avec des langues qui utilisent le jeu de caracteres a double octet (DBCS). |
| **bool** [get_RecoverWorkbookFromChartCache](./get_recoverworkbookfromchartcache/)() override | Si la source de donnees pour le diagramme provient d'un classeur externe et qu'elle n'est pas disponible, elle sera recuperée depuis le cache du diagramme. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de donnees du compteur de references associee a l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalises. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type reel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifie si l'objet represente une instance du type décrit par targetType. Analogue de l'operateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implemente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalises. |
|  [Object](../../system/object/object/)() | Cree l'objet. Initialise toutes les structures de donnees internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en realite, il initialise simplement un nouvel objet et permet de copier les sub-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operateur d'affectation. Ne copie rien, en realite, il initialise simplement un nouvel objet et permet de copier les sub-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par reference l'objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaine et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaines. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de references partagees de la valeur specifiee. |
| void [set_PreferredCulture](./set_preferredculture/)([System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>) override | Definit les informations de culture preferees pour calculer certaines fonctions destinees a etre utilisees avec des langues qui utilisent le jeu de caracteres a double octet (DBCS). |
| void [set_RecoverWorkbookFromChartCache](./set_recoverworkbookfromchartcache/)(**bool**) override | Si la source de donnees pour le diagramme provient d'un classeur externe et qu'elle n'est pas disponible, elle sera recuperée depuis le cache du diagramme. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Definit le n-ieme argument de modele comme un pointeur faible (plutot que partage). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de references partagees. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incremente le compteur de references partagees. Ne doit pas etre appele directement; utilisez plutot des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decremente et renvoie le compteur de references partagees. Ne doit pas etre appele directement; utilisez plutot des pointeurs intelligents ou ThisProtector. |
|  [SpreadsheetOptions](./spreadsheetoptions/)() | Initialise une nouvelle instance de la classe [SpreadsheetOptions](./). |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la methode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalises en chaine. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implemente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implemente le deverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incremente le compteur de references faibles. Ne doit pas etre appele directement; utilisez plutot des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decremente le compteur de references faibles. Ne doit pas etre appele directement; utilisez plutot des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Detruit l'objet. Libere toutes les structures de donnees internes. |

## Voir aussi

* Classe [ISpreadsheetOptions](../ispreadsheetoptions/)
* Espace de noms [Aspose::Slides](../)
* Bibliotheque [Aspose.Slides](../../)