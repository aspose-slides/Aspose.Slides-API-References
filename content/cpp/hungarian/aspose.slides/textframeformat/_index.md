---
title: TextFrameFormat
second_title: Aspose.Slides C++ API referencia
description: Tartalmazza a TextFrame formatTextFrameFormatting tulajdonságait.
type: docs
weight: 5461
url: /hu/aspose.slides/textframeformat/
---
## TextFrameFormat osztály

Contains the [TextFrame](../textframe/)'s formatTextFrameFormatting properties.

```cpp
class TextFrameFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::ITextFrameFormat,
                        public Aspose::Slides::Charts::IChartTextBlockFormat
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Összehasonlítja a megadott objektummal. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szémantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulálja a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek számít, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulálja a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek számít, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() override | Visszaadja a függőleges horgony szöveget egy [TextFrame](../textframe/)-ban. Olvassa [TextAnchorType](../textanchortype/). |
| [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() override | Visszaadja a szöveg automatikus illesztés módját. Olvassa [TextAutofitType](../textautofittype/). |
| [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() override | Ha [NullableBool::True](../nullablebool/), akkor a szöveget vízszintesen középre kell helyezni a keretben. Olvassa [NullableBool](../nullablebool/). |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | Visszaadja a szövegtér oszlopainak számát. Ennek az értéknek pozitív számnak kell lennie. Ellenkező esetben az érték nullára lesz állítva. A 0 érték meghatározatlan értéket jelent. Olvassa **int32_t**. |
| **double** [get_ColumnSpacing](./get_columnspacing/)() override | Visszaadja a szövegszlopok közötti távolságot a szövegtérben (pontban). Ez csak akkor érvényes, ha egy vagy több, tehát több mint 1 oszlop van jelen. Ennek az értéknek pozitív számnak kell lennie. Ellenkező esetben az érték nullára lesz állítva. Olvassa **double**. |
| **bool** [get_KeepTextFlat](./get_keeptextflat/)() override | Megkapja, hogy a szöveg lapos marad-e, még ha 3-D forgatás hatás is alkalmazva lett. Olvassa **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Visszaadja az alsó margó (pont) értékét egy [TextFrame](../textframe/)-ban. Olvassa **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Visszaadja a bal margó (pont) értékét egy [TextFrame](../textframe/)-ban. Olvassa **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Visszaadja a jobb margó (pont) értékét egy [TextFrame](../textframe/)-ban. Olvassa **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Visszaadja a felső margó (pont) értékét egy [TextFrame](../textframe/)-ban. Olvassa **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Visszaadja a Parent_Immediate objektumot. Csak olvasható [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Visszaadja a szülő [IPresentationComponent](../ipresentationcomponent/)-t. Csak olvasható [IPresentationComponent](../ipresentationcomponent/). |
| **float** [get_RotationAngle](./get_rotationangle/)() override | Meghatározza a szövegre a keretben alkalmazandó egyéni forgatást. Ha nincs megadva, akkor a kísérő alakzat forgatása kerül felhasználásra. Ha meg van adva, akkor ez függetlenül az alakzattól kerül alkalmazásra. Ez azt jelenti, hogy az alakzat is kaphat forgatást a szöveg saját forgatása mellett. A vizuális szöveg forgatás eredményét ez a tulajdonság és a TextVerticalType előre definiált függőleges típus összesíti. Olvassa **float**. |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Meghatározza a szöveg tájolását. A vizuális szöveg forgatás eredményét ez a tulajdonság és a RotationAngle egyéni szög összegzi. Olvassa [Slides::TextVerticalType](../textverticaltype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | Visszaadja a [ThreeDFormat](../threedformat/) objektumot, amely a szöveg 3D hatás tulajdonságait képviseli. Csak olvasható [IThreeDFormat](../ithreedformat/). |
| [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() override | Megkapja a szövegbefuttató alakzatot. Olvassa [TextShapeType](../textshapetype/). |
| [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() override | **True** ha a szöveg [TextFrame](../textframe/) margóinál van betörve. Olvassa [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektumhoz társított referencia számláló adatstruktúrát. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() override | Megkapja a hatékony szövegkeret formázási adatokat öröklődéssel együtt. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Visszaadja a hash kódot. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyéni típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit sem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referencia alapján. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referencia alapján. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia módon hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja a string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) override | Beállítja a függőleges horgony szöveget egy [TextFrame](../textframe/)-ban. Írja [TextAnchorType](../textanchortype/). |
| void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) override | Beállítja a szöveg automatikus illesztés módját. Írja [TextAutofitType](../textautofittype/). |
| void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) override | Ha [NullableBool::True](../nullablebool/), akkor a szöveget vízszintesen középre kell helyezni a keretben. Írja [NullableBool](../nullablebool/). |
| void [set_ColumnCount](./set_columncount/)(**int32_t**) override | Beállítja a szövegtér oszlopainak számát. Ennek az értéknek pozitív számnak kell lennie. Ellenkező esetben az érték nullára lesz állítva. A 0 érték meghatározatlan értéket jelent. Írja **int32_t**. |
| void [set_ColumnSpacing](./set_columnspacing/)(**double**) override | Beállítja a szövegszlopok közötti távolságot a szövegtérben (pontban). Ez csak akkor érvényes, ha több mint 1 oszlop van. Ennek az értéknek pozitív számnak kell lennie. Ellenkező esetben az érték nullára lesz állítva. Írja **double**. |
| void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) override | Beállítja, hogy a szöveg lapos maradjon még 3-D forgatás hatása esetén is. Írja **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Beállítja az alsó margót (pont) egy [TextFrame](../textframe/)-ban. Írja **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Beállítja a bal margót (pont) egy [TextFrame](../textframe/)-ban. Írja **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Beállítja a jobb margót (pont) egy [TextFrame](../textframe/)-ban. Írja **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Beállítja a felső margót (pont) egy [TextFrame](../textframe/)-ban. Írja **double**. |
| void [set_RotationAngle](./set_rotationangle/)(**float**) override | Meghatározza a szövegre a keretben alkalmazandó egyéni forgatást. Ha nincs megadva, akkor a kísérő alakzat forgatása kerül felhasználásra. Ha meg van adva, akkor ez függetlenül az alakzattól kerül alkalmazásra. Ez azt jelenti, hogy az alakzat is kaphat forgatást a szöveg saját forgatása mellett. A vizuális szöveg forgatás eredményét ez a tulajdonság és a TextVerticalType előre definiált függőleges típus összesíti. Írja **float**. |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Meghatározza a szöveg tájolását. A vizuális szöveg forgatás eredményét ez a tulajdonság és a RotationAngle egyéni szög összegzi. Írja [Slides::TextVerticalType](../textverticaltype/). |
| void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) override | Beállítja a szövegbefuttató alakzatot. Írja [TextShapeType](../textshapetype/). |
| void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) override | **True** ha a szöveg [TextFrame](../textframe/) margóinál van betörve. Írja [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | A n-edik sablonargumentumot gyenge mutatóként (nem megosztottként) állítja be. Lehetővé teszi a mutatók konténerekben való gyenge módra történő átkapcsolását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [TextFrameFormat](./textframeformat/)() | Inicializál egy új [TextFrameFormat](./) osztály példányt. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyéni objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
## Lásd még

* Osztály [PVIObject](../pviobject/)
* Osztály [ITextFrameFormat](../itextframeformat/)
* Osztály [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)