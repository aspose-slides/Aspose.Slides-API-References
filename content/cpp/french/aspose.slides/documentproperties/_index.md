---
title: DocumentProperties
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente les propriétés d'une présentation.
type: docs
weight: 794
url: /fr/aspose.slides/documentproperties/
---
## DocumentProperties classe

Représente les propriétés d'une présentation.

```cpp
class DocumentProperties : public Aspose::Slides::IDocumentProperties,
                           public Aspose::Slides::IGenericCloneable<System::SharedPtr<Aspose::Slides::IDocumentProperties>>
```

## Méthodes

| Method | Description |
| --- | --- |
| void [ClearBuiltInProperties](./clearbuiltinproperties/)() override | Efface et définit les valeurs par défaut pour toutes les propriétés intégrées. |
| void [ClearCustomProperties](./clearcustomproperties/)() override | Supprime toutes les propriétés personnalisées. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | Clone l'objet actuel. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [CloneT](./clonet/)() override | Clone l'objet actuel. |
| **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) override | Vérifie la présence d'une propriété personnalisée avec un nom spécifié. |
| [DocumentProperties](./documentproperties/)() | Initialise une nouvelle instance de la classe [DocumentProperties](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés égaux bien que selon IEC 60559:1989 NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés égaux bien que selon IEC 60559:1989 NaN ne soit égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À usage interne uniquement. |
| [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() override | Renvoie le modèle d'une application. Lire [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() override | Renvoie la version de l'application. Lecture seule [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Author](./get_author/)() override | Renvoie l'auteur d'une présentation. Lire [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Category](./get_category/)() override | Renvoie la catégorie d'une présentation. Lire [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | Renvoie les commentaires d'une présentation. Lire [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Company](./get_company/)() override | Renvoie la propriété de l'entreprise. Lire [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() override | Renvoie l'état du contenu d'une présentation. Lire [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Renvoie le type de contenu d'une présentation. Lire [System::String](../../system/string/). |
| **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() override | Renvoie le nombre de propriétés personnalisées réellement contenues dans une collection. Lecture seule **int32_t**. |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | Renvoie la date de création d'une présentation. Les valeurs sont en UTC. Lire [System::DateTime](../../system/datetime/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() override | Indique le regroupement des parties du document et le nombre de parties dans chaque groupe. Lecture seule [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| **int32_t** [get_HiddenSlides](./get_hiddenslides/)() override | Renvoie le nombre de diapositives masquées dans un document de présentation. Lecture seule **int32_t**. |
| [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() override | Renvoie la propriété de document HyperlinkBase. Lire [System::String](../../system/string/). |
| **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() override | Spécifie qu'un ou plusieurs hyperliens dans cette partie ont été mis à jour exclusivement dans cette partie par un producteur. Le prochain producteur ouvrant ce document devra mettre à jour les relations d'hyperliens avec les nouveaux hyperliens spécifiés dans cette partie. Lire **bool**. |
| [System::String](../../system/string/) [get_Keywords](./get_keywords/)() override | Renvoie les mots-clés d'une présentation. Lire [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() override | Renvoie la date à laquelle une présentation a été imprimée pour la dernière fois. Lire [System::DateTime](../../system/datetime/). |
| [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() override | Renvoie le nom de la dernière personne ayant modifié une présentation. Lire [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() override | Renvoie la date de la dernière modification d'une présentation. Les valeurs sont en UTC. Lecture seule dans le cas de [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (car elle sera mise à jour en interne pendant le processus d'enregistrement de l'objet [IPresentation](../ipresentation/)). Peut être modifiée via l'instance [DocumentProperties](./) renvoyée par la méthode [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Veuillez voir l'exemple dans le résumé de la méthode [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| **bool** [get_LinksUpToDate](./get_linksuptodate/)() override | Indique si les hyperliens dans un document sont à jour. Définissez cet élément sur **true** pour indiquer que les hyperliens sont mis à jour. Définissez cet élément sur **false** pour indiquer que les hyperliens sont obsolètes. Lire **bool**. |
| [System::String](../../system/string/) [get_Manager](./get_manager/)() override | Renvoie la propriété du gestionnaire. Lire [System::String](../../system/string/). |
| **int32_t** [get_MultimediaClips](./get_multimediaclips/)() override | Renvoie le nombre total de clips audio ou vidéo présents dans le document. Lecture seule **int32_t**. |
| [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() override | Renvoie le nom de l'application. Lire [System::String](../../system/string/). |
| **int32_t** [get_Notes](./get_notes/)() override | Renvoie le nombre de diapositives dans une présentation contenant des notes. Lecture seule **int32_t**. |
| **int32_t** [get_Paragraphs](./get_paragraphs/)() override | Renvoie le nombre total de paragraphes trouvés dans un document le cas échéant. Lecture seule **int32_t**. |
| [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() override | Renvoie le format prévu d'une présentation. Lire [System::String](../../system/string/). |
| **int32_t** [get_RevisionNumber](./get_revisionnumber/)() override | Renvoie le numéro de révision de la présentation. Lire **int32_t**. |
| **bool** [get_ScaleCrop](./get_scalecrop/)() override | Indique le mode d'affichage de la miniature du document. Définissez cet élément sur **true** pour activer le redimensionnement de la miniature du document à l'affichage. Définissez cet élément sur **false** pour activer le recadrage de la miniature du document afin de n'afficher que les sections qui correspondent à l'affichage. Lire **bool**. |
| **bool** [get_SharedDoc](./get_shareddoc/)() override | Détermine si la présentation est partagée entre plusieurs personnes. Lire **bool**. |
| **int32_t** [get_Slides](./get_slides/)() override | Renvoie le nombre total de diapositives dans un document de présentation. Lecture seule **int32_t**. |
| [System::String](../../system/string/) [get_Subject](./get_subject/)() override | Renvoie le sujet d'une présentation. Lire [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | Renvoie le titre d'une présentation. Lire [System::String](../../system/string/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() override | Spécifie le titre de chaque partie du document. Ces parties ne sont pas des parties de document mais des représentations conceptuelles de sections du document. Lecture seule [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() override | Temps total d'édition d'une présentation. Lire [System::TimeSpan](../../system/timespan/). |
| **int32_t** [get_Words](./get_words/)() override | Renvoie le nombre total de mots contenus dans un document. Lecture seule **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) override | Renvoie le nom d'une propriété personnalisée à l'index spécifié. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) override | Obtient une valeur booléenne nommée à partir des propriétés personnalisées. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) override | Obtient une valeur entière nommée à partir des propriétés personnalisées. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) override | Obtient une valeur DateTime nommée à partir des propriétés personnalisées. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) override | Obtient une valeur chaîne nommée à partir des propriétés personnalisées. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) override | Obtient une valeur flottante nommée à partir des propriétés personnalisées. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) override | Obtient une valeur double nommée à partir des propriétés personnalisées. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() override | Obtient un tableau d'étiquettes de sensibilité à partir des propriétés personnalisées du document (Métadonnées Microsoft Information Protection SDK). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) override | Renvoie la propriété personnalisée associée à un nom spécifié. Lire [System::Object](../../system/object/). |
| void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Définit la propriété personnalisée associée à un nom spécifié. Écrire [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
| [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, il initialise simplement un nouvel objet et permet la construction de copies des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en réalité, il initialise simplement un nouvel objet et permet la construction de copies des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) override | Supprime une propriété personnalisée associée à un nom spécifié. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du montant spécifié. |
| void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) override | Définit le modèle d'une application. Écrire [System::String](../../system/string/). |
| void [set_Author](./set_author/)([System::String](../../system/string/)) override | Définit l'auteur d'une présentation. Écrire [System::String](../../system/string/). |
| void [set_Category](./set_category/)([System::String](../../system/string/)) override | Définit la catégorie d'une présentation. Écrire [System::String](../../system/string/). |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | Définit les commentaires d'une présentation. Écrire [System::String](../../system/string/). |
| void [set_Company](./set_company/)([System::String](../../system/string/)) override | Définit la propriété de l'entreprise. Écrire [System::String](../../system/string/). |
| void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) override | Définit l'état du contenu d'une présentation. Écrire [System::String](../../system/string/). |
| void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) override | Définit le type de contenu d'une présentation. Écrire [System::String](../../system/string/). |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | Renvoie la date de création d'une présentation. Les valeurs sont en UTC. Écrire [System::DateTime](../../system/datetime/). |
| void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) override | Définit la propriété de document HyperlinkBase. Écrire [System::String](../../system/string/). |
| void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) override | Spécifie qu'un ou plusieurs hyperliens dans cette partie ont été mis à jour exclusivement dans cette partie par un producteur. Le prochain producteur ouvrant ce document devra mettre à jour les relations d'hyperliens avec les nouveaux hyperliens spécifiés dans cette partie. Écrire **bool**. |
| void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) override | Définit les mots-clés d'une présentation. Écrire [System::String](../../system/string/). |
| void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) override | Renvoie la date à laquelle une présentation a été imprimée pour la dernière fois. Écrire [System::DateTime](../../system/datetime/). |
| void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) override | Définit le nom de la dernière personne ayant modifié une présentation. Écrire [System::String](../../system/string/). |
| void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) override | Renvoie la date de la dernière modification d'une présentation. Les valeurs sont en UTC. Lecture seule dans le cas de [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (car elle sera mise à jour en interne pendant le processus d'enregistrement de l'objet [IPresentation](../ipresentation/)). Peut être modifiée via l'instance [DocumentProperties](./) renvoyée par la méthode [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Veuillez voir l'exemple dans le résumé de la méthode [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) override | Indique si les hyperliens dans un document sont à jour. Définissez cet élément sur **true** pour indiquer que les hyperliens sont mis à jour. Définissez cet élément sur **false** pour indiquer que les hyperliens sont obsolètes. Écrire **bool**. |
| void [set_Manager](./set_manager/)([System::String](../../system/string/)) override | Définit la propriété du gestionnaire. Écrire [System::String](../../system/string/). |
| void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) override | Définit le nom de l'application. Écrire [System::String](../../system/string/). |
| void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) override | Définit le format prévu d'une présentation. Écrire [System::String](../../system/string/). |
| void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) override | Définit le numéro de révision de la présentation. Écrire **int32_t**. |
| void [set_ScaleCrop](./set_scalecrop/)(**bool**) override | Indique le mode d'affichage de la miniature du document. Définissez cet élément sur **true** pour activer le redimensionnement de la miniature du document à l'affichage. Définissez cet élément sur **false** pour activer le recadrage de la miniature du document afin de n'afficher que les sections qui correspondent à l'affichage. Écrire **bool**. |
| void [set_SharedDoc](./set_shareddoc/)(**bool**) override | Détermine si la présentation est partagée entre plusieurs personnes. Écrire **bool**. |
| void [set_Subject](./set_subject/)([System::String](../../system/string/)) override | Définit le sujet d'une présentation. Écrire [System::String](../../system/string/). |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | Définit le titre d'une présentation. Écrire [System::String](../../system/string/). |
| void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) override | Temps total d'édition d'une présentation. Écrire [System::TimeSpan](../../system/timespan/). |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) override | Définit une propriété booléenne personnalisée nommée. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) override | Définit une propriété entière personnalisée nommée. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) override | Définit une propriété DateTime personnalisée nommée. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Définit une propriété chaîne personnalisée nommée. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) override | Définit une propriété flottante personnalisée nommée. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) override | Définit une propriété double personnalisée nommée. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de changer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir les objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Remarques

L'exemple suivant montre comment accéder aux propriétés intégrées de PowerPoint [Presentation](../presentation/).
```cpp
// Instancier la classe Presentation qui représente la présentation
auto pres = System::MakeObject<Presentation>(dataDir + u"AccessBuiltin Properties.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = pres->get_DocumentProperties();
// Display the builtin properties
System::Console::WriteLine(System::String(u"Category : ") + documentProperties->get_Category());
System::Console::WriteLine(System::String(u"Current Status : ") + documentProperties->get_ContentStatus());
System::Console::WriteLine(System::String(u"Creation Date : ") + documentProperties->get_CreatedTime());
System::Console::WriteLine(System::String(u"Author : ") + documentProperties->get_Author());
System::Console::WriteLine(System::String(u"Description : ") + documentProperties->get_Comments());
```
L'exemple suivant montre comment modifier les propriétés intégrées de PowerPoint [Presentation](../presentation/).
```cpp
// Instancier la classe Presentation qui représente la Presentation
auto presentation = System::MakeObject<Presentation>(dataDir + u"ModifyBuiltinProperties.pptx");

// Créer une référence à l'objet IDocumentProperties associé à Presentation
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();
// Définir les propriétés intégrées
documentProperties->set_Author(u"Aspose.Slides for .NET");
documentProperties->set_Title(u"Modifying Presentation Properties");
documentProperties->set_Subject(u"Aspose Subject");
// Enregistrer votre présentation dans un fichier
presentation->Save(u"DocumentProperties_out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Classe [IDocumentProperties](../idocumentproperties/)
* Classe [IGenericCloneable](../igenericcloneable/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)