---
title: ICell
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Reprezentuje buňku v tabulce.
type: docs
weight: 1639
url: /cs/aspose.slides/icell/
---
## ICell třída

Represents a cell in a table.

```cpp
class ICell : public Aspose::Slides::ISlideComponent
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantik C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnoty ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual **bool** [get_AnchorCenter](./get_anchorcenter/)() | Určuje, zda je textové pole vevnitř buňky centrováno. Čte **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() | Vrací objekt [CellFormat](../cellformat/), který obsahuje formátovací vlastnosti pro tuto buňku. Pouze pro čtení [ICellFormat](../icellformat/). |
| virtual **int32_t** [get_ColSpan](./get_colspan/)() | Vrací počet sloupců mřížky v tabulce nadřazené tabulky, které má aktuální buňka překrývat. Toto vlastnost umožňuje buňkám vypadat, jako by byly sloučeny, protože překrývají svislé hranice jiných buněk v tabulce. Pouze pro čtení **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() | Získá první sloupec buňky. Pouze pro čtení [IColumn](../icolumn/). |
| virtual **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() | Vrací index prvního sloupce, který buňka pokrývá. Pouze pro čtení **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() | Získá první řádek buňky. Pouze pro čtení [IRow](../irow/). |
| virtual **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() | Vrací index prvního řádku, který buňka pokrývá. Pouze pro čtení **int32_t**. |
| virtual **double** [get_Height](./get_height/)() | Vrací výšku buňky. Pouze pro čtení **double**. |
| virtual **bool** [get_IsMergedCell](./get_ismergedcell/)() | Vrací true, pokud je buňka sloučena s jakoukoli upravenou buňkou, jinak false. Pouze pro čtení **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Vrací spodní okraj v [TextFrame](../textframe/). Čte **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Vrací levý okraj v [TextFrame](../textframe/). Čte **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Vrací pravý okraj v [TextFrame](../textframe/). Čte **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Vrací horní okraj v [TextFrame](../textframe/). Čte **double**. |
| virtual **double** [get_MinimalHeight](./get_minimalheight/)() | Vrací minimální výšku buňky. Toto je součet minimálních výšek všech řádků pokrytých buňkou. Pouze pro čtení **double**. |
| virtual **double** [get_OffsetX](./get_offsetx/)() | Vrací vzdálenost z levé strany tabulky k levé straně buňky. Pouze pro čtení **double**. |
| virtual **double** [get_OffsetY](./get_offsety/)() | Vrací vzdálenost z horní strany tabulky k horní straně buňky. Pouze pro čtení **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Vrací prezentaci. Pouze pro čtení [IPresentation](../ipresentation/). |
| virtual **int32_t** [get_RowSpan](./get_rowspan/)() | Vrací počet řádků, které sloučená buňka překrývá. Toto se používá v kombinaci s atributem vMerge na dalších buňkách pro určení počáteční buňky horizontálního sloučení. Pouze pro čtení **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Vrací základní snímek. Pouze pro čtení [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() | Vrací nadřazený objekt [Table](../table/) buňky. Pouze pro čtení [ITable](../itable/). |
| virtual [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() | Vrací typ ukotvení textu. Čte [Slides::TextAnchorType](../textanchortype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() | Vrací textový rám buňky. Pouze pro čtení [ITextFrame](../itextframe/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Vrací typ svislého textu. Čte [Slides::TextVerticalType](../textverticaltype/). |
| virtual **double** [get_Width](./get_width/)() | Vrací šířku buňky. Pouze pro čtení **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| virtual void [set_AnchorCenter](./set_anchorcenter/)(**bool**) | Určuje, zda je textové pole vevnitř buňky centrováno. Zapíše **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Nastavuje spodní okraj v [TextFrame](../textframe/). Zapíše **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Nastavuje levý okraj v [TextFrame](../textframe/). Zapíše **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Nastavuje pravý okraj v [TextFrame](../textframe/). Zapíše **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Nastavuje horní okraj v [TextFrame](../textframe/). Zapíše **double**. |
| virtual void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) | Nastavuje typ ukotvení textu. Zapíše [Slides::TextAnchorType](../textanchortype/). |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Nastavuje typ svislého textu. Zapíše [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument na slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual void [SplitByColSpan](./splitbycolspan/)(**int32_t**) | Rozdělí buňku na dvě buňky podle indexu sloupce. |
| virtual void [SplitByHeight](./splitbyheight/)(**double**) | Rozdělí buňku podle výšky. |
| virtual void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) | Rozdělí buňku na dvě buňky podle indexu řádku. |
| virtual void [SplitByWidth](./splitbywidth/)(**double**) | Rozdělí buňku podle šířky. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolňuje všechny vnitřní datové struktury. |
## Viz také

* Třída [ISlideComponent](../islidecomponent/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)