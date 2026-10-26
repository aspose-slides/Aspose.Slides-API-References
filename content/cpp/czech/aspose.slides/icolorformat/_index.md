---
title: IColorFormat
second_title: Aspose.Slides pro C++ referenční příručka API
description: Reprezentuje barvu používanou v prezentaci.
type: docs
weight: 1691
url: /cs/aspose.slides/icolorformat/
---
## IColorFormat třída


Reprezentuje barvu používanou v prezentaci.

```cpp
class IColorFormat : public Aspose::Slides::IFillParamSource
```

## Metody

| Method | Description |
| --- | --- |
| virtual void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](./)\>) | Zkopíruje formát barvy z \"color\". |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnoty ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual **uint8_t** [get_B](./get_b/)() | Vrací modrou složku barvy. Všechny transformace barev jsou ignorovány. Čtení **uint8_t**. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() | Vrací výslednou barvu (s aplikovanými všemi transformacemi barev). Nastavuje RGB barvy a maže všechny transformace barev. Čtení [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) | Vrací operaci transformace barvy aplikovanou na barvu na zadaném indexu. Čtení/zápis [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() | Vrací kolekci transformací barev aplikovaných na barvu. Pouze pro čtení [IColorOperationCollection](../icoloroperationcollection/). |
| virtual [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() | Vrací metodu definice barvy. Čtení [Slides::ColorType](../colortype/). |
| virtual **float** [get_FloatB](./get_floatb/)() | Vrací modrou složku barvy. Všechny transformace barev jsou ignorovány. Čtení **float**. |
| virtual **float** [get_FloatG](./get_floatg/)() | Vrací zelenou složku barvy. Všechny transformace barev jsou ignorovány. Čtení **float**. |
| virtual **float** [get_FloatR](./get_floatr/)() | Vrací červenou složku barvy. Všechny transformace barev jsou ignorovány. Čtení **float**. |
| virtual **uint8_t** [get_G](./get_g/)() | Vrací zelenou složku barvy. Všechny transformace barev jsou ignorovány. Čtení **uint8_t**. |
| virtual **float** [get_Hue](./get_hue/)() | Vrací odstín (hue) barvy v reprezentaci HSL. Všechny transformace barev jsou ignorovány. Čtení **float**. |
| virtual **float** [get_Luminance](./get_luminance/)() | Vrací luminanci barvy v reprezentaci HSL. Všechny transformace barev jsou ignorovány. Čtení **float**. |
| virtual [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() | Vrací přednastavenou barvu. Čtení [Slides::PresetColor](../presetcolor/). |
| virtual **uint8_t** [get_R](./get_r/)() | Vrací červenou složku barvy. Všechny transformace barev jsou ignorovány. Čtení **uint8_t**. |
| virtual **float** [get_Saturation](./get_saturation/)() | Vrací saturaci barvy v reprezentaci HSL. Všechny transformace barev jsou ignorovány. Čtení **float**. |
| virtual [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() | Vrací barvu identifikovanou barvou ze schématu. Čtení [Slides::SchemeColor](../schemecolor/). |
| virtual [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() | Vrací barvu identifikovanou systémovou tabulkou barev. Čtení [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování konstruktorů podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování konstruktorů podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenci objektu typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje počítadlo sdílených referencí o zadanou hodnotu. |
| virtual void [set_B](./set_b/)(**uint8_t**) | Nastavuje modrou složku barvy. Všechny transformace barev jsou ignorovány. Zápis **uint8_t**. |
| virtual void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) | Vrací výslednou barvu (s aplikovanými všemi transformacemi barev). Nastavuje RGB barvy a maže všechny transformace barev. Zápis [System::Drawing::Color](../../system.drawing/color/). |
| virtual void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) | Nastaví operaci transformace barvy aplikovanou na barvu na zadaném indexu. Čtení/zápis [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) | Nastavuje metodu definice barvy. Zápis [Slides::ColorType](../colortype/). |
| virtual void [set_FloatB](./set_floatb/)(**float**) | Nastavuje modrou složku barvy. Všechny transformace barev jsou ignorovány. Zápis **float**. |
| virtual void [set_FloatG](./set_floatg/)(**float**) | Nastavuje zelenou složku barvy. Všechny transformace barev jsou ignorovány. Zápis **float**. |
| virtual void [set_FloatR](./set_floatr/)(**float**) | Nastavuje červenou složku barvy. Všechny transformace barev jsou ignorovány. Zápis **float**. |
| virtual void [set_G](./set_g/)(**uint8_t**) | Nastavuje zelenou složku barvy. Všechny transformace barev jsou ignorovány. Zápis **uint8_t**. |
| virtual void [set_Hue](./set_hue/)(**float**) | Nastavuje odstín (hue) barvy v reprezentaci HSL. Všechny transformace barev jsou ignorovány. Zápis **float**. |
| virtual void [set_Luminance](./set_luminance/)(**float**) | Nastavuje luminanci barvy v reprezentaci HSL. Všechny transformace barev jsou ignorovány. Zápis **float**. |
| virtual void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) | Nastavuje přednastavenou barvu. Zápis [Slides::PresetColor](../presetcolor/). |
| virtual void [set_R](./set_r/)(**uint8_t**) | Nastavuje červenou složku barvy. Všechny transformace barev jsou ignorovány. Zápis **uint8_t**. |
| virtual void [set_Saturation](./set_saturation/)(**float**) | Nastavuje saturaci barvy v reprezentaci HSL. Všechny transformace barev jsou ignorovány. Zápis **float**. |
| virtual void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) | Nastavuje barvu identifikovanou barvou ze schématu. Zápis [Slides::SchemeColor](../schemecolor/). |
| virtual void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) | Nastavuje barvu identifikovanou systémovou tabulkou barev. Zápis [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu počítadla sdílených referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje počítadlo sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací počítadlo sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) | Vrací [System::String](../../system/string/) představující aktuální formát barvy. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje počítadlo slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje počítadlo slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny interní datové struktury. |
## Viz také

* Třída [IFillParamSource](../ifillparamsource/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)