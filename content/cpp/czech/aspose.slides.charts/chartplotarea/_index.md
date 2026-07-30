---
title: ChartPlotArea
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Reprezentuje obdélník, ve kterém má být graf vykreslen.
type: docs
weight: 248
url: /cs/aspose.slides.charts/chartplotarea/
---
## ChartPlotArea třída

Reprezentuje obdélník, ve kterém by měl být vykreslen graf.

```cpp
class ChartPlotArea : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                      public Aspose::Slides::Charts::IChartPlotArea
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) sémantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Určuje skutečnou výšku prvku grafu. Předtím zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/) pro získání aktuálních hodnot. Čte **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Určuje skutečnou šířku prvku grafu. Předtím zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/) pro získání aktuálních hodnot. Čte **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Určuje skutečnou souřadnici x (levá) prvku grafu vzhledem k levému hornímu rohu grafu. Předtím zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/) pro získání aktuálních hodnot. Čte **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Určuje skutečnou hodnotu horního okraje prvku grafu vzhledem k levému hornímu rohu grafu. Předtím zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/) pro získání aktuálních hodnot. Čte **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Spodní okraj. Pouze ke čtení **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | [Chart](../chart/). Pouze ke čtení [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Vrací formát oblasti vykreslování. Pouze ke čtení [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Vrací výšku ohraničujícího rámečku oblasti vykreslování jako podíl výšky grafu (od 0 do 1). Čte **float**. |
| **bool** [get_IsLocationAutocalculated](./get_islocationautocalculated/)() | Definuje, jak má být umístění vypočítáno: true – vypočítáno automaticky; definováno pomocí vlastností X, Y, Width, Height. Pouze ke čtení **bool**. |
| [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() override | Pokud je rozložení oblasti vykreslování definováno ručně, tato vlastnost určuje, zda rozvrhnout oblast podle jejího vnitřku (bez os a popisků os) nebo podle vnějšího okraje (včetně os a popisků os). Čte [LayoutTargetType](../layouttargettype/). |
| **float** [get_Right](./get_right/)() override | Pravý okraj. Pouze ke čtení **float**. |
| **float** [get_Width](./get_width/)() override | Vrací šířku ohraničujícího rámečku oblasti vykreslování jako podíl šířky grafu (od 0 do 1). Čte **float**. |
| **float** [get_X](./get_x/)() override | Vrací souřadnici x levého horního rohu ohraničujícího rámečku oblasti vykreslování jako podíl šířky grafu (od 0 do 1). Čte **float**. |
| **float** [get_Y](./get_y/)() override | Vrací souřadnici y levého horního rohu ohraničujícího rámečku oblasti vykreslování jako podíl výšky grafu (od 0 do 1). Čte **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování uživatelských objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ověří, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Vyvolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování uživatelských typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopiovací konstruktor. Ve skutečnosti nic nepřepisuje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nepřepisuje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje počítadlo sdílených referencí o zadanou hodnotu. |
| void [set_Height](./set_height/)(**float**) override | Nastavuje výšku ohraničujícího rámečku oblasti vykreslování jako podíl výšky grafu (od 0 do 1). Zapíše **float**. |
| void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) override | Pokud je rozložení oblasti vykreslování definováno ručně, tato vlastnost určuje, zda rozvrhnout oblast podle jejího vnitřku (bez os a popisků os) nebo podle vnějšího okraje (včetně os a popisků os). Zapíše [LayoutTargetType](../layouttargettype/). |
| void [set_Width](./set_width/)(**float**) override | Nastavuje šířku ohraničujícího rámečku oblasti vykreslování jako podíl šířky grafu (od 0 do 1). Zapíše **float**. |
| void [set_X](./set_x/)(**float**) override | Nastavuje souřadnici x levého horního rohu ohraničujícího rámečku oblasti vykreslování jako podíl šířky grafu (od 0 do 1). Zapíše **float**. |
| void [set_Y](./set_y/)(**float**) override | Nastavuje souřadnici y levého horního rohu ohraničujícího rámečku oblasti vykreslování jako podíl výšky grafu (od 0 do 1). Zapíše **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu počítadla sdílených referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje počítadlo sdílených referencí. Nemělo by být voláno přímo; použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací počítadlo sdílených referencí. Nemělo by být voláno přímo; použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod uživatelských objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení příkazu C# lock(). Vyvolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje počítadlo slabých referencí. Nemělo by být voláno přímo; použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje počítadlo slabých referencí. Nemělo by být voláno přímo; použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [DomObject](../../aspose.slides/domobject/)
* Třída [IChartPlotArea](../ichartplotarea/)
* Jmenný prostor [Aspose::Slides::Charts](../)
* Knihovna [Aspose.Slides](../../)