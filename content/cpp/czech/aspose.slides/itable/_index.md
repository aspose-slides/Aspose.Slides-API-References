---
title: ITable
second_title: Aspose.Slides pro C++ – reference API
description: Představuje tabulku na snímku.
type: docs
weight: 4018
url: /cs/aspose.slides/itable/
---
## ITable třída

Represents a table on a slide.

```cpp
class ITable : public virtual Aspose::Slides::IGraphicalObject,
               public Aspose::Slides::IBulkTextFormattable
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Přidá nový placeholder, pokud neexistuje, a nastaví vlastnosti placeholderu na specifikovaný. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovná objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty typů hodnot ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Vrací alternativní text spojený s tvarem. Číst [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Vrací název alternativního textu spojeného s tvarem. Číst [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Vlastnost určuje, jak bude tvar vykreslen v režimu černobílého zobrazení. Číst [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_Column](./get_column/)(**int32_t**) | Vrací sloupec na zadaném indexu. Pouze pro čtení [Aspose::Slides::IColumn](../icolumn/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumnCollection](../icolumncollection/)\> [get_Columns](./get_columns/)() | Vrací kolekci sloupců. Pouze pro čtení [IColumnCollection](../icolumncollection/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Vrací počet připojovacích míst na tvaru. Pouze pro čtení **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Vrací vlastní data tvaru. Pouze pro čtení [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Vrací objekt [EffectFormat](../effectformat/), který obsahuje pixelové efekty aplikované na tvar. Pouze pro čtení [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Vrací objekt [FillFormat](../fillformat/), který obsahuje vlastnosti výplně pro tvar. Pouze pro čtení [IFillFormat](../ifillformat/). |
| virtual **bool** [get_FirstCol](./get_firstcol/)() | Určuje, zda má být první sloupec tabulky vykreslen se zvláštním formátováním. Číst **bool**. |
| virtual **bool** [get_FirstRow](./get_firstrow/)() | Určuje, zda má být první řádek tabulky vykreslen se zvláštním formátováním. Číst **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Vrací vlastnosti rámce tvaru. Číst [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | Vrací zámky tvaru. Pouze pro čtení [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Získá výšku tvaru, měřenou v bodech. Číst **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Určuje, zda je tvar skrytý. Číst **bool**. |
| virtual **bool** [get_HorizontalBanding](./get_horizontalbanding/)() | Určuje, zda mají být sudé řádky vykresleny s odlišným formátováním. Číst **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Vrací hyperodkaz definovaný pro kliknutí myší. Číst [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Správce hyperodkazů. Pouze pro čtení [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Vrací hyperodkaz definovaný pro přejetí myší. Číst [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Získá volbu 'Mark as decorative'. Číst/zapisovat **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Určuje, zda je tvar seskupen. Pouze pro čtení **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Určuje, zda je tvar TextHolder. Pouze pro čtení **bool**. |
| virtual **bool** [get_LastCol](./get_lastcol/)() | Určuje, zda má být poslední sloupec tabulky vykreslen se zvláštním formátováním. Číst **bool**. |
| virtual **bool** [get_LastRow](./get_lastrow/)() | Určuje, zda má být poslední řádek tabulky vykreslen se zvláštním formátováním. Číst **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Vrací objekt [LineFormat](../lineformat/), který obsahuje vlastnosti formátování čáry pro tvar. Pouze pro čtení [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Vrací název tvaru. Číst [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou životnost tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu. Pouze pro čtení **uint32_t**. Viz také [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Vrací nadřazený objekt [GroupShape](../groupshape/), pokud je tvar seskupen. V opačném případě vrací null. Pouze pro čtení [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Vrací placeholder pro tvar. Pouze pro čtení [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Vrací prezentaci. Pouze pro čtení [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Vrací surové vlastnosti rámce tvaru. Číst [IShapeFrame](../ishapeframe/). |
| virtual **bool** [get_RightToLeft](./get_righttoleft/)() | Určuje, zda má tabulka pravý-od-levý čtecí pořádek. Čte **bool**. |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Vrací počet stupňů, o které je specifikovaný tvar otočen kolem osy z. Kladná hodnota značí rotaci po směru hodinových ručiček; záporná hodnota značí rotaci proti směru hodinových ručiček. Číst **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_Row](./get_row/)(**int32_t**) | Vrací řádek na zadaném indexu. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRowCollection](../irowcollection/)\> [get_Rows](./get_rows/)() | Vrací kolekci řádků. Pouze pro čtení [IRowCollection](../irowcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Vrací zámky tvaru. Pouze pro čtení [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Vrací základní snímek. Pouze pro čtení [IBaseSlide](../ibaseslide/). |
| virtual [TableStylePreset](../tablestylepreset/) [get_StylePreset](./get_stylepreset/)() | Získá nebo nastaví vestavěný styl tabulky. Číst [TableStylePreset](../tablestylepreset/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITableFormat](../itableformat/)\> [get_TableFormat](./get_tableformat/)() | Vrací objekt [TableFormat](../tableformat/), který obsahuje vlastnosti formátování pro tuto tabulku. Pouze pro čtení [ITableFormat](../itableformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Vrací objekt [ThreeDFormat](../threedformat/), který obsahuje vlastnosti formátování čáry pro tvar. Pouze pro čtení [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Vrací interní identifikátor v rámci prezentace určený pro použití doplňky nebo jiným kódem. Protože tato hodnota může být uživatelem nebo programově změněna, neměla by být považována za trvalý jedinečný klíč. Pouze pro čtení **uint32_t**. Viz také [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **bool** [get_VerticalBanding](./get_verticalbanding/)() | Určuje, zda mají být sudé sloupce vykresleny s odlišným formátováním. Číst **bool**. |
| virtual **float** [get_Width](../ishape/get_width/)() | Získá šířku tvaru, měřenou v bodech. Číst **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Získá souřadnici x levého horního rohu tvaru, měřenou v bodech. Číst **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Získá souřadnici y levého horního rohu tvaru, měřenou v bodech. Číst **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Vrací pozici tvaru v pořadí z. Shapes[0] vrací tvar na konci z-řazení a Shapes[Shapes.Count - 1] vrací tvar na začátku z-řazení. Pouze pro čtení **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Vrací základní placeholder tvar (tvar z rozvržení a/nebo master snímku, ze kterého je aktuální tvar zděděn). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá strukturu počítadla odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Vrací miniaturu tvaru. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) typ ohraničení miniatury tvaru se používá ve výchozím nastavení. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Vrací miniaturu tvaru. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) | Vrací buňku na zadaných indexech sloupce a řádku. Pouze pro čtení [ICell](../icell/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání C# lock() příkazem. Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [MergeCells](./mergecells/)([System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, **bool**) | Sloučí sousední buňky. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovná objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovná objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovná referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ string a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač odkazů o zadanou hodnotu. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Definuje, že tento tvar není placeholder. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Nastaví alternativní text spojený s tvarem. Zapisovat [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Nastaví název alternativního textu spojeného s tvarem. Zapisovat [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Vlastnost určuje, jak bude tvar vykreslen v režimu černobílého zobrazení. Zapisovat [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_FirstCol](./set_firstcol/)(**bool**) | Určuje, zda má být první sloupec tabulky vykreslen se zvláštním formátováním. Zapisovat **bool**. |
| virtual void [set_FirstRow](./set_firstrow/)(**bool**) | Určuje, zda má být první řádek tabulky vykreslen se zvláštním formátováním. Zapisovat **bool**. |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Nastaví vlastnosti rámce tvaru. Zapisovat [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Nastaví výšku tvaru, měřenou v bodech. Zapisovat **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Určuje, zda je tvar skrytý. Zapisovat **bool**. |
| virtual void [set_HorizontalBanding](./set_horizontalbanding/)(**bool**) | Určuje, zda mají být sudé řádky vykresleny s odlišným formátováním. Zapisovat **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Nastaví hyperodkaz definovaný pro kliknutí myší. Zapisovat [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Nastaví hyperodkaz definovaný pro přejetí myší. Zapisovat [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Nastaví volbu 'Mark as decorative'. Číst/zapisovat **bool**. |
| virtual void [set_LastCol](./set_lastcol/)(**bool**) | Určuje, zda má být poslední sloupec tabulky vykreslen se zvláštním formátováním. Zapisovat **bool**. |
| virtual void [set_LastRow](./set_lastrow/)(**bool**) | Určuje, zda má být poslední řádek tabulky vykreslen se zvláštním formátováním. Zapisovat **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Nastaví název tvaru. Zapisovat [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Nastaví surové vlastnosti rámce tvaru. Zapisovat [IShapeFrame](../ishapeframe/). |
| virtual void [set_RightToLeft](./set_righttoleft/)(**bool**) | Určuje, zda má tabulka pravý-od-levý čtecí pořádek. Zapisovat **bool**. |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Nastaví počet stupňů, o které je specifikovaný tvar otočen kolem osy z. Kladná hodnota značí rotaci po směru hodinových ručiček; záporná hodnota značí rotaci proti směru hodinových ručiček. Zapisovat **float**. |
| virtual void [set_StylePreset](./set_stylepreset/)([TableStylePreset](../tablestylepreset/)) | Získá nebo nastaví vestavěný styl tabulky. Zapisovat [TableStylePreset](../tablestylepreset/). |
| virtual void [set_VerticalBanding](./set_verticalbanding/)(**bool**) | Určuje, zda mají být sudé sloupce vykresleny s odlišným formátováním. Zapisovat **bool**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Nastaví šířku tvaru, měřenou v bodech. Zapisovat **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Nastaví souřadnici x levého horního rohu tvaru, měřenou v bodech. Zapisovat **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Nastaví souřadnici y levého horního rohu tvaru, měřenou v bodech. Zapisovat **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako weak pointer (namísto shared). Umožňuje přepínání ukazatelů v kontejnerech do weak režimu. |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\>) | Nastaví definované vlastnosti formátu části na všechny části prvku. |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormat](../iparagraphformat/)\>) | Nastaví definované vlastnosti formátu odstavce na všechny odstavce prvku. |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormat](../itextframeformat/)\>) | Nastaví definované vlastnosti formátu textového rámce na všechny textové rámečky prvku. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte smart ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte smart ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení C# lock() příkazem. Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje weak čítač odkazů. Nemělo by se volat přímo; místo toho použijte smart ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje weak čítač odkazů. Nemělo by se volat příně; místo toho použijte smart ukazatele nebo ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Uloží obsah [Shape](../shape/) jako SVG soubor. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Uloží obsah [Shape](../shape/) jako SVG soubor. |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolňuje všechny vnitřní datové struktury. |

## Viz také

* Třída [IGraphicalObject](../igraphicalobject/)
* Třída [IBulkTextFormattable](../ibulktextformattable/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)