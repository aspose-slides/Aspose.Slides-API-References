---
title: UnmanagedMemoryStream
second_title: Aspose.Slides C++ API Referencia
description: "Hozzáférést biztosít a nem kezelt memóriához. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy a new operátorral, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az argumentumként való átadáshoz a függvényeknek."
type: docs
weight: 456
url: /hu/system.io/unmanagedmemorystream/
---
## UnmanagedMemoryStream osztály

Biztosít hozzáférést a nem kezelt memóriához. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy a new operátorral, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) pointerbe, és használja ezt a pointert az argumentumként való átadáshoz a függvényeknek.

```cpp
class UnmanagedMemoryStream : public System::IO::Stream
```

## Metódusok

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Elindít egy aszinkron olvasási műveletet. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Elindít egy aszinkron írási műveletet. |
| virtual void [Close](../stream/close/)() | Lezárja az adatfolyamot. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Másolja a bájtokat a megadott adatfolyamba. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Másolja a bájtokat a megadott adatfolyamba a megadott puffermérettel. |
| void [Dispose](../stream/dispose/)() override | Felszabadítja a jelen objektum által használt összes erőforrást, és lezárja az adatfolyamot. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Várakozik, amíg a megadott aszinkron olvasási művelet be nem fejeződik. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Befejezi az aszinkron írási műveletet. Várakozik, amíg a megadott aszinkron írási művelet be nem fejeződik. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulálja a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekintendő, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulálja a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekintendő, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| void [Flush](./flush/)() override | Nem csinál semmit. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon törli ennek az adatfolyamnak az összes puffert, az összegyűjtött adatokat a mögöttes eszközbe írja, és figyeli a leállítási kéréseket. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Aszinkron módon törli ennek az adatfolyamnak az összes puffert, az összegyűjtött adatokat a mögöttes eszközbe írja, és figyeli a leállítási kéréseket. |
| **bool** [get_CanRead](./get_canread/)() const override | Megállapítja, hogy az adatfolyam olvasható-e. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Megállapítja, hogy az adatfolyam támogatja-e a pozicionálást. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Lekér egy értéket, amely meghatározza, hogy a jelenlegi adatfolyam időtúlléphet-e. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Megállapítja, hogy az adatfolyam írható-e. |
| virtual **int64_t** [get_Capacity](./get_capacity/)() const | Visszaadja a mögöttes memória puffer jelenlegi kapacitását. |
| **int64_t** [get_Length](./get_length/)() const override | Visszaadja az adatfolyam hosszát bájtokban. |
| **int64_t** [get_Position](./get_position/)() const override | Visszaadja az adatfolyam jelenlegi pozícióját. |
| **uint8_t** * [get_PositionPointer](./get_positionpointer/)() | NEM KIVITELEZETT. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Lekér egy értéket ezredmásodpercben, amely meghatározza, mennyi ideig próbálja meg a stream olvasni, mielőtt időtúllépés történik. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Lekér egy értéket ezredmásodpercben, amely meghatározza, mennyi ideig próbálja meg a stream írni, mielőtt időtúllépés történik. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekérdezi az objektumhoz tartozó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekérdezi az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak inicializálja az új objektumot, és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak inicializálja az új objektumot, és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Olvasza a megadott számú bájtot az adatfolyamból, és a megadott bájt tömbbe írja. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Olvasza a megadott számú bájtot az adatfolyamból, és a megadott bájt tömbbe írja. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Olvasza a megadott számú bájtot az adatfolyamból, és a megadott bájt tömbbe írja. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Olvasza a megadott számú bájtot az adatfolyamból, és a megadott bájt spannba írja. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon olvas egy bájtsorozatot a jelenlegi adatfolyamból, a pozíciót a beolvasott bájtok számával növeli, és figyeli a leállítási kéréseket. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Aszinkron módon olvas egy bájtsorozatot a jelenlegi adatfolyamból, a pozíciót a beolvasott bájtok számával növeli, és figyeli a leállítási kéréseket. |
| virtual int [ReadByte](../stream/readbyte/)() | Olvas egy egyetlen bájtot az adatfolyamból, és visszaad egy 32 bites egész értéket, amely megegyezik a beolvasott bájt értékével. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciaként hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciaként hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Beállítja a jelen objektum által képviselt adatfolyam pozícióját. |
| void [set_Position](./set_position/)(**int64_t**) override | Beállítja az adatfolyam pozícióját. |
| void [set_PositionPointer](./set_positionpointer/)(**uint8_t** *) | NEM KIVITELEZETT. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Beállít egy értéket, amely meghatározza, hogy a jelen adatfolyam időtúlléphet-e. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Beállít egy értéket ezredmásodpercben, amely meghatározza, mennyi ideig próbálja meg az adatfolyam olvasni, mielőtt időtúllépés történik. |
| void [SetLength](./setlength/)(**int64_t**) override | NEM KIVITELEZETT. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (nem megosztott). Lehetővé teszi a mutatók konténerben való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekérdezi a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi az egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
|  [UnmanagedMemoryStream](./unmanagedmemorystream/)(**uint8_t** *, **int64_t**) | Létrehoz egy új példányt a [UnmanagedMemoryStream](./)-ból. |
|  [UnmanagedMemoryStream](./unmanagedmemorystream/)(**uint8_t** *, **int64_t**, **int64_t**, [FileAccess](../fileaccess/)) | Létrehoz egy új példányt a [UnmanagedMemoryStream](./)-ból. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | NEM KIVITELEZETT. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | NEM KIVITELEZETT. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Az adott bájt tömb megadott részletét írja az adatfolyamba. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Az adott bájt span megadott részletét írja az adatfolyamba. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon ír egy bájtsorozatot a jelen adatfolyamba, a pozíciót a megírt bájtok számával növeli, és figyeli a leállítási kéréseket. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Aszinkron módon ír egy bájtsorozatot a jelen adatfolyamba, a pozíciót a megírt bájtok számával növeli, és figyeli a leállítási kéréseket. |
| virtual void [WriteByte](../stream/writebyte/)(**uint8_t**) | Az adott előjel nélküli 8-bites egész értéket írja az adatfolyamba. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Mezők

| Field | Description |
| --- | --- |
| static [Null](../stream/null/) | Egy adatfolyam mögöttes tároló nélkül. |

## Lásd még

* Osztály [Stream](../stream/)
* Névtér [System::IO](../)
* Könyvtár [Aspose.Slides](../../)