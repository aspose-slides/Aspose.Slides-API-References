---
title: IPictureFrameLock
second_title: Aspose.Slides для C++ справочник API
description: Определяет, какие операции отключены у родительского PictureFrameEx.
type: docs
weight: 3264
url: /ru/aspose.slides/ipictureframelock/
---
## IPictureFrameLock класс

Определяет, какие операции отключены у родительского PictureFrameEx.

```cpp
class IPictureFrameLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Методы

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних нужд. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | Определяет, запрещено ли изменение значений корректировки. Читает **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | Определяет, запрещено ли изменение стрелок. Читает **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Определяет, должна ли форма сохранять соотношение сторон при изменении размера. Читает **bool**. |
| virtual **bool** [get_CropLocked](./get_croplocked/)() | Определяет, запрещено ли обрезание изображения. Читает **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | Определяет, запрещено ли прямое изменение контура этой формы. Читает **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Определяет, запрещено ли добавление этой формы в группу. Читает **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Возвращает true, если все флаги блокировки отключены. Только для чтения **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | Определяет, запрещено ли перемещение этой формы. Читает **bool**. |
| virtual **bool** [get_RotationLocked](./get_rotationlocked/)() | Определяет, запрещено ли изменение угла вращения этой формы. Читает **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Определяет, запрещено ли выбор этой формы. Читает **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | Определяет, запрещено ли изменение типа формы. Читает **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Определяет, запрещено ли изменение размера этой формы. Читает **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Возвращает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Возвращает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку, аналог C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типа значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | Определяет, запрещено ли изменение значений корректировки. Записывает **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | Определяет, запрещено ли изменение стрелок. Записывает **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Определяет, должна ли форма сохранять соотношение сторон при изменении размера. Записывает **bool**. |
| virtual void [set_CropLocked](./set_croplocked/)(**bool**) | Определяет, запрещено ли обрезание изображения. Записывает **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | Определяет, запрещено ли прямое изменение контура этой формы. Записывает **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Определяет, запрещено ли добавление этой формы в группу. Записывает **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | Определяет, запрещено ли перемещение этой формы. Записывает **bool**. |
| virtual void [set_RotationLocked](./set_rotationlocked/)(**bool**) | Определяет, запрещено ли изменение угла вращения этой формы. Записывает **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Определяет, запрещено ли выбор этой формы. Записывает **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | Определяет, запрещено ли изменение типа формы. Записывает **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Определяет, запрещено ли изменение размера этой формы. Записывает **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Возвращает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет конвертировать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку, аналог C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
## См. также

* Class [IBaseShapeLock](../ibaseshapelock/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)