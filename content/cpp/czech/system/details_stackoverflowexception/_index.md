---
title: Details_StackOverflowException
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Výjimka StackOverflowException je vyhozena, když se přeteče zásobník provádění vlákna. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu StackOverflowException. Nikdy neobalujte instance třídy StackOverflowException do System::SmartPtr."
type: docs
weight: 690
url: /cs/system/details_stackoverflowexception/
---
## Details_StackOverflowException třída

StackOverflowException je vyhozena, když se přeteče zásobník provádění vlákna. Nikdy nevytvářejte instance této třídy ručně. Použijte třídu StackOverflowException. Nikdy nezabaluje instance třídy StackOverflowException do [System::SmartPtr](../smartptr/).

```cpp
class Details_StackOverflowException : public System::Details_SystemException
```

## Metody

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s dvojitou přesností ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Vrací slovník s vlastními daty výjimky. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Vrací 32bitovou celočíselnou hodnotu, která je kódem HRESULT spojeným s výjimkou reprezentovanou aktuálním objektem. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Vrací referenci na objekt představující vnitřní výjimku. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Vrací řetězec obsahující popis chyby. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Vrací řetězec obsahující trace zásobníku. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Vrací kopii objektu Exception, který představuje nejvnitřnější výjimku. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Získá datovou strukturu počítadla odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analogie C# [Object.GetHashCode()](../object/gethashcode/). Umožňuje hashování vlastních objektů. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Implementuje zamykání pomocí C# výrazu lock(). Zavolejte přímo nebo použijte sentinelní objekt [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specializace [Object::ReferenceEquals](../object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Sníží sdílený čítač odkazů o zadanou hodnotu. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Nastaví HRESULT, kódovanou číselnou hodnotu přiřazenou konkrétní výjimce. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače odkazů. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Zvýší sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Vrací řetězcovou reprezentaci aktuálního objektu. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Implementuje odemknutí pomocí C# výrazu lock(). Zavolejte přímo nebo použijte sentinelní objekt [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zvýší slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Sníží slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | Implementuje metodu [what()](../details_exception/what/), která je volána třídou [ExceptionWrapper](../exceptionwrapper/). Navzdory tomu, že tato třída není děděna z std::exception, odvozené třídy mohou použít chráněné/soukromé členy k implementaci své logiky. Přesunutí implementace této metody do [ExceptionWrapper](../exceptionwrapper/) může tuto logiku porušit. |
| virtual  [~Object](../object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [Details_SystemException](../details_systemexception/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)