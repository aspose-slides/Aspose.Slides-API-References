---
title: FontsManager
second_title: Référence de l'API Aspose.Slides pour C++
description: Gère les polices à travers la présentation.
type: docs
weight: 989
url: /fr/aspose.slides/fontsmanager/
---
## FontsManager classe

Gère les polices à travers la présentation.

```cpp
class FontsManager : public Aspose::Slides::IFontsManager
```

## Méthodes

| Méthode | Description |
| --- | --- |
| void [AddEmbeddedFont](./addembeddedfont/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>, [Aspose::Slides::Export::EmbedFontCharacters](../../aspose.slides.export/embedfontcharacters/)) override | Ajoute la police incorporée |
| void [AddEmbeddedFont](./addembeddedfont/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [Aspose::Slides::Export::EmbedFontCharacters](../../aspose.slides.export/embedfontcharacters/)) override | Ajoute la police incorporée |
| virtual void [AddEmbeddedFont](../ifontsmanager/addembeddedfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>, [Export::EmbedFontCharacters](../../aspose.slides.export/embedfontcharacters/)) | Ajoute la police incorporée. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence à la façon C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur à la façon C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontFallBackRule](../ifontfallbackrule/)\> [get_FontFallBackRule](./get_fontfallbackrule/)(**int32_t**) override | Renvoie la règle à l’index spécifié pour des substitutions appropriées par la fonctionnalité de secours. Lecture seule [Aspose::Slides::IFontFallBackRule](../ifontfallbackrule/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontFallBackRulesCollection](../ifontfallbackrulescollection/)\> [get_FontFallBackRulesCollection](./get_fontfallbackrulescollection/)() override | Représente la collection d’un utilisateur de règles FontFallBack pour la gestion des collections de polices afin de permettre des substitutions appropriées par la fonctionnalité de secours Lecture [IFontFallBackRulesCollection](../ifontfallbackrulescollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRule](../ifontsubstrule/)\> [get_FontSubstRule](./get_fontsubstrule/)(**int32_t**) override | Renvoie la règle de substitution de police à l’index spécifié à utiliser lors du rendu. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../ifontsubstrulecollection/)\> [get_FontSubstRuleList](./get_fontsubstrulelist/)() override | Substitutions de police à utiliser lors du rendu. Lecture [IFontSubstRuleCollection](../ifontsubstrulecollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l’objet. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>\> [GetEmbeddedFonts](./getembeddedfonts/)() override | Renvoie les polices incorporées dans la présentation |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetFontBytes](./getfontbytes/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>, [Aspose::Slides::FontStyleType](../fontstyletype/)) override | Récupère le tableau d’octets représentant les données de police pour un style de police et des données de police spécifiés. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetFontBytes](../ifontsmanager/getfontbytes/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>, [FontStyleType](../fontstyletype/)) | Récupère le tableau d’octets représentant les données de police pour un style de police et des données de police spécifiés. |
| [Aspose::Slides::EmbeddingLevel](../embeddinglevel/) [GetFontEmbeddingLevel](./getfontembeddinglevel/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::String](../../system/string/)) override | Détermine le niveau d’incorporation d’une police à partir du tableau d’octets donné et du nom de police. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>\> [GetFonts](./getfonts/)() override | Renvoie les polices utilisées dans la présentation |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d’objets personnalisés. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::FontSubstitutionInfo](../fontsubstitutioninfo/)\>\>\> [GetSubstitutions](./getsubstitutions/)() override | Obtient les informations sur les polices qui seront remplacées lors du rendu de la présentation. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::FontSubstitutionInfo](../fontsubstitutioninfo/)\>\>\> [GetSubstitutions](./getsubstitutions/)([System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) override | Obtient les informations sur les polices qui seront remplacées lors du rendu des diapositives spécifiées. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l’objet. Analogue de l’appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l’objet représente une instance du type décrit par targetType. Analogue de l’opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l’objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d’affectation. Ne copie rien, en fait, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d’une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| void [RemoveEmbeddedFont](./removeembeddedfont/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>) override | Supprime la police incorporée |
| virtual void [RemoveEmbeddedFont](../ifontsmanager/removeembeddedfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Supprime la police incorporée |
| void [ReplaceFont](./replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontData](../ifontdata/)\>) override | Remplace la police dans la présentation |
| void [ReplaceFont](./replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRule](../ifontsubstrule/)\>) override | Remplace la police dans la présentation en utilisant les informations fournies dans [FontSubstRule](../fontsubstrule/) |
| void [ReplaceFont](./replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../ifontsubstrulecollection/)\>) override | Remplace la police dans la présentation en utilisant les informations fournies dans la collection de [FontSubstRule](../fontsubstrule/) |
| virtual void [ReplaceFont](../ifontsmanager/replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Remplace la police dans la présentation |
| virtual void [ReplaceFont](../ifontsmanager/replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSubstRule](../ifontsubstrule/)\>) | Remplace la police dans la présentation en utilisant les informations fournies dans [IFontSubstRule](../ifontsubstrule/) |
| virtual void [ReplaceFont](../ifontsmanager/replacefont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSubstRuleCollection](../ifontsubstrulecollection/)\>) | Remplace la police dans la présentation en utilisant les informations fournies dans la collection de [IFontSubstRule](../ifontsubstrule/) |
| void [set_FontFallBackRulesCollection](./set_fontfallbackrulescollection/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontFallBackRulesCollection](../ifontfallbackrulescollection/)\>) override | Représente la collection d’un utilisateur de règles FontFallBack pour la gestion des collections de polices afin de permettre des substitutions appropriées par la fonctionnalité de secours Écriture [IFontFallBackRulesCollection](../ifontfallbackrulescollection/). |
| virtual void [set_FontFallBackRulesCollection](../ifontsmanager/set_fontfallbackrulescollection/)([System::SharedPtr](../../system/sharedptr/)\<[IFontFallBackRulesCollection](../ifontfallbackrulescollection/)\>) | Représente la collection d’un utilisateur de règles FontFallBack pour la gestion des collections de polices afin de permettre des substitutions appropriées par la fonctionnalité de secours Écriture [IFontFallBackRulesCollection](../ifontfallbackrulescollection/). |
| void [set_FontSubstRuleList](./set_fontsubstrulelist/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../ifontsubstrulecollection/)\>) override | Substitutions de police à utiliser lors du rendu. Écriture [IFontSubstRuleCollection](../ifontsubstrulecollection/). |
| virtual void [set_FontSubstRuleList](../ifontsmanager/set_fontsubstrulelist/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSubstRuleCollection](../ifontsubstrulecollection/)\>) | Substitutions de police à utiliser lors du rendu Écriture [IFontSubstRuleCollection](../ifontsubstrulecollection/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme un pointeur faible (plutôt que partagé). Permet de changer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l’instruction C# lock(). Appelez directement ou utilisez l’objet sentinelle [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l’objet. Libère toutes les structures de données internes. |

## Remarques

L’exemple suivant montre comment ajouter des polices incorporées à PowerPoint [Presentation](../presentation/).
```cpp
auto presentation = System::MakeObject<Presentation>(u"Fonts.pptx");
System::ArrayPtr<System::SharedPtr<IFontData>> allFonts = presentation->get_FontsManager()->GetFonts();
System::ArrayPtr<System::SharedPtr<IFontData>> embeddedFonts = presentation->get_FontsManager()->GetEmbeddedFonts();

for (auto&& font : allFonts)
{
    if (!embeddedFonts->Contains(font))
    {
        presentation->get_FontsManager()->AddEmbeddedFont(font, EmbedFontCharacters::All);
    }
}

// Save the presentation
presentation->Save(u"AddEmbeddedFont_out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Classe [IFontsManager](../ifontsmanager/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)