---
title: FileStream
second_title: Aspose.Slides for C++ API-referencia
description: "Egy szinkron és aszinkron olvasási és írási műveleteket támogató fájl adatfolyamot képvisel. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mert ez futási hibákat és/vagy aszertációs hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és ezt a mutatót használja a függvényeknek argumentumként történő átadáshoz."
type: docs
weight: 287
url: /hu/system.io/filestream/
---
## FileStream osztály


A fájl adatfolyamot képviseli, amely szinkron és aszinkron olvasási és írási műveleteket támogat. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futási hibákat és/vagy aszertációs hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és ezt a mutatót használja a függvények argumentumaként.

```cpp
class FileStream : public System::IO::Stream
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Elindít egy aszinkron olvasási műveletet. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Elindít egy aszinkron írási műveletet. |
| void [Close](./close/)() override | Bezárja a jelenlegi [FileStream](./) objektumot. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Byte-okat másol a megadott adatfolyamra. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Byte-okat másol a megadott adatfolyamra a megadott puffermérettel. |
| void [Dispose](../stream/dispose/)() override | Felszabadítja a jelenlegi objektum által használt összes erőforrást, és bezárja az adatfolyamot. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Vár, amíg a megadott aszinkron olvasási művelet be nem fejeződik. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Befejez egy aszinkron írási műveletet. Vár, amíg a megadott aszinkron írási művelet be nem fejeződik. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szintaxis szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | Létrehoz egy új példányt a [FileStream](./) osztályból, és inicializálja a megadott paraméterekkel. |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/), **int32_t**, [FileOptions](../fileoptions/)) | Létrehoz egy új példányt a [FileStream](./) osztályból, és inicializálja a megadott paraméterekkel. |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/), **int32_t**, **bool**) | Létrehoz egy új példányt a [FileStream](./) osztályból, és inicializálja a megadott paraméterekkel. |
|  [FileStream](./filestream/)(const [FileStream](./)\&) |  |
| void [Flush](./flush/)() override | Kiüríti az adatfolyam puffereit, és az összes pufferelt adatot a mögöttes fájlba írja. |
| void [Flush](./flush/)(**bool**) | Kiüríti az adatfolyam puffereit, és az összes pufferelt adatot a mögöttes fájlba írja. Szinonima a [Flush()](./flush/) metódusra. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | Aszinkron módon kiüríti az adatfolyam összes puffert, elvégzi a pufferelt adatok írását a mögöttes eszközre, és figyeli a leállítási kérelmeket. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Aszinkron módon kiüríti az adatfolyam összes puffert, elvégzi a pufferelt adatok írását a mögöttes eszközre, és figyeli a leállítási kérelmeket. |
| **bool** [get_CanRead](./get_canread/)() const override | Megállapítja, hogy az adatfolyam olvasható-e. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Megállapítja, hogy az adatfolyam támogatja-e a pozicionálást. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Megkap egy értéket, amely meghatározza, hogy a jelenlegi adatfolyam időtúlléphető-e. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Megállapítja, hogy az adatfolyam írható-e. |
| **int64_t** [get_Length](./get_length/)() const override | Visszaadja az adatfolyam hosszát bájtokban. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Visszaadja a jelenlegi [FileStream](./) objektum által kapszulázott fájl nevét. |
| **int64_t** [get_Position](./get_position/)() const override | Visszaadja az adatfolyam aktuális pozícióját. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Megkap egy értéket ezredmásodpercben, amely meghatározza, mennyi ideig próbálja az adatfolyam az olvasást időtúllépés előtt. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Megkap egy értéket ezredmásodpercben, amely meghatározza, mennyi ideig próbálja az adatfolyam az írást időtúllépés előtt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektumhoz társított referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzés, hogy az objektum a targetType által leírt típus egy példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívd közvetlenül vagy használd a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [FileStream](./)\& [operator=](./operator_equal/)(const [FileStream](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Beolvassa a megadott számú byte-ot az adatfolyamból, és a megadott bájt tömbbe írja. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Beolvassa a megadott számú byte-ot az adatfolyamból, és a megadott bájt tömbbe írja. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Beolvassa a megadott számú byte-ot az adatfolyamból, és a megadott bájt tömbbe írja. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Beolvassa a megadott számú byte-ot az adatfolyamból, és a megadott byte-span-be írja. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | Aszinkron módon beolvas egy bájtsorozatot a jelenlegi adatfolyamból, a pozíciót a beolvasott bájtok számával előre mozgatja, és figyeli a leállítási kérelmeket. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Aszinkron módon beolvas egy bájtsorozatot a jelenlegi adatfolyamból, a pozíciót a beolvasott bájtok számával előre mozgatja, és figyeli a leállítási kérelmeket. |
| **int32_t** [ReadByte](./readbyte/)() override | Beolvas egyetlen byte-ot az adatfolyamból, és visszaad egy 32 bites egész értéket, amely megegyezik a beolvasott byte értékével. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípusú objektumot referencia szerint hasonlít össze a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Beállítja a jelenlegi objektum által képviselt adatfolyam pozícióját. |
| void [set_Position](./set_position/)(**int64_t**) override | Kiüríti az adatfolyamot, majd beállítja a pozíciót. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Beállít egy értéket, amely meghatározza, hogy a jelenlegi adatfolyam időtúlléphető-e. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Beállít egy értéket ezredmásodpercben, amely meghatározza, mennyi ideig próbálja az adatfolyam az olvasást időtúllépés előtt. |
| void [SetLength](./setlength/)(**int64_t**) override | Beállítja a jelenlegi objektum által képviselt adatfolyam hosszát. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | A n-edik sablonargumentumot gyenge mutatóként (nem megosztott) állítja be. Lehetővé teszi a mutatók átkapcsolását a tárolókban gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használj okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használj okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívd közvetlenül vagy használd a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használj okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használj okos mutatókat vagy ThisProtector-t. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | A megadott bájt-tömbből a megadott részlet byte-okat az adatfolyamba írja. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | A megadott bájt-tömbből a megadott részlet byte-okat az adatfolyamba írja. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | A megadott bájt-tömbből a megadott részlet byte-okat az adatfolyamba írja. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | A megadott byte-span-ből a megadott részlet byte-okat az adatfolyamba írja. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | Aszinkron módon ír egy bájtsorozatot a jelenlegi adatfolyamba, a pozíciót a leírt bájtok számával előre mozgatja, és figyeli a leállítási kérelmeket. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Aszinkron módon ír egy bájtsorozatot a jelenlegi adatfolyamba, a pozíciót a leírt bájtok számával előre mozgatja, és figyeli a leállítási kérelmeket. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | A megadott 8 bites előjel nélküli egész értéket az adatfolyamba írja. |
|  [~FileStream](./~filestream/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static constexpr [DefaultBufferSize](./defaultbuffersize/) | Az olvasási és írási műveletek során pufferelt byte-ok alapértelmezett száma. |
| static [Null](../stream/null/) | Egy adatfolyam, amelynek nincs alatta tárolása. |

## Lásd még

* Osztály [Stream](../stream/)
* Névterület [System::IO](../)
* Könyvtár [Aspose.Slides](../../)