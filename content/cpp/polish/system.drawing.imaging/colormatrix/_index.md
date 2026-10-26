---
title: ColorMatrix
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Reprezentuje macierz 5x5 zawierającą współrzędne przestrzeni kolorów RGBAW. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji System::MakeObject(). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub błędy asercji. Zawsze opakowuj tę klasę w wskaźnik System::SmartPtr i używaj tego wskaźnika do przekazywania go jako argumentu do funkcji."
type: docs
weight: 27
url: /pl/system.drawing.imaging/colormatrix/
---
## ColorMatrix klasa


Reprezentuje macierz 5x5 zawierającą współrzędne przestrzeni kolorów RGBAW. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub błędy asercji. Zawsze opakowuj tę klasę w wskaźnik [System::SmartPtr](../../system/smartptr/) i używaj tego wskaźnika do przekazywania jej jako argumentu do funkcji.

```cpp
class ColorMatrix : public System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
|  [ColorMatrix](./colormatrix/)() | Tworzy nową instancję klasy [ColorMatrix](./) i inicjalizuje ją wartościami macierzy jednostkowej. |
|  [ColorMatrix](./colormatrix/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::ArrayPtr](../../system/arrayptr/)\<**float**\>\>\&) | Tworzy nową instancję klasy [ColorMatrix](./) i inicjalizuje ją podanymi wartościami. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu referencyjnego w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typu wartościowego w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, pomimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, gdzie dwa NaN są uznawane za równe, pomimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| **float** [get_Matrix00](./get_matrix00/)() const | Zwraca wartość w wierszu 0 i kolumnie 0. |
| **float** [get_Matrix01](./get_matrix01/)() const | Zwraca wartość w wierszu 0 i kolumnie 1. |
| **float** [get_Matrix02](./get_matrix02/)() const | Zwraca wartość w wierszu 0 i kolumnie 2. |
| **float** [get_Matrix03](./get_matrix03/)() const | Zwraca wartość w wierszu 0 i kolumnie 3. |
| **float** [get_Matrix04](./get_matrix04/)() const | Zwraca wartość w wierszu 0 i kolumnie 4. |
| **float** [get_Matrix10](./get_matrix10/)() const | Zwraca wartość w wierszu 1 i kolumnie 0. |
| **float** [get_Matrix11](./get_matrix11/)() const | Zwraca wartość w wierszu 1 i kolumnie 1. |
| **float** [get_Matrix12](./get_matrix12/)() const | Zwraca wartość w wierszu 1 i kolumnie 2. |
| **float** [get_Matrix13](./get_matrix13/)() const | Zwraca wartość w wierszu 1 i kolumnie 3. |
| **float** [get_Matrix14](./get_matrix14/)() const | Zwraca wartość w wierszu 1 i kolumnie 4. |
| **float** [get_Matrix20](./get_matrix20/)() const | Zwraca wartość w wierszu 2 i kolumnie 0. |
| **float** [get_Matrix21](./get_matrix21/)() const | Zwraca wartość w wierszu 2 i kolumnie 1. |
| **float** [get_Matrix22](./get_matrix22/)() const | Zwraca wartość w wierszu 2 i kolumnie 2. |
| **float** [get_Matrix23](./get_matrix23/)() const | Zwraca wartość w wierszu 2 i kolumnie 3. |
| **float** [get_Matrix24](./get_matrix24/)() const | Zwraca wartość w wierszu 2 i kolumnie 4. |
| **float** [get_Matrix30](./get_matrix30/)() const | Zwraca wartość w wierszu 3 i kolumnie 0. |
| **float** [get_Matrix31](./get_matrix31/)() const | Zwraca wartość w wierszu 3 i kolumnie 1. |
| **float** [get_Matrix32](./get_matrix32/)() const | Zwraca wartość w wierszu 3 i kolumnie 2. |
| **float** [get_Matrix33](./get_matrix33/)() const | Zwraca wartość w wierszu 3 i kolumnie 3. |
| **float** [get_Matrix34](./get_matrix34/)() const | Zwraca wartość w wierszu 3 i kolumnie 4. |
| **float** [get_Matrix40](./get_matrix40/)() const | Zwraca wartość w wierszu 4 i kolumnie 0. |
| **float** [get_Matrix41](./get_matrix41/)() const | Zwraca wartość w wierszu 4 i kolumnie 1. |
| **float** [get_Matrix42](./get_matrix42/)() const | Zwraca wartość w wierszu 4 i kolumnie 2. |
| **float** [get_Matrix43](./get_matrix43/)() const | Zwraca wartość w wierszu 4 i kolumnie 3. |
| **float** [get_Matrix44](./get_matrix44/)() const | Zwraca wartość w wierszu 4 i kolumnie 4. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę danych licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umożliwia haszowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analog wywołania C# [System.Object.GetType()](../../system/object/gettype/). |
| **float** [idx_get](./idx_get/)(int, int) | Zwraca wartość w określonym wierszu i kolumnie. |
| **float** [idx_set](./idx_set/)(int, int, **float**) | Ustawia określoną wartość w podanej lokalizacji macierzy. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę statement lock() z C#. Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umożliwia klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje nic, naprawdę, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje nic, naprawdę, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| void [set_Matrix00](./set_matrix00/)(**float**) | Ustawia wartość w wierszu 0 i kolumnie 0. |
| void [set_Matrix01](./set_matrix01/)(**float**) | Ustawia wartość w wierszu 0 i kolumnie 1. |
| void [set_Matrix02](./set_matrix02/)(**float**) | Ustawia wartość w wierszu 0 i kolumnie 2. |
| void [set_Matrix03](./set_matrix03/)(**float**) | Ustawia wartość w wierszu 0 i kolumnie 3. |
| void [set_Matrix04](./set_matrix04/)(**float**) | Ustawia wartość w wierszu 0 i kolumnie 4. |
| void [set_Matrix10](./set_matrix10/)(**float**) | Ustawia wartość w wierszu 1 i kolumnie 0. |
| void [set_Matrix11](./set_matrix11/)(**float**) | Ustawia wartość w wierszu 1 i kolumnie 1. |
| void [set_Matrix12](./set_matrix12/)(**float**) | Ustawia wartość w wierszu 1 i kolumnie 2. |
| void [set_Matrix13](./set_matrix13/)(**float**) | Ustawia wartość w wierszu 1 i kolumnie 3. |
| void [set_Matrix14](./set_matrix14/)(**float**) | Ustawia wartość w wierszu 1 i kolumnie 4. |
| void [set_Matrix20](./set_matrix20/)(**float**) | Ustawia wartość w wierszu 2 i kolumnie 0. |
| void [set_Matrix21](./set_matrix21/)(**float**) | Ustawia wartość w wierszu 2 i kolumnie 1. |
| void [set_Matrix22](./set_matrix22/)(**float**) | Ustawia wartość w wierszu 2 i kolumnie 2. |
| void [set_Matrix23](./set_matrix23/)(**float**) | Ustawia wartość w wierszu 2 i kolumnie 3. |
| void [set_Matrix24](./set_matrix24/)(**float**) | Ustawia wartość w wierszu 2 i kolumnie 4. |
| void [set_Matrix30](./set_matrix30/)(**float**) | Ustawia wartość w wierszu 3 i kolumnie 0. |
| void [set_Matrix31](./set_matrix31/)(**float**) | Ustawia wartość w wierszu 3 i kolumnie 1. |
| void [set_Matrix32](./set_matrix32/)(**float**) | Ustawia wartość w wierszu 3 i kolumnie 2. |
| void [set_Matrix33](./set_matrix33/)(**float**) | Ustawia wartość w wierszu 3 i kolumnie 3. |
| void [set_Matrix34](./set_matrix34/)(**float**) | Ustawia wartość w wierszu 3 i kolumnie 4. |
| void [set_Matrix40](./set_matrix40/)(**float**) | Ustawia wartość w wierszu 4 i kolumnie 0. |
| void [set_Matrix41](./set_matrix41/)(**float**) | Ustawia wartość w wierszu 4 i kolumnie 1. |
| void [set_Matrix42](./set_matrix42/)(**float**) | Ustawia wartość w wierszu 4 i kolumnie 2. |
| void [set_Matrix43](./set_matrix43/)(**float**) | Ustawia wartość w wierszu 4 i kolumnie 3. |
| void [set_Matrix44](./set_matrix44/)(**float**) | Ustawia wartość w wierszu 4 i kolumnie 4. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Pozwala przełączać wskaźniki w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umożliwia konwersję własnych obiektów na string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie statement lock() z C#. Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [System::Drawing::Imaging](../)
* Biblioteka [Aspose.Slides](../../)