---
title: IChartDataCell
second_title: Aspose.Slides pro C++ - API reference
description: Reprezentuje buňku pro data grafu.
type: docs
weight: 664
url: /cs/aspose.slides.charts/ichartdatacell/
---
## IChartDataCell třída


Represents cell for chart data.

```cpp
class IChartDataCell : public virtual System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual void [Calculate](./calculate/)(**bool**) | Pokud buňka obsahuje vzorec, hodnota bude aktualizována na základě tohoto vzorce. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání desetinných čísel ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání desetinných čísel ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorksheet](../ichartdataworksheet/)\> [get_ChartDataWorksheet](./get_chartdataworksheet/)() | Získá list. Pouze pro čtení [IChartDataWorksheet](../ichartdataworksheet/). |
| virtual **int32_t** [get_Column](./get_column/)() | Vrací index sloupce listu, ve kterém je buňka umístěna. Pouze pro čtení **int32_t**. |
| virtual [System::String](../../system/string/) [get_CustomNumberFormat](./get_customnumberformat/)() | Získá vlastní formát zobrazení čísel a datumů. Pokud je hodnota prázdná, bude použita hodnota PresetNumberFormat. Čtení [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Formula](./get_formula/)() | Získá vzorec ve stylu A1. |
| virtual **bool** [get_IsHidden](./get_ishidden/)() | Určuje, zda je buňka skrytá. Pouze pro čtení **bool**. |
| virtual **uint8_t** [get_PresetNumberFormat](./get_presetnumberformat/)() | Získá vestavěný formát zobrazení čísel a datumů. Přednastavené číslo musí být v rozmezí [0..22] nebo [37..49]. Pouze pro čtení **uint8_t**. |
| virtual [System::String](../../system/string/) [get_R1C1Formula](./get_r1c1formula/)() | Získá vzorec ve stylu R1C1. |
| virtual **int32_t** [get_Row](./get_row/)() | Vrací index řádku listu, ve kterém je buňka umístěna. Pouze pro čtení **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Value](./get_value/)() | Získá hodnotu buňky. Čtení [System::Object](../../system/object/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu reference counteru spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog C# operátoru 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání C# příkazem lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenčně objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží počet sdílených referencí o zadanou hodnotu. |
| virtual void [set_CustomNumberFormat](./set_customnumberformat/)([System::String](../../system/string/)) | Nastaví vlastní formát zobrazení čísel a datumů. Pokud je hodnota prázdná, bude použita hodnota PresetNumberFormat. Zápis [System::String](../../system/string/). |
| virtual void [set_Formula](./set_formula/)([System::String](../../system/string/)) | Nastaví vzorec ve stylu A1. |
| virtual void [set_PresetNumberFormat](./set_presetnumberformat/)(**uint8_t**) | Nastaví vestavěný formát zobrazení čísel a datumů. Přednastavené číslo musí být v rozmezí [0..22] nebo [37..49]. Zápis **uint8_t**. |
| virtual void [set_R1C1Formula](./set_r1c1formula/)([System::String](../../system/string/)) | Nastaví vzorec ve stylu R1C1. |
| virtual void [set_Value](./set_value/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Nastaví hodnotu buňky. Zápis [System::Object](../../system/object/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument na slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu počitadla sdílených referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje počet sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací počet sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení C# příkazem lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje počet slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje počet slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)