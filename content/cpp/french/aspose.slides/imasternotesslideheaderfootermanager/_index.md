---
title: IMasterNotesSlideHeaderFooterManager
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente le gestionnaire qui conserve le comportement des espaces réservés du pied de page, de la date-heure et du numéro de page de la diapositive de notes maîtresse, ainsi que de tous les espaces réservés enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus sur les diapositives de notes dépendantes. Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maîtresse.
type: docs
weight: 2900
url: /fr/aspose.slides/imasternotesslideheaderfootermanager/
---
## IMasterNotesSlideHeaderFooterManager classe

Représente le gestionnaire qui contient le comportement des espaces réservés du pied de page, de la date-heure et du numéro de page de la diapositive de notes maîtresse, ainsi que de tous les espaces réservés enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus sur les diapositives de notes dépendantes. Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maîtresse.

```cpp
class IMasterNotesSlideHeaderFooterManager : public virtual Aspose::Slides::IBaseHandoutNotesSlideHeaderFooterManag
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante à la manière de C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante à la manière de C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| virtual **bool** [get_IsDateTimeVisible](../ibaseslideheaderfootermanager/get_isdatetimevisible/)() | Obtient la valeur indiquant qu’un espace réservé date-heure est présent. Lire **bool**. |
| virtual **bool** [get_IsFooterVisible](../ibaseslideheaderfootermanager/get_isfootervisible/)() | Obtient la valeur indiquant qu’un espace réservé pied de page est présent. Lire **bool**. |
| virtual **bool** [get_IsHeaderVisible](../ibasehandoutnotesslideheaderfootermanag/get_isheadervisible/)() | Obtient la valeur indiquant qu’un espace réservé en-tête est présent. Lire **bool**. |
| virtual **bool** [get_IsSlideNumberVisible](../ibaseslideheaderfootermanager/get_isslidenumbervisible/)() | Obtient la valeur indiquant qu’un espace réservé numéro de page est présent. Lire **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l’objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage des objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l’objet. Analogue de l’appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l’objet représente une instance du type décrit par targetType. Analogue de l’opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage des types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l’objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie réellement rien, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d’affectation. Ne copie réellement rien, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d’une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre indiqué. |
| virtual void [SetDateTimeAndChildDateTimesText](./setdatetimeandchilddatetimestext/)([System::String](../../system/string/)) | Définit le texte de l’espace réservé date-heure de la diapositive de notes maîtresse et de tous les espaces réservés date-heure enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus sur les diapositives de notes dépendantes. Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maîtresse. |
| virtual void [SetDateTimeAndChildDateTimesVisibility](./setdatetimeandchilddatetimesvisibility/)(**bool**) | Modifie la visibilité de l’espace réservé date-heure de la diapositive de notes maîtresse et de tous les espaces réservés date-heure enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus sur les diapositives de notes dépendantes. Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maîtresse. |
| virtual void [SetDateTimeText](../ibaseslideheaderfootermanager/setdatetimetext/)([System::String](../../system/string/)) | Définit le texte de l’espace réservé date-heure de la diapositive. |
| virtual void [SetDateTimeVisibility](../ibaseslideheaderfootermanager/setdatetimevisibility/)(**bool**) | Modifie la visibilité de l’espace réservé date-heure de la diapositive. |
| virtual void [SetFooterAndChildFootersText](./setfooterandchildfooterstext/)([System::String](../../system/string/)) | Définit le texte de l’espace réservé pied de page de la diapositive de notes maîtresse et de tous les espaces réservés pied de page enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus sur les diapositives de notes dépendantes. Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maîtresse. |
| virtual void [SetFooterAndChildFootersVisibility](./setfooterandchildfootersvisibility/)(**bool**) | Modifie la visibilité de l’espace réservé pied de page de la diapositive de notes maîtresse et de tous les espaces réservés pied de page enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus sur les diapositives de notes dépendantes. Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maîtresse. |
| virtual void [SetFooterText](../ibaseslideheaderfootermanager/setfootertext/)([System::String](../../system/string/)) | Définit le texte de l’espace réservé pied de page de la diapositive. |
| virtual void [SetFooterVisibility](../ibaseslideheaderfootermanager/setfootervisibility/)(**bool**) | Modifie la visibilité de l’espace réservé pied de page de la diapositive. |
| virtual void [SetHeaderAndChildHeadersText](./setheaderandchildheaderstext/)([System::String](../../system/string/)) | Définit le texte de l’espace réservé en-tête de la diapositive de notes maîtresse et de tous les espaces réservés en-tête enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus sur les diapositives de notes dépendantes. Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maîtresse. |
| virtual void [SetHeaderAndChildHeadersVisibility](./setheaderandchildheadersvisibility/)(**bool**) | Modifie la visibilité de l’espace réservé en-tête de la diapositive de notes maîtresse et de tous les espaces réservés en-tête enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus sur les diapositives de notes dépendantes. Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maîtresse. |
| virtual void [SetHeaderText](../ibasehandoutnotesslideheaderfootermanag/setheadertext/)([System::String](../../system/string/)) | Définit le texte de l’espace réservé en-tête de la diapositive. |
| virtual void [SetHeaderVisibility](../ibasehandoutnotesslideheaderfootermanag/setheadervisibility/)(**bool**) | Modifie la visibilité de l’espace réservé en-tête de la diapositive. |
| virtual void [SetSlideNumberAndChildSlideNumbersVisibility](./setslidenumberandchildslidenumbersvisibility/)(**bool**) | Modifie la visibilité de l’espace réservé numéro de page de la diapositive de notes maîtresse et de tous les espaces réservés numéro de page enfants. Les espaces réservés enfants signifient que les espaces réservés sont contenus sur les diapositives de notes dépendantes. Les diapositives de notes dépendantes utilisent et dépendent de la diapositive de notes maîtresse. |
| virtual void [SetSlideNumberVisibility](../ibaseslideheaderfootermanager/setslidenumbervisibility/)(**bool**) | Modifie la visibilité de l’espace réservé numéro de page de la diapositive. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument du modèle comme pointeur faible (plutôt que partagé). Autorise le passage des pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagé. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagé. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagé. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet la conversion d’objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faible. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faible. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l’objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [IBaseHandoutNotesSlideHeaderFooterManag](../ibasehandoutnotesslideheaderfootermanag/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)