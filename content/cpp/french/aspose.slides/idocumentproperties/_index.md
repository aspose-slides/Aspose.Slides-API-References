---
title: IDocumentProperties
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente les propriétés d'une présentation.
type: docs
weight: 1977
url: /fr/aspose.slides/idocumentproperties/
---
## IDocumentProperties classe

Représente les propriétés d'une présentation.

```cpp
class IDocumentProperties : public virtual System::Object
```

## Méthodes

| Méthode | Description |
| --- | --- |
| virtual void [ClearBuiltInProperties](./clearbuiltinproperties/)() | Efface et définit les valeurs par défaut pour toutes les propriétés intégrées. |
| virtual void [ClearCustomProperties](./clearcustomproperties/)() | Supprime toutes les propriétés personnalisées. |
| virtual **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) | Vérifie la présence d'une propriété personnalisée avec un nom spécifié. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres flottants de type C# où deux NaN sont considérés comme égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres flottants de type C# où deux NaN sont considérés comme égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| virtual [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() | Renvoie le modèle d'une application. Lire [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() | Renvoie la version de l'application. Lecture seule [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Author](./get_author/)() | Renvoie l'auteur d'une présentation. Lire [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Category](./get_category/)() | Renvoie la catégorie d'une présentation. Lire [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Comments](./get_comments/)() | Renvoie les commentaires d'une présentation. Lire [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Company](./get_company/)() | Renvoie la propriété société. Lire [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() | Renvoie l'état du contenu d'une présentation. Lire [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() | Renvoie le type de contenu d'une présentation. Lire [System::String](../../system/string/). |
| virtual **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() | Renvoie le nombre de propriétés personnalisées réellement contenues dans une collection. Lecture seule **int32_t**. |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() | Renvoie la date à laquelle une présentation a été créée. Les valeurs sont en UTC. Lire [System::DateTime](../../system/datetime/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() | Indique le regroupement des parties du document et le nombre de parties dans chaque groupe. Lecture seule [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| virtual **int32_t** [get_HiddenSlides](./get_hiddenslides/)() | Spécifie le nombre de diapositives cachées dans un document de présentation. Lecture seule **int32_t**. |
| virtual [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() | Renvoie la propriété du document HyperlinkBase. Lire [System::String](../../system/string/). |
| virtual **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() | Spécifie qu'un ou plusieurs hyperliens dans cette partie ont été mis à jour exclusivement dans cette partie par un producteur. Le prochain producteur ouvrant ce document devra mettre à jour les relations d'hyperliens avec les nouveaux hyperliens spécifiés dans cette partie. Lire **bool**. |
| virtual [System::String](../../system/string/) [get_Keywords](./get_keywords/)() | Renvoie les mots-clés d'une présentation. Lire [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() | Renvoie la date de la dernière impression d'une présentation. Lire [System::DateTime](../../system/datetime/). |
| virtual [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() | Renvoie le nom de la dernière personne ayant modifié une présentation. Lire [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() | Renvoie la date à laquelle une présentation a été modifiée pour la dernière fois. Les valeurs sont en UTC. Lecture seule dans le cas de Presentation.DocumentProperties (car elle sera mise à jour en interne pendant le processus d'enregistrement de l'objet [IPresentation](../ipresentation/)). Peut être modifiée via l'instance [DocumentProperties](../documentproperties/) retournée par la méthode [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Veuillez consulter l'exemple dans le résumé de la méthode [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| virtual **bool** [get_LinksUpToDate](./get_linksuptodate/)() | Indique si les hyperliens d'un document sont à jour. Définissez cet élément sur **true** pour indiquer que les hyperliens sont mis à jour. Définissez cet élément sur **false** pour indiquer que les hyperliens sont obsolètes. Lire **bool**. |
| virtual [System::String](../../system/string/) [get_Manager](./get_manager/)() | Renvoie la propriété du gestionnaire. Lire [System::String](../../system/string/). |
| virtual **int32_t** [get_MultimediaClips](./get_multimediaclips/)() | Spécifie le nombre total de clips audio ou vidéo présents dans le document. Lecture seule **int32_t**. |
| virtual [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() | Renvoie le nom de l'application. Lire [System::String](../../system/string/). |
| virtual **int32_t** [get_Notes](./get_notes/)() | Spécifie le nombre de diapositives d'une présentation contenant des notes. Lecture seule **int32_t**. |
| virtual **int32_t** [get_Paragraphs](./get_paragraphs/)() | Spécifie le nombre total de paragraphes trouvés dans un document, le cas échéant. Lecture seule **int32_t**. |
| virtual [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() | Renvoie le format prévu d'une présentation. Lire [System::String](../../system/string/). |
| virtual **int32_t** [get_RevisionNumber](./get_revisionnumber/)() | Renvoie le numéro de révision de la présentation. Lire **int32_t**. |
| virtual **bool** [get_ScaleCrop](./get_scalecrop/)() | Indique le mode d'affichage de la miniature du document. Définissez cet élément sur **true** pour activer le redimensionnement de la miniature du document à l'affichage. Définissez cet élément sur **false** pour activer le recadrage de la miniature du document afin de n'afficher que les sections qui s'adaptent à l'affichage. Lire **bool**. |
| virtual **bool** [get_SharedDoc](./get_shareddoc/)() | Détermine si la présentation est partagée entre plusieurs personnes. Lire **bool**. |
| virtual **int32_t** [get_Slides](./get_slides/)() | Spécifie le nombre total de diapositives dans un document de présentation. Lecture seule **int32_t**. |
| virtual [System::String](../../system/string/) [get_Subject](./get_subject/)() | Renvoie le sujet d'une présentation. Lire [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | Renvoie le titre d'une présentation. Lire [System::String](../../system/string/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() | Spécifie le titre de chaque partie du document. Ces parties ne sont pas des parties de document mais des représentations conceptuelles des sections du document. Lecture seule [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| virtual [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() | Temps total d'édition d'une présentation. Lire [System::TimeSpan](../../system/timespan/). |
| virtual **int32_t** [get_Words](./get_words/)() | Spécifie le nombre total de mots contenus dans un document. Lecture seule **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) | Renvoie le nom d'une propriété personnalisée à l'index spécifié. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) | Obtient une valeur booléenne nommée à partir des propriétés personnalisées. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) | Obtient une valeur entière nommée à partir des propriétés personnalisées. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) | Obtient une valeur DateTime nommée à partir des propriétés personnalisées. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) | Obtient une valeur chaîne nommée à partir des propriétés personnalisées. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) | Obtient une valeur flottante nommée à partir des propriétés personnalisées. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) | Obtient une valeur double nommée à partir des propriétés personnalisées. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Active le hachage des objets personnalisés. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() | Obtient un tableau d'étiquettes de sensibilité à partir des propriétés personnalisées du document (Métadonnées du SDK Microsoft Information Protection). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) | Renvoie la propriété personnalisée associée à un nom spécifié. Lire [System::Object](../../system/object/). |
| virtual void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Définit la propriété personnalisée associée à un nom spécifié. Écrire [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Active le clonage des types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes. |
| virtual **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) | Supprime une propriété personnalisée associée à un nom spécifié. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| virtual void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) | Définit le modèle d'une application. Écrire [System::String](../../system/string/). |
| virtual void [set_Author](./set_author/)([System::String](../../system/string/)) | Définit l'auteur d'une présentation. Écrire [System::String](../../system/string/). |
| virtual void [set_Category](./set_category/)([System::String](../../system/string/)) | Définit la catégorie d'une présentation. Écrire [System::String](../../system/string/). |
| virtual void [set_Comments](./set_comments/)([System::String](../../system/string/)) | Définit les commentaires d'une présentation. Écrire [System::String](../../system/string/). |
| virtual void [set_Company](./set_company/)([System::String](../../system/string/)) | Définit la propriété société. Écrire [System::String](../../system/string/). |
| virtual void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) | Définit l'état du contenu d'une présentation. Écrire [System::String](../../system/string/). |
| virtual void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) | Définit le type de contenu d'une présentation. Écrire [System::String](../../system/string/). |
| virtual void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) | Renvoie la date à laquelle une présentation a été créée. Les valeurs sont en UTC. Écrire [System::DateTime](../../system/datetime/). |
| virtual void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) | Définit la propriété du document HyperlinkBase. Écrire [System::String](../../system/string/). |
| virtual void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) | Spécifie qu'un ou plusieurs hyperliens dans cette partie ont été mis à jour exclusivement dans cette partie par un producteur. Le prochain producteur ouvrant ce document devra mettre à jour les relations d'hyperliens avec les nouveaux hyperliens spécifiés dans cette partie. Écrire **bool**. |
| virtual void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) | Définit les mots-clés d'une présentation. Écrire [System::String](../../system/string/). |
| virtual void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) | Renvoie la date de la dernière impression d'une présentation. Écrire [System::DateTime](../../system/datetime/). |
| virtual void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) | Définit le nom de la dernière personne ayant modifié une présentation. Écrire [System::String](../../system/string/). |
| virtual void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) | Renvoie la date à laquelle une présentation a été modifiée pour la dernière fois. Les valeurs sont en UTC. Lecture seule dans le cas de Presentation.DocumentProperties (car elle sera mise à jour en interne pendant le processus d'enregistrement de l'objet [IPresentation](../ipresentation/)). Peut être modifiée via l'instance [DocumentProperties](../documentproperties/) retournée par la méthode [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Veuillez consulter l'exemple dans le résumé de la méthode [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| virtual void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) | Indique si les hyperliens d'un document sont à jour. Définissez cet élément sur **true** pour indiquer que les hyperliens sont mis à jour. Définissez cet élément sur **false** pour indiquer que les hyperliens sont obsolètes. Écrire **bool**. |
| virtual void [set_Manager](./set_manager/)([System::String](../../system/string/)) | Définit la propriété du gestionnaire. Écrire [System::String](../../system/string/). |
| virtual void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) | Définit le nom de l'application. Écrire [System::String](../../system/string/). |
| virtual void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) | Définit le format prévu d'une présentation. Écrire [System::String](../../system/string/). |
| virtual void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) | Définit le numéro de révision de la présentation. Écrire **int32_t**. |
| virtual void [set_ScaleCrop](./set_scalecrop/)(**bool**) | Indique le mode d'affichage de la miniature du document. Définissez cet élément sur **true** pour activer le redimensionnement de la miniature du document à l'affichage. Définissez cet élément sur **false** pour activer le recadrage de la miniature du document afin de n'afficher que les sections qui s'adaptent à l'affichage. Écrire **bool**. |
| virtual void [set_SharedDoc](./set_shareddoc/)(**bool**) | Détermine si la présentation est partagée entre plusieurs personnes. Écrire **bool**. |
| virtual void [set_Subject](./set_subject/)([System::String](../../system/string/)) | Définit le sujet d'une présentation. Écrire [System::String](../../system/string/). |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | Définit le titre d'une présentation. Écrire [System::String](../../system/string/). |
| virtual void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) | Temps total d'édition d'une présentation. Écrire [System::TimeSpan](../../system/timespan/). |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) | Définit une propriété booléenne personnalisée nommée. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) | Définit une propriété entière personnalisée nommée. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) | Définit une propriété DateTime personnalisée nommée. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) | Définit une propriété chaîne personnalisée nommée. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) | Définit une propriété flottante personnalisée nommée. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) | Définit une propriété double personnalisée nommée. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Active la conversion des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [Object](../../system/object/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)