---
title: ICell
second_title: Aspose.Slides voor C++ API-referentie
description: Vertegenwoordigt een cel in een tabel.
type: docs
weight: 1639
url: /nl/aspose.slides/icell/
---
## ICell klasse

Vertegenwoordigt een cel in een tabel.

```cpp
class ICell : public Aspose::Slides::ISlideComponent
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-achtige vergelijking van zwevende kommagetallen waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-achtige vergelijking van zwevende kommagetallen waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| virtual **bool** [get_AnchorCenter](./get_anchorcenter/)() | Bepaalt of het tekstvak binnen een cel gecentreerd is. Lezen **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() | Retourneert het [CellFormat](../cellformat/)-object dat opmaak-eigenschappen voor deze cel bevat. Alleen-lezen [ICellFormat](../icellformat/). |
| virtual **int32_t** [get_ColSpan](./get_colspan/)() | Retourneert het aantal rasterkolommen in het tabelraster van de bovenliggende tabel die door de huidige cel worden overspannen. Deze eigenschap maakt het mogelijk dat cellen de indruk wekken samengevoegd te zijn, doordat ze verticale grenzen van andere cellen in de tabel overspannen. Alleen-lezen **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() | Haalt eerste kolom van cel. Alleen-lezen [IColumn](../icolumn/). |
| virtual **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() | Retourneert een index van de eerste kolom die door de cel wordt gedekt. Alleen-lezen **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() | Haalt eerste rij van cel. Alleen-lezen [IRow](../irow/). |
| virtual **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() | Retourneert een index van de eerste rij die door de cel wordt gedekt. Alleen-lezen **int32_t**. |
| virtual **double** [get_Height](./get_height/)() | Retourneert de hoogte van de cel. Alleen-lezen **double**. |
| virtual **bool** [get_IsMergedCell](./get_ismergedcell/)() | Retourneert true als de cel is samengevoegd met een aangepaste cel, anders false. Alleen-lezen **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Retourneert de onderste marge in een [TextFrame](../textframe/). Lezen **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Retourneert de linker marge in een [TextFrame](../textframe/). Lezen **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Retourneert de rechter marge in een [TextFrame](../textframe/). Lezen **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Retourneert de bovenste marge in een [TextFrame](../textframe/). Lezen **double**. |
| virtual **double** [get_MinimalHeight](./get_minimalheight/)() | Retourneert de minimale hoogte van een cel. Dit is de som van de minimale hoogtes van alle rijen die door de cel worden bedekt. Alleen-lezen **double**. |
| virtual **double** [get_OffsetX](./get_offsetx/)() | Retourneert een afstand van de linkerkant van een tabel tot de linkerkant van een cel. Alleen-lezen **double**. |
| virtual **double** [get_OffsetY](./get_offsety/)() | Retourneert een afstand van de bovenkant van een tabel tot de bovenkant van een cel. Alleen-lezen **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Retourneert de presentatie. Alleen-lezen [IPresentation](../ipresentation/). |
| virtual **int32_t** [get_RowSpan](./get_rowspan/)() | Retourneert het aantal rijen dat een samengevoegde cel overspant. Dit wordt in combinatie met het vMerge-attribuut op andere cellen gebruikt om de begincel van een horizontale samenvoeging te specificeren. Alleen-lezen **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Retourneert de basistabblad. Alleen-lezen [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() | Retourneert het bovenliggende [Table](../table/)-object voor een cel. Alleen-lezen [ITable](../itable/). |
| virtual [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() | Retourneert het tekstankertype. Lezen [Slides::TextAnchorType](../textanchortype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() | Retourneert het tekstkader van een cel. Alleen-lezen [ITextFrame](../itextframe/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Retourneert het type verticale tekst. Lezen [Slides::TextVerticalType](../textverticaltype/). |
| virtual **double** [get_Width](./get_width/)() | Retourneert de breedte van de cel. Alleen-lezen **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt het hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type dat wordt beschreven door targetType. Analoge van C# ‘is’-operator. |
| void [Lock](../../system/object/lock/)() | Implementatie van C# lock()-statement vergrendeling. Direct aanroepen of [LockContext](../../system/lockcontext/)-bewakingsobject gebruiken. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt het klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert in feite niets, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert in feite niets, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_AnchorCenter](./set_anchorcenter/)(**bool**) | Bepaalt of het tekstvak binnen een cel gecentreerd is. Schrijf **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Stelt de onderste marge in een [TextFrame](../textframe/) in. Schrijf **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Stelt de linker marge in een [TextFrame](../textframe/) in. Schrijf **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Stelt de rechter marge in een [TextFrame](../textframe/) in. Schrijf **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Stelt de bovenste marge in een [TextFrame](../textframe/) in. Schrijf **double**. |
| virtual void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) | Stelt het tekstankertype in. Schrijf [Slides::TextAnchorType](../textanchortype/). |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Stelt het type verticale tekst in. Schrijf [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeelde). Maakt het mogelijk om pointers in containers naar zwakke modus te wijzigen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt huidige waarde van gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual void [SplitByColSpan](./splitbycolspan/)(**int32_t**) | Splitst de cel in twee cellen op kolomindex. |
| virtual void [SplitByHeight](./splitbyheight/)(**double**) | Splitst de cel op hoogte. |
| virtual void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) | Splitst de cel in twee cellen op rij-index. |
| virtual void [SplitByWidth](./splitbywidth/)(**double**) | Splitst de cel op breedte. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het mogelijk om aangepaste objecten naar string te converteren. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementatie van C# typeof([System.Object](../../system/object/))-constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementatie van C# lock()-statement ontgrendeling. Direct aanroepen of [LockContext](../../system/lockcontext/)-bewakingsobject gebruiken. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |

## Zie ook

* Klasse [ISlideComponent](../islidecomponent/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)