---
title: Table
second_title: Aspose.Slides pro C++ referenční příručka API
description: Reprezentuje tabulku na snímku.
type: docs
weight: 5409
url: /cs/aspose.slides/table/
---
## Třída Table

Represents a table on a slide.

```cpp
class Table : public Aspose::Slides::GraphicalObject,
              public Aspose::Slides::ITable
```
## Metody

| Metoda | Popis |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Přidá nový zástupný znak, pokud neexistuje, a nastaví vlastnosti zástupného znaku na zadaný. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnoty ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s typem double ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Vrací alternativní text spjatý s tvarem. Čtěte [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Vrací titulek alternativního textu spjatého s tvarem. Čtěte [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Vlastnost určuje, jak bude tvar vykreslen v černobílém režimu. Čtěte [Slides::BlackWhiteMode](../blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_Column](./get_column/)(**int32_t**) override | Vrací sloupec na zadaném indexu. Pouze pro čtení [Aspose::Slides::IColumn](../icolumn/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumnCollection](../icolumncollection/)\> [get_Columns](./get_columns/)() override | Vrací kolekci sloupců. Pouze pro čtení [IColumnCollection](../icolumncollection/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Vrací počet připojovacích míst na tvaru. Pouze pro čtení **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Vrací vlastní data tvaru. Pouze pro čtení [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Vrací objekt [EffectFormat](../effectformat/), který obsahuje pixelové efekty aplikované na tvar. Poznámka: může vrátit null pro některé typy tvarů, které nemají vlastnosti efektu. Pouze pro čtení [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | Vrací objekt [TableFormat::get_FillFormat](../tableformat/get_fillformat/) obsahující formátování výplně pro [Table](./). Pouze pro čtení [IFillFormat](../ifillformat/). |
| **bool** [get_FirstCol](./get_firstcol/)() override | Určuje, zda má být první sloupec tabulky vykreslen se speciálním formátováním. Čte se **bool**. |
| **bool** [get_FirstRow](./get_firstrow/)() override | Určuje, zda má být první řádek tabulky vykreslen se speciálním formátováním. Čte se **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Vrací vlastnosti rámce tvaru. Čtěte [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | Vrací zamykání tvaru. Pouze pro čtení [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | Získá výšku tvaru, měřenou v bodech. Čte **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Určuje, zda je tvar skrytý. Čte **bool**. |
| **bool** [get_HorizontalBanding](./get_horizontalbanding/)() override | Určuje, zda mají být sudé řádky vykresleny s odlišným formátováním. Čte **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Vrací hypertextový odkaz definovaný pro kliknutí myší. Čtěte [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Vrací správce hypertextových odkazů. Pouze pro čtení [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Vrací hypertextový odkaz definovaný pro najetí myší. Čtěte [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Získá volbu 'Mark as decorative'. Čtení/zápis **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Určuje, zda je tvar seskupen. Pouze pro čtení **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Určuje, zda je tvar TextHolder_PPT. Pouze pro čtení **bool**. |
| **bool** [get_LastCol](./get_lastcol/)() override | Určuje, zda má být poslední sloupec tabulky vykreslen se speciálním formátováním. Čte **bool**. |
| **bool** [get_LastRow](./get_lastrow/)() override | Určuje, zda má být poslední řádek tabulky vykreslen se speciálním formátováním. Čte **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Vrací objekt [LineFormat](../lineformat/), který obsahuje vlastnosti formátování čáry pro tvar. Poznámka: může vrátit null pro některé typy tvarů, které nemají vlastnosti čáry. Pouze pro čtení [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Vrací název tvaru. Nesmí být null. Použijte prázdný řetězec, pokud je to potřeba. Čtěte [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Vrací jedinečný identifikátor v rozsahu snímku, který zůstává konstantní po celou životnost tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu. Pouze pro čtení **uint32_t**. Viz také [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Vrací nadřazený objekt [GroupShape](../groupshape/), pokud je tvar seskupen. Jinak vrací null. Pouze pro čtení [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Vrací zástupný znak pro tvar. Vrací null, pokud tvar nemá zástupný znak. Pouze pro čtení [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Vrací nadřazenou prezentaci snímku. Pouze pro čtení [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Vrací surové vlastnosti rámce tvaru. Čtěte [IShapeFrame](../ishapeframe/). |
| **bool** [get_RightToLeft](./get_righttoleft/)() override | Určuje, zda má tabulka směr čtení zprava doleva. Čte **bool**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | Vrací počet stupňů, o které je určený tvar otočen kolem osy z. Kladná hodnota značí otočení po směru hodinových ručiček; záporná hodnota značí otočení proti směru hodinových ručiček. Čte **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_Row](./get_row/)(**int32_t**) override | Vrací řádek na zadaném indexu. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRowCollection](../irowcollection/)\> [get_Rows](./get_rows/)() override | Vrací kolekci řádků. Pouze pro čtení [IRowCollection](../irowcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Vrací zamykání tvaru. Pouze pro čtení [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Vrací nadřazený snímek tvaru. Pouze pro čtení [IBaseSlide](../ibaseslide/). |
| [TableStylePreset](../tablestylepreset/) [get_StylePreset](./get_stylepreset/)() override | Získá vestavěný styl tabulky. Čtěte [TableStylePreset](../tablestylepreset/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITableFormat](../itableformat/)\> [get_TableFormat](./get_tableformat/)() override | Vrací objekt [TableFormat](../tableformat/), který obsahuje vlastnosti formátování pro tuto tabulku. Pouze pro čtení [ITableFormat](../itableformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Vrací objekt [ThreeDFormat](../threedformat/) s 3D vlastnostmi efektu pro tvar. Poznámka: může vrátit null pro některé typy tvarů, které nemají 3D vlastnosti. Pouze pro čtení [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Vrací interní identifikátor v rozsahu prezentace určený pro použití doplňky nebo jiným kódem. Protože může být uživatelem nebo programově přidělen znovu, nesmí být považován za trvalý jedinečný klíč. Pouze pro čtení **uint32_t**. Viz také [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **bool** [get_VerticalBanding](./get_verticalbanding/)() override | Určuje, zda mají být sudé sloupce vykresleny s odlišným formátováním. Čte **bool**. |
| **float** [get_Width](../shape/get_width/)() override | Získá šířku tvaru, měřenou v bodech. Čte **float**. |
| **float** [get_X](../shape/get_x/)() override | Získá souřadnici x levého horního rohu tvaru, měřenou v bodech. Čte **float**. |
| **float** [get_Y](../shape/get_y/)() override | Získá souřadnici y levého horního rohu tvaru, měřenou v bodech. Čte **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Vrací pozici tvaru v pořadí z. Shapes[0] vrací tvar na konci z-řazení, a Shapes[Shapes.Count - 1] vrací tvar na začátku z-řazení. Pouze pro čtení **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Vrací základní tvar zástupného znaku (tvar z rozložení a/nebo hlavního snímku, ze kterého je aktuální tvar zděděn). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# metody [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Vrací náhled tvaru. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) typ ohraničení náhledu tvaru je použit ve výchozím nastavení. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Vrací náhled tvaru. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Získá vizuální ohraničení tvaru vypočtené z jeho vykresleného obsahu. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) override | Vrací buňku na zadaných indexech sloupce a řádku. Pouze pro čtení [Cell](../cell/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# metody [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [MergeCells](./mergecells/)([System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, **bool**) override | Spojí sousední buňky. |
|   [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|   [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nezkopíruje nic, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nezkopíruje nic, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač odkazů o zadanou hodnotu. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Definuje, že tento tvar není zástupný znak. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Nastaví alternativní text spjatý s tvarem. Zapište [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Nastaví titulek alternativního textu spjatého s tvarem. Zapište [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Vlastnost určuje, jak bude tvar vykreslen v černobílém režimu. Zapište [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_FirstCol](./set_firstcol/)(**bool**) override | Určuje, zda má být první sloupec tabulky vykreslen se speciálním formátováním. Zapište **bool**. |
| void [set_FirstRow](./set_firstrow/)(**bool**) override | Určuje, zda má být první řádek tabulky vykreslen se speciálním formátováním. Zapište **bool**. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Nastaví vlastnosti rámce tvaru. Zapište [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Nastaví výšku tvaru, měřenou v bodech. Zapište **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Určuje, zda je tvar skryt. Zapište **bool**. |
| void [set_HorizontalBanding](./set_horizontalbanding/)(**bool**) override | Určuje, zda mají být sudé řádky vykresleny s odlišným formátováním. Zapište **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Nastaví hypertextový odkaz definovaný pro kliknutí myší. Zapište [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Nastaví hypertextový odkaz definovaný pro najetí myší. Zapište [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Nastaví volbu 'Mark as decorative'. Čtení/zápis **bool**. |
| void [set_LastCol](./set_lastcol/)(**bool**) override | Určuje, zda má být poslední sloupec tabulky vykreslen se speciálním formátováním. Zapište **bool**. |
| void [set_LastRow](./set_lastrow/)(**bool**) override | Určuje, zda má být poslední řádek tabulky vykreslen se speciálním formátováním. Zapište **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Nastaví název tvaru. Nesmí být null. Použijte prázdný řetězec, pokud je potřeba. Zapište [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Nastaví surové vlastnosti rámce tvaru. Zapište [IShapeFrame](../ishapeframe/). |
| void [set_RightToLeft](./set_righttoleft/)(**bool**) override | Určuje, zda má tabulka směr čtení zprava doleva. Zapisuje **bool**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Nastaví počet stupňů, o které je určený tvar otočen kolem osy z. Kladná hodnota značí otočení po směru hodinových ručiček; záporná hodnota značí otočení proti směru hodinových ručiček. Zapište **float**. |
| void [set_StylePreset](./set_stylepreset/)([TableStylePreset](../tablestylepreset/)) override | Nastaví vestavěný styl tabulky. Zapište [TableStylePreset](../tablestylepreset/). |
| void [set_VerticalBanding](./set_verticalbanding/)(**bool**) override | Určuje, zda mají být sudé sloupce vykresleny s odlišným formátováním. Zapište **bool**. |
| void [set_Width](../shape/set_width/)(**float**) override | Nastaví šířku tvaru, měřenou v bodech. Zapište **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Nastaví souřadnici x levého horního rohu tvaru, měřenou v bodech. Zapište **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Nastaví souřadnici y levého horního rohu tvaru, měřenou v bodech. Zapište **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\>) override | Nastaví definované formátování částí na všechny části buněk tabulky. |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormat](../iparagraphformat/)\>) override | Nastaví definované formátování odstavců na všechny odstavce buněk tabulky. |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormat](../itextframeformat/)\>) override | Nastaví definované formátování textových rámců na všechny textové rámce buněk tabulky. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# metody [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Uloží obsah [Shape](../shape/) jako SVG soubor. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Uloží obsah [Shape](../shape/) jako SVG soubor. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [GraphicalObject](../graphicalobject/)
* Třída [ITable](../itable/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)