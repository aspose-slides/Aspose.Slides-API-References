---
title: DataLabelFormat
second_title: Aspose.Slides pro C++ referenční příručka API
description: Reprezentuje možnosti formátování pro DataLabel.
type: docs
weight: 391
url: /cs/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat třída


Reprezentuje možnosti formátování pro [DataLabel](../datalabel/).

```cpp
class DataLabelFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::Charts::IDataLabelFormat
```

## Metody

| Metoda | Popis |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Porovnává se specifikovaným objektem. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro vnitřní použití. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Vrací graf. Jen pro čtení [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Reprezentuje formát datové štítku. Jen pro čtení [IFormat](../iformat/). |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Čte **bool**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | Reprezentuje formátový řetězec pro objekt DataLabels. Čte [System::String](../../system/string/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | Vrací objekt Parent_Immediate. Jen pro čtení [IDOMObject](../../aspose.slides/idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Vrací rodiče [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). Jen pro čtení [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() override | Reprezentuje pozici datové štítku. Čte [LegendDataLabelPosition](../legenddatalabelposition/). |
| [System::String](../../system/string/) [get_Separator](./get_separator/)() override | Nastavuje nebo vrací Variant představující oddělovač používaný pro datové štítky v grafu. Čte [System::String](../../system/string/). |
| **bool** [get_ShowBubbleSize](./get_showbubblesize/)() override | Reprezentuje chování zobrazení hodnoty velikosti bubliny datové štítky určeného grafu. True zobrazí hodnotu velikosti bubliny. False skryje. Čte **bool**. |
| **bool** [get_ShowCategoryName](./get_showcategoryname/)() override | Reprezentuje chování zobrazení názvu kategorie datové štítky určeného grafu. True zobrazí název kategorie pro datové štítky v grafu. False skryje. Čte **bool**. |
| **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() override | Určuje, zda bude datová štítka určeného grafu zobrazena jako datový výkřik nebo jako datová štítek. |
| **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() override | Reprezentuje chování zobrazení hodnoty buňky datové štítky určeného grafu. True zobrazí hodnotu buňky. False skryje. Čte **bool**. |
| **bool** [get_ShowLeaderLines](./get_showleaderlines/)() override | Reprezentuje chování zobrazení vodicích čar datové štítky určeného grafu. True zobrazí vodicí čáry. False skryje. Čte **bool**. |
| **bool** [get_ShowLegendKey](./get_showlegendkey/)() override | Reprezentuje chování zobrazení klíče legendy datové štítky. True pokud je klíč legendy datové štítky viditelný. Čte **bool**. |
| **bool** [get_ShowPercentage](./get_showpercentage/)() override | Reprezentuje chování zobrazení procentuální hodnoty datové štítky. True zobrazí procentuální hodnotu. False skryje. Čte **bool**. |
| **bool** [get_ShowSeriesName](./get_showseriesname/)() override | Vrací Boolean, který určuje chování zobrazení názvu řady pro datové štítky v grafu. True pro zobrazení názvu řady. False skryje. Čte **bool**. |
| **bool** [get_ShowValue](./get_showvalue/)() override | Reprezentuje chování zobrazení procentuální hodnoty datové štítky. True zobrazí procentuální hodnotu. False skryje. Čte **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Vrací formát textu grafu. Jen pro čtení [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu čítače referencí spojenou s objektem. |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | Vrací hash kód. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte sentinel objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenci hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Zapíše **bool**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | Reprezentuje formátový řetězec pro objekt DataLabels. Zapíše [System::String](../../system/string/). |
| void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) override | Reprezentuje pozici datové štítky. Zapíše [LegendDataLabelPosition](../legenddatalabelposition/). |
| void [set_Separator](./set_separator/)([System::String](../../system/string/)) override | Nastavuje nebo vrací Variant představující oddělovač používaný pro datové štítky v grafu. Zapíše [System::String](../../system/string/). |
| void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) override | Reprezentuje chování zobrazení hodnoty velikosti bubliny datové štítky určeného grafu. True zobrazí hodnotu velikosti bubliny. False skryje. Zapíše **bool**. |
| void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) override | Reprezentuje chování zobrazení názvu kategorie datové štítky určeného grafu. True zobrazí název kategorie pro datové štítky v grafu. False skryje. Zapíše **bool**. |
| void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) override | Určuje, zda bude datová štítka určeného grafu zobrazena jako datový výkřik nebo jako štítek. |
| void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) override | Reprezentuje chování zobrazení hodnoty buňky datové štítky určeného grafu. True zobrazí hodnotu buňky. False skryje. Zapíše **bool**. |
| void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) override | Reprezentuje chování zobrazení vodicích čar datové štítky určeného grafu. True zobrazí vodicí čáry. False skryje. Zapíše **bool**. |
| void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) override | Reprezentuje chování zobrazení klíče legendy datové štítky. True pokud je klíč legendy datové štítky viditelný. Zapíše **bool**. |
| void [set_ShowPercentage](./set_showpercentage/)(**bool**) override | Reprezentuje chování zobrazení procentuální hodnoty datové štítky. True zobrazí procentuální hodnotu. False skryje. Zapíše **bool**. |
| void [set_ShowSeriesName](./set_showseriesname/)(**bool**) override | Nastavuje Boolean, který určuje chování zobrazení názvu řady pro datové štítky v grafu. True pro zobrazení názvu řady. False skryje. Zapíše **bool**. |
| void [set_ShowValue](./set_showvalue/)(**bool**) override | Reprezentuje chování zobrazení procentuální hodnoty datové štítky. True zobrazí procentuální hodnotu. False skryje. Zapíše **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako weak pointer (namísto shared). Umožňuje přepínání ukazatelů v kontejnerech do weak režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock(). Zavolejte přímo nebo použijte sentinel objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje weak čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje weak čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [PVIObject](../../aspose.slides/pviobject/)
* Třída [IDataLabelFormat](../idatalabelformat/)
* Jmenný prostor [Aspose::Slides::Charts](../)
* Knihovna [Aspose.Slides](../../)