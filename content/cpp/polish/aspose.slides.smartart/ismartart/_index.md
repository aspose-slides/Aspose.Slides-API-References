---
title: ISmartArt
second_title: Aspose.Slides dla C++ – Odwołanie API
description: Reprezentuje diagram SmartArt.
type: docs
weight: 1
url: /pl/aspose.slides.smartart/ismartart/
---
## ISmartArt klasa

Represents a [SmartArt](../smartart/) diagram.

```cpp
class ISmartArt : public virtual Aspose::Slides::IGraphicalObject
```

## Metody

| Method | Opis |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | Dodaje nowy placeholder, jeśli nie istnieje, i ustawia właściwości placeholdera na określony. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_AllNodes](./get_allnodes/)() | Zwraca kolekcje wszystkich węzłów w obiekcie [SmartArt](../smartart/). Tylko do odczytu [ISmartArtNodeCollection](../ismartartnodecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | Zwraca tekst alternatywny powiązany z kształtem. Tylko do odczytu [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | Zwraca tytuł tekstu alternatywnego powiązanego z kształtem. Tylko do odczytu [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym. Tylko do odczytu [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual [SmartArtColorType](../smartartcolortype/) [get_ColorStyle](./get_colorstyle/)() | Zwraca lub ustawia styl koloru obiektu [SmartArt](../smartart/). Tylko do odczytu [SmartArtColorType](../smartartcolortype/). |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | Zwraca liczbę punktów połączenia na kształcie. Tylko do odczytu **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | Zwraca niestandardowe dane kształtu. Tylko do odczytu [ICustomData](../../aspose.slides/icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | Zwraca obiekt [EffectFormat](../../aspose.slides/effectformat/), który zawiera efekty pikseli stosowane do kształtu. Tylko do odczytu [IEffectFormat](../../aspose.slides/ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | Zwraca obiekt [FillFormat](../../aspose.slides/fillformat/), który zawiera właściwości formatowania wypełnienia dla kształtu. Tylko do odczytu [IFillFormat](../../aspose.slides/ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | Zwraca właściwości ramki kształtu. Tylko do odczytu [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/igraphicalobject/get_graphicalobjectlock/)() | Zwraca blokady kształtu. Tylko do odczytu [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/). |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | Pobiera wysokość kształtu, mierzona w punktach. Tylko do odczytu **float**. |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | Określa, czy kształt jest ukryty. Tylko do odczytu **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | Zwraca hiperłącze zdefiniowane dla kliknięcia myszą. Tylko do odczytu [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | Menedżer hiperłączy. Tylko do odczytu [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | Zwraca hiperłącze zdefiniowane dla najechania myszą. Tylko do odczytu [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | Pobiera opcję „Mark as decorative”. Odczyt/zapis **bool**. |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | Określa, czy kształt jest grupowany. Tylko do odczytu **bool**. |
| virtual **bool** [get_IsReversed](./get_isreversed/)() | Zwraca lub ustawia stan diagramu [SmartArt](../smartart/) względem (lewo-do-prawo) LTR lub (prawo-do-lewo) RTL, jeśli diagram obsługuje odwrócenie. Tylko do odczytu **bool**. |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | Określa, czy kształt jest TextHolder. Tylko do odczytu **bool**. |
| virtual [SmartArtLayoutType](../smartartlayouttype/) [get_Layout](./get_layout/)() | Zwraca lub ustawia układ obiektu [SmartArt](../smartart/). Tylko do odczytu [SmartArtLayoutType](../smartartlayouttype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | Zwraca obiekt [LineFormat](../../aspose.slides/lineformat/), który zawiera właściwości formatowania linii dla kształtu. Tylko do odczytu [ILineFormat](../../aspose.slides/ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | Zwraca nazwę kształtu. Tylko do odczytu [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_Node](./get_node/)(**int32_t**) | Zwraca węzeł z kolekcji węzłów głównych w obiekcie [SmartArt](../smartart/) pod wskazanym indeksem. Tylko do odczytu [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_NodeFromAll](./get_nodefromall/)(**int32_t**) | Zwraca węzeł z kolekcji zawierającej wszystkie węzły w obiekcie [SmartArt](../smartart/) pod wskazanym indeksem. Tylko do odczytu [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_Nodes](./get_nodes/)() | Zwraca kolekcje węzłów głównych w obiekcie [SmartArt](../smartart/). Tylko do odczytu [ISmartArtNodeCollection](../ismartartnodecollection/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | Zwraca unikalny identyfikator w zakresie slajdu, który pozostaje stały przez cały okres życia kształtu i umożliwia PowerPointowi lub kodowi interfejsowemu niezawodne odwoływanie się do kształtu z dowolnego miejsca dokumentu. Tylko do odczytu **uint32_t**. Zobacz także [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | Zwraca nadrzędny obiekt [GroupShape](../../aspose.slides/groupshape/), jeśli kształt jest grupowany. W przeciwnym razie zwraca null. Tylko do odczytu [IGroupShape](../../aspose.slides/igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | Zwraca placeholder dla kształtu. Tylko do odczytu [IPlaceholder](../../aspose.slides/iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Zwraca prezentację. Tylko do odczytu [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [SmartArtQuickStyleType](../smartartquickstyletype/) [get_QuickStyle](./get_quickstyle/)() | Zwraca lub ustawia szybki styl obiektu [SmartArt](../smartart/). Tylko do odczytu [SmartArtQuickStyleType](../smartartquickstyletype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | Zwraca surowe właściwości ramki kształtu. Tylko do odczytu [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | Zwraca liczbę stopni, o które określony kształt jest obrócony wokół osi Z. Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna oznacza obrót przeciwny do ruchu wskazówek zegara. Tylko do odczytu **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | Zwraca blokady kształtu. Tylko do odczytu [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Zwraca podstawowy slajd. Tylko do odczytu [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | Zwraca obiekt [ThreeDFormat](../../aspose.slides/threedformat/), który zawiera właściwości formatowania linii dla kształtu. Tylko do odczytu [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | Zwraca wewnętrzny, prezentacją-zakresowy identyfikator przeznaczony do użytku przez dodatki lub inny kod. Ponieważ wartość tę może ponownie przypisać użytkownik lub programowo, nie należy jej traktować jako trwały unikalny klucz. Tylko do odczytu **uint32_t**. Zobacz także [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | Pobiera szerokość kształtu, mierzona w punktach. Tylko do odczytu **float**. |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | Pobiera współrzędną x lewego górnego rogu kształtu, mierzona w punktach. Tylko do odczytu **float**. |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | Pobiera współrzędną y lewego górnego rogu kształtu, mierzona w punktach. Tylko do odczytu **float**. |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | Zwraca pozycję kształtu w kolejności Z. Shapes[0] zwraca kształt znajdujący się najdalej w tle, a Shapes[Shapes.Count - 1] zwraca kształt znajdujący się najbliżej przodu. Tylko do odczytu **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | Zwraca podstawowy placeholder shape (shape z układu i/lub slajdu-matki, z którego dziedziczony jest bieżący shape). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie niestandardowych obiektów. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | Zwraca miniaturę kształtu. [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) typ granic miniatury kształtu jest używany domyślnie. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | Zwraca miniaturę kształtu. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie niestandardowych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie przy konstruowaniu podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie przy konstruowaniu podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o określoną wartość. |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | Definiuje, że ten kształt nie jest placeholderem. |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | Ustawia tekst alternatywny powiązany z kształtem. Zapis [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Ustawia tytuł tekstu alternatywnego powiązanego z kształtem. Zapis [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | Właściwość określa, jak kształt będzie renderowany w trybie czarno-białym. Zapis [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| virtual void [set_ColorStyle](./set_colorstyle/)([SmartArtColorType](../smartartcolortype/)) | Zwraca lub ustawia styl koloru obiektu [SmartArt](../smartart/). Zapis [SmartArtColorType](../smartartcolortype/). |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | Ustawia właściwości ramki kształtu. Zapis [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | Ustawia wysokość kształtu, mierzoną w punktach. Zapis **float**. |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | Określa, czy kształt jest ukryty. Zapis **bool**. |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | Ustawia hiperłącze zdefiniowane dla kliknięcia myszą. Zapis [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | Ustawia hiperłącze zdefiniowane dla najechania myszą. Zapis [IHyperlink](../../aspose.slides/ihyperlink/). |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | Ustawia opcję „Mark as decorative”. Zapis/odczyt **bool**. |
| virtual void [set_IsReversed](./set_isreversed/)(**bool**) | Zwraca lub ustawia stan diagramu [SmartArt](../smartart/) względem (lewo-do-prawo) LTR lub (prawo-do-lewo) RTL, jeśli diagram obsługuje odwrócenie. Zapis **bool**. |
| virtual void [set_Layout](./set_layout/)([SmartArtLayoutType](../smartartlayouttype/)) | Zwraca lub ustawia układ obiektu [SmartArt](../smartart/). Zapis [SmartArtLayoutType](../smartartlayouttype/). |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | Ustawia nazwę kształtu. Zapis [System::String](../../system/string/). |
| virtual void [set_QuickStyle](./set_quickstyle/)([SmartArtQuickStyleType](../smartartquickstyletype/)) | Zwraca lub ustawia szybki styl obiektu [SmartArt](../smartart/). Zapis [SmartArtQuickStyleType](../smartartquickstyletype/). |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | Ustawia surowe właściwości ramki kształtu. Zapis [IShapeFrame](../../aspose.slides/ishapeframe/). |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | Ustawia liczbę stopni, o które określony kształt jest obrócony wokół osi Z. Wartość dodatnia oznacza obrót zgodny z ruchem wskazówek zegara; wartość ujemna oznacza obrót przeciwny. Zapis **float**. |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | Ustawia szerokość kształtu, mierzoną w punktach. Zapis **float**. |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | Ustawia współrzędną x lewego górnego rogu kształtu, mierzoną w punktach. Zapis **float**. |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | Ustawia współrzędną y lewego górnego rogu kształtu, mierzoną w punktach. Zapis **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala na zmianę wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Inkrementuje licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Dekrementuje i zwraca licznik współdzielonych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję niestandardowych obiektów do string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażniczego [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Inkrementuje licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Dekrementuje licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Zapisuje zawartość [Shape](../../aspose.slides/shape/) jako plik SVG. |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Zapisuje zawartość [Shape](../../aspose.slides/shape/) jako plik SVG. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
## Zobacz również

* Klasa [IGraphicalObject](../../aspose.slides/igraphicalobject/)
* Przestrzeń nazw [Aspose::Slides::SmartArt](../)
* Biblioteka [Aspose.Slides](../../)