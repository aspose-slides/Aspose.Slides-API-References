---
title: IDataLabelFormat
second_title: Aspose.Slides pro referenci API C++
description: Zastupuje možnosti formátování pro DataLabel.
type: docs
weight: 963
url: /cs/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat třída


Zastupuje možnosti formátování pro [DataLabel](../datalabel/).

```cpp
class IDataLabelFormat : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) semantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí řádovou čárkou ve stylu C# kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí řádovou čárkou ve stylu C# kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Vrací graf. Pouze pro čtení [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Zastupuje formát datové popisky. Pouze pro čtení [IFormat](../iformat/). |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Čte **bool**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | Zastupuje řetězec formátu pro objekt DataLabels. Čte [System::String](../../system/string/). |
| virtual [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() | Zastupuje pozici datové popisky. Čte [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Vrací prezentaci. Pouze pro čtení [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::String](../../system/string/) [get_Separator](./get_separator/)() | Nastaví nebo vrátí Variant představující oddělovač používaný pro datové popisky v grafu. Čte [System::String](../../system/string/). |
| virtual **bool** [get_ShowBubbleSize](./get_showbubblesize/)() | Zastupuje chování zobrazení hodnoty velikosti bubliny datové popisky v daném grafu. True zobrazí hodnotu velikosti bubliny. False skryje. Čte **bool**. |
| virtual **bool** [get_ShowCategoryName](./get_showcategoryname/)() | Zastupuje chování zobrazení názvu kategorie datové popisky v daném grafu. True zobrazí název kategorie. False skryje. Čte **bool**. |
| virtual **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() | Určuje, zda bude datová popiska v daném grafu zobrazena jako výkřik dat nebo jako datová popiska. |
| virtual **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() | Zastupuje chování zobrazení hodnoty buňky datové popisky v daném grafu. True zobrazí hodnotu buňky. False skryje. Čte **bool**. |
| virtual **bool** [get_ShowLeaderLines](./get_showleaderlines/)() | Zastupuje chování zobrazení čar šípky datové popisky v daném grafu. True zobrazí čáry šípky. False skryje. Čte **bool**. |
| virtual **bool** [get_ShowLegendKey](./get_showlegendkey/)() | Zastupuje chování zobrazení klíče legendy datové popisky v daném grafu. True pokud je klíč legendy viditelný. Čte **bool**. |
| virtual **bool** [get_ShowPercentage](./get_showpercentage/)() | Zastupuje chování zobrazení procentuální hodnoty datové popisky v daném grafu. True zobrazí procentuální hodnotu. False skryje. Čte **bool**. |
| virtual **bool** [get_ShowSeriesName](./get_showseriesname/)() | Vrací Boolean indikující chování zobrazení názvu řady pro datové popisky v grafu. True zobrazí název řady. False skryje. Čte **bool**. |
| virtual **bool** [get_ShowValue](./get_showvalue/)() | Zastupuje chování zobrazení procentuální hodnoty datové popisky v daném grafu. True zobrazí procentuální hodnotu. False skryje. Čte **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Vrací základní snímek. Pouze pro čtení [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Vrací formát textu grafu. Pouze pro čtení [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu čítače reference spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Volat přímo nebo použít objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
| [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává objekt typu hodnota s nullptr podle reference. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač reference o zadanou hodnotu. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Zapíše **bool**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | Zastupuje řetězec formátu pro objekt DataLabels. Zapíše [System::String](../../system/string/). |
| virtual void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) | Zastupuje pozici datové popisky. Zapíše [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual void [set_Separator](./set_separator/)([System::String](../../system/string/)) | Nastaví nebo vrátí Variant představující oddělovač používaný pro datové popisky v grafu. Zapíše [System::String](../../system/string/). |
| virtual void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) | Zastupuje chování zobrazení hodnoty velikosti bubliny datové popisky v daném grafu. True zobrazí hodnotu velikosti bubliny. False skryje. Zapíše **bool**. |
| virtual void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) | Zastupuje chování zobrazení názvu kategorie datové popisky v daném grafu. True zobrazí název kategorie. False skryje. Zapíše **bool**. |
| virtual void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) | Určuje, zda bude datová popiska v daném grafu zobrazena jako výkřik dat nebo jako datová popiska. |
| virtual void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) | Zastupuje chování zobrazení hodnoty buňky datové popisky v daném grafu. True zobrazí hodnotu buňky. False skryje. Zapíše **bool**. |
| virtual void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) | Zastupuje chování zobrazení čar šípky datové popisky v daném grafu. True zobrazí čáry šípky. False skryje. Zapíše **bool**. |
| virtual void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) | Zastupuje chování zobrazení klíče legendy datové popisky v daném grafu. True pokud je klíč legendy viditelný. Zapíše **bool**. |
| virtual void [set_ShowPercentage](./set_showpercentage/)(**bool**) | Zastupuje chování zobrazení procentuální hodnoty datové popisky v daném grafu. True zobrazí procentuální hodnotu. False skryje. Zapíše **bool**. |
| virtual void [set_ShowSeriesName](./set_showseriesname/)(**bool**) | Nastaví Boolean indikující chování zobrazení názvu řady pro datové popisky v grafu. True zobrazí název řady. False skryje. Zapíše **bool**. |
| virtual void [set_ShowValue](./set_showvalue/)(**bool**) | Zastupuje chování zobrazení procentuální hodnoty datové popisky v daném grafu. True zobrazí procentuální hodnotu. False skryje. Zapíše **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače reference. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší sdílený čítač reference. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač reference. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock(). Volat přímo nebo použít objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší slabý čítač reference. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač reference. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [IFormattedTextContainer](../iformattedtextcontainer/)
* Jmenný prostor [Aspose::Slides::Charts](../)
* Knihovna [Aspose.Slides](../../)