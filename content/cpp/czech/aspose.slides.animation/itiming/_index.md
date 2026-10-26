---
title: ITiming
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Reprezentuje časování animace.
type: docs
weight: 443
url: /cs/aspose.slides.animation/itiming/
---
## ITiming třída

Represents animation timing.

```cpp
class ITiming : public virtual System::Object
```

## Metody

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) sémantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za stejné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s dvojitou přesností ve stylu C#, kde jsou dvě NaN považovány za stejné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual **float** [get_Accelerate](./get_accelerate/)() | Popisuje procento trvání efektu zrychlovacího chování. Čte se **float**. |
| virtual **bool** [get_AutoReverse](./get_autoreverse/)() | Popisuje, zda se animace po přehrání v dopředném směru automaticky přehraje v opačném směru. Čte se **bool**. |
| virtual **float** [get_Decelerate](./get_decelerate/)() | Popisuje procento trvání efektu zpomalovacího chování. Čte se **float**. |
| virtual **float** [get_Duration](./get_duration/)() | Popisuje trvání efektu animace. Čte se **float**. |
| virtual **float** [get_RepeatCount](./get_repeatcount/)() | Popisuje počet opakování efektu. Čte se **float**. |
| virtual **float** [get_RepeatDuration](./get_repeatduration/)() | Popisuje počet opakování efektu. Čte se **float**. |
| virtual **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() | Tento atribut určuje, zda se efekt bude opakovat až do konce snímku. Čte se **bool**. |
| virtual **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() | Tento atribut určuje, zda se efekt bude opakovat až do dalšího kliknutí. Čte se **bool**. |
| virtual [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() | Určuje, zda se efekt má restartovat po dokončení. Čte se [EffectRestartType](../effectrestarttype/). |
| virtual **bool** [get_Rewind](./get_rewind/)() | Tento atribut určuje, zda se efekt po přehrání přetočí zpět. Čte se **bool**. |
| virtual **float** [get_Speed](./get_speed/)() | Určuje procento, o které se má časování zrychlit (nebo zpomalit). Čte se **float**. |
| virtual **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() | Popisuje dobu zpoždění po spuštění. Čte se **float**. |
| virtual [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() | Popisuje typ spouštěče. Čte se [EffectTriggerType](../effecttriggertype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() příkazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje konstrukci kopií podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje konstrukci kopií podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| virtual void [set_Accelerate](./set_accelerate/)(**float**) | Popisuje procento trvání efektu zrychlovacího chování. Zapíše se **float**. |
| virtual void [set_AutoReverse](./set_autoreverse/)(**bool**) | Popisuje, zda se animace po přehrání vpřed automaticky přehraje v opačném směru. Zapíše se **bool**. |
| virtual void [set_Decelerate](./set_decelerate/)(**float**) | Popisuje procento trvání efektu zpomalovacího chování. Zapíše se **float**. |
| virtual void [set_Duration](./set_duration/)(**float**) | Popisuje trvání efektu animace. Zapíše se **float**. |
| virtual void [set_RepeatCount](./set_repeatcount/)(**float**) | Popisuje počet opakování efektu. Zapíše se **float**. |
| virtual void [set_RepeatDuration](./set_repeatduration/)(**float**) | Popisuje počet opakování efektu. Zapíše se **float**. |
| virtual void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) | Tento atribut určuje, zda se efekt bude opakovat až do konce snímku. Zapíše se **bool**. |
| virtual void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) | Tento atribut určuje, zda se efekt bude opakovat až do dalšího kliknutí. Zapíše se **bool**. |
| virtual void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) | Určuje, zda se efekt má restartovat po dokončení. Zapíše se [EffectRestartType](../effectrestarttype/). |
| virtual void [set_Rewind](./set_rewind/)(**bool**) | Tento atribut určuje, zda se efekt po přehrání přetočí zpět. Zapíše se **bool**. |
| virtual void [set_Speed](./set_speed/)(**float**) | Určuje procento, o které se má časování zrychlit (nebo zpomalit). Zapíše se **float**. |
| virtual void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) | Popisuje dobu zpoždění po spuštění. Zapíše se **float**. |
| virtual void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) | Popisuje typ spouštěče. Zapíše se [EffectTriggerType](../effecttriggertype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock() příkazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolňuje všechny vnitřní datové struktury. |

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [Aspose::Slides::Animation](../)
* Knihovna [Aspose.Slides](../../)