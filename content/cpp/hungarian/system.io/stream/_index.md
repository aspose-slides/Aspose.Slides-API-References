---
title: Stream
second_title: Aspose.Slides C++ API-referencia
description: "Egy alaposztály különféle stream megvalósításokhoz. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból stacken vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy assert hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az objektum függvényeknek való átadásához argumentumként."
type: docs
weight: 365
url: /hu/system.io/stream/
---
## Stream osztály

Alaposztály különféle stream megvalósításokhoz. Ennek az osztálynak az példányait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból stacken vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy assert hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az objektum függvényeknek való átadásához argumentumként.
```cpp
class Stream : public System::IDisposable
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Elindít egy aszinkron olvasási műveletet. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Elindít egy aszinkron írási műveletet. |
| virtual void [Close](./close/)() | Lezárja a streamet. |
| void [CopyTo](./copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](./)\>\&) | Átmásolja a bájtokat a megadott streambe. |
| void [CopyTo](./copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](./)\>\&, **int32_t**) | Átmásolja a bájtokat a megadott streambe, a megadott pufferméret használatával. |
| void [Dispose](./dispose/)() override | Felszabadítja az aktuális objektum által használt összes erőforrást és lezárja a streamet. |
| virtual int [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Megvárja, amíg a megadott aszinkron olvasási művelet befejeződik. |
| virtual void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Befejez egy aszinkron írási műveletet. Megvárja, amíg a megadott aszinkron írási művelet befejeződik. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szintaxis szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, habár az IEC 60559:1989 szerint a NaN nem egyenlő egyetlen értékkel sem, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, habár az IEC 60559:1989 szerint a NaN nem egyenlő egyetlen értékkel sem, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual void [Flush](./flush/)() | Kiüríti a stream puffereit és a pufferelt adatokat az alaprendszerbe írja. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon kiüríti a stream összes puffert, a pufferelt adatokat az alapeszközbe írja, és figyeli a megszakítási kéréseket. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)() | Aszinkron módon kiüríti a stream összes puffert, a pufferelt adatokat az alapeszközbe írja, és figyeli a megszakítási kéréseket. |
| virtual **bool** [get_CanRead](./get_canread/)() const | Megállapítja, hogy a stream olvasható-e. |
| virtual **bool** [get_CanSeek](./get_canseek/)() const | Megállapítja, hogy a stream támogatja-e a keresést. |
| virtual **bool** [get_CanTimeout](./get_cantimeout/)() const | Visszaad egy értéket, amely meghatározza, hogy a jelenlegi stream időtúllépést szenvedhet-e. |
| virtual **bool** [get_CanWrite](./get_canwrite/)() const | Megállapítja, hogy a stream írható-e. |
| virtual **int64_t** [get_Length](./get_length/)() const | Visszaadja a stream hosszát bájtokban. |
| virtual **int64_t** [get_Position](./get_position/)() const | Visszaadja a stream aktuális pozícióját. |
| virtual int [get_ReadTimeout](./get_readtimeout/)() const | Visszaad egy értéket ezredmásodpercben, amely meghatározza, meddig próbál olvasni a stream a timeout előtt. |
| virtual int [get_WriteTimeout](./get_writetimeout/)() const | Visszaad egy értéket ezredmásodpercben, amely meghatározza, meddig próbál írni a stream a timeout előtt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Visszaadja az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Visszaadja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítást zárolásként. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| virtual **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Beolvassa a streamből a megadott számú bájtot és a megadott bájt tömbbe írja. |
| virtual **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Beolvassa a streamből a megadott számú bájtot és a megadott bájt tömbbe írja. |
| **int32_t** [Read](./read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Beolvassa a streamből a megadott számú bájtot és a megadott bájt tömbbe írja. |
| virtual **int32_t** [Read](./read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Beolvassa a streamből a megadott számú bájtot és a megadott bájt span-be írja. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon beolvas egy bájt sorozatot a jelenlegi streamebből, a stream pozícióját a beolvasott bájtok számával előrelépteti, és figyeli a megszakítási kéréseket. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Aszinkron módon beolvas egy bájt sorozatot a jelenlegi streamebből, a stream pozícióját a beolvasott bájtok számával előrelépteti, és figyeli a megszakítási kéréseket. |
| virtual int [ReadByte](./readbyte/)() | Beolvas egyetlen bájtot a streamből és visszaad egy 32-bites egész értéket, amely megegyezik a beolvasott bájt értékével. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípusú objektumot referenciával hasonlít össze a nullptr-vel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) | Beállítja a stream pozícióját, amelyet az aktuális objektum képvisel. |
| virtual void [set_Position](./set_position/)(**int64_t**) | Beállítja a stream pozícióját. |
| virtual void [set_ReadTimeout](./set_readtimeout/)(int) | Beállít egy értéket, amely meghatározza, hogy a jelenlegi stream időtúllépést szenvedhet-e. |
| virtual void [set_WriteTimeout](./set_writetimeout/)(int) | Beállít egy értéket ezredmásodpercben, amely meghatározza, meddig próbál olvasni a stream a timeout előtt. |
| virtual void [SetLength](./setlength/)(**int64_t**) | Beállítja a stream hosszát, amelyet az aktuális objektum képvisel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóként állítja be (ahelyett, hogy megosztott lenne). Lehetővé teszi a mutatók átkapcsolását a konténerekben gyenge módba. |
| int [SharedCount](../../system/object/sharedcount/)() const | Visszaadja a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; használjon okos mutatókat vagy ThisProtector-t. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Az adott bájt tömb megadott részhalmazát írja a streambe. |
| virtual void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Az adott bájt tömb megadott részhalmazát írja a streambe. |
| void [Write](./write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Az adott bájt tömb megadott részhalmazát írja a streambe. |
| virtual void [Write](./write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Az adott bájt span megadott részhalmazát írja a streambe. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon ír egy bájt sorozatot a jelenlegi streamebből, a stream aktuális pozícióját a leírt bájtok számával előrelépteti, és figyeli a megszakítási kéréseket. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Aszinkron módon ír egy bájt sorozatot a jelenlegi streamebből, a stream aktuális pozícióját a leírt bájtok számával előrelépteti, és figyeli a megszakítási kéréseket. |
| virtual void [WriteByte](./writebyte/)(**uint8_t**) | Az adott 8 bites előjel nélküli egész értéket írja a streambe. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static [Null](./null/) | Egy stream alaptároló nélkül. |

## Typedefek

| Typedef | Leírás |
| --- | --- |
| [Ptr](./ptr/) | Egy alias a jelen osztályra mutató megosztott mutatóhoz. |

## Lásd még

* Osztály [IDisposable](../../system/idisposable/)
* Névtér [System::IO](../)
* Könyvtár [Aspose.Slides](../../)