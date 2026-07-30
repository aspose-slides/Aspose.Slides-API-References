---
title: BasePortionFormat
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Obecné vlastnosti formátování textových částí.
type: docs
weight: 144
url: /cs/aspose.slides/baseportionformat/
---
## BasePortionFormat třída

Common text portion formatting properties.

```cpp
class BasePortionFormat : public Aspose::Slides::PVIObject,
                          public virtual Aspose::Slides::IBasePortionFormat
```

## Metody

| Metoda | Popis |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Porovnává se zadaným objektem. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) sémantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() override | Vrací Id alternativního jazyka. Přečtěte [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() override | Vrací informace o fontu složitého skriptu. Null znamená, že font není definován a měl by být zděděn z Masteru. Přečtěte [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() override | Vrací informace o fontu východoasijského písma. Null znamená, že font není definován a měl by být zděděn z Masteru. Přečtěte [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | Vrací vlastnosti textu [EffectFormat](../effectformat/). Nedědí se. Pouze ke čtení [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](./get_escapement/)() override | Vrací text horního nebo dolního indexu. Hodnota od -100 % (dolní index) do 100 % (horní index). **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota není definována a měla by být zděděna z Masteru. Přečtěte **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | Vrací vlastnosti textu [FillFormat](../fillformat/). Nedědí se. Pouze ke čtení [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() override | Určuje, zda je font tučný. Nedědí se. Přečtěte [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](./get_fontheight/)() override | Vrací výšku fontu části. **std::numeric_limits<float>::quiet_NaN()** znamená, že výška není definována a měla by být zděděna z Masteru. Přečtěte **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() override | Určuje, zda je font kurzíva. Nedědí se. Přečtěte [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() override | Vrací typ podtržení textu. Nedědí se. Přečtěte [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() override | Vrací barvu použitou pro zvýraznění textu. Nedědí se. Pouze ke čtení [IColorFormat](../icolorformat/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() override | Určuje, zda má styl podtržení vlastní [FillFormat](../fillformat/) vlastnosti nebo zdědí z [FillFormat](../fillformat/) vlastností textu. Přečtěte [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() override | Určuje, zda má styl podtržení vlastní [LineFormat](../lineformat/) vlastnosti nebo zdědí z [LineFormat](../lineformat/) vlastností textu. Přečtěte [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() override | Vrací minimální velikost fontu, při které se má zapnout kerning. **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota není definována a měla by být zděděna z Masteru. Přečtěte **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() override | Určuje, zda mají čísla ignorovat specifické svislé rozložení textu východoasijského jazyka. Nedědí se. Přečtěte [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() override | Vrací Id jazyka pro kontrolu pravopisu. Používá se pro kontrolu pravopisu a gramatiky. Přečtěte [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() override | Vrací informace o latinském fontu. Null znamená, že font není definován a měl by být zděděn z Masteru. Přečtěte [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | Vrací vlastnosti [LineFormat](../lineformat/) pro obrysování textu. Nedědí se. Pouze ke čtení [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() override | Určuje, zda má být výška textu normalizována. Nedědí se. Přečtěte [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Vrací objekt Parent_Immediate. Pouze ke čtení [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Vrací nadřazený [IPresentationComponent](../ipresentationcomponent/). Pouze ke čtení [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() override | Určuje, zda text nemá být kontrolován pravopisem. Nedědí se. Přečtěte [NullableBool](../nullablebool/). |
| **float** [get_Spacing](./get_spacing/)() override | Vrací přírůstek mezery mezi znaky. **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota není definována a měla by být zděděna z Masteru. Přečtěte **float**. |
| **bool** [get_SpellCheck](./get_spellcheck/)() override | Získává hodnotu určující, zda je pro část textu povoleno pravopisné kontrolování. Když je tato vlastnost nastavena na false, kontrola pravopisu pro textové elementy je potlačena. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() override | Vrací typ přeškrtnutí textu. Nedědí se. Přečtěte [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() override | Vrací informace o symbolickém fontu. Null znamená, že font není definován a měl by být zděděn z Masteru. Přečtěte [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() override | Vrací typ kapitalizace textu. Nedědí se. Přečtěte [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() override | Vrací vlastnosti podtržení [FillFormat](../fillformat/). Nedědí se. Pouze ke čtení [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() override | Vrací vlastnosti [LineFormat](../lineformat/) použité k obrysování podtržení. Nedědí se. Pouze ke čtení [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu referenčního čítače asociovanou s objektem. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Vrací hash kód. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání C# lock() výroků. Zavolejte přímo nebo použijte [LockContext](../../system/lockcontext/) objekt strážce. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává hodnotový typ objektu s nullptr podle reference. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) override | Nastavuje Id alternativního jazyka. Zapište [System::String](../../system/string/). |
| void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Nastavuje informace o fontu složitého skriptu. Null znamená, že font není definován a měl by být zděděn z Masteru. Zapište [IFontData](../ifontdata/). |
| void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Nastavuje informace o fontu východoasijského písma. Null znamená, že font není definován a měl by být zděděn z Masteru. Zapište [IFontData](../ifontdata/). |
| void [set_Escapement](./set_escapement/)(**float**) override | Nastavuje text horního nebo dolního indexu. Hodnota od -100 % (dolní index) do 100 % (horní index). **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota není definována a měla by být zděděna z Masteru. Zapište **float**. |
| void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) override | Určuje, zda je font tučný. Nedědí se. Zapište [NullableBool](../nullablebool/). |
| void [set_FontHeight](./set_fontheight/)(**float**) override | Nastavuje výšku fontu části. **std::numeric_limits<float>::quiet_NaN()** znamená, že výška není definována a měla by být zděděna z Masteru. Zapište **float**. |
| void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) override | Určuje, zda je font kurzíva. Nedědí se. Zapište [NullableBool](../nullablebool/). |
| void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | Nastavuje typ podtržení textu. Nedědí se. Zapište [TextUnderlineType](../textunderlinetype/). |
| void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | Určuje, zda má styl podtržení vlastní [FillFormat](../fillformat/) vlastnosti nebo zdědí z [FillFormat](../fillformat/) vlastností textu. Zapište [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | Určuje, zda má styl podtržení vlastní [LineFormat](../lineformat/) vlastnosti nebo zdědí z [LineFormat](../lineformat/) vlastností textu. Zapište [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) override | Nastavuje minimální velikost fontu, při které se má zapnout kerning. **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota není definována a měla by být zděděna z Masteru. Zapište **float**. |
| void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) override | Určuje, zda mají čísla ignorovat specifické svislé rozložení textu východoasijského jazyka. Nedědí se. Zapište [NullableBool](../nullablebool/). |
| void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) override | Nastavuje Id jazyka pro kontrolu pravopisu. Používá se pro kontrolu pravopisu a gramatiky. Zapište [System::String](../../system/string/). |
| void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Nastavuje informace o latinském fontu. Null znamená, že font není definován a měl by být zděděn z Masteru. Zapište [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) override | Určuje, zda má být výška textu normalizována. Nedědí se. Zapište [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) override | Určuje, zda text nemá být kontrolován pravopisem. Nedědí se. Zapište [NullableBool](../nullablebool/). |
| void [set_Spacing](./set_spacing/)(**float**) override | Nastavuje přírůstek mezery mezi znaky. **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota není definována a měla by být zděděna z Masteru. Zapište **float**. |
| void [set_SpellCheck](./set_spellcheck/)(**bool**) override | Nastavuje hodnotu určující, zda je pro část textu povoleno pravopisné kontrolování. Když je tato vlastnost nastavena na false, kontrola pravopisu pro textové elementy je potlačena. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je **false**. |
| void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | Nastavuje typ přeškrtnutí textu. Nedědí se. Zapište [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Nastavuje informace o symbolickém fontu. Null znamená, že font není definován a měl by být zděděn z Masteru. Zapište [IFontData](../ifontdata/). |
| void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | Nastavuje typ kapitalizace textu. Nedědí se. Zapište [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument na slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí C# lock() výrazu. Zavolejte přímo nebo použijte [LockContext](../../system/lockcontext/) objekt strážce. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; použijte chytré ukazatele nebo ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolňuje všechny vnitřní datové struktury. |
## Viz také

* Třída [PVIObject](../pviobject/)
* Třída [IBasePortionFormat](../ibaseportionformat/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)