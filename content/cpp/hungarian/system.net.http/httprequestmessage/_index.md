---
title: HttpRequestMessage
second_title: Aspose.Slides C++ API Referencia
description: "Egy HTTP kérés üzenetet reprezentál. Ennek az osztálynak az objektumait csak a System::MakeObject() függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a stacken vagy az operator new segítségével, mert ez futásidejű hibákat és/vagy állítási hibákat okozhat. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót a függvények argumentumaként való átadásához."
type: docs
weight: 105
url: /hu/system.net.http/httprequestmessage/
---
## HttpRequestMessage osztály

Egy HTTP kérés üzenetet képvisel. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ezen típusú objektumból a stacken vagy az operator new használatával, mert ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót a függvények argumentumaként való átadásához.

```cpp
class HttpRequestMessage : public System::IDisposable
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| void [Dispose](./dispose/)() override | Felszabadítja a jelenlegi példányt. Ez a metódus a HTTP kérés tartalmát is felszabadítja. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpContent](../httpcontent/)\> [get_Content](./get_content/)() | Lekéri a HTTP kérés tartalmát. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Http::Headers::HttpRequestHeaders](../../system.net.http.headers/httprequestheaders/)\> [get_Headers](./get_headers/)() | Visszaadja a HTTP tartalom fejléceit. |
| [System::SharedPtr](../../system/sharedptr/)\<[HttpMethod](../httpmethod/)\> [get_Method](./get_method/)() | Lekéri a HTTP kérés módszerét. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Properties](./get_properties/)() | Visszaadja a HTTP kérés tulajdonságainak gyűjteményét. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() | Lekéri a kért erőforrás URI-ját. |
| [System::Version](../../system/version/) [get_Version](./get_version/)() | Lekéri a HTTP verziót. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciaszámláló adatstruktúráját. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
|  [HttpRequestMessage](./httprequestmessage/)() | Új példányt hoz létre. |
|  [HttpRequestMessage](./httprequestmessage/)([System::SharedPtr](../../system/sharedptr/)\<[HttpMethod](../httpmethod/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Új példányt hoz létre. |
|  [HttpRequestMessage](./httprequestmessage/)([System::SharedPtr](../../system/sharedptr/)\<[HttpMethod](../httpmethod/)\>, [String](../../system/string/)) | Új példányt hoz létre. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus egy példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| **bool** [MarkAsSent](./markassent/)() | Megjelöli a jelenlegi kérést elküldöttként. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak inicializál egy új objektumot és lehetővé teszi a leszármazottak másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak inicializál egy új objektumot és lehetővé teszi a leszármazottak másoló konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az érték típusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_Content](./set_content/)([System::SharedPtr](../../system/sharedptr/)\<[HttpContent](../httpcontent/)\>) | Beállítja a HTTP kérés tartalmát. |
| void [set_Method](./set_method/)([System::SharedPtr](../../system/sharedptr/)\<[HttpMethod](../httpmethod/)\>) | Beállítja a HTTP kérés módszerét. |
| void [set_RequestUri](./set_requesturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Beállítja a kért erőforrás URI-ját. |
| void [set_Version](./set_version/)([System::Version](../../system/version/)) | Beállítja a HTTP verziót. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók konténerekben történő gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámláló értékét. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámláló értékét. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| [String](../../system/string/) [ToString](./tostring/)() const override | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámláló értékét. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámláló értékét. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadít minden belső adatstruktúrát. |

## Lásd még

* Osztály [IDisposable](../../system/idisposable/)
* Névtér [System::Net::Http](../)
* Könyvtár [Aspose.Slides](../../)