---
title: Font
second_title: Aspose.Slides для C++ справочник API
description: "Представляет конкретный формат текста, включая гарнитуру шрифта, размер и стиль. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 79
url: /ru/system.drawing/font/
---
## Класс Font

Represents a particular format for text, including font face, size, and style. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Font : public System::Object
```

## Методы

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Font](./)\> [Clone](./clone/)() | Возвращает копию текущего шрифта. |
| void [Dispose](./dispose/)() | Освобождает все ресурсы операционной системы, полученные текущим объектом. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Определяет, являются ли текущий и указанный объекты идентичными. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
|  [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[Font](./)\>\&, [FontStyle](../fontstyle/)) | Создаёт новый экземпляр класса [Font](./), представляющий указанный существующий шрифт с заданным стилем шрифта. |
|  [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\>\&, **float**, [FontStyle](../fontstyle/), [GraphicsUnit](../graphicsunit/), **uint8_t**, **bool**) | Создаёт новый экземпляр класса [Font](./). |
|  [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\>\&, **float**, [GraphicsUnit](../graphicsunit/)) | Создаёт новый экземпляр класса [Font](./). |
|  [Font](./font/)(const [String](../../system/string/)\&, **float**, [FontStyle](../fontstyle/), [GraphicsUnit](../graphicsunit/), **uint8_t**, **bool**) | Создаёт новый экземпляр класса [Font](./). |
|  [Font](./font/)(const [String](../../system/string/)\&, **float**, [GraphicsUnit](../graphicsunit/)) | Создаёт новый экземпляр класса [Font](./). |
| static [SharedPtr](../../system/sharedptr/)\<[Font](./)\> [FromLogFont](./fromlogfont/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | НЕ РЕАЛИЗОВАНО. |
| **bool** [get_Bold](./get_bold/)() | Определяет, применён ли к шрифту, представленному текущим объектом, стиль полужирный. |
| [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\> [get_FontFamily](./get_fontfamily/)() | Возвращает семейство шрифта, представленного текущим объектом. |
| [FontStyle](../fontstyle/) [get_FontStyle](./get_fontstyle/)() | Возвращает стиль шрифта, представленного текущим объектом. |
| **uint8_t** [get_GdiCharSet](./get_gdicharset/)() | Возвращает значение, указывающее набор символов GDI, используемый шрифтом, представленным текущим объектом. |
| int [get_Height](./get_height/)() | Возвращает межстрочный интервал шрифта, представленного текущим объектом, в пикселях. |
| **bool** [get_Italic](./get_italic/)() | Определяет, применён ли к шрифту, представленному текущим объектом, стиль курсив. |
| [String](../../system/string/) [get_Name](./get_name/)() | Возвращает имя гарнитуры шрифта, представленного текущим объектом. |
| [String](../../system/string/) [get_OriginalFontName](./get_originalfontname/)() | Возвращает первоначально указанное имя шрифта. |
| **float** [get_Size](./get_size/)() | Возвращает размер em шрифта, представленного текущим объектом, измеренный в единицах, указанных свойством Unit. |
| **float** [get_SizeInPoints](./get_sizeinpoints/)() | Возвращает размер em шрифта, представленного текущим объектом, в пунктах. |
| **bool** [get_Strikeout](./get_strikeout/)() | Определяет, применён ли к шрифту, представленному текущим объектом, стиль зачёркивания. |
| [FontStyle](../fontstyle/) [get_Style](./get_style/)() | Возвращает стиль шрифта, представленного текущим объектом. |
| **bool** [get_Underline](./get_underline/)() | Определяет, применён ли к шрифту, представленному текущим объектом, стиль подчёркивания. |
| [GraphicsUnit](../graphicsunit/) [get_Unit](./get_unit/)() | Возвращает единицу измерения для шрифта, представленного текущим объектом. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| **float** [GetHeight](./getheight/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Возвращает межстрочный интервал шрифта, представленного текущим объектом, в текущей единице заданного объекта [Graphics](../graphics/). |
| **float** [GetHeight](./getheight/)(**float**) | Возвращает высоту шрифта, представленного текущим объектом, при отрисовке на устройстве вывода с указанным вертикальным разрешением. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывается напрямую или использует объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копирующее построение подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копирующее построение подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не совместный). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывается напрямую или использует объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Смотрите также

* Класс [Object](../../system/object/)
* Пространство имён [System::Drawing](../)
* Библиотека [Aspose.Slides](../../)