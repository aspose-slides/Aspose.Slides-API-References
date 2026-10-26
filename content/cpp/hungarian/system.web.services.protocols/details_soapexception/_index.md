---
title: Details_SoapException
second_title: Aspose.Slides C++ API Referencia
description: "Reprezentálja azt a kivételt, amely akkor dobódik, amikor egy metódust SOAP-on keresztül hívnak, és hiba lép fel. Soha ne hozzon létre példányokat ebből az osztályból manuálisan. Használja helyette a SoapException osztályt. Soha ne csomagolja be a SoapException osztály példányait a System::SmartPtr-be."
type: docs
weight: 1
url: /hu/system.web.services.protocols/details_soapexception/
---
## Details_SoapException osztály


Képviseli azt a kivételt, amely akkor kerül dobásra, amikor egy metódust SOAP-on keresztül hívnak, és hiba lép fel. Soha ne hozzon létre példányokat ebből az osztályból manuálisan. Használja helyette a SoapException osztályt. Soha ne csomagolja be a SoapException osztály példányait [System::SmartPtr](../../system/smartptr/)-ba.

```cpp
class Details_SoapException : public System::Details_SystemException
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
|  [Details_SoapException](./details_soapexception/)() | Új példányt hoz létre. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | Új példányt hoz létre. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [Exception](../../system/exception/)) | Új példányt hoz létre. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/)) | Új példányt hoz létre. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [Exception](../../system/exception/)) | Új példányt hoz létre. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>) | Új példányt hoz létre. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>, [Exception](../../system/exception/)) | Új példányt hoz létre. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\>) | Új példányt hoz létre. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\>, [Exception](../../system/exception/)) | Új példányt hoz létre. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\>, [Exception](../../system/exception/)) | Új példányt hoz létre. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat C# [Object.Equals](../../system/object/equals/) szintaxis szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Hivatkozástípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Szimulálja a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekintendő, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, így a NaN-nal sem. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Szimulálja a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekintendő, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, így a NaN-nal sem. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [String](../../system/string/) [get_Actor](./get_actor/)() | Visszaadja a kódrészletet, ahol a kivétel dobásra kerül, ha a SOAP 1.1 verziója van használatban. |
| [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_Code](./get_code/)() | Visszaad egy névtérrel kvalifikált helyi nevet 'namespace:localname' formátumban, amely meghatározza a SOAP hibakódot. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | Visszaad egy szótárat egyedi kivételadatokkal. |
| [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\> [get_Detail](./get_detail/)() | Visszaadja a dobott kivétel részleteit. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | Visszaad egy 32 bites egész értéket, amely az aktuális objektum által képviselt kivételhez kapcsolódó HRESULT kód. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | Visszaad egy hivatkozást az objektumra, amely a belső kivételt reprezentálja. |
| [String](../../system/string/) [get_Lang](./get_lang/)() | Visszaadja a nyelvet, amelyet a kivételtulajdonságok lokalizálásához használnak. |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | Visszaadja a hibaleírást tartalmazó karakterláncot. |
| [String](../../system/string/) [get_Node](./get_node/)() | Visszaadja a kódrészletet, ahol a kivétel dobásra kerül, ha a SOAP 1.2 verziója van használatban. |
| [String](../../system/string/) [get_Role](./get_role/)() | Visszaadja a kivételt dobó XML webszolgáltatás szerepét. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | Visszaadja a veremnyomot tartalmazó karakterláncot. |
| [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\> [get_SubCode](./get_subcode/)() | Visszaad opcionális információkat a 'subcode' XML elemből. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | Visszaadja a legbelső kivételt reprezentáló Exception objektum másolatát. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referenciakorlát adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyedi objektumok hash-elését. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_systemexception/gettype/)() const override | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| **bool** [Is](../../system/details_systemexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| static **bool** [IsClientFaultCode](./isclientfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | Ellenőrzi, hogy a megadott kód megegyezik-e a 'Client' SOAP hibakóddal. |
| static **bool** [IsMustUnderstandFaultCode](./ismustunderstandfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | Ellenőrzi, hogy a megadott kód megegyezik-e a 'MustUnderstand' SOAP hibakóddal. |
| static **bool** [IsServerFaultCode](./isserverfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | Ellenőrzi, hogy a megadott kód megegyezik-e a 'Server' SOAP hibakóddal. |
| static **bool** [IsVersionMismatchFaultCode](./isversionmismatchfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | Ellenőrzi, hogy a megadott kód megegyezik-e a 'VersionMismatch' SOAP hibakóddal. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítást a zároláshoz. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint összehasonlítja az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | Beállítja a HRESULT-et, egy kódolt numerikus értéket, amelyet egy adott kivételhez rendelnek. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n'th sablonargumentumot gyenge mutatóra (a shared helyett). Lehetővé teszi a mutatók váltását a konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | Visszaadja az aktuális objektum karakterlánc reprezentációját. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_systemexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual const char * [what](../../system/details_exception/what/)() const | Megvalósítja a [what()](../../system/details_exception/what/) metódust, amelyet a [ExceptionWrapper](../../system/exceptionwrapper/) osztály hív. Annak ellenére, hogy ez az osztály nem örököl a std::exception-ből, a származtatott osztályok védett/privát tagokat használhatnak a logika megvalósításához. Ennek a metódus-implementációnak a [ExceptionWrapper](../../system/exceptionwrapper/)-ba helyezése megsértheti ezt a logikát. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static [ClientFaultCode](./clientfaultcode/) | Egy SOAP hibakód, amely azt a kliens hívást reprezentálja, amely helytelenül van formázva vagy nem tartalmazza a szükséges információkat. |
| static [DetailElementName](./detailelementname/) | Egy névtérrel kvalifikált helyi név 'namespace:localname' formátumban. |
| static [MustUnderstandFaultCode](./mustunderstandfaultcode/) | Egy SOAP hibakód, amely azt jelzi, ha a 'MustUnderstand' attribútummal jelölt SOAP elem nincs feldolgozva. |
| static [ServerFaultCode](./serverfaultcode/) | Egy SOAP hibakód, amely a szerveren bekövetkezett hibát jelzi. |
| static [VersionMismatchFaultCode](./versionmismatchfaultcode/) | Egy SOAP hibakód, amely egy érvénytelen névteret jelöl. |

## Lásd még

* Osztály [Details_SystemException](../../system/details_systemexception/)
* Névtér [System::Web::Services::Protocols](../)
* Könyvtár [Aspose.Slides](../../)