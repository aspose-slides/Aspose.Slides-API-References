---
title: Region
second_title: "Справочник API Aspose.Slides для C++"
description: "Представляет внутреннее пространство графической фигуры. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 261
url: /ru/system.drawing/region/
---
## Region класс

Represents the interior of a graphic shape. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Region : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Region](./)\> [Clone](./clone/)() const | Возвращает копию текущего объекта. |
| void [Complement](./complement/)(const [RectangleF](../rectanglef/)\&) | Заменяет регион, представленный текущим объектом, частью региона, определённого указанным прямоугольником, который не пересекается с этим регионом. |
| void [Complement](./complement/)(const [Rectangle](../rectangle/)\&) | Заменяет регион, представленный текущим объектом, частью региона, определённого указанным прямоугольником, который не пересекается с этим регионом. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Заменяет регион, представленный текущим объектом, частью региона, определённого указанным путем, который не пересекается с этим регионом. |
| void [Complement](./complement/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Заменяет регион, представленный текущим объектом, частью указанного региона, который не пересекается с этим регионом. |
| void [Dispose](./dispose/)() | Освобождает все ресурсы операционной системы, полученные текущим объектом. |
| **bool** [Equals](./equals/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Определяет, идентичен ли указанный регион региону, представляемому текущим объектом, на указанной поверхности рисования. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| void [Exclude](./exclude/)(const [RectangleF](../rectanglef/)\&) | Заменяет регион, представленный текущим объектом, результатом исключения из него региона, определённого указанным прямоугольником. |
| void [Exclude](./exclude/)(const [Rectangle](../rectangle/)\&) | Заменяет регион, представленный текущим объектом, результатом исключения из него региона, определённого указанным прямоугольником. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Заменяет регион, представленный текущим объектом, результатом исключения из него региона, определённого указанным путём. |
| void [Exclude](./exclude/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Заменяет регион, представленный текущим объектом, результатом исключения из него указанного региона. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Получает структуру [RectangleF](../rectanglef/), представляющую прямоугольник, ограничивающий этот [Region](./) на поверхности рисования объекта [Graphics](../graphics/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\> [GetRegionData](./getregiondata/)() const | Возвращает объект RegionData, содержащий данные, определяющие регион, представляемый текущим объектом. |
| [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\> [GetRegionScans](./getregionscans/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) const | Возвращает массив структур [RectangleF](../rectanglef/), приближенно представляющих этот [Region](./) после применения указанного преобразования матрицы. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Intersect](./intersect/)(const [RectangleF](../rectanglef/)\&) | Заменяет регион, представленный текущим объектом, результатом пересечения этого региона с регионом, определённым указанным прямоугольником. |
| void [Intersect](./intersect/)(const [Rectangle](../rectangle/)\&) | Заменяет регион, представленный текущим объектом, результатом пересечения этого региона с регионом, определённым указанным прямоугольником. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Заменяет регион, представленный текущим объектом, результатом пересечения этого региона с регионом, определённым указанным путём. |
| void [Intersect](./intersect/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Заменяет регион, представленный текущим объектом, результатом пересечения этого региона с указанным регионом. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# `is`. |
| **bool** [IsEmpty](./isempty/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Определяет, имеет ли регион, представленный текущим объектом, пустой внутренний объём на указанной поверхности рисования. |
| **bool** [IsInfinite](./isinfinite/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Определяет, имеет ли регион, представленный текущим объектом, бесконечный внутренний объём на указанной поверхности рисования. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&) const | Определяет, содержится ли указанная точка внутри региона, представленного текущим объектом. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&) const | Определяет, содержится ли указанная точка внутри региона, представленного текущим объектом. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&) | Определяет, входит ли какая-либо часть указанного прямоугольника в регион, представленный текущим объектом. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&) | Определяет, входит ли какая-либо часть указанного прямоугольника в регион, представленный текущим объектом. |
| **bool** [IsVisible](./isvisible/)(const [Point](../point/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Определяет, содержится ли указанная точка внутри региона, представленного текущим объектом, с использованием указанных графических средств. |
| **bool** [IsVisible](./isvisible/)(const [PointF](../pointf/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Определяет, содержится ли указанная точка внутри региона, представленного текущим объектом, с использованием указанных графических средств. |
| **bool** [IsVisible](./isvisible/)(const [Rectangle](../rectangle/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Определяет, входит ли какая-либо часть указанного прямоугольника в регион, представленный текущим объектом, с использованием указанных графических средств. |
| **bool** [IsVisible](./isvisible/)(const [RectangleF](../rectanglef/)\&, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Определяет, входит ли какая-либо часть указанного прямоугольника в регион, представленный текущим объектом, с использованием указанных графических средств. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) const | Определяет, содержится ли указанная точка внутри региона, представленного текущим объектом. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) const | Определяет, содержится ли указанная точка внутри региона, представленного текущим объектом, с использованием указанных графических средств. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку, аналогичную оператору C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| void [MakeEmpty](./makeempty/)() | Инициализирует текущий объект пустым внутренним объёмом. |
| void [MakeInfinite](./makeinfinite/)() | Инициализирует этот объект региона бесконечным внутренним объёмом. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копирующее конструирование подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копирующее конструирование подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значения со ссылкой на nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
|  [Region](./region/)() | Конструирует новый экземпляр класса [Region](./). |
|  [Region](./region/)(const [RectangleF](../rectanglef/)\&) | Конструирует новый экземпляр класса [Region](./), представляющего регион, определённый указанным прямоугольником. |
|  [Region](./region/)(const [Rectangle](../rectangle/)\&) | Конструирует новый экземпляр класса [Region](./), представляющего регион, определённый указанным прямоугольником. |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Конструирует новый экземпляр класса [Region](./), представляющего регион, определённый указанным путём. |
|  [Region](./region/)(const SkPath\&) |  |
|  [Region](./region/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::RegionData](../../system.drawing.drawing2d/regiondata/)\>\&) | Конструирует новый экземпляр класса [Region](./), представляющего регион, определённый объектом RegionData. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный параметр как слабый указатель (а не совместный). Позволяет переключать указатели в контейнерах в режим слабых. |
| int [SharedCount](../../system/object/sharedcount/)() const | Возвращает текущие значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | Трансформирует этот регион с помощью указанной матрицы. |
| void [Transform](./transform/)(const SkMatrix\&) | Трансформирует этот регион с помощью указанной матрицы. |
| void [Translate](./translate/)(int, int) | Сдвигает координаты региона на указанную величину. |
| void [Translate](./translate/)(**float**, **float**) | Сдвигает координаты региона на указанную величину. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Union](./union/)(const [RectangleF](../rectanglef/)\&) | Заменяет регион, представленный текущим объектом, результатом операции объединения этого региона и региона, определённого указанным прямоугольником. |
| void [Union](./union/)(const [Rectangle](../rectangle/)\&) | Заменяет регион, представленный текущим объектом, результатом объединения этого региона и региона, определённого указанным прямоугольником. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Заменяет регион, представленный текущим объектом, результатом объединения этого региона и региона, определённого указанным путём. |
| void [Union](./union/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Заменяет регион, представленный текущим объектом, результатом объединения этого региона и указанного региона. |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку, аналогичную оператору C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| void [Xor](./xor/)(const [RectangleF](../rectanglef/)\&) | Заменяет регион, представленный текущим объектом, частями этого региона и региона, определённого указанным прямоугольником, которые не пересекаются. |
| void [Xor](./xor/)(const [Rectangle](../rectangle/)\&) | Заменяет регион, представленный текущим объектом, частями этого региона и региона, определённого указанным прямоугольником, которые не пересекаются. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | Заменяет регион, представленный текущим объектом, частями этого региона и региона, определённого указанным путём, которые не пересекаются. |
| void [Xor](./xor/)(const [SharedPtr](../../system/sharedptr/)\<[Region](./)\>\&) | Заменяет регион, представленный текущим объектом, частями этого региона и указанного региона, которые не пересекаются. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
| virtual  [~Region](./~region/)() | Деструктор. |

## См. также

* Класс [Object](../../system/object/)
* Пространство имён [System::Drawing](../)
* Библиотека [Aspose.Slides](../../)