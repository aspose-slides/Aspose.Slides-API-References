---
title: PortionFormat
second_title: Référence de l'API Aspose.Slides pour C++
description: Cette classe contient les propriétés de mise en forme des portions de texte. Contrairement à IPortionFormatEffectiveData, toutes les propriétés de cette classe sont modifiables.
type: docs
weight: 4811
url: /fr/aspose.slides/portionformat/
---
## PortionFormat classe

This class contains the text portion formatting properties. Unlike [IPortionFormatEffectiveData](../iportionformateffectivedata/), all properties of this class are writeable.

```cpp
class PortionFormat : public Aspose::Slides::BasePortionFormat,
                      public Aspose::Slides::IPortionFormat
```

## Méthodes

| Méthode | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Compare avec l'objet spécifié. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../baseportionformat/get_alternativelanguageid/)() override | Renvoie l'Id d'une langue alternative. Lire [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() override | Renvoie l'identifiant du signet. Lire [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../baseportionformat/get_complexscriptfont/)() override | Renvoie les informations de police du script complexe. Null signifie que la police est indéfinie et doit être héritée du Maître. Lire [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../baseportionformat/get_eastasianfont/)() override | Renvoie les informations de police Est-Asiatique. Null signifie que la police est indéfinie et doit être héritée du Maître. Lire [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../baseportionformat/get_effectformat/)() override | Renvoie les propriétés du texte [EffectFormat](../effectformat/). Aucun héritage appliqué. Lecture seule [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](../baseportionformat/get_escapement/)() override | Renvoie le texte en exposant ou indice. Valeur de -100 % (indice) à 100 % (exposant). **std::numeric_limits<float>::quiet_NaN()** signifie que la valeur est indéfinie et doit être héritée du Maître. Lecture **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../baseportionformat/get_fillformat/)() override | Renvoie les propriétés du texte [FillFormat](../fillformat/). Aucun héritage appliqué. Lecture seule [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](../baseportionformat/get_fontbold/)() override | Détermine si la police est en gras. Aucun héritage appliqué. Lire [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](../baseportionformat/get_fontheight/)() override | Renvoie la hauteur de police d'une portion. **std::numeric_limits<float>::quiet_NaN()** signifie que la hauteur est indéfinie et doit être héritée du Maître. Lecture **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](../baseportionformat/get_fontitalic/)() override | Détermine si la police est italique. Aucun héritage appliqué. Lire [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../baseportionformat/get_fontunderline/)() override | Renvoie le type de soulignement du texte. Aucun héritage appliqué. Lire [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../baseportionformat/get_highlightcolor/)() override | Renvoie la couleur utilisée pour mettre en évidence un texte. Aucun héritage appliqué. Lecture seule [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | Renvoie le lien hypertexte défini pour le clic de souris. Lire [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | Gestionnaire de liens hypertexte. Lecture seule [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | Renvoie le lien hypertexte défini pour le survol de la souris. Lire [IHyperlink](../ihyperlink/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../baseportionformat/get_ishardunderlinefill/)() override | Détermine si le style de soulignement possède ses propres propriétés [FillFormat](../fillformat/) ou les hérite des propriétés [FillFormat](../fillformat/) du texte. Lire [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../baseportionformat/get_ishardunderlineline/)() override | Détermine si le style de soulignement possède ses propres propriétés [LineFormat](../lineformat/) ou les hérite des propriétés [LineFormat](../lineformat/) du texte. Lire [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](../baseportionformat/get_kerningminimalsize/)() override | Renvoie la taille de police minimale, pour laquelle le crénage doit être activé. **std::numeric_limits<float>::quiet_NaN()** signifie que la valeur est indéfinie et doit être héritée du Maître. Lecture **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](../baseportionformat/get_kumimoji/)() override | Détermine si les nombres doivent ignorer la mise en page verticale du texte propre aux langues orientales. Aucun héritage appliqué. Lire [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](../baseportionformat/get_languageid/)() override | Renvoie l'Id d'une langue de vérification. Utilisée pour la vérification de l'orthographe et de la grammaire. Lire [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../baseportionformat/get_latinfont/)() override | Renvoie les informations de police Latin. Null signifie que la police est indéfinie et doit être héritée du Maître. Lire [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../baseportionformat/get_lineformat/)() override | Renvoie les propriétés [LineFormat](../lineformat/) pour le contour du texte. Aucun héritage appliqué. Lecture seule [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](../baseportionformat/get_normaliseheight/)() override | Détermine si la hauteur du texte doit être normalisée. Aucun héritage appliqué. Lire [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Renvoie l'objet Parent_Immediate. Lecture seule [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Renvoie le parent [IPresentationComponent](../ipresentationcomponent/). Lecture seule [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](../baseportionformat/get_proofdisabled/)() override | Détermine si le texte ne doit pas être vérifié. Aucun héritage appliqué. Lire [NullableBool](../nullablebool/). |
| **bool** [get_SmartTagClean](./get_smarttagclean/)() override | Détermine si la smart tag doit être nettoyée. Aucun héritage appliqué. Lecture **bool**. |
| **float** [get_Spacing](../baseportionformat/get_spacing/)() override | Renvoie l'incrément d'espacement intercaractères. **std::numeric_limits<float>::quiet_NaN()** signifie que la valeur est indéfinie et doit être héritée du Maître. Lecture **float**. |
| **bool** [get_SpellCheck](../baseportionformat/get_spellcheck/)() override | Obtient une valeur indiquant si la vérification orthographique est activée pour la portion de texte. Lorsque cette propriété est définie sur false, les vérifications orthographiques des éléments de texte sont supprimées. Lorsqu'elle est définie sur true, la vérification orthographique est autorisée. La valeur par défaut est **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../baseportionformat/get_strikethroughtype/)() override | Renvoie le type de barré d'un texte. Aucun héritage appliqué. Lire [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../baseportionformat/get_symbolfont/)() override | Renvoie les informations de police symbolique. Null signifie que la police est indéfinie et doit être héritée du Maître. Lire [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../baseportionformat/get_textcaptype/)() override | Renvoie le type de capitalisation du texte. Aucun héritage appliqué. Lire [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../baseportionformat/get_underlinefillformat/)() override | Renvoie les propriétés de la ligne de soulignement [FillFormat](../fillformat/). Aucun héritage appliqué. Lecture seule [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../baseportionformat/get_underlinelineformat/)() override | Renvoie les propriétés [LineFormat](../lineformat/) utilisées pour le contour de la ligne de soulignement. Aucun héritage appliqué. Lecture seule [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() override | Obtient les données de mise en forme effectives de la portion avec l'héritage appliqué. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Renvoie le code de hachage. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet de cloner des types personnalisés. |
| [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, il se contente d'initialiser le nouvel objet et permet la copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en réalité, il se contente d'initialiser le nouvel objet et permet la copie des sous-classes. |
| [PortionFormat](./portionformat/)() | Initialise une nouvelle instance de la classe [PortionFormat](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence l'objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| void [set_AlternativeLanguageId](../baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | Définit l'Id d'une langue alternative. Écriture [System::String](../../system/string/). |
| void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) override | Définit l'identifiant du signet. Écriture [System::String](../../system/string/). |
| void [set_ComplexScriptFont](../baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Définit les informations de police du script complexe. Null signifie que la police est indéfinie et doit être héritée du Maître. Écriture [IFontData](../ifontdata/). |
| void [set_EastAsianFont](../baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Définit les informations de police Est-Asiatique. Null signifie que la police est indéfinie et doit être héritée du Maître. Écriture [IFontData](../ifontdata/). |
| void [set_Escapement](../baseportionformat/set_escapement/)(**float**) override | Définit le texte en exposant ou indice. Valeur de -100 % (indice) à 100 % (exposant). **std::numeric_limits<float>::quiet_NaN()** signifie que la valeur est indéfinie et doit être héritée du Maître. Écriture **float**. |
| void [set_FontBold](../baseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) override | Détermine si la police est en gras. Aucun héritage appliqué. Écriture [NullableBool](../nullablebool/). |
| void [set_FontHeight](../baseportionformat/set_fontheight/)(**float**) override | Définit la hauteur de police d'une portion. **std::numeric_limits<float>::quiet_NaN()** signifie que la hauteur est indéfinie et doit être héritée du Maître. Écriture **float**. |
| void [set_FontItalic](../baseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) override | Détermine si la police est italique. Aucun héritage appliqué. Écriture [NullableBool](../nullablebool/). |
| void [set_FontUnderline](../baseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | Définit le type de soulignement du texte. Aucun héritage appliqué. Écriture [TextUnderlineType](../textunderlinetype/). |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Définit le lien hypertexte défini pour le clic de souris. Écriture [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Définit le lien hypertexte défini pour le survol de la souris. Écriture [IHyperlink](../ihyperlink/). |
| void [set_IsHardUnderlineFill](../baseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | Détermine si le style de soulignement possède ses propres propriétés [FillFormat](../fillformat/) ou les hérite des propriétés [FillFormat](../fillformat/) du texte. Écriture [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](../baseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | Détermine si le style de soulignement possède ses propres propriétés [LineFormat](../lineformat/) ou les hérite des propriétés [LineFormat](../lineformat/) du texte. Écriture [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](../baseportionformat/set_kerningminimalsize/)(**float**) override | Définit la taille de police minimale, pour laquelle le crénage doit être activé. **std::numeric_limits<float>::quiet_NaN()** signifie que la valeur est indéfinie et doit être héritée du Maître. Écriture **float**. |
| void [set_Kumimoji](../baseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) override | Détermine si les nombres doivent ignorer la mise en page verticale du texte propre aux langues orientales. Aucun héritage appliqué. Écriture [NullableBool](../nullablebool/). |
| void [set_LanguageId](../baseportionformat/set_languageid/)([System::String](../../system/string/)) override | Définit l'Id d'une langue de vérification. Utilisée pour la vérification de l'orthographe et de la grammaire. Écriture [System::String](../../system/string/). |
| void [set_LatinFont](../baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Définit les informations de police Latin. Null signifie que la police est indéfinie et doit être héritée du Maître. Écriture [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](../baseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) override | Détermine si la hauteur du texte doit être normalisée. Aucun héritage appliqué. Écriture [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](../baseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) override | Détermine si le texte ne doit pas être vérifié. Aucun héritage appliqué. Écriture [NullableBool](../nullablebool/). |
| void [set_SmartTagClean](./set_smarttagclean/)(**bool**) override | Détermine si la smart tag doit être nettoyée. Aucun héritage appliqué. Écriture **bool**. |
| void [set_Spacing](../baseportionformat/set_spacing/)(**float**) override | Définit l'incrément d'espacement intercaractères. **std::numeric_limits<float>::quiet_NaN()** signifie que la valeur est indéfinie et doit être héritée du Maître. Écriture **float**. |
| void [set_SpellCheck](../baseportionformat/set_spellcheck/)(**bool**) override | Définit une valeur indiquant si la vérification orthographique est activée pour la portion de texte. Lorsque cette propriété est définie sur false, les vérifications orthographiques des éléments de texte sont supprimées. Lorsqu'elle est définie sur true, la vérification orthographique est autorisée. La valeur par défaut est **false**. |
| void [set_StrikethroughType](../baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | Définit le type de barré d'un texte. Aucun héritage appliqué. Écriture [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](../baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Définit les informations de police symbolique. Null signifie que la police est indéfinie et doit être héritée du Maître. Écriture [IFontData](../ifontdata/). |
| void [set_TextCapType](../baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | Définit le type de capitalisation du texte. Aucun héritage appliqué. Écriture [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de changer les pointeurs dans les conteneurs en mode faible. |
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

Cette classe est utilisée pour renvoyer et manipuler les propriétés de mise en forme de la portion de texte définies pour la portion particulière. Cela signifie qu'aucun héritage n'est appliqué lors de l'obtention des valeurs, de sorte que dans la plupart des cas vous obtiendrez des valeurs signifiant « indéfini ».

Afin d'obtenir les valeurs effectives des paramètres de mise en forme, y compris celles héritées, vous devez utiliser la méthode [PortionFormat::GetEffective](./geteffective/) qui renvoie une instance [IPortionFormatEffectiveData](../iportionformateffectivedata/).

L'exemple suivant montre comment affecter la police Latin à la portion d'un [Paragraph](../paragraph/) de PowerPoint [Presentation](../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f);

System::SharedPtr<Paragraph> paragraph = System::MakeObject<Paragraph>();
System::SharedPtr<Portion> portion = System::MakeObject<Portion>(u"Theme text format");
paragraph->get_Portions()->Add(portion);
shape->get_TextFrame()->get_Paragraphs()->Add(paragraph);
// Aspose.Slides utilise ces identifiants spéciaux (similaires à ceux utilisés dans PowerPoint):
// +mn-lt - Police du corps Latin (Police Latin Mineure)
// +mj-lt - Police du titre Latin (Police Latin Majeure)
// +mn-ea - Police du corps Est-Asiatique (Police Est-Asiatique Mineure)
// +mj-ea - Police du titre Est-Asiatique (Police Est-Asiatique Majeure)
portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"+mn-lt"));
```

## Voir aussi

* Classe [BasePortionFormat](../baseportionformat/)
* Classe [IPortionFormat](../iportionformat/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)