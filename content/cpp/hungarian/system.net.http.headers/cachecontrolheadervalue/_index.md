---
title: CacheControlHeaderValue
second_title: Aspose.Slides C++ API referencia
description: "Reprezentálja a 'Cache-Control' fejléc értékét. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az new operátorral, mivel ez futásidejű hibákat és/vagy assert hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és ezt a mutatót használja az argumentumként való átadásra a függvényeknek."
type: docs
weight: 14
url: /hu/system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue osztály


A 'Cache-Control' fejléc értékét képviseli. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az new operátorral, mivel ez futásidejű hibákat és/vagy assert hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és ezt a mutatót használja az argumentumként való átadásra a függvényeknek.

```cpp
class CacheControlHeaderValue : public System::ICloneable
```


## Metódusok

| Módszer | Leírás |
| --- | --- |
|  [CacheControlHeaderValue](./cachecontrolheadervalue/)() | Új példányt hoz létre. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika alapján. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika alapján. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Extensions](./get_extensions/)() | Visszaadja a cache-extension tokenek gyűjteményét. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxAge](./get_maxage/)() | Lekéri a maximális életkor értékét másodpercben, amely meghatározza, hogy a kliens meddig fogadja el a választ. |
| **bool** [get_MaxStale](./get_maxstale/)() | Lekéri az értéket, amely meghatározza, hogy a kliens elfogadja-e a lejárt válaszokat. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxStaleLimit](./get_maxstalelimit/)() | Lekéri az értéket másodpercben, amely meghatározza, hogy a kliens meddig fogadja el a lejárt válaszokat. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MinFresh](./get_minfresh/)() | Lekéri az értéket, amely meghatározza a frissességi időtartamot. |
| **bool** [get_MustRevalidate](./get_mustrevalidate/)() | Lekéri az értéket, amely meghatározza, hogy a szerver megköveteli-e a gyorsítótár-bejegyzés újraellenőrzését, amikor az elavulttá válik. |
| **bool** [get_NoCache](./get_nocache/)() | Lekéri az értéket, amely meghatározza, hogy a kliens elfogadja-e a gyorsítótárazott választ. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_NoCacheHeaders](./get_nocacheheaders/)() | Lekéri a 'no-cache' direktívában a 'Cache-Control' fejlécben szereplő mezőnevek gyűjteményét. |
| **bool** [get_NoStore](./get_nostore/)() | Lekéri az értéket, amely meghatározza, hogy egy gyorsítótár ne tároljon semmilyen részt egy HTTP kérésből vagy válaszból. |
| **bool** [get_NoTransform](./get_notransform/)() | Lekéri az értéket, amely meghatározza, hogy egy gyorsítótár vagy proxy ne módosítson semmilyen részt az entitás törzsében. |
| **bool** [get_OnlyIfCached](./get_onlyifcached/)() | Lekéri az értéket, amely meghatározza, hogy a kliens csak gyorsítótárazott bejegyzéseket használjon. |
| **bool** [get_Private](./get_private/)() | Lekéri az értéket, amely meghatározza, hogy a HTTP válasz üzenet vagy annak egy része egyetlen felhasználó számára készült, és ne legyen megosztott gyorsítótár által tárolva. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_PrivateHeaders](./get_privateheaders/)() | Lekéri a 'private' direktívában a 'Cache-Control' fejlécben szereplő mezőnevek gyűjteményét. |
| **bool** [get_ProxyRevalidate](./get_proxyrevalidate/)() | Lekéri az értéket, amely meghatározza, hogy a szerver megköveteli-e egy gyorsítótár-bejegyzés újraellenőrzését, amikor az elavulttá válik a megosztott felhasználói ügynök gyorsítótárak esetén. |
| **bool** [get_Public](./get_public/)() | Lekéri az értéket, amely meghatározza, hogy egy HTTP válasz tárolható-e bármely gyorsítótár által. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_SharedMaxAge](./get_sharedmaxage/)() | Lekéri a megosztott maximális életkor értékét másodpercben, amely felülírja a 'max-age' direktívát a 'Cache-Control' fejlécben vagy az 'Expires' fejlécet a megosztott gyorsítótár esetén. |
| static **int32_t** [GetCacheControlLength](./getcachecontrollength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Átalakítja a megadott indexnél kezdődő karakterláncot a [CacheControlHeaderValue](./) osztály egy példányává. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciacsökkentő adatstruktúrát. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másolás-konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másolás-konstrukcióját. |
| static [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Átalakítja a megadott karakterláncot a [CacheControlHeaderValue](./) osztály egy példányává. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával összehasonlítja az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_MaxAge](./set_maxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Beállítja a maximális életkor értékét másodpercben, amely meghatározza, hogy a kliens meddig fogadja el a választ. |
| void [set_MaxStale](./set_maxstale/)(**bool**) | Beállítja az értéket, amely meghatározza, hogy a kliens elfogadja-e a lejárt válaszokat. |
| void [set_MaxStaleLimit](./set_maxstalelimit/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Beállítja az értéket másodpercben, amely meghatározza, hogy a kliens meddig fogadja el a lejárt válaszokat. |
| void [set_MinFresh](./set_minfresh/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Beállítja az értéket, amely meghatározza a frissességi időtartamot. |
| void [set_MustRevalidate](./set_mustrevalidate/)(**bool**) | Beállítja az értéket, amely meghatározza, hogy a szerver megköveteli-e a gyorsítótár-bejegyzés újraellenőrzését, amikor az elavulttá válik. |
| void [set_NoCache](./set_nocache/)(**bool**) | Beállítja az értéket, amely meghatározza, hogy a kliens elfogadja-e a gyorsítótárazott választ. |
| void [set_NoStore](./set_nostore/)(**bool**) | Beállítja az értéket, amely meghatározza, hogy a gyorsítótár ne tároljon semmilyen részt egy HTTP kérésből vagy válaszból. |
| void [set_NoTransform](./set_notransform/)(**bool**) | Beállítja az értéket, amely meghatározza, hogy a gyorsítótár vagy proxy ne módosítson semmilyen részt az entitás törzsében. |
| void [set_OnlyIfCached](./set_onlyifcached/)(**bool**) | Beállítja az értéket, amely meghatározza, hogy a kliens csak gyorsítótárazott bejegyzéseket használjon. |
| void [set_Private](./set_private/)(**bool**) | Beállítja az értéket, amely meghatározza, hogy a HTTP válasz üzenet vagy annak egy része egyetlen felhasználó számára készült, és ne legyen megosztott gyorsítótár által tárolva. |
| void [set_ProxyRevalidate](./set_proxyrevalidate/)(**bool**) | Beállítja az értéket, amely meghatározza, hogy a szerver megköveteli-e egy gyorsítótár-bejegyzés újraellenőrzését, amikor az elavulttá válik a megosztott felhasználói ügynök gyorsítótárak esetén. |
| void [set_Public](./set_public/)(**bool**) | Beállítja az értéket, amely meghatározza, hogy egy HTTP válasz bármely gyorsítótár által tárolható-e. |
| void [set_SharedMaxAge](./set_sharedmaxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Beállítja a megosztott maximális életkor értékét másodpercben, amely felülírja a 'max-age' direktívát a 'Cache-Control' fejlécben vagy az 'Expires' fejlécet egy megosztott gyorsítótár esetén. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (nem megosztott). Lehetővé teszi a mutatók konténerben való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okosmutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okosmutatókat vagy ThisProtector-t. |
| [String](../../system/string/) [ToString](./tostring/)() const override | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Megpróbálja a megadott karakterláncot a [CacheControlHeaderValue](./) osztály egy példányává konvertálni. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okosmutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okosmutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadít minden belső adatstruktúrát. |

## Lásd még

* Osztály [ICloneable](../../system/icloneable/)
* Névtere [System::Net::Http::Headers](../)
* Könyvtár [Aspose.Slides](../../)