---
title: ITrendline
second_title: Aspose.Slides pro C++ API Reference
description: Třída představuje trendovou čáru řady grafu
type: docs
weight: 1223
url: /cs/aspose.slides.charts/itrendline/
---
## ITrendline třída


Třída představuje trendovou čáru řady grafu

```cpp
class ITrendline : public Aspose::Slides::Charts::IOverridableText
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Inicializuje TextFrameForOverriding textem v parametru "text". Pokud je TextFrameForOverriding již inicializován, jednoduše změní jeho text. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání floating point ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovna žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání floating point ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovna žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual **double** [get_Backward](./get_backward/)() | Určuje počet kategorií (nebo jednotek v rozptýleném grafu), které trendová čára rozšiřuje před data řady, která je trendována. V rozptýlených i nerozptýlených grafech může být hodnota libovolná nezáporná hodnota. Čte **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Vrací graf. Pouze pro čtení [IChart](../ichart/). |
| virtual **bool** [get_DisplayEquation](./get_displayequation/)() | Určuje, že rovnice trendové čáry je zobrazena v grafu (ve stejném štítku jako Rsquaredvalue). Čte **bool**. |
| virtual **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() | Určuje, že hodnota R-kvadrátu trendové čáry je zobrazena v grafu (ve stejném štítku jako rovnice). Čte **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Reprezentuje formát trendové čáry. Čte [IFormat](../iformat/). |
| virtual **double** [get_Forward](./get_forward/)() | Určuje počet kategorií (nebo jednotek v rozptýleném grafu), které trendová čára rozšiřuje po data řady, která je trendována. V rozptýlených i nerozptýlených grafech může být hodnota libovolná nezáporná hodnota. Čte **double**. |
| virtual **double** [get_Intercept](./get_intercept/)() | Určuje hodnotu, kde má trendová čára protínat osu y. Tato vlastnost je podporována pouze, když je typ trendové čáry exp, linear nebo poly. Čte **double**. |
| virtual **uint8_t** [get_Order](./get_order/)() | Určuje řád polynomické trendové čáry. Pro ostatní typy trendových čar je ignorováno. Hodnota musí být mezi 2 a 6. Čte **uint8_t**. |
| virtual **uint8_t** [get_Period](./get_period/)() | Určuje periodu trendové čáry pro klouzavý průměr. Pro ostatní varianty trendových čar je ignorováno. Hodnota musí být mezi 2 a 255. Čte **uint8_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Vrací prezentaci. Pouze pro čtení [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | Reprezentuje položku legendy související s touto trendovou čarou. Pouze pro čtení [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Vrací základní snímek. Pouze pro čtení [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Vrací formát textu grafu. Pouze pro čtení [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Může obsahovat bohatě formátovaný text. Pokud tato vlastnost není null, pak tento formátovaný text přepíše automaticky generovaný text. Automaticky generovaný text je implicitní vlastností popisku dat, štítku jednotek osy hodnot, názvu osy, názvu grafu, štítku trendové čáry. Automaticky generovaný text je formátován pomocí vlastnosti [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Pouze pro čtení [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() | Získá název trendové čáry. Čte [System::String](../../system/string/). |
| virtual [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() | Získá typ trendové čáry. Čte [TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu referenčního čítače přidruženou k objektu. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() příkazu. Volat přímo nebo použít [LockContext](../../system/lockcontext/) objekt strážce. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje konstrukci podtříd kopií. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje konstrukci podtříd kopií. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený referenční čítač o zadanou hodnotu. |
| virtual void [set_Backward](./set_backward/)(**double**) | Určuje počet kategorií (nebo jednotek v rozptýleném grafu), které trendová čára rozšiřuje před data řady, která je trendována. V rozptýlených i nerozptýlených grafech může být hodnota libovolná nezáporná hodnota. Zapíše **double**. |
| virtual void [set_DisplayEquation](./set_displayequation/)(**bool**) | Určuje, že rovnice trendové čáry je zobrazena v grafu (ve stejném štítku jako Rsquaredvalue). Zapíše **bool**. |
| virtual void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) | Určuje, že hodnota R-kvadrátu trendové čáry je zobrazena v grafu (ve stejném štítku jako rovnice). Zapíše **bool**. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | Reprezentuje formát trendové čáry. Zapíše [IFormat](../iformat/). |
| virtual void [set_Forward](./set_forward/)(**double**) | Určuje počet kategorií (nebo jednotek v rozptýleném grafu), které trendová čára rozšiřuje po data řady, která je trendována. V rozptýlených i nerozptýlených grafech může být hodnota libovolná nezáporná hodnota. Zapíše **double**. |
| virtual void [set_Intercept](./set_intercept/)(**double**) | Určuje hodnotu, kde má trendová čára protínat osu y. Tato vlastnost je podporována pouze, když je typ trendové čáry exp, linear nebo poly. Zapíše **double**. |
| virtual void [set_Order](./set_order/)(**uint8_t**) | Určuje řád polynomické trendové čáry. Pro ostatní typy trendových čar je ignorováno. Hodnota musí být mezi 2 a 6. Zapíše **uint8_t**. |
| virtual void [set_Period](./set_period/)(**uint8_t**) | Určuje periodu trendové čáry pro klouzavý průměr. Pro ostatní varianty trendových čar je ignorováno. Hodnota musí být mezi 2 a 255. Zapíše **uint8_t**. |
| virtual void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) | Nastaví název trendové čáry. Zapíše [System::String](../../system/string/). |
| virtual void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) | Nastaví typ trendové čáry. Zapíše [TrendlineType](../trendlinetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do režimu slabého. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného referenčního čítače. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí C# lock() příkazu. Volat přímo nebo použít [LockContext](../../system/lockcontext/) objekt strážce. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší slabý referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý referenční čítač. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [IOverridableText](../ioverridabletext/)
* Jmenný prostor [Aspose::Slides::Charts](../)
* Knihovna [Aspose.Slides](../../)