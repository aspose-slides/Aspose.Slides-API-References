---
title: IAutoShapeLock
second_title: Aspose.Slides для C++ справочник API
description: Определяет, какие операции отключены у родительского AutoshapeEx.
type: docs
weight: 1379
url: /ru/aspose.slides/iautoshapelock/
---
## IAutoShapeLock класс


Determines which operations are disabled on the parent AutoshapeEx.

```cpp
class IAutoShapeLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | Определяет, запрещено ли изменение значений регулировки. Читает **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | Определяет, запрещено ли изменение стрелок. Читает **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Определяет, должна ли фигура сохранять соотношение сторон при изменении размера. Читает **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | Определяет, запрещено ли прямое изменение контура этой фигуры. Читает **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Определяет, запрещено ли добавление этой фигуры в группу. Читает **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Возвращает true, если все флаги блокировки отключены. Только для чтения **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | Определяет, запрещено ли перемещение этой фигуры. Читает **bool**. |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | Определяет, запрещено ли изменение угла вращения этой фигуры. Читает **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Определяет, запрещен ли выбор этой фигуры. Читает **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | Определяет, запрещено ли изменение типа фигуры. Читает **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Определяет, запрещено ли изменение размера этой фигуры. Читает **bool**. |
| virtual **bool** [get_TextLocked](./get_textlocked/)() | Определяет, запрещено ли редактирование текста. Читает **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывается напрямую или с помощью объекта-сторожа [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счетчик общих ссылок на указанное значение. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | Определяет, запрещено ли изменение значений регулировки. Записывает **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | Определяет, запрещено ли изменение стрелок. Записывает **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Определяет, должна ли фигура сохранять соотношение сторон при изменении размера. Записывает **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | Определяет, запрещено ли прямое изменение контура этой фигуры. Записывает **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Определяет, запрещено ли добавление этой фигуры в группу. Записывает **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | Определяет, запрещено ли перемещение этой фигуры. Записывает **bool**. |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | Определяет, запрещено ли изменение угла вращения этой фигуры. Записывает **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Определяет, запрещен ли выбор этой фигуры. Записывает **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | Определяет, запрещено ли изменение типа фигуры. Записывает **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Определяет, запрещено ли изменение размера этой фигуры. Записывает **bool**. |
| virtual void [set_TextLocked](./set_textlocked/)(**bool**) | Определяет, запрещено ли редактирование текста. Записывает **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не общий). Позволяет переключать указатели в контейнерах в режим слабых. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счетчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счетчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счетчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывается напрямую или с помощью объекта-сторожа [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [IBaseShapeLock](../ibaseshapelock/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)