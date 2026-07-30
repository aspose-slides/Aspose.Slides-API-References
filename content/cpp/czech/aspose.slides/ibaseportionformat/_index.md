---
title: IBasePortionFormat
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Tato třída obsahuje vlastnosti formátování textových částí. Na rozdíl od IPortionFormatEffectiveData jsou všechny vlastnosti této třídy zapisovatelné.
type: docs
weight: 1457
url: /cs/aspose.slides/ibaseportionformat/
---
## Třída IBasePortionFormat

Tato třída obsahuje vlastnosti formátování textových částí. Na rozdíl od [IPortionFormatEffectiveData](../iportionformateffectivedata/) jsou všechny vlastnosti této třídy zapisovatelné.

```cpp
class IBasePortionFormat : public virtual System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Napodobuje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Napodobuje porovnání s dvojitou přesností ve stylu C#, kde jsou dva NaN považovány za rovné i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | Vrací Id alternativního jazyka. Přečtěte si [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | Vrací informace o fontu pro složité skripty. Null znamená, že font není definován a měl by být zděděn z Masteru. Přečtěte si [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | Vrací informace o východoasijském fontu. Null znamená, že font není definován a měl by být zděděn z Masteru. Přečtěte si [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | Vrací vlastnosti textu [EffectFormat](../effectformat/). Není použito dědění. Pouze pro čtení [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](./get_escapement/)() | Vrací text v podobě nadřazeného (superscript) nebo podřazeného (subscript). Hodnota od -100 % (subscript) do 100 % (superscript). **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota je nedefinovaná a měla by být zděděna z Masteru. Pouze **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | Vrací vlastnosti textu [FillFormat](../fillformat/). Není použito dědění. Pouze pro čtení [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() | Určuje, zda je font tučný. Není použito dědění. Přečtěte [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](./get_fontheight/)() | Vrací výšku fontu části. **std::numeric_limits<float>::quiet_NaN()** znamená, že výška je nedefinovaná a měla by být zděděna z Masteru. Pouze **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() | Určuje, zda je font kurzíva. Není použito dědění. Přečtěte [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | Vrací typ podtržení textu. Není použito dědění. Přečtěte [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() | Vrací barvu použitou pro zvýraznění textu. Není použito dědění. Pouze pro čtení [IColorFormat](../icolorformat/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | Určuje, zda má styl podtržení vlastní vlastnosti [FillFormat](../fillformat/) nebo je zděděn z vlastností [FillFormat](../fillformat/) textu. Přečtěte [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | Určuje, zda má styl podtržení vlastní vlastnosti [LineFormat](../lineformat/) nebo je zděděn z vlastností [LineFormat](../lineformat/) textu. Přečtěte [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | Vrací minimální velikost fontu, při které by mělo být zapnuto kerning. **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota je nedefinovaná a měla by být zděděna z Masteru. Pouze **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() | Určuje, zda mají čísla ignorovat vertikální rozvržení specifické pro východoasijské jazyky textu. Není použito dědění. Přečtěte [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | Vrací Id jazyka pro kontrolu. Používá se pro kontrolu pravopisu a gramatiky. Přečtěte [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | Vrací informace o latinském fontu. Null znamená, že font není definován a měl by být zděděn z Masteru. Přečtěte [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | Vrací vlastnosti [LineFormat](../lineformat/) pro obrysování textu. Není použito dědění. Pouze pro čtení [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() | Určuje, zda by výška textu měla být normalizována. Není použito dědění. Přečtěte [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() | Určuje, zda text nemá být kontrolován. Není použito dědění. Přečtěte [NullableBool](../nullablebool/). |
| virtual **float** [get_Spacing](./get_spacing/)() | Vrací přírůstek mezery mezi znaky. **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota je nedefinovaná a měla by být zděděna z Masteru. Pouze **float**. |
| virtual **bool** [get_SpellCheck](./get_spellcheck/)() | Získá hodnotu, která udává, zda je pro část textu povolena kontrola pravopisu. Když je tato vlastnost nastavena na false, kontrola pravopisu pro textové elementy je potlačena. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | Vrací typ přeškrtnutí textu. Není použito dědění. Přečtěte [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | Vrací informace o symbolickém fontu. Null znamená, že font není definován a měl by být zděděn z Masteru. Přečtěte [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | Vrací typ kapitalizace textu. Není použito dědění. Přečtěte [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | Vrací vlastnosti podtržité čáry [FillFormat](../fillformat/). Není použito dědění. Pouze pro čtení [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | Vrací vlastnosti [LineFormat](../lineformat/) použité k obrysování podtržené čáry. Není použito dědění. Pouze pro čtení [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie k metodě C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie k volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie k operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí výrazu C# lock(). Zavolejte přímo nebo použijte objekt hlídacího typu [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie k metodě C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač odkazů o zadanou hodnotu. |
| virtual void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) | Nastavuje Id alternativního jazyka. Zapsat [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Nastavuje informace o fontu pro složité skripty. Null znamená, že font není definován a měl by být zděděn z Masteru. Zapsat [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Nastavuje informace o východoasijském fontu. Null znamená, že font není definován a měl by být zděděn z Masteru. Zapsat [IFontData](../ifontdata/). |
| virtual void [set_Escapement](./set_escapement/)(**float**) | Nastavuje text v podobě nadřazeného (superscript) nebo podřazeného (subscript). Hodnota od -100 % (subscript) do 100 % (superscript). **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota je nedefinovaná a měla by být zděděna z Masteru. Zapsat **float**. |
| virtual void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) | Určuje, zda je font tučný. Není použito dědění. Zapsat [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](./set_fontheight/)(**float**) | Nastavuje výšku fontu části. **std::numeric_limits<float>::quiet_NaN()** znamená, že výška je nedefinovaná a měla by být zděděna z Masteru. Zapsat **float**. |
| virtual void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) | Určuje, zda je font kurzíva. Není použito dědění. Zapsat [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | Nastavuje typ podtržení textu. Není použito dědění. Zapsat [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | Určuje, zda má styl podtržení vlastní vlastnosti [FillFormat](../fillformat/) nebo je zděděn z vlastností [FillFormat](../fillformat/) textu. Zapsat [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) | Určuje, zda má styl podtržení vlastní vlastnosti [LineFormat](../lineformat/) nebo je zděděn z vlastností [LineFormat](../lineformat/) textu. Zapsat [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) | Nastavuje minimální velikost fontu, při které by mělo být zapnuto kerning. **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota je nedefinovaná a měla by být zděděna z Masteru. Zapsat **float**. |
| virtual void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) | Určuje, zda mají čísla ignorovat vertikální rozvržení textu specifické pro východoasijské jazyky. Není použito dědění. Zapsat [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) | Nastavuje Id jazyka pro kontrolu. Používá se pro kontrolu pravopisu a gramatiky. Zapsat [System::String](../../system/string/). |
| virtual void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Nastavuje informace o latinském fontu. Null znamená, že font není definován a měl by být zděděn z Masteru. Zapsat [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) | Určuje, zda by výška textu měla být normalizována. Není použito dědění. Zapsat [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) | Určuje, zda text nemá být kontrolován. Není použito dědění. Zapsat [NullableBool](../nullablebool/). |
| virtual void [set_Spacing](./set_spacing/)(**float**) | Nastavuje přírůstek mezery mezi znaky. **std::numeric_limits<float>::quiet_NaN()** znamená, že hodnota je nedefinovaná a měla by být zděděna z Masteru. Zapsat **float**. |
| virtual void [set_SpellCheck](./set_spellcheck/)(**bool**) | Nastavuje hodnotu udávající, zda je pro část textu povolena kontrola pravopisu. Když je tato vlastnost nastavena na false, kontrola pravopisu pro textové elementy je potlačena. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je **false**. |
| virtual void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | Nastavuje typ přeškrtnutí textu. Není použito dědění. Zapsat [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Nastavuje informace o symbolickém fontu. Null znamená, že font není definován a měl by být zděděn z Masteru. Zapsat [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | Nastavuje typ kapitalizace textu. Není použito dědění. Zapsat [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného počítadla odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač odkazů. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač odkazů. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie k metodě C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí výrazu C# lock(). Zavolejte přímo nebo použijte objekt hlídacího typu [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač odkazů. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač odkazů. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Poznámky

Tato třída se používá k získání a manipulaci s vlastnostmi formátování textových částí definovanými pro konkrétní část. To znamená, že při získávání hodnot není použito dědění, takže ve většině případů získáte hodnoty označující „nedefinováno“.

Pro získání efektivních hodnot parametrů formátování včetně děděných je nutné použít metodu [IPortionFormat::GetEffective](../iportionformat/geteffective/), která vrací instanci [IPortionFormatEffectiveData](../iportionformateffectivedata/).

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)