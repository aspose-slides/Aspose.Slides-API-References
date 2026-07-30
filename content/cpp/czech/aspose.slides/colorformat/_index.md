---
title: ColorFormat
second_title: Aspose.Slides pro C++ referenční příručka API
description: Representuje barvu použitou v prezentaci.
type: docs
weight: 339
url: /cs/aspose.slides/colorformat/
---
## ColorFormat třída

Represents a color used in a presentation.

```cpp
class ColorFormat : public Aspose::Slides::PVIObject,
                    public Aspose::Slides::IColorFormat
```

## Metody

| Metoda | Popis |
| --- | --- |
| void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\>) override | Copy color format from "color". |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Kontroluje rovnost se zadaným objektem. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) semantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Napodobuje porovnání v plovoucí řádové čárce ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Napodobuje porovnání v plovoucí řádové čárce ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| **uint8_t** [get_B](./get_b/)() override | Vrátí modrou složku barvy. Všechny transformace barev jsou ignorovány. Čtení **uint8_t**. |
| [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() override | Vrátí výslednou barvu (se všemi aplikovanými transformacemi barev). Nastaví RGB barvy a vymaže všechny transformace barev. Čtení [System::Drawing::Color](../../system.drawing/color/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) override | Vrátí operaci transformace barvy aplikovanou na barvu na zadaném indexu. Čtení/zápis [Aspose::Slides::IColorOperation](../icoloroperation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() override | Vrátí kolekci transformací barev aplikovaných na barvu. Pouze pro čtení [IColorOperationCollection](../icoloroperationcollection/). |
| [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() override | Vrátí metodu definice barvy. Čtení [Slides::ColorType](../colortype/). |
| **float** [get_FloatB](./get_floatb/)() override | Vrátí modrou složku barvy. Všechny transformace barev jsou ignorovány. Čtení **float**. |
| **float** [get_FloatG](./get_floatg/)() override | Vrátí zelenou složku barvy. Všechny transformace barev jsou ignorovány. Čtení **float**. |
| **float** [get_FloatR](./get_floatr/)() override | Vrátí červenou složku barvy. Všechny transformace barev jsou ignorovány. Čtení **float**. |
| **uint8_t** [get_G](./get_g/)() override | Vrátí zelenou složku barvy. Všechny transformace barev jsou ignorovány. |
| **float** [get_Hue](./get_hue/)() override | Vrátí odstín (hue) barvy v reprezentaci HSL. Všechny transformace barev jsou ignorovány. Čtení **float**. |
| **float** [get_Luminance](./get_luminance/)() override | Vrátí luminanci barvy v reprezentaci HSL. Všechny transformace barev jsou ignorovány. Čtení **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Vrátí objekt Parent_Immediate. Pouze pro čtení [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Vrátí nadřazený [IPresentationComponent](../ipresentationcomponent/). Pouze pro čtení [IPresentationComponent](../ipresentationcomponent/). |
| [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() override | Vrátí přednastavenou barvu. Čtení [Slides::PresetColor](../presetcolor/). |
| **uint8_t** [get_R](./get_r/)() override | Vrátí červenou složku barvy. Všechny transformace barev jsou ignorovány. Čtení **uint8_t**. |
| **float** [get_Saturation](./get_saturation/)() override | Vrátí sytost barvy v reprezentaci HSL. Všechny transformace barev jsou ignorovány. Čtení **float**. |
| [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() override | Vrátí barvu identifikovanou barevným schématem. Čtení [Slides::SchemeColor](../schemecolor/). |
| [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() override | Vrátí barvu identifikovanou systémovou tabulkou barev. Čtení [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu čítače referencí spojenou s objektem. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Vrátí hash kód. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie k volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie k operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání podle C# lock() příkazu. Volá se přímo nebo použijte [LockContext](../../system/lockcontext/) sentinelní objekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie k metodě C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenčně hodnotový typ objektu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| void [set_B](./set_b/)(**uint8_t**) override | Nastaví modrou složku barvy. Všechny transformace barev jsou ignorovány. Zápis **uint8_t**. |
| void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) override | Vrátí výslednou barvu (se všemi aplikovanými transformacemi barev). Nastaví RGB barvy a vymaže všechny transformace barev. Zápis [System::Drawing::Color](../../system.drawing/color/). |
| void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) override | Nastaví operaci transformace barvy aplikovanou na barvu na zadaném indexu. Čtení/zápis [Aspose::Slides::IColorOperation](../icoloroperation/) |
| void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) override | Nastaví metodu definice barvy. Zápis [Slides::ColorType](../colortype/). |
| void [set_FloatB](./set_floatb/)(**float**) override | Nastaví modrou složku barvy. Všechny transformace barev jsou ignorovány. Zápis **float**. |
| void [set_FloatG](./set_floatg/)(**float**) override | Nastaví zelenou složku barvy. Všechny transformace barev jsou ignorovány. Zápis **float**. |
| void [set_FloatR](./set_floatr/)(**float**) override | Nastaví červenou složku barvy. Všechny transformace barev jsou ignorovány. Zápis **float**. |
| void [set_G](./set_g/)(**uint8_t**) override | Nastaví zelenou složku barvy. Všechny transformace barev jsou ignorovány. |
| void [set_Hue](./set_hue/)(**float**) override | Nastaví odstín (hue) barvy v reprezentaci HSL. Všechny transformace barev jsou ignorovány. Zápis **float**. |
| void [set_Luminance](./set_luminance/)(**float**) override | Nastaví luminanci barvy v reprezentaci HSL. Všechny transformace barev jsou ignorovány. Zápis **float**. |
| void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) override | Nastaví přednastavenou barvu. Zápis [Slides::PresetColor](../presetcolor/). |
| void [set_R](./set_r/)(**uint8_t**) override | Nastaví červenou složku barvy. Všechny transformace barev jsou ignorovány. Zápis **uint8_t**. |
| void [set_Saturation](./set_saturation/)(**float**) override | Nastaví sytost barvy v reprezentaci HSL. Všechny transformace barev jsou ignorovány. Zápis **float**. |
| void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) override | Nastaví barvu identifikovanou barevným schématem. Zápis [Slides::SchemeColor](../schemecolor/). |
| void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) override | Nastaví barvu identifikovanou systémovou tabulkou barev. Zápis [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) override | Vrátí [System::String](../../system/string/), který představuje aktuální formát barvy. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie k metodě C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí dle C# lock() příkazu. Volá se přímo nebo použijte [LockContext](../../system/lockcontext/) sentinelní objekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [PVIObject](../pviobject/)
* Třída [IColorFormat](../icolorformat/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)