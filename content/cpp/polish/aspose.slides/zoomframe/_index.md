---
title: ZoomFrame
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Reprezentuje obiekt Zoom slajdu w slajdzie.
type: docs
weight: 5578
url: /pl/aspose.slides/zoomframe/
---
## ZoomFrame klasa

Reprezentuje obiekt [Slide](../slide/) Zoom w slajdzie.

```cpp
class ZoomFrame : public Aspose::Slides::ZoomObject,
                  public Aspose::Slides::IZoomFrame
```

## Metody

| Metoda | Opis |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Dodaje nowy symbol zastępczy, jeśli go nie ma, i ustawia właściwości symbolu zastępczego na określony. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Zwraca tekst alternatywny powiązany z kształtem. Zobacz [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Zwraca tytuł tekstu alternatywnego powiązanego z kształtem. Zobacz [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym. Zobacz [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Zwraca liczbę punktów połączeń na kształcie. Tylko do odczytu **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Zwraca niestandardowe dane kształtu. Tylko do odczytu [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Zwraca obiekt [EffectFormat](../effectformat/), który zawiera efekty pikselowe zastosowane do kształtu. Uwaga: może zwrócić null dla niektórych rodzajów kształtów, które nie mają właściwości efektu. Tylko odczyt [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Zwraca obiekt [FillFormat](../fillformat/), który zawiera właściwości formatowania wypełnienia dla kształtu. Uwaga: może zwrócić null dla niektórych rodzajów kształtów, które nie mają właściwości wypełnienia. Tylko odczyt [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Zwraca właściwości ramki kształtu. Zobacz [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | Zwraca blokady kształtu. Tylko odczyt [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | Pobiera wysokość kształtu, mierzoną w punktach. Tylko odczyt **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Określa, czy kształt jest ukryty. Tylko odczyt **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Zwraca hiperłącze zdefiniowane dla kliknięcia myszy. Zobacz [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Zwraca menedżer hiperłączy. Tylko odczyt [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Zwraca hiperłącze zdefiniowane dla najechania myszy. Zobacz [IHyperlink](../ihyperlink/). |
| [ZoomImageType](../zoomimagetype/) [get_ImageType](../zoomobject/get_imagetype/)() override | Pobiera typ obrazu obiektu zoom. Zobacz [ZoomImageType](../zoomimagetype/). Domyślna wartość: Preview |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Pobiera opcję 'Mark as decorative'. Odczyt/zapis **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Określa, czy kształt jest grupowany. Tylko odczyt **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Określa, czy kształt jest TextHolder_PPT. Tylko odczyt **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Zwraca obiekt [LineFormat](../lineformat/), który zawiera właściwości formatowania linii dla kształtu. Uwaga: może zwrócić null dla niektórych rodzajów kształtów, które nie mają właściwości linii. Tylko odczyt [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Zwraca nazwę kształtu. Nie może być null. W razie potrzeby użyj pustego ciągu. Zobacz [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Zwraca unikalny identyfikator związany ze slajdem, który pozostaje stały przez cały okres życia kształtu i pozwala PowerPointowi lub kodowi interop na niezawodne odwoływanie się do kształtu z dowolnego miejsca w dokumencie. Tylko odczyt **uint32_t**. Zobacz także [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Zwraca obiekt rodzica [GroupShape](../groupshape/), jeśli kształt jest grupowany. W przeciwnym razie zwraca null. Tylko odczyt [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Zwraca placeholder dla kształtu. Zwraca null, jeśli kształt nie ma placeholdera. Tylko odczyt [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Zwraca prezentację nadrzędną slajdu. Tylko odczyt [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Zwraca surowe właściwości ramki kształtu. Zobacz [IShapeFrame](../ishapeframe/). |
| **bool** [get_ReturnToParent](../zoomobject/get_returntoparent/)() override | Pobiera zachowanie nawigacji w pokazie slajdów. Tylko odczyt **bool**. Domyślna wartość: false |
| **float** [get_Rotation](../shape/get_rotation/)() override | Zwraca liczbę stopni, o którą określony kształt jest obrócony wokół osi z. Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna oznacza obrót przeciwny. Tylko odczyt **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Zwraca blokady kształtu. Tylko odczyt [IBaseShapeLock](../ibaseshapelock/). |
| **bool** [get_ShowBackground](../zoomobject/get_showbackground/)() override | Pobiera wartość określającą, czy Zoom użyje tła docelowego slajdu. Tylko odczyt **bool**. Domyślna wartość: true |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Zwraca slajd nadrzędny kształtu. Tylko odczyt [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() override | Pobiera obiekt slajdu, do którego odwołuje się obiekt Zoom [Slide](../slide/). Zobacz [ISlide](../islide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Zwraca obiekt [ThreeDFormat](../threedformat/), który zawiera właściwości efektu 3D dla kształtu. Uwaga: może zwrócić null dla niektórych rodzajów kształtów, które nie mają właściwości 3D. Tylko odczyt [IThreeDFormat](../ithreedformat/). |
| **float** [get_TransitionDuration](../zoomobject/get_transitionduration/)() override | Pobiera czas trwania przejścia między Zoom a slajdem. Tylko odczyt **float**. Domyślna wartość: 1.0f |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Zwraca wewnętrzny identyfikator związany z prezentacją, przeznaczony do użytku przez dodatki lub inny kod. Ponieważ wartość ta może być zmieniana przez użytkownika lub programowo, nie należy jej traktować jako trwały unikalny klucz. Tylko odczyt **uint32_t**. Zobacz także [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | Pobiera szerokość kształtu, mierzoną w punktach. Tylko odczyt **float**. |
| **float** [get_X](../shape/get_x/)() override | Pobiera współrzędną x lewego górnego rogu kształtu, mierzoną w punktach. Tylko odczyt **float**. |
| **float** [get_Y](../shape/get_y/)() override | Pobiera współrzędną y lewego górnego rogu kształtu, mierzoną w punktach. Tylko odczyt **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../zoomobject/get_zoomimage/)() override | Pobiera obraz dla obiektu zoom. Zobacz [IPPImage](../ippimage/). |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Zwraca pozycję kształtu w kolejności Z. Shapes[0] zwraca kształt na końcu kolejności Z, a Shapes[Shapes.Count - 1] zwraca kształt na początku kolejności Z. Tylko odczyt **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Zwraca podstawowy kształt placeholder (kształt z układu i/lub slajdu nadrzędnego, z którego dziedziczy bieżący kształt). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie niestandardowych obiektów. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Zwraca miniaturę kształtu. Domyślnie używany jest typ [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) granic miniatury kształtu. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Zwraca miniaturę kształtu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Pobiera wizualne granice kształtu obliczone z jego renderowanej zawartości. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu stróża [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie niestandardowych typów. |
| [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. W rzeczywistości nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty referencyjnie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty referencyjnie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Określa, że ten kształt nie jest placeholderem. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Ustawia tekst alternatywny powiązany z kształtem. Zapis [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Ustawia tytuł tekstu alternatywnego powiązanego z kształtem. Zapis [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym. Zapis [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ustawia właściwości ramki kształtu. Zapis [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Ustawia wysokość kształtu, mierzoną w punktach. Zapis **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Określa, czy kształt jest ukryty. Zapis **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Ustawia hiperłącze zdefiniowane dla kliknięcia myszy. Zapis [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Ustawia hiperłącze zdefiniowane dla najechania myszy. Zapis [IHyperlink](../ihyperlink/). |
| void [set_ImageType](../zoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) override | Ustawia typ obrazu obiektu zoom. Zapis [ZoomImageType](../zoomimagetype/). Domyślna wartość: Preview |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Ustawia opcję 'Mark as decorative'. Zapis/odczyt **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Ustawia nazwę kształtu. Nie może być null. W razie potrzeby użyj pustego ciągu. Zapis [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Ustawia surowe właściwości ramki kształtu. Zapis [IShapeFrame](../ishapeframe/). |
| void [set_ReturnToParent](../zoomobject/set_returntoparent/)(**bool**) override | Ustawia zachowanie nawigacji w pokazie slajdów. Zapis **bool**. Domyślna wartość: false |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi z. Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; ujemna - przeciwny. Zapis **float**. |
| void [set_ShowBackground](../zoomobject/set_showbackground/)(**bool**) override | Ustawia wartość określającą, czy Zoom użyje tła docelowego slajdu. Zapis **bool**. Domyślna wartość: true |
| void [set_TargetSlide](./set_targetslide/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | Ustawia obiekt slajdu, do którego odwołuje się obiekt Zoom [Slide](../slide/). Zapis [ISlide](../islide/). |
| void [set_TransitionDuration](../zoomobject/set_transitionduration/)(**float**) override | Ustawia czas trwania przejścia między Zoom a slajdem. Zapis **float**. Domyślna wartość: 1.0f |
| void [set_Width](../shape/set_width/)(**float**) override | Ustawia szerokość kształtu, mierzoną w punktach. Zapis **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Ustawia współrzędną x lewego górnego rogu kształtu, mierzoną w punktach. Zapis **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Ustawia współrzędną y lewego górnego rogu kształtu, mierzoną w punktach. Zapis **float**. |
| void [set_ZoomImage](../zoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | Ustawia obraz dla obiektu zoom. Zapis [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako weak pointer (zamiast shared). Umożliwia zmianę wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie niestandardowych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu stróża [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Zapisuje zawartość [Shape](../shape/) jako plik SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Zapisuje zawartość [Shape](../shape/) jako plik SVG. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [ZoomObject](../zoomobject/)
* Klasa [IZoomFrame](../izoomframe/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)