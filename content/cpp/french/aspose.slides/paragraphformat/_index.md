---
title: ParagraphFormat
second_title: Référence de l'API Aspose.Slides pour C++
description: Cette classe contient les propriétés de formatage de paragraphe. Contrairement à IParagraphFormatEffectiveData, toutes les propriétés de cette classe sont modifiables.
type: docs
weight: 4668
url: /fr/aspose.slides/paragraphformat/
---
## ParagraphFormat classe

Cette classe contient les propriétés de formatage de paragraphe. Contrairement à [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/), toutes les propriétés de cette classe sont modifiables.

```cpp
class ParagraphFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IParagraphFormat,
                        public Aspose::Slides::Charts::IChartParagraphFormat
```

## Méthodes

| Méthode | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Compare avec l'objet spécifié. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de points flottants de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de points flottants de style C# où deux NaN sont considérés comme égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() override | Renvoie l'alignement du texte dans un paragraphe sans héritage. Lire [TextAlignment](../textalignment/). |
| **float** [get_DefaultTabSize](./get_defaulttabsize/)() override | Renvoie la taille d'onglet par défaut sans héritage. Lire **float**. |
| [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() override | Détermine si le retour à la ligne Est-Asiatique est utilisé dans un paragraphe. Aucun héritage appliqué. Lire [NullableBool](../nullablebool/). |
| [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() override | Renvoie un alignement de police dans un paragraphe sans héritage. Lire [Slides::FontAlignment](../fontalignment/). |
| [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() override | Détermine si la ponctuation suspendue est utilisée dans un paragraphe. Aucun héritage appliqué. Lire [NullableBool](../nullablebool/). |
| **float** [get_Indent](./get_indent/)() override | Renvoie le retrait de première ligne / retrait suspendu du paragraphe sans héritage. Le retard suspendu peut être défini avec des valeurs négatives. Lire **float**. |
| [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() override | Détermine si le retour à la ligne latin est utilisé dans un paragraphe. Aucun héritage appliqué. Lire [NullableBool](../nullablebool/). |
| **float** [get_MarginLeft](./get_marginleft/)() override | Renvoie la marge gauche dans un paragraphe sans héritage. Lire **float**. |
| **float** [get_MarginRight](./get_marginright/)() override | Renvoie la marge droite dans un paragraphe sans héritage. Lire **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Renvoie l'objet Parent_Immediate. Lecture seule [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Renvoie le parent [IPresentationComponent](../ipresentationcomponent/). Lecture seule [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() override | Détermine si l'écriture de droite à gauche est utilisée dans un paragraphe. Aucun héritage appliqué. Lire [NullableBool](../nullablebool/). |
| **float** [get_SpaceAfter](./get_spaceafter/)() override | Renvoie la quantité d'espace après la dernière ligne d'un paragraphe sans héritage. Une valeur positive indique le pourcentage de la taille de la police que doit occuper l'espace blanc. Une valeur négative indique la taille de l'espace blanc en points. Lire **float**. |
| **float** [get_SpaceBefore](./get_spacebefore/)() override | Renvoie la quantité d'espace avant la première ligne d'un paragraphe sans héritage. Une valeur positive indique le pourcentage de la taille de la police que doit occuper l'espace blanc. Une valeur négative indique la taille de l'espace blanc en points. Lire **float**. |
| **float** [get_SpaceWithin](./get_spacewithin/)() override | Renvoie la quantité d'espace entre les lignes de base dans un paragraphe. Une valeur positive indique un pourcentage, une valeur négative une taille en points. Aucun héritage appliqué. Lire **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) override | Renvoie l'onglet d'un paragraphe à l'indice spécifié. Aucun héritage appliqué. Lecture seule [Aspose::Slides::ITab](../itab/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() override | Renvoie les onglets d'un paragraphe. Aucun héritage appliqué. Lecture seule [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() override | Obtient les données de formatage de paragraphe effectives avec l'héritage appliqué. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Renvoie le code de hachage. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, il initialise simplement un nouveau objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, il initialise simplement un nouveau objet et permet la construction par copie des sous-classes. |
|  [ParagraphFormat](./paragraphformat/)() | Initialise une nouvelle instance de la classe [ParagraphFormat](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) override | Définit l'alignement du texte dans un paragraphe sans héritage. Écrire [TextAlignment](../textalignment/). |
| void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) override | Définit la taille d'onglet par défaut sans héritage. Écrire **float**. |
| void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) override | Détermine si le retour à la ligne Est-Asiatique est utilisé dans un paragraphe. Aucun héritage appliqué. Écrire [NullableBool](../nullablebool/). |
| void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) override | Définit un alignement de police dans un paragraphe sans héritage. Écrire [Slides::FontAlignment](../fontalignment/). |
| void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) override | Détermine si la ponctuation suspendue est utilisée dans un paragraphe. Aucun héritage appliqué. Écrire [NullableBool](../nullablebool/). |
| void [set_Indent](./set_indent/)(**float**) override | Définit le retrait de première ligne / retrait suspendu du paragraphe sans héritage. Le retrait suspendu peut être défini avec des valeurs négatives. Écrire **float**. |
| void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) override | Détermine si le retour à la ligne latin est utilisé dans un paragraphe. Aucun héritage appliqué. Écrire [NullableBool](../nullablebool/). |
| void [set_MarginLeft](./set_marginleft/)(**float**) override | Définit la marge gauche dans un paragraphe sans héritage. Écrire **float**. |
| void [set_MarginRight](./set_marginright/)(**float**) override | Définit la marge droite dans un paragraphe sans héritage. Écrire **float**. |
| void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) override | Détermine si l'écriture de droite à gauche est utilisée dans un paragraphe. Aucun héritage appliqué. Écrire [NullableBool](../nullablebool/). |
| void [set_SpaceAfter](./set_spaceafter/)(**float**) override | Définit la quantité d'espace après la dernière ligne d'un paragraphe sans héritage. Une valeur positive indique le pourcentage de la taille de la police que doit occuper l'espace blanc. Une valeur négative indique la taille de l'espace blanc en points. Écrire **float**. |
| void [set_SpaceBefore](./set_spacebefore/)(**float**) override | Définit la quantité d'espace avant la première ligne d'un paragraphe sans héritage. Une valeur positive indique le pourcentage de la taille de la police que doit occuper l'espace blanc. Une valeur négative indique la taille de l'espace blanc en points. Écrire **float**. |
| void [set_SpaceWithin](./set_spacewithin/)(**float**) override | Définit la quantité d'espace entre les lignes de base dans un paragraphe. Une valeur positive indique un pourcentage, une valeur négative une taille en points. Aucun héritage appliqué. Écrire **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de passer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Remarques

Cette classe est utilisée pour renvoyer et manipuler les propriétés de formatage de paragraphe définies pour le paragraphe particulier. Cela signifie qu'aucun héritage n'est appliqué lors de la récupération des valeurs, de sorte que dans la plupart des cas vous obtiendrez des valeurs signifiant « indéfini ».

Afin d'obtenir les valeurs effectives des paramètres de formatage, y compris celles héritées, vous devez utiliser la méthode [ParagraphFormat::GetEffective](./geteffective/) qui renvoie une instance [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/).

## Voir aussi

* Classe [PVIObject](../pviobject/)
* Classe [IParagraphFormat](../iparagraphformat/)
* Classe [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)