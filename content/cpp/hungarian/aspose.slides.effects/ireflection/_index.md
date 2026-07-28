---
title: IReflection
second_title: Aspose.Slides for C++ API referencia
description: Egy tükrözési effektust reprezentál.
type: docs
weight: 937
url: /hu/aspose.slides.effects/ireflection/
---
## IReflection osztály

Egy tükrözési effektust reprezentál.

```cpp
class IReflection : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                    public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IReflectionEffectiveData>>
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantikával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktypusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekintendő, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekintendő, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) sugár. Olvas **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Tükrözés iránya. Olvas **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Tükrözés távolsága. Olvas **double**. |
| virtual **float** [get_EndPosAlpha](./get_endposalpha/)() | Meghatározza a végső alfa érték (százalék) pozícióját (az alfa-grádiens lejtőjén). Olvas **float**. |
| virtual **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() | Végső tükrözés átlátszósága (százalék). Olvas **float**. |
| virtual **float** [get_FadeDirection](./get_fadedirection/)() | Meghatározza a tükrözés eltolásának irányát (szög). Olvas **float**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Téglalap igazítás. Olvas [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Meghatározza, hogy a tükrözés a formával együtt forgasson-e, ha a forma el van forgatva. Olvas **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Meghatározza a vízszintes méretezési tényezőt, a negatív skálázás tükrözést okoz (százalék). Olvas **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Meghatározza a függőleges méretezési tényezőt, a negatív skálázás tükrözést okoz (százalék). Olvas **double**. |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Meghatározza a vízszintes ferdeségi szöget. Olvas **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Meghatározza a függőleges ferdeségi szöget. Olvas **double**. |
| virtual **float** [get_StartPosAlpha](./get_startposalpha/)() | Meghatározza a kezdő alfa érték (százalék) pozícióját (az alfa-grádiens lejtőjén). Olvas **float**. |
| virtual **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() | Kezdő tükrözés átlátszósága (százalék). Olvas **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Az objektumhoz társított referenciaszámláló adatstruktúrát adja vissza. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | Az öröklődéssel alkalmazott hatékony adatot adja vissza. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Az objektum tényleges típusát adja vissza. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a cél típus által leírt példány-e. A C# „is” operátor analógiája. |
| void [Lock](../../system/object/lock/)() | A C# lock() utasítás zárolását valósítja meg. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Minden belső adatstruktúrát inicializál. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlít össze egy érték típusú objektumot a nullptr-el. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciálisítása a string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciálisítása stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) sugár. Ír **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | Tükrözés iránya. Ír **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | Tükrözés távolsága. Ír **double**. |
| virtual void [set_EndPosAlpha](./set_endposalpha/)(**float**) | Meghatározza a végső alfa érték (százalék) pozícióját (az alfa-grádiens lejtőjén). Ír **float**. |
| virtual void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) | Végső tükrözés átlátszósága (százalék). Ír **float**. |
| virtual void [set_FadeDirection](./set_fadedirection/)(**float**) | Meghatározza a tükrözés eltolásának irányát (szög). Ír **float**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | Téglalap igazítás. Ír [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | Meghatározza, hogy a tükrözés a formával együtt forgasson-e, ha a forma el van forgatva. Ír **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | Meghatározza a vízszintes méretezési tényezőt, a negatív skálázás tükrözést okoz (százalék). Ír **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | Meghatározza a függőleges méretezési tényezőt, a negatív skálázás tükrözést okoz (százalék). Ír **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | Meghatározza a vízszintes ferdeségi szöget. Ír **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | Meghatározza a függőleges ferdeségi szöget. Ír **double**. |
| virtual void [set_StartPosAlpha](./set_startposalpha/)(**float**) | Meghatározza a kezdő alfa érték (százalék) pozícióját (az alfa-grádiens lejtőjén). Ír **float**. |
| virtual void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) | Kezdő tükrözés átlátszósága (százalék). Ír **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (nem megosztott). Lehetővé teszi a mutatók konténerben való átkapcsolását gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | A megosztott referenciaszámláló aktuális értékét adja vissza. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; inkább használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; inkább használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok konvertálását stringgé. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | A C# typeof([System.Object](../../system/object/)) szerkezetet valósítja meg. |
| void [Unlock](../../system/object/unlock/)() | A C# lock() utasítás feloldását valósítja meg. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; inkább használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; inkább használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IImageTransformOperation](../iimagetransformoperation/)
* Osztály [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* Névterület [Aspose::Slides::Effects](../)
* Könyvtár [Aspose.Slides](../../)