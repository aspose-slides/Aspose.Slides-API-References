---
title: IGeometryPath
second_title: Справка API Aspose.Slides для C++
description: Представляет геометрический путь GeometryShape
type: docs
weight: 2341
url: /ru/aspose.slides/igeometrypath/
---
## IGeometryPath класс

Представляет геометрический путь [GeometryShape](../geometryshape/)

```cpp
class IGeometryPath : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual void [ArcTo](./arcto/)(**float**, **float**, **float**, **float**) | Добавляет указанную дугу к пути. |
| virtual void [CloseFigure](./closefigure/)() | Закрывает текущую фигуру этого пути. |
| virtual void [CubicBezierTo](./cubicbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/)) | Добавляет кубическую кривую Безье в конец пути. |
| virtual void [CubicBezierTo](./cubicbezierto/)(**float**, **float**, **float**, **float**, **float**, **float**) | Добавляет кубическую кривую Безье в конец пути. |
| virtual void [CubicBezierTo](./cubicbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), **uint32_t**) | Добавляет кубическую кривую Безье в указанное место пути. |
| virtual void [CubicBezierTo](./cubicbezierto/)(**float**, **float**, **float**, **float**, **float**, **float**, **uint32_t**) | Добавляет кубическую кривую Безье в указанное место пути. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual [PathFillModeType](../pathfillmodetype/) [get_FillMode](./get_fillmode/)() | Устанавливает режим заполнения. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPathSegment](../ipathsegment/)\>\> [get_PathData](./get_pathdata/)() | Возвращает геометрический путь [GeometryShape](../geometryshape/) в виде массива сегментов пути. |
| virtual **bool** [get_Stroke](./get_stroke/)() | Устанавливает вид линии. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| virtual void [LineTo](./lineto/)([System::Drawing::PointF](../../system.drawing/pointf/)) | Добавляет линию в конец пути. |
| virtual void [LineTo](./lineto/)(**float**, **float**) | Добавляет линию в конец пути. |
| virtual void [LineTo](./lineto/)([System::Drawing::PointF](../../system.drawing/pointf/), **uint32_t**) | Добавляет линию в указанное место пути. |
| virtual void [LineTo](./lineto/)(**float**, **float**, **uint32_t**) | Добавляет линию в указанное место пути. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| virtual void [MoveTo](./moveto/)([System::Drawing::PointF](../../system.drawing/pointf/)) | Устанавливает позицию следующей точки. |
| virtual void [MoveTo](./moveto/)(**float**, **float**) | Устанавливает позицию следующей точки. |
| [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| virtual void [QuadraticBezierTo](./quadraticbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/)) | Добавляет квадратичную кривую Безье в конец пути. |
| virtual void [QuadraticBezierTo](./quadraticbezierto/)(**float**, **float**, **float**, **float**) | Добавляет квадратичную кривую Безье в конец пути. |
| virtual void [QuadraticBezierTo](./quadraticbezierto/)([System::Drawing::PointF](../../system.drawing/pointf/), [System::Drawing::PointF](../../system.drawing/pointf/), **uint32_t**) | Добавляет квадратичную кривую Безье в указанное место пути. |
| virtual void [QuadraticBezierTo](./quadraticbezierto/)(**float**, **float**, **float**, **float**, **uint32_t**) | Добавляет квадратичную кривую Безье в указанное место пути. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| virtual void [RemoveAt](./removeat/)(**int32_t**) | Удаляет сегмент по указанному индексу геометрического пути. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual void [set_FillMode](./set_fillmode/)([PathFillModeType](../pathfillmodetype/)) | Устанавливает режим заполнения. |
| virtual void [set_Stroke](./set_stroke/)(**bool**) | Устанавливает вид линии. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-ый параметр шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Смотрите также

* Класс [Object](../../system/object/)
* Пространство имен [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)