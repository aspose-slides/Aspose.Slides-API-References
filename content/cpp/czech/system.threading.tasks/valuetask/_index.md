---
title: ValueTask
second_title: Aspose.Slides pro C++ API Reference
description: Poskytuje výsledek asynchronní operace, na který lze čekat.
type: docs
weight: 92
url: /cs/system.threading.tasks/valuetask/
---
## ValueTask třída


Poskytuje výsledek asynchronní operace, na který lze čekat.

```cpp
class ValueTask : public System::IEquatable<ValueTask>,
                  public System::Details::BoxableObjectBase
```

## Metody

| Metoda | Popis |
| --- | --- |
| [TaskPtr](../../system/taskptr/) [AsTask](./astask/)() const | Převádí tento [ValueTask](./) na sdílený ukazatel na [Task](../task/). |
| [Runtime::CompilerServices::ConfiguredValueTaskAwaitable](../../system.runtime.compilerservices/configuredvaluetaskawaitable/) [ConfigureAwait](./configureawait/)(**bool**) const | Nastavuje awaiter pro tuto úlohu. |
| **bool** [Equals](./equals/)([ValueTask](./)) override | Určuje, zda tato instance se rovná jiné instance [ValueTask](./). |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Určuje, zda tato instance se rovná jinému objektu. |
| virtual **bool** [Equals](../../system/iequatable/equals/)(T) | Určuje, zda jsou aktuální a zadané objekty stejné. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| **bool** [get_IsCanceled](./get_iscanceled/)() const | Vrací hodnotu udávající, zda úloha skončila z důvodu zrušení. |
| **bool** [get_IsCompleted](./get_iscompleted/)() const | Vrací hodnotu udávající, zda úloha byla dokončena. |
| **bool** [get_IsCompletedSuccessfully](./get_iscompletedsuccessfully/)() const | Vrací hodnotu udávající, zda úloha byla úspěšně dokončena. |
| **bool** [get_IsFaulted](./get_isfaulted/)() const | Vrací hodnotu udávající, zda úloha skončila kvůli neodchycené výjimce. |
| [Runtime::CompilerServices::ValueTaskAwaiter](../../system.runtime.compilerservices/valuetaskawaiter/) [GetAwaiter](./getawaiter/)() const | Vrací awaiter pro tuto úlohu pro podporu await výrazů. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Vrací datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Vrací skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného pomocí targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí výrazu C# lock(). Volat přímo nebo použít objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| **bool** [operator!=](./operator_not_equal/)(const [ValueTask](./)\&) const | Operátor nerovnosti pro [ValueTask](./). |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| **bool** [operator==](./operator_equal_equal/)(const [ValueTask](./)\&) const | Operátor rovnosti pro [ValueTask](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží počet sdílených referencí o zadanou hodnotu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument na slabý ukazatel (namísto sdíleného). Umožňuje přepnout ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Vrací aktuální hodnotu počítadla sdílených referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje počet sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací počet sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí výrazu C# lock(). Volat přímo nebo použít objekt strážce [LockContext](../../system/lockcontext/). |
|  [ValueTask](./valuetask/)() | Vytvoří prázdný, neinicializovaný [ValueTask](./). |
|  [ValueTask](./valuetask/)(const [TaskPtr](../../system/taskptr/)\&) | Vytvoří [ValueTask](./) ze sdíleného ukazatele na [Task](../task/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje počet slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje počet slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [IEquatable](../../system/iequatable/)
* Jmenný prostor [System::Threading::Tasks](../)
* Knihovna [Aspose.Slides](../../)