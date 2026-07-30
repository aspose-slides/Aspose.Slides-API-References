---
title: IPortionFormat
second_title: Aspose.Slides pro C++ – reference API
description: Tato třída obsahuje vlastnosti formátování textových úseků. Na rozdíl od IPortionFormatEffectiveData jsou všechny vlastnosti této třídy zapisovatelné.
type: docs
weight: 3329
url: /cs/aspose.slides/iportionformat/
---
## IPortionFormat třída


Tato třída obsahuje vlastnosti formátování textového úseku. Na rozdíl od [IPortionFormatEffectiveData](../iportionformateffectivedata/) jsou všechny vlastnosti této třídy zapisovatelné.

```cpp
class IPortionFormat : public virtual Aspose::Slides::IBasePortionFormat,
                       public Aspose::Slides::IHyperlinkContainer
```

## Metody

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) sémantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../ibaseportionformat/get_alternativelanguageid/)() | Vrací Id alternativního jazyka. Čtěte [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() | Vrací identifikátor záložky. Čtěte [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../ibaseportionformat/get_complexscriptfont/)() | Vrací informace o fontu složitého skriptu. Null znamená, že font není definován a měl by být zděděn z Masteru. Čtěte [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../ibaseportionformat/get_eastasianfont/)() | Vrací informace o fontu východní Asie. Null znamená, že font není definován a měl by být zděděn z Masteru. Čtěte [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ibaseportionformat/get_effectformat/)() | Vrací vlastnosti textu [EffectFormat](../effectformat/). Dědičnost se neuplatňuje. Pouze pro čtení [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](../ibaseportionformat/get_escapement/)() | Vrací text ve formě horního nebo dolního indexu. Hodnota od -100 % (dolní index) do 100 % (horní index). **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota není definována a měla by být zděděna z Masteru. Číst **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ibaseportionformat/get_fillformat/)() | Vrací vlastnosti textu [FillFormat](../fillformat/). Dědičnost se neuplatňuje. Pouze pro čtení [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](../ibaseportionformat/get_fontbold/)() | Určuje, zda je font tučný. Dědičnost se neuplatňuje. Číst [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](../ibaseportionformat/get_fontheight/)() | Vrací výšku fontu úseku. **std::numeric_limits<float>::quiet_NaN()** znamená, že výška není definována a měla by být zděděna z Masteru. Číst **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](../ibaseportionformat/get_fontitalic/)() | Určuje, zda je font kurzívou. Dědičnost se neuplatňuje. Číst [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../ibaseportionformat/get_fontunderline/)() | Vrací typ podtržení textu. Dědičnost se neuplatňuje. Číst [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../ibaseportionformat/get_highlightcolor/)() | Vrací barvu použitou pro zvýraznění textu. Dědičnost se neuplatňuje. Pouze pro čtení [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Vrací hyperodkaz definovaný pro kliknutí myší. Číst [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Správce hyperodkazů Pouze pro čtení [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Vrací hyperodkaz definovaný pro přejetí myší. Číst [IHyperlink](../ihyperlink/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../ibaseportionformat/get_ishardunderlinefill/)() | Určuje, zda má styl podtržení vlastní vlastnosti [FillFormat](../fillformat/) nebo je dědí z vlastností [FillFormat](../fillformat/) textu. Číst [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../ibaseportionformat/get_ishardunderlineline/)() | Určuje, zda má styl podtržení vlastní vlastnosti [LineFormat](../lineformat/) nebo je dědí z vlastností [LineFormat](../lineformat/) textu. Číst [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](../ibaseportionformat/get_kerningminimalsize/)() | Vrací minimální velikost fontu, při které by měl být zapnut kerning. **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota není definována a měla by být zděděna z Masteru. Číst **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](../ibaseportionformat/get_kumimoji/)() | Určuje, zda čísla mají ignorovat specifické vertikální rozložení textu pro východní jazyky. Dědičnost se neuplatňuje. Číst [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](../ibaseportionformat/get_languageid/)() | Vrací Id jazykové kontroly. Používá se pro kontrolu pravopisu a gramatiky. Číst [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../ibaseportionformat/get_latinfont/)() | Vrací informace o latinském fontu. Null znamená, že font není definován a měl by být zděděn z Masteru. Číst [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ibaseportionformat/get_lineformat/)() | Vrací vlastnosti [LineFormat](../lineformat/) pro obrysování textu. Dědičnost se neuplatňuje. Pouze pro čtení [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](../ibaseportionformat/get_normaliseheight/)() | Určuje, zda by výška textu měla být normalizována. Dědičnost se neuplatňuje. Číst [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](../ibaseportionformat/get_proofdisabled/)() | Určuje, zda by text neměl být kontrolován. Dědičnost se neuplatňuje. Číst [NullableBool](../nullablebool/). |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | Určuje, zda by měl být chytrý štítek vyčištěn. Dědičnost se neuplatňuje. Číst **bool**. |
| virtual **float** [get_Spacing](../ibaseportionformat/get_spacing/)() | Vrací přírůstek mezery mezi znaky. **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota není definována a měla by být zděděna z Masteru. Číst **float**. |
| virtual **bool** [get_SpellCheck](../ibaseportionformat/get_spellcheck/)() | Získává hodnotu udávající, zda je pro úsek textu povolena kontrola pravopisu. Když je tato vlastnost nastavena na false, kontrola pravopisu pro textové prvky je potlačena. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../ibaseportionformat/get_strikethroughtype/)() | Vrací typ přeškrtnutí textu. Dědičnost se neuplatňuje. Číst [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../ibaseportionformat/get_symbolfont/)() | Vrací informace o symbolickém fontu. Null znamená, že font není definován a měl by být zděděn z Masteru. Číst [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../ibaseportionformat/get_textcaptype/)() | Vrací typ kapitalizace textu. Dědičnost se neuplatňuje. Číst [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../ibaseportionformat/get_underlinefillformat/)() | Vrací vlastnosti podtržny řádky [FillFormat](../fillformat/). Dědičnost se neuplatňuje. Pouze pro čtení [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../ibaseportionformat/get_underlinelineformat/)() | Vrací vlastnosti [LineFormat](../lineformat/) použité k obrysování podtržného řádku. Dědičnost se neuplatňuje. Pouze pro čtení [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu počítadla referencí spojenou s objektem. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() | Získává efektivní data formátování úseku s aplikovanou dědičností. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Vlastně nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Vlastně nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenčně objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| virtual void [set_AlternativeLanguageId](../ibaseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) | Nastavuje Id alternativního jazyka. Zapisujte [System::String](../../system/string/). |
| virtual void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) | Nastavuje identifikátor záložky. Zapisujte [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](../ibaseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Nastavuje informace o fontu složitého skriptu. Null znamená, že font není definován a měl by být zděděn z Masteru. Zapisujte [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](../ibaseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Nastavuje informace o fontu východní Asie. Null znamená, že font není definován a měl by být zděděn z Masteru. Zapisujte [IFontData](../ifontdata/). |
| virtual void [set_Escapement](../ibaseportionformat/set_escapement/)(**float**) | Nastavuje text ve formě horního nebo dolního indexu. Hodnota od -100 % (dolní index) do 100 % (horní index). **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota není definována a měla by být zděděna z Masteru. Zapisujte **float**. |
| virtual void [set_FontBold](../ibaseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) | Určuje, zda je font tučný. Dědičnost se neuplatňuje. Zapisujte [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](../ibaseportionformat/set_fontheight/)(**float**) | Nastavuje výšku fontu úseku. **std::numeric_limits<float>::quiet_NaN()** znamená, že výška není definována a měla by být zděděna z Masteru. Zapisujte **float**. |
| virtual void [set_FontItalic](../ibaseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) | Určuje, zda je font kurzívou. Dědičnost se neuplatňuje. Zapisujte [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](../ibaseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | Nastavuje typ podtržení textu. Dědičnost se neuplatňuje. Zapisujte [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Nastavuje hyperodkaz definovaný pro kliknutí myší. Zapisujte [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Nastavuje hyperodkaz definovaný pro přejetí myší. Zapisujte [IHyperlink](../ihyperlink/). |
| virtual void [set_IsHardUnderlineFill](../ibaseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | Určuje, zda má styl podtržení vlastní vlastnosti [FillFormat](../fillformat/) nebo je dědí z vlastností [FillFormat](../fillformat/) textu. Zapisujte [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](../ibaseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) | Určuje, zda má styl podtržení vlastní vlastnosti [LineFormat](../lineformat/) nebo je dědí z vlastností [LineFormat](../lineformat/) textu. Zapisujte [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](../ibaseportionformat/set_kerningminimalsize/)(**float**) | Nastavuje minimální velikost fontu, při které by měl být zapnut kerning. **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota není definována a měla by být zděděna z Masteru. Zapisujte **float**. |
| virtual void [set_Kumimoji](../ibaseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) | Určuje, zda čísla mají ignorovat specifické vertikální rozložení textu pro východní jazyky. Dědičnost se neuplatňuje. Zapisujte [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](../ibaseportionformat/set_languageid/)([System::String](../../system/string/)) | Nastavuje Id jazyka kontroly pravopisu. Používá se pro kontrolu pravopisu a gramatiky. Zapisujte [System::String](../../system/string/). |
| virtual void [set_LatinFont](../ibaseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Nastavuje informace o latinském fontu. Null znamená, že font není definován a měl by být zděděn z Masteru. Zapisujte [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](../ibaseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) | Určuje, zda by výška textu měla být normalizována. Dědičnost se neuplatňuje. Zapisujte [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](../ibaseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) | Určuje, zda by text neměl být kontrolován. Dědičnost se neuplatňuje. Zapisujte [NullableBool](../nullablebool/). |
| virtual void [set_SmartTagClean](./set_smarttagclean/)(**bool**) | Určuje, zda by měl být chytrý štítek vyčištěn. Dědičnost se neuplatňuje. Zapisujte **bool**. |
| virtual void [set_Spacing](../ibaseportionformat/set_spacing/)(**float**) | Nastavuje přírůstek mezery mezi znaky. **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota není definována a měla by být zděděna z Masteru. Zapisujte **float**. |
| virtual void [set_SpellCheck](../ibaseportionformat/set_spellcheck/)(**bool**) | Nastavuje hodnotu udávající, zda je pro úsek textu povolena kontrola pravopisu. Když je tato vlastnost nastavena na false, kontrola pravopisu pro textové prvky je potlačena. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je **false**. |
| virtual void [set_StrikethroughType](../ibaseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | Nastavuje typ přeškrtnutí textu. Dědičnost se neuplatňuje. Zapisujte [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](../ibaseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Nastavuje informace o symbolickém fontu. Null znamená, že font není definován a měl by být zděděn z Masteru. Zapisujte [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](../ibaseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | Nastavuje typ kapitalizace textu. Dědičnost se neuplatňuje. Zapisujte [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepnout ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převádět vlastní objekty na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolňuje všechny interní datové struktury. |

## Poznámky

Tato třída se používá k vrácení a manipulaci s vlastnostmi formátování textového úseku definovanými pro konkrétní úsek. To znamená, že při získávání hodnot se nedědí, takže ve většině případů získáte hodnoty označující „nedefinováno“.

Pro získání efektivních hodnot parametrů formátování včetně děděných je nutné použít metodu [IPortionFormat::GetEffective](./geteffective/), která vrací instanci [IPortionFormatEffectiveData](../iportionformateffectivedata/).

## Viz také

* Třída [IBasePortionFormat](../ibaseportionformat/)
* Třída [IHyperlinkContainer](../ihyperlinkcontainer/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)