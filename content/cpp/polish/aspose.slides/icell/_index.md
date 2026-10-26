---
title: ICell
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Reprezentuje komórkę w tabeli.
type: docs
weight: 1639
url: /pl/aspose.slides/icell/
---
## Klasa ICell

Represents a cell in a table.

```cpp
class ICell : public Aspose::Slides::ISlideComponent
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartości w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual **bool** [get_AnchorCenter](./get_anchorcenter/)() | Określa, czy pole tekstowe jest wyśrodkowane w komórce. Odczyt **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() | Zwraca obiekt [CellFormat](../cellformat/) zawierający właściwości formatowania dla tej komórki. Tylko do odczytu [ICellFormat](../icellformat/). |
| virtual **int32_t** [get_ColSpan](./get_colspan/)() | Zwraca liczbę kolumn siatki w tabeli nadrzędnej, które mają być obejmowane przez bieżącą komórkę. To właściwość pozwalająca komórkom wyglądać jak połączone, gdy obejmują pionowe granice innych komórek w tabeli. Tylko do odczytu **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() | Pobiera pierwszą kolumnę komórki. Tylko do odczytu [IColumn](../icolumn/). |
| virtual **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() | Zwraca indeks pierwszej kolumny objętej przez komórkę. Tylko do odczytu **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() | Pobiera pierwszy wiersz komórki. Tylko do odczytu [IRow](../irow/). |
| virtual **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() | Zwraca indeks pierwszego wiersza objętego przez komórkę. Tylko do odczytu **int32_t**. |
| virtual **double** [get_Height](./get_height/)() | Zwraca wysokość komórki. Tylko do odczytu **double**. |
| virtual **bool** [get_IsMergedCell](./get_ismergedcell/)() | Zwraca true, jeśli komórka jest połączona z dowolną dopasowaną komórką, w przeciwnym razie false. Tylko do odczytu **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Zwraca dolny margines w [TextFrame](../textframe/). Odczyt **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Zwraca lewy margines w [TextFrame](../textframe/). Odczyt **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Zwraca prawy margines w [TextFrame](../textframe/). Odczyt **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Zwraca górny margines w [TextFrame](../textframe/). Odczyt **double**. |
| virtual **double** [get_MinimalHeight](./get_minimalheight/)() | Zwraca minimalną wysokość komórki. Jest to suma minimalnych wysokości wszystkich wierszy obejmowanych przez komórkę. Tylko do odczytu **double**. |
| virtual **double** [get_OffsetX](./get_offsetx/)() | Zwraca odległość od lewej krawędzi tabeli do lewej krawędzi komórki. Tylko do odczytu **double**. |
| virtual **double** [get_OffsetY](./get_offsety/)() | Zwraca odległość od górnej krawędzi tabeli do górnej krawędzi komórki. Tylko do odczytu **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Zwraca prezentację. Tylko do odczytu [IPresentation](../ipresentation/). |
| virtual **int32_t** [get_RowSpan](./get_rowspan/)() | Zwraca liczbę wierszy, które zajmuje połączona komórka. Jest to używane w połączeniu z atrybutem vMerge innych komórek w celu określenia komórki początkowej poziomego połączenia. Tylko do odczytu **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Zwraca slajd bazowy. Tylko do odczytu [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() | Zwraca nadrzędny obiekt [Table](../table/) dla komórki. Tylko do odczytu [ITable](../itable/). |
| virtual [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() | Zwraca typ zakotwiczenia tekstu. Odczyt [Slides::TextAnchorType](../textanchortype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() | Zwraca ramkę tekstową komórki. Tylko do odczytu [ITextFrame](../itextframe/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Zwraca typ pionowego tekstu. Odczyt [Slides::TextVerticalType](../textverticaltype/). |
| virtual **double** [get_Width](./get_width/)() | Zwraca szerokość komórki. Tylko do odczytu **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartości z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| virtual void [set_AnchorCenter](./set_anchorcenter/)(**bool**) | Określa, czy pole tekstowe jest wyśrodkowane w komórce. Zapis **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Ustawia dolny margines w [TextFrame](../textframe/). Zapis **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Ustawia lewy margines w [TextFrame](../textframe/). Zapis **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Ustawia prawy margines w [TextFrame](../textframe/). Zapis **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Ustawia górny margines w [TextFrame](../textframe/). Zapis **double**. |
| virtual void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) | Ustawia typ zakotwiczenia tekstu. Zapis [Slides::TextAnchorType](../textanchortype/). |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Ustawia typ pionowego tekstu. Zapis [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual void [SplitByColSpan](./splitbycolspan/)(**int32_t**) | Dzieli komórkę na dwie komórki według indeksu kolumny. |
| virtual void [SplitByHeight](./splitbyheight/)(**double**) | Dzieli komórkę według wysokości. |
| virtual void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) | Dzieli komórkę na dwie komórki według indeksu wiersza. |
| virtual void [SplitByWidth](./splitbywidth/)(**double**) | Dzieli komórkę według szerokości. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowywanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [ISlideComponent](../islidecomponent/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)