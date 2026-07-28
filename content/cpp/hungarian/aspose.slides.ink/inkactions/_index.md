---
title: InkActions
second_title: Aspose.Slides C++ API Referenciája
description: A tinta műveletek gyökerét képviseli.
type: docs
weight: 66
url: /hu/aspose.slides.ink/inkactions/
---
## InkActions osztály

A tinta műveletek gyökerét képviseli.

```cpp
class InkActions : public Aspose::Slides::GraphicalObject,
                   public Aspose::Slides::Ink::IInkActions
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | Új helyőrzőt ad hozzá, ha nincs, és a helyőrző tulajdonságait egy megadottra állítja. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | Visszaadja az alakzathoz tartozó alternatív szöveget. Olvasd [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | Visszaadja az alakzathoz tartozó alternatív szöveg címét. Olvasd [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | A tulajdonság meghatározza, hogyan jelenik meg az alakzat fekete-fehér megjelenítési módban. Olvasd [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | Visszaadja az alakzaton lévő csatlakozási pontok számát. Csak olvasható **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | Visszaadja az alakzat egyéni adatait. Csak olvasható [ICustomData](../../aspose.slides/icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | Visszaadja a [EffectFormat](../../aspose.slides/effectformat/) objektumot, amely a alakzatra alkalmazott pixel effektusokat tartalmazza. Megjegyzés: bizonyos típusú alakzatoknál, amelyeknek nincsenek effektus tulajdonságai, null értéket adhat vissza. Csak olvasható [IEffectFormat](../../aspose.slides/ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | Visszaadja a [FillFormat](../../aspose.slides/fillformat/) objektumot, amely az alakzat kitöltésformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú alakzatoknál, amelyeknek nincs kitöltési tulajdonságuk, null értéket adhat vissza. Csak olvasható [IFillFormat](../../aspose.slides/ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | Visszaadja az alakzat keretének tulajdonságait. Olvasd [IShapeFrame](../../aspose.slides/ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/graphicalobject/get_graphicalobjectlock/)() override | Visszaadja az alakzat zárolásait. Csak olvasható [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | Lekéri az alakzat magasságát pontban mérve. Olvasd **float**. |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | Megállapítja, hogy az alakzat rejtett-e. Olvasd **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | Visszaadja az egérkattintásra definiált hiperhivatkozást. Olvasd [IHyperlink](../../aspose.slides/ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | Visszaadja a hiperhivatkozáskezelőt. Csak olvasható [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | Visszaadja az egér fölé mozgatására definiált hiperhivatkozást. Olvasd [IHyperlink](../../aspose.slides/ihyperlink/). |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | Lekéri a 'Mark as decorative' opciót Olvasás/írás **bool**. |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | Megállapítja, hogy az alakzat csoportosítva van-e. Csak olvasható **bool**. |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | Megállapítja, hogy az alakzat TextHolder_PPT-e. Csak olvasható **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | Visszaadja a [LineFormat](../../aspose.slides/lineformat/) objektumot, amely az alakzat vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú alakzatoknál, amelyeknek nincs vonal tulajdonságuk, null értéket adhat vissza. Csak olvasható [ILineFormat](../../aspose.slides/ilineformat/). |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | Visszaadja egy alakzat nevét. Nem lehet null. Szükség esetén használj üres karakterláncot. Olvasd [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | Visszaad egy diára vonatkozó egyedi azonosítót, amely a shape élettartama alatt állandó, és lehetővé teszi, hogy a PowerPoint vagy az interop kód megbízhatóan hivatkozzon az alakzatra a dokumentum bármely részéről. Csak olvasható **uint32_t**. Lásd még [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | Visszaadja a szülő [GroupShape](../../aspose.slides/groupshape/) objektumot, ha az alakzat csoportosítva van. Egyébként null értéket ad vissza. Csak olvasható [IGroupShape](../../aspose.slides/igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | Visszaadja az alakzat helyőrzőjét. Null értéket ad vissza, ha az alakzatnak nincs helyőrzője. Csak olvasható [IPlaceholder](../../aspose.slides/iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | Visszaadja egy dia szülő bemutatóját. Csak olvasható [IPresentation](../../aspose.slides/ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | Visszaadja a nyers alakzat keretének tulajdonságait. Olvasd [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | Visszaadja a fokok számát, amelyben a megadott alakzat a z-tengely körül elfordul. A pozitív érték az óramutató irányú forgást jelzi; a negatív érték az óramutató járásával ellentétes forgást. Olvasd **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | Visszaadja az alakzat zárolásait. Csak olvasható [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | Visszaadja az alakzat szülő diáját. Csak olvasható [IBaseSlide](../../aspose.slides/ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | Visszaadja a [ThreeDFormat](../../aspose.slides/threedformat/) objektumot, amely az alakzat 3D effektus tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú alakzatoknál, amelyeknek nincs 3D tulajdonságuk, null értéket adhat vissza. Csak olvasható [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | Visszaad egy belső, a bemutatóra vonatkozó azonosítót, amelyet kiegészítők vagy más kód használhat. Mivel ezt az értéket a felhasználó vagy programozottan újra lehet rendelni, nem szabad tartós egyedi kulcsként kezelni. Csak olvasható **uint32_t**. Lásd még [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/). |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | Lekéri az alakzat szélességét pontban mérve. Olvasd **float**. |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | Lekéri az alakzat bal felső sarkának x-koordinátáját pontban mérve. Olvasd **float**. |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | Lekéri az alakzat bal felső sarkának y-koordinátáját pontban mérve. Olvasd **float**. |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | Visszaadja egy alakzat pozícióját a z-sorrendben. A Shapes[0] a z-sorrend hátsó alakzatát adja vissza, a Shapes[Shapes.Count - 1] pedig az elsőt. Csak olvasható **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | Visszaad egy alaphelyőrző alakzatot (az elrendezésből és/vagy mester diáról származó alakzat, amelyből az aktuális alakzat örököl). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó hivatkozásszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | Visszaadja az alakzat bélyegképét. Alapértelmezés szerint a [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) alakzat bélyegkép határoló típusa használatos. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | Visszaadja az alakzat bélyegképét. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | Lekéri az alakzat vizuális határait, amelyeket a renderelt tartalom alapján számoltak ki. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívd közvetlenül vagy használd a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak új objektumot inicializál és lehetővé teszi a származtatott osztályok másolását. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit sem másol, csak új objektumot inicializál és lehetővé teszi a származtatott osztályok másolását. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia alapján hasonlítja össze az értéktípusú objektumot a nullptr-val. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott hivatkozásszámlálót a megadott értékkel. |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | Definiálja, hogy ez az alakzat nem helyőrző. |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | Beállítja az alakzathoz tartozó alternatív szöveget. Írd [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Beállítja az alakzathoz tartozó alternatív szöveg címét. Írd [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | A tulajdonság meghatározza, hogyan jelenik meg az alakzat fekete-fehér megjelenítési módban. Írd [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | Beállítja az alakzat keretének tulajdonságait. Írd [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | Beállítja az alakzat magasságát pontban mérve. Írd **float**. |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | Meghatározza, hogy az alakzat rejtett-e. Írd **bool**. |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | Beállítja az egérkattintásra definiált hiperhivatkozást. Írd [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | Beállítja az egér fölé mozgatására definiált hiperhivatkozást. Írd [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | Beállítja a 'Mark as decorative' opciót Olvasás/írás **bool**. |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | Beállítja egy alakzat nevét. Nem lehet null. Szükség esetén használj üres karakterláncot. Írd [System::String](../../system/string/). |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | Beállítja a nyers alakzat keretének tulajdonságait. Írd [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | Beállítja a fokok számát, amelyben a megadott alakzat a z-tengely körül elfordul. A pozitív érték az óramutató irányú forgást jelzi; a negatív érték az óramutató járásával ellentétes forgást. Írd **float**. |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | Beállítja az alakzat szélességét pontban mérve. Írd **float**. |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | Beállítja az alakzat bal felső sarkának x-koordinátáját pontban mérve. Írd **float**. |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | Beállítja az alakzat bal felső sarkának y-koordinátáját pontban mérve. Írd **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóra (nem megosztott). Lehetővé teszi a mutatók konténerekben történő átkapcsolását gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott hivatkozásszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott hivatkozásszámlálót. Nem szabad közvetlenül hívni; helyette használj okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott hivatkozásszámlálót. Nem szabad közvetlenül hívni; helyette használj okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívd közvetlenül vagy használd a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge hivatkozásszámlálót. Nem szabad közvetlenül hívni; helyette használj okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge hivatkozásszámlálót. Nem szabad közvetlenül hívni; helyette használj okos mutatókat vagy ThisProtector-t. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Elmenti a [Shape](../../aspose.slides/shape/) tartalmát SVG fájlként. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Elmenti a [Shape](../../aspose.slides/shape/) tartalmát SVG fájlként. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [GraphicalObject](../../aspose.slides/graphicalobject/)
* Osztály [IInkActions](../iinkactions/)
* Névtér [Aspose::Slides::Ink](../)
* Könyvtár [Aspose.Slides](../../)