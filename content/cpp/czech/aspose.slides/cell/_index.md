---
title: Cell
second_title: Aspose.Slides pro C++ API Reference
description: Reprezentuje buňku tabulky.
type: docs
weight: 300
url: /cs/aspose.slides/cell/
---
## Cell třída

Reprezentuje buňku tabulky.

```cpp
class Cell : public Aspose::Slides::IDOMObject,
             public Aspose::Slides::ICell
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| **bool** [get_AnchorCenter](./get_anchorcenter/)() override | Určuje, zda je textové pole vycentrované uvnitř buňky. Čte **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() override | Vrací objekt [CellFormat](../cellformat/), který obsahuje vlastnosti formátování pro tuto buňku. Pouze pro čtení [ICellFormat](../icellformat/). |
| **int32_t** [get_ColSpan](./get_colspan/)() override | Vrací počet sloupců v mřížce tabulky rodiče, které má buňka pokrýt. Tato vlastnost umožňuje buňkám vypadat jako sloučené, protože přesahují vertikální hranice jiných buněk v tabulce. Pouze pro čtení **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() override | Získává první sloupec buňky. Pouze pro čtení [IColumn](../icolumn/). |
| **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() override | Vrací index prvního sloupce, který buňka pokrývá. Pouze pro čtení **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() override | Získává první řádek buňky. Pouze pro čtení [IRow](../irow/). |
| **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() override | Vrací index prvního řádku, který buňka pokrývá. Pouze pro čtení **int32_t**. |
| **double** [get_Height](./get_height/)() override | Vrací výšku buňky. Pouze pro čtení **double**. |
| **bool** [get_IsMergedCell](./get_ismergedcell/)() override | Vrací true, pokud je buňka sloučena s libovolnou upravenou buňkou, jinak false. Pouze pro čtení **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Vrací spodní okraj v [TextFrame](../textframe/). Čte **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Vrací levý okraj v [TextFrame](../textframe/). Čte **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Vrací pravý okraj v [TextFrame](../textframe/). Čte **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Vrací horní okraj v [TextFrame](../textframe/). Čte **double**. |
| **double** [get_MinimalHeight](./get_minimalheight/)() override | Vrací minimální výšku buňky. Jedná se o součet minimálních výšek všech řádků, které buňka pokrývá. Pouze pro čtení **double**. |
| **double** [get_OffsetX](./get_offsetx/)() override | Vrací vzdálenost z levé strany tabulky k levé straně buňky. Pouze pro čtení **double**. |
| **double** [get_OffsetY](./get_offsety/)() override | Vrací vzdálenost z horní strany tabulky k horní straně buňky. Pouze pro čtení **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | Vrací nadřazenou prezentaci buňky. Pouze pro čtení [IPresentation](../ipresentation/). |
| **int32_t** [get_RowSpan](./get_rowspan/)() override | Vrací počet řádků, které sloučená buňka zabírá. Používá se v kombinaci s atributem vMerge na dalších buňkách pro určení počáteční buňky horizontálního sloučení. Pouze pro čtení **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | Vrací nadřazený snímek buňky. Pouze pro čtení [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() override | Vrací nadřazený objekt [Table](../table/) pro buňku. Pouze pro čtení [ITable](../itable/). |
| [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() override | Vrací typ ukotvení textu. Čte [Slides::TextAnchorType](../textanchortype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | Vrací textový rámec buňky. Pouze pro čtení [ITextFrame](../itextframe/). |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Vrací typ svislého textu. Čte [Slides::TextVerticalType](../textverticaltype/). |
| **double** [get_Width](./get_width/)() override | Vrací šířku buňky. Pouze pro čtení **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu referenčního čítače spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání příkazu C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
| [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává hodnotový typ objektu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený referenční čítač o zadanou hodnotu. |
| void [set_AnchorCenter](./set_anchorcenter/)(**bool**) override | Určuje, zda je textové pole vycentrované uvnitř buňky. Zapíše **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Nastavuje spodní okraj v [TextFrame](../textframe/). Zapíše **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Nastavuje levý okraj v [TextFrame](../textframe/). Zapíše **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Nastavuje pravý okraj v [TextFrame](../textframe/). Zapíše **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Nastavuje horní okraj v [TextFrame](../textframe/). Zapíše **double**. |
| void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) override | Nastavuje typ ukotvení textu. Zapíše [Slides::TextAnchorType](../textanchortype/). |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Nastavuje typ svislého textu. Zapíše [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného referenčního čítače. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený referenční čítač. Není vhodné volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený referenční čítač. Není vhodné volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [SplitByColSpan](./splitbycolspan/)(**int32_t**) override | Rozděluje buňku na dvě buňky podle indexu sloupce. |
| void [SplitByHeight](./splitbyheight/)(**double**) override | Rozděluje buňku podle výšky. |
| void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) override | Rozděluje buňku na dvě buňky podle indexu řádku. |
| void [SplitByWidth](./splitbywidth/)(**double**) override | Rozděluje buňku podle šířky. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí příkazu C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý referenční čítač. Není vhodné volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý referenční čítač. Není vhodné volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niči objekt. Uvolňuje všechny vnitřní datové struktury. |

## Viz také

* Class [IDOMObject](../idomobject/)
* Class [ICell](../icell/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)