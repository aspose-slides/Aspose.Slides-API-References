---
title: SmartArt
second_title: Aspose.Slides C++ API-referencia
description: SmartArt diagramot képvisel
type: docs
weight: 66
url: /hu/aspose.slides.smartart/smartart/
---
## SmartArt osztály

Egy [SmartArt](./) diagramot képvisel

```cpp
class SmartArt : public Aspose::Slides::GraphicalObject,
                 public Aspose::Slides::SmartArt::ISmartArt
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | Új helyfoglalót ad hozzá, ha nincs, és beállítja a helyfoglaló tulajdonságait egy megadottra. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_AllNodes](./get_allnodes/)() override | Visszaadja az összes csomópont gyűjteményét a [SmartArt](./) objektumban. Csak olvasható [ISmartArtNodeCollection](../ismartartnodecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | Visszaadja a alakzathoz tartozó alternatív szöveget. Olvasható [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | Visszaadja a alakzathoz tartozó alternatív szöveg címét. Olvasható [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | A tulajdonság meghatározza, hogyan jelenik meg az alakzat fekete-fehér megjelenítési módban. Olvasható [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| [SmartArtColorType](../smartartcolortype/) [get_ColorStyle](./get_colorstyle/)() override | Visszaadja a [SmartArt](./) objektum színstílusát. Olvasható [SmartArtColorType](../smartartcolortype/). |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | Visszaadja az alakzatra mutató kapcsolódási pontok számát. Csak olvasható **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | Visszaadja az alakzat egyéni adatait. Csak olvasható [ICustomData](../../aspose.slides/icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | Visszaadja a [EffectFormat](../../aspose.slides/effectformat/) objektumot, amely az alakzatra alkalmazott pixelhatásokat tartalmazza. Megjegyzés: bizonyos alakzattípusoknál, amelyeknek nincs effektus tulajdonsága, null értéket adhat vissza. Csak olvasható [IEffectFormat](../../aspose.slides/ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | Visszaadja a [FillFormat](../../aspose.slides/fillformat/) objektumot, amely az alakzat kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzattípusoknál, amelyeknek nincs kitöltési tulajdonsága, null értéket adhat vissza. Csak olvasható [IFillFormat](../../aspose.slides/ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | Visszaadja az alakzat keretének tulajdonságait. Olvasható [IShapeFrame](../../aspose.slides/ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/graphicalobject/get_graphicalobjectlock/)() override | Visszaadja az alakzat zárolásait. Csak olvasható [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | Megkapja az alakzat magasságát pontokban. Olvasható **float**. |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | Megállapítja, hogy az alakzat rejtett-e. Olvasható **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | Visszaadja az egérkattintásra definiált hiperhivatkozást. Olvasható [IHyperlink](../../aspose.slides/ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | Visszaadja a hiperhivatkozáskezelőt. Csak olvasható [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | Visszaadja az egér fölé mutatásra definiált hiperhivatkozást. Olvasható [IHyperlink](../../aspose.slides/ihyperlink/). |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | Lekéri a 'Mark as decorative' beállítást Olvasás/írás **bool**. |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | Megállapítja, hogy az alakzat csoportosított-e. Csak olvasható **bool**. |
| **bool** [get_IsReversed](./get_isreversed/)() override | Visszaadja vagy beállítja a [SmartArt](./) diagram állapotát a (balról jobbra) LTR vagy (jobbról balra) RTL tekintetében, ha a diagram támogatja a fordítást. Olvasható **bool**. |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | Megállapítja, hogy az alakzat TextHolder_PPT-e. Csak olvasható **bool**. |
| [SmartArtLayoutType](../smartartlayouttype/) [get_Layout](./get_layout/)() override | Visszaadja a [SmartArt](./) objektum elrendezését. Olvasható [SmartArtLayoutType](../smartartlayouttype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | Visszaadja a [LineFormat](../../aspose.slides/lineformat/) objektumot, amely az alakzat vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzattípusoknál, amelyeknek nincs vonal tulajdonsága, null értéket adhat vissza. Csak olvasható [ILineFormat](../../aspose.slides/ilineformat/). |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | Visszaadja egy alakzat nevét. Nem lehet null. Szükség esetén használjon üres stringet. Olvasható [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_Node](./get_node/)(**int32_t**) override | Visszaad egy csomópontot a [SmartArt](./) objektum gyökércsomópontok gyűjteményéből a megadott indexnél. Csak olvasható [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_NodeFromAll](./get_nodefromall/)(**int32_t**) override | Visszaad egy csomópontot a [SmartArt](./) objektum összes csomópontot tartalmazó gyűjteményéből a megadott indexnél. Csak olvasható [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_Nodes](./get_nodes/)() override | Visszaadja a [SmartArt](./) objektum gyökércsomópontjainak gyűjteményét. Csak olvasható [ISmartArtNodeCollection](../ismartartnodecollection/). |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | Visszaad egy diára korlátozott egyedi azonosítót, amely a forma élettartama alatt állandó, és lehetővé teszi a PowerPoint vagy interop kód számára, hogy megbízhatóan hivatkozzon a formára a dokumentum bármely részéről. Csak olvasható **uint32_t**. Lásd még [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | Visszaadja a szülő [GroupShape](../../aspose.slides/groupshape/) objektumot, ha az alakzat csoportosított. Ellenkező esetben null értéket ad vissza. Csak olvasható [IGroupShape](../../aspose.slides/igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | Visszaadja az alakzat helyfoglalóját. Ha az alakzatnak nincs helyfoglalója, null értéket ad vissza. Csak olvasható [IPlaceholder](../../aspose.slides/iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | Visszaadja a dia szülő prezentációját. Csak olvasható [IPresentation](../../aspose.slides/ipresentation/). |
| [SmartArtQuickStyleType](../smartartquickstyletype/) [get_QuickStyle](./get_quickstyle/)() override | Visszaadja a [SmartArt](./) objektum gyorsstílusát. Olvasható [SmartArtQuickStyleType](../smartartquickstyletype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | Visszaadja a nyers alakzatforma tulajdonságait. Olvasható [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | Visszaadja a fokok számát, amennyivel a megadott alakzat a z-tengely körül elfordul. A pozitív érték óramutató járásával megegyező forgást jelez; a negatív érték az óramutatóval ellentétes forgást. Olvasható **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | Visszaadja az alakzat zárolásait. Csak olvasható [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | Visszaadja az alakzat szülő diáját. Csak olvasható [IBaseSlide](../../aspose.slides/ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | Visszaadja a [ThreeDFormat](../../aspose.slides/threedformat/) objektumot, amely az alakzat 3D-hatás tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzattípusoknál, amelyeknek nincs 3D tulajdonsága, null értéket adhat vissza. Csak olvasható [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | Visszaad egy belső, prezentációra korlátozott azonosítót, amelyet kiegészítők vagy más kód használhat. Mivel ezt az értéket a felhasználó vagy programozott módon újra lehet rendelni, nem tekinthető állandó egyedi kulcsnak. Csak olvasható **uint32_t**. Lásd még [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/). |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | Megkapja az alakzat szélességét pontokban. Olvasható **float**. |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | Megkapja az alakzat bal felső sarkának x-koordinátáját pontokban. Olvasható **float**. |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | Megkapja az alakzat bal felső sarkának y-koordinátáját pontokban. Olvasható **float**. |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | Visszaadja egy alakzat pozícióját a z-sorrendben. A Shapes[0] a z-sorrend hátul lévő alakzatot adja vissza, a Shapes[Shapes.Count - 1] pedig az előre lévő alakzatot. Csak olvasható **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | Visszaad egy alap helyfoglaló alakzatot (az elrendezésből és/vagy a mesterslájdról származó alakzatot, amelyből az aktuális alakzat örököl). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektummal kapcsolatos referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | Visszaadja az alakzat bélyegképét. [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) alakzat bélyegkép határ típusa használatos alapértelmezés szerint. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | Visszaadja az alakzat bélyegképét. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | Megkapja az alakzat vizuális határait, amelyek a megjelenített tartalomból számítódnak. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() állítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktőr. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozás szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként hasonlítja össze az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | Meghatározza, hogy ez az alakzat nem helyfoglaló. |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | Beállítja az alakzathoz tartozó alternatív szöveget. Írás [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Beállítja az alakzathoz tartozó alternatív szöveg címét. Írás [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | A tulajdonság meghatározza, hogyan jelenik meg egy alakzat fekete-fehér megjelenítési módban. Írás [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| void [set_ColorStyle](./set_colorstyle/)([SmartArtColorType](../smartartcolortype/)) override | Beállítja a [SmartArt](./) objektum színstílusát. Írás [SmartArtColorType](../smartartcolortype/). |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | Beállítja az alakzat keretének tulajdonságait. Írás [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | Beállítja az alakzat magasságát pontokban. Írás **float**. |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | Megállapítja, hogy az alakzat rejtett-e. Írás **bool**. |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | Beállítja az egérkattintásra definiált hiperhivatkozást. Írás [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | Beállítja az egér fölé mutatásra definiált hiperhivatkozást. Írás [IHyperlink](../../aspose.slides/ihyperlink/). |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | Beállítja a 'Mark as decorative' opciót Olvasás/írás **bool**. |
| void [set_IsReversed](./set_isreversed/)(**bool**) override | Visszaadja vagy beállítja a [SmartArt](./) diagram állapotát a (balról jobbra) LTR vagy (jobbról balra) RTL tekintetében, ha a diagram támogatja a fordítást. Írás **bool**. |
| void [set_Layout](./set_layout/)([SmartArtLayoutType](../smartartlayouttype/)) override | Beállítja a [SmartArt](./) objektum elrendezését. Írás [SmartArtLayoutType](../smartartlayouttype/). |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | Beállítja egy alakzat nevét. Nem lehet null. Szükség esetén használjon üres stringet. Írás [System::String](../../system/string/). |
| void [set_QuickStyle](./set_quickstyle/)([SmartArtQuickStyleType](../smartartquickstyletype/)) override | Beállítja a [SmartArt](./) objektum gyorsstílusát. Írás [SmartArtQuickStyleType](../smartartquickstyletype/). |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | Beállítja a nyers alakzatforma tulajdonságait. Írás [IShapeFrame](../../aspose.slides/ishapeframe/). |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | Beállítja a fokok számát, amennyivel a megadott alakzat a z-tengely körül elfordul. A pozitív érték óramutató járásával megegyező forgást jelez; a negatív érték az óramutatóval ellentétes forgást. Írás **float**. |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | Beállítja az alakzat szélességét pontokban. Írás **float**. |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | Beállítja az alakzat bal felső sarkának x-koordinátáját pontokban. Írás **float**. |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | Beállítja az alakzat bal felső sarkának y-koordinátáját pontokban. Írás **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett) állítja. Lehetővé teszi a mutatók konténerekben való gyenge módba való átkapcsolását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() állítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Elmenti a [Shape](../../aspose.slides/shape/) tartalmát SVG fájlként. |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Elmenti a [Shape](../../aspose.slides/shape/) tartalmát SVG fájlként. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [GraphicalObject](../../aspose.slides/graphicalobject/)
* Osztály [ISmartArt](../ismartart/)
* Névtér [Aspose::Slides::SmartArt](../)
* Könyvtár [Aspose.Slides](../../)