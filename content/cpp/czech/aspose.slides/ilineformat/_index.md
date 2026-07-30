---
title: ILineFormat
second_title: Aspose.Slides pro C++ referenční příručka API
description: Reprezentuje formát čáry.
type: docs
weight: 2757
url: /cs/aspose.slides/ilineformat/
---
## ILineFormat třída

Reprezentuje formát čáry.

```cpp
class ILineFormat : public Aspose::Slides::ILineParamSource
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](./)\>) | Určuje, zda jsou dvě instance [LineFormat](../lineformat/) rovny. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual [LineAlignment](../linealignment/) [get_Alignment](./get_alignment/)() | Vrací zarovnání čáry. Čtěte [LineAlignment](../linealignment/). |
| virtual [LineArrowheadLength](../linearrowheadlength/) [get_BeginArrowheadLength](./get_beginarrowheadlength/)() | Vrací délku špičky šipky na začátku čáry. Čtěte [LineArrowheadLength](../linearrowheadlength/). |
| virtual [LineArrowheadStyle](../linearrowheadstyle/) [get_BeginArrowheadStyle](./get_beginarrowheadstyle/)() | Vrací styl špičky šipky na začátku čáry. Čtěte [LineArrowheadStyle](../linearrowheadstyle/). |
| virtual [LineArrowheadWidth](../linearrowheadwidth/) [get_BeginArrowheadWidth](./get_beginarrowheadwidth/)() | Vrací šířku špičky šipky na začátku čáry. Čtěte [LineArrowheadWidth](../linearrowheadwidth/). |
| virtual [LineCapStyle](../linecapstyle/) [get_CapStyle](./get_capstyle/)() | Vrací styl zakončení čáry. Čtěte [LineCapStyle](../linecapstyle/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CustomDashPattern](./get_customdashpattern/)() | Vrací vlastní vzor čárkování. Čtěte **float**[]. |
| virtual [LineDashStyle](../linedashstyle/) [get_DashStyle](./get_dashstyle/)() | Vrací styl čárkování čáry. Čtěte [LineDashStyle](../linedashstyle/). |
| virtual [LineArrowheadLength](../linearrowheadlength/) [get_EndArrowheadLength](./get_endarrowheadlength/)() | Vrací délku špičky šipky na konci čáry. Čtěte [LineArrowheadLength](../linearrowheadlength/). |
| virtual [LineArrowheadStyle](../linearrowheadstyle/) [get_EndArrowheadStyle](./get_endarrowheadstyle/)() | Vrací styl špičky šipky na konci čáry. Čtěte [LineArrowheadStyle](../linearrowheadstyle/). |
| virtual [LineArrowheadWidth](../linearrowheadwidth/) [get_EndArrowheadWidth](./get_endarrowheadwidth/)() | Vrací šířku špičky šipky na konci čáry. Čtěte [LineArrowheadWidth](../linearrowheadwidth/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFillFormat](../ilinefillformat/)\> [get_FillFormat](./get_fillformat/)() | Vrací formát výplně čáry. Pouze pro čtení [ILineFillFormat](../ilinefillformat/). |
| virtual **bool** [get_IsFormatNotDefined](./get_isformatnotdefined/)() | Vrací pravdu, pokud formát čáry není definován (právě vytvořený, výchozí). Pouze pro čtení **bool**. |
| virtual [LineJoinStyle](../linejoinstyle/) [get_JoinStyle](./get_joinstyle/)() | Vrací styl spojení čar. Čtěte [LineJoinStyle](../linejoinstyle/). |
| virtual **float** [get_MiterLimit](./get_miterlimit/)() | Vrací limit šikmého řezu čáry. Čtěte **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISketchFormat](../isketchformat/)\> [get_SketchFormat](./get_sketchformat/)() | Vrací formát skici čáry. Pouze pro čtení [ISketchFormat](../isketchformat/). |
| virtual [LineStyle](../linestyle/) [get_Style](./get_style/)() | Vrací styl čáry. Čtěte [LineStyle](../linestyle/). |
| virtual **double** [get_Width](./get_width/)() | Vrací šířku čáry. Čtěte **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [GetEffective](./geteffective/)() | Získá efektivní data formátování čáry s aplikovaným děděním. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte strážný objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží počítadlo sdílených referencí o zadanou hodnotu. |
| virtual void [set_Alignment](./set_alignment/)([LineAlignment](../linealignment/)) | Nastavuje zarovnání čáry. Zapište [LineAlignment](../linealignment/). |
| virtual void [set_BeginArrowheadLength](./set_beginarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) | Nastavuje délku špičky šipky na začátku čáry. Zapište [LineArrowheadLength](../linearrowheadlength/). |
| virtual void [set_BeginArrowheadStyle](./set_beginarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) | Nastavuje styl špičky šipky na začátku čáry. Zapište [LineArrowheadStyle](../linearrowheadstyle/). |
| virtual void [set_BeginArrowheadWidth](./set_beginarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) | Nastavuje šířku špičky šipky na začátku čáry. Zapište [LineArrowheadWidth](../linearrowheadwidth/). |
| virtual void [set_CapStyle](./set_capstyle/)([LineCapStyle](../linecapstyle/)) | Nastavuje styl zakončení čáry. Zapište [LineCapStyle](../linecapstyle/). |
| virtual void [set_CustomDashPattern](./set_customdashpattern/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) | Nastavuje vlastní vzor čárkování. Zapište **float**[]. |
| virtual void [set_DashStyle](./set_dashstyle/)([LineDashStyle](../linedashstyle/)) | Nastavuje styl čárkování čáry. Zapište [LineDashStyle](../linedashstyle/). |
| virtual void [set_EndArrowheadLength](./set_endarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) | Nastavuje délku špičky šipky na konci čáry. Zapište [LineArrowheadLength](../linearrowheadlength/). |
| virtual void [set_EndArrowheadStyle](./set_endarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) | Nastavuje styl špičky šipky na konci čáry. Zapište [LineArrowheadStyle](../linearrowheadstyle/). |
| virtual void [set_EndArrowheadWidth](./set_endarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) | Nastavuje šířku špičky šipky na konci čáry. Zapište [LineArrowheadWidth](../linearrowheadwidth/). |
| virtual void [set_JoinStyle](./set_joinstyle/)([LineJoinStyle](../linejoinstyle/)) | Nastavuje styl spojení čar. Zapište [LineJoinStyle](../linejoinstyle/). |
| virtual void [set_MiterLimit](./set_miterlimit/)(**float**) | Nastavuje limit šikmého řezu čáry. Zapište **float**. |
| virtual void [set_Style](./set_style/)([LineStyle](../linestyle/)) | Nastavuje styl čáry. Zapište [LineStyle](../linestyle/). |
| virtual void [set_Width](./set_width/)(**double**) | Nastavuje šířku čáry. Zapište **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu počítadla sdílených referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje počítadlo sdílených referencí. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací počítadlo sdílených referencí. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock(). Zavolejte přímo nebo použijte strážný objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje počítadlo slabých referencí. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje počítadlo slabých referencí. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [ILineParamSource](../ilineparamsource/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)