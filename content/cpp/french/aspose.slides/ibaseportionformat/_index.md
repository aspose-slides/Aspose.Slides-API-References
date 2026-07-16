---
title: IBasePortionFormat
second_title: Référence de l'API Aspose.Slides pour C++
description: Cette classe contient les propriétés de formatage de la portion de texte. Contrairement à IPortionFormatEffectiveData, toutes les propriétés de cette classe sont modifiables.
type: docs
weight: 1457
url: /fr/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat classe

Cette classe contient les propriétés de formatage de la portion de texte. Contrairement à [IPortionFormatEffectiveData](../iportionformateffectivedata/), toutes les propriétés de cette classe sont modifiables.

```cpp
class IBasePortionFormat : public virtual System::Object
```

## Méthodes

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n'est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | Renvoie l'Id d'une langue alternative. Lecture [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | Renvoie les informations de police de script complexe. Null signifie que la police n'est pas définie et doit être héritée du maître. Lecture [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | Renvoie les informations de police est-asiatique. Null signifie que la police n'est pas définie et doit être héritée du maître. Lecture [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | Renvoie les propriétés de texte [EffectFormat](../effectformat/). Aucun héritage appliqué. Lecture seule [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](./get_escapement/)() | Renvoie le texte en exposant ou indice. Valeur de -100% (indice) à 100% (exposant). **std::numeric_limits<float>::quiet_NaN()** signifie que la valeur est indéfinie et doit être héritée du maître. Lecture **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | Renvoie les propriétés de texte [FillFormat](../fillformat/). Aucun héritage appliqué. Lecture seule [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() | Détermine si la police est en gras. Aucun héritage appliqué. Lecture [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](./get_fontheight/)() | Renvoie la hauteur de police d'une portion. **std::numeric_limits<float>::quiet_NaN()** signifie que la hauteur est indéfinie et doit être héritée du maître. Lecture **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() | Détermine si la police est italique. Aucun héritage appliqué. Lecture [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | Renvoie le type de soulignement du texte. Aucun héritage appliqué. Lecture [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() | Renvoie la couleur utilisée pour mettre en évidence un texte. Aucun héritage appliqué. Lecture seule [IColorFormat](../icolorformat/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | Détermine si le style de soulignement possède ses propres propriétés [FillFormat](../fillformat/) ou les hérite des propriétés [FillFormat](../fillformat/) du texte. Lecture [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | Détermine si le style de soulignement possède ses propres propriétés [LineFormat](../lineformat/) ou les hérite des propriétés [LineFormat](../lineformat/) du texte. Lecture [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | Renvoie la taille minimale de police pour laquelle le crénage doit être activé. **std::numeric_limits<float>::quiet_NaN()** signifie que la valeur est indéfinie et doit être héritée du maître. Lecture **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() | Détermine si les nombres doivent ignorer la mise en page verticale spécifique aux langues orientales du texte. Aucun héritage appliqué. Lecture [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | Renvoie l'Id d'une langue de relecture. Utilisé pour vérifier l'orthographe et la grammaire. Lecture [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | Renvoie les informations de police latine. Null signifie que la police n'est pas définie et doit être héritée du maître. Lecture [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | Renvoie les propriétés [LineFormat](../lineformat/) pour le contour du texte. Aucun héritage appliqué. Lecture seule [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() | Détermine si la hauteur du texte doit être normalisée. Aucun héritage appliqué. Lecture [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() | Détermine si le texte ne doit pas être relu. Aucun héritage appliqué. Lecture [NullableBool](../nullablebool/). |
| virtual **float** [get_Spacing](./get_spacing/)() | Renvoie l'incrément d'espacement inter-caractères. **std::numeric_limits<float>::quiet_NaN()** signifie que la valeur est indéfinie et doit être héritée du maître. Lecture **float**. |
| virtual **bool** [get_SpellCheck](./get_spellcheck/)() | Obtient une valeur indiquant si la vérification orthographique est activée pour la portion de texte. Lorsque cette propriété est définie sur false, les vérifications orthographiques des éléments de texte sont supprimées. Lorsqu'elle est définie sur true, la vérification orthographique est autorisée. La valeur par défaut est **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | Renvoie le type de barré d'un texte. Aucun héritage appliqué. Lecture [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | Renvoie les informations de police symbolique. Null signifie que la police n'est pas définie et doit être héritée du maître. Lecture [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | Renvoie le type de capitalisation du texte. Aucun héritage appliqué. Lecture [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | Renvoie les propriétés de la ligne de soulignement [FillFormat](../fillformat/). Aucun héritage appliqué. Lecture seule [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | Renvoie les propriétés [LineFormat](../lineformat/) utilisées pour le contour de la ligne de soulignement. Aucun héritage appliqué. Lecture seule [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, en fait, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre spécifié. |
| virtual void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) | Définit l'Id d'une langue alternative. Écriture [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Définit les informations de police de script complexe. Null signifie que la police n'est pas définie et doit être héritée du maître. Écriture [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Définit les informations de police est-asiatique. Null signifie que la police n'est pas définie et doit être héritée du maître. Écriture [IFontData](../ifontdata/). |
| virtual void [set_Escapement](./set_escapement/)(**float**) | Définit le texte en exposant ou indice. Valeur de -100% (indice) à 100% (exposant). **std::numeric_limits<float>::quiet_NaN()** signifie que la valeur est indéfinie et doit être héritée du maître. Écriture **float**. |
| virtual void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) | Détermine si la police est en gras. Aucun héritage appliqué. Écriture [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](./set_fontheight/)(**float**) | Définit la hauteur de police d'une portion. **std::numeric_limits<float>::quiet_NaN()** signifie que la hauteur est indéfinie et doit être héritée du maître. Écriture **float**. |
| virtual void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) | Détermine si la police est italique. Aucun héritage appliqué. Écriture [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | Définit le type de soulignement du texte. Aucun héritage appliqué. Écriture [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | Détermine si le style de soulignement possède ses propres propriétés [FillFormat](../fillformat/) ou les hérite des propriétés [FillFormat](../fillformat/) du texte. Écriture [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) | Détermine si le style de soulignement possède ses propres propriétés [LineFormat](../lineformat/) ou les hérite des propriétés [LineFormat](../lineformat/) du texte. Écriture [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) | Définit la taille minimale de police pour laquelle le crénage doit être activé. **std::numeric_limits<float>::quiet_NaN()** signifie que la valeur est indéfinie et doit être héritée du maître. Écriture **float**. |
| virtual void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) | Détermine si les nombres doivent ignorer la mise en page verticale spécifique aux langues orientales du texte. Aucun héritage appliqué. Écriture [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) | Définit l'Id d'une langue de relecture. Utilisé pour vérifier l'orthographe et la grammaire. Écriture [System::String](../../system/string/). |
| virtual void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Définit les informations de police latine. Null signifie que la police n'est pas définie et doit être héritée du maître. Écriture [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) | Détermine si la hauteur du texte doit être normalisée. Aucun héritage appliqué. Écriture [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) | Détermine si le texte ne doit pas être relu. Aucun héritage appliqué. Écriture [NullableBool](../nullablebool/). |
| virtual void [set_Spacing](./set_spacing/)(**float**) | Définit l'incrément d'espacement inter-caractères. **std::numeric_limits<float>::quiet_NaN()** signifie que la valeur est indéfinie et doit être héritée du maître. Écriture **float**. |
| virtual void [set_SpellCheck](./set_spellcheck/)(**bool**) | Définit une valeur indiquant si la vérification orthographique est activée pour la portion de texte. Lorsque cette propriété est définie sur false, les vérifications orthographiques des éléments de texte sont supprimées. Lorsqu'elle est définie sur true, la vérification orthographique est autorisée. La valeur par défaut est **false**. |
| virtual void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | Définit le type de barré d'un texte. Aucun héritage appliqué. Écriture [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Définit les informations de police symbolique. Null signifie que la police n'est pas définie et doit être héritée du maître. Écriture [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | Définit le type de capitalisation du texte. Aucun héritage appliqué. Écriture [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ème argument de modèle comme pointeur faible (plutôt que partagé). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet la conversion d'objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Remarques

Cette classe est utilisée pour renvoyer et manipuler les propriétés de formatage de portion de texte définies pour la portion particulière. Cela signifie qu'aucun héritage n'est appliqué lors de l'obtention des valeurs, ainsi dans la majorité des cas vous obtiendrez des valeurs signifiant « indéfini ».

Afin d'obtenir les valeurs effectives des paramètres de formatage, y compris celles héritées, vous devez utiliser la méthode [IPortionFormat::GetEffective](../iportionformat/geteffective/) qui renvoie une instance [IPortionFormatEffectiveData](../iportionformateffectivedata/).

## Voir aussi

* Classe [Object](../../system/object/)
* Espace de noms [Aspose::Slides](../)
* Bibliothèque [Aspose.Slides](../../)