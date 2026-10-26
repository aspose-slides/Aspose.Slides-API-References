---
title: AutoShapeLock
second_title: Aspose.Slides для C++ справочник API
description: Определяет, какие операции отключены у родительского AutoshapeEx.
type: docs
weight: 79
url: /ru/aspose.slides/autoshapelock/
---
## AutoShapeLock класс


Определяет, какие операции отключены у родительского AutoshapeEx.

```cpp
class AutoShapeLock : public Aspose::Slides::BaseShapeLock,
                      public Aspose::Slides::IAutoShapeLock
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типа значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | Определяет, запрещено ли изменение значений настройки. Чтение **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | Определяет, запрещено ли изменение стрелок. Чтение **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Определяет, должна ли форма сохранять пропорции при изменении размера. Чтение **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | Определяет, запрещено ли прямое изменение контура этой формы. Чтение **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Определяет, запрещено ли добавление этой формы в группу. Чтение **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Возвращает true, если все флаги блокировки отключены. Только для чтения **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Определяет, запрещено ли перемещение этой формы. Чтение **bool**. |
| **bool** [get_RotateLocked](./get_rotatelocked/)() override | Определяет, запрещено ли изменение угла вращения этой формы. Чтение **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Определяет, запрещено ли выбор этой формы. Чтение **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | Определяет, запрещено ли изменение типа формы. Чтение **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Определяет, запрещено ли изменение размера этой формы. Чтение **bool**. |
| **bool** [get_TextLocked](./get_textlocked/)() override | Определяет, запрещено ли редактирование текста. Чтение **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывается непосредственно или с использованием объекта-сторожа [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типового значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | Определяет, запрещено ли изменение значений настройки. Запись **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | Определяет, запрещено ли изменение стрелок. Запись **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Определяет, должна ли форма сохранять пропорции при изменении размера. Запись **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | Определяет, запрещено ли прямое изменение контура этой формы. Запись **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Определяет, запрещено ли добавление этой формы в группу. Запись **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Определяет, запрещено ли перемещение этой формы. Запись **bool**. |
| void [set_RotateLocked](./set_rotatelocked/)(**bool**) override | Определяет, запрещено ли изменение угла вращения этой формы. Запись **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Определяет, запрещено ли выбор этой формы. Запись **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | Определяет, запрещено ли изменение типа формы. Запись **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Определяет, запрещено ли изменение размера этой формы. Запись **bool**. |
| void [set_TextLocked](./set_textlocked/)(**bool**) override | Определяет, запрещено ли редактирование текста. Запись **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает значение счётчика совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывается напрямую или с использованием объекта-сторожа [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Разрушает объект. Освобождает все внутренние структуры данных. |

## Смотрите также

* Класс [BaseShapeLock](../baseshapelock/)
* Класс [IAutoShapeLock](../iautoshapelock/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)