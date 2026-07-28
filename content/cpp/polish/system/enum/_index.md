---
title: Enum
second_title: Aspose.Slides – dokumentacja API dla C++
description: Udostępnia metody, które wykonują pewne operacje na wartościach typu wyliczeniowego. Jest to typ statyczny bez usług instancji. Nie należy nigdy tworzyć jego instancji w żaden sposób.
type: docs
weight: 1587
url: /pl/system/enum/
---
## Struktura wyliczenia


Udostępnia metody, które wykonują pewne operacje na wartościach typu wyliczeniowego. Jest to typ statyczny bez usług instancji. Nie należy nigdy tworzyć jego instancji w żaden sposób.

```cpp
template<class E,class Guard>class Enum
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| E | Typ wyliczenia, którego wartości obsługuje klasa |
| Guard | Argument typu serwisowego, którego celem jest zapewnienie, że **E** jest typem wyliczalnym |
## Metody

| Metoda | Opis |
| --- | --- |
| static int [Compare](./compare/)(E, T) | Wykonuje arytmetyczne porównanie wartości podanych stałych wyliczeniowych. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetDescription](./getdescription/)(T) | Zwraca nazwę stałej wyliczeniowej, która ma podaną wartość. |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetName](./getname/)(T) | Zwraca nazwę stałej wyliczeniowej, która ma podaną wartość. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() | Zwraca tablicę zawierającą nazwy wszystkich członków wyliczenia **E**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() | Zwraca typ bazowy wyliczenia. |
| static [ArrayPtr](../arrayptr/)\<E\> [GetValues](./getvalues/)() | Zwraca tablicę zawierającą wszystkie elementy wyliczenia **E**. |
| static **bool** [HasFlag](./hasflag/)(E, E) | Określa, czy określone bity są ustawione w binarnej reprezentacji podanej wartości wyliczeniowej. |
| static **bool** [IsDefined](./isdefined/)(E) | Określa, czy podana wartość jest członkiem typu wyliczeniowego **E**. |
| static std::enable_if\<std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, **bool**\>::type [IsDefined](./isdefined/)(T) | Określa, czy podana wartość jest członkiem typu wyliczeniowego **T**. |
| static **bool** [IsDefined](./isdefined/)(const [String](../string/)\&) | Określa, czy wartość o podanej nazwie znajduje się wśród członków wyliczenia **E**. |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | Konwertuje podany ciąg znaków na równoważną stałą wyliczeniową. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, E\&) | Próbuje skonwertować podany ciąg znaków na równoważną stałą wyliczeniową. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**, E\&) | Próbuje skonwertować podany ciąg znaków na równoważną stałą wyliczeniową. |
## Typedefs

| Typedef | Opis |
| --- | --- |
| [UnderlyingType](./underlyingtype/) | Alias dla bazowego typu wyliczenia. |

## Zobacz również

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)