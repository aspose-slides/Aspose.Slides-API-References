---
title: FontFallBackRule
second_title: Aspose.Slides C++ API hivatkozás
description: A betűtípus fallback szabályt reprezentálja
type: docs
weight: 937
url: /hu/aspose.slides/fontfallbackrule/
---
## FontFallBackRule osztály


A betűtípus fallback szabályt reprezentálja

```cpp
class FontFallBackRule : public Aspose::Slides::IFontFallBackRule
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| void [AddFallBackFonts](./addfallbackfonts/)([System::String](../../system/string/)) override | Új betűtípust (betűtípusokat) ad a FallBack betűtípusok listájához. |
| void [AddFallBackFonts](./addfallbackfonts/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | Új betűtípusokat ad a FallBack betűtípusok listájához. |
| void [Clear](./clear/)() override | Eltávolít minden betűtípust a listáról. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | A C#-stílusú lebegőpontos összehasonlítást emulálja, ahol két NaN-t egyenlőnek tekint, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | A C#-stílusú lebegőpontos összehasonlítást emulálja, ahol két NaN-t egyenlőnek tekint, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
|  [FontFallBackRule](./fontfallbackrule/)(**uint32_t**, **uint32_t**, [System::String](../../system/string/)) | Új példányt hoz létre. |
|  [FontFallBackRule](./fontfallbackrule/)(**uint32_t**, **uint32_t**, [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) | Új példányt hoz létre. |
| **int32_t** [get_Count](./get_count/)() override | A tartományhoz ténylegesen definiált betűtípusok számát adja vissza. Csak olvasható **int32_t**. |
| **uint32_t** [get_RangeEndIndex](./get_rangeendindex/)() override | A folytonos Unicode tartomány utolsó indexét adja. |
| **uint32_t** [get_RangeStartIndex](./get_rangestartindex/)() override | A folytonos Unicode tartomány első indexét adja. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Az objektumhoz kapcsolódó referencia számláló adatstruktúrát adja. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Az objektum tényleges típusát adja. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| [System::String](../../system/string/) [idx_get](./idx_get/)(**int32_t**) override | A megadott indexnél lévő betűtípus nevét adja. Csak olvasható [IFontFallBackRule](../ifontfallbackrule/). |
| **int32_t** [IndexOf](./indexof/)([System::String](../../system/string/)) override | Visszaadja a megadott szabály indexét a gyűjteményben. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referencia szerint hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referencia szerint hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint hasonlítja össze az érték típusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| void [Remove](./remove/)([System::String](../../system/string/)) override | Eltávolítja a listából a specifikus FallBack betűtípus első előfordulását. |
| void [RemoveAt](./removeat/)(**int32_t**) override | Eltávolítja a FallBack betűtípust a lista megadott indexén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [set_RangeEndIndex](./set_rangeendindex/)(**uint32_t**) | A folytonos Unicode tartomány utolsó indexét adja. |
| void [set_RangeStartIndex](./set_rangestartindex/)(**uint32_t**) | A folytonos Unicode tartomány első indexét adja. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóvá (nem megosztottá) állítja. Lehetővé teszi a tárolókban lévő mutatók weak módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Visszaadja a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [ToArray](./toarray/)() override | Létrehoz és visszaad egy tömböt az összes FallBack betűtípussal ehhez a szabályhoz. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [ToArray](./toarray/)(**int32_t**, **int32_t**) override | Létrehoz és visszaad egy tömböt az összes FallBack betűtípussal a listában megadott tartományból. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IFontFallBackRule](../ifontfallbackrule/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)