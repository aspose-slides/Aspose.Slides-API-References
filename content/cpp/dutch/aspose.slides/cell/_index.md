---
title: Cell
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een cel van een tabel voor.
type: docs
weight: 300
url: /nl/aspose.slides/cell/
---
## Cell klasse

Stelt een cel van een tabel voor.

```cpp
class Cell : public Aspose::Slides::IDOMObject,
             public Aspose::Slides::ICell
```

## Methoden

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevende-kommaget vergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevende-kommaget vergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **bool** [get_AnchorCenter](./get_anchorcenter/)() override | Bepaalt of het tekstvak binnen een cel gecentreerd is. Lezen **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() override | Retourneert het [CellFormat](../cellformat/) object dat de opmaak-eigenschappen voor deze cel bevat. Alleen-lezen [ICellFormat](../icellformat/). |
| **int32_t** [get_ColSpan](./get_colspan/)() override | Retourneert het aantal rasterkolommen in het tabelraster van de bovenliggende tabel dat door de huidige cel wordt overspannen. Deze eigenschap maakt het mogelijk dat cellen de uitstraling hebben van samengevoegd te zijn, doordat ze verticale grenzen van andere cellen in de tabel overspannen. Alleen-lezen **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() override | Haalt de eerste kolom van de cel op. Alleen-lezen [IColumn](../icolumn/). |
| **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() override | Retourneert een index van de eerste kolom die door de cel wordt gedekt. Alleen-lezen **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() override | Haalt de eerste rij van de cel op. Alleen-lezen [IRow](../irow/). |
| **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() override | Retourneert een index van de eerste rij die door de cel wordt gedekt. Alleen-lezen **int32_t**. |
| **double** [get_Height](./get_height/)() override | Retourneert de hoogte van de cel. Alleen-lezen **double**. |
| **bool** [get_IsMergedCell](./get_ismergedcell/)() override | Retourneert true als de cel is samengevoegd met een aangepaste cel, anders false. Alleen-lezen **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Retourneert de onderste marge in een [TextFrame](../textframe/). Lezen **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Retourneert de linkermarge in een [TextFrame](../textframe/). Lezen **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Retourneert de rechtermarge in een [TextFrame](../textframe/). Lezen **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Retourneert de bovenste marge in een [TextFrame](../textframe/). Lezen **double**. |
| **double** [get_MinimalHeight](./get_minimalheight/)() override | Retourneert de minimale hoogte van een cel. Dit is de som van de minimale hoogtes van alle rijen die door de cel worden gedekt. Alleen-lezen **double**. |
| **double** [get_OffsetX](./get_offsetx/)() override | Retourneert een afstand van de linkerkant van een tabel tot de linkerkant van een cel. Alleen-lezen **double**. |
| **double** [get_OffsetY](./get_offsety/)() override | Retourneert een afstand van de bovenkant van een tabel tot de bovenkant van een cel. Alleen-lezen **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | Retourneert de bovenliggende presentatie van een cel. Alleen-lezen [IPresentation](../ipresentation/). |
| **int32_t** [get_RowSpan](./get_rowspan/)() override | Retourneert het aantal rijen dat door een samengevoegde cel wordt overspannen. Dit wordt gebruikt in combinatie met het vMerge-attribuut op andere cellen om de begincel van een horizontale samenvoeging te specificeren. Alleen-lezen **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | Retourneert de bovenliggende dia van een cel. Alleen-lezen [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() override | Retourneert het bovenliggende [Table](../table/) object voor een cel. Alleen-lezen [ITable](../itable/). |
| [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() override | Retourneert het tekst-ankertype. Lezen [Slides::TextAnchorType](../textanchortype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | Retourneert het tekstframe van een cel. Alleen-lezen [ITextFrame](../itextframe/). |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Retourneert het type van verticale tekst. Lezen [Slides::TextVerticalType](../textverticaltype/). |
| **double** [get_Width](./get_width/)() override | Retourneert de breedte van de cel. Alleen-lezen **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analog van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analog van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets werkelijk, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets werkelijk, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentietelling met de opgegeven waarde. |
| void [set_AnchorCenter](./set_anchorcenter/)(**bool**) override | Bepaalt of het tekstvak binnen een cel gecentreerd is. Schrijf **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Stelt de onderste marge in een [TextFrame](../textframe/) in. Schrijf **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Stelt de linkermarge in een [TextFrame](../textframe/) in. Schrijf **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Stelt de rechtermarge in een [TextFrame](../textframe/) in. Schrijf **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Stelt de bovenste marge in een [TextFrame](../textframe/) in. Schrijf **double**. |
| void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) override | Stelt het tekst-ankertype in. Schrijf [Slides::TextAnchorType](../textanchortype/). |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Stelt het type van verticale tekst in. Schrijf [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'th template-argument in als een zwakke aanwijzer (in plaats van gedeeld). Maakt het mogelijk om aanwijzers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentietelling. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentietelling. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [SplitByColSpan](./splitbycolspan/)(**int32_t**) override | Splitst de cel in twee cellen op basis van kolomindex. |
| void [SplitByHeight](./splitbyheight/)(**double**) override | Splitst de cel op hoogte. |
| void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) override | Splitst de cel in twee cellen op basis van rij-index. |
| void [SplitByWidth](./splitbywidth/)(**double**) override | Splitst de cel op breedte. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentietelling. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentietelling. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [IDOMObject](../idomobject/)
* Klasse [ICell](../icell/)
* Namespace [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)