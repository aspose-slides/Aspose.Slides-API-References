---
title: IColorSchemeEffectiveData
second_title: Aspose.Slides C++ API referencia
description: Megváltoztathatatlan objektum, amely a hatékony színséma tulajdonságait tartalmazza.
type: docs
weight: 157
url: /hu/aspose.slides.theme/icolorschemeeffectivedata/
---
## IColorSchemeEffectiveData osztály

Megváltoztathatatlan objektum, amely a hatékony színséma tulajdonságait tartalmazza.

```cpp
class IColorSchemeEffectiveData : public virtual System::Object
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referenciatípusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent1](./get_accent1/)() | Az első akcentus szín a sémában. Csak olvasható [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent2](./get_accent2/)() | A második akcentus szín a sémában. Csak olvasható [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent3](./get_accent3/)() | A harmadik akcentus szín a sémában. Csak olvasható [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent4](./get_accent4/)() | A negyedik akcentus szín a sémában. Csak olvasható [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent5](./get_accent5/)() | Az ötödik akcentus szín a sémában. Csak olvasható [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent6](./get_accent6/)() | A hatodik akcentus szín a sémában. Csak olvasható [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Dark1](./get_dark1/)() | Az első sötét szín a sémában. Csak olvasható [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Dark2](./get_dark2/)() | A második sötét szín a sémában. Csak olvasható [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_FollowedHyperlink](./get_followedhyperlink/)() | A meglátogatott hiperhivatkozások színe. Csak olvasható [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Hyperlink](./get_hyperlink/)() | A hiperhivatkozások színe. Csak olvasható [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Light1](./get_light1/)() | Az első világos szín a sémában. Csak olvasható [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Light2](./get_light2/)() | A második világos szín a sémában. Csak olvasható [System::Drawing::Color](../../system.drawing/color/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [idx_get](./idx_get/)([ColorSchemeIndex](../../aspose.slides/colorschemeindex/)) | Lekéri a megadott indexű elemet. Csak olvasható [System::Drawing::Color](../../system.drawing/color/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak inicializál egy új objektumot és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak inicializál egy új objektumot és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók konténerekben való átkapcsolását gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Megjegyzések

Ez az osztály a [IThemeEffectiveData](../ithemeeffectivedata/) részeként használatos.

## Lásd még

* Osztály [Object](../../system/object/)
* Névtér [Aspose::Slides::Theme](../)
* Könyvtár [Aspose.Slides](../../)