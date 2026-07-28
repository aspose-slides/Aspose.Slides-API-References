---
title: Portion
second_title: Aspose.Slides C++ API referenciája
description: Egy szövegbekezdésen belüli szövegrészletet képvisel.
type: docs
weight: 4772
url: /hu/aspose.slides/portion/
---
## Portion osztály

Egy szöveg bekezdésen belüli szövegrészletet képvisel.

```cpp
class Portion : public Aspose::Slides::IPortion,
                public Aspose::Slides::IDOMObject
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| void [AddField](./addfield/)([System::SharedPtr](../../system/sharedptr/)\<[IFieldType](../ifieldtype/)\>) override | Átalakítja ezt a részt egy automatikusan frissített mezővé. |
| void [AddField](./addfield/)([System::String](../../system/string/)) override | Átalakítja ezt a részt egy automatikusan frissített mezővé. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| [System::SharedPtr](../../system/sharedptr/)\<[IField](../ifield/)\> [get_Field](./get_field/)() override | Visszaad egy mezőt ebből a részből. Csak olvasható [IField](../ifield/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_PortionFormat](./get_portionformat/)() override | Visszaad egy formázási objektumot, amely explicit módon beállított formázási tulajdonságokat tartalmaz a szövegrészlethez, öröklődés nélkül. Csak olvasható [IPortionFormat](../iportionformat/). |
| [System::String](../../system/string/) [get_Text](./get_text/)() override | Lekéri egy rész egyszerű szövegét. Csak olvasás [System::String](../../system/string/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [GetCoordinates](./getcoordinates/)() override | Lekéri a rész kezdetének koordinátáit. A pont X koordinátája a rész első karakterétől bal oldali távolságot is tartalmazza. A Y koordináta a felső oldali távolságot is tartalmazza. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetRect](./getrect/)() override | Lekéri a részt körülvevő téglalap koordinátáit. A téglalap tartalmazza a rész összes szövegsorát, beleértve az üreseket is. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívható közvetlenül vagy a [LockContext](../../system/lockcontext/) felügyeleti objektummal. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi a származtatott osztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi a származtatott osztályok másoló konstruktorát. |
|  [Portion](./portion/)() | Inicializál egy új példányt a [Portion](./) osztályból. |
|  [Portion](./portion/)([System::String](../../system/string/)) | Inicializál egy új példányt a [Portion](./) osztályból. |
|  [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Portion](./)\>) | Inicializál egy új példányt a [Portion](./) osztályból. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként hasonlít össze értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [RemoveField](./removefield/)() override | Átalakítja ezt a mezőrészt egyszerű részre. |
| void [set_Text](./set_text/)([System::String](../../system/string/)) override | Beállítja egy rész egyszerű szövegét. Írás [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók tárolókon belüli weak módra való átkapcsolását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívható közvetlenül vagy a [LockContext](../../system/lockcontext/) felügyeleti objektummal. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
## Lásd még

* Osztály [IPortion](../iportion/)
* Osztály [IDOMObject](../idomobject/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)