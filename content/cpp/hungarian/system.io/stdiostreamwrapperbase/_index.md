---
title: STDIOStreamWrapperBase
second_title: Aspose.Slides C++ API referencia
description: "A System.IO.Stream-hez hasonló csomagoló osztály alapja. Ennek az osztálynak az objektumait csak a System::MakeObject() függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy assertion hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr pointerbe, és ezt a pointert használja a függvények argumentumaként való átadáshoz."
type: docs
weight: 352
url: /hu/system.io/stdiostreamwrapperbase/
---
## STDIOStreamWrapperBase osztály

Representál egy alaposztályt a [System.IO.Stream](../stream/)-szerű csomagolók számára. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy assertion hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) pointerbe, és használja ezt a pointert a függvények argumentumaként történő átadásra.

```cpp
template<typename T,typename>class STDIOStreamWrapperBase : public System::IO::Stream
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Elindít egy aszinkron olvasási műveletet. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Elindít egy aszinkron írási műveletet. |
| virtual void [Close](../stream/close/)() | Bezárja a streamet. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Byte-okat másol a megadott streambe. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Byte-okat másol a megadott streambe, a megadott pufferméret használatával. |
| void [Dispose](../stream/dispose/)() override | Felszabadítja a jelenlegi objektum által használt összes erőforrást és bezárja a streamet. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Vár, amíg a megadott aszinkron olvasási művelet befejeződik. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Befejez egy aszinkron írási műveletet. Vár, amíg a megadott aszinkron írási művelet befejeződik. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szintaxis szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekintendő, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekintendő, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| virtual void [Flush](../stream/flush/)() | Törli ennek a streamnek a puffereit és az összes pufferelt adatot az alatta lévő tárolóba írja. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon törli a stream összes puffert, az esetleges pufferelt adatot az alatta lévő eszközbe írja, és figyeli a leállítási kéréseket. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Aszinkron módon törli a stream összes puffert, az esetleges pufferelt adatot az alatta lévő eszközbe írja, és figyeli a leállítási kéréseket. |
| **bool** [get_CanRead](./get_canread/)() const override | Megállapítja, hogy a stream támogatja-e az olvasást. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Megállapítja, hogy a stream támogatja-e a keresést. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Lekéri azt az értéket, amely meghatározza, hogy a jelenlegi stream időtúllépést engedélyez-e. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Megállapítja, hogy a stream támogatja-e az írást. |
| **int64_t** [get_Length](./get_length/)() const override | Visszaadja a stream hosszát. |
| **int64_t** [get_Position](./get_position/)() const override | Visszaadja a stream jelenlegi pozícióját. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Lekéri azt az értéket ezredmásodpercben, amely meghatározza, mennyi ideig próbálja a stream az olvasást időtúllépés előtt. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Lekéri azt az értéket ezredmásodpercben, amely meghatározza, mennyi ideig próbálja a stream az írást időtúllépés előtt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) felügyeleti objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másolókonstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [STDIOStreamWrapperBase](./)\& [operator=](./operator_equal/)(const [STDIOStreamWrapperBase](./)\&) | Másolás-értékadó operátor. Törölve. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| virtual **int32_t** [Read](../stream/read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Olvassa a megadott számú byte-ot a streamből és a megadott byte tömbbe írja. |
| virtual **int32_t** [Read](../stream/read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Olvassa a megadott számú byte-ot a streamből és a megadott byte tömbbe írja. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Olvassa a megadott számú byte-ot a streamből és a megadott byte tömbbe írja. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Olvassa a megadott számú byte-ot a streamből és a megadott byte span-be írja. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon olvas egy byte sorozatot a jelenlegi streamből, előrehalad a streamben a beolvasott byte-ok számával, és figyeli a leállítási kéréseket. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Aszinkron módon olvas egy byte sorozatot a jelenlegi streamből, előrehalad a streamben a beolvasott byte-ok számával, és figyeli a leállítási kéréseket. |
| virtual int [ReadByte](../stream/readbyte/)() | Olvas egyetlen byte-ot a streamből és egy 32 bites egész értéket ad vissza, ami megegyezik az olvasott byte értékével. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia-szerűen hasonlítja össze az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](./thistype/), [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/)) | RTTI információ. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Beállítja a jelenlegi objektum által reprezentált stream pozícióját. |
| void [set_Position](./set_position/)(**int64_t**) override | Beállítja a stream pozícióját. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Beállít egy értéket, amely meghatározza, hogy a jelenlegi stream időtúllépést engedélyez-e. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Beállít egy értéket ezredmásodpercben, amely meghatározza, mennyi ideig próbálja a stream az olvasást időtúllépés előtt. |
| virtual void [SetLength](../stream/setlength/)(**int64_t**) | Beállítja a jelenlegi objektum által reprezentált stream hosszát. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | A n-edik sablonargumentumot gyenge pointerre állítja (a megosztott helyett). Lehetővé teszi a pointerek átkapcsolását konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
|  [STDIOStreamWrapperBase](./stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](./)\&) | Másolókonstruktor. Törölve. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) felügyeleti objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual void [Write](../stream/write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | A megadott byte tömbből a megadott részhalmaz byte-ot írja a streambe. |
| virtual void [Write](../stream/write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | A megadott byte tömbből a megadott részhalmaz byte-ot írja a streambe. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | A megadott byte tömbből a megadott részhalmaz byte-ot írja a streambe. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | A megadott byte spabból a megadott részhalmaz byte-ot írja a streambe. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon ír egy byte sorozatot a jelenlegi streambe, előrehalad a streamben a beírt byte-ok számával, és figyeli a leállítási kéréseket. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Aszinkron módon ír egy byte sorozatot a jelenlegi streambe, előrehalad a streamben a beírt byte-ok számával, és figyeli a leállítási kéréseket. |
| virtual void [WriteByte](../stream/writebyte/)(**uint8_t**) | A megadott 8 bites előjeles nélküli egész értéket írja a streambe. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static [Null](../stream/null/) | Egy stream, amelynek nincs alatta lévő tárolója. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |

## Lásd még

* Osztály [Stream](../stream/)
* Névtér [System::IO](../)
* Könyvtár [Aspose.Slides](../../)