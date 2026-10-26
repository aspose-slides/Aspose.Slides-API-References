---
title: OuterShadow
second_title: Aspose.Slides for C++ API referenciája
description: Képviseli egy külső árnyék hatást.
type: docs
weight: 1041
url: /hu/aspose.slides.effects/outershadow/
---
## OuterShadow osztály

Képviseli egy külső árnyék hatást.

```cpp
class OuterShadow : public Aspose::Slides::Effects::IOuterShadow,
                    public Aspose::Slides::Effects::IVisualEffect,
                    public Aspose::Slides::IPVIObject
```

## Metódusok

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Meghatározza, hogy a megadott [OuterShadow](./) egyenlő-e az aktuális [OuterShadow](./)-val. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja a objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referenciatípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) sugár, pontban. Alapértelmezett érték \\u2013 0 pt. Olvasható **double**. |
| **float** [get_Direction](./get_direction/)() override | Az árnyék iránya fokban. Alapértelmezett érték \\u2013 0 \\u00B0 (balról jobbra). Olvasható **float**. |
| **double** [get_Distance](./get_distance/)() override | Az árnyék távolsága az objektumtól pontban. Alapértelmezett érték \\u2013 0 pt. Olvasható **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Visszaadja a szülő [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)-t. Írásvédett [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Téglalap igazítás. Alapértelmezett érték \\u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Olvasható [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Jelzi, hogy az árnyék mozog-e együtt az alakzattal. Alapértelmezett érték \\u2013 true. Olvasható **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Vízszintes méretezési tényező, az eredeti méret százalékában. Negatív méretezés tükrözést okoz. Alapértelmezett érték \\u2013 100 %. Olvasható **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Függőleges méretezési tényező, az eredeti méret százalékában. Negatív méretezés tükrözést okoz. Alapértelmezett érték \\u2013 100 %. Olvasható **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() override | Az árnyék színe. Alapértelmezett érték \\u2013 automatikus fekete (témafüggő). Írásvédett [IColorFormat](../../aspose.slides/icolorformat/). |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Vízszintes dőlés szöge fokban. Alapértelmezett érték \\u2013 0 \\u00B0. Olvasható **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Függőleges dőlés szöge fokban. Alapértelmezett érték \\u2013 0 \\u00B0. Olvasható **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Verzió. Írásvédett **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referenciaszámláló adatstruktúrát. |
| [System::SharedPtr](../../system/sharedptr/)\<[IOuterShadowEffectiveData](../ioutershadoweffectivedata/)\> [GetEffective](./geteffective/)() override | Lekéri a hatékony Outer Shadow effektus adatokat az öröklődés alkalmazásával. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Hash függvényként szolgál egy adott típushoz. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri a objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként hasonlítja össze az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) sugár, pontban. Alapértelmezett érték \\u2013 0 pt. Írható **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Az árnyék iránya fokban. Alapértelmezett érték \\u2013 0 \\u00B0 (balról jobbra). Írható **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Az árnyék távolsága az objektumtól pontban. Alapértelmezett érték \\u2013 0 pt. Írható **double**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Téglalap igazítás. Alapértelmezett érték \\u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Írható [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Jelzi, hogy az árnyék a alakzattal együtt forgat-e. Alapértelmezett érték \\u2013 true. Írható **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Vízszintes méretezési tényező, az eredeti méret százalékában. Negatív méretezés tükrözést okoz. Alapértelmezett érték \\u2013 100 %. Írható **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Függőleges méretezési tényező, az eredeti méret százalékában. Negatív méretezés tükrözést okoz. Alapértelmezett érték \\u2013 100 %. Írható **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Vízszintes dőlés szöge fokban. Alapértelmezett érték \\u2013 0 \\u00B0. Írható **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Függőleges dőlés szöge fokban. Alapértelmezett érték \\u2013 0 \\u00B0. Írható **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablon argumentumot gyenge mutatóként (nem megosztottként). Lehetővé teszi a mutatók konténerekben gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IOuterShadow](../ioutershadow/)
* Osztály [IVisualEffect](../ivisualeffect/)
* Osztály [IPVIObject](../../aspose.slides/ipviobject/)
* Névterület [Aspose::Slides::Effects](../)
* Könyvtár [Aspose.Slides](../../)