---
title: IBulletFormat
second_title: Aspose.Slides C++ API referencia
description: A bekezdés felsorolásformázási tulajdonságait reprezentálja.
type: docs
weight: 1561
url: /hu/aspose.slides/ibulletformat/
---
## IBulletFormat osztály


A bekezdés felsorolásformázási tulajdonságait ábrázolja.

```cpp
class IBulletFormat : public virtual System::Object
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() | Beállítja az alapértelmezett nem nulla eltolásokat a hatékony bekezdés Indent és MarginLeft értékeihez, amikor a felsorolás engedélyezve van (mint a PowerPoint, ha engedélyezi a bekezdés felsorolásait/számozását). Ha a felsorolás le van tiltva, akkor csak visszaállítja a bekezdés Indent és MarginLeft értékeit (mint a PowerPoint, ha letiltja a bekezdés felsorolásait/számozását). Az eltolások a jelenlegi felsorolási kontextusra vonatkoznak – IBulletFormat::get(set)_Type, .NumberedBulletStyle és FontHeight az első részben. A nem nulla eltolások a jelenlegi bekezdés hatékony Indent és MarginLeft értékeire alkalmazottak (az eredményértékek lokális értékek lesznek). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szintaxis használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál double esetén, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| virtual char16_t [get_Char](./get_char/)() | Visszaadja a bekezdés saját, öröklődés nélküli felsorolás karakterét. Olvasható **wchar_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() | Visszaadja a bekezdés saját, öröklődés nélküli felsorolás színformátumát. Csak olvasható [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() | Visszaadja a bekezdés saját, öröklődés nélküli felsorolás betűtípusát. Olvasás [IFontData](../ifontdata/). |
| virtual **float** [get_Height](./get_height/)() | Visszaadja a bekezdés saját, öröklődés nélküli felsorolás magasságát. A std::numeric_limits<float>::quiet_NaN() érték határozza meg, hogy a felsorolás a bekezdés első részből örökölje a magasságot. Olvasható **float**. |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() | Meghatározza, hogy a felsorolás saját színnel rendelkezik-e, vagy a bekezdés első részéből örökli azt. **[NullableBool::True](../nullablebool/)** ha a felsorolás saját színnel bír, és **[NullableBool::False](../nullablebool/)** ha a színt a bekezdés első része adja át. Olvasás [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() | Megállapítja, hogy a felsorolás saját betűtípussal rendelkezik-e, vagy a bekezdés első részéből örökli azt. **[NullableBool::True](../nullablebool/)** ha a felsorolás saját betűtípussal bír, és **[NullableBool::False](../nullablebool/)** ha a betűtípust a bekezdés első része adja át. Olvasás [NullableBool](../nullablebool/). |
| virtual **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() | Visszaadja az első számot, amely a számozott felsorolások csoportjában öröklődés nélkül használatos. Olvasható **int16_t**. |
| virtual [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() | Visszaadja a számozott felsorolás stílusát öröklődés nélkül. Olvasás [NumberedBulletStyle](../numberedbulletstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | Visszaadja a bekezdésben felsorolásként használt képet öröklődés nélkül. Csak olvasható [ISlidesPicture](../islidespicture/). |
| virtual [BulletType](../bullettype/) [get_Type](./get_type/)() | Visszaadja a bekezdés saját, öröklődés nélküli felsorolás típusát. Olvasás [BulletType](../bullettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciaszámláló adatstruktúrát. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() | Lekéri a hatékony felsorolásformázási adatokat az öröklődés alkalmazásával. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül, vagy használja a [LockContext](../../system/lockcontext/) sentry objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit nem másol, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másoló konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípusú objektumot hivatkozással hasonlít össze a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [set_Char](./set_char/)(char16_t) | Beállítja a bekezdés saját, öröklődés nélküli felsorolás karakterét. Írás **wchar_t**. |
| virtual void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Beállítja a bekezdés saját, öröklődés nélküli felsorolás betűtípusát. Írás [IFontData](../ifontdata/). |
| virtual void [set_Height](./set_height/)(**float**) | Beállítja a bekezdés saját, öröklődés nélküli felsorolás magasságát. A std::numeric_limits<float>::quiet_NaN() érték határozza meg, hogy a felsorolás a bekezdés első részéből örökölje a magasságot. Írás **float**. |
| virtual void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) | Megállapítja, hogy a felsorolás saját színnel rendelkezik-e, vagy a bekezdés első részéből örökli azt. **[NullableBool::True](../nullablebool/)** ha a felsorolás saját színnel bír, és **[NullableBool::False](../nullablebool/)** ha a színt a bekezdés első része adja át. Írás [NullableBool](../nullablebool/). |
| virtual void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) | Megállapítja, hogy a felsorolás saját betűtípussal rendelkezik-e, vagy a bekezdés első részéből örökli azt. **[NullableBool::True](../nullablebool/)** ha a felsorolás saját betűtípussal bír, és **[NullableBool::False](../nullablebool/)** ha a betűtípust a bekezdés első része adja át. Írás [NullableBool](../nullablebool/). |
| virtual void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) | Beállítja az első számot, amely a számozott felsorolások csoportjában öröklődés nélkül használatos. Írás **int16_t**. |
| virtual void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) | Beállítja a számozott felsorolás stílusát öröklődés nélkül. Írás [NumberedBulletStyle](../numberedbulletstyle/). |
| virtual void [set_Type](./set_type/)([BulletType](../bullettype/)) | Beállítja a bekezdés saját, öröklődés nélküli felsorolás típusát. Írás [BulletType](../bullettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (a shared helyett). Lehetővé teszi a mutatók konténerben való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) szerkezetet. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül, vagy használja a [LockContext](../../system/lockcontext/) sentry objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)