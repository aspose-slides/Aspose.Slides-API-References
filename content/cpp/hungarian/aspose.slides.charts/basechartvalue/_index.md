---
title: BaseChartValue
second_title: Aspose.Slides C++ API hivatkozás
description: Egy diagram értékét képviseli.
type: docs
weight: 40
url: /hu/aspose.slides.charts/basechartvalue/
---
## BaseChartValue osztály


Egy diagram értékét képviseli.

```cpp
class BaseChartValue : public virtual Aspose::Slides::Charts::IBaseChartValue,
                       public Aspose::Slides::IDOMObject
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | A C#-stílusú lebegőpontos összehasonlítást utánozza, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | A C#-stílusú lebegőpontos összehasonlítást utánozza, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Data](./get_data/)() | Adat. Olvasás [System::Object](../../system/object/). |
| [Aspose::Slides::Charts::DataSourceType](../datasourcetype/) [get_DataSourceType](./get_datasourcetype/)() override | Megadja, hogy az AsCell, AsCells, AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az leszármazottakban. Más szóval a Data tulajdonság értékének típusát határozza meg. Olvasás [Charts::DataSourceType](../datasourcetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | A objektumhoz társított referenciaszámláló adatstruktúrát adja vissza. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Az objektum tényleges típusát adja vissza. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | A C# lock() utasítás zárolását valósítja meg. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentry objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak újat hoz létre és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak újat hoz létre és lehetővé teszi az alosztályok másoló konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-vel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [set_Data](./set_data/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Adat. Írás [System::Object](../../system/object/). |
| void [set_DataSourceType](./set_datasourcetype/)([Aspose::Slides::Charts::DataSourceType](../datasourcetype/)) override | Megadja, hogy az AsCell, AsCells, AsLiteralString vagy AsLiteralDouble tulajdonság valós-e az leszármazottakban. Más szóval a Data tulajdonság értékének típusát határozza meg. Írás [Charts::DataSourceType](../datasourcetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóval állítja be (a megosztott helyett). Lehetővé teszi a mutatók átállítását gyenge módra a konténerekben. |
| int [SharedCount](../../system/object/sharedcount/)() const | A megosztott referenciaszámláló aktuális értékét adja vissza. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | A C# typeof([System.Object](../../system/object/)) konstrukciót valósítja meg. |
| void [Unlock](../../system/object/unlock/)() | A C# lock() utasítás feloldását valósítja meg. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentry objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
## Lásd még

* Osztály [IBaseChartValue](../ibasechartvalue/)
* Osztály [IDOMObject](../../aspose.slides/idomobject/)
* Névtér [Aspose::Slides::Charts](../)
* Könyvtár [Aspose.Slides](../../)