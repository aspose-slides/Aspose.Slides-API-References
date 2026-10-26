---
title: PortionFormat
second_title: Aspose.Slides pro C++ API Reference
description: Tato třída obsahuje vlastnosti formátování textových úseků. Na rozdíl od IPortionFormatEffectiveData jsou všechny vlastnosti této třídy zapisovatelné.
type: docs
weight: 4811
url: /cs/aspose.slides/portionformat/
---
## PortionFormat třída


Tato třída obsahuje vlastnosti formátování textových úseků. Na rozdíl od [IPortionFormatEffectiveData](../iportionformateffectivedata/) jsou všechny vlastnosti této třídy zapisovatelné.

```cpp
class PortionFormat : public Aspose::Slides::BasePortionFormat,
                      public Aspose::Slides::IPortionFormat
```

## Metody

| Metoda | Popis |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Porovná s určeným objektem. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovná objekty pomocí C# [Object.Equals](../../system/object/equals/) sémantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty typu reference ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí řádovou čárkou ve stylu C#, kde jsou dva NaN považovány za rovny, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí řádovou čárkou ve stylu C#, kde jsou dva NaN považovány za rovny, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../baseportionformat/get_alternativelanguageid/)() override | Vrací Id alternativního jazyka. Přečtěte si [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() override | Vrací identifikátor záložky. Přečtěte si [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../baseportionformat/get_complexscriptfont/)() override | Vrací informace o písmu složitého skriptu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Přečtěte si [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../baseportionformat/get_eastasianfont/)() override | Vrací informace o východoasijském písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Přečtěte si [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../baseportionformat/get_effectformat/)() override | Vrací vlastnosti textu [EffectFormat](../effectformat/). Není použita dědičnost. Pouze pro čtení [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](../baseportionformat/get_escapement/)() override | Vrací horní nebo dolní index textu. Hodnota od -100 % (dolní index) do 100 % (horní index). **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čte **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../baseportionformat/get_fillformat/)() override | Vrací vlastnosti textu [FillFormat](../fillformat/). Není použita dědičnost. Pouze pro čtení [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](../baseportionformat/get_fontbold/)() override | Určuje, zda je písmo tučné. Není použita dědičnost. Přečtěte si [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](../baseportionformat/get_fontheight/)() override | Vrací výšku písma úseku. **std::numeric_limits<float>::quiet_NaN()** znamená, že výška není definována a měla by být zděděna z Masteru. Čte **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](../baseportionformat/get_fontitalic/)() override | Určuje, zda je písmo kurzíva. Není použita dědičnost. Přečtěte si [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../baseportionformat/get_fontunderline/)() override | Vrací typ podtržení textu. Není použita dědičnost. Přečtěte si [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../baseportionformat/get_highlightcolor/)() override | Vrací barvu použitou k zvýraznění textu. Není použita dědičnost. Pouze pro čtení [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | Vrací hypertextový odkaz definovaný pro kliknutím myši. Přečtěte si [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | Správce hypertextových odkazů. Pouze pro čtení [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | Vrací hypertextový odkaz definovaný pro přejetí myší. Přečtěte si [IHyperlink](../ihyperlink/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../baseportionformat/get_ishardunderlinefill/)() override | Určuje, zda má styl podtržení vlastní vlastnosti [FillFormat](../fillformat/) nebo je zděděn z vlastností [FillFormat](../fillformat/) textu. Přečtěte si [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../baseportionformat/get_ishardunderlineline/)() override | Určuje, zda má styl podtržení vlastní vlastnosti [LineFormat](../lineformat/) nebo je zděděn z vlastností [LineFormat](../lineformat/) textu. Přečtěte si [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](../baseportionformat/get_kerningminimalsize/)() override | Vrací minimální velikost písma, při které má být zapnutý kerning. **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čte **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](../baseportionformat/get_kumimoji/)() override | Určuje, zda čísla mají ignorovat specifické vertikální rozvržení textu pro východoasijské jazyky. Není použita dědičnost. Přečtěte si [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](../baseportionformat/get_languageid/)() override | Vrací Id jazyka pro jazykovou kontrolu. Používá se pro kontrolu pravopisu a gramatiky. Přečtěte si [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../baseportionformat/get_latinfont/)() override | Vrací informace o latinském písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Přečtěte si [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../baseportionformat/get_lineformat/)() override | Vrací vlastnosti [LineFormat](../lineformat/) pro obrysování textu. Není použita dědičnost. Pouze pro čtení [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](../baseportionformat/get_normaliseheight/)() override | Určuje, zda má být výška textu normalizována. Není použita dědičnost. Přečtěte si [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Vrací objekt Parent_Immediate. Pouze pro čtení [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Vrací nadřazený [IPresentationComponent](../ipresentationcomponent/). Pouze pro čtení [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](../baseportionformat/get_proofdisabled/)() override | Určuje, zda text nemá být kontrolován. Není použita dědičnost. Přečtěte si [NullableBool](../nullablebool/). |
| **bool** [get_SmartTagClean](./get_smarttagclean/)() override | Určuje, zda by měl být inteligentní štítek vyčištěn. Není použita dědičnost. Čte **bool**. |
| **float** [get_Spacing](../baseportionformat/get_spacing/)() override | Vrací přírůstek mezery mezi znaky. **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čte **float**. |
| **bool** [get_SpellCheck](../baseportionformat/get_spellcheck/)() override | Získá hodnotu udávající, zda je pro úsek textu povolena kontrola pravopisu. Když je tato vlastnost nastavena na **false**, kontroly pravopisu pro textové prvky jsou potlačeny. Když je nastavena na **true**, kontrola pravopisu je povolena. Výchozí hodnota je **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../baseportionformat/get_strikethroughtype/)() override | Vrací typ přeškrtnutí textu. Není použita dědičnost. Přečtěte si [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../baseportionformat/get_symbolfont/)() override | Vrací informace o symbolickém písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Přečtěte si [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../baseportionformat/get_textcaptype/)() override | Vrací typ kapitalizace textu. Není použita dědičnost. Přečtěte si [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../baseportionformat/get_underlinefillformat/)() override | Vrací vlastnosti podtržové čáry [FillFormat](../fillformat/). Není použita dědičnost. Pouze pro čtení [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../baseportionformat/get_underlinelineformat/)() override | Vrací vlastnosti [LineFormat](../lineformat/) použité k obrysování podtržové čáry. Není použita dědičnost. Pouze pro čtení [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu čítače referencí spojenou s objektem. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() override | Získá data efektivního formátování úseku s aplikovanou dědičností. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Vrací hash kód. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání příkazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metodě C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
|  [PortionFormat](./portionformat/)() | Inicializuje novou instanci třídy [PortionFormat](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovná objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovná objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu value s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Speciální implementace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Speciální implementace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o určenou hodnotu. |
| void [set_AlternativeLanguageId](../baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | Nastaví Id alternativního jazyka. Zapíše [System::String](../../system/string/). |
| void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) override | Nastaví identifikátor záložky. Zapíše [System::String](../../system/string/). |
| void [set_ComplexScriptFont](../baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Nastaví informace o písmu složitého skriptu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Zapíše [IFontData](../ifontdata/). |
| void [set_EastAsianFont](../baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Nastaví informace o východoasijském písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Zapíše [IFontData](../ifontdata/). |
| void [set_Escapement](../baseportionformat/set_escapement/)(**float**) override | Nastaví text jako horní nebo dolní index. Hodnota od -100 % (dolní index) do 100 % (horní index). **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota není definována a měla by být zděděna z Masteru. Zapíše **float**. |
| void [set_FontBold](../baseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) override | Určuje, zda je písmo tučné. Není použita dědičnost. Zapíše [NullableBool](../nullablebool/). |
| void [set_FontHeight](../baseportionformat/set_fontheight/)(**float**) override | Nastaví výšku písma úseku. **std::numeric_limits<float>::quiet_NaN()** znamená, že výška není definována a měla by být zděděna z Masteru. Zapíše **float**. |
| void [set_FontItalic](../baseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) override | Určuje, zda je písmo kurzíva. Není použita dědičnost. Zapíše [NullableBool](../nullablebool/). |
| void [set_FontUnderline](../baseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | Nastaví typ podtržení textu. Není použita dědičnost. Zapíše [TextUnderlineType](../textunderlinetype/). |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Nastaví hypertextový odkaz definovaný pro kliknutím myši. Zapíše [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Nastaví hypertextový odkaz definovaný pro přejetí myší. Zapíše [IHyperlink](../ihyperlink/). |
| void [set_IsHardUnderlineFill](../baseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | Určuje, zda styl podtržení má vlastní vlastnosti [FillFormat](../fillformat/) nebo je zdědí z vlastností [FillFormat](../fillformat/) textu. Zapíše [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](../baseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | Určuje, zda styl podtržení má vlastní vlastnosti [LineFormat](../lineformat/) nebo je zdědí z vlastností [LineFormat](../lineformat/) textu. Zapíše [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](../baseportionformat/set_kerningminimalsize/)(**float**) override | Nastaví minimální velikost písma, při které má být zapnutý kerning. **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota není definována a měla by být zděděna z Masteru. Zapíše **float**. |
| void [set_Kumimoji](../baseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) override | Určuje, zda čísla mají ignorovat specifické vertikální rozvržení textu pro východoasijské jazyky. Není použita dědičnost. Zapíše [NullableBool](../nullablebool/). |
| void [set_LanguageId](../baseportionformat/set_languageid/)([System::String](../../system/string/)) override | Nastaví Id jazyka pro jazykovou kontrolu. Používá se pro kontrolu pravopisu a gramatiky. Zapíše [System::String](../../system/string/). |
| void [set_LatinFont](../baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Nastaví informace o latinském písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Zapíše [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](../baseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) override | Určuje, zda má být výška textu normalizována. Není použita dědičnost. Zapíše [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](../baseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) override | Určuje, zda text nemá být kontrolován. Není použita dědičnost. Zapíše [NullableBool](../nullablebool/). |
| void [set_SmartTagClean](./set_smarttagclean/)(**bool**) override | Určuje, zda by měl být inteligentní štítek vyčištěn. Není použita dědičnost. Zapíše **bool**. |
| void [set_Spacing](../baseportionformat/set_spacing/)(**float**) override | Nastaví přírůstek mezery mezi znaky. **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota není definována a měla by být zděděna z Masteru. Zapíše **float**. |
| void [set_SpellCheck](../baseportionformat/set_spellcheck/)(**bool**) override | Nastaví hodnotu udávající, zda je pro úsek textu povolena kontrola pravopisu. Když je tato vlastnost nastavena na **false**, kontroly pravopisu pro textové prvky jsou potlačeny. Když je nastavena na **true**, kontrola pravopisu je povolena. Výchozí hodnota je **false**. |
| void [set_StrikethroughType](../baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | Nastaví typ přeškrtnutí textu. Není použita dědičnost. Zapíše [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](../baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Nastaví informace o symbolickém písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Zapíše [IFontData](../ifontdata/). |
| void [set_TextCapType](../baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | Nastaví typ kapitalizace textu. Není použita dědičnost. Zapíše [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí příkazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Poznámky


Tato třída se používá k vracení a manipulaci s vlastnostmi formátování textových úseků definovanými pro konkrétní úsek. To znamená, že při získávání hodnot se nepoužije dědičnost, takže ve většině případů získáte hodnoty znamenající „nedefinováno“.

Pro získání efektivních hodnot parametrů formátování včetně zděděných je potřeba použít metodu [PortionFormat::GetEffective](./geteffective/), která vrací instanci [IPortionFormatEffectiveData](../iportionformateffectivedata/).

Následující příklady ukazují, jak přiřadit latinské písmo úseku [Paragraph](../paragraph/) v PowerPointu [Presentation](../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f);

System::SharedPtr<Paragraph> paragraph = System::MakeObject<Paragraph>();
System::SharedPtr<Portion> portion = System::MakeObject<Portion>(u"Theme text format");
paragraph->get_Portions()->Add(portion);
shape->get_TextFrame()->get_Paragraphs()->Add(paragraph);
// Aspose.Slides používá tyto speciální identifikátory (podobně jako v PowerPointu):
// +mn-lt - Tělové písmo Latin (Menší latinské písmo)
// +mj-lt - Nadpisové písmo Latin (Větší latinské písmo)
// +mn-ea - Tělové písmo East Asian (Menší východoasijské písmo)
// +mj-ea - Tělové písmo East Asian (Menší východoasijské písmo)
portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"+mn-lt"));
```

## Viz také

* Třída [BasePortionFormat](../baseportionformat/)
* Třída [IPortionFormat](../iportionformat/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)