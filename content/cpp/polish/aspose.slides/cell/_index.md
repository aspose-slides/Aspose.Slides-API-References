---
title: Cell
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Reprezentuje komórkę tabeli.
type: docs
weight: 300
url: /pl/aspose.slides/cell/
---
## Cell klasa

Reprezentuje komórkę tabeli.

```cpp
class Cell : public Aspose::Slides::IDOMObject,
             public Aspose::Slides::ICell
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że według IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że według IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do wewnętrznych celów. |
| **bool** [get_AnchorCenter](./get_anchorcenter/)() override | Określa, czy pole tekstowe jest wyśrodkowane wewnątrz komórki. Odczyt **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() override | Zwraca obiekt [CellFormat](../cellformat/), który zawiera właściwości formatowania dla tej komórki. Tylko do odczytu [ICellFormat](../icellformat/). |
| **int32_t** [get_ColSpan](./get_colspan/)() override | Zwraca liczbę kolumn siatki w nadrzędnej tabeli, które mają być objęte bieżącą komórką. Ta właściwość pozwala komórkom wyglądać na połączone, ponieważ obejmują pionowe granice innych komórek w tabeli. Tylko do odczytu **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() override | Pobiera pierwszą kolumnę komórki. Tylko do odczytu [IColumn](../icolumn/). |
| **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() override | Zwraca indeks pierwszej kolumny objętej komórką. Tylko do odczytu **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() override | Pobiera pierwszy wiersz komórki. Tylko do odczytu [IRow](../irow/). |
| **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() override | Zwraca indeks pierwszego wiersza objętego komórką. Tylko do odczytu **int32_t**. |
| **double** [get_Height](./get_height/)() override | Zwraca wysokość komórki. Tylko do odczytu **double**. |
| **bool** [get_IsMergedCell](./get_ismergedcell/)() override | Zwraca true, jeśli komórka jest połączona z jakąkolwiek dopasowaną komórką, w przeciwnym razie false. Tylko do odczytu **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Zwraca dolny margines w [TextFrame](../textframe/). Odczyt **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Zwraca lewy margines w [TextFrame](../textframe/). Odczyt **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Zwraca prawy margines w [TextFrame](../textframe/). Odczyt **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Zwraca górny margines w [TextFrame](../textframe/). Odczyt **double**. |
| **double** [get_MinimalHeight](./get_minimalheight/)() override | Zwraca minimalną wysokość komórki. Jest to suma minimalnych wysokości wszystkich wierszy objętych komórką. Tylko do odczytu **double**. |
| **double** [get_OffsetX](./get_offsetx/)() override | Zwraca odległość od lewej krawędzi tabeli do lewej krawędzi komórki. Tylko do odczytu **double**. |
| **double** [get_OffsetY](./get_offsety/)() override | Zwraca odległość od górnej krawędzi tabeli do górnej krawędzi komórki. Tylko do odczytu **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | Zwraca prezentację nadrzędną komórki. Tylko do odczytu [IPresentation](../ipresentation/). |
| **int32_t** [get_RowSpan](./get_rowspan/)() override | Zwraca liczbę wierszy, które zajmuje połączona komórka. Używane jest w połączeniu z atrybutem vMerge w innych komórkach w celu określenia komórki początkowej poziomego łączenia. Tylko do odczytu **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | Zwraca slajd nadrzędny komórki. Tylko do odczytu [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() override | Zwraca obiekt [Table](../table/) nadrzędny dla komórki. Tylko do odczytu [ITable](../itable/). |
| [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() override | Zwraca typ kotwicy tekstu. Odczyt [Slides::TextAnchorType](../textanchortype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | Zwraca ramkę tekstową komórki. Tylko do odczytu [ITextFrame](../itextframe/). |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Zwraca typ pionowego tekstu. Odczyt [Slides::TextVerticalType](../textverticaltype/). |
| **double** [get_Width](./get_width/)() override | Zwraca szerokość komórki. Tylko do odczytu **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje działanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje obiekt typu wartościowego z nullptr przez referencję. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_AnchorCenter](./set_anchorcenter/)(**bool**) override | Określa, czy pole tekstowe jest wyśrodkowane wewnątrz komórki. Zapis **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Ustawia dolny margines w [TextFrame](../textframe/). Zapis **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Ustawia lewy margines w [TextFrame](../textframe/). Zapis **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Ustawia prawy margines w [TextFrame](../textframe/). Zapis **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Ustawia górny margines w [TextFrame](../textframe/). Zapis **double**. |
| void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) override | Ustawia typ kotwicy tekstu. Zapis [Slides::TextAnchorType](../textanchortype/). |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Ustawia typ pionowego tekstu. Zapis [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [SplitByColSpan](./splitbycolspan/)(**int32_t**) override | Dzieli komórkę na dwie komórki według indeksu kolumny. |
| void [SplitByHeight](./splitbyheight/)(**double**) override | Dzieli komórkę według wysokości. |
| void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) override | Dzieli komórkę na dwie komórki według indeksu wiersza. |
| void [SplitByWidth](./splitbywidth/)(**double**) override | Dzieli komórkę według szerokości. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do łańcucha znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [IDOMObject](../idomobject/)
* Klasa [ICell](../icell/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)