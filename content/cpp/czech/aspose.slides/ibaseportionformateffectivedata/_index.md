---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides pro C++ - reference API
description: Základní rozhraní pro neměnné objekty, které obsahují účinné vlastnosti formátování částí textu.
type: docs
weight: 1470
url: /cs/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData třída

Základní rozhraní pro neměnné objekty, které obsahují účinné vlastnosti formátování částí textu.

```cpp
class IBasePortionFormatEffectiveData : public virtual System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnávání desetinných čísel ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnávání desetinných čísel ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | Vrací Id alternativního jazyka. Pouze pro čtení [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | Vrací informace o písmu pro složité skripty. Pouze pro čtení [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | Vrací informace o písmu pro východoasijské jazyky. Pouze pro čtení [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [get_EffectFormat](./get_effectformat/)() | Vrací vlastnosti textu [EffectFormat](../effectformat/). Pouze pro čtení [IEffectFormatEffectiveData](../ieffectformateffectivedata/). |
| virtual **float** [get_Escapement](./get_escapement/)() | Vrací text jako horní index nebo dolní index. Hodnota od -100 % (dolní index) do 100 % (horní index). Pouze pro čtení **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_FillFormat](./get_fillformat/)() | Vrací vlastnosti textu [FillFormat](../fillformat/). Pouze pro čtení [IFillFormatEffectiveData](../ifillformateffectivedata/). |
| virtual **bool** [get_FontBold](./get_fontbold/)() | Určuje, zda je písmo tučné. Pouze pro čtení **bool**. |
| virtual **float** [get_FontHeight](./get_fontheight/)() | Vrací výšku písma textové části v bodech. Pouze pro čtení **float**. |
| virtual **bool** [get_FontItalic](./get_fontitalic/)() | Určuje, zda je písmo kurzíva. Pouze pro čtení **bool**. |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | Vrací typ podtržení textu. Pouze pro čtení [TextUnderlineType](../textunderlinetype/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_HighlightColor](./get_highlightcolor/)() | Vrací barvu použitou pro zvýraznění textu. Pouze pro čtení [System::Drawing::Color](../../system.drawing/color/). |
| virtual **bool** [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | Určuje, zda má styl podtržení vlastní vlastnosti [FillFormat](../fillformat/) nebo je děděn z vlastností [FillFormat](../fillformat/) textu. Pouze pro čtení **bool**. |
| virtual **bool** [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | Určuje, zda má styl podtržení vlastní vlastnosti [LineFormat](../lineformat/) nebo je děděn z vlastností [LineFormat](../lineformat/) textu. Pouze pro čtení **bool**. |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | Vrací minimální velikost písma, pro kterou by mělo být zapnuto kerning. Pouze pro čtení **float**. |
| virtual **bool** [get_Kumimoji](./get_kumimoji/)() | Určuje, zda mají čísla ignorovat specifické vertikální rozložení textu východoasijských jazyků. Pouze pro čtení **bool**. |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | Vrací Id jazyka. Pouze pro čtení [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | Vrací informace o latinském písmu. Pouze pro čtení [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_LineFormat](./get_lineformat/)() | Vrací vlastnosti [LineFormat](../lineformat/) pro obrysování textu. Pouze pro čtení [ILineFormatEffectiveData](../ilineformateffectivedata/). |
| virtual **bool** [get_NormaliseHeight](./get_normaliseheight/)() | Určuje, zda by výška textu měla být normalizována. Pouze pro čtení **bool**. |
| virtual **bool** [get_ProofDisabled](./get_proofdisabled/)() | Určuje, zda text nemá být kontrolován. Pouze pro čtení **bool**. |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | Určuje, zda má být inteligentní štítek vyčištěn. Pouze pro čtení **bool**. |
| virtual **float** [get_Spacing](./get_spacing/)() | Vrací přírůstek mezery mezi znaky v bodech. Pouze pro čtení **float**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | Vrací typ přeškrtnutí textu. Pouze pro čtení [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | Vrací informace o symbolickém písmu. Pouze pro čtení [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | Vrací typ kapitalizace textu. Pouze pro čtení [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | Vrací vlastnosti podtržítka [FillFormat](../fillformat/). Pouze pro čtení [IFillFormatEffectiveData](../ifillformateffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | Vrací vlastnosti [LineFormat](../lineformat/) použité k obrysování podtržítka. Pouze pro čtení [ILineFormatEffectiveData](../ilineformateffectivedata/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného parametrem targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt hlídky [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí hodnotový typ s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač odkazů o zadanou hodnotu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (místo sdíleného). Umožňuje přepnout ukazatele v kontejnerech do režimu slabých. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší sdílený čítač odkazů. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač odkazů. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokování pomocí C# lock(). Zavolejte přímo nebo použijte objekt hlídky [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší čítač slabých odkazů. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží čítač slabých odkazů. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)