---
title: LayoutPlaceholderManager
second_title: Référence API Aspose.Slides pour C++
description: Représente le gestionnaire qui permet d'ajouter des espaces réservés à la diapositive de mise en page.
type: docs
weight: 4278
url: /fr/aspose.slides/layoutplaceholdermanager/
---
## LayoutPlaceholderManager classe

Represents manager that allows you to add placeholders to the layout slide.

```cpp
class LayoutPlaceholderManager : public Aspose::Slides::ILayoutPlaceholderManager
```

## Méthodes

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddChartPlaceholder](./addchartplaceholder/)(**float**, **float**, **float**, **float**) override | Ajoute une nouvelle forme d'espace réservé à la diapositive de mise en page pour contenir un graphique. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddContentPlaceholder](./addcontentplaceholder/)(**float**, **float**, **float**, **float**) override | Ajoute une nouvelle forme d'espace réservé à la diapositive de mise en page pour contenir du contenu, tel qu'une image, un tableau, un média ou du texte. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddMediaPlaceholder](./addmediaplaceholder/)(**float**, **float**, **float**, **float**) override | Ajoute une nouvelle forme d'espace réservé à la diapositive de mise en page pour contenir un objet média. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddOnlineImagePlaceholder](./addonlineimageplaceholder/)(**float**, **float**, **float**, **float**) override | Ajoute une nouvelle forme d'espace réservé à la diapositive de mise en page pour contenir une image en ligne. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddPicturePlaceholder](./addpictureplaceholder/)(**float**, **float**, **float**, **float**) override | Ajoute une nouvelle forme d'espace réservé à la diapositive de mise en page pour contenir une image. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddSmartArtPlaceholder](./addsmartartplaceholder/)(**float**, **float**, **float**, **float**) override | Ajoute une nouvelle forme d'espace réservé à la diapositive de mise en page pour contenir un diagramme [SmartArt](../../aspose.slides.smartart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddTablePlaceholder](./addtableplaceholder/)(**float**, **float**, **float**, **float**) override | Ajoute une nouvelle forme d'espace réservé à la diapositive de mise en page pour contenir un tableau. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddTextPlaceholder](./addtextplaceholder/)(**float**, **float**, **float**, **float**) override | Ajoute une nouvelle forme d'espace réservé à la diapositive de mise en page pour contenir du texte. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddVerticalContentPlaceholder](./addverticalcontentplaceholder/)(**float**, **float**, **float**, **float**) override | Ajoute une nouvelle forme d'espace réservé à la diapositive de mise en page pour contenir du contenu, tel qu'une image, un tableau, un média ou du texte, dans une direction verticale. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddVerticalTextPlaceholder](./addverticaltextplaceholder/)(**float**, **float**, **float**, **float**) override | Ajoute une nouvelle forme d'espace réservé à la diapositive de mise en page pour contenir du texte dans une direction verticale. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, le NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, le NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l’appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Met en œuvre le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, il initialise simplement un nouvel objet et permet la copie de construction des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en réalité, il initialise simplement un nouvel objet et permet la copie de construction des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence l'objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le nième argument de modèle comme pointeur faible (plutôt que partagé). Permet de passer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet la conversion d'objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Met en œuvre la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Met en œuvre le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [ILayoutPlaceholderManager](../ilayoutplaceholdermanager/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)