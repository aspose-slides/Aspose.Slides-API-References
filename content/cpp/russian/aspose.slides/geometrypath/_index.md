---
title: GeometryPath
second_title: Справочник API Aspose.Slides для C++
description: Представляет геометрический путь GeometryShape
type: docs
weight: 1067
url: /ru/aspose.slides/geometrypath/
---
## GeometryPath класс

Представляет геометрический путь [GeometryShape](../geometryshape/)

```cpp
class GeometryPath : public Aspose::Slides::IGeometryPath
```

## Методы

| Method | Description |
| --- | --- |
| void [ArcTo](./arcto/)(**float**, **float**, **float**, **float**) override | Добавляет указанную дугу к пути. |
| void [CloseFigure](./closefigure/)() override | Закрывает текущий контур этого пути |
| void [CubicBezierTo](./cubicbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/)) override | Добавляет кубическую кривую Безье в конец пути |
| void [CubicBezierTo](./cubicbezierto/)(**float**, **float**, **float**, **float**, **float**, **float**) override | Добавляет кубическую кривую Безье в конец пути |
| void [CubicBezierTo](./cubicbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), **uint32_t**) override | Добавляет кубическую кривую Безье в указанное место пути |
| void [CubicBezierTo](./cubicbezierto/)(**float**, **float**, **float**, **float**, **float**, **float**, **uint32_t**) override | Добавляет кубическую кривую Безье в указанное место пути |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
|  [GeometryPath](./geometrypath/)() | Создаёт экземпляр [GeometryPath](./) |
| [PathFillModeType](../pathfillmodetype/) [get_FillMode](./get_fillmode/)() override | Устанавливает режим заливки |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPathSegment](../ipathsegment/)\>\> [get_PathData](./get_pathdata/)() override | Возвращает геометрический путь [GeometryShape](../geometryshape/) в виде массива сегментов пути. |
| **bool** [get_Stroke](./get_stroke/)() override | Устанавливает внешний вид контура |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [LineTo](./lineto/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | Добавляет линию в конец пути |
| void [LineTo](./lineto/)(**float**, **float**) override | Добавляет линию в конец пути |
| void [LineTo](./lineto/)([System::Drawing::PointF](../../system.drawing/pointf/), **uint32_t**) override | Добавляет линию в указанное место пути |
| void [LineTo](./lineto/)(**float**, **float**, **uint32_t**) override | Добавляет линию в указанное место пути |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-смотритель [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| void [MoveTo](./moveto/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | Устанавливает позицию следующей точки. |
| void [MoveTo](./moveto/)(**float**, **float**) override | Устанавливает позицию следующей точки. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| void [QuadraticBezierTo](./quadraticbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/)) override | Добавляет квадратичную кривую Безье в конец пути |
| void [QuadraticBezierTo](./quadraticbezierto/)(**float**, **float**, **float**, **float**) override | Добавляет квадратичную кривую Безье в конец пути |
| void [QuadraticBezierTo](./quadraticbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), **uint32_t**) override | Добавляет квадратичную кривую Безье в указанное место пути |
| void [QuadraticBezierTo](./quadraticbezierto/)(**float**, **float**, **float**, **float**, **uint32_t**) override | Добавляет квадратичную кривую Безье в указанное место пути |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типа значения со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| void [RemoveAt](./removeat/)(**int32_t**) override | Удаляет сегмент в указанном индексе геометрического пути. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [set_FillMode](./set_fillmode/)([PathFillModeType](../pathfillmodetype/)) override | Устанавливает режим заливки |
| void [set_Stroke](./set_stroke/)(**bool**) override | Устанавливает внешний вид контура |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-ый аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Инкрементирует счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Декрементирует и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-смотритель [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Инкрементирует счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Декрементирует счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [IGeometryPath](../igeometrypath/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)