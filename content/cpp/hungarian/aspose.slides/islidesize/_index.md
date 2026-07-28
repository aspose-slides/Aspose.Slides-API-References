---
title: ISlideSize
second_title: Aspose.Slides for C++ API referencia
description: A dia méretét és orientációját ábrázolja.
type: docs
weight: 3823
url: /hu/aspose.slides/islidesize/
---
## ISlideSize osztály

A dia méretét és orientációját ábrázolja.

```cpp
class ISlideSize : public virtual System::Object
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| virtual [SlideOrientation](../slideorientation/) [get_Orientation](./get_orientation/)() | Visszaadja a dia orientációját. |
| virtual [System::Drawing::SizeF](../../system.drawing/sizef/) [get_Size](./get_size/)() | Visszaadja a dia méreteket pontban. Új érték hozzárendelése visszaállítja a [ISlideSize::get_Type](./get_type/) értéket [SlideSizeType::Custom](../slidesizetype/)-ra és beállítja a [ISlideSize::get_Orientation](./get_orientation/)-t. |
| virtual [SlideSizeType](../slidesizetype/) [get_Type](./get_type/)() | Visszaadja a dia méret típusát. Bármely, kivéve [SlideSizeType::Custom](../slidesizetype/) érték hozzárendelése módosítja a [ISlideSize::get_Size](./get_size/)-t az előre definiált méretek szerint, miközben megtartja a jelenlegi [ISlideSize::get_Orientation](./get_orientation/)-t. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Visszaadja az objektumhoz tartozó referencialekérő számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Visszaadja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) felügyeleti objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolási konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolási konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az érték típusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencialek számát a megadott értékkel. |
| virtual void [set_Orientation](./set_orientation/)([SlideOrientation](../slideorientation/)) | Beállítja a dia orientációját. |
| virtual void [SetSize](./setsize/)([SlideSizeType](../slidesizetype/), [SlideSizeScaleType](../slidesizescaletype/)) | Beállítja a dia méretét típus alapján és átméretezi a meglévő tartalmat. A [SlideSizeType::Custom](../slidesizetype/)-től eltérő érték hozzárendelése módosítja a [ISlideSize::get_Size](./get_size/)-t a kiválasztott típus szerint, miközben megőrzi a [ISlideSize::get_Orientation](./get_orientation/)-t. |
| virtual void [SetSize](./setsize/)(**float**, **float**, [SlideSizeScaleType](../slidesizescaletype/)) | Kifejezetten beállítja a dia méreteket és átméretezi a meglévő tartalmat. Ez visszaállítja a [ISlideSize::get_Type](./get_type/) értékét [SlideSizeType::Custom](../slidesizetype/)-ra és beállítja a [ISlideSize::get_Orientation](./get_orientation/)-t. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóvá (a megosztott helyett). Lehetővé teszi a mutatók átkapcsolását a tárolókban gyenge módba. |
| int [SharedCount](../../system/object/sharedcount/)() const | Visszaadja a megosztott referencialek számának aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencialek számát. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencialek számát. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) felügyeleti objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencialek számát. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencialek számát. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtere [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)