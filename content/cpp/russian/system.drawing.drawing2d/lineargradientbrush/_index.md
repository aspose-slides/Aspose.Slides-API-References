---
title: LinearGradientBrush
second_title: Aspose.Slides для C++ справочника API
description: "Представляет кисть линейного градиента. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 105
url: /ru/system.drawing.drawing2d/lineargradientbrush/
---
## LinearGradientBrush класс

Представляет кисть линейного градиента. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class LinearGradientBrush : public System::Drawing::Brush
```

## Методы

| Метод | Описание |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Создаёт копию текущего объекта. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | Ничего не делает. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| [SharedPtr](../../system/sharedptr/)\<[Blend](../blend/)\> [get_Blend](./get_blend/)() const | Возвращает blend, который определяет коэффициенты и позиции базовых цветов для этой кисти. |
| **bool** [get_GammaCorrection](./get_gammacorrection/)() const | Возвращает значение, указывающее, включена ли корректировка гаммы для этой кисти. |
| [SharedPtr](../../system/sharedptr/)\<[ColorBlend](../colorblend/)\> [get_InterpolationColors](./get_interpolationcolors/)() const | Возвращает объект [ColorBlend](../colorblend/), определяющий многокольоровой линейный градиент. |
| [ArrayPtr](../../system/arrayptr/)\<[Color](../../system.drawing/color/)\> [get_LinearColors](./get_linearcolors/)() const | Возвращает начальный и конечный цвета этого градиента. |
| [RectangleF](../../system.drawing/rectanglef/) [get_Rectangle](./get_rectangle/)() | Возвращает ограничивающий прямоугольник. |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\> [get_Transform](./get_transform/)() const | Возвращает копию объекта [Matrix](../matrix/), который определяет геометрические трансформации кисти, представленной текущим объектом. |
| [WrapMode](../wrapmode/) [get_WrapMode](./get_wrapmode/)() const | Возвращает режим обтекания. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| [LinearGradientBrush](./lineargradientbrush/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&) | Создаёт новый экземпляр [LinearGradientBrush](./). |
| [LinearGradientBrush](./lineargradientbrush/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&) | Создаёт новый экземпляр [LinearGradientBrush](./). |
| [LinearGradientBrush](./lineargradientbrush/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&, [LinearGradientMode](../lineargradientmode/)) | Создаёт новый экземпляр [LinearGradientBrush](./). |
| [LinearGradientBrush](./lineargradientbrush/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&, [LinearGradientMode](../lineargradientmode/)) | Создаёт новый экземпляр [LinearGradientBrush](./). |
| [LinearGradientBrush](./lineargradientbrush/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&, **float**, **bool**) | Создаёт новый экземпляр [LinearGradientBrush](./). |
| [LinearGradientBrush](./lineargradientbrush/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [Color](../../system.drawing/color/)\&, const [Color](../../system.drawing/color/)\&, **float**, **bool**) | Создаёт новый экземпляр [LinearGradientBrush](./). |
| void [Lock](../../system/object/lock/)() | Реализует блокировку, аналогичную оператору C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\>\&, [MatrixOrder](../matrixorder/)) | Умножает матрицу трансформации текущего объекта на указанную матрицу. |
| [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копирующее конструирование подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копирующее конструирование подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [ResetTransform](./resettransform/)() | Сбрасывает матрицу трансформации текущего объекта. |
| void [RotateTransform](./rotatetransform/)(**float**, [MatrixOrder](../matrixorder/)) | Вращает матрицу трансформации текущего объекта. |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Масштабирует матрицу трансформации текущего объекта. |
| void [set_Blend](./set_blend/)(const [SharedPtr](../../system/sharedptr/)\<[Blend](../blend/)\>\&) | Устанавливает blend, определяющий коэффициенты и позиции базовых цветов для этой кисти. |
| void [set_GammaCorrection](./set_gammacorrection/)(**bool**) | Устанавливает статус коррекции гаммы для этой кисти. |
| void [set_InterpolationColors](./set_interpolationcolors/)(const [SharedPtr](../../system/sharedptr/)\<[ColorBlend](../colorblend/)\>\&) | Устанавливает объект [ColorBlend](../colorblend/), определяющий многокольоровой линейный градиент. |
| void [set_LinearColors](./set_linearcolors/)(const [ArrayPtr](../../system/arrayptr/)\<[Color](../../system.drawing/color/)\>\&) | Устанавливает начальный и конечный цвета этого градиента. |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](../matrix/)\>\&) | Устанавливает объект [Matrix](../matrix/), который определяет геометрические трансформации кисти, представленной текущим объектом. |
| void [set_WrapMode](./set_wrapmode/)([WrapMode](../wrapmode/)) | Устанавливает режим обтекания. |
| void [SetBlendTriangularShape](./setblendtriangularshape/)(**float**, **float**) | НЕ РЕАЛИЗОВАНО. |
| void [SetSigmaBellShape](./setsigmabellshape/)(**float**, **float**) | НЕ РЕАЛИЗОВАНО. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-ый аргумент шаблона в виде слабого указателя (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../matrixorder/)) | Перемещает матрицу трансформации текущего объекта. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку, аналогичную оператору C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [Brush](../../system.drawing/brush/)
* Пространство имён [System::Drawing::Drawing2D](../)
* Библиотека [Aspose.Slides](../../)