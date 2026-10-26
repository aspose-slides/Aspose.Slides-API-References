---
title: Matrix
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Reprezentuje macierz 3x3 definiującą operacje transformacji. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji System::MakeObject() . Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub naruszenia asercji. Zawsze otaczaj tę klasę wskaźnikiem System::SmartPtr i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji."
type: docs
weight: 118
url: /pl/system.drawing.drawing2d/matrix/
---
## Matrix klasa

Reprezentuje macierz 3x3 definiującą operacje transformacji. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonania i/lub naruszenia asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji.

```cpp
class Matrix : public System::Object
```

## Metody

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\> [Clone](./clone/)() const | Tworzy kopię bieżącego obiektu. |
| void [Dispose](./dispose/)() | Zwalnia wszystkie zasoby systemu operacyjnego nabyte przez bieżący obiekt. |
| **bool** [Equals](./equals/)([ptr](../../system/object/ptr/)) override | Sprawdza, czy podany obiekt jest [Matrix](./) i jest identyczny z tym obiektem. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie liczb zmiennoprzecinkowych w stylu C#, w którym dwa NaN są traktowane jako równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_Elements](./get_elements/)() const | Zwraca tablicę zawierającą elementy macierzy w następującej kolejności: m11, m12, m21, m22, dx, dy. |
| **bool** [get_IsIdentity](./get_isidentity/)() const | Określa, czy macierz reprezentowana przez bieżący obiekt jest macierzą jednostkową. |
| **bool** [get_IsInvertible](./get_isinvertible/)() const | Określa, czy macierz reprezentowana przez bieżący obiekt jest odwracalna. |
| **float** [get_OffsetX](./get_offsetx/)() const | Zwraca wartość translacji X macierzy reprezentowanej przez bieżący obiekt. |
| **float** [get_OffsetY](./get_offsety/)() const | Zwraca wartość translacji Y macierzy reprezentowanej przez bieżący obiekt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Invert](./invert/)() | Odwraca macierz reprezentowaną przez bieżący obiekt. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokowanie instrukcją C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| [Matrix](./matrix/)() | Tworzy nową instancję klasy [Matrix](./), która reprezentuje macierz jednostkową. |
| [Matrix](./matrix/)(**float**, **float**, **float**, **float**, **float**, **float**) | Tworzy nową instancję klasy [Matrix](./) i inicjalizuje ją podanymi wartościami. |
| [Matrix](./matrix/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Tworzy nową instancję klasy [Matrix](./) odpowiadającą transformacji geometrycznej określonej przez podany prostokąt i tablicę punktów. |
| [Matrix](./matrix/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Tworzy nową instancję klasy [Matrix](./) odpowiadającą transformacji geometrycznej określonej przez podany prostokąt i tablicę punktów. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&) | Mnoży macierz reprezentowaną przez bieżący obiekt przez podaną macierz. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&, [MatrixOrder](../matrixorder/)) | Mnoży macierz reprezentowaną przez bieżący obiekt przez podaną macierz. |
| [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągu znaków i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza współdzielony licznik referencji o podaną wartość. |
| void [Reset](./reset/)() | Resetuje macierz reprezentowaną przez bieżący obiekt, aby stała się macierzą jednostkową. |
| void [Rotate](./rotate/)(**float**) | Obraca macierz reprezentowaną przez bieżący obiekt zgodnie z ruchem wskazówek zegara o podany kąt. |
| void [Rotate](./rotate/)(**float**, [MatrixOrder](../matrixorder/)) | Obraca macierz reprezentowaną przez bieżący obiekt zgodnie z ruchem wskazówek zegara wokół początku układu o podany kąt. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&) | Obraca macierz reprezentowaną przez bieżący obiekt zgodnie z ruchem wskazówek zegara wokół określonego punktu o podany kąt. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&, [MatrixOrder](../matrixorder/)) | Obraca macierz reprezentowaną przez bieżący obiekt zgodnie z ruchem wskazówek zegara wokół określonego punktu o podany kąt. |
| void [Scale](./scale/)(**float**, **float**) | Stosuje podany wektor skalowania do macierzy reprezentowanej przez bieżący obiekt. |
| void [Scale](./scale/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Stosuje podany wektor skalowania do macierzy reprezentowanej przez bieżący obiekt. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość współdzielonego licznika referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca współdzielony licznik referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [Shear](./shear/)(**float**, **float**) | Stosuje podany wektor ukośności do macierzy reprezentowanej przez bieżący obiekt. |
| void [Shear](./shear/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Stosuje podany wektor ukośności do macierzy reprezentowanej przez bieżący obiekt. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na łańcuch znaków. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Stosuje transformację geometryczną zdefiniowaną przez macierz reprezentowaną przez bieżący obiekt do podanych punktów. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Stosuje transformację geometryczną zdefiniowaną przez macierz reprezentowaną przez bieżący obiekt do podanych punktów. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Stosuje transformację geometryczną zdefiniowaną przez macierz reprezentowaną przez bieżący obiekt do podanych punktów. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Stosuje transformację geometryczną zdefiniowaną przez macierz reprezentowaną przez bieżący obiekt do podanych punktów. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Stosuje wyłącznie komponenty skalowania i rotacji macierzy reprezentowanej przez bieżący obiekt do podanych punktów. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Stosuje wyłącznie komponenty skalowania i rotacji macierzy reprezentowanej przez bieżący obiekt do podanych punktów. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Stosuje wyłącznie komponenty skalowania i rotacji macierzy reprezentowanej przez bieżący obiekt do podanych punktów. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Stosuje wyłącznie komponenty skalowania i rotacji macierzy reprezentowanej przez bieżący obiekt do podanych punktów. |
| void [Translate](./translate/)(**float**, **float**) | Stosuje podany wektor translacji do macierzy reprezentowanej przez bieżący obiekt. |
| void [Translate](./translate/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Stosuje podany wektor translacji do macierzy reprezentowanej przez bieżący obiekt. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie instrukcji C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| void [VectorTransformPoints](./vectortransformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Mnoży każdy wektor w tablicy przez macierz reprezentowaną przez bieżący obiekt. |
| void [VectorTransformPoints](./vectortransformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Mnoży każdy wektor w tablicy przez macierz reprezentowaną przez bieżący obiekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno być wywoływane bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Matrix](./~matrix/)() | Destruktor. |
| virtual  [~Object](../../system/object/~object/)() | Usuwa obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |

## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [System::Drawing::Drawing2D](../)
* Biblioteka [Aspose.Slides](../../)