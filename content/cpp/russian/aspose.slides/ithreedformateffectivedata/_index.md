---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides для C++ Справочник API
description: Неизменяемый объект, представляющий эффективные свойства 3-D форматирования.
type: docs
weight: 4174
url: /ru/aspose.slides/ithreedformateffectivedata/
---
## IThreeDFormatEffectiveData класс

Неизменяемый объект, представляющий эффективные свойства 3-D форматирования.

```cpp
class IThreeDFormatEffectiveData : public Aspose::Slides::IThreeDParamSource
```
## Методы

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типовых значений в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeBevelEffectiveData](../ishapebeveleffectivedata/)\> [get_BevelBottom](./get_bevelbottom/)() | Возвращает тип нижней 3D фаски. Только для чтения [IShapeBevelEffectiveData](../ishapebeveleffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeBevelEffectiveData](../ishapebeveleffectivedata/)\> [get_BevelTop](./get_beveltop/)() | Возвращает тип верхней 3D фаски. Только для чтения [IShapeBevelEffectiveData](../ishapebeveleffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICameraEffectiveData](../icameraeffectivedata/)\> [get_Camera](./get_camera/)() | Возвращает настройки камеры. Только для чтения [ICameraEffectiveData](../icameraeffectivedata/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_ContourColor](./get_contourcolor/)() | Возвращает цвет контура. Только для чтения [System::Drawing::Color](../../system.drawing/color/). |
| virtual **double** [get_ContourWidth](./get_contourwidth/)() | Возвращает ширину 3D контура. Только для чтения **double**. |
| virtual **double** [get_Depth](./get_depth/)() | Возвращает глубину 3D формы. Только для чтения **double**. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_ExtrusionColor](./get_extrusioncolor/)() | Возвращает цвет экструдирования. Только для чтения [System::Drawing::Color](../../system.drawing/color/). |
| virtual **double** [get_ExtrusionHeight](./get_extrusionheight/)() | Возвращает высоту эффекта экструдирования. Только для чтения **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILightRigEffectiveData](../ilightrigeffectivedata/)\> [get_LightRig](./get_lightrig/)() | Возвращает тип света. Только для чтения [ILightRigEffectiveData](../ilightrigeffectivedata/). |
| virtual [MaterialPresetType](../materialpresettype/) [get_Material](./get_material/)() | Возвращает тип материала. Только для чтения [MaterialPresetType](../materialpresettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Обеспечивает хеширование пользовательских объектов. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Обеспечивает клонирование пользовательских типов. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типового значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона в слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Обеспечивает преобразование пользовательских объектов в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
## Замечания

Этот интерфейс используется совместно с интерфейсом [IThreeDFormat](../ithreedformat/) для возврата эффективных значений форматирования с учётом наследования. 
## См. также

* Класс [IThreeDParamSource](../ithreedparamsource/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)