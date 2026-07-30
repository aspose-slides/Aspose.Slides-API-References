---
title: Details_MemberAccessException
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: "MemberAccessException je vyvolána, když je proveden pokus o přístup k členu neexistující třídy nebo když přístup k členu není povolen. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu MemberAccessException. Nikdy neobalujte instance třídy MemberAccessException do System::SmartPtr."
type: docs
weight: 547
url: /cs/system/details_memberaccessexception/
---
## Details_MemberAccessException třída


MemberAccessException je vyvolána, když je provedeno pokus o přístup k členu neexistující třídy nebo když přístup k členu není povolen. Nikdy nevytvářejte instance této třídy ručně. Použijte místo toho třídu MemberAccessException. Nikdy neobalujte instance třídy MemberAccessException do [System::SmartPtr](../smartptr/).

```cpp
class Details_MemberAccessException : public System::Details_SystemException
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnoty ve stylu C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | Vrací slovník s vlastními daty výjimky. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | Vrací 32-bitovou celou hodnotu, což je kód HRESULT spojený s výjimkou reprezentovanou aktuálním objektem. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | Vrací odkaz na objekt představující vnitřní výjimku. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | Vrací řetězec obsahující popis chyby. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | Vrací řetězec obsahující stopu zásobníku. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | Vrací kopii objektu Exception, který představuje nejvnitřnější výjimku. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Získává datovou strukturu počítadla odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../object/gethashcode/). Umožňuje hašování vlastních objektů. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | Získává skutečný typ objektu. Analog volání C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | Implementuje uzamykání příkazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../object/object/)([Object](../object/) const\&) | Kopírovací konstruktor. Vlastně nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operátor přiřazení. Vlastně nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Porovnává objekty odkazem. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Porovnává objekty odkazem. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává odkazem objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specializace [Object::ReferenceEquals](../object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Snižuje sdílený čítač odkazů o zadanou hodnotu. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | Nastavuje HRESULT, číselnou kódovanou hodnotu přiřazenou konkrétní výjimce. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Nastavuje n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../object/sharedcount/)() const | Získává aktuální hodnotu sdíleného počítadla odkazů. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Zvyšuje sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | Vrací řetězcovou reprezentaci aktuálního objektu. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | Implementuje odemknutí příkazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zvyšuje slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Snižuje slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual const char * [what](../details_exception/what/)() const | Implementuje metodu [what()](../details_exception/what/), která je volána třídou [ExceptionWrapper](../exceptionwrapper/). Navzdory tomu, že tato třída nezdědí z std::exception, mohou odvozené třídy využívat chráněné/soukromé členy k implementaci své logiky. Přesunutí implementace této metody do [ExceptionWrapper](../exceptionwrapper/) může tuto logiku narušit. |
| virtual  [~Object](../object/~object/)() | Ničí objekt. Uvolňuje všechny vnitřní datové struktury. |
## Viz také

* Třída [Details_SystemException](../details_systemexception/)
* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)