---
title: String
second_title: Справочник API Aspose.Slides для C++
description: "Класс String используется по всей библиотеке. Является заменой C# System.String при переводе кода. По соображениям оптимизации не считается подклассом Object. Этот тип следует выделять в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа."
type: docs
weight: 1249
url: /ru/system/string/
---
## Класс String

[String](./) класс, используемый по всей библиотеке. Является заменой C# [System.String](./) при переводе кода. По соображениям оптимизации не считается подклассом [Object](../object/). Этот тип следует выделять в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](../smartptr/) для управления объектами этого типа.

```cpp
class String
```

## Методы

| Метод | Описание |
| --- | --- |
|  [ASPOSECPP_VALUE_TYPE_IMPLEMENTS_INTERFACES](./asposecpp_value_type_implements_interfaces/)() | [String](./) является типом значения на стороне C++, который неявно (без наследования) реализует некоторые интерфейсы. |
| const UChar * [begin](./begin/)() const | Возвращает указатель на начало реального буфера строки. Никогда ничего не переallocирует. Не гарантирует, что буфер завершается нулевым символом. |
| [String](./) [Clone](./clone/)() const | Создает копию текущей строки. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**) | Сравнивает два подстрока, возвращая значение меньше-равно-больше. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Сравнивает два подстрока, возвращая значение меньше-равно-больше. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Сравнивает две строки, возвращая значение меньше-равно-больше. |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) | Сравнивает две строки, возвращая значение меньше-равно-больше. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**) | Сравнивает две строки, возвращая значение меньше-равно-больше. |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Сравнивает две строки, возвращая значение меньше-равно-больше. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, const [String](./)\&) | Сравнивает две строки в ординальном режиме. |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, int, const [String](./)\&, int, int) | Сравнивает две строки в ординальном режиме. |
| int [CompareTo](./compareto/)(const [String](./)\&) const | Сравнивает две строки в стиле «меньше-равно-больше». Использует текущую культуру. |
| static [String](./) [Concat](./concat/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&) | Конкатенирует строки. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&) | Конкатенирует строки. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&) | Конкатенирует строки. |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&, const [String](./)\&) | Конкатенирует строки. |
| **bool** [Contains](./contains/)(const [String](./)\&) const | Проверяет, является ли str подстрокой текущей строки. |
| **bool** [Contains](./contains/)(char16_t) const | Проверяет, содержит ли строка указанный символ. |
| static [String](./) [Copy](./copy/)(const [String](./)\&) | Создает копию строки. |
| void [CopyTo](./copyto/)(int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) const | Копирует символы строки в существующие элементы массива. Размер не изменяется. |
| const UChar * [end](./end/)() const | Возвращает указатель на конец реального буфера строки. Никогда ничего не переallocирует. Не гарантирует, что буфер завершается нулевым символом. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&) const | Проверяет, заканчивается ли строка указанной подстрокой. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Проверяет, заканчивается ли строка указанной подстрокой. |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Проверяет, заканчивается ли строка указанной подстрокой. |
| **bool** [Equals](./equals/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Сравнение на равенство [String](./). Поддерживаются несколько режимов, определяемых перечислением StringComparison. |
| **bool** [Equals](./equals/)(const [String](./)\&) const | Сравнение на равенство [String](./). Используется режим сравнения [System::StringComparison::Ordinal](../stringcomparison/). |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&) | Сравнивает две строки на равенство с использованием ординального режима. |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | Сравнивает две строки на равенство. |
| int [FastToAscii](./fasttoascii/)(char, int) const | Пытается преобразовать [String](./) в ASCII-строку. |
| static [String](./) [Format](./format/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, const [String](./)\&, const Args\&...) | Форматирует строку в стиле C#. |
| static [String](./) [Format](./format/)(std::nullptr_t, const [String](./)\&, const Args\&...) | Форматирует строку в стиле C#. |
| static [String](./) [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | Форматирует строку в стиле C#. |
| static [String](./) [Format](./format/)(const [String](./)\&, const Args\&...) | Форматирует строку в стиле C#. |
| static [String](./) [Format](./format/)(const [String](./)\&, const [System::ArrayPtr](../arrayptr/)\<T\>\&) | Форматирует строку в стиле C#. |
| static [String](./) [FromAscii](./fromascii/)(const char *) | Создает [String](./) из ASCII-строки. |
| static [String](./) [FromAscii](./fromascii/)(const char *, int) | Создает [String](./) из ASCII-строки. |
| static [String](./) [FromAscii](./fromascii/)(const std::string\&) | Создает [String](./) из ASCII-строки. |
| static [String](./) [FromUtf16](./fromutf16/)(const std::u16string\&) | Создает [String](./) из строки utf16. |
| static [String](./) [FromUtf32](./fromutf32/)(const **uint32_t** *, **int32_t**) | Создает [String](./) из строки utf32. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *) | Создает [String](./) из строки utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const char *, int) | Создает [String](./) из строки utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const **uint8_t** *) | Создает [String](./) из строки utf8. |
| static [String](./) [FromUtf8](./fromutf8/)(const std::string\&) | Создает [String](./) из строки utf8. |
| static [String](./) [FromWCS](./fromwcs/)(const std::wstring\&) | Создает [String](./) из ширококодовой строки. |
| int [get_Length](./get_length/)() const | Получает длину строки. |
| int [GetHashCode](./gethashcode/)() const | Вычисляет хеш содержащейся строки. Реализовано в ICU, не совпадает с хешами в C#. |
| int [IndexOf](./indexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Поиск подстроки вперёд. |
| int [IndexOf](./indexof/)(char_t, int) const | Поиск символа вперёд. |
| int [IndexOf](./indexof/)(char_t, int, int) const | Поиск символа вперёд в подстроке. |
| int [IndexOf](./indexof/)(const [String](./)\&, int) const | Поиск подстроки вперёд. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Поиск подстроки вперёд. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) const | Поиск подстроки вперёд. |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int) const | Поиск подстроки вперёд. |
| int [IndexOfAny](./indexofany/)(char_t, int) const | Поиск символа вперёд. |
| int [IndexOfAny](./indexofany/)(const [String](./)\&, int) const | Последовательно ищет все символы str в этой строке. Если найден первый символ, возвращается его позиция, иначе ищется второй и т.д. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Ищет любой из переданных символов во всей строке. Сравнивает первый символ строки со всеми символами anyOf, затем второй и т.д. Возвращает индекс первого соответствующего символа. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Ищет любой из переданных символов в подстроке. Сравнивает первый символ строки со всеми символами anyOf, затем второй и т.д. Возвращает индекс первого соответствующего символа. |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Ищет любой из переданных символов в подстроке. Сравнивает первый символ строки со всеми символами anyOf, затем второй и т.д. Возвращает индекс первого соответствующего символа. |
| [String](./) [Insert](./insert/)(int, const [String](./)\&) const | Вставляет подстроку в указанную позицию. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Проверяет, является ли объект строки типом, указанным в [TypeInfo](../typeinfo/). |
| **bool** [IsAsciiString](./isasciistring/)() const | Указывает, содержит ли [String](./) только ASCII-символы. |
| **bool** [IsEmpty](./isempty/)() const | Проверяет, что строка не null и пуста. |
| **bool** [IsNormalized](./isnormalized/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Проверяет, нормализована ли юникод-строка с использованием указанной формы нормализации. |
| **bool** [IsNull](./isnull/)() const | Проверяет, считается ли строка null. [String](./) является null только если она построена через конструктор [String()](./string/), перемещена, скопирована или присвоена из null-строки или вызван метод [reset()](./reset/). |
| **bool** [IsNullOrEmpty](./isnullorempty/)() const | Проверяет, пуста ли строка или считается null. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [String](./)\&) | Проверяет, является ли переданная строка null или пустой. |
| static **bool** [IsNullOrWhiteSpace](./isnullorwhitespace/)(const [String](./)\&) | Указывает, является ли указанная строка null, пустой или состоит только из пробельных символов. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, int) | Объединяет массив, используя строку-разделитель. |
| static [String](./) [Join](./join/)(const [String](./)\&, const System::Details::ArrayView\<[String](./)\>\&, int, int) | Объединяет массив, используя строку-разделитель. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](./)\>\>\&) | Объединяет массив, используя строку-разделитель. |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\&) | Объединяет массив, используя строку-разделитель. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int) const | Поиск подстроки назад. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Поиск подстроки назад. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | Поиск подстроки назад. |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, int, [StringComparison](../stringcomparison/)) const | Поиск подстроки назад. |
| int [LastIndexOf](./lastindexof/)(char_t) const | Поиск символа назад. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**) const | Поиск символа назад. |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**, **int32_t**) const | Поиск символа назад. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Ищет любые из переданных символов во всей строке в обратном порядке. Сравнивает последний символ строки со всеми символами anyOf, затем предыдущий и т.д. Возвращает индекс первого найденного совпадения. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | Ищет любые из переданных символов в подстроке в обратном порядке. Сравнивает последний символ строки со всеми символами anyOf, затем предыдущий и т.д. Возвращает индекс первого найденного совпадения. |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | Ищет любые из переданных символов в подстроке в обратном порядке. Сравнивает последний символ строки со всеми символами anyOf, затем предыдущий и т.д. Возвращает индекс первого найденного совпадения. |
| [String](./) [Normalize](./normalize/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | Нормализует юникод-строку, используя указанную форму нормализации. |
|  [operator ReadOnlySpan< char16_t >](./operator_readonlyspan_less_char16_t__greater/)() const | Преобразует строку в только-для-чтения span. |
| **bool** [operator!=](./operator_not_equal/)(const [String](./)\&) const | Оператор сравнения неравенства. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Проверяет, что строка не null. Применяет ту же логику, что и вызов [IsNull()](./isnull/). |
| [String](./) [operator+](./operator_plus/)(const [String](./)\&) const | Оператор конкатенации [String](./). |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Конкатенация [String](./) со строковым литералом или указателем на строку символов. |
| [String](./) [operator+](./operator_plus/)(char_t) const | Adds character to the end of the string. |
| [String](./) [operator+](./operator_plus/)(int) const | Adds integer value string representation to the end of the string. |
| [String](./) [operator+](./operator_plus/)(**uint32_t**) const | Adds unsigned integer value string representation to the end of the string. |
| [String](./) [operator+](./operator_plus/)(**double**) const | Adds floating point value string representation to the end of the string. |
| [String](./) [operator+](./operator_plus/)(**int64_t**) const | Adds integer value string representation to the end of the string. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Adds reference type object string representation to the end of the string. |
| [String](./) [operator+](./operator_plus/)(const T\&) const | Adds reference type object string representation to the end of the string. |
| [String](./) [operator+](./operator_plus/)(T) const | Adds boolean value string representation to the end of the string. |
| [String](./)\& [operator+=](./operator_plus_equal/)(char_t) | Оператор присваивания конкатенации. |
| [String](./)\& [operator+=](./operator_plus_equal/)(const [String](./)\&) | Оператор присваивания конкатенации. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**double**) | Оператор присваивания конкатенации. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint8_t**) | Оператор присваивания конкатенации. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int16_t**) | Оператор присваивания конкатенации. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint16_t**) | Оператор присваивания конкатенации. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int32_t**) | Оператор присваивания конкатенации. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint32_t**) | Оператор присваивания конкатенации. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int64_t**) | Оператор присваивания конкатенации. |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint64_t**) | Оператор присваивания конкатенации. |
| [String](./)\& [operator+=](./operator_plus_equal/)(T) | Оператор присваивания конкатенации. |
| **bool** [operator<](./operator_less/)(const [String](./)\&) const | Сравнивает строки порядка. |
| [String](./)\& [operator=](./operator_equal/)(const [String](./)\&) | Оператор присваивания. |
| [String](./)\& [operator=](./operator_equal/)([String](./)\&&) | Оператор перемещения присваивания. |
| **bool** [operator==](./operator_equal_equal/)(const [String](./)\&) const | Оператор сравнения на равенство. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Проверяет, что строка null. Применяет ту же логику, что и вызов [IsNull()](./isnull/). |
| **bool** [operator>](./operator_greater/)(const [String](./)\&) const | Сравнивает порядок строк. |
| char_t [operator[]](./operator[]/)(int) const | Получает символ в указанной позиции. |
| [String](./) [PadLeft](./padleft/)(int, char_t) const | Adds padding on the left of original string. |
| [String](./) [PadRight](./padright/)(int, char_t) const | Adds padding on the right of original string. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() const | Returns reverse iterator to the last character (if any) of actual string buffer. |
| [String](./) [Remove](./remove/)(**int32_t**, **int32_t**) const | Extracts everything but substring from current string. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() const | Returns reverse iterator to the before first character (if any) of actual string buffer. |
| [String](./) [Replace](./replace/)(char_t, char_t) const | Replaces all occurrences of character in the string. |
| [String](./) [Replace](./replace/)(const [String](./)\&, const [String](./)\&) const | Replaces all occurrences of lookup in this string. |
| [String](./)\& [reset](./reset/)() | Sets string to null. Is analogous to 'string_variable_name = null' in C#. |
| [String](./)\& [SetCharAt](./setcharat/)(int, char_t) | Sets character at specified position. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, [StringSplitOptions](../stringsplitoptions/)) const | Splits string by character. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Splits string by character. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, char_t, [StringSplitOptions](../stringsplitoptions/)) const | Splits string by one of two characters. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Splits string by one of characters specified. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | Splits string by one of characters specified. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, [StringSplitOptions](../stringsplitoptions/)) const | Splits string by substring. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Splits string by substring. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, [StringSplitOptions](../stringsplitoptions/)) const | Splits string by substring. |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, [StringSplitOptions](../stringsplitoptions/)) const | Splits string by substring. В текущей реализации поддерживает массив разделителей из нуля или одного элемента. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&) const | Проверяет, начинается ли строка с указанной подстроки. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | Проверяет, начинается ли строка с указанной подстроки. |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Проверяет, начинается ли строка с указанной подстроки. |
|  [String](./string/)() | Конструктор по умолчанию. Создаёт объект строки, считающийся null. |
|  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char16_t\>::value\>::type *) | Конструирует строку на основе строкового литерала. Считает литерал нул-терминированной строкой, вычисляет длину целевой строки по размеру литерала. |
|  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char16_t\>::value\>::type *) | Конструирует строку на основе указателя на строку символов. Считает указанный строковый объект нул-терминированным, вычисляет длину целевой строки по нулевому символу. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char\>::value\>::type *) | Конструирует строку на основе строкового литерала. Считает литерал нул-терминированной строкой в UTF8, вычисляет длину целевой строки по размеру литерала. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char\>::value\>::type *) | Конструирует строку на основе указателя на строку символов. Считает указанный строковый объект нул-терминированным в UTF8, вычисляет длину целевой строки по нулевому символу. |
|  [String](./string/)(const char16_t *, int) | Конструирует строку из указателя на строку символов и явной длины. |
|  [String](./string/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) | Инициализирует новый экземпляр класса [System.String](./) Unicode-символами, указанными в переданном только-для-чтения span. |
|  [String](./string/)(const char *, int) | Конструирует строку из указателя на строку символов и явной длины. |
|  [String](./string/)(const char16_t *, int, int) | Конструирует строку из указателя на строку символов, начиная с позиции, используя длину. |
| explicit  [String](./string/)(const char16_t, int) | Конструктор заполнения. |
|  [String](./string/)(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) | Конструктор из nullptr. Объявлен как шаблон для разрешения приоритетов с другими шаблонными конструкторами. |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, **wchar_t**\>::value\>::type *) | Конструирует строку на основе литерала широких строк. Считает литерал нул-терминированной строкой, вычисляет длину целевой строки по размеру литерала. Конверсия из **wchar_t** трудоёмка на некоторых платформах, поэтому не допускаются неявные конверсии. |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, **wchar_t**\>::value\>::type *) | Конструирует строку на основе указателя на широкую строку. Считает указанный строковый объект нул-терминированным, вычисляет длину целевой строки по нулевому символу. Конверсия из **wchar_t** трудоёмка на некоторых платформах, поэтому не допускаются неявные конверсии. |
| explicit  [String](./string/)(const **wchar_t** *, int) | Конструирует строку из указателя на широкую строку и явной длины. Конверсия из **wchar_t** трудоёмка на некоторых платформах, поэтому не допускаются неявные конверсии. |
| explicit  [String](./string/)(const **wchar_t**, int) | Конструктор заполнения. Конверсия из **wchar_t** трудоёмка на некоторых платформах, поэтому не допускаются неявные конверсии. |
|  [String](./string/)(const [String](./)\&) | Конструктор копирования. |
|  [String](./string/)([String](./)\&&) | Конструктор перемещения. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&) | Преобразует весь массив символов в строку. |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, int) | Преобразует поддиапазон массива символов в строку. Если параметры выходят за границы массива, создаётся пустая строка. |
| explicit  [String](./string/)(const codeporting_icu::UnicodeString\&) | Оборачивает UnicodeString в [String](./). |
| explicit  [String](./string/)(codeporting_icu::UnicodeString\&&) | Конструктор перемещения. |
| explicit  [String](./string/)(const std::wstring\&) | Создаёт [String](./) из ширококодовой строки. |
| explicit  [String](./string/)(const std::u16string\&) | Создаёт [String](./) из строки utf16. |
| explicit  [String](./string/)(const std::string\&) | Создаёт [String](./) из std::string, представленного в формате UTF-8. |
| explicit  [String](./string/)(const std::u32string\&) | Создаёт [String](./) из std::u32string. |
| [String](./) [Substring](./substring/)(**int32_t**) const | Извлекает подстроку. |
| [String](./) [Substring](./substring/)(**int32_t**, **int32_t**) const | Извлекает подстроку. |
| std::string [ToAsciiString](./toasciistring/)() const | Преобразует строку в std::string. Использует кодировку ASCII. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)(**int32_t**, **int32_t**, **bool**) const | Преобразует строку или подстроку в массив байтов. |
| [ArrayPtr](../arrayptr/)\<char_t\> [ToCharArray](./tochararray/)(**int32_t**, **int32_t**) const | Преобразует строку или подстроку в массив символов. |
| [String](./) [ToLower](./tolower/)() const | Преобразует все символы строки в нижний регистр. |
| [String](./) [ToLower](./tolower/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Преобразует все символы строки в нижний регистр, используя конкретную культуру. |
| [String](./) [ToLowerInvariant](./tolowerinvariant/)() const | Преобразует все символы строки в нижний регистр, используя инвариантную культуру. |
| [String](./) [ToString](./tostring/)() const | Обёртка для работы с классом [String](./) в контекстах, где [ToString()](./tostring/) вызывается для объектов типa значения. |
| [String](./) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Обёртка для работы с классом [String](./) в контекстах, где [ToString()](./tostring/) вызывается для объектов типa значения. |
| std::u16string [ToU16Str](./tou16str/)() const | Преобразует строку в std::u16string. |
| std::u32string [ToU32Str](./tou32str/)() const | Преобразует строку в std::u32string. |
| [String](./) [ToUpper](./toupper/)() const | Преобразует все символы строки в верхний регистр. |
| [String](./) [ToUpper](./toupper/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Преобразует все символы строки в верхний регистр, используя конкретную культуру. |
| [String](./) [ToUpperInvariant](./toupperinvariant/)() const | Преобразует все символы строки в верхний регистр, используя инвариантную культуру. |
| std::string [ToUtf8String](./toutf8string/)() const | Преобразует строку в std::string. Использует кодировку UTF-8. |
| std::wstring [ToWCS](./towcs/)() const | Преобразует строку в std::wstring. |
| [String](./) [Trim](./trim/)() const | Удаляет все пробельные символы в начале и в конце строки. |
| [String](./) [Trim](./trim/)(char_t) const | Удаляет все вхождения переданного символа в начале и в конце строки. |
| [String](./) [Trim](./trim/)(const [String](./)\&) const | Удаляет все вхождения переданных символов в начале и в конце строки. |
| [String](./) [Trim](./trim/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Удаляет все вхождения переданных символов в начале и в конце строки. |
| [String](./) [TrimEnd](./trimend/)() const | Удаляет все пробельные символы в конце строки. |
| [String](./) [TrimEnd](./trimend/)(char_t) const | Удаляет все вхождения переданного символа в конце строки. |
| [String](./) [TrimEnd](./trimend/)(const [String](./)\&) const | Удаляет все вхождения переданных символов в конце строки. |
| [String](./) [TrimEnd](./trimend/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Удаляет все вхождения переданных символов в конце строки. |
| [String](./) [TrimStart](./trimstart/)() const | Удаляет все пробельные символы в начале строки. |
| [String](./) [TrimStart](./trimstart/)(char_t) const | Удаляет все вхождения переданного символа в начале строки. |
| [String](./) [TrimStart](./trimstart/)(const [String](./)\&) const | Удаляет все вхождения переданных символов в начале строки. |
| [String](./) [TrimStart](./trimstart/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | Удаляет все вхождения переданных символов в начале строки. |
| const UChar * [u_str](./u_str/)() const | Возвращает буфер в стиле ICU, нул-терминированный. Может переallocировать строку. |
|  [~String](./~string/)() | Деструктор. |
## Поля

| Поле | Описание |
| --- | --- |
| static [Empty](./empty/) | Пустая строка. |
| static [Null](./null/) | Null-строка. |
## Типы

| Тип | Описание |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | Тип обратного итератора. |
## Примечания



```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // Создайте строку из массива символов и выведите её.
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // Создайте строку из массива байтов и выведите её.
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // Обрежьте строку ниже и выведите её.
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // Выведите количество слов в строке.
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
Этот пример кода дает следующий вывод:
hello
world
"This string contains whitespaces in the beginning and at the end."
Number of words: 11
*/
```

## Смотрите также

* Namespace [System](../)
* Library [Aspose.Slides](../../)