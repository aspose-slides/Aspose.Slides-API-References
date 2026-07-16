---
title: PresentationHeaderFooterManager
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente le gestionnaire qui détient le comportement de tous les espaces réservés de pied de page, de date-heure et de numéro de page de la présentation.
type: docs
weight: 4863
url: /fr/aspose.slides/presentationheaderfootermanager/
---
## PresentationHeaderFooterManager classe


Représente le gestionnaire qui détient le comportement de tous les espaces réservés de pied de page, de date-heure et de numéro de page de la présentation.

```cpp
class PresentationHeaderFooterManager : public Aspose::Slides::BaseHeaderFooterManager,
                                        public Aspose::Slides::IPresentationHeaderFooterManager
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence en style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur en style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pour usage interne uniquement. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en réalité, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| void [SetAllDateTimesText](./setalldatetimestext/)([System::String](../../system/string/)) override | Dé définit le texte de tous les espaces réservés de date-heure, y compris les diapositives maîtres, les diapositives de mise en page, les diapositives, le maître des notes, les diapositives de notes et le maître du prospectus. |
| void [SetAllDateTimesVisibility](./setalldatetimesvisibility/)(**bool**) override | Modifie la visibilité de tous les espaces réservés de date-heure, y compris les diapositives maîtres, les diapositives de mise en page, les diapositives, le maître des notes, les diapositives de notes et le maître du prospectus. |
| void [SetAllFootersText](./setallfooterstext/)([System::String](../../system/string/)) override | Dé définit le texte de tous les espaces réservés de pied de page, y compris les diapositives maîtres, les diapositives de mise en page, les diapositives, le maître des notes, les diapositives de notes et le maître du prospectus. |
| void [SetAllFootersVisibility](./setallfootersvisibility/)(**bool**) override | Modifie la visibilité de tous les espaces réservés de pied de page, y compris les diapositives maîtres, les diapositives de mise en page, les diapositives, le maître des notes, les diapositives de notes et le maître du prospectus. |
| void [SetAllHeadersText](./setallheaderstext/)([System::String](../../system/string/)) override | Dé définit le texte de tous les espaces réservés d'en-tête, y compris le maître des notes, les diapositives de notes et le maître du prospectus. |
| void [SetAllHeadersVisibility](./setallheadersvisibility/)(**bool**) override | Modifie la visibilité de tous les espaces réservés d'en-tête, y compris le maître des notes, les diapositives de notes et le maître du prospectus. |
| void [SetAllSlideNumbersVisibility](./setallslidenumbersvisibility/)(**bool**) override | Modifie la visibilité de tous les espaces réservés de numéro de page, y compris les diapositives maîtres, les diapositives de mise en page, les diapositives, le maître des notes, les diapositives de notes et le maître du prospectus. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de passer les pointeurs dans les conteneurs en mode faible. |
| void [SetVisibilityOnAllTitleSlides](./setvisibilityonalltitleslides/)(**bool**) override | Modifie la visibilité des espaces réservés de pied de page, de date-heure et de numéro de page pour toutes les diapositives titre et pour la première diapositive de mise en page. Diapositives titre \\u2013 diapositives basées sur la première diapositive de mise en page (indépendamment du type de cette première mise en page). |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne devrait pas être appelé directement; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne devrait pas être appelé directement; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet la conversion d'objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne devrait pas être appelé directement; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne devrait pas être appelé directement; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [BaseHeaderFooterManager](../baseheaderfootermanager/)
* Classe [IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)