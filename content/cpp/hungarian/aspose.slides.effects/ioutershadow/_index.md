---
title: IOuterShadow
second_title: Aspose.Slides C++ API hivatkozás
description: Külső árnyék effektust képvisel.
type: docs
weight: 885
url: /hu/aspose.slides.effects/ioutershadow/
---
## IOuterShadow osztály

Külső árnyék hatást reprezentál.

```cpp
class IOuterShadow : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                     public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IOuterShadowEffectiveData>>
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat C# stílusban hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat C# stílusban hasonlít össze. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekintendő, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekintendő, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) sugár, pontban. Alapértelmezett érték \u2013 0 pt. Olvas **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Az árnyék iránya fokban. Alapértelmezett érték \u2013 0 \u00B0 (balról jobbra). Olvas **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Az árnyék távolsága az objektumtól, pontban. Alapértelmezett érték \u2013 0 pt. Olvas **double**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Téglalap igazítás. Alapértelmezett érték \u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Olvas [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Jelzi, hogy az árnyék a formával együtt forog-e. Alapértelmezett érték \u2013 true. Olvas **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Vízszintes méretezési tényező, az eredeti méret százalékában. Negatív méretezés tükrözést eredményez. Alapértelmezett érték \u2013 100 %. Olvas **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Függőleges méretezési tényező, az eredeti méret százalékában. Negatív méretezés tükrözést eredményez. Alapértelmezett érték \u2013 100 %. Olvas **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() | Az árnyék színe. Alapértelmezett érték \u2013 automatikus fekete (témafüggő). Csak olvasható [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Vízszintes dőlés szöge fokban. Alapértelmezett érték \u2013 0 \u00B0. Olvas **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Függőleges dőlés szöge fokban. Alapértelmezett érték \u2013 0 \u00B0. Olvas **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektumhoz társított referencia számláló adatstruktúrát. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Megkapja a hatékony adatot az öröklődés alkalmazásával. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referencia szerint hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referencia szerint hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípusú objektumot referencia szerint hasonlít össze a nullptr-tal. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) sugár, pontban. Alapértelmezett érték \u2013 0 pt. Ír **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | Az árnyék iránya fokban. Alapértelmezett érték \u2013 0 \u00B0 (balról jobbra). Ír **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | Az árnyék távolsága az objektumtól, pontban. Alapértelmezett érték \u2013 0 pt. Ír **double**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Téglalap igazítás. Alapértelmezett érték \u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). Ír [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Jelzi, hogy az árnyék a formával együtt forog-e. Alapértelmezett érték \u2013 true. Ír **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Vízszintes méretezési tényező, az eredeti méret százalékában. Negatív méretezés tükrözést eredményez. Alapértelmezett érték \u2013 100 %. Ír **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Függőleges méretezési tényező, az eredeti méret százalékában. Negatív méretezés tükrözést eredményez. Alapértelmezett érték \u2013 100 %. Ír **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Vízszintes dőlés szöge fokban. Alapértelmezett érték \u2013 0 \u00B0. Ír **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Függőleges dőlés szöge fokban. Alapértelmezett érték \u2013 0 \u00B0. Ír **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablon argumentumot gyenge mutatóként (a megosztott helyett). Lehetővé teszi a mutatók konténerekben való gyenge módra történő átváltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referencia számláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi az egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IImageTransformOperation](../iimagetransformoperation/)
* Osztály [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* Névterület [Aspose::Slides::Effects](../)
* Könyvtár [Aspose.Slides](../../)