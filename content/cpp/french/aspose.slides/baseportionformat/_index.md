---
title: BasePortionFormat
second_title: Référence de l'API Aspose.Slides pour C++
description: Propriétés de mise en forme communes des portions de texte.
type: docs
weight: 144
url: /fr/aspose.slides/baseportionformat/
---
## BasePortionFormat classe


Common text portion formatting properties.

```cpp
class BasePortionFormat : public Aspose::Slides::PVIObject,
                          public virtual Aspose::Slides::IBasePortionFormat
```

## Méthodes

| Method | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Compare avec l'objet spécifié. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison à virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() override | Renvoie l'Id d'une langue alternative. Lire [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() override | Renvoie les informations de police du script complexe. Null signifie que la police est indéfinie et doit être héritée du Master. Lire [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() override | Renvoie les informations de police d'Asie orientale. Null signifie que la police est indéfinie et doit être héritée du Master. Lire [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | Renvoie les propriétés du texte [EffectFormat](../effectformat/). Aucun héritage appliqué. Lecture seule [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](./get_escapement/)() override | Renvoie le texte en exposant ou indice. Valeur de -100 % (indice) à 100 % (exposant). **std::numeric_limits<float>::quiet_NaN()** signifie que la valeur est indéfinie et doit être héritée du Master. Lecture **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | Renvoie les propriétés du texte [FillFormat](../fillformat/). Aucun héritage appliqué. Lecture seule [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() override | Détermine si la police est en gras. Aucun héritage appliqué. Lire [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](./get_fontheight/)() override | Renvoie la hauteur de police d'une portion. **std::numeric_limits<float>::quiet_NaN()** signifie que la hauteur est indéfinie et doit être héritée du Master. Lecture **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() override | Détermine si la police est italique. Aucun héritage appliqué. Lire [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() override | Renvoie le type de soulignement du texte. Aucun héritage appliqué. Lire [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() override | Renvoie la couleur utilisée pour mettre en surbrillance un texte. Aucun héritage appliqué. Lecture seule [IColorFormat](../icolorformat/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() override | Détermine si le style de soulignement possède ses propres propriétés [FillFormat](../fillformat/) ou les hérite des propriétés [FillFormat](../fillformat/) du texte. Lire [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() override | Détermine si le style de soulignement possède ses propres propriétés [LineFormat](../lineformat/) ou les hérite des propriétés [LineFormat](../lineformat/) du texte. Lire [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() override | Renvoie la taille de police minimale pour laquelle le crénage doit être activé. **std::numeric_limits<float>::quiet_NaN()** signifie que la valeur est indéfinie et doit être héritée du Master. Lecture **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() override | Détermine si les nombres doivent ignorer la disposition verticale du texte propre aux langues orientales. Aucun héritage appliqué. Lire [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() override | Renvoie l'Id d'une langue de relecture. Utilisée pour la vérification orthographique et grammaticale. Lire [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() override | Renvoie les informations de police latine. Null signifie que la police est indéfinie et doit être héritée du Master. Lire [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | Renvoie les propriétés [LineFormat](../lineformat/) pour le contour du texte. Aucun héritage appliqué. Lecture seule [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() override | Détermine si la hauteur d'un texte doit être normalisée. Aucun héritage appliqué. Lire [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Renvoie l'objet Parent_Immediate. Lecture seule [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Renvoie le parent [IPresentationComponent](../ipresentationcomponent/). Lecture seule [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() override | Détermine si le texte ne doit pas être relu. Aucun héritage appliqué. Lire [NullableBool](../nullablebool/). |
| **float** [get_Spacing](./get_spacing/)() override | Renvoie l'incrément d'espacement inter-caractères. **std::numeric_limits<float>::quiet_NaN()** signifie que la valeur est indéfinie et doit être héritée du Master. Lecture **float**. |
| **bool** [get_SpellCheck](./get_spellcheck/)() override | Obtient une valeur indiquant si la vérification orthographique est activée pour la portion de texte. Lorsque cette propriété est définie sur false, les vérifications orthographiques des éléments de texte sont supprimées. Lorsqu'elle est définie sur true, la vérification orthographique est autorisée. La valeur par défaut est **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() override | Renvoie le type de barré d'un texte. Aucun héritage appliqué. Lire [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() override | Renvoie les informations de police symbolique. Null signifie que la police est indéfinie et doit être héritée du Master. Lire [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() override | Renvoie le type de capitalisation du texte. Aucun héritage appliqué. Lire [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() override | Renvoie les propriétés de la ligne de soulignement [FillFormat](../fillformat/). Aucun héritage appliqué. Lecture seule [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() override | Renvoie les propriétés [LineFormat](../lineformat/) utilisées pour le contour de la ligne de soulignement. Aucun héritage appliqué. Lecture seule [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Renvoie le code de hachage. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet de cloner des types personnalisés. |
| [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie en fait rien, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie en fait rien, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) override | Définit l'Id d'une langue alternative. Écrire [System::String](../../system/string/). |
| void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Définit les informations de police du script complexe. Null signifie que la police est indéfinie et doit être héritée du Master. Écrire [IFontData](../ifontdata/). |
| void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Définit les informations de police d'Asie orientale. Null signifie que la police est indéfinie et doit être héritée du Master. Écrire [IFontData](../ifontdata/). |
| void [set_Escapement](./set_escapement/)(**float**) override | Définit le texte en exposant ou indice. Valeur de -100 % (indice) à 100 % (exposant). **std::numeric_limits<float>::quiet_NaN()** signifie que la valeur est indéfinie et doit être héritée du Master. Écrire **float**. |
| void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) override | Détermine si la police est en gras. Aucun héritage appliqué. Écrire [NullableBool](../nullablebool/). |
| void [set_FontHeight](./set_fontheight/)(**float**) override | Définit la hauteur de police d'une portion. **std::numeric_limits<float>::quiet_NaN()** signifie que la hauteur est indéfinie et doit être héritée du Master. Écrire **float**. |
| void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) override | Détermine si la police est italique. Aucun héritage appliqué. Écrire [NullableBool](../nullablebool/). |
| void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | Définit le type de soulignement du texte. Aucun héritage appliqué. Écrire [TextUnderlineType](../textunderlinetype/). |
| void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | Détermine si le style de soulignement possède ses propres propriétés [FillFormat](../fillformat/) ou les hérite des propriétés [FillFormat](../fillformat/) du texte. Écrire [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | Détermine si le style de soulignement possède ses propres propriétés [LineFormat](../lineformat/) ou les hérite des propriétés [LineFormat](../lineformat/) du texte. Écrire [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) override | Définit la taille de police minimale pour laquelle le crénage doit être activé. **std::numeric_limits<float>::quiet_NaN()** signifie que la valeur est indéfinie et doit être héritée du Master. Écrire **float**. |
| void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) override | Détermine si les nombres doivent ignorer la disposition verticale du texte propre aux langues orientales. Aucun héritage appliqué. Écrire [NullableBool](../nullablebool/). |
| void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) override | Définit l'Id d'une langue de relecture. Utilisée pour la vérification orthographique et grammaticale. Écrire [System::String](../../system/string/). |
| void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Définit les informations de police latine. Null signifie que la police est indéfinie et doit être héritée du Master. Écrire [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) override | Détermine si la hauteur d'un texte doit être normalisée. Aucun héritage appliqué. Écrire [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) override | Détermine si le texte ne doit pas être relu. Aucun héritage appliqué. Écrire [NullableBool](../nullablebool/). |
| void [set_Spacing](./set_spacing/)(**float**) override | Définit l'incrément d'espacement inter-caractères. **std::numeric_limits<float>::quiet_NaN()** signifie que la valeur est indéfinie et doit être héritée du Master. Écrire **float**. |
| void [set_SpellCheck](./set_spellcheck/)(**bool**) override | Définit une valeur indiquant si la vérification orthographique est activée pour la portion de texte. Lorsque cette propriété est définie sur false, les vérifications orthographiques des éléments de texte sont supprimées. Lorsqu'elle est définie sur true, la vérification orthographique est autorisée. La valeur par défaut est **false**. |
| void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | Définit le type de barré d'un texte. Aucun héritage appliqué. Écrire [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Définit les informations de police symbolique. Null signifie que la police est indéfinie et doit être héritée du Master. Écrire [IFontData](../ifontdata/). |
| void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | Définit le type de capitalisation du texte. Aucun héritage appliqué. Écrire [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le nᵉ argument de modèle comme pointeur faible (plutôt que partagé). Permet de changer les pointeurs dans les conteneurs en mode faible. |
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

## Voir aussi

* Classe [PVIObject](../pviobject/)
* Classe [IBasePortionFormat](../ibaseportionformat/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)