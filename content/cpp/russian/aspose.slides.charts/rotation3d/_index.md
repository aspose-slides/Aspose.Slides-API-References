---
title: Rotation3D
second_title: Aspose.Slides для C++ справочник API
description: Представляет 3D-поворот диаграммы.
type: docs
weight: 1327
url: /ru/aspose.slides.charts/rotation3d/
---
## Класс Rotation3D

Представляет 3D-поворот диаграммы.

```cpp
class Rotation3D : public Aspose::Slides::Charts::IRotation3D,
                   public Aspose::Slides::IDOMObject
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типа значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних нужд. |
| **uint16_t** [get_DepthPercents](./get_depthpercents/)() override | Возвращает глубину 3D-диаграммы в процентах от ширины диаграммы (от 20 до 2000 %). Чтение **uint16_t**. |
| **uint16_t** [get_HeightPercents](./get_heightpercents/)() override | Задает высоту 3-D-диаграммы в процентах от ширины диаграммы (от 5 до 500 %). Чтение **uint16_t**. |
| **uint8_t** [get_Perspective](./get_perspective/)() override | Возвращает значение перспективы (угол поля зрения) для 3D-диаграмм (от 0 до 240). Игнорируется, если свойство RightAngleAxes истинно. Чтение **uint8_t**. |
| **bool** [get_RightAngleAxes](./get_rightangleaxes/)() override | Определяет, находятся ли оси диаграммы под прямым углом, а не нарисованы в перспективе. Другими словами, определяет, независимы ли углы осей диаграммы от её поворота или наклона. Чтение **bool**. |
| **int8_t** [get_RotationX](./get_rotationx/)() override | Возвращает угол поворота вокруг оси X, t.e. в направлении Y для 3D-диаграмм (от -90 до 90 градусов). Свойство соответствует элементу 21.2.2.157 rotX (X Rotation) в ECMA-376 и опции "Y Rotation" в PowerPoint 2007+. Чтение **int8_t**. |
| **uint16_t** [get_RotationY](./get_rotationy/)() override | Возвращает угол поворота вокруг оси Y, t.e. в направлении X для 3D-диаграмм (от 0 до 360 градусов). Свойство соответствует элементу 21.2.2.158 rotY (Y Rotation) в ECMA-376 и опции "X Rotation" в PowerPoint 2007+. Чтение **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывается напрямую или с использованием охранного объекта [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, лишь инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, лишь инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект типа значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) override | Устанавливает глубину 3D-диаграммы в процентах от ширины диаграммы (от 20 до 2000 %). Запись **uint16_t**. |
| void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) override | Задает высоту 3-D-диаграммы в процентах от ширины диаграммы (от 5 до 500 %). Запись **uint16_t**. |
| void [set_Perspective](./set_perspective/)(**uint8_t**) override | Устанавливает значение перспективы (угол поля зрения) для 3D-диаграмм (от 0 до 240). Игнорируется, если свойство RightAngleAxes истинно. Запись **uint8_t**. |
| void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) override | Определяет, находятся ли оси диаграммы под прямым углом, а не нарисованы в перспективе. Другими словами, определяет, независимы ли углы осей диаграммы от её поворота или наклона. Запись **bool**. |
| void [set_RotationX](./set_rotationx/)(**int8_t**) override | Устанавливает угол поворота вокруг оси X, t.e. в направлении Y для 3D-диаграмм (от -90 до 90 градусов). Свойство соответствует элементу 21.2.2.157 rotX (X Rotation) в ECMA-376 и опции "Y Rotation" в PowerPoint 2007+. Запись **int8_t**. |
| void [set_RotationY](./set_rotationy/)(**uint16_t**) override | Устанавливает угол поворота вокруг оси Y, t.e. в направлении X для 3D-диаграмм (от 0 до 360 градусов). Свойство соответствует элементу 21.2.2.158 rotY (Y Rotation) в ECMA-376 и опции "X Rotation" в PowerPoint 2007+. Запись **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-ый аргумент шаблона как слабый указатель (a ne shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкт C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывается напрямую или с использованием охранного объекта [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [IRotation3D](../irotation3d/)
* Класс [IDOMObject](../../aspose.slides/idomobject/)
* Пространство имён [Aspose::Slides::Charts](../)
* Библиотека [Aspose.Slides](../../)