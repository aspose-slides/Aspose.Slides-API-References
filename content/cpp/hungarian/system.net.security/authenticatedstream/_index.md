---
title: AuthenticatedStream
second_title: Aspose.Slides C++ API Referencia
description: "Tartalmazza a hitelesítő adatok áramlón keresztüli továbbításához szükséges metódusokat. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az operator new használatával, mert futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és ezt a mutatót használja az argumentumként történő átadásra a függvényeknek."
type: docs
weight: 1
url: /hu/system.net.security/authenticatedstream/
---
## AuthenticatedStream osztály

Tartalmazza a hitelesítő adatok áramlón keresztüli továbbításához szükséges metódusokat. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az operator new használatával, mert futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és ezt a mutatót használja az argumentumként történő átadásra a függvényeknek.

```cpp
class AuthenticatedStream : public System::IO::Stream
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Aszinkron olvasási műveletet indít el. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Aszinkron írási műveletet indít el. |
| virtual void [Close](../../system.io/stream/close/)() | Lezárja az adatfolyamot. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | Másolja a bájtokat a megadott adatfolyamra. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | Másolja a bájtokat a megadott adatfolyamra, a megadott pufferméret használatával. |
| void [Dispose](../../system.io/stream/dispose/)() override | Felszabadítja az aktuális objektum által használt összes erőforrást, és lezárja az adatfolyamot. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Várakozik, amíg a megadott aszinkron olvasási művelet be nem fejeződik. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Befejezi egy aszinkron írási műveletet. Várakozik, amíg a megadott aszinkron írási művelet be nem fejeződik. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szintaxis szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| virtual void [Flush](../../system.io/stream/flush/)() | Kiüríti ennek az adatfolyamnak a puffereit, és az összes pufferelt adatot az alatta lévő tárolóba írja. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon kiüríti ennek az adatfolyamnak az összes puffert, az esetleges pufferelt adatot az alatta lévő eszközre írja, és figyeli a leállítási kéréseket. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | Aszinkron módon kiüríti ennek az adatfolyamnak az összes puffert, az esetleges pufferelt adatot az alatta lévő eszközre írja, és figyeli a leállítási kéréseket. |
| virtual **bool** [get_CanRead](../../system.io/stream/get_canread/)() const | Megállapítja, hogy az adatfolyam olvasható-e. |
| virtual **bool** [get_CanSeek](../../system.io/stream/get_canseek/)() const | Megállapítja, hogy az adatfolyam támogatja-e a pozicionálást. |
| virtual **bool** [get_CanTimeout](../../system.io/stream/get_cantimeout/)() const | Visszaad egy értéket, ami meghatározza, hogy az aktuális adatfolyam időtúllépést okozhat-e. |
| virtual **bool** [get_CanWrite](../../system.io/stream/get_canwrite/)() const | Megállapítja, hogy az adatfolyam írható-e. |
| virtual **bool** [get_IsAuthenticated](./get_isauthenticated/)() const | Visszaad egy értéket, amely jelzi, hogy a hitelesítés sikeresen megtörtént. |
| virtual **bool** [get_IsEncrypted](./get_isencrypted/)() const | Visszaad egy értéket, amely jelzi, hogy a stream segítségével küldött adat titkosított-e. |
| virtual **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const | Visszaad egy értéket, amely jelzi, hogy a szerver és az ügyfél hitelesítve van-e. |
| virtual **bool** [get_IsServer](./get_isserver/)() const | Visszaad egy értéket, amely jelzi, hogy a kapcsolat helyi oldala a szerver-e. |
| virtual **bool** [get_IsSigned](./get_issigned/)() const | Visszaad egy értéket, amely jelzi, hogy a stream használatával küldött adat alá van-e írva. |
| **bool** [get_LeaveInnerStreamOpen](./get_leaveinnerstreamopen/)() const | Visszaadja azt az adatfolyamot, amelyet az aktuális osztálypéldányok az adatok küldésére és fogadására használnak. |
| virtual **int64_t** [get_Length](../../system.io/stream/get_length/)() const | Visszaadja az adatfolyam hosszát byte-ban. |
| virtual **int64_t** [get_Position](../../system.io/stream/get_position/)() const | Visszaadja az adatfolyam aktuális pozícióját. |
| virtual int [get_ReadTimeout](../../system.io/stream/get_readtimeout/)() const | Visszaad egy értéket, ezredmásodpercben, amely meghatározza, mennyi ideig próbál az adatfolyam olvasni, mielőtt időtúllépést eredményez. |
| virtual int [get_WriteTimeout](../../system.io/stream/get_writetimeout/)() const | Visszaad egy értéket, ezredmásodpercben, amely meghatározza, mennyi ideig próbál az adatfolyam írni, mielőtt időtúllépést eredményez. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Visszaadja az objektumhoz társított referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Visszaadja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak inicializálja az új objektumot, és lehetővé teszi az alosztályok másolókonstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Átadás operátor. Valójában semmit nem másol, csak inicializálja az új objektumot, és lehetővé teszi az alosztályok másolókonstruktorát. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Beolvassa a megadott számú bájtot az adatfolyamból, és a megadott bájt tömbbe írja. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Beolvassa a megadott számú bájtot az adatfolyamból, és a megadott bájt tömbbe írja. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Beolvassa a megadott számú bájtot az adatfolyamból, és a megadott bájt tömbbe írja. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Beolvassa a megadott számú bájtot az adatfolyamból, és a megadott bájt spanne írja. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon beolvas egy bájtsorozatot az aktuális adatfolyamból, a beolvasott bájtok számával előrelépteti a pozíciót, és figyeli a leállítási kéréseket. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Aszinkron módon beolvas egy bájtsorozatot az aktuális adatfolyamból, a beolvasott bájtok számával előrelépteti a pozíciót, és figyeli a leállítási kéréseket. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | Beolvas egyetlen bájtot az adatfolyamból, és egy 32-bites egész értéket ad vissza, amely megegyezik a beolvasott bájt értékével. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípusú objektumot referenciaként hasonlít össze a nullptr-vel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual **int64_t** [Seek](../../system.io/stream/seek/)(**int64_t**, [SeekOrigin](../../system.io/seekorigin/)) | Beállítja a jelenlegi objektum által képviselt adatfolyam pozícióját. |
| virtual void [set_Position](../../system.io/stream/set_position/)(**int64_t**) | Beállítja az adatfolyam pozícióját. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | Beállít egy értéket, amely meghatározza, hogy az aktuális adatfolyam időtúllépést okozhat-e. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | Beállít egy értéket ezredmásodpercben, amely meghatározza, mennyi ideig próbálja a stream olvasni, mielőtt időtúllépést okozna. |
| virtual void [SetLength](../../system.io/stream/setlength/)(**int64_t**) | Beállítja a jelenlegi objektum által képviselt adatfolyam hosszát. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n't. sablonparamétert gyenge mutatóvá állítja (a megosztott helyett). Lehetővé teszi a mutatók átkapcsolását a konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Visszaadja a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual void [Write](../../system.io/stream/write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Az adott bájt tömb megadott alintervallumát a stream-be írja. |
| virtual void [Write](../../system.io/stream/write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Az adott bájt tömb megadott alintervallumát a stream-be írja. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Az adott bájt tömb megadott alintervallumát a stream-be írja. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Az adott byte span megadott alintervallumát a stream-be írja. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon ír egy bájtsorozatot az aktuális adatfolyamba, a leírt bájtok számával előrelépteti a pozíciót, és figyeli a leállítási kéréseket. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Aszinkron módon ír egy bájtsorozatot az aktuális adatfolyamba, a leírt bájtok számával előrelépteti a pozíciót, és figyeli a leállítási kéréseket. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | A megadott 8-bites előjel nélküli egész értéket a stream-be írja. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Egy adatfolyam, amelynek nincs alatta lévő tárolója. |

## Lásd még

* Osztály [Stream](../../system.io/stream/)
* Névtér [System::Net::Security](../)
* Könyvtár [Aspose.Slides](../../)