---
title: ISectionZoomFrame
second_title: Aspose.Slides dla C++ - odniesienie API
description: Reprezentuje obiekt Section Zoom na slajdzie.
type: docs
weight: 3602
url: /pl/aspose.slides/isectionzoomframe/
---
## ISectionZoomFrame klasa


Reprezentuje obiekt Zoom [Section](../section/) na slajdzie.

```cpp
class ISectionZoomFrame : public virtual Aspose::Slides::IZoomObject
```

## Metody

| Metoda | Opis |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Dodaje nowy placeholder, jeśli go nie ma, i ustawia właściwości placeholdera na określony. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Zwraca tekst alternatywny powiązany z kształtem. Zobacz [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Zwraca tytuł tekstu alternatywnego powiązanego z kształtem. Zobacz [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym. Zobacz [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Zwraca liczbę punktów połączeń na kształcie. Tylko do odczytu **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Zwraca własne dane kształtu. Tylko do odczytu [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Zwraca obiekt [EffectFormat](../effectformat/), który zawiera efekty pikselowe zastosowane do kształtu. Tylko do odczytu [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Zwraca obiekt [FillFormat](../fillformat/), który zawiera właściwości formatowania wypełnienia dla kształtu. Tylko do odczytu [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Zwraca właściwości ramki kształtu. Zobacz [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | Zwraca blokady kształtu. Tylko do odczytu [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Pobiera wysokość kształtu, wyrażoną w punktach. Odczyt **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Określa, czy kształt jest ukryty. Odczyt **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Zwraca hiperłącze zdefiniowane dla kliknięcia myszy. Zobacz [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Menedżer hiperłączy. Tylko do odczytu [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Zwraca hiperłącze zdefiniowane dla najechania myszą. Zobacz [IHyperlink](../ihyperlink/). |
| virtual [ZoomImageType](../zoomimagetype/) [get_ImageType](../izoomobject/get_imagetype/)() | Pobiera typ obrazu obiektu zoom. Zobacz [ZoomImageType](../zoomimagetype/). Domyślna wartość: Preview |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Pobiera opcję 'Mark as decorative'. Odczyt/zapis **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Określa, czy kształt jest grupowany. Tylko do odczytu **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Określa, czy kształt jest TextHolder. Tylko do odczytu **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Zwraca obiekt [LineFormat](../lineformat/), który zawiera właściwości formatowania linii dla kształtu. Tylko do odczytu [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Zwraca nazwę kształtu. Zobacz [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Zwraca unikalny identyfikator w zakresie slajdu, który pozostaje stały przez cały czas życia kształtu i umożliwia PowerPointowi lub kodowi interop niezawodne odwoływanie się do kształtu z dowolnego miejsca w dokumencie. Tylko do odczytu **uint32_t**. Zobacz także [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Zwraca obiekt rodzica [GroupShape](../groupshape/), jeśli kształt jest grupowany. W przeciwnym razie zwraca null. Tylko do odczytu [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Zwraca placeholder dla kształtu. Tylko do odczytu [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Zwraca prezentację. Tylko do odczytu [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Zwraca surowe właściwości ramki kształtu. Zobacz [IShapeFrame](../ishapeframe/). |
| virtual **bool** [get_ReturnToParent](../izoomobject/get_returntoparent/)() | Pobiera zachowanie nawigacji w pokazie slajdów. Odczyt **bool**. Domyślna wartość: false |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Zwraca liczbę stopni, o które dany kształt jest obrócony wokół osi z. Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna oznacza obrót przeciwny do ruchu wskazówek zegara. Odczyt **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Zwraca blokady kształtu. Tylko do odczytu [IBaseShapeLock](../ibaseshapelock/). |
| virtual **bool** [get_ShowBackground](../izoomobject/get_showbackground/)() | Pobiera wartość określającą, czy Zoom użyje tła docelowego slajdu. Odczyt **bool**. Domyślna wartość: true |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Zwraca slajd bazowy. Tylko do odczytu [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_TargetSection](./get_targetsection/)() | Pobiera obiekt sekcji, do której powiązany jest obiekt Zoom [Section](../section/). Zobacz [ISection](../isection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Zwraca obiekt [ThreeDFormat](../threedformat/), który zawiera właściwości formatowania linii dla kształtu. Tylko do odczytu [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TransitionDuration](../izoomobject/get_transitionduration/)() | Pobiera czas trwania przejścia między Zoom a slajdem. Odczyt **float**. Domyślna wartość: 1.0f |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Zwraca wewnętrzny identyfikator w zakresie prezentacji przeznaczony do użycia przez dodatki lub inny kod. Ponieważ wartość tę może ponownie przypisać użytkownik lub programowo, nie należy traktować jej jako trwały unikalny klucz. Tylko do odczytu **uint32_t**. Zobacz także [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | Pobiera szerokość kształtu, wyrażoną w punktach. Odczyt **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Pobiera współrzędną x lewego górnego rogu kształtu, wyrażoną w punktach. Odczyt **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Pobiera współrzędną y lewego górnego rogu kształtu, wyrażoną w punktach. Odczyt **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../izoomobject/get_zoomimage/)() | Pobiera obraz dla obiektu zoom. Zobacz [IPPImage](../ippimage/). |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Zwraca pozycję kształtu w kolejności Z. Shapes[0] zwraca kształt z tyłu kolejności Z, a Shapes[Shapes.Count - 1] zwraca kształt z przodu kolejności Z. Tylko do odczytu **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Zwraca podstawowy kształt placeholder (kształt z układu i/lub slajdu głównego, z którego dziedziczony jest bieżący kształt). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Zwraca miniaturę kształtu. Domyślnie używany jest typ [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) ograniczenia miniatury kształtu. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Zwraca miniaturę kształtu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i pozwala na kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i pozwala na kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku stringów. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o określoną wartość. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Określa, że ten kształt nie jest placeholderem. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Ustawia tekst alternatywny powiązany z kształtem. Zapis [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Ustawia tytuł tekstu alternatywnego powiązanego z kształtem. Zapis [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym. Zapis [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Ustawia właściwości ramki kształtu. Zapis [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Ustawia wysokość kształtu, wyrażoną w punktach. Zapis **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Ustawia, czy kształt jest ukryty. Zapis **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Ustawia hiperłącze zdefiniowane dla kliknięcia myszy. Zapis [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Ustawia hiperłącze zdefiniowane dla najechania myszą. Zapis [IHyperlink](../ihyperlink/). |
| virtual void [set_ImageType](../izoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) | Ustawia typ obrazu obiektu zoom. Zapis [ZoomImageType](../zoomimagetype/). Domyślna wartość: Preview |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Ustawia opcję 'Mark as decorative'. Zapis/odczyt **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Ustawia nazwę kształtu. Zapis [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Ustawia surowe właściwości ramki kształtu. Zapis [IShapeFrame](../ishapeframe/). |
| virtual void [set_ReturnToParent](../izoomobject/set_returntoparent/)(**bool**) | Ustawia zachowanie nawigacji w pokazie slajdów. Zapis **bool**. Domyślna wartość: false |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Ustawia liczbę stopni, o które dany kształt jest obrócony wokół osi z. Pozytywna wartość oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna oznacza obrót przeciwny. Zapis **float**. |
| virtual void [set_ShowBackground](../izoomobject/set_showbackground/)(**bool**) | Ustawia wartość określającą, czy Zoom użyje tła docelowego slajdu. Zapis **bool**. Domyślna wartość: true |
| virtual void [set_TargetSection](./set_targetsection/)([System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) | Ustawia obiekt sekcji, do którego powiązany jest obiekt Zoom [Section](../section/). Zapis [ISection](../isection/). |
| virtual void [set_TransitionDuration](../izoomobject/set_transitionduration/)(**float**) | Ustawia czas trwania przejścia między Zoom a slajdem. Zapis **float**. Domyślna wartość: 1.0f |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Ustawia szerokość kształtu, wyrażoną w punktach. Zapis **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Ustawia współrzędną x lewego górnego rogu kształtu, wyrażoną w punktach. Zapis **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Ustawia współrzędną y lewego górnego rogu kształtu, wyrażoną w punktach. Zapis **float**. |
| virtual void [set_ZoomImage](../izoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) | Ustawia obraz dla obiektu zoom. Zapis [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustaw n-arg szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala na zmianę wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwertowanie własnych obiektów na ciąg znaków. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Zapisuje zawartość [Shape](../shape/) jako plik SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Zapisuje zawartość [Shape](../shape/) jako plik SVG. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [IZoomObject](../izoomobject/)
* Przestrzeń nazw [Aspose::Slides](../)
* Biblioteka [Aspose.Slides](../../)