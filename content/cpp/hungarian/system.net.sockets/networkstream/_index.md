---
title: NetworkStream
second_title: Aspose.Slides a C++ API hivatkozáshoz
description: "Biztosítja a hálózati hozzáféréshez szükséges adat alatti adatfolyamot. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény segítségével szabad lefoglalni. Soha ne hozza létre ennek a típusnak a példányát a veremben vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat okozhat. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az argumentumként való átadásra a függvényekhez."
type: docs
weight: 40
url: /hu/system.net.sockets/networkstream/
---
## NetworkStream osztály

Biztosítja a hálózati hozzáféréshez szükséges adatok alapjául szolgáló adatfolyamot. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy a new operátorral, mert ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót a függvények argumentumaként.

```cpp
class NetworkStream : public System::IO::Stream
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Elindít egy aszinkron olvasási műveletet. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Elindít egy aszinkron olvasási műveletet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Elindít egy aszinkron írási műveletet. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Elindít egy aszinkron írási műveletet. |
| void [Close](./close/)(int) | Bezárja a jelenlegi példányt a megadott idő lejárta után. |
| virtual void [Close](../../system.io/stream/close/)() | Bezárja az adatfolyamot. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | Átmásolja a bájtokat a megadott adatfolyamra. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | Átmásolja a bájtokat a megadott adatfolyamra, a megadott puffermérettel. |
| void [Dispose](../../system.io/stream/dispose/)() override | Felszabadítja az aktuális objektum által használt összes erőforrást, és bezárja az adatfolyamot. |
| **int32_t** [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Vár, amíg a megadott aszinkron olvasási művelet befejeződik. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Vár, amíg a megadott aszinkron olvasási művelet befejeződik. |
| void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Befejez egy aszinkron írási műveletet. Vár, amíg a megadott aszinkron írási művelet befejeződik. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Befejez egy aszinkron írási műveletet. Vár, amíg a megadott aszinkron írási művelet befejeződik. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referenciatípusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN-t egyenlőnek tekint, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN-t egyenlőnek tekint, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| void [Flush](./flush/)() override | Kiüríti az adatfolyam puffereit, és az összes pufferelt adatot az alapul szolgáló tárhelyre írja. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon törli az adatfolyam összes puffert, a pufferelt adatot az alapul szolgáló eszközre írja, és figyeli a leállítási kéréseket. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | Aszinkron módon törli az adatfolyam összes puffert, a pufferelt adatot az alapul szolgáló eszközre írja, és figyeli a leállítási kéréseket. |
| **bool** [get_CanRead](./get_canread/)() const override | Megállapítja, hogy az adatfolyam olvasható-e. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Megállapítja, hogy az adatfolyam támogatja-e a pozicionálást. |
| **bool** [get_CanTimeout](./get_cantimeout/)() const override | Lekér egy értéket, amely meghatározza, hogy az aktuális adatfolyam időtúllépést okozhat-e. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Megállapítja, hogy az adatfolyam írható-e. |
| **bool** [get_DataAvailable](./get_dataavailable/)() const | Visszaad egy értéket, amely jelzi, hogy van-e olvasható adat. |
| **int64_t** [get_Length](./get_length/)() const override | Visszaadja az adatfolyam hosszát bájtokban. |
| **int64_t** [get_Position](./get_position/)() const override | Visszaadja az adatfolyam jelenlegi pozícióját. |
| **int32_t** [get_ReadTimeout](./get_readtimeout/)() const override | Lekér egy értéket, ezredmásodpercben, amely meghatározza, meddig próbálja az adatfolyam olvasni, mielőtt időtúllépés történik. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\> [get_Socket](./get_socket/)() | Lekérdezi az alapul szolgáló [Socket](../socket/). |
| **int32_t** [get_WriteTimeout](./get_writetimeout/)() const override | Lekér egy értéket, ezredmásodpercben, amely meghatározza, meddig próbálja az adatfolyam írni, mielőtt időtúllépés történik. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektummal kapcsolatos referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyéni objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyéni típusok klónozását. |
|  [NetworkStream](./networkstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\>) | Új példányt hoz létre. |
|  [NetworkStream](./networkstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\>, [System::IO::FileAccess](../../system.io/fileaccess/), **bool**) | Új példányt hoz létre. |
|  [NetworkStream](./networkstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\>, **bool**) | Új példányt hoz létre. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolásával történő konstrukciót. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolásával történő konstrukciót. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Beolvasza a megadott számú bájtot az adatfolyamból, és a megadott bájttömbbe írja. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Beolvasza a megadott számú bájtot az adatfolyamból, és a megadott bájttömbbe írja. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Beolvasza a megadott számú bájtot az adatfolyamból, és a megadott bájttömbbe írja. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Beolvasza a megadott számú bájtot az adatfolyamból, és a megadott bájtspannra írja. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon beolvas egy bájtsorozatot az aktuális adatfolyamból, a pozíciót a beolvasott bájtok számával lépteti előre, és figyeli a leállítási kéréseket. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Aszinkron módon beolvas egy bájtsorozatot az aktuális adatfolyamból, a pozíciót a beolvasott bájtok számával lépteti előre, és figyeli a leállítási kéréseket. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | Beolvas egyetlen bájtot az adatfolyamból, és visszaad egy 32 bites egész értéket, amely megegyezik a beolvasott bájt értékével. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | Beállítja az aktuális objektum által képviselt adatfolyam pozícióját. |
| void [set_Position](./set_position/)(**int64_t**) override | Beállítja az adatfolyam pozícióját. |
| void [set_ReadTimeout](./set_readtimeout/)(**int32_t**) override | Beállít egy értéket, amely meghatározza, hogy az aktuális adatfolyam időtúllépést okozhat-e. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | Beállít egy értéket, amely meghatározza, hogy az aktuális adatfolyam időtúllépést okozhat-e. |
| void [set_WriteTimeout](./set_writetimeout/)(**int32_t**) override | Beállít egy értéket ezredmásodpercben, amely meghatározza, meddig próbálja az adatfolyam olvasni, mielőtt időtúllépés történik. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | Beállít egy értéket ezredmásodpercben, amely meghatározza, meddig próbálja az adatfolyam olvasni, mielőtt időtúllépés történik. |
| void [SetLength](./setlength/)(**int64_t**) override | Beállítja az aktuális objektum által képviselt adatfolyam hosszát. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóként (nem megosztottként) állítja be. Lehetővé teszi a mutatók átváltását konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyéni objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Az adatfolyamba írja a megadott bájttömb megadott alintervallumát. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Az adatfolyamba írja a megadott bájttömb megadott alintervallumát. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Az adatfolyamba írja a megadott bájttömb megadott alintervallumát. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Az adatfolyamba írja a megadott bájtspann megadott alintervallumát. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon ír egy bájtsorozatot a jelenlegi adatfolyamba, a pozíciót a megírt bájtok számával lépteti előre, és figyeli a leállítási kéréseket. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Aszinkron módon ír egy bájtsorozatot a jelenlegi adatfolyamba, a pozíciót a megírt bájtok számával lépteti előre, és figyeli a leállítási kéréseket. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | Az adatfolyamba írja a megadott előjelszám nélküli 8-bites egész értéket. |
| virtual  [~NetworkStream](./~networkstream/)() | Megsemmisíti a jelenlegi példányt. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Egy adatfolyam, amelynek nincs alaptárolója. |

## Lásd még

* Osztály [Stream](../../system.io/stream/)
* Névterület [System::Net::Sockets](../)
* Könyvtár [Aspose.Slides](../../)