---
title: BulletFormat
second_title: Aspose.Slides for C++ API-referencia
description: A bekezdés golyóformázási tulajdonságait ábrázolja.
type: docs
weight: 248
url: /hu/aspose.slides/bulletformat/
---
## BulletFormat osztály

A bekezdés golyóformázási tulajdonságait ábrázolja.

```cpp
class BulletFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IBulletFormat
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() override | Beállítja az alapértelmezett nem nulla eltolásokat a hatékony bekezdés Indent és MarginLeft értékekhez, ha a golyók engedélyezve vannak (mint a PowerPoint, ha bekezdés golyókat/számozást engedélyez). Ha a golyók le vannak tiltva, csak visszaállítja a bekezdés Indent és MarginLeft értékeket (mint a PowerPoint, ha letiltja a bekezdés golyókat/számozást). Az eltolások a jelenlegi golyó kontextusra vonatkoznak – IBulletFormat::get(set)_Type, .NumberedBulletStyle és az első rész FontHeight értéke. A nem nulla eltolások a jelenlegi bekezdés hatékony Indent és MarginLeft értékeire kerülnek alkalmazásra (az eredményértékek lokális értékekké válnak). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Összehasonlítja a megadott objektummal. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekintendő, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekintendő, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| char16_t [get_Char](./get_char/)() override | Visszaadja a bekezdés golyó karakterét öröklődés nélkül. Olvassa **wchar_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() override | Visszaadja a bekezdés golyó színformátumát öröklődés nélkül. Csak olvasható [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() override | Visszaadja a bekezdés golyó betűtípusát öröklődés nélkül. Olvassa [IFontData](../ifontdata/). |
| **float** [get_Height](./get_height/)() override | Visszaadja a bekezdés golyó magasságát öröklődés nélkül. A std::numeric_limits<float>::quiet_NaN() érték határozza meg, hogy a golyó a bekezdés első részéből örökölje a magasságot. Olvassa **float**. |
| [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() override | Meghatározza, hogy a golyó saját színnel rendelkezik-e vagy a bekezdés első részétől örökli-e azt. **[NullableBool::True](../nullablebool/)** ha a golyó saját színnel rendelkezik és **[NullableBool::False](../nullablebool/)** ha a golyó a bekezdés első részétől örökli a színt. Olvassa [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() override | Meghatározza, hogy a golyó saját betűtípussal rendelkezik-e vagy a bekezdés első részétől örökli-e azt. **[NullableBool::True](../nullablebool/)** ha a golyó saját betűtípussal rendelkezik és **[NullableBool::False](../nullablebool/)** ha a golyó a bekezdés első részétől örökli a betűtípust. Olvassa [NullableBool](../nullablebool/). |
| **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() override | Visszaadja az első számot, amely a számozott golyók csoportjában öröklődés nélkül használatos. Olvassa **int16_t**. |
| [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() override | Visszaadja a számozott golyó stílusát öröklődés nélkül. Olvassa [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Visszaad egy Parent_Immediate objektumot. Csak olvasható [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Visszaadja a szülő [IPresentationComponent](../ipresentationcomponent/) objektumot. Csak olvasható [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Visszaadja a bekezdés golyóként használt képet öröklődés nélkül. Csak olvasható [ISlidesPicture](../islidespicture/). |
| [BulletType](../bullettype/) [get_Type](./get_type/)() override | Visszaadja a bekezdés golyó típusát öröklődés nélkül. Olvassa [BulletType](../bullettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referencia számláló adatstruktúrát. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() override | Lekéri a hatékony golyóformázási adatokat az öröklődés alkalmazásával. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Visszaadja a hash kódot. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# „is” operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Nem másol semmit, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolókonstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Nem másol semmit, csak inicializálja az új objektumot és lehetővé teszi az alosztályok másolókonstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat összehasonlít referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat összehasonlít referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia-összehasonlítja a value-típusú objektumot a nullptr-lal. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [set_Char](./set_char/)(char16_t) override | Beállítja a bekezdés golyó karakterét öröklődés nélkül. Írja **wchar_t**. |
| void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Beállítja a bekezdés golyó betűtípusát öröklődés nélkül. Írja [IFontData](../ifontdata/). |
| void [set_Height](./set_height/)(**float**) override | Beállítja a bekezdés golyó magasságát öröklődés nélkül. A std::numeric_limits<float>::quiet_NaN() érték határozza meg, hogy a golyó a bekezdés első részéből örökölje a magasságot. Írja **float**. |
| void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) override | Meghatározza, hogy a golyó saját színnel rendelkezik-e vagy a bekezdés első részétől örökli-e azt. **[NullableBool::True](../nullablebool/)** ha a golyó saját színnel rendelkezik és **[NullableBool::False](../nullablebool/)** ha a golyó a bekezdés első részétől örökli a színt. Írja [NullableBool](../nullablebool/). |
| void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) override | Meghatározza, hogy a golyó saját betűtípussal rendelkezik-e vagy a bekezdés első részétől örökli-e azt. **[NullableBool::True](../nullablebool/)** ha a golyó saját betűtípussal rendelkezik és **[NullableBool::False](../nullablebool/)** ha a golyó a bekezdés első részétől örökli a betűtípust. Írja [NullableBool](../nullablebool/). |
| void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) override | Beállítja az első számot, amely a számozott golyók csoportjában öröklődés nélkül használatos. Írja **int16_t**. |
| void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) override | Beállítja a számozott golyó stílusát öröklődés nélkül. Írja [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| void [set_Type](./set_type/)([BulletType](../bullettype/)) override | Beállítja a bekezdés golyó típusát öröklődés nélkül. Írja [BulletType](../bullettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | A n-edik sablonargumentumot gyenge pointerrel állítja be (a shared helyett). Lehetővé teszi a pointerek konténerekben történő weak módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [PVIObject](../pviobject/)
* Osztály [IBulletFormat](../ibulletformat/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)