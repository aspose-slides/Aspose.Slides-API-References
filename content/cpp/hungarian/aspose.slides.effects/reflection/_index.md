---
title: Reflection
second_title: Aspose.Slides C++ API referenciája
description: Egy Reflexió effektust ábrázol.
type: docs
weight: 1067
url: /hu/aspose.slides.effects/reflection/
---
## Reflection osztály


Ábrázolja a [Reflection](./) hatást.

```cpp
class Reflection : public Aspose::Slides::Effects::IReflection,
                   public Aspose::Slides::Effects::IVisualEffect,
                   public Aspose::Slides::IPVIObject
```

## Módszerek

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Megállapítja, hogy a megadott [Reflection](./) egyenlő-e a jelenlegi [Reflection](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantikával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) sugár. Olvassa **double**. |
| **float** [get_Direction](./get_direction/)() override | A visszaverés iránya. Olvassa **float**. |
| **double** [get_Distance](./get_distance/)() override | A visszaverés távolsága. Olvassa **double**. |
| **float** [get_EndPosAlpha](./get_endposalpha/)() override | Megadja a végső alfa érték (százalék) végpozícióját (az alfa gradiens rámpán). Olvassa **float**. |
| **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() override | A visszaverés végső átlátszatlansága. (százalék). Olvassa **float**. |
| **float** [get_FadeDirection](./get_fadedirection/)() override | Megadja a visszaverés eltolásának irányát. (szög). Olvassa **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Visszaadja a szülő [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). Csak olvasható [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | Téglalap igazítás. Olvassa [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | Megadja, hogy a visszaverésnek el kell-e fordulnia a formával, ha a forma el van forgatva. Olvassa **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | Megadja a vízszintes méretezési tényezőt, a negatív méretezés tükrözést okoz. (százalék) Olvassa **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | Megadja a függőleges méretezési tényezőt, a negatív méretezés tükrözést okoz. (százalék) Olvassa **double**. |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Megadja a vízszintes ferdítési szöget. Olvassa **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Megadja a függőleges ferdítési szöget. Olvassa **double**. |
| **float** [get_StartPosAlpha](./get_startposalpha/)() override | Megadja a kezdő alfa érték (százalék) kezdőpozícióját (az alfa gradiens rámpán). Olvassa **float**. |
| **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() override | A visszaverés kezdeti átlátszatlansága. (százalék). Olvassa **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | Verzió. Csak olvasható **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referenciavételezési számláló adatstruktúrát. |
| [System::SharedPtr](../../system/sharedptr/)\<[IReflectionEffectiveData](../ireflectioneffectivedata/)\> [GetEffective](./geteffective/)() override | Lekéri a hatékony [Reflection](./) effektus adatot a öröklődés alkalmazásával. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Hash függvényként szolgál egy adott típushoz. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum egy példány-e a targetType által leírt típusról. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaból érték típusú objektumot hasonlít össze a nullptr-lel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciavételezést a megadott értékkel. |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) sugár. Írja **double**. |
| void [set_Direction](./set_direction/)(**float**) override | A visszaverés iránya. Írja **float**. |
| void [set_Distance](./set_distance/)(**double**) override | A visszaverés távolsága. Írja **double**. |
| void [set_EndPosAlpha](./set_endposalpha/)(**float**) override | Megadja a végső alfa érték (százalék) végpozícióját (az alfa gradiens rámpán). Írja **float**. |
| void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) override | A visszaverés végső átlátszatlansága. (százalék). Írja **float**. |
| void [set_FadeDirection](./set_fadedirection/)(**float**) override | Megadja a visszaverés eltolásának irányát. (szög). Írja **float**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | Téglalap igazítás. Írja [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | Megadja, hogy a visszaverésnek el kell-e fordulnia a formával, ha a forma el van forgatva. Írja **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | Megadja a vízszintes méretezési tényezőt, a negatív méretezés tükrözést okoz. (százalék) Írja **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | Megadja a függőleges méretezési tényezőt, a negatív méretezés tükrözést okoz. (százalék) Írja **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Megadja a vízszintes ferdítési szöget. Írja **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Megadja a függőleges ferdítési szöget. Írja **double**. |
| void [set_StartPosAlpha](./set_startposalpha/)(**float**) override | Megadja a kezdő alfa érték (százalék) kezdőpozícióját (az alfa gradiens rámpán). Írja **float**. |
| void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) override | A visszaverés kezdeti átlátszatlansága. (százalék). Írja **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók átkapcsolását konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciavételező aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciavételezőt. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciavételezőt. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciavételezőt. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciavételezőt. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
## Lásd még

* Osztály [IReflection](../ireflection/)
* Osztály [IVisualEffect](../ivisualeffect/)
* Osztály [IPVIObject](../../aspose.slides/ipviobject/)
* Névtér [Aspose::Slides::Effects](../)
* Könyvtár [Aspose.Slides](../../)