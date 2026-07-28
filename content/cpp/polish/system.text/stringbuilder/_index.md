---
title: StringBuilder
second_title: Aspose.Slides dla C++ - referencja API
description: "Bufor służący do kumulowania ciągu znaków kawałek po kawałku. Ten typ może być przydzielany zarówno na stosie jako typ wartościowy, jak i na stercie przy użyciu funkcji System::MakeObject(). Po przydzieleniu obiektu nigdy nie mieszaj tych dwóch przypadków użycia: posiadanie wskaźników SmartPtr do obiektów przydzielonych na stosie jest surowo zabronione."
type: docs
weight: 326
url: /pl/system.text/stringbuilder/
---
## StringBuilder klasa


[Buffer](../../system/buffer/) do kumulowania części ciągu znaków. Ten typ może być przydzielony zarówno na stosie jako typ wartościowy, jak i na stercie przy użyciu funkcji [System::MakeObject()](../../system/makeobject/). Po przydzieleniu obiektu nigdy nie mieszaj tych dwóch przypadków użycia: posiadanie wskaźników [SmartPtr](../../system/smartptr/) do obiektów przydzielonych na stosie jest surowo zabronione.

```cpp
class StringBuilder : public System::Object
```

## Metody

| Metoda | Opis |
| --- | --- |
| [StringBuilder](./) * [Append](./append/)(char_t) | Dodaje znak do buildera. |
| [StringBuilder](./) * [Append](./append/)(char_t, int) | Dodaje znaki do buildera. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Dodaje tablicę znaków do buildera. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Dodaje wycinek tablicy znaków do buildera. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&) | Dodaje ciąg znaków do buildera. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&, int, int) | Dodaje wycinek ciągu znaków do buildera. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<T\>\&) | Dodaje tekstową reprezentację obiektu do buildera. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<[StringBuilder](./)\>\&) | Dodaje zawartość innego buildera do buildera. |
| [StringBuilder](./) * [Append](./append/)(**float**) | Dodaje wartość typu float do buildera. |
| [StringBuilder](./) * [Append](./append/)(**double**) | Dodaje wartość typu double do buildera. |
| [StringBuilder](./) * [Append](./append/)(int) | Dodaje wartość całkowitą do buildera. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Append](./append/)(T) | Dodaje wartość arytmetyczną do buildera. |
| std::enable_if\<std::is_enum\<E\>::value, [StringBuilder](./) *\>::type [Append](./append/)(E) | Dodaje reprezentację tekstową wartości wyliczeniowej do buildera. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [String](../../system/string/)\&, const TArgs\&...) | Dodaje sformatowany ciąg znaków do buildera. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\>\&, const [String](../../system/string/)\&, const TArgs\&...) | Dodaje sformatowany ciąg znaków do buildera. |
| [StringBuilder](./) * [AppendLine](./appendline/)() | Dodaje znak nowej linii do buildera. |
| [StringBuilder](./) * [AppendLine](./appendline/)(const [String](../../system/string/)\&) | Dodaje ciąg znaków zakończony znakiem nowej linii do buildera. |
| [StringBuilder](./) * [Clear](./clear/)() | Usuwa wszystkie znaki z buildera. |
| void [CopyTo](./copyto/)(int, [System::ArrayPtr](../../system/arrayptr/)\<char_t\> const\&, int, int) | Kopiuje dane buildera do istniejących pozycji tablicy. |
| **int32_t** [EnsureCapacity](./ensurecapacity/)(**int32_t**) | Zapewnia, że pojemność tej instancji [System.Text.StringBuilder](./) jest co najmniej podaną wartością. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porównuje obiekty używając semantyki C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typów referencyjnych w stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porównuje obiekty typów wartościowych w stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porównanie zmiennoprzecinkowe w stylu C#, w którym dwa NaN są uznawane za równe, mimo że zgodnie z IEC 60559:1989 NaN nie jest równy żadnej wartości, w tym NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Tylko do użytku wewnętrznego. |
| int [get_Capacity](./get_capacity/)() const | Pobiera bieżącą pojemność buildera ciągu znaków. |
| int [get_Length](./get_length/)() const | Pobiera długość ciągu aktualnie w builderze. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Pobiera strukturę licznika referencji powiązaną z obiektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogiczna metoda C# [Object.GetHashCode()](../../system/object/gethashcode/). Włącza hashowanie własnych obiektów. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Pobiera rzeczywisty typ obiektu. Analogiczna metoda C# [System.Object.GetType()](../../system/object/gettype/). |
| char_t [idx_get](./idx_get/)(int) const | Pobiera znak na określonej pozycji. |
| void [idx_set](./idx_set/)(int, char_t) | Ustawia znak na określonej pozycji. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [String](../../system/string/)\&) | Wstawia ciąg znaków w stałą pozycję buildera. |
| [StringBuilder](./) * [Insert](./insert/)(**int32_t**, const [String](../../system/string/)\&, **int32_t**) | Wstawia powtarzany ciąg znaków w stałą pozycję buildera. |
| [StringBuilder](./) * [Insert](./insert/)(int, char_t) | Wstawia znak w stałą pozycję buildera. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Wstawia znaki w stałą pozycję buildera. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Insert](./insert/)(int, T) | Wstawia wartość w stałą pozycję buildera. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Sprawdza, czy obiekt jest instancją typu opisanego przez targetType. Analog operatora C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje blokadę statementu C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogiczna metoda C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Włącza klonowanie własnych typów. |
|  [Object](../../system/object/object/)() | Tworzy obiekt. Inicjalizuje wszystkie wewnętrzne struktury danych. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Konstruktor kopiujący. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operator przypisania. Nie kopiuje niczego, po prostu inicjalizuje nowy obiekt i umożliwia kopiowanie podklas. |
| char_t [operator[]](./operator[]/)(int) const | Pobiera znak na określonej pozycji. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porównuje obiekty przez referencję. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porównuje referencyjnie obiekt typu wartościowego z nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku string i nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specjalizacja [Object::ReferenceEquals](../../system/object/referenceequals/) dla przypadku ciągów znaków. |
| [StringBuilder](./) * [Remove](./remove/)(int, int) | Usuwa fragment z buildera. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Zmniejsza licznik współdzielonych referencji o podaną wartość. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Zastępuje podciąg w builderze. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | Zastępuje podciąg w zakresie buildera. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t) | Zastępuje znak w builderze. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t, int, int) | Zastępuje znak w zakresie buildera. |
| void [set_Capacity](./set_capacity/)(int) | Ustawia bieżącą pojemność buildera ciągu znaków. |
| void [set_Length](./set_length/)(int) | Obcina lub rozszerza builder do podanej długości. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ustawia n-ty argument szablonu jako słaby wskaźnik (zamiast współdzielonego). Umożliwia przełączanie wskaźników w kontenerach na tryb słaby. |
| int [SharedCount](../../system/object/sharedcount/)() const | Pobiera bieżącą wartość licznika współdzielonych referencji. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zwiększa licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmniejsza i zwraca licznik współdzielonych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
|  [StringBuilder](./stringbuilder/)() | Konstruktor. |
|  [StringBuilder](./stringbuilder/)(int) | Konstruktor. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&) | Konstruktor. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int) | Konstruktor. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int, int, int) | Konstruktor. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Pobiera ciąg znaków aktualnie zawarty w builderze. |
| [String](../../system/string/) [ToString](./tostring/)(int, int) const | Pobiera podciąg aktualnie zawarty w builderze. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukcję C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokowanie statementu C# lock(). Wywołaj bezpośrednio lub użyj obiektu strażnika [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zwiększa licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmniejsza licznik słabych referencji. Nie powinno się wywoływać bezpośrednio; zamiast tego użyj inteligentnych wskaźników lub ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niszczy obiekt. Zwalnia wszystkie wewnętrzne struktury danych. |
|  [~StringBuilder](./~stringbuilder/)() | Destruktor. |
## Zobacz także

* Klasa [Object](../../system/object/)
* Przestrzeń nazw [System::Text](../)
* Biblioteka [Aspose.Slides](../../)