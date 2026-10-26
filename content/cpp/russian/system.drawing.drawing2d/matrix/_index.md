---
title: Matrix
second_title: Aspose.Slides для C++ справочник API
description: "Представляет 3x3 матрицу, определяющую операции трансформации. Объекты этого класса следует выделять только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 118
url: /ru/system.drawing.drawing2d/matrix/
---
## Matrix класс

Представляет 3x3 матрицу, определяющую операции трансформации. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class Matrix : public System::Object
```

## Методы

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\> [Clone](./clone/)() const | Создаёт копию текущего объекта. |
| void [Dispose](./dispose/)() | Освобождает все ресурсы операционной системы, приобретённые текущим объектом. |
| **bool** [Equals](./equals/)([ptr](../../system/object/ptr/)) override | Проверяет, является ли указанный объект [Matrix](./) и идентичен этому объекту. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равно ни- одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равно ни- одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_Elements](./get_elements/)() const | Возвращает массив, содержащий элементы матрицы в следующем порядке: m11, m12, m21, m22, dx, dy. |
| **bool** [get_IsIdentity](./get_isidentity/)() const | Определяет, является ли матрица, представленная текущим объектом, единичной матрицей. |
| **bool** [get_IsInvertible](./get_isinvertible/)() const | Определяет, является ли матрица, представленная текущим объектом, обратимой. |
| **float** [get_OffsetX](./get_offsetx/)() const | Возвращает значение трансляции X матрицы, представленной текущим объектом. |
| **float** [get_OffsetY](./get_offsety/)() const | Возвращает значение трансляции Y матрицы, представленной текущим объектом. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Invert](./invert/)() | Инвертирует матрицу, представленную текущим объектом. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
|  [Matrix](./matrix/)() | Создаёт новый экземпляр класса [Matrix](./), представляющего единичную матрицу. |
|  [Matrix](./matrix/)(**float**, **float**, **float**, **float**, **float**, **float**) | Создаёт новый экземпляр класса [Matrix](./) и инициализирует его указанными значениями. |
|  [Matrix](./matrix/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Создаёт новый экземпляр класса [Matrix](./) для геометрической трансформации, определённой указанным прямоугольником и массивом точек. |
|  [Matrix](./matrix/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Создаёт новый экземпляр класса [Matrix](./) для геометрической трансформации, определённой указанным прямоугольником и массивом точек. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&) | Умножает матрицу, представленную текущим объектом, на указанную матрицу. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&, [MatrixOrder](../matrixorder/)) | Умножает матрицу, представленную текущим объектом, на указанную матрицу. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать при построении подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать при построении подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [Reset](./reset/)() | Сбрасывает матрицу, представленную текущим объектом, так чтобы она стала единичной матрицей. |
| void [Rotate](./rotate/)(**float**) | Поворачивает матрицу, представленную текущим объектом, по часовой стрелке на указанный угол. |
| void [Rotate](./rotate/)(**float**, [MatrixOrder](../matrixorder/)) | Поворачивает матрицу, представленную текущим объектом, по часовой стрелке вокруг начала координат на указанный угол. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&) | Поворачивает матрицу, представленную текущим объектом, по часовой стрелке вокруг указанной точки на указанный угол. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&, [MatrixOrder](../matrixorder/)) | Поворачивает матрицу, представленную текущим объектом, по часовой стрелке вокруг указанной точки на указанный угол. |
| void [Scale](./scale/)(**float**, **float**) | Применяет указанный вектор масштаба к матрице, представленной текущим объектом. |
| void [Scale](./scale/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Применяет указанный вектор масштаба к матрице, представленной текущим объектом. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [Shear](./shear/)(**float**, **float**) | Применяет указанный вектор сдвига к матрице, представленной текущим объектом. |
| void [Shear](./shear/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Применяет указанный вектор сдвига к матрице, представленной текущим объектом. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Применяет геометрическую трансформацию, определённую матрицей, представленной текущим объектом, к указанным точкам. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Применяет геометрическую трансформацию, определённую матрицей, представленной текущим объектом, к указанным точкам. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Применяет геометрическую трансформацию, определённую матрицей, представленной текущим объектом, к указанным точкам. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Применяет геометрическую трансформацию, определённую матрицей, представленной текущим объектом, к указанным точкам. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Применяет только компоненты масштабирования и вращения матрицы, представленной текущим объектом, к указанным точкам. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Применяет только компоненты масштабирования и вращения матрицы, представленной текущим объектом, к указанным точкам. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Применяет только компоненты масштабирования и вращения матрицы, представленной текущим объектом, к указанным точкам. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Применяет только компоненты масштабирования и вращения матрицы, представленной текущим объектом, к указанным точкам. |
| void [Translate](./translate/)(**float**, **float**) | Применяет указанный вектор трансляции к матрице, представленной текущим объектом. |
| void [Translate](./translate/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Применяет указанный вектор трансляции к матрице, представленной текущим объектом. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| void [VectorTransformPoints](./vectortransformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Умножает каждый вектор в массиве на матрицу, представленную текущим объектом. |
| void [VectorTransformPoints](./vectortransformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Умножает каждый вектор в массиве на матрицу, представленную текущим объектом. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Matrix](./~matrix/)() | Деструктор. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
## См. также

* Класс [Object](../../system/object/)
* Пространство имён [System::Drawing::Drawing2D](../)
* Библиотека [Aspose.Slides](../../)