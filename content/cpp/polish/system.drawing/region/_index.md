---
title: Region
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Reprezentuje wnętrze graficznego kształtu. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy wykonania i/lub naruszenia asercji. Zawsze otaczaj tę klasę wskaźnikiem System::SmartPtr i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji."
type: docs
weight: 261
url: /pl/system.drawing/region/
---
## Region klasa

Reprezentuje wnętrze graficznego kształtu. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy wykonania i/lub naruszenia asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania go do funkcji jako argument.

```cpp
class Region : public System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Region](./)\> [Clone](./clone/)() const | Zwraca kopię bieżącego obiektu. |
| void [Complement](./complement/)(const [RectangleF](../rectanglef/)\&) | Zastępuje region reprezentowany przez bieżący obiekt częścią regionu określonego przez podany prostokąt, który nie przecina się z tym regionem. |
| void [Complement](./complement/)(const [Rectangle](../rectangle/)\&) | Zastępuje region reprezentowany przez bieżący obiekt częścią regionu określonego przez podany prostokąt, który nie przecina się z tym regionem. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Zastępuje region reprezentowany przez bieżący obiekt częścią regionu określonego przez podaną ścieżkę, który nie przecina się z tym regionem. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Zastępuje region reprezentowany przez bieżący obiekt częścią regionu określonego przez podany prostokąt, który nie przecina się z tym regionem. |
| void [Dispose](./dispose/)() | Zwalnia wszystkie zasoby systemowe przydzielone bieżącemu obiektowi. |
| **bool** [Equals](./equals/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Określa, czy podany region jest identyczny z regionem reprezentowanym przez bieżący obiekt na określonej powierzchni rysunkowej. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty przy użyciu semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, włącznie z NaN. |
| void [Exclude](./exclude/)(const [RectangleF](../rectanglef/)\&) | Zastępuje region reprezentowany przez bieżący obiekt wynikiem wykluczenia z niego regionu określonego przez podany prostokąt. |
| void [Exclude](./exclude/)(const [Rectangle](../rectangle/)\&) | Zastępuje region reprezentowany przez bieżący obiekt wynikiem wykluczenia z niego regionu określonego przez podany prostokąt. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Zastępuje region reprezentowany przez bieżący obiekt wynikiem wykluczenia z niego regionu określonego przez podaną ścieżkę. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Zastępuje region reprezentowany przez bieżący obiekt wynikiem wykluczenia z niego podanego regionu. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Pobiera strukturę [RectangleF](../rectanglef/) reprezentującą prostokąt ograniczający ten [Region](./) na powierzchni rysunkowej obiektu [Graphics](../graphics/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Odpowiednik metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\> [GetRegionData](./getregiondata/)() const | Zwraca obiekt RegionData zawierający dane definiujące region reprezentowany przez bieżący obiekt. |
| [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\> [GetRegionScans](./getregionscans/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) const | Zwraca tablicę struktur [RectangleF](../rectanglef/) przybliżających ten [Region](./) po zastosowaniu określonej transformacji macierzy. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Odpowiednik wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Intersect](./intersect/)(const [RectangleF](../rectanglef/)\&) | Zastępuje region reprezentowany przez bieżący obiekt wynikiem przecięcia tego regionu z regionem określonym przez podany prostokąt. |
| void [Intersect](./intersect/)(const [Rectangle](../rectangle/)\&) | Zastępuje region reprezentowany przez bieżący obiekt wynikiem przecięcia tego regionu z regionem określonym przez podany prostokąt. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Zastępuje region reprezentowany przez bieżący obiekt wynikiem przecięcia tego regionu z regionem określonym przez podaną ścieżkę. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Zastępuje region reprezentowany przez bieżący obiekt wynikiem przecięcia tego regionu z określonym regionem. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Odpowiednik operatora C# 'is'. |
| **bool** [IsEmpty](./isempty/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Określa, czy region reprezentowany przez bieżący obiekt ma pustą wewnętrzną część na określonej powierzchni rysunkowej. |
| **bool** [IsInfinite](./isinfinite/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Określa, czy region reprezentowany przez bieżący obiekt ma nieskończoną wewnętrzną część na określonej powierzchni rysunkowej. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&) const | Określa, czy podany punkt znajduje się w regionie reprezentowanym przez bieżący obiekt. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&) const | Określa, czy podany punkt znajduje się w regionie reprezentowanym przez bieżący obiekt. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&) | Określa, czy jakakolwiek część podanego prostokąta znajduje się w regionie reprezentowanym przez bieżący obiekt. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&) | Określa, czy jakakolwiek część podanego prostokąta znajduje się w regionie reprezentowanym przez bieżący obiekt. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Określa, czy podany punkt znajduje się w regionie reprezentowanym przez bieżący obiekt przy użyciu określonych elementów graficznych. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Określa, czy podany punkt znajduje się w regionie reprezentowanym przez bieżący obiekt przy użyciu określonych elementów graficznych. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Określa, czy jakakolwiek część podanego prostokąta znajduje się w regionie reprezentowanym przez bieżący obiekt przy użyciu określonych elementów graficznych. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Określa, czy jakakolwiek część podanego prostokąta znajduje się w regionie reprezentowanym przez bieżący obiekt przy użyciu określonych elementów graficznych. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) const | Określa, czy podany punkt znajduje się w regionie reprezentowanym przez bieżący obiekt. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Określa, czy podany punkt znajduje się w regionie reprezentowanym przez bieżący obiekt przy użyciu określonych elementów graficznych. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu ochronnego [LockContext](../../system/lockcontext/). |
| void [MakeEmpty](./makeempty/)() | Inicjalizuje bieżący obiekt pustym wnętrzem. |
| void [MakeInfinite](./makeinfinite/)() | Inicjalizuje ten obiekt regionu nieskończonym wnętrzem. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Odpowiednik metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcucha i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku łańcuchów. |
| [Region](./region/)() | Tworzy nową instancję klasy [Region](./). |
| [Region](./region/)(const [RectangleF](../rectanglef/)\&) | Tworzy nową instancję klasy [Region](./) reprezentującej region określony przez podany prostokąt. |
| [Region](./region/)(const [Rectangle](../rectangle/)\&) | Tworzy nową instancję klasy [Region](./) reprezentującej region określony przez podany prostokąt. |
| [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Tworzy nową instancję klasy [Region](./) reprezentującej region określony przez podaną ścieżkę. |
| [Region](./region/)(const SkPath\&) |  |
| [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\>\&) | Tworzy nową instancję klasy [Region](./) reprezentującej region określony przez podany obiekt RegionData. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia zmianę wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Odpowiednik metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów do stringa. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | Transformuje ten region przy użyciu określonej macierzy. |
| void [Transform](./transform/)(const SkMatrix\&) | Transformuje ten region przy użyciu określonej macierzy. |
| void [Translate](./translate/)(int, int) | Przesuwa współrzędne regionu o podaną wartość. |
| void [Translate](./translate/)(**float**, **float**) | Przesuwa współrzędne regionu o podaną wartość. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Union](./union/)(const [RectangleF](../rectanglef/)\&) | Zastępuje region reprezentowany przez bieżący obiekt wynikiem operacji sumy tego regionu i regionu określonego przez podany prostokąt. |
| void [Union](./union/)(const [Rectangle](../rectangle/)\&) | Zastępuje region reprezentowany przez bieżący obiekt wynikiem sumy tego regionu i regionu określonego przez podany prostokąt. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Zastępuje region reprezentowany przez bieżący obiekt wynikiem sumy tego regionu i regionu określonego przez podaną ścieżkę. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Zastępuje region reprezentowany przez bieżący obiekt wynikiem sumy tego regionu i podanego regionu. |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu ochronnego [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [Xor](./xor/)(const [RectangleF](../rectanglef/)\&) | Zastępuje region reprezentowany przez bieżący obiekt częściami tego regionu i regionu określonego przez podany prostokąt, które nie nakładają się. |
| void [Xor](./xor/)(const [Rectangle](../rectangle/)\&) | Zastępuje region reprezentowany przez bieżący obiekt częściami tego regionu i regionu określonego przez podany prostokąt, które nie nakładają się. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Zastępuje region reprezentowany przez bieżący obiekt częściami tego regionu i regionu określonego przez podaną ścieżkę, które nie nakładają się. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Zastępuje region reprezentowany przez bieżący obiekt częściami tego regionu i podanego regionu, które nie nakładają się. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
| virtual  [~Region](./~region/)() | Destruktor. |

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [System::Drawing](../)
* Biblioteka [Aspose.Slides](../../)