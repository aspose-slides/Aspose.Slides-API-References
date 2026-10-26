---
title: DataLabel
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Reprezentuje popisky řady.
type: docs
weight: 365
url: /cs/aspose.slides.charts/datalabel/
---
## DataLabel třída


Represents a series labels.

```cpp
class DataLabel : public Aspose::Slides::Charts::IDataLabel,
                  public Aspose::Slides::IDOMObject
```

## Metody

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Inicializuje TextFrameForOverriding textem v parametru "text". Pokud je TextFrameForOverriding již inicializován, jednoduše změní jeho text. |
|  [DataLabel](./datalabel/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) | Vytvoří novou instanci třídy [DataLabel](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí řádovou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí řádovou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Určuje skutečnou výšku elementu grafu. Předtím zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/) pro získání skutečných hodnot. Čte se **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Určuje skutečnou šířku elementu grafu. Předtím zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/) pro získání skutečných hodnot. Čte se **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Určuje skutečnou souřadnici x (levý okraj) elementu grafu vzhledem k levému hornímu rohu grafu. Předtím zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/) pro získání skutečných hodnot. Čte se **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Určuje skutečnou horní část elementu grafu vzhledem k levému hornímu rohu grafu. Předtím zavolejte metodu [IChart::ValidateChartLayout](../ichart/validatechartlayout/) pro získání skutečných hodnot. Čte se **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Spodní část. Pouze ke čtení **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Vrací nadřazený graf. Pouze ke čtení [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() override | Vrací formát popisku dat. Pouze ke čtení [IDataLabelFormat](../idatalabelformat/). |
| **float** [get_Height](./get_height/)() override | Vrací výšku nadpisu jako zlomek výšky grafu. Čte se **float**. |
| **bool** [get_IsVisible](./get_isvisible/)() override | False znamená, že popisek dat není viditelný (a všechny příznaky Show* (ShowValue, ...) jsou také false). Pouze ke čtení **bool**. |
| **float** [get_Right](./get_right/)() override | Vpravo. Pouze ke čtení **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Vrací formát textu. Pouze ke čtení [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Může obsahovat bohatě formátovaný text. Pokud není tato vlastnost null, hodnota tohoto formátovaného textu přepíše automaticky generovaný text popisku dat. Automaticky generovaný text popisku dat znamená text spravovaný pomocí vlastností ShowSeriesName, ShowValue, … a formátovaný pomocí vlastnosti TextFormatManager.TextFormat. Pouze ke čtení [ITextFrame](../../aspose.slides/itextframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() override | Získá buňku dat sešitu. Použije se, pokud je vlastnost IDataLabelFormat::get(set)_ShowLabelValueFromCell nastavena na true. |
| **float** [get_Width](./get_width/)() override | Vrací šířku nadpisu jako zlomek šířky grafu. Čte se **float**. |
| **float** [get_X](./get_x/)() override | Vrací souřadnici x nadpisu jako zlomek šířky grafu. Čte se **float**. |
| **float** [get_Y](./get_y/)() override | Vrací souřadnici y nadpisu jako zlomek výšky grafu. Čte se **float**. |
| [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() override | Vrací skutečný text popisku na základě nastavení [DataLabelFormat](../datalabelformat/) nebo hodnoty [get_TextFrameForOverriding()](./get_textframeforoverriding/)->get(set)_Text(). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu čítače reference spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Hide](./hide/)() override | Skryje popisek dat nastavením všech příznaků Show* (ShowValue, ...) na false. IsVisible bude po tomto false. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje uzamčení pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí hodnotový typ objektu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| void [set_Height](./set_height/)(**float**) override | Nastaví výšku nadpisu jako zlomek výšky grafu. Zapište **float**. |
| void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) override | Nastaví buňku dat sešitu. Použije se, pokud je vlastnost IDataLabelFormat::get(set)_ShowLabelValueFromCell nastavena na true. |
| void [set_Width](./set_width/)(**float**) override | Nastaví šířku nadpisu jako zlomek šířky grafu. Zapište **float**. |
| void [set_X](./set_x/)(**float**) override | Nastaví souřadnici x nadpisu jako zlomek šířky grafu. Zapište **float**. |
| void [set_Y](./set_y/)(**float**) override | Nastaví souřadnici y nadpisu jako zlomek výšky grafu. Zapište **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |
## Viz také

* Třída [IDataLabel](../idatalabel/)
* Třída [IDOMObject](../../aspose.slides/idomobject/)
* Jmenný prostor [Aspose::Slides::Charts](../)
* Knihovna [Aspose.Slides](../../)