---
title: Trendline
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Třída představuje trendovou čáru řady grafu
type: docs
weight: 1366
url: /cs/aspose.slides.charts/trendline/
---
## Trendline třída

Třída představuje trendovou čáru řady grafu

```cpp
class Trendline : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::TrendlineCollection>>,
                  public Aspose::Slides::Charts::ITrendline
```

## Metody

| Metoda | Popis |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Inicializuje TextFrameForOverriding textem v parametru „text“. Pokud je TextFrameForOverriding již inicializováno, jednoduše změní jeho text. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| **double** [get_Backward](./get_backward/)() override | Určuje počet kategorií (nebo jednotek v rozptylovém grafu), které trendová čára rozšiřuje před daty pro řadu, která je trendována. V rozptylových i nerozptylových grafech může být hodnota libovolná nezáporná. Čte **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Vrací nadřazený graf. Pouze pro čtení [IChart](../ichart/). |
| **bool** [get_DisplayEquation](./get_displayequation/)() override | Určuje, že rovnice trendové čáry je zobrazena na grafu (ve stejném popisku jako hodnota Rsquared). Čte **bool**. |
| **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() override | Určuje, že hodnota R-squared trendové čáry je zobrazena na grafu (ve stejném popisku jako rovnice). Čte **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Zastupuje formát trendové čáry. Čte [IFormat](../iformat/). |
| **double** [get_Forward](./get_forward/)() override | Určuje počet kategorií (nebo jednotek v rozptylovém grafu), které trendová čára rozšiřuje po datech pro řadu, která je trendována. V rozptylových i nerozptylových grafech může být hodnota libovolná nezáporná. Čte **double**. |
| **double** [get_Intercept](./get_intercept/)() override | Určuje hodnotu, kde má trendová čára protínat osu y. Tato vlastnost je podporována pouze pro typy trendových čar exp, linear nebo poly. Čte **double**. |
| **uint8_t** [get_Order](./get_order/)() override | Určuje řád polynomické trendové čáry. Pro jiné typy trendových čar je ignorováno. Hodnota musí být mezi 2 a 6. Čte **uint8_t**. |
| **uint8_t** [get_Period](./get_period/)() override | Určuje periodu trendové čáry pro klouzavý průměr. Pro jiné varianty je ignorováno. Hodnota musí být mezi 2 a 255. Čte **uint8_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | Zastupuje položku legendy související s touto trendovou čárou. Pouze pro čtení [ILegendEntryProperties](../ilegendentryproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Vrací formát textu. Pouze pro čtení [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Může obsahovat bohatě formátovaný text. Pokud tato vlastnost není null, tento formátovaný text přepisuje automaticky generovaný text štítku dat. Automaticky generovaný text štítku dat je text spravovaný vlastnostmi ShowSeriesName, ShowValue, … a formátovaný pomocí TextFormatManager.TextFormat. Pouze pro čtení [ITextFrame](../../aspose.slides/itextframe/). |
| [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() override | Získává název trendové čáry. Čte [System::String](../../system/string/). |
| [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() override | Získává typ trendové čáry. Čte [Charts::TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu počítadla odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hašování uživatelských objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává aktuální typ objektu. Analogie C# [System.Object.GetType()](../../system/object/gettype/) volání. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie C# operátoru ‘is’. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() výrazu. Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování uživatelských typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží počet sdílených odkazů o zadanou hodnotu. |
| void [set_Backward](./set_backward/)(**double**) override | Určuje počet kategorií (nebo jednotek v rozptylovém grafu), které trendová čára rozšiřuje před daty pro řadu, která je trendována. V rozptylových i nerozptylových grafech může být hodnota libovolná nezáporná. Zapíše **double**. |
| void [set_DisplayEquation](./set_displayequation/)(**bool**) override | Určuje, že rovnice trendové čáry je zobrazena na grafu (ve stejném popisku jako hodnota Rsquared). Zapíše **bool**. |
| void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) override | Určuje, že hodnota R-squared trendové čáry je zobrazena na grafu (ve stejném popisku jako rovnice). Zapíše **bool**. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | Zastupuje formát trendové čáry. Zapíše [IFormat](../iformat/). |
| void [set_Forward](./set_forward/)(**double**) override | Určuje počet kategorií (nebo jednotek v rozptylovém grafu), které trendová čára rozšiřuje po datech pro řadu, která je trendována. V rozptylových i nerozptylových grafech může být hodnota libovolná nezáporná. Zapíše **double**. |
| void [set_Intercept](./set_intercept/)(**double**) override | Určuje hodnotu, kde má trendová čára protínat osu y. Tato vlastnost je podporována pouze pro typy trendových čar exp, linear nebo poly. Zapíše **double**. |
| void [set_Order](./set_order/)(**uint8_t**) override | Určuje řád polynomické trendové čáry. Pro jiné typy je ignorováno. Hodnota musí být mezi 2 a 6. Zapíše **uint8_t**. |
| void [set_Period](./set_period/)(**uint8_t**) override | Určuje periodu trendové čáry pro klouzavý průměr. Pro jiné varianty je ignorováno. Hodnota musí být mezi 2 a 255. Zapíše **uint8_t**. |
| void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) override | Nastavuje název trendové čáry. Zapíše [System::String](../../system/string/). |
| void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) override | Nastavuje typ trendové čáry. Zapíše [Charts::TrendlineType](../trendlinetype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Nastavuje n-tý šablonový argument na weak ukazatel (namísto shared). Umožňuje přepínání ukazatelů v kontejnerech do weak režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu počítadla sdílených odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje počet sdílených odkazů. Nemělo by se volat přímo; místo toho používejte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací počet sdílených odkazů. Nemělo by se volat přímo; místo toho používejte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převod uživatelských objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock() výrazu. Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje počet weak odkazů. Nemělo by se volat přímo; místo toho používejte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje počet weak odkazů. Nemělo by se volat přímo; místo toho používejte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolňuje všechny vnitřní datové struktury. |

## Viz také

* Třída [DomObject](../../aspose.slides/domobject/)
* Třída [ITrendline](../itrendline/)
* Jmenný prostor [Aspose::Slides::Charts](../)
* Knihovna [Aspose.Slides](../../)