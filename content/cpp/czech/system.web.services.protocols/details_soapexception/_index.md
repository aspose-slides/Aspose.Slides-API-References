---
title: Details_SoapException
second_title: Aspose.Slides pro C++ – reference API
description: "Reprezentuje výjimku vyvolanou, když je metoda volána přes SOAP a nastane chyba. Nikdy nevytvářejte instance této třídy ručně. Použijte třídu SoapException. Nikdy neobalujte instance třídy SoapException do System::SmartPtr."
type: docs
weight: 1
url: /cs/system.web.services.protocols/details_soapexception/
---
## Details_SoapException třída


Reprezentuje výjimku vyvolanou, když je metoda volána přes SOAP a nastane chyba. Nikdy nevytvářejte instance této třídy ručně. Místo toho použijte třídu SoapException. Nikdy neobalujte instance třídy SoapException do [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_SoapException : public System::Details_SystemException
```

## Metody

| Metoda | Popis |
| --- | --- |
|  [Details_SoapException](./details_soapexception/)() | Vytvoří novou instanci. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | Vytvoří novou instanci. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [Exception](../../system/exception/)) | Vytvoří novou instanci. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/)) | Vytvoří novou instanci. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [Exception](../../system/exception/)) | Vytvoří novou instanci. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>) | Vytvoří novou instanci. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>, [Exception](../../system/exception/)) | Vytvoří novou instanci. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\>) | Vytvoří novou instanci. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\>, [Exception](../../system/exception/)) | Vytvoří novou instanci. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\>, [Exception](../../system/exception/)) | Vytvoří novou instanci. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovná objekty pomocí C# [Object.Equals](../../system/object/equals/) sémantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání v plovoucí řádové čárce ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání v plovoucí řádové čárce ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| [String](../../system/string/) [get_Actor](./get_actor/)() | Vrací část kódu, kde je výjimka vyvolána při použití SOAP verze 1.1. |
| [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_Code](./get_code/)() | Vrací lokální název kvalifikovaný jmenným prostorem ve formátu 'namespace:localname', který určuje kód chyby SOAP. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | Vrací slovník s vlastními daty výjimky. |
| [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\> [get_Detail](./get_detail/)() | Vrací podrobnosti o vyvolané výjimce. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | Vrací 32-bitovou celočíselnou hodnotu, což je kód HRESULT přidružený k výjimce reprezentované aktuálním objektem. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | Vrací odkaz na objekt představující vnitřní výjimku. |
| [String](../../system/string/) [get_Lang](./get_lang/)() | Vrací jazyk, který se používá k lokalizaci vlastností výjimky. |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | Vrací řetězec obsahující popis chyby. |
| [String](../../system/string/) [get_Node](./get_node/)() | Vrací část kódu, kde je výjimka vyvolána při použití SOAP verze 1.2. |
| [String](../../system/string/) [get_Role](./get_role/)() | Vrací roli XML webové služby, která výjimku vyvolává. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | Vrací řetězec obsahující zásobník volání (stack trace). |
| [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\> [get_SubCode](./get_subcode/)() | Vrací volitelnou informaci z XML elementu 'subcode'. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | Vrací kopii objektu Exception představující nejvnitřnější výjimku. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_systemexception/gettype/)() const override | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [Is](../../system/details_systemexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| static **bool** [IsClientFaultCode](./isclientfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | Kontroluje, zda je zadaný kód roven kódu SOAP chyby 'Client'. |
| static **bool** [IsMustUnderstandFaultCode](./ismustunderstandfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | Kontroluje, zda je zadaný kód roven kódu SOAP chyby 'MustUnderstand'. |
| static **bool** [IsServerFaultCode](./isserverfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | Kontroluje, zda je zadaný kód roven kódu SOAP chyby 'Server'. |
| static **bool** [IsVersionMismatchFaultCode](./isversionmismatchfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | Kontroluje, zda je zadaný kód roven kódu SOAP chyby 'VersionMismatch'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykací výraz C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopie. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenčně objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | Nastaví HRESULT, číselnou hodnotu kódu přiřazenou konkrétní výjimce. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší sdílený čítač referencí. Nemělo by se volat přímo; použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; použijte chytré ukazatele nebo ThisProtector. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | Vrací řetězcovou reprezentaci aktuálního objektu. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_systemexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemykání výrazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší čítač slabých referencí. Nemělo by se volat přímo; použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží čítač slabých referencí. Nemělo by se volat přímo; použijte chytré ukazatele nebo ThisProtector. |
| virtual const char * [what](../../system/details_exception/what/)() const | Implementuje metodu [what()](../../system/details_exception/what/), která je volána třídou [ExceptionWrapper](../../system/exceptionwrapper/). Navzdory tomu, že tato třída nezdědí ze std::exception, odvozené třídy mohou použít chráněné / soukromé členy k implementaci vlastní logiky. Přesunutí implementace této metody do [ExceptionWrapper](../../system/exceptionwrapper/) může tuto logiku narušit. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |
## Pole

| Pole | Popis |
| --- | --- |
| static [ClientFaultCode](./clientfaultcode/) | Kód chyby SOAP, který představuje klientský požadavek špatně formátovaný nebo neobsahující požadované informace. |
| static [DetailElementName](./detailelementname/) | Lokální název kvalifikovaný jmenným prostorem ve formátu 'namespace:localname'. |
| static [MustUnderstandFaultCode](./mustunderstandfaultcode/) | Kód chyby SOAP, který signalizuje, že element SOAP označený atributem 'MustUnderstand' nebyl zpracován. |
| static [ServerFaultCode](./serverfaultcode/) | Kód chyby SOAP, který představuje chybu na serveru. |
| static [VersionMismatchFaultCode](./versionmismatchfaultcode/) | Kód chyby SOAP, který představuje neplatný jmenný prostor. |
## Viz také

* Třída [Details_SystemException](../../system/details_systemexception/)
* Jmenný prostor [System::Web::Services::Protocols](../)
* Knihovna [Aspose.Slides](../../)