---
title: SectionZoomFrame
second_title: Aspose.Slides dla C++ – odniesienie API
description: Reprezentuje obiekt Section Zoom na slajdzie.
type: docs
weight: 5045
url: /pl/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame klasa

Reprezentuje obiekt [Section](../section/) Zoom na slajdzie.

```cpp
class SectionZoomFrame : public Aspose::Slides::ZoomObject,
                         public virtual Aspose::Slides::ISectionZoomFrame
```

## Metody

| Metoda | Opis |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Dodaje nowy placeholder, jeśli go nie ma, i ustawia właściwości placeholdera na określony. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włączając NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Zwraca tekst alternatywny powiązany z kształtem. Zobacz [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Zwraca tytuł tekstu alternatywnego powiązanego z kształtem. Zobacz [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Właśćność określa, jak kształt będzie renderowany w trybie czarno-białym. Zobacz [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Zwraca liczbę punktów połączeń na kształcie. Tylko do odczytu **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Zwraca niestandardowe dane kształtu. Tylko do odczytu [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Zwraca obiekt [EffectFormat](../effectformat/) zawierający efekty pikselowe zastosowane do kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają własności efektów. Tylko do odczytu [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Zwraca obiekt [FillFormat](../fillformat/) zawierający właściwości formatowania wypełnienia dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają własności wypełnienia. Tylko do odczytu [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Zwraca właściwości ramki kształtu. Zobacz [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | Zwraca blokady kształtu. Tylko do odczytu [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | Zwraca wysokość kształtu, mierzoną w punktach. Tylko do odczytu **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Określa, czy kształt jest ukryty. Tylko do odczytu **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Zwraca hiperlink zdefiniowany dla kliknięcia myszy. Zobacz [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Zwraca menedżer hiperlinków. Tylko do odczytu [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Zwraca hiperlink zdefiniowany dla najechania myszy. Zobacz [IHyperlink](../ihyperlink/). |
| [ZoomImageType](../zoomimagetype/) [get_ImageType](../zoomobject/get_imagetype/)() override | Pobiera typ obrazu obiektu zoom. Zobacz [ZoomImageType](../zoomimagetype/). Wartość domyślna: Preview |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Pobiera opcję „Mark as decorative”. Odczyt/zapis **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Określa, czy kształt jest grupowany. Tylko do odczytu **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Określa, czy kształt jest TextHolder_PPT. Tylko do odczytu **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Zwraca obiekt [LineFormat](../lineformat/) zawierający właściwości formatowania linii dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają własności linii. Tylko do odczytu [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Zwraca nazwę kształtu. Nie może być null. W razie potrzeby użyj pustego łańcucha. Zobacz [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Zwraca unikalny identyfikator skali slajdu, stały przez cały czas życia kształtu i umożliwiający programom PowerPoint lub interfejsowi odwoływanie się do kształtu z dowolnego miejsca dokumentu. Tylko do odczytu **uint32_t**. Zobacz także [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Zwraca obiekt nadrzędny [GroupShape](../groupshape/) jeśli kształt jest grupowany. W przeciwnym razie zwraca null. Tylko do odczytu [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Zwraca placeholder dla kształtu. Zwraca null, jeśli kształt nie ma placeholdera. Tylko do odczytu [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Zwraca prezentację nadrzędną slajdu. Tylko do odczytu [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Zwraca surowe właściwości ramki kształtu. Zobacz [IShapeFrame](../ishapeframe/). |
| **bool** [get_ReturnToParent](../zoomobject/get_returntoparent/)() override | Pobiera zachowanie nawigacji w pokazie slajdów. Tylko do odczytu **bool**. Wartość domyślna: false |
| **float** [get_Rotation](../shape/get_rotation/)() override | Zwraca liczbę stopni, o które określony kształt jest obrócony wokół osi z. Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna – przeciwny. Tylko do odczytu **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Zwraca blokady kształtu. Tylko do odczytu [IBaseShapeLock](../ibaseshapelock/). |
| **bool** [get_ShowBackground](../zoomobject/get_showbackground/)() override | Pobiera wartość określającą, czy Zoom użyje tła slajdu docelowego. Tylko do odczytu **bool**. Wartość domyślna: true |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Zwraca slajd nadrzędny kształtu. Tylko do odczytu [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_TargetSection](./get_targetsection/)() override | Pobiera obiekt sekcji, do której odwołuje się obiekt [Section](../section/) Zoom. Zobacz [ISection](../isection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Zwraca obiekt [ThreeDFormat](../threedformat/) zawierający własności efektu 3D dla kształtu. Uwaga: może zwrócić null dla niektórych typów kształtów, które nie mają własności 3D. Tylko do odczytu [IThreeDFormat](../ithreedformat/). |
| **float** [get_TransitionDuration](../zoomobject/get_transitionduration/)() override | Pobiera czas trwania przejścia między Zoom a slajdem. Tylko do odczytu **float**. Wartość domyślna: 1.0f |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Zwraca wewnętrzny identyfikator skali prezentacji przeznaczony do użytku przez dodatki lub inny kod. Ponieważ wartość tę może zmienić użytkownik lub programowo, nie należy jej traktować jako trwały unikalny klucz. Tylko do odczytu **uint32_t**. Zobacz także [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | Zwraca szerokość kształtu, mierzoną w punktach. Tylko do odczytu **float**. |
| **float** [get_X](../shape/get_x/)() override | Zwraca współrzędną x lewego górnego rogu kształtu, mierzoną w punktach. Tylko do odczytu **float**. |
| **float** [get_Y](../shape/get_y/)() override | Zwraca współrzędną y lewego górnego rogu kształtu, mierzoną w punktach. Tylko do odczytu **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../zoomobject/get_zoomimage/)() override | Pobiera obraz dla obiektu zoom. Zobacz [IPPImage](../ippimage/). |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Zwraca pozycję kształtu w kolejności Z. Shapes[0] zwraca kształt z tyłu kolejności Z, a Shapes[Shapes.Count - 1] zwraca kształt z przodu kolejności Z. Tylko do odczytu **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Zwraca podstawowy kształt placeholder (k shape z układu i/lub slajdu głównego, z którego dziedziczy bieżący kształt). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogiczna do metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie obiektów niestandardowych. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Zwraca miniaturkę kształtu. Domyślnie używany jest typ granic miniaturki [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Zwraca miniaturkę kształtu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analogiczna do wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Pobiera wizualne granice kształtu obliczone na podstawie jego renderowanej zawartości. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analogiczna do operatora C# „is”. |
| void [Lock](../../system/object/lock/)() | Implementuje działanie instrukcji C# lock() blokującej. Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna do metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie typów niestandardowych. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, naprawdę, jedynie inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, naprawdę, jedynie inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje obiekt typu wartościowego z nullptr przez referencję. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Definiuje, że ten kształt nie jest placeholderem. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Ustawia tekst alternatywny powiązany z kształtem. Zapisz [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Ustawia tytuł tekstu alternatywnego powiązanego z kształtem. Zapisz [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Właśćność określa, jak kształt będzie renderowany w trybie czarno-białym. Zapisz [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ustawia właściwości ramki kształtu. Zapisz [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Ustawia wysokość kształtu, mierzoną w punktach. Zapisz **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Określa, czy kształt jest ukryty. Zapisz **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Ustawia hiperlink zdefiniowany dla kliknięcia myszy. Zapisz [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Ustawia hiperlink zdefiniowany dla najechania myszy. Zapisz [IHyperlink](../ihyperlink/). |
| void [set_ImageType](../zoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) override | Ustawia typ obrazu obiektu zoom. Zapisz [ZoomImageType](../zoomimagetype/). Wartość domyślna: Preview |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Ustawia opcję „Mark as decorative”. Odczyt/zapis **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Ustawia nazwę kształtu. Nie może być null. W razie potrzeby użyj pustego łańcucha. Zapisz [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ustawia surowe właściwości ramki kształtu. Zapisz [IShapeFrame](../ishapeframe/). |
| void [set_ReturnToParent](../zoomobject/set_returntoparent/)(**bool**) override | Ustawia zachowanie nawigacji w pokazie slajdów. Zapisz **bool**. Wartość domyślna: false |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi z. Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna – przeciwny. Zapisz **float**. |
| void [set_ShowBackground](../zoomobject/set_showbackground/)(**bool**) override | Ustawia wartość określającą, czy Zoom użyje tła slajdu docelowego. Zapisz **bool**. Wartość domyślna: true |
| void [set_TargetSection](./set_targetsection/)([System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) override | Ustawia obiekt sekcji, do której odwołuje się obiekt [Section](../section/) Zoom. Zapisz [ISection](../isection/). |
| void [set_TransitionDuration](../zoomobject/set_transitionduration/)(**float**) override | Ustawia czas trwania przejścia między Zoom a slajdem. Zapisz **float**. Wartość domyślna: 1.0f |
| void [set_Width](../shape/set_width/)(**float**) override | Ustawia szerokość kształtu, mierzoną w punktach. Zapisz **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Ustawia współrzędną x lewego górnego rogu kształtu, mierzoną w punktach. Zapisz **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Ustawia współrzędną y lewego górnego rogu kształtu, mierzoną w punktach. Zapisz **float**. |
| void [set_ZoomImage](../zoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | Ustawia obraz dla obiektu zoom. Zapisz [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogiczna do metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję obiektów niestandardowych do łańcucha znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa słaby licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza słaby licznik referencji. Nie należy wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Zapisuje zawartość [Shape](../shape/) jako plik SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Zapisuje zawartość [Shape](../shape/) jako plik SVG. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [ZoomObject](../zoomobject/)
* Klasa [ISectionZoomFrame](../isectionzoomframe/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)