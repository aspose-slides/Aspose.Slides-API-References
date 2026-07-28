---
title: Table
second_title: Aspose.Slides dla C++ - referencja API
description: Reprezentuje tabelę na slajdzie.
type: docs
weight: 5409
url: /pl/aspose.slides/table/
---
## Table klasa

Represents a table on a slide.

```cpp
class Table : public Aspose::Slides::GraphicalObject,
              public Aspose::Slides::ITable
```

## Metody

| Metoda | Opis |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Dodaje nowy placeholder, jeśli go nie ma, i ustawia właściwości placeholdera na określony. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Zwraca tekst alternatywny powiązany z obiektem. Czytaj [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Zwraca tytuł tekstu alternatywnego powiązanego z obiektem. Czytaj [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Właściwość określa, jak obiekt będzie renderowany w trybie czarno-białym. Czytaj [Slides::BlackWhiteMode](../blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_Column](./get_column/)(**int32_t**) override | Zwraca kolumnę o podanym indeksie. Tylko do odczytu [Aspose::Slides::IColumn](../icolumn/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumnCollection](../icolumncollection/)\> [get_Columns](./get_columns/)() override | Zwraca zbiór kolumn. Tylko do odczytu [IColumnCollection](../icolumncollection/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Zwraca liczbę punktów połączeń na obiekcie. Tylko do odczytu **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Zwraca niestandardowe dane obiektu. Tylko do odczytu [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Zwraca obiekt [EffectFormat](../effectformat/), który zawiera efekty pikselowe zastosowane do obiektu. Uwaga: może zwrócić null dla pewnych typów obiektów, które nie mają właściwości efektów. Tylko do odczytu [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | Zwraca obiekt [TableFormat::get_FillFormat](../tableformat/get_fillformat/) zawierający formatowanie wypełnienia dla [Table](./). Tylko do odczytu [IFillFormat](../ifillformat/). |
| **bool** [get_FirstCol](./get_firstcol/)() override | Określa, czy pierwsza kolumna tabeli ma być rysowana ze specjalnym formatowaniem. Czytaj **bool**. |
| **bool** [get_FirstRow](./get_firstrow/)() override | Określa, czy pierwszy wiersz tabeli ma być rysowany ze specjalnym formatowaniem. Czytaj **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Zwraca właściwości ramki obiektu. Czytaj [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | Zwraca blokady obiektu. Tylko do odczytu [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | Zwraca wysokość obiektu, mierzoną w punktach. Czytaj **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Określa, czy obiekt jest ukryty. Czytaj **bool**. |
| **bool** [get_HorizontalBanding](./get_horizontalbanding/)() override | Określa, czy parzyste wiersze mają być rysowane z innym formatowaniem. Czytaj **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Zwraca hiperłącze zdefiniowane dla kliknięcia myszy. Czytaj [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Zwraca menedżera hiperłączy. Tylko do odczytu [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Zwraca hiperłącze zdefiniowane dla najechania myszy. Czytaj [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Określa opcję 'Mark as decorative'. Odczyt/zapis **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Określa, czy obiekt jest grupowany. Tylko do odczytu **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Określa, czy obiekt jest TextHolder_PPT. Tylko do odczytu **bool**. |
| **bool** [get_LastCol](./get_lastcol/)() override | Określa, czy ostatnia kolumna tabeli ma być rysowana ze specjalnym formatowaniem. Czytaj **bool**. |
| **bool** [get_LastRow](./get_lastrow/)() override | Określa, czy ostatni wiersz tabeli ma być rysowany ze specjalnym formatowaniem. Czytaj **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Zwraca obiekt [LineFormat](../lineformat/) zawierający właściwości formatowania linii dla obiektu. Uwaga: może zwrócić null dla niektórych typów obiektów, które nie mają właściwości linii. Tylko do odczytu [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Zwraca nazwę obiektu. Nie może być null. W razie potrzeby użyj pustego ciągu. Czytaj [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Zwraca unikalny identyfikator w zakresie slajdu, który pozostaje stały przez cały czas życia obiektu i pozwala PowerPointowi lub kodowi interop niezawodnie odwoływać się do obiektu z dowolnego miejsca w dokumencie. Tylko do odczytu **uint32_t**. Zobacz także [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Zwraca obiekt nadrzędny [GroupShape](../groupshape/), jeśli obiekt jest zgrupowany. W przeciwnym razie zwraca null. Tylko do odczytu [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Zwraca placeholder dla obiektu. Zwraca null, jeśli obiekt nie ma placeholdera. Tylko do odczytu [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Zwraca prezentację nadrzędną slajdu. Tylko do odczytu [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Zwraca surowe właściwości ramki obiektu. Czytaj [IShapeFrame](../ishapeframe/). |
| **bool** [get_RightToLeft](./get_righttoleft/)() override | Określa, czy tabela ma kolejność czytania od prawej do lewej. Czyta **bool**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | Zwraca liczbę stopni, o które określony obiekt jest obrócony wokół osi z. Dodatnia wartość oznacza obrót zgodnie z ruchem wskazówek zegara; ujemna wartość oznacza obrót przeciwny do ruchu wskazówek zegara. Czytaj **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_Row](./get_row/)(**int32_t**) override | Zwraca wiersz o podanym indeksie. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRowCollection](../irowcollection/)\> [get_Rows](./get_rows/)() override | Zwraca zbiór wierszy. Tylko do odczytu [IRowCollection](../irowcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Zwraca blokady obiektu. Tylko do odczytu [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Zwraca slajd nadrzędny obiektu. Tylko do odczytu [IBaseSlide](../ibaseslide/). |
| [TableStylePreset](../tablestylepreset/) [get_StylePreset](./get_stylepreset/)() override | Pobiera wbudowany styl tabeli. Czytaj [TableStylePreset](../tablestylepreset/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITableFormat](../itableformat/)\> [get_TableFormat](./get_tableformat/)() override | Zwraca obiekt [TableFormat](../tableformat/) zawierający właściwości formatowania tej tabeli. Tylko do odczytu [ITableFormat](../itableformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Zwraca obiekt [ThreeDFormat](../threedformat/) zawierający właściwości efektu 3D dla obiektu. Uwaga: może zwrócić null dla niektórych typów obiektów, które nie mają właściwości 3D. Tylko do odczytu [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Zwraca wewnętrzny identyfikator w zakresie prezentacji przeznaczony do użycia przez dodatki lub inny kod. Ponieważ wartość ta może być ponownie przypisana przez użytkownika lub programowo, nie należy jej traktować jako trwałego unikalnego klucza. Tylko do odczytu **uint32_t**. Zobacz także [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **bool** [get_VerticalBanding](./get_verticalbanding/)() override | Określa, czy parzyste kolumny mają być rysowane z innym formatowaniem. Czytaj **bool**. |
| **float** [get_Width](../shape/get_width/)() override | Zwraca szerokość obiektu, mierzoną w punktach. Czytaj **float**. |
| **float** [get_X](../shape/get_x/)() override | Zwraca współrzędną x lewego górnego rogu obiektu, mierzoną w punktach. Czytaj **float**. |
| **float** [get_Y](../shape/get_y/)() override | Zwraca współrzędną y lewego górnego rogu obiektu, mierzoną w punktach. Czytaj **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Zwraca pozycję obiektu w kolejności Z. Shapes[0] zwraca obiekt znajdujący się z tyłu kolejności Z, a Shapes[Shapes.Count - 1] zwraca obiekt znajdujący się z przodu kolejności Z. Tylko do odczytu **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Zwraca podstawowy kształt placeholder (kształt z układu i/lub slajdu-matki, z którego aktualny kształt jest dziedziczony). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Zwraca strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Zwraca miniaturkę obiektu. Domyślnie używany jest typ granic miniaturki [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Zwraca miniaturkę obiektu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Zwraca rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Zwraca wizualne granice obiektu obliczone na podstawie jego renderowanej treści. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) override | Zwraca komórkę o podanych indeksach kolumny i wiersza. Tylko do odczytu [Cell](../cell/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę statement lock() w C#. Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [MergeCells](./mergecells/)([System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, **bool**) override | Łączy sąsiednie komórki. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nie kopiuje nic, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nie kopiuje nic, tylko inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje obiekt typu wartościowego z nullptr poprzez referencję. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Definiuje, że ten obiekt nie jest placeholderem. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Ustawia tekst alternatywny powiązany z obiektem. Zapisz [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Ustawia tytuł tekstu alternatywnego powiązanego z obiektem. Zapisz [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Właściwość określa, jak obiekt będzie renderowany w trybie czarno-białym. Zapisz [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_FirstCol](./set_firstcol/)(**bool**) override | Określa, czy pierwsza kolumna tabeli ma być rysowana ze specjalnym formatowaniem. Zapisz **bool**. |
| void [set_FirstRow](./set_firstrow/)(**bool**) override | Określa, czy pierwszy wiersz tabeli ma być rysowany ze specjalnym formatowaniem. Zapisz **bool**. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ustawia właściwości ramki obiektu. Zapisz [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Ustawia wysokość obiektu, mierzoną w punktach. Zapisz **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Określa, czy obiekt jest ukryty. Zapisz **bool**. |
| void [set_HorizontalBanding](./set_horizontalbanding/)(**bool**) override | Określa, czy parzyste wiersze mają być rysowane z innym formatowaniem. Zapisz **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Ustawia hiperłącze zdefiniowane dla kliknięcia myszy. Zapisz [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Ustawia hiperłącze zdefiniowane dla najechania myszy. Zapisz [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Ustawia opcję 'Mark as decorative'. Odczyt/zapis **bool**. |
| void [set_LastCol](./set_lastcol/)(**bool**) override | Określa, czy ostatnia kolumna tabeli ma być rysowana ze specjalnym formatowaniem. Zapisz **bool**. |
| void [set_LastRow](./set_lastrow/)(**bool**) override | Określa, czy ostatni wiersz tabeli ma być rysowany ze specjalnym formatowaniem. Zapisz **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Ustawia nazwę obiektu. Nie może być null. W razie potrzeby użyj pustego ciągu. Zapisz [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ustawia surowe właściwości ramki obiektu. Zapisz [IShapeFrame](../ishapeframe/). |
| void [set_RightToLeft](./set_righttoleft/)(**bool**) override | Określa, czy tabela ma kolejność czytania od prawej do lewej. Zapisuje **bool**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Ustawia liczbę stopni, o które określony obiekt jest obrócony wokół osi z. Dodatnia wartość oznacza obrót zgodnie z ruchem wskazówek zegara; ujemna wartość oznacza obrót przeciwny do ruchu wskazówek zegara. Zapisz **float**. |
| void [set_StylePreset](./set_stylepreset/)([TableStylePreset](../tablestylepreset/)) override | Ustawia wbudowany styl tabeli. Zapisz [TableStylePreset](../tablestylepreset/). |
| void [set_VerticalBanding](./set_verticalbanding/)(**bool**) override | Określa, czy parzyste kolumny mają być rysowane z innym formatowaniem. Zapisz **bool**. |
| void [set_Width](../shape/set_width/)(**float**) override | Ustawia szerokość obiektu, mierzoną w punktach. Zapisz **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Ustawia współrzędną x lewego górnego rogu obiektu, mierzoną w punktach. Zapisz **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Ustawia współrzędną y lewego górnego rogu obiektu, mierzoną w punktach. Zapisz **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\>) override | Ustawia zdefiniowane właściwości formatu części na wszystkie części komórek tabeli. |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormat](../iparagraphformat/)\>) override | Ustawia zdefiniowane właściwości formatu akapitu na wszystkie akapity komórek tabeli. |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormat](../itextframeformat/)\>) override | Ustawia zdefiniowane właściwości formatu ramki tekstowej na wszystkie ramki tekstowe komórek tabeli. |
| int [SharedCount](../../system/object/sharedcount/)() const | Zwraca bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie własnych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie statementu lock() w C#. Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Zapisuje zawartość [Shape](../shape/) jako plik SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Zapisuje zawartość [Shape](../shape/) jako plik SVG. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [GraphicalObject](../graphicalobject/)
* Klasa [ITable](../itable/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)