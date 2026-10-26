---
title: SlideShowSettings
second_title: Aspose.Slides pro C++ API Reference
description: Reprezentuje nastavení promítání snímků pro prezentaci.
type: docs
weight: 5214
url: /cs/aspose.slides/slideshowsettings/
---
## SlideShowSettings třída


Reprezentuje nastavení promítání snímků pro prezentaci.

```cpp
class SlideShowSettings : public System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro vnitřní použití. |
| **bool** [get_Loop](./get_loop/)() | Smyčka [Slide](../slide/) Promítání |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_PenColor](./get_pencolor/)() | Barva pera pro [Slide](../slide/) promítání |
| **bool** [get_ShowAnimation](./get_showanimation/)() | Promítání [Animation](../../aspose.slides.animation/) v [Slide](../slide/) promítání |
| **bool** [get_ShowMediaControls](./get_showmediacontrols/)() const | Zobrazit ovládací prvky médií |
| **bool** [get_ShowNarration](./get_shownarration/)() | Promítání vyprávění v [Slide](../slide/) promítání |
| [System::SharedPtr](../../system/sharedptr/)\<[SlidesRange](../slidesrange/)\> [get_Slides](./get_slides/)() const | [Slides](../) rozsah |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::SlideShowType](../slideshowtype/)\> [get_SlideShowType](./get_slideshowtype/)() | Získá typ promítání snímků. Reprezentován následujícími [SlideShowType](../slideshowtype/) předky: [BrowsedAtKiosk](../browsedatkiosk/), [PresentedBySpeaker](../presentedbyspeaker/) a [BrowsedByIndividual](../browsedbyindividual/). |
| **bool** [get_UseTimings](./get_usetimings/)() | Použít načasování v [Slide](../slide/) promítání |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání příkazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopiovací konstruktor. Vlastně nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování konstruktorů podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Vlastně nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování konstruktorů podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| void [set_Loop](./set_loop/)(**bool**) | Smyčka [Slide](../slide/) Promítání |
| void [set_ShowAnimation](./set_showanimation/)(**bool**) | Promítání [Animation](../../aspose.slides.animation/) v [Slide](../slide/) promítání |
| void [set_ShowMediaControls](./set_showmediacontrols/)(**bool**) | Zobrazit ovládací prvky médií |
| void [set_ShowNarration](./set_shownarration/)(**bool**) | Promítání vyprávění v [Slide](../slide/) promítání |
| void [set_Slides](./set_slides/)([System::SharedPtr](../../system/sharedptr/)\<[SlidesRange](../slidesrange/)\>) | [Slides](../) rozsah |
| void [set_SlideShowType](./set_slideshowtype/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::SlideShowType](../slideshowtype/)\>) | Nastaví typ promítání snímků. Reprezentován následujícími [SlideShowType](../slideshowtype/) předky: [BrowsedAtKiosk](../browsedatkiosk/), [PresentedBySpeaker](../presentedbyspeaker/) a [BrowsedByIndividual](../browsedbyindividual/). |
| void [set_UseTimings](./set_usetimings/)(**bool**) | Použít načasování v [Slide](../slide/) promítání |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemykání příkazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)