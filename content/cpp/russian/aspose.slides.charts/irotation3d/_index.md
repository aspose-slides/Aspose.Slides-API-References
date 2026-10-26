---
title: IRotation3D
second_title: Aspose.Slides для C++ Справочник API
description: Представляет 3D вращение диаграммы.
type: docs
weight: 1171
url: /ru/aspose.slides.charts/irotation3d/
---
## IRotation3D класс


Представляет 3D-вращение диаграммы.

```cpp
class IRotation3D : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual **uint16_t** [get_DepthPercents](./get_depthpercents/)() | Возвращает глубину 3D-диаграммы в процентах от ширины диаграммы (от 20 до 2000 %). Чтение **uint16_t**. |
| virtual **uint16_t** [get_HeightPercents](./get_heightpercents/)() | Указывает высоту 3-D-диаграммы в процентах от ширины диаграммы (от 5 до 500 %). Чтение **uint16_t**. |
| virtual **uint8_t** [get_Perspective](./get_perspective/)() | Возвращает значение перспективы (угол угла обзора) для 3D-диаграмм (от 0 до 100). Игнорируется, если значение свойства RightAngleAxes равно true. Чтение **uint8_t**. |
| virtual **bool** [get_RightAngleAxes](./get_rightangleaxes/)() | Определяет, находятся ли оси диаграммы под прямым углом, а не нарисованы в перспективе. Иными словами, определяет, независимы ли углы осей диаграммы от её вращения или наклона. Чтение **bool**. |
| virtual **int8_t** [get_RotationX](./get_rotationx/)() | Возвращает степень вращения вокруг оси X, т.е. в направлении Y для 3D-диаграмм (от -90 до 90 градусов). Свойство соответствует элементу 21.2.2.157 rotX (X Rotation) в ECMA-376 и опции «Y Rotation» в PowerPoint 2007+. Чтение **int8_t**. |
| virtual **uint16_t** [get_RotationY](./get_rotationy/)() | Возвращает степень вращения вокруг оси Y, т.е. в направлении X для 3D-диаграмм (от 0 до 360 градусов). Свойство соответствует элементу 21.2.2.158 rotY (Y Rotation) в ECMA-376 и опции «X Rotation» в PowerPoint 2007+. Чтение **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет вычислять хеш пользовательских объектов. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывается напрямую или с использованием объекта-стража [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, а лишь инициализирует новый объект и позволяет выполнять копирующее конструирование подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, а лишь инициализирует новый объект и позволяет копирующее конструирование подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| virtual void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) | Устанавливает глубину 3D-диаграммы в процентах от ширины диаграммы (от 20 до 2000 %). Запись **uint16_t**. |
| virtual void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) | Устанавливает высоту 3-D-диаграммы в процентах от ширины диаграммы (от 5 до 500 %). Запись **uint16_t**. |
| virtual void [set_Perspective](./set_perspective/)(**uint8_t**) | Устанавливает значение перспективы (угол угла обзора) для 3D-диаграмм (от 0 до 100). Игнорируется, если значение свойства RightAngleAxes равно true. Запись **uint8_t**. |
| virtual void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) | Определяет, находятся ли оси диаграммы под прямым углом, а не нарисованы в перспективе. Иными словами, определяет, независимы ли углы осей диаграммы от её вращения или наклона. Запись **bool**. |
| virtual void [set_RotationX](./set_rotationx/)(**int8_t**) | Устанавливает степень вращения вокруг оси X, т.е. в направлении Y для 3D-диаграмм (от -90 до 90 градусов). Свойство соответствует элементу 21.2.2.157 rotX (X Rotation) в ECMA-376 и опции «Y Rotation» в PowerPoint 2007+. Запись **int8_t**. |
| virtual void [set_RotationY](./set_rotationy/)(**uint16_t**) | Устанавливает степень вращения вокруг оси Y, т.е. в направлении X для 3D-диаграмм (от 0 до 360 градусов). Свойство соответствует элементу 21.2.2.158 rotY (Y Rotation) в ECMA-376 и опции «X Rotation» в PowerPoint 2007+. Запись **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не совместный). Позволяет переключать указатели в контейнерах в режим слабых ссылок. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкт typeof([System.Object](../../system/object/)) языка C#. |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывается напрямую или с использованием объекта-стража [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
## См. также

* Класс [Object](../../system/object/)
* Пространство имён [Aspose::Slides::Charts](../)
* Библиотека [Aspose.Slides](../../)