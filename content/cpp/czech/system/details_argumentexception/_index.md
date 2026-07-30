---
title: Details_ArgumentException
second_title: Aspose.Slides pro C++ API Reference
description: "ArgumentException je vyvolána, když je předán argument metodě, která je volána, a je neplatný. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu ArgumentException. Nikdy neobalujte instance třídy ArgumentException do System::SmartPtr."
type: docs
weight: 326
url: /cs/system/details_argumentexception/
---
## Details_ArgumentException třída


ArgumentException je vyvolána, když je předán argument metodě, která je volána, a je neplatný. Nikdy nevytvářejte instance této třídy ručně. Místo toho použijte třídu ArgumentException. Nikdy neobalujte instance třídy ArgumentException do [System::SmartPtr](../smartptr/).

```cpp
class Details_ArgumentException : public System::Details_SystemException
```

## Metody

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání čísel s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání čísel s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Vrací slovník s vlastními daty výjimky. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Vrací 32bitové celé číslo, které je kódem HRESULT spojeným s výjimkou reprezentovanou aktuálním objektem. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Vrací odkaz na objekt představující vnitřní výjimku. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Vrací řetězec obsahující popis chyby. |
| [String](../string/) [get_ParamName](./get_paramname/)() |  |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Vrací řetězec obsahující trasu zásobníku. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Vrací kopii objektu Exception, který představuje nejvnitřnější výjimku. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Získává datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../object/gethashcode/). Umožňuje hašování vlastních objektů. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Získává skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Implementuje zamykání pomocí příkazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specializace [Object::ReferenceEquals](../object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Snižuje sdílený počet referencí o zadanou hodnotu. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Nastavuje HRESULT, kódovanou číselnou hodnotu přiřazenou konkrétní výjimce. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../object/sharedcount/)() const | Získává aktuální hodnotu sdíleného počítadla referencí. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Zvyšuje sdílený počet referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený počet referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Vrací řetězcovou reprezentaci aktuálního objektu. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Implementuje odemčení pomocí příkazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zvyšuje slabý počet referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Snižuje slabý počet referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | Implementuje metodu [what()](../details_exception/what/), která je volána třídou [ExceptionWrapper](../exceptionwrapper/). Navzdory tomu, že tato třída není zděděna ze std::exception, odvozené třídy mohou používat chráněné/soukromé členy k implementaci své logiky. Přesunutí implementace této metody do [ExceptionWrapper](../exceptionwrapper/) může tuto logiku porušit. |
| virtual  [~Object](../object/~object/)() | Ničí objekt. Uvolňuje všechny vnitřní datové struktury. |

## Poznámky


ArgumentNullException je vyvolána, když je metodě, která je volána, předán nulový argument, a metoda očekává nenulovou hodnotu. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu ArgumentNullException. Nikdy neobalujte instance třídy ArgumentNullException do [System::SmartPtr](../smartptr/). 
## Viz také

* Třída [Details_SystemException](../details_systemexception/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)