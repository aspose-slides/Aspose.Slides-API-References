---
title: Hyperlink
second_title: Référence de l'API Aspose.Slides for C++
description: Représente un hyperlien.
type: docs
weight: 1236
url: /fr/aspose.slides/hyperlink/
---
## Hyperlink classe

Représente un hyperlien.

```cpp
class Hyperlink : public Aspose::Slides::PVIObject,
                  public Aspose::Slides::IHyperlink
```

## Méthodes

| Méthode | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Détermine si les deux instances [Hyperlink](./) sont égales. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence au style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux bien que selon IEC 60559:1989 NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux bien que selon IEC 60559:1989 NaN ne soit égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| [HyperlinkActionType](../hyperlinkactiontype/) [get_ActionType](./get_actiontype/)() override | Renvoie le type de l'action de [Hyperlink](./). Lecture seule [HyperlinkActionType](../hyperlinkactiontype/). |
| [HyperlinkColorSource](../hyperlinkcolorsource/) [get_ColorSource](./get_colorsource/)() override | Représente la source de la couleur du lien hypertexte – soit les styles, soit le format de la portion. Lecture [HyperlinkColorSource](../hyperlinkcolorsource/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_EndShow](./get_endshow/)() | Renvoie un lien hypertexte qui termine le diaporama. Lecture seule [Hyperlink](./). |
| [System::String](../../system/string/) [get_ExternalUrl](./get_externalurl/)() override | Spécifie l'URL externe. Lecture seule [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ExternalUrlOriginal](./get_externalurloriginal/)() override | Représente un lien hypertexte qui est défini pour cette portion sans tenir compte du contenu réel de la portion. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_FirstSlide](./get_firstslide/)() | Renvoie un lien hypertexte vers la première diapositive de la présentation. Lecture seule [Hyperlink](./). |
| **bool** [get_HighlightClick](./get_highlightclick/)() override | Détermine si le lien hypertexte doit être mis en évidence lors du clic. Lecture **bool**. |
| **bool** [get_History](./get_history/)() override | Détermine si la cible du lien hypertexte parent doit être ajoutée à une liste de liens hypertexte vus lorsqu'elle est invoquée. Lecture **bool**. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_LastSlide](./get_lastslide/)() | Renvoie un lien hypertexte vers la dernière diapositive de la présentation. Lecture seule [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_LastVievedSlide](./get_lastvievedslide/)() | Renvoie un lien hypertexte vers la dernière diapositive visualisée. Lecture seule [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_Media](./get_media/)() | Renvoie un lien hypertexte spécial « play mediafile ». Utilisé dans [AudioFrame](../audioframe/) et [VideoFrame](../videoframe/). Lecture seule [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_NextSlide](./get_nextslide/)() | Renvoie un lien hypertexte vers la diapositive suivante. Lecture seule [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_NoAction](./get_noaction/)() | Renvoie un lien hypertexte spécial « do nothing ». Lecture seule [Hyperlink](./). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Renvoie le parent [IPresentationComponent](../ipresentationcomponent/). Lecture seule [IPresentationComponent](../ipresentationcomponent/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_PreviousSlide](./get_previousslide/)() | Renvoie un lien hypertexte vers la diapositive précédente. Lecture seule [Hyperlink](./). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() override | Représente le son joué du lien hypertexte. Lecture [IAudio](../iaudio/). |
| **bool** [get_StopSoundOnClick](./get_stopsoundonclick/)() override | Détermine si le son doit être arrêté lors du clic sur le lien hypertexte. Lecture **bool**. |
| [System::String](../../system/string/) [get_TargetFrame](./get_targetframe/)() override | Renvoie le cadre au sein du frameset HTML parent pour la cible du lien hypertexte parent lorsqu'il existe. Lecture/écriture [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() override | Si le [Hyperlink](./) cible une diapositive spécifique, renvoie cette diapositive. Lecture seule [ISlide](../islide/). |
| [System::String](../../system/string/) [get_Tooltip](./get_tooltip/)() override | Renvoie la chaîne qui peut être affichée dans une interface utilisateur associée au lien hypertexte parent. Lecture [System::String](../../system/string/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Sert de fonction de hachage pour un type particulier, adaptée à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
|  [Hyperlink](./hyperlink/)([System::String](../../system/string/)) | Crée une instance d'un lien hypertexte. |
|  [Hyperlink](./hyperlink/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) | Crée une instance d'un lien hypertexte pointant vers une diapositive spécifique. Remarque : le lien hypertexte créé doit être attribué à un objet de la même présentation, sinon le lien sera enregistré comme NoAction. |
|  [Hyperlink](./hyperlink/)([System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\>, [System::String](../../system/string/), [System::String](../../system/string/), **bool**, **bool**, **bool**) | Crée une instance d'un lien hypertexte en utilisant un autre lien hypertexte comme source, en surchargeant les propriétés secondaires. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, vraiment, il initialise simplement le nouvel objet et permet la construction de copies pour les sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, vraiment, il initialise simplement le nouvel objet et permet la construction de copies pour les sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence l'objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| void [set_ColorSource](./set_colorsource/)([HyperlinkColorSource](../hyperlinkcolorsource/)) override | Représente la source de la couleur du lien hypertexte – soit les styles, soit le format de la portion. Écriture [HyperlinkColorSource](../hyperlinkcolorsource/). |
| void [set_HighlightClick](./set_highlightclick/)(**bool**) override | Détermine si le lien hypertexte doit être mis en évidence lors du clic. Écriture **bool**. |
| void [set_History](./set_history/)(**bool**) override | Détermine si la cible du lien hypertexte parent doit être ajoutée à une liste de liens hypertexte vus lorsqu'elle est invoquée. Écriture **bool**. |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | Représente le son joué du lien hypertexte. Écriture [IAudio](../iaudio/). |
| void [set_StopSoundOnClick](./set_stopsoundonclick/)(**bool**) override | Détermine si le son doit être arrêté lors du clic sur le lien hypertexte. Écriture **bool**. |
| void [set_TargetFrame](./set_targetframe/)([System::String](../../system/string/)) override | Renvoie le cadre au sein du frameset HTML parent pour la cible du lien hypertexte parent lorsqu'il existe. Lecture/écriture [System::String](../../system/string/). |
| void [set_Tooltip](./set_tooltip/)([System::String](../../system/string/)) override | Renvoie la chaîne qui peut être affichée dans une interface utilisateur associée au lien hypertexte parent. Écriture [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de changer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente le construct typeof([System.Object](../../system/object/)) de C#. |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Voir aussi

* Classe [PVIObject](../pviobject/)
* Classe [IHyperlink](../ihyperlink/)
* Espace de noms [Aspose::Slides](../)
* Library [Aspose.Slides](../../)