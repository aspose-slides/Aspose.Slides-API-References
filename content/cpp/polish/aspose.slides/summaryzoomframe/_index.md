---
title: SummaryZoomFrame
second_title: Aspose.Slides dla C++ – odniesienie API
description: Reprezentuje obiekt Summary Zoom na slajdzie.
type: docs
weight: 5318
url: /pl/aspose.slides/summaryzoomframe/
---
## SummaryZoomFrame klasa

Reprezentuje obiekt Summary Zoom na slajdzie.

```cpp
class SummaryZoomFrame : public Aspose::Slides::GraphicalObject,
                         public Aspose::Slides::ISummaryZoomFrame
```

## Metody

| Metoda | Opis |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Dodaje nowy placeholder, jeśli go nie ma, i ustawia właściwości placeholdera na określony. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Zwraca alternatywny tekst powiązany z kształtem. Zobacz [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Zwraca tytuł alternatywnego tekstu powiązanego z kształtem. Zobacz [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym. Zobacz [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Zwraca liczbę punktów połączeń na kształcie. Tylko do odczytu **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Zwraca niestandardowe dane kształtu. Tylko do odczytu [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Zwraca obiekt [EffectFormat](../effectformat/), który zawiera efekty pikselowe zastosowane do kształtu. Uwaga: może zwrócić null dla niektórych rodzajów kształtów, które nie mają właściwości efektu. Tylko do odczytu [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Zwraca obiekt [FillFormat](../fillformat/), który zawiera właściwości formatowania wypełnienia dla kształtu. Uwaga: może zwrócić null dla niektórych rodzajów kształtów, które nie mają właściwości wypełnienia. Tylko do odczytu [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Zwraca właściwości ramki kształtu. Zobacz [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | Zwraca blokady kształtu. Tylko do odczytu [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | Pobiera wysokość kształtu, mierzoną w punktach. Odczytaj **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Określa, czy kształt jest ukryty. Odczytaj **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Zwraca hiperłącze zdefiniowane dla kliknięcia myszy. Zobacz [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Zwraca menedżera hiperłączy. Tylko do odczytu [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Zwraca hiperłącze zdefiniowane dla najechania myszą. Zobacz [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Pobiera opcję 'Mark as decorative'. Odczyt/zapis **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Określa, czy kształt jest pogrupowany. Tylko do odczytu **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Określa, czy kształt jest TextHolder_PPT. Tylko do odczytu **bool**. |
| [ZoomLayout](../zoomlayout/) [get_Layout](./get_layout/)() override | Pobiera układ sekcji Summary Zoom w ramce. Wartość domyślna to GridLayout. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Zwraca obiekt [LineFormat](../lineformat/), który zawiera właściwości formatowania linii dla kształtu. Uwaga: może zwrócić null dla niektórych rodzajów kształtów, które nie mają właściwości linii. Tylko do odczytu [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Zwraca nazwę kształtu. Nie może być nullem. Użyj pustego stringa, jeśli to konieczne. Zobacz [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Zwraca unikalny identyfikator o zakresie slajdu, który pozostaje stały przez cały czas życia kształtu i pozwala PowerPointowi lub kodowi interop niezawodnie odwoływać się do kształtu z dowolnego miejsca w dokumencie. Tylko do odczytu **uint32_t**. Zobacz także [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Zwraca obiekt rodzica [GroupShape](../groupshape/), jeśli kształt jest pogrupowany. W przeciwnym razie zwraca null. Tylko do odczytu [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Zwraca placeholder dla kształtu. Zwraca null, jeśli kształt nie ma placeholdera. Tylko do odczytu [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Zwraca prezentację nadrzędną slajdu. Tylko do odczytu [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Zwraca surowe właściwości ramki kształtu. Zobacz [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](../shape/get_rotation/)() override | Zwraca liczbę stopni, o które określony kształt jest obrócony wokół osi z. Dodatnia wartość oznacza obrót zgodny z ruchem wskazówek zegara; ujemna wartość oznacza obrót przeciwny do ruchu wskazówek zegara. Odczytaj **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Zwraca blokady kształtu. Tylko do odczytu [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Zwraca slajd nadrzędny kształtu. Tylko do odczytu [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISummaryZoomSectionCollection](../isummaryzoomsectioncollection/)\> [get_SummaryZoomCollection](./get_summaryzoomcollection/)() override | Pobiera [ISummaryZoomSectionCollection](../isummaryzoomsectioncollection/) dla obiektu Summary Zoom Frame. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISummaryZoomSection](../isummaryzoomsection/)\> [get_SummaryZoomSection](./get_summaryzoomsection/)(**int32_t**) override | Zwraca obiekt Summary Zoom [Section](../section/) w slajdzie pod wskazanym indeksem. Tylko do odczytu [Aspose::Slides::ISummaryZoomSection](../isummaryzoomsection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Zwraca obiekt [ThreeDFormat](../threedformat/) zawierający właściwości efektu 3D dla kształtu. Uwaga: może zwrócić null dla niektórych rodzajów kształtów, które nie mają właściwości 3D. Tylko do odczytu [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Zwraca wewnętrzny, o zakresie prezentacji, identyfikator przeznaczony do użycia przez dodatki lub inny kod. Ponieważ wartość ta może być ponownie przypisana przez użytkownika lub programowo, nie powinna być traktowana jako trwały unikalny klucz. Tylko do odczytu **uint32_t**. Zobacz także [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | Pobiera szerokość kształtu, mierzoną w punktach. Odczytaj **float**. |
| **float** [get_X](../shape/get_x/)() override | Pobiera współrzędną x lewego górnego rogu kształtu, mierzoną w punktach. Odczytaj **float**. |
| **float** [get_Y](../shape/get_y/)() override | Pobiera współrzędną y lewego górnego rogu kształtu, mierzoną w punktach. Odczytaj **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Zwraca pozycję kształtu w kolejności Z. Shapes[0] zwraca kształt znajdujący się z tyłu kolejności Z, a Shapes[Shapes.Count - 1] zwraca kształt znajdujący się z przodu kolejności Z. Tylko do odczytu **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Zwraca podstawowy kształt placeholdera (kształt z układu i/lub slajdu master, z którego dziedziczy bieżący kształt). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie niestandardowych obiektów. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Zwraca miniaturę kształtu. Typ [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) granic miniatury kształtu jest używany domyślnie. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Zwraca miniaturę kształtu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt reprezentuje instancję typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie niestandardowych typów. |
| [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Definiuje, że ten kształt nie jest placeholderem. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Ustawia alternatywny tekst powiązany z kształtem. Zapisz [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Ustawia tytuł alternatywnego tekstu powiązanego z kształtem. Zapisz [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym. Zapisz [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ustawia właściwości ramki kształtu. Zapisz [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Ustawia wysokość kształtu, mierzoną w punktach. Zapisz **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Ustawia, czy kształt jest ukryty. Zapisz **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Ustawia hiperłącze zdefiniowane dla kliknięcia myszy. Zapisz [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Ustawia hiperłącze zdefiniowane dla najechania myszą. Zapisz [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Ustawia opcję 'Mark as decorative'. Odczyt/zapis **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Ustawia nazwę kształtu. Nie może być nullem. Użyj pustego stringa, jeśli to konieczne. Zapisz [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ustawia surowe właściwości ramki kształtu. Zapisz [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi z. Dodatnia wartość oznacza obrót zgodny z ruchem wskazówek zegara; ujemna wartość oznacza obrót przeciwny do ruchu wskazówek zegara. Zapisz **float**. |
| void [set_Width](../shape/set_width/)(**float**) override | Ustawia szerokość kształtu, mierzoną w punktach. Zapisz **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Ustawia współrzędną x lewego górnego rogu kształtu, mierzoną w punktach. Zapisz **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Ustawia współrzędną y lewego górnego rogu kształtu, mierzoną w punktach. Zapisz **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Inkrementuje współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Dekrementuje i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję niestandardowych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowywanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Inkrementuje słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Dekrementuje słaby licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Zapisuje zawartość [Shape](../shape/) jako plik SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Zapisuje zawartość [Shape](../shape/) jako plik SVG. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [GraphicalObject](../graphicalobject/)
* Klasa [ISummaryZoomFrame](../isummaryzoomframe/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)