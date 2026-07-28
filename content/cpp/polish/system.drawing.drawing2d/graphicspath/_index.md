---
title: GraphicsPath
second_title: Odwołanie API Aspose.Slides dla C++
description: "Reprezentuje zestaw połączonych linii i krzywych. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji System::MakeObject() . Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonania i/lub błędy asercji. Zawsze owijaj tę klasę we wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji."
type: docs
weight: 66
url: /pl/system.drawing.drawing2d/graphicspath/
---
## GraphicsPath klasa

Reprezentuje zestaw połączonych linii i krzywych. Obiekty tej klasy powinny być tworzone wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub błędy asercji. Zawsze owijaj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji.

```cpp
class GraphicsPath : public System::Object
```

## Metody

| Method | Description |
| --- | --- |
| void [AddArc](./addarc/)(**float**, **float**, **float**, **float**, **float**, **float**) | Dodaje określony łuk eliptyczny do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddArc](./addarc/)(int, int, int, int, **float**, **float**) | Dodaje określony łuk eliptyczny do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddArc](./addarc/)(const [RectangleF](../../system.drawing/rectanglef/)\&, **float**, **float**) | Dodaje określony łuk eliptyczny do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddArc](./addarc/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Dodaje określony łuk eliptyczny do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddBezier](./addbezier/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Dodaje określoną krzywą Beziera trzeciego stopnia do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddBezier](./addbezier/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Dodaje określoną krzywą Beziera trzeciego stopnia do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | Dodaje określoną krzywą Beziera trzeciego stopnia do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddBezier](./addbezier/)(**float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | Dodaje określoną krzywą Beziera trzeciego stopnia do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Dodaje sekwencję połączonych krzywych Beziera trzeciego stopnia do bieżącej figury. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Dodaje sekwencję połączonych krzywych Beziera trzeciego stopnia do bieżącej figury. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Dodaje określoną zamkniętą krzywą do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Dodaje określoną zamkniętą krzywą do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Dodaje określoną krzywą do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Dodaje określoną krzywą do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, int, int, **float**) | Dodaje określoną krzywą do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, int, int, **float**) | Dodaje określoną krzywą do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddEllipse](./addellipse/)(**float**, **float**, **float**, **float**) | Dodaje określoną elipsę do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddEllipse](./addellipse/)(int, int, int, int) | Dodaje określoną elipsę do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddEllipse](./addellipse/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Dodaje określoną elipsę do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddEllipse](./addellipse/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Dodaje określoną elipsę do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddLine](./addline/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Dodaje określoną linię do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddLine](./addline/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Dodaje określoną linię do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddLine](./addline/)(int, int, int, int) | Dodaje określoną linię do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddLine](./addline/)(**float**, **float**, **float**, **float**) | Dodaje określoną linię do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Dodaje określoną serię połączonych odcinków linii do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Dodaje określoną serię połączonych odcinków linii do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddPath](./addpath/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\>\&, **bool**) | Dodaje określoną ścieżkę do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddPie](./addpie/)(**float**, **float**, **float**, **float**, **float**, **float**) | Dodaje określony obrys kształtu koła do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddPie](./addpie/)(int, int, int, int, **float**, **float**) | Dodaje określony obrys kształtu koła do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddPie](./addpie/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Dodaje określony obrys kształtu koła do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Dodaje określony wielokąt do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Dodaje określony wielokąt do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddRectangle](./addrectangle/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Dodaje określony prostokąt do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddRectangle](./addrectangle/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Dodaje określony prostokąt do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../../system.drawing/rectangle/)\>\&) | Dodaje określoną serię prostokątów do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../../system.drawing/rectanglef/)\>\&) | Dodaje określoną serię prostokątów do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Point](../../system.drawing/point/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Dodaje ciąg tekstu do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [PointF](../../system.drawing/pointf/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Dodaje ciąg tekstu do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Rectangle](../../system.drawing/rectangle/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Dodaje ciąg tekstu do ścieżki reprezentowanej przez bieżący obiekt. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [RectangleF](../../system.drawing/rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Dodaje ciąg tekstu do ścieżki reprezentowanej przez bieżący obiekt. |
| virtual [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\> [Clone](./clone/)() | Tworzy kopię bieżącego obiektu. |
| void [CloseAllFigures](./closeallfigures/)() | Zamyka wszystkie otwarte figury i rozpoczyna nową. |
| void [CloseFigure](./closefigure/)() | Zamyka bieżącą figurę i rozpoczyna nową. |
| void [Dispose](./dispose/)() | Zwalnia wszystkie zasoby systemowe przydzielone bieżącemu obiektowi. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych podwójnej precyzji w stylu C#, gdzie dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| void [Flatten](./flatten/)() | Spłaszcza każdą krzywą w ścieżce, zamieniając ją na serię połączonych linii. Używana jest wartość spłaszczenia 0,25. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&) | Spłaszcza każdą krzywą w ścieżce, zamieniając ją na serię połączonych linii. Używana jest wartość spłaszczenia 0,25. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&, **float**) | Spłaszcza każdą krzywą w ścieżce, zamieniając ją na serię połączonych linii. |
| [FillMode](../fillmode/) [get_FillMode](./get_fillmode/)() | Zwraca tryb wypełnienia bieżącego obiektu. |
| [SharedPtr](../../system/sharedptr/)\<[PathData](../pathdata/)\> [get_PathData](./get_pathdata/)() | Zwraca obiekt [PathData](../pathdata/) zawierający punkty tworzące ścieżkę reprezentowaną przez bieżący obiekt oraz ich typy. |
| [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\> [get_PathPoints](./get_pathpoints/)() const | Zwraca tablicę zawierającą punkty tworzące ścieżkę reprezentowaną przez bieżący obiekt. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_PathTypes](./get_pathtypes/)() const | Zwraca tablicę zawierającą wartości określające typy punktów tworzących ścieżkę reprezentowaną przez bieżący obiekt. |
| int [get_PointCount](./get_pointcount/)() const | Zwraca liczbę punktów w ścieżce reprezentowanej przez bieżący obiekt. |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](./getbounds/)(const [MatrixPtr](../matrixptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) const | Zwraca obiekt [RectangleF](../../system.drawing/rectanglef/) reprezentujący prostokąt ograniczający ścieżkę reprezentowaną przez bieżący obiekt po przekształceniu go określoną macierzą. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| Detail::FigureType [GetFigureFlags](./getfigureflags/)() | Zwraca wartość będącą bitową kombinacją wartości Detail::FigureType wskazującą, jakie typy figur znajdują się w ścieżce reprezentowanej przez bieżący obiekt. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogiczna metoda C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| [PointF](../../system.drawing/pointf/) [GetLastPoint](./getlastpoint/)() const | Zwraca obiekt [PointF](../../system.drawing/pointf/) reprezentujący ostatni punkt w ścieżce. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
|  [GraphicsPath](./graphicspath/)([FillMode](../fillmode/)) | Tworzy nową instancję klasy [GraphicsPath](./) z określonym trybem wypełnienia. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Tworzy nową instancję obiektu [GraphicsPath](./) reprezentującego określoną ścieżkę. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Tworzy nową instancję obiektu [GraphicsPath](./) reprezentującego określoną ścieżkę. |
|  [GraphicsPath](./graphicspath/)(const SkPath\&) |  |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| **bool** [IsOutlineVisible](./isoutlinevisible/)(const [PointF](../../system.drawing/pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Określa, czy podany punkt znajduje się wewnątrz (pod) konturu tego [GraphicsPath](./) przy rysowaniu za pomocą określonego [Pen](../../system.drawing/pen/). NIE ZREALIZOWANO. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../../system.drawing/pointf/)\&) | Określa, czy podany punkt znajduje się w ścieżce reprezentowanej przez bieżący obiekt. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | Określa, czy podany punkt znajduje się w ścieżce reprezentowanej przez bieżący obiekt. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna metoda C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o określoną wartość. |
| void [Reset](./reset/)() | Opróżnia ścieżkę, usuwając z niej wszystkie punkty. |
| void [Reverse](./reverse/)() | Odwraca kolejność punktów w tablicy PathPoints tego [GraphicsPath](./). |
| void [set_FillMode](./set_fillmode/)([FillMode](../fillmode/)) | Ustawia tryb wypełnienia bieżącego obiektu. |
| void [SetMarkers](./setmarkers/)() | NIE ZREALIZOWANO. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [StartFigure](./startfigure/)() | Rozpoczyna nową figurę. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogiczna metoda C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na łańcuch znaków. |
| void [Transform](./transform/)(const [MatrixPtr](../matrixptr/)\&) | Transformuje ścieżkę reprezentowaną przez bieżący obiekt, stosując określoną macierz transformacji. |
| void [Transform](./transform/)(const SkMatrix\&) |  |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowywanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [Widen](./widen/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Zastępuje tę ścieżkę obrysem wokół oryginalnej ścieżki. |
|  [~GraphicsPath](./~graphicspath/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [System::Drawing::Drawing2D](../)
* Biblioteka [Aspose.Slides](../../)