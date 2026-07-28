---
title: BasicSTDOStreamWrapper
second_title: Aspose.Slides C++ API Referencia
description: "System.IO.Stream-szerű csomagolót képvisel a std::basic_ostream és származtatott objektumai számára. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót a függvények argumentumaként."
type: docs
weight: 27
url: /hu/system.io/basicstdostreamwrapper/
---
## BasicSTDOStreamWrapper osztály

Representál egy [System.IO.Stream](../stream/)-szerű csomagolót a std::basic_ostream és származtatott objektumai számára. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót a függvények argumentumaként.

```cpp
template<typename T,typename>class BasicSTDOStreamWrapper : public virtual System::IO::STDIOStreamWrapperBase<T>
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
|  [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)(std::basic_ostream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | Létrehoz egy új példányt a [BasicSTDOStreamWrapper](./)-ból. |
|  [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)(const [BasicSTDOStreamWrapper](./)\&) | Másoló konstruktor. Törölve. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Elindít egy aszinkron olvasási műveletet. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Elindít egy aszinkron írási műveletet. |
| virtual void [Close](../stream/close/)() | Bezárja a streamet. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Másolja a bájtokat a megadott streambe. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Másolja a bájtokat a megadott streambe, a megadott pufferméret használatával. |
| void [Dispose](../stream/dispose/)() override | Felszabadítja az aktuális objektum által használt összes erőforrást és bezárja a streamet. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Várakozik, amíg a megadott aszinkron olvasási művelet befejeződik. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Befejez egy aszinkron írási műveletet. Várakozik, amíg a megadott aszinkron írási művelet befejeződik. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-szerű lebegőpontos összehasonlítást szimulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-szerű lebegőpontos összehasonlítást szimulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| void [Flush](./flush/)() override | Kiüríti a stream puffereit, és a tárolt adatokat az alapul szolgáló tárolóba írja. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon kiüríti a stream összes puffert, a pufferezett adatokat az alapul szolgáló eszközbe írja, és figyeli a megszakítási kéréseket. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Aszinkron módon kiüríti a stream összes puffert, a pufferezett adatokat az alapul szolgáló eszközbe írja, és figyeli a megszakítási kéréseket. |
| **bool** [get_CanRead](../stdiostreamwrapperbase/get_canread/)() const override | Megállapítja, hogy a stream támogatja-e az olvasást. |
| **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | Megállapítja, hogy a stream támogatja-e a keresést. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Visszaad egy értéket, amely meghatározza, hogy az aktuális stream időtúllépést szenved-e. |
| **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | Visszaadja a stream hosszát. |
| **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | Visszaadja a stream aktuális pozícióját. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Visszaad egy értéket (ezredmásodpercben), amely meghatározza, mennyi ideig próbál a stream olvasni, mielőtt időtúllépés történik. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Visszaad egy értéket (ezredmásodpercben), amely meghatározza, mennyi ideig próbál a stream írni, mielőtt időtúllépés történik. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Visszaadja az objektumhoz tartozó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Visszaadja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| [BasicSTDOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDOStreamWrapper](./)\&) | Másoló hozzárendelő operátor. Törölve. |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Másoló hozzárendelő operátor. Törölve. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Hozzárendelő operátor. Valójában semmit sem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Ha a csomagolási mód bináris, a megadott számú bájtot olvassa a streamből, egyébként a megadott számú karaktert, és **uint8_t** típusra konvertálja. Az olvasás eredményét a megadott bájt tömbbe írja. Nem támogatott! |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | A megadott számú bájtot olvassa a streamből, és a megadott bájt tömbbe írja. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | A megadott számú bájtot olvassa a streamből, és a megadott bájt tömbbe írja. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | A megadott számú bájtot olvassa a streamből, és a megadott bájt spánba írja. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon olvas egy bájtszekvenciát az aktuális streamből, a stream pozícióját a beolvasott bájtok számával lépteti előre, és figyeli a megszakítási kéréseket. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Aszinkron módon olvas egy bájtszekvenciát az aktuális streamből, a stream pozícióját a beolvasott bájtok számával lépteti előre, és figyeli a megszakítási kéréseket. |
| int [ReadByte](./readbyte/)() override | Ha a csomagolási mód bináris, egyetlen bájtot olvas az utoljára dekódolt karaktertárolóból, egyébként egy karaktert a streamből, és **uint8_t** típusra konvertálja. Nem támogatott! |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | RTTI információ. |
| **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Beállítja a stream pozícióját, amelyet az aktuális objektum képvisel. |
| void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | Beállítja a stream pozícióját. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Beállít egy értéket, amely meghatározza, hogy az aktuális stream időtúllépést szenvedhet-e. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Beállít egy értéket (ezredmásodpercben), amely meghatározza, mennyi ideig próbál a stream olvasni, mielőtt időtúllépés történik. |
| void [SetLength](./setlength/)(**int64_t**) override | Beállítja a stream hosszát, amelyet az aktuális objektum képvisel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (a megosztott helyett). Lehetővé teszi a mutatók átkapcsolását a tárolókban gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Visszaadja a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Másoló konstruktor. Törölve. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Ha a csomagolási mód bináris, a megadott bájttartományt a megadott bájt tömbből a streambe írja, egyébként a megadott bájttartományt a bájt tömbből char_type típusra konvertálja, és az eredményt a streambe írja. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | A megadott bájttartományt a megadott bájt tömbből a streambe írja. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | A megadott bájttartományt a megadott bájt tömbből a streambe írja. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | A megadott bájttartományt a megadott bájt spánból a streambe írja. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon ír egy bájtszekvenciát az aktuális streambe, a stream aktuális pozícióját a megírt bájtok számával lépteti előre, és figyeli a megszakítási kéréseket. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Aszinkron módon ír egy bájtszekvenciát az aktuális streambe, a stream aktuális pozícióját a megírt bájtok számával lépteti előre, és figyeli a megszakítási kéréseket. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | Ha a csomagolási mód bináris, a megadott 8-bites unsigned egész értéket a streambe írja, egyébként char_type típusra konvertálja, majd az eredményt a streambe írja. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static [Null](../stream/null/) | Egy stream alaptároló nélkül. |

## Typedefek

| Typedef | Leírás |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |

## Lásd még

* Osztály [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)
* Névtér [System::IO](../)
* Könyvtár [Aspose.Slides](../../)