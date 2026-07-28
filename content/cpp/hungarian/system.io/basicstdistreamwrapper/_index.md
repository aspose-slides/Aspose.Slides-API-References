---
title: BasicSTDIStreamWrapper
second_title: Aspose.Slides C++ API referencia
description: "Representál egy System.IO.Stream-szerű burkolót a std::basic_istream és származtatott objektumai számára. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mert ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót a függvények argumentumaként történő átadásra."
type: docs
weight: 14
url: /hu/system.io/basicstdistreamwrapper/
---
## BasicSTDIStreamWrapper osztály

A [System.IO.Stream](../stream/)-szerű burkolót képviseli a std::basic_istream és annak származtatott objektumai számára. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stack-en vagy az operator new használatával, mert ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót arra, hogy argumentumként átadja a függvényeknek.

```cpp
template<typename T,typename>class BasicSTDIStreamWrapper : public virtual System::IO::STDIOStreamWrapperBase<T>
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
|  [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(std::basic_istream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | Új példányt hoz létre a [BasicSTDIStreamWrapper](./)-ból. |
|  [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(const [BasicSTDIStreamWrapper](./)\&) | Másoló konstruktor. Törölve. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Aszinkron olvasási műveletet indít el. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Aszinkron írási műveletet indít el. |
| virtual void [Close](../stream/close/)() | Bezárja az adatfolyamot. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Byte-okat másol a megadott adatfolyamra. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Byte-okat másol a megadott adatfolyamra a megadott puffermérettel. |
| void [Dispose](../stream/dispose/)() override | Felszabadítja az aktuális objektum által használt összes erőforrást és bezárja az adatfolyamot. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Megvárja, amíg a megadott aszinkron olvasási művelet befejeződik. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Befejez egy aszinkron írási műveletet. Megvárja, amíg a megadott aszinkron írási művelet befejeződik. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| void [Flush](./flush/)() override | Törli az adatfolyam puffereit és kiírja az összes pufferelt adatot az alatta lévő tárolóba. Nem támogatott! |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon törli az adatfolyam összes puffert, az összes pufferelt adatot az alatta lévő eszközre írja, és figyeli a leállítási kéréseket. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Aszinkron módon törli az adatfolyam összes puffert, az összes pufferelt adatot az alatta lévő eszközre írja, és figyeli a leállítási kéréseket. |
| **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | Megállapítja, hogy az adatfolyam támogatja-e a keresést. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Értéket ad vissza, amely meghatározza, hogy az aktuális adatfolyam időtúllépést okozhat-e. |
| **bool** [get_CanWrite](../stdiostreamwrapperbase/get_canwrite/)() const override | Megállapítja, hogy az adatfolyam támogatja-e a írást. |
| **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | Visszaadja az adatfolyam hosszát. |
| **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | Visszaadja az adatfolyam aktuális pozícióját. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Értéket ad vissza milliszekundumban, amely meghatározza, mennyi ideig próbálja az adatfolyam olvasni, mielőtt időtúllépés következik. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Értéket ad vissza milliszekundumban, amely meghatározza, mennyi ideig próbálja az adatfolyam írni, mielőtt időtúllépés következik. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektumhoz kapcsolódó referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
| [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [BasicSTDIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDIStreamWrapper](./)\&) | Másoló hozzárendelő operátor. Törölve. |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Másoló hozzárendelő operátor. Törölve. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Hozzárendelő operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Ha a becsomagolási mód bináris, a megadott számú byte-ot olvassa a streamből, egyébként a megadott számú karaktert olvassa és **uint8_t** típusra konvertálja. Az olvasás eredményét a megadott byte tömbbe írja. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | A megadott számú byte-ot olvassa a streamből és a megadott byte tömbbe írja. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | A megadott számú byte-ot olvassa a streamből és a megadott byte tömbbe írja. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | A megadott számú byte-ot olvassa a streamből és a megadott byte span-be írja. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon beolvas egy byte sorozatot az aktuális streamből, a stream pozícióját a beolvasott byte-ok számával lépteti előre, és figyeli a leállítási kéréseket. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Aszinkron módon beolvas egy byte sorozatot az aktuális streamből, a stream pozícióját a beolvasott byte-ok számával lépteti előre, és figyeli a leállítási kéréseket. |
| int [ReadByte](./readbyte/)() override | Ha a becsomagolási mód bináris, egyetlen byte-ot olvas a legutóbbi dekódolt karakter tárolóból, egyébként egyetlen karaktert olvas a streamből és **uint8_t** típusra konvertálja. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | RTTI információ. |
| **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Beállítja az aktuális objektum által képviselt adatfolyam pozícióját. |
| void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | Beállítja az adatfolyam pozícióját. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Beállít egy értéket, amely meghatározza, hogy az aktuális adatfolyam időtúllépést okozhat-e. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Beállít egy értéket milliszekundumban, amely meghatározza, mennyi ideig próbálja az adatfolyam olvasni, mielőtt időtúllépés következik. |
| void [SetLength](./setlength/)(**int64_t**) override | Beállítja az aktuális objektum által képviselt adatfolyam hosszát. Nem támogatott! |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | A n-edik sablonargumentumot gyenge mutatóra állítja (nem megosztott). Lehetővé teszi a mutatók átkapcsolását konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referencia számláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Másoló konstruktor. Törölve. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Ha a becsomagolási mód bináris, a megadott byte tömbből a megadott részhalmazt írja az adatfolyamra, egyébként a megadott részhalmazt char_type típusra konvertálja, majd az eredményt írja az adatfolyamra. Nem támogatott! |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | A megadott byte tömbből a megadott részhalmazt írja az adatfolyamra. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | A megadott byte tömbből a megadott részhalmazt írja az adatfolyamra. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | A megadott byte spanből a megadott részhalmazt írja az adatfolyamra. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Aszinkron módon ír egy byte sorozatot az aktuális adatfolyamba, a stream pozícióját a megírt byte-ok számával lépteti előre, és figyeli a leállítási kéréseket. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Aszinkron módon ír egy byte sorozatot az aktuális adatfolyamba, a stream pozícióját a megírt byte-ok számával lépteti előre, és figyeli a leállítási kéréseket. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | Ha a becsomagolási mód bináris, az adott 8-bites unsigned egész értéket írja az adatfolyamra, egyébként konvertálja char_type típusra, majd az eredményt írja az adatfolyamra. Nem támogatott! |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static [Null](../stream/null/) | Egy adatfolyam, amelynek nincs alatta tárolója. |

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
* Névtere [System::IO](../)
* Könyvtár [Aspose.Slides](../../)