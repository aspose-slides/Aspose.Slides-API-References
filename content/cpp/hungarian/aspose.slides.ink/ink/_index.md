---
title: Ink
second_title: Aspose.Slides C++ API Referenciája
description: Egy dián lévő tintaobjektumot reprezentál.
type: docs
weight: 53
url: /hu/aspose.slides.ink/ink/
---
## Ink osztály


Represents an ink object on a slide.

```cpp
class Ink : public Aspose::Slides::GraphicalObject,
            public Aspose::Slides::Ink::IInk
```

## Módszerek

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | Új helyőrzőt ad hozzá, ha nincs, és a helyőrző tulajdonságait egy megadottra állítja. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantikai szabályai szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN semelyik értékkel, beleértve a NaN-t, nem egyenlő. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN semelyik értékkel, beleértve a NaN-t, nem egyenlő. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | Visszaadja a formához kapcsolódó alternatív szöveget. Olvas [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | Visszaadja a formához kapcsolódó alternatív szöveg címét. Olvas [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | A tulajdonság meghatározza, hogy a forma hogyan jelenik meg fekete-fehér megjelenítési módban. Olvas [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | Visszaadja a forma csatlakozási pontjainak számát. Csak olvasható **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | Visszaadja a forma egyéni adatait. Csak olvasható [ICustomData](../../aspose.slides/icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | Visszaadja a [EffectFormat](../../aspose.slides/effectformat/) objektumot, amely a forma alkalmazott pixel effektjeit tartalmazza. Megjegyzés: bizonyos, effektus tulajdonsággal nem rendelkező formák esetén null értéket adhat vissza. Csak olvasható [IEffectFormat](../../aspose.slides/ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | Visszaadja a [FillFormat](../../aspose.slides/fillformat/) objektumot, amely a forma kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos, kitöltési tulajdonságokkal nem rendelkező formák esetén null értéket adhat vissza. Csak olvasható [IFillFormat](../../aspose.slides/ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | Visszaadja a forma keret tulajdonságait. Olvas [IShapeFrame](../../aspose.slides/ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/graphicalobject/get_graphicalobjectlock/)() override | Visszaadja a forma zárolásait. Csak olvasható [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | Megkapja a forma magasságát pontokban mérve. Olvas **float**. |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | Megállapítja, hogy a forma rejtett-e. Olvas **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | Visszaadja az egérkattintásra definiált hiperhivatkozást. Olvas [IHyperlink](../../aspose.slides/ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | Visszaadja a hiperhivatkozás-kezelőt. Csak olvasható [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | Visszaadja az egér fölé mozgatására definiált hiperhivatkozást. Olvas [IHyperlink](../../aspose.slides/ihyperlink/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[InkEffectType](../inkeffecttype/), [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\>\>\> [get_InkEffectImages](./get_inkeffectimages/)() | Lekéri az egyéni képek gyűjteményét, amelyet a tintakefék vizuális effektusainak szimulálására használnak. Ezek a képek a tinta renderelésekor bizonyos [InkEffectType](../inkeffecttype/) értékekkel, például Galaxy, Rainbow stb., kerülnek felhasználásra. Saját képek megadásával szabályozható, hogy az egyes tintaeffektek hogyan jelennek meg. |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | Megkapja a 'Mark as decorative' opciót Olvas/ír **bool**. |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | Megállapítja, hogy a forma csoportosított-e. Csak olvasható **bool**. |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | Megállapítja, hogy a forma TextHolder_PPT-e. Csak olvasható **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | Visszaadja a [LineFormat](../../aspose.slides/lineformat/) objektumot, amely a forma vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos, vonal tulajdonságokkal nem rendelkező formák esetén null értéket adhat vissza. Csak olvasható [ILineFormat](../../aspose.slides/ilineformat/). |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | Visszaadja egy forma nevét. Nem lehet null. Szükség esetén üres karakterláncot használjon. Olvas [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | Visszaad egy diára vonatkozó egyedi azonosítót, amely a forma életciklusa alatt állandó, és lehetővé teszi a PowerPoint vagy interop kód számára, hogy a dokumentum bármely részéről megbízhatóan hivatkozzon a formára. Csak olvasható **uint32_t**. Lásd még [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | Visszaadja a szülő [GroupShape](../../aspose.slides/groupshape/) objektumot, ha a forma csoportosított. Egyébként null értéket ad vissza. Csak olvasható [IGroupShape](../../aspose.slides/igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | Visszaadja a forma helyőrzőt. Null értéket ad vissza, ha a formának nincs helyőrzője. Csak olvasható [IPlaceholder](../../aspose.slides/iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | Visszaadja a dia szülő prezentációját. Csak olvasható [IPresentation](../../aspose.slides/ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | Visszaadja a nyers forma keret tulajdonságait. Olvas [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | Visszaadja a fokok számát, amellyel a megadott forma el van fordítva a z tengely körül. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az ellentétes irányú forgást. Olvas **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | Visszaadja a forma zárolásait. Csak olvasható [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | Visszaadja a forma szülő diát. Csak olvasható [IBaseSlide](../../aspose.slides/ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | Visszaadja a [ThreeDFormat](../../aspose.slides/threedformat/) objektumot, amely a forma 3D effektus tulajdonságait tartalmazza. Megjegyzés: bizonyos, 3D tulajdonságokkal nem rendelkező formák esetén null értéket adhat vissza. Csak olvasható [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IInkTrace](../iinktrace/)\>\> [get_Traces](./get_traces/)() override | Lekéri az összes nyomot, amely a [IInk](../iink/) elem [IInkTrace](../iinktrace/)-ban található. Csak olvasható. |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | Visszaad egy belső, prezentációra vonatkozó azonosítót, amelyet kiegészítők vagy más kód használhat. Mivel ezt az értéket a felhasználó vagy programozottan át lehet rendelnie, nem kezelhető állandó egyedi kulcsként. Csak olvasható **uint32_t**. Lásd még [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/). |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | Megkapja a forma szélességét pontokban mérve. Olvas **float**. |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | Megkapja a forma bal felső sarkának x-koordinátáját pontokban mérve. Olvas **float**. |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | Megkapja a forma bal felső sarkának y-koordinátáját pontokban mérve. Olvas **float**. |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | Visszaadja a forma pozícióját a z-sorrendben. A Shapes[0] a z-sorrend hátulja lévő formát adja vissza, a Shapes[Shapes.Count - 1] pedig az előre lévő formát. Csak olvasható **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | Visszaad egy alap helyőrző formát (a layout vagy mester dia formáját, amelyről az aktuális forma örököl). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Kapja meg a objektumhoz kapcsolódó referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyéni objektumok hash-elését. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | Visszaadja a forma bélyegképét. Alapértelmezés szerint a [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) forma bélyegkép határ típust használja. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | Visszaadja a forma bélyegképét. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | Megkapja a forma vizuális határait, amelyet a renderelt tartalma alapján számítanak. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típuspéldány-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyéni típusok klónozását. |
| [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint hasonlítja össze az érték típusú objektumot a nullptr-tal. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | Meghatározza, hogy ez a forma nem helyőrző. |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | Beállítja a forma mellékelt alternatív szövegét. Ír [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Beállítja a forma alternatív szövegének címét. Ír [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | A tulajdonság meghatározza, hogy a forma hogyan jelenik meg fekete-fehér módon. Ír [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | Beállítja a forma keret tulajdonságait. Ír [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | Beállítja a forma magasságát pontokban mérve. Ír **float**. |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | Megállapítja, hogy a forma rejtett-e. Ír **bool**. |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | Beállítja az egérkattintásra definiált hiperhivatkozást. Ír [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | Beállítja az egér fölé mozgatásra definiált hiperhivatkozást. Ír [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | Beállítja a 'Mark as decorative' opciót Olvas/ír **bool**. |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | Beállítja egy forma nevét. Nem lehet null. Szükség esetén üres karakterláncot használjon. Ír [System::String](../../system/string/). |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | Beállítja a nyers forma keret tulajdonságait. Ír [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | Beállítja a fokok számát, amellyel a megadott forma el van fordítva a z tengely körül. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az ellenkező irányú forgást. Ír **float**. |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | Beállítja a forma szélességét pontokban mérve. Ír **float**. |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | Beállítja a forma bal felső sarkának x-koordinátáját pontokban mérve. Ír **float**. |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | Beállítja a forma bal felső sarkának y-koordinátáját pontkban mérve. Ír **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóra (nem megosztott). Lehetővé teszi a mutatók átkapcsolását a konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyéni objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Elmenti a [Shape](../../aspose.slides/shape/) tartalmát SVG fájlként. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Elmenti a [Shape](../../aspose.slides/shape/) tartalmát SVG fájlként. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [GraphicalObject](../../aspose.slides/graphicalobject/)
* Osztály [IInk](../iink/)
* Névtér [Aspose::Slides::Ink](../)
* Könyvtár [Aspose.Slides](../../)