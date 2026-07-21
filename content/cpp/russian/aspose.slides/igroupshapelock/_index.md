---
title: IGroupShapeLock
second_title: Справочник API Aspose.Slides для C++
description: Определяет, какие операции отключены у родительского GroupShape.
type: docs
weight: 2497
url: /ru/aspose.slides/igroupshapelock/
---
## IGroupShapeLock класс


Определяет, какие операции отключены у родительского [GroupShape](../groupshape/).

```cpp
class IGroupShapeLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Определяет, должна ли фигура сохранять пропорции при изменении размера. Чтение **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Определяет, запрещено ли добавлять эту фигуру в группу. Чтение **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Возвращает true, если все флаги блокировки отключены. Только для чтения **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | Определяет, запрещено ли перемещение этой фигуры. Чтение **bool**. |
| virtual **bool** [get_RotationLocked](./get_rotationlocked/)() | Определяет, запрещена ли смена угла поворота этой фигуры. Чтение **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Определяет, запрещен ли выбор этой фигуры. Чтение **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Определяет, запрещено ли изменение размера этой фигуры. Чтение **bool**. |
| virtual **bool** [get_UngroupingLocked](./get_ungroupinglocked/)() | Определяет, запрещено ли разъединение этой групповой фигуры. Чтение **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-охранник [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект значимого типа с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Определяет, должна ли фигура сохранять пропорции при изменении размера. Запись **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Определяет, запрещено ли добавлять эту фигуру в группу. Запись **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | Определяет, запрещено ли перемещение этой фигуры. Запись **bool**. |
| virtual void [set_RotationLocked](./set_rotationlocked/)(**bool**) | Определяет, запрещена ли смена угла поворота этой фигуры. Запись **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Определяет, запрещен ли выбор этой фигуры. Запись **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Определяет, запрещено ли изменение размера этой фигуры. Запись **bool**. |
| virtual void [set_UngroupingLocked](./set_ungroupinglocked/)(**bool**) | Определяет, запрещено ли разъединение этой групповой фигуры. Запись **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим слабых. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает значение счётчика общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-охранник [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
## См. также

* Класс [IBaseShapeLock](../ibaseshapelock/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)