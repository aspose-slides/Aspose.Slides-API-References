---
title: BasicSTDIOStreamWrapper
second_title: Aspose.Slides C++ API referencia
description: "A System.IO.Stream-szerű burkolót képviseli a std::basic_iostream és annak származtatott objektumaihoz. Ennek az osztálynak az objektumait csak a System::MakeObject() függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stackben vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat okozhat. Mindig burkolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az argumentumként való átadásra a függvényeknek."
type: docs
weight: 1
url: /hu/system.io/basicstdiostreamwrapper/
---
## BasicSTDIOStreamWrapper osztály


Egy [System.IO.Stream](../stream/)-szerű burkolót képvisel a std::basic_iostream és annak származtatott objektumaihoz. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a veremben vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig burkolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót a függvények argumentumaként.

```cpp
template<typename T,typename>class BasicSTDIOStreamWrapper : public System::IO::BasicSTDIStreamWrapper<T>,
                                                             public System::IO::BasicSTDOStreamWrapper<T>
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
|  [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/)(std::basic_iostream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/), [STDIOStreamPositionPreference](../stdiostreampositionpreference/)) | Új példányt hoz létre a [BasicSTDIOStreamWrapper](./)-ból. |
|  [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/)(const [BasicSTDIOStreamWrapper](./)\&) | Másoló konstruktor. Törölve. |
|  [BasicSTDIStreamWrapper](../basicstdistreamwrapper/basicstdistreamwrapper/)(std::basic_istream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | Új példányt hoz létre a [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)-ból. |
|  [BasicSTDIStreamWrapper](../basicstdistreamwrapper/basicstdistreamwrapper/)(const [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)\&) | Másoló konstruktor. Törölve. |
|  [BasicSTDOStreamWrapper](../basicstdostreamwrapper/basicstdostreamwrapper/)(std::basic_ostream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | Új példányt hoz létre a [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)-ból. |
|  [BasicSTDOStreamWrapper](../basicstdostreamwrapper/basicstdostreamwrapper/)(const [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)\&) | Másoló konstruktor. Törölve. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Elindít egy aszinkron olvasási műveletet. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Elindít egy aszinkron írási műveletet. |
| virtual void [Close](../stream/close/)() | Bezárja az adatfolyamot. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Átmásolja a bájtokat a megadott adatfolyamba. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Átmásolja a bájtokat a megadott adatfolyamba, a megadott puffermérettel. |
| void [Dispose](../stream/dispose/)() override | Felszabadítja az aktuális objektum által használt összes erőforrást és bezárja az adatfolyamot. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Vár, amíg a megadott aszinkron olvasási művelet befejeződik. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Befejez egy aszinkron írási műveletet. Vár, amíg a megadott aszinkron írási művelet befejeződik. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantikával hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| void [Flush](./flush/)() override | Kiüríti ennek az adatfolyamnak a puffereit, és az összes pufferelt adatot az alapul szolgáló tárolóba írja. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon kiüríti az összes puffert ebben az adatfolyamban, az összes pufferelt adatot az alapul szolgáló eszközbe írja, és figyeli a leállítási kéréseket. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Aszinkron módon kiüríti az összes puffert ebben az adatfolyamban, az összes pufferelt adatot az alapul szolgáló eszközbe írja, és figyeli a leállítási kéréseket. |
| **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | Megállapítja, hogy az adatfolyam támogatja-e a pozíciómozgatást. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Visszaad egy értéket, amely meghatározza, hogy az aktuális adatfolyam időtúlléphet-e. |
| **bool** [get_CanWrite](../stdiostreamwrapperbase/get_canwrite/)() const override | Megállapítja, hogy az adatfolyam támogatja-e a írást. |
| **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | Visszaadja az adatfolyam hosszát. |
| **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | Visszaadja az adatfolyam aktuális pozícióját. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Visszaad egy értéket milliszekundumban, amely meghatározza, mennyi ideig próbálja az adatfolyam az olvasást, mielőtt időtúllépés következik be. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Visszaad egy értéket milliszekundumban, amely meghatározza, mennyi ideig próbálja az adatfolyam az írást, mielőtt időtúllépés következik be. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Visszaadja az objektumhoz társított referencia számláló adatstruktúráját. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Visszaadja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus egy példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | A C# lock() utasítás zárolását valósítja meg. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstruktorát. |
| [BasicSTDIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDIOStreamWrapper](./)\&) | Másoló értékadás operátor. Törölve. |
| [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)\& [operator=](../basicstdistreamwrapper/operator_equal/)(const [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)\&) | Másoló értékadás operátor. Törölve. |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Másoló értékadás operátor. Törölve. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadás operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstruktorát. |
| [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)\& [operator=](../basicstdostreamwrapper/operator_equal/)(const [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)\&) | Másoló értékadás operátor. Törölve. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Ha a csomagolási mód bináris, a megadott számú bájtot olvassa az adatfolyamból, egyébként a megadott számú karaktert olvassa, és **uint8_t** típusra konvertálja. A beolvasás eredményét a megadott bájt tömbbe írja. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | A megadott számú bájtot olvassa az adatfolyamból és a megadott bájt tömbbe írja. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | A megadott számú bájtot olvassa az adatfolyamból és a megadott bájt tömbbe írja. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | A megadott számú bájtot olvassa az adatfolyamból és a megadott bájt spannra írja. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon beolvas egy bájtsorozatot az aktuális adatfolyamból, a pozíciót a beolvasott bájtok számával előre lépteti, és figyeli a leállítási kéréseket. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Aszinkron módon beolvas egy bájtsorozatot az aktuális adatfolyamból, a pozíciót a beolvasott bájtok számával előre lépteti, és figyeli a leállítási kéréseket. |
| int [ReadByte](./readbyte/)() override | Ha a csomagolási mód bináris, egyetlen bájtot olvas az utoljára dekódolt karakter tárolóból, egyébként egy karaktert olvas az adatfolyamból és **uint8_t** típusra konvertálja. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Érték típusú objektumot referenciával hasonlít össze a nullptr-vel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | RTTI információ. |
| **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Beállítja az áramlat pozícióját, amelyet az aktuális objektum képvisel. |
| void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | Beállítja az adatfolyam pozícióját. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Beállít egy értéket, amely meghatározza, hogy az aktuális adatfolyam időtúlléphet-e. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Beállít egy értéket milliszekundumban, amely meghatározza, mennyi ideig próbálja az adatfolyam az olvasást, mielőtt időtúllépés következik be. |
| void [SetLength](./setlength/)(**int64_t**) override | Beállítja az adatfolyam hosszát, amelyet az aktuális objektum képvisel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablon argumentumot gyenge mutatóként (a megosztott helyett). Lehetővé teszi a konténerekben lévő mutatók gyenge módra való átváltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Visszaadja a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Másoló konstruktor. Törölve. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | A C# lock() utasítás feloldását valósítja meg. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Ha a csomagolási mód bináris, a megadott bájt tömb egy meghatározott alrészt a streambe írja, egyébként a megadott alrészt **char_type** típusra konvertálja, majd az eredményt a streambe írja. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | A megadott bájt tömb egy meghatározott alrészt a streambe írja. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | A megadott bájt tömb egy meghatározott alrészt a streambe írja. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | A megadott bájt span egy meghatározott alrészt a streambe írja. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon ír egy bájtsorozatot az aktuális adatfolyamba, a pozíciót az írt bájtok számával előre lépteti, és figyeli a leállítási kéréseket. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Aszinkron módon ír egy bájtsorozatot az aktuális adatfolyamba, a pozíciót az írt bájtok számával előre lépteti, és figyeli a leállítási kéréseket. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | Ha a csomagolási mód bináris, a megadott 8 bit előjeles egész értéket írja a streambe, egyébként **char_type** típusra konvertálja, majd az eredményt írja a streambe. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static [Null](../stream/null/) | A stream with no underlying storage. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [BaseIType](./baseitype/) |  |
| [BaseOType](./baseotype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |

## Lásd még

* Osztály [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)
* Osztály [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)
* Névtere [System::IO](../)
* Könyvtár [Aspose.Slides](../../)