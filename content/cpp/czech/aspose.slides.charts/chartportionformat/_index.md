---
title: ChartPortionFormat
second_title: Aspose.Slides pro C++ API Reference
description: Tato třída obsahuje vlastnosti formátování částí grafu používané v grafech. Na rozdíl od IPortionFormatEffectiveData jsou všechny vlastnosti této třídy zapisovatelné.
type: docs
weight: 261
url: /cs/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat třída


Tato třída obsahuje vlastnosti formátování částí grafu používané v grafech. Na rozdíl od [IPortionFormatEffectiveData](../../aspose.slides/iportionformateffectivedata/) jsou všechny vlastnosti této třídy zapisovatelné.

```cpp
class ChartPortionFormat : public Aspose::Slides::BasePortionFormat,
                           public Aspose::Slides::Charts::IChartPortionFormat
```

## Metody

| Metoda | Popis |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Porovnává s určeným objektem. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za stejné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za stejné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../../aspose.slides/baseportionformat/get_alternativelanguageid/)() override | Vrací Id alternativního jazyka. Číst [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_ComplexScriptFont](../../aspose.slides/baseportionformat/get_complexscriptfont/)() override | Vrací informace o fontu složitého skriptu. Null znamená, že font není definován a měl by být zděděn z hlavního. Číst [IFontData](../../aspose.slides/ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_EastAsianFont](../../aspose.slides/baseportionformat/get_eastasianfont/)() override | Vrací informace o východoasijském fontu. Null znamená, že font není definován a měl by být zděděn z hlavního. Číst [IFontData](../../aspose.slides/ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/baseportionformat/get_effectformat/)() override | Vrací vlastnosti textu [EffectFormat](../../aspose.slides/effectformat/). Není použito dědění. Pouze ke čtení [IEffectFormat](../../aspose.slides/ieffectformat/). |
| **float** [get_Escapement](../../aspose.slides/baseportionformat/get_escapement/)() override | Vrací text horního nebo dolního indexu. Hodnota od -100 % (dolní index) do 100 % (horní index). **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota není definována a měla by být zděděna z hlavního. Číst **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/baseportionformat/get_fillformat/)() override | Vrací vlastnosti textu [FillFormat](../../aspose.slides/fillformat/). Není použito dědění. Pouze ke čtení [IFillFormat](../../aspose.slides/ifillformat/). |
| [NullableBool](../../aspose.slides/nullablebool/) [get_FontBold](../../aspose.slides/baseportionformat/get_fontbold/)() override | Určuje, zda je font tučný. Není použito dědění. Číst [NullableBool](../../aspose.slides/nullablebool/). |
| **float** [get_FontHeight](../../aspose.slides/baseportionformat/get_fontheight/)() override | Vrací výšku fontu části. **std::numeric_limits<float>::quiet_NaN()** znamená, že výška není definována a měla by být zděděna z hlavního. Číst **float**. |
| [NullableBool](../../aspose.slides/nullablebool/) [get_FontItalic](../../aspose.slides/baseportionformat/get_fontitalic/)() override | Určuje, zda je font kurzívou. Není použito dědění. Číst [NullableBool](../../aspose.slides/nullablebool/). |
| [TextUnderlineType](../../aspose.slides/textunderlinetype/) [get_FontUnderline](../../aspose.slides/baseportionformat/get_fontunderline/)() override | Vrací typ podtržení textu. Není použito dědění. Číst [TextUnderlineType](../../aspose.slides/textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_HighlightColor](../../aspose.slides/baseportionformat/get_highlightcolor/)() override | Vrací barvu použitou k zvýraznění textu. Není použito dědění. Pouze ke čtení [IColorFormat](../../aspose.slides/icolorformat/). |
| [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineFill](../../aspose.slides/baseportionformat/get_ishardunderlinefill/)() override | Určuje, zda má styl podtržení vlastní vlastnosti [FillFormat](../../aspose.slides/fillformat/) nebo je dědí z vlastností [FillFormat](../../aspose.slides/fillformat/) textu. Číst [NullableBool](../../aspose.slides/nullablebool/). |
| [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineLine](../../aspose.slides/baseportionformat/get_ishardunderlineline/)() override | Určuje, zda má styl podtržení vlastní vlastnosti [LineFormat](../../aspose.slides/lineformat/) nebo je dědí z vlastností [LineFormat](../../aspose.slides/lineformat/) textu. Číst [NullableBool](../../aspose.slides/nullablebool/). |
| **float** [get_KerningMinimalSize](../../aspose.slides/baseportionformat/get_kerningminimalsize/)() override | Vrací minimální velikost fontu, pro kterou by mělo být zapnuto kerning. **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota není definována a měla by být zděděna z hlavního. Číst **float**. |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Kumimoji](../../aspose.slides/baseportionformat/get_kumimoji/)() override | Určuje, zda by čísla měla ignorovat specifické svislé rozložení textu východoasijských jazyků. Není použito dědění. Číst [NullableBool](../../aspose.slides/nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](../../aspose.slides/baseportionformat/get_languageid/)() override | Vrací Id jazykové kontroly. Používá se pro kontrolu pravopisu a gramatiky. Číst [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_LatinFont](../../aspose.slides/baseportionformat/get_latinfont/)() override | Vrací informace o latinském fontu. Null znamená, že font není definován a měl by být zděděn z hlavního. Číst [IFontData](../../aspose.slides/ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/baseportionformat/get_lineformat/)() override | Vrací vlastnosti [LineFormat](../../aspose.slides/lineformat/) pro obrysování textu. Není použito dědění. Pouze ke čtení [ILineFormat](../../aspose.slides/ilineformat/). |
| [NullableBool](../../aspose.slides/nullablebool/) [get_NormaliseHeight](../../aspose.slides/baseportionformat/get_normaliseheight/)() override | Určuje, zda by výška textu měla být normalizována. Není použito dědění. Číst [NullableBool](../../aspose.slides/nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | Vrací objekt Parent_Immediate. Pouze ke čtení [IDOMObject](../../aspose.slides/idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Vrací nadřazený [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). Pouze ke čtení [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [NullableBool](../../aspose.slides/nullablebool/) [get_ProofDisabled](../../aspose.slides/baseportionformat/get_proofdisabled/)() override | Určuje, zda by text neměl být kontrolován. Není použito dědění. Číst [NullableBool](../../aspose.slides/nullablebool/). |
| **float** [get_Spacing](../../aspose.slides/baseportionformat/get_spacing/)() override | Vrací přírůstek mezery mezi znaky. **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota není definována a měla by být zděděna z hlavního. Číst **float**. |
| **bool** [get_SpellCheck](../../aspose.slides/baseportionformat/get_spellcheck/)() override | Získává hodnotu udávající, zda je pro část textu povolena kontrola pravopisu. Když je tato vlastnost nastavena na false, kontroly pravopisu pro textové prvky jsou potlačeny. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je **false**. |
| [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/) [get_StrikethroughType](../../aspose.slides/baseportionformat/get_strikethroughtype/)() override | Vrací typ přeškrtnutí textu. Není použito dědění. Číst [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_SymbolFont](../../aspose.slides/baseportionformat/get_symbolfont/)() override | Vrací informace o symbolickém fontu. Null znamená, že font není definován a měl by být zděděn z hlavního. Číst [IFontData](../../aspose.slides/ifontdata/). |
| [Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/) [get_TextCapType](../../aspose.slides/baseportionformat/get_textcaptype/)() override | Vrací typ kapitalizace textu. Není použito dědění. Číst [Slides::TextCapType](../../aspose.slides/textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_UnderlineFillFormat](../../aspose.slides/baseportionformat/get_underlinefillformat/)() override | Vrací vlastnosti podtržítka [FillFormat](../../aspose.slides/fillformat/). Není použito dědění. Pouze ke čtení [IFillFormat](../../aspose.slides/ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_UnderlineLineFormat](../../aspose.slides/baseportionformat/get_underlinelineformat/)() override | Vrací vlastnosti [LineFormat](../../aspose.slides/lineformat/) použité k obrysování podtržítka. Není použito dědění. Pouze ke čtení [ILineFormat](../../aspose.slides/ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu čítače odkazů spojenou s objektem. |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | Vrací hash kód. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
| [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač odkazů o zadanou hodnotu. |
| void [set_AlternativeLanguageId](../../aspose.slides/baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | Nastavuje Id alternativního jazyka. Zapisovat [System::String](../../system/string/). |
| void [set_ComplexScriptFont](../../aspose.slides/baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | Nastavuje informace o fontu složitého skriptu. Null znamená, že font není definován a měl by být zděděn z hlavního. Zapisovat [IFontData](../../aspose.slides/ifontdata/). |
| void [set_EastAsianFont](../../aspose.slides/baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | Nastavuje informace o východoasijském fontu. Null znamená, že font není definován a měl by být zděděn z hlavního. Zapisovat [IFontData](../../aspose.slides/ifontdata/). |
| void [set_Escapement](../../aspose.slides/baseportionformat/set_escapement/)(**float**) override | Nastavuje text horního nebo dolního indexu. Hodnota od -100 % (dolní index) do 100 % (horní index). **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota není definována a měla by být zděděna z hlavního. Zapisovat **float**. |
| void [set_FontBold](../../aspose.slides/baseportionformat/set_fontbold/)([NullableBool](../../aspose.slides/nullablebool/)) override | Určuje, zda je font tučný. Není použito dědění. Zapisovat [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_FontHeight](../../aspose.slides/baseportionformat/set_fontheight/)(**float**) override | Nastavuje výšku fontu části. **std::numeric_limits<float>::quiet_NaN()** znamená, že výška není definována a měla by být zděděna z hlavního. Zapisovat **float**. |
| void [set_FontItalic](../../aspose.slides/baseportionformat/set_fontitalic/)([NullableBool](../../aspose.slides/nullablebool/)) override | Určuje, zda je font kurzívou. Není použito dědění. Zapisovat [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_FontUnderline](../../aspose.slides/baseportionformat/set_fontunderline/)([TextUnderlineType](../../aspose.slides/textunderlinetype/)) override | Nastavuje typ podtržení textu. Není použito dědění. Zapisovat [TextUnderlineType](../../aspose.slides/textunderlinetype/). |
| void [set_IsHardUnderlineFill](../../aspose.slides/baseportionformat/set_ishardunderlinefill/)([NullableBool](../../aspose.slides/nullablebool/)) override | Určuje, zda má styl podtržení vlastní vlastnosti [FillFormat](../../aspose.slides/fillformat/) nebo je dědí z vlastností [FillFormat](../../aspose.slides/fillformat/) textu. Zapisovat [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_IsHardUnderlineLine](../../aspose.slides/baseportionformat/set_ishardunderlineline/)([NullableBool](../../aspose.slides/nullablebool/)) override | Určuje, zda má styl podtržení vlastní vlastnosti [LineFormat](../../aspose.slides/lineformat/) nebo je dědí z vlastností [LineFormat](../../aspose.slides/lineformat/) textu. Zapisovat [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_KerningMinimalSize](../../aspose.slides/baseportionformat/set_kerningminimalsize/)(**float**) override | Nastavuje minimální velikost fontu, pro kterou by mělo být zapnuto kerning. **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota není definována a měla by být zděděna z hlavního. Zapisovat **float**. |
| void [set_Kumimoji](../../aspose.slides/baseportionformat/set_kumimoji/)([NullableBool](../../aspose.slides/nullablebool/)) override | Určuje, zda by čísla měla ignorovat specifické svislé rozložení textu východoasijských jazyků. Není použito dědění. Zapisovat [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_LanguageId](../../aspose.slides/baseportionformat/set_languageid/)([System::String](../../system/string/)) override | Nastavuje Id jazykové kontroly. Používá se pro kontrolu pravopisu a gramatiky. Zapisovat [System::String](../../system/string/). |
| void [set_LatinFont](../../aspose.slides/baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | Nastavuje informace o latinském fontu. Null znamená, že font není definován a měl by být zděděn z hlavního. Zapisovat [IFontData](../../aspose.slides/ifontdata/). |
| void [set_NormaliseHeight](../../aspose.slides/baseportionformat/set_normaliseheight/)([NullableBool](../../aspose.slides/nullablebool/)) override | Určuje, zda by výška textu měla být normalizována. Není použito dědění. Zapisovat [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_ProofDisabled](../../aspose.slides/baseportionformat/set_proofdisabled/)([NullableBool](../../aspose.slides/nullablebool/)) override | Určuje, zda by text neměl být kontrolován. Není použito dědění. Zapisovat [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_Spacing](../../aspose.slides/baseportionformat/set_spacing/)(**float**) override | Nastavuje přírůstek mezery mezi znaky. **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota není definována a měla by být zděděna z hlavního. Zapisovat **float**. |
| void [set_SpellCheck](../../aspose.slides/baseportionformat/set_spellcheck/)(**bool**) override | Nastavuje hodnotu udávající, zda je pro část textu povolena kontrola pravopisu. Když je tato vlastnost nastavena na false, kontroly pravopisu pro textové prvky jsou potlačeny. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je **false**. |
| void [set_StrikethroughType](../../aspose.slides/baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../../aspose.slides/textstrikethroughtype/)) override | Nastavuje typ přeškrtnutí textu. Není použito dědění. Zapisovat [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/). |
| void [set_SymbolFont](../../aspose.slides/baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | Nastavuje informace o symbolickém fontu. Null znamená, že font není definován a měl by být zděděn z hlavního. Zapisovat [IFontData](../../aspose.slides/ifontdata/). |
| void [set_TextCapType](../../aspose.slides/baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/)) override | Nastavuje typ kapitalizace textu. Není použito dědění. Zapisovat [Slides::TextCapType](../../aspose.slides/textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného čítače odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolňuje všechny vnitřní datové struktury. |

## Poznámky


Tato třída se používá k získání a manipulaci s vlastnostmi formátování částí textu definovanými pro konkrétní část. To znamená, že při získávání hodnot se nedědí, takže ve většině případů získáte hodnoty, které znamenají „nedefinováno“.

Pro získání efektivních hodnot parametrů formátování včetně zděděných je potřeba použít metodu [PortionFormat::GetEffective](../../aspose.slides/portionformat/geteffective/), která vrací instanci [IPortionFormatEffectiveData](../../aspose.slides/iportionformateffectivedata/).

## Viz také

* Třída [BasePortionFormat](../../aspose.slides/baseportionformat/)
* Třída [IChartPortionFormat](../ichartportionformat/)
* Jmenný prostor [Aspose::Slides::Charts](../)
* Knihovna [Aspose.Slides](../../)