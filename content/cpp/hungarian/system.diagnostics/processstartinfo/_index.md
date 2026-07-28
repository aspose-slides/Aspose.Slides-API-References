---
title: ProcessStartInfo
second_title: Aspose.Slides for C++ API Referencia
description: "Leírja a folyamat indítási paramétereit. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból stack-en vagy az new operátorral, mert ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót a függvényeknek argumentumként történő átadásához."
type: docs
weight: 40
url: /hu/system.diagnostics/processstartinfo/
---
## ProcessStartInfo osztály


Leírja a folyamat indítási paramétereit. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból stack-en vagy az new operátorral, mert ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót a függvényeknek argumentumként történő átadásához.

```cpp
class ProcessStartInfo : public System::Object
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat C# stílusban hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat C# stílusban hasonlít össze. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | A C#-stílusú lebegőpontos összehasonlítást utánozza, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | A C#-stílusú lebegőpontos összehasonlítást utánozza, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| [String](../../system/string/) [get_Arguments](./get_arguments/)() const | A folyamat argumentumait adja vissza. |
| **bool** [get_CreateNoWindow](./get_createnowindow/)() const | A NoWindow tulajdonságot adja vissza. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [get_EnvironmentVariables](./get_environmentvariables/)() const | A folyamat környezeti változóit adja vissza. |
| [String](../../system/string/) [get_FileName](./get_filename/)() const | A folyamat fájlnevet adja vissza. |
| **bool** [get_RedirectStandardError](./get_redirectstandarderror/)() const | A RedirectStandardError tulajdonságot adja vissza. |
| **bool** [get_RedirectStandardInput](./get_redirectstandardinput/)() const | A RedirectStandardInput tulajdonságot adja vissza. |
| **bool** [get_RedirectStandardOutput](./get_redirectstandardoutput/)() const | A RedirectStandardOutput tulajdonságot adja vissza. |
| **bool** [get_UseShellExecute](./get_useshellexecute/)() const | A UseShellExecute tulajdonságot adja vissza. |
| [ProcessWindowStyle](../processwindowstyle/) [get_WindowStyle](./get_windowstyle/)() const | Az ablakstílust adja vissza. |
| [String](../../system/string/) [get_WorkingDirectory](./get_workingdirectory/)() const | A folyamat munkakönyvtárát adja vissza. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Az objektumhoz társított referenciaszámláló adatstruktúrát adja vissza. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Az objektum tényleges típusát adja vissza. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | A C# lock() utasítás zárolását valósítja meg. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktőr. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Átadás operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstruktorát. |
|  [ProcessStartInfo](./processstartinfo/)() | Üres start info objektumot hoz létre. |
|  [ProcessStartInfo](./processstartinfo/)(const [String](../../system/string/)\&) | Start info objektumot hoz létre. |
|  [ProcessStartInfo](./processstartinfo/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Start info objektumot hoz létre. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípusú objektumot nullptr-vel való referencia-összehasonlításra használja. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_Arguments](./set_arguments/)(const [String](../../system/string/)\&) | Beállítja a folyamat argumentumait. |
| void [set_CreateNoWindow](./set_createnowindow/)(**bool**) | Beállítja a NoWindow tulajdonságot. |
| void [set_FileName](./set_filename/)(const [String](../../system/string/)\&) | Beállítja a folyamat fájlnevet. |
| void [set_RedirectStandardError](./set_redirectstandarderror/)(**bool**) | Beállítja a RedirectStandardError tulajdonságot. |
| void [set_RedirectStandardInput](./set_redirectstandardinput/)(**bool**) | Beállítja a RedirectStandardInput tulajdonságot. |
| void [set_RedirectStandardOutput](./set_redirectstandardoutput/)(**bool**) | Beállítja a RedirectStandardOutput tulajdonságot. |
| void [set_UseShellExecute](./set_useshellexecute/)(**bool**) | Beállítja a UseShellExecute tulajdonságot. |
| void [set_WindowStyle](./set_windowstyle/)([ProcessWindowStyle](../processwindowstyle/)) | Beállítja az ablakstílust. |
| void [set_WorkingDirectory](./set_workingdirectory/)(const [String](../../system/string/)\&) | Beállítja a folyamat munkakönyvtárát. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | A n-edik sablonargumentumot gyenge mutatóra állítja (a megosztott helyett). Lehetővé teszi a mutatók konténerben való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | A megosztott referenciaszámláló aktuális értékét adja vissza. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | A C# typeof([System.Object](../../system/object/)) konstrukciót valósítja meg. |
| void [Unlock](../../system/object/unlock/)() | A C# lock() utasítás feloldását valósítja meg. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtér [System::Diagnostics](../)
* Könyvtár [Aspose.Slides](../../)