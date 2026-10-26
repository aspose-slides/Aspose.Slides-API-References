---
title: ColorMatrix
second_title: "Aspose.Slides для C++: справочник API"
description: "Представляет собой 5×5 матрицу, содержащую координаты цветового пространства RGBAW. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляры данного типа в стеке или с помощью оператора new, поскольку это приведёт к ошибкам выполнения и/или сбоям проверок. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 27
url: /ru/system.drawing.imaging/colormatrix/
---
## ColorMatrix класс

Представляет собой 5×5 матрицу, содержащую координаты цветового пространства RGBAW. Экземпляры этого класса должны быть выделены только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям проверок. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class ColorMatrix : public System::Object
```

## Методы

| Method | Description |
| --- | --- |
|  [ColorMatrix](./colormatrix/)() | Создаёт новый экземпляр класса [ColorMatrix](./) и инициализирует его значениями единичной матрицы. |
|  [ColorMatrix](./colormatrix/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::ArrayPtr](../../system/arrayptr/)\<**float**\>\>\&) | Создаёт новый экземпляр класса [ColorMatrix](./) и инициализирует его заданными значениями. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значений в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| **float** [get_Matrix00](./get_matrix00/)() const | Возвращает значение в 0-й строке и 0-м столбце. |
| **float** [get_Matrix01](./get_matrix01/)() const | Возвращает значение в 0-й строке и 1-м столбце. |
| **float** [get_Matrix02](./get_matrix02/)() const | Возвращает значение в 0-й строке и 2-м столбце. |
| **float** [get_Matrix03](./get_matrix03/)() const | Возвращает значение в 0-й строке и 3-м столбце. |
| **float** [get_Matrix04](./get_matrix04/)() const | Возвращает значение в 0-й строке и 4-м столбце. |
| **float** [get_Matrix10](./get_matrix10/)() const | Возвращает значение в 1-й строке и 0-м столбце. |
| **float** [get_Matrix11](./get_matrix11/)() const | Возвращает значение в 1-й строке и 1-м столбце. |
| **float** [get_Matrix12](./get_matrix12/)() const | Возвращает значение в 1-й строке и 2-м столбце. |
| **float** [get_Matrix13](./get_matrix13/)() const | Возвращает значение в 1-й строке и 3-м столбце. |
| **float** [get_Matrix14](./get_matrix14/)() const | Возвращает значение в 1-й строке и 4-м столбце. |
| **float** [get_Matrix20](./get_matrix20/)() const | Возвращает значение в 2-й строке и 0-м столбце. |
| **float** [get_Matrix21](./get_matrix21/)() const | Возвращает значение в 2-й строке и 1-м столбце. |
| **float** [get_Matrix22](./get_matrix22/)() const | Возвращает значение в 2-й строке и 2-м столбце. |
| **float** [get_Matrix23](./get_matrix23/)() const | Возвращает значение в 2-й строке и 3-м столбце. |
| **float** [get_Matrix24](./get_matrix24/)() const | Возвращает значение в 2-й строке и 4-м столбце. |
| **float** [get_Matrix30](./get_matrix30/)() const | Возвращает значение в 3-й строке и 0-м столбце. |
| **float** [get_Matrix31](./get_matrix31/)() const | Возвращает значение в 3-й строке и 1-м столбце. |
| **float** [get_Matrix32](./get_matrix32/)() const | Возвращает значение в 3-й строке и 2-м столбце. |
| **float** [get_Matrix33](./get_matrix33/)() const | Возвращает значение в 3-й строке и 3-м столбце. |
| **float** [get_Matrix34](./get_matrix34/)() const | Возвращает значение в 3-й строке и 4-м столбце. |
| **float** [get_Matrix40](./get_matrix40/)() const | Возвращает значение в 4-й строке и 0-м столбце. |
| **float** [get_Matrix41](./get_matrix41/)() const | Возвращает значение в 4-й строке и 1-м столбце. |
| **float** [get_Matrix42](./get_matrix42/)() const | Возвращает значение в 4-й строке и 2-м столбце. |
| **float** [get_Matrix43](./get_matrix43/)() const | Возвращает значение в 4-й строке и 3-м столбце. |
| **float** [get_Matrix44](./get_matrix44/)() const | Возвращает значение в 4-й строке и 4-м столбце. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| **float** [idx_get](./idx_get/)(int, int) | Возвращает значение в указанной строке и столбце. |
| **float** [idx_set](./idx_set/)(int, int, **float**) | Устанавливает указанное значение в заданном месте матрицы. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку, аналог C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значений со ссылкой nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [set_Matrix00](./set_matrix00/)(**float**) | Устанавливает значение в 0-й строке и 0-м столбце. |
| void [set_Matrix01](./set_matrix01/)(**float**) | Устанавливает значение в 0-й строке и 1-м столбце. |
| void [set_Matrix02](./set_matrix02/)(**float**) | Устанавливает значение в 0-й строке и 2-м столбце. |
| void [set_Matrix03](./set_matrix03/)(**float**) | Устанавливает значение в 0-й строке и 3-м столбце. |
| void [set_Matrix04](./set_matrix04/)(**float**) | Устанавливает значение в 0-й строке и 4-м столбце. |
| void [set_Matrix10](./set_matrix10/)(**float**) | Устанавливает значение в 1-й строке и 0-м столбце. |
| void [set_Matrix11](./set_matrix11/)(**float**) | Устанавливает значение в 1-й строке и 1-м столбце. |
| void [set_Matrix12](./set_matrix12/)(**float**) | Устанавливает значение в 1-й строке и 2-м столбце. |
| void [set_Matrix13](./set_matrix13/)(**float**) | Устанавливает значение в 1-й строке и 3-м столбце. |
| void [set_Matrix14](./set_matrix14/)(**float**) | Устанавливает значение в 1-й строке и 4-м столбце. |
| void [set_Matrix20](./set_matrix20/)(**float**) | Устанавливает значение в 2-й строке и 0-м столбце. |
| void [set_Matrix21](./set_matrix21/)(**float**) | Устанавливает значение в 2-й строке и 1-м столбце. |
| void [set_Matrix22](./set_matrix22/)(**float**) | Устанавливает значение в 2-й строке и 2-м столбце. |
| void [set_Matrix23](./set_matrix23/)(**float**) | Устанавливает значение в 2-й строке и 3-м столбце. |
| void [set_Matrix24](./set_matrix24/)(**float**) | Устанавливает значение в 2-й строке и 4-м столбце. |
| void [set_Matrix30](./set_matrix30/)(**float**) | Устанавливает значение в 3-й строке и 0-м столбце. |
| void [set_Matrix31](./set_matrix31/)(**float**) | Устанавливает значение в 3-й строке и 1-м столбце. |
| void [set_Matrix32](./set_matrix32/)(**float**) | Устанавливает значение в 3-й строке и 2-м столбце. |
| void [set_Matrix33](./set_matrix33/)(**float**) | Устанавливает значение в 3-й строке и 3-м столбце. |
| void [set_Matrix34](./set_matrix34/)(**float**) | Устанавливает значение в 3-й строке и 4-м столбце. |
| void [set_Matrix40](./set_matrix40/)(**float**) | Устанавливает значение в 4-й строке и 0-м столбце. |
| void [set_Matrix41](./set_matrix41/)(**float**) | Устанавливает значение в 4-й строке и 1-м столбце. |
| void [set_Matrix42](./set_matrix42/)(**float**) | Устанавливает значение в 4-й строке и 2-м столбце. |
| void [set_Matrix43](./set_matrix43/)(**float**) | Устанавливает значение в 4-й строке и 3-м столбце. |
| void [set_Matrix44](./set_matrix44/)(**float**) | Устанавливает значение в 4-й строке и 4-м столбце. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й параметр шаблона как слабый указатель (в отличие от shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку, аналог C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [Object](../../system/object/)
* Пространство имён [System::Drawing::Imaging](../)
* Библиотека [Aspose.Slides](../../)