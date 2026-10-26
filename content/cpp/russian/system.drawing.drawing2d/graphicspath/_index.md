---
title: GraphicsPath
second_title: Aspose.Slides для C++ справочник API
description: "Представляет набор соединённых линий и кривых. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям проверок. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 66
url: /ru/system.drawing.drawing2d/graphicspath/
---
## GraphicsPath класс


Represents a set of connected lines and curves. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class GraphicsPath : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| void [AddArc](./addarc/)(**float**, **float**, **float**, **float**, **float**, **float**) | Добавляет указанную эллиптическую дугу к пути, представляющему текущий объект. |
| void [AddArc](./addarc/)(int, int, int, int, **float**, **float**) | Добавляет указанную эллиптическую дугу к пути, представляющему текущий объект. |
| void [AddArc](./addarc/)(const [RectangleF](../../system.drawing/rectanglef/)\&, **float**, **float**) | Добавляет указанную эллиптическую дугу к пути, представляющему текущий объект. |
| void [AddArc](./addarc/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Добавляет указанную эллиптическую дугу к пути, представляющему текущий объект. |
| void [AddBezier](./addbezier/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Добавляет указанную кубическую кривую Безье к пути, представляющему текущий объект. |
| void [AddBezier](./addbezier/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Добавляет указанную кубическую кривую Безье к пути, представляющему текущий объект. |
| void [AddBezier](./addbezier/)(int, int, int, int, int, int, int, int) | Добавляет указанную кубическую кривую Безье к пути, представляющему текущий объект. |
| void [AddBezier](./addbezier/)(**float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | Добавляет указанную кубическую кривую Безье к пути, представляющему текущий объект. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Добавляет последовательность соединённых кубических кривых Безье к текущей фигуре. |
| void [AddBeziers](./addbeziers/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Добавляет последовательность соединённых кубических кривых Безье к текущей фигуре. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Добавляет указанную замкнутую кривую к пути, представляющему текущий объект. |
| void [AddClosedCurve](./addclosedcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Добавляет указанную замкнутую кривую к пути, представляющему текущий объект. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, **float**) | Добавляет указанную кривую к пути, представляющему текущий объект. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, **float**) | Добавляет указанную кривую к пути, представляющему текущий объект. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, int, int, **float**) | Добавляет указанную кривую к пути, представляющему текущий объект. |
| void [AddCurve](./addcurve/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, int, int, **float**) | Добавляет указанную кривую к пути, представляющему текущий объект. |
| void [AddEllipse](./addellipse/)(**float**, **float**, **float**, **float**) | Добавляет указанный эллипс к пути, представляющему текущий объект. |
| void [AddEllipse](./addellipse/)(int, int, int, int) | Добавляет указанный эллипс к пути, представляющему текущий объект. |
| void [AddEllipse](./addellipse/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Добавляет указанный эллипс к пути, представляющему текущий объект. |
| void [AddEllipse](./addellipse/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Добавляет указанный эллипс к пути, представляющему текущий объект. |
| void [AddLine](./addline/)(const [Point](../../system.drawing/point/)\&, const [Point](../../system.drawing/point/)\&) | Добавляет указанную линию к пути, представляющему текущий объект. |
| void [AddLine](./addline/)(const [PointF](../../system.drawing/pointf/)\&, const [PointF](../../system.drawing/pointf/)\&) | Добавляет указанную линию к пути, представляющему текущий объект. |
| void [AddLine](./addline/)(int, int, int, int) | Добавляет указанную линию к пути, представляющему текущий объект. |
| void [AddLine](./addline/)(**float**, **float**, **float**, **float**) | Добавляет указанную линию к пути, представляющему текущий объект. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Добавляет указанную последовательность соединённых отрезков к пути, представляющему текущий объект. |
| void [AddLines](./addlines/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Добавляет указанную последовательность соединённых отрезков к пути, представляющему текущий объект. |
| void [AddPath](./addpath/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\>\&, **bool**) | Добавляет указанный путь к пути, представляющему текущий объект. |
| void [AddPie](./addpie/)(**float**, **float**, **float**, **float**, **float**, **float**) | Добавляет указанную контурную форму сектора к пути, представляющему текущий объект. |
| void [AddPie](./addpie/)(int, int, int, int, **float**, **float**) | Добавляет указанную контурную форму сектора к пути, представляющему текущий объект. |
| void [AddPie](./addpie/)(const [Rectangle](../../system.drawing/rectangle/)\&, **float**, **float**) | Добавляет указанную контурную форму сектора к пути, представляющему текущий объект. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Добавляет указанный многоугольник к пути, представляющему текущий объект. |
| void [AddPolygon](./addpolygon/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Добавляет указанный многоугольник к пути, представляющему текущий объект. |
| void [AddRectangle](./addrectangle/)(const [Rectangle](../../system.drawing/rectangle/)\&) | Добавляет указанный прямоугольник к пути, представляющему текущий объект. |
| void [AddRectangle](./addrectangle/)(const [RectangleF](../../system.drawing/rectanglef/)\&) | Добавляет указанный прямоугольник к пути, представляющему текущий объект. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../../system.drawing/rectangle/)\>\&) | Добавляет указанную последовательность прямоугольников к пути, представляющему текущий объект. |
| void [AddRectangles](./addrectangles/)(const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../../system.drawing/rectanglef/)\>\&) | Добавляет указанную последовательность прямоугольников к пути, представляющему текущий объект. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Point](../../system.drawing/point/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Добавляет строку текста к пути, представляющему текущий объект. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [PointF](../../system.drawing/pointf/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Добавляет строку текста к пути, представляющему текущий объект. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [Rectangle](../../system.drawing/rectangle/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Добавляет строку текста к пути, представляющему текущий объект. |
| void [AddString](./addstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../../system.drawing/fontfamily/)\>\&, int, **float**, [RectangleF](../../system.drawing/rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../../system.drawing/stringformat/)\>\&) | Добавляет строку текста к пути, представляющему текущий объект. |
| virtual [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](./)\> [Clone](./clone/)() | Создаёт копию текущего объекта. |
| void [CloseAllFigures](./closeallfigures/)() | Закрывает все открытые фигуры и начинает новую. |
| void [CloseFigure](./closefigure/)() | Закрывает текущую фигуру и начинает новую. |
| void [Dispose](./dispose/)() | Освобождает все ресурсы операционной системы, захваченные текущим объектом. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| void [Flatten](./flatten/)() | Выполняет уплощение каждой кривой в пути, преобразуя её в последовательность соединённых линий. Используется значение уплощения 0.25. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&) | Выполняет уплощение каждой кривой в пути, преобразуя её в последовательность соединённых линий. Используется значение уплощения 0.25. |
| void [Flatten](./flatten/)(const [MatrixPtr](../matrixptr/)\&, **float**) | Выполняет уплощение каждой кривой в пути, преобразуя её в последовательность соединённых линий. |
| [FillMode](../fillmode/) [get_FillMode](./get_fillmode/)() | Возвращает режим заполнения текущего объекта. |
| [SharedPtr](../../system/sharedptr/)\<[PathData](../pathdata/)\> [get_PathData](./get_pathdata/)() | Возвращает объект [PathData](../pathdata/), содержащий точки, образующие путь, представляемый текущим объектом, и их типы. |
| [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\> [get_PathPoints](./get_pathpoints/)() const | Возвращает массив, содержащий точки, образующие путь, представляемый текущим объектом. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_PathTypes](./get_pathtypes/)() const | Возвращает массив, содержащий значения, указывающие типы точек, образующих путь, представляемый текущим объектом. |
| int [get_PointCount](./get_pointcount/)() const | Возвращает количество точек в пути, представляемом текущим объектом. |
| [RectangleF](../../system.drawing/rectanglef/) [GetBounds](./getbounds/)(const [MatrixPtr](../matrixptr/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) const | Возвращает объект [RectangleF](../../system.drawing/rectanglef/), представляющий прямоугольник, ограничивающий путь, представляемый текущим объектом, после преобразования с указанной матрицей. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, ассоциированную с объектом. |
| Detail::FigureType [GetFigureFlags](./getfigureflags/)() | Возвращает значение, представляющее побитовое сочетание значений Detail::FigureType, указывающее, какие типы фигур содержатся в пути, представляемом текущим объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| [PointF](../../system.drawing/pointf/) [GetLastPoint](./getlastpoint/)() const | Возвращает объект [PointF](../../system.drawing/pointf/), представляющий последнюю точку в пути. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
|  [GraphicsPath](./graphicspath/)([FillMode](../fillmode/)) | Создаёт новый экземпляр класса [GraphicsPath](./) с указанным режимом заполнения. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Создаёт новый экземпляр объекта [GraphicsPath](./), представляющего указанный путь. |
|  [GraphicsPath](./graphicspath/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, [FillMode](../fillmode/)) | Создаёт новый экземпляр объекта [GraphicsPath](./), представляющего указанный путь. |
|  [GraphicsPath](./graphicspath/)(const SkPath\&) |  |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| **bool** [IsOutlineVisible](./isoutlinevisible/)(const [PointF](../../system.drawing/pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Определяет, находится ли указанная точка внутри (под) контура этого [GraphicsPath](./), когда он отрисован с указанным [Pen](../../system.drawing/pen/). НЕ РЕАЛИЗОВАНО. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../../system.drawing/pointf/)\&) | Определяет, находится ли указанная точка внутри пути, представляемого текущим объектом. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | Определяет, находится ли указанная точка внутри пути, представляемого текущим объектом. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копии. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [Reset](./reset/)() | Очищает путь, удаляя все точки. |
| void [Reverse](./reverse/)() | Разворачивает порядок точек в массиве PathPoints этого [GraphicsPath](./). |
| void [set_FillMode](./set_fillmode/)([FillMode](../fillmode/)) | Устанавливает режим заполнения текущего объекта. |
| void [SetMarkers](./setmarkers/)() | НЕ РЕАЛИЗОВАНО. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона в виде слабого указателя (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [StartFigure](./startfigure/)() | Начинает новую фигуру. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| void [Transform](./transform/)(const [MatrixPtr](../matrixptr/)\&) | Трансформирует путь, представляемый текущим объектом, применив к нему указанную матрицу преобразования. |
| void [Transform](./transform/)(const SkMatrix\&) |  |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [Widen](./widen/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../../system.drawing/pen/)\>\&) | Заменяет этот путь контуром вокруг исходного пути. |
|  [~GraphicsPath](./~graphicspath/)() | Деструктор. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [Object](../../system/object/)
* Пространство имён [System::Drawing::Drawing2D](../)
* Библиотека [Aspose.Slides](../../)