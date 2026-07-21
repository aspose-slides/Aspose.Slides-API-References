---
title: SmartArtNode
second_title: Справочник API Aspose.Slides для C++
description: Представляет узел объекта SmartArt
type: docs
weight: 79
url: /ru/aspose.slides.smartart/smartartnode/
---
## SmartArtNode класс

Представляет узел объекта [SmartArt](../smartart/) 

```cpp
class SmartArtNode : public Aspose::Slides::SmartArt::ISmartArtNode
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типовых значений в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_BulletFillFormat](./get_bulletfillformat/)() override | Возвращает объект [FillFormat](../../aspose.slides/fillformat/), содержащий свойства заливки для марки узла. Примечание: может вернуть null для некоторых типов макета [SmartArt](../smartart/), которые не предоставляют маркеры для узлов. Только для чтения [IFillFormat](../../aspose.slides/ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_ChildNode](./get_childnode/)(**int32_t**) override | Возвращает дочерний узел данного узла по указанному индексу. Только для чтения [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_ChildNodes](./get_childnodes/)() override | Возвращает коллекцию всех дочерних узлов текущего узла. Только для чтения [ISmartArtNodeCollection](../ismartartnodecollection/). |
| **bool** [get_IsAssistant](./get_isassistant/)() override | Возвращает узел как помощник. Чтение **bool**. |
| **bool** [get_IsHidden](./get_ishidden/)() override | Возвращает true, если этот узел скрыт в модели данных. Только для чтения **bool**. |
| **int32_t** [get_Level](./get_level/)() override | Возвращает уровень вложенности узла. Только для чтения **int32_t**. |
| [OrganizationChartLayoutType](../organizationchartlayouttype/) [get_OrganizationChartLayout](./get_organizationchartlayout/)() override | Возвращает тип макета организационной схемы, связанный с текущим узлом. Чтение [OrganizationChartLayoutType](../organizationchartlayouttype/). |
| **int32_t** [get_Position](./get_position/)() override | Возвращает позицию узла среди соседних узлов, начиная с нуля. Чтение **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtShape](../ismartartshape/)\> [get_Shape](./get_shape/)(**int32_t**) override | Возвращает форму, связанную с этим узлом по указанному индексу. Только для чтения [Aspose::Slides::SmartArt::ISmartArtShape](../ismartartshape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtShapeCollection](../ismartartshapecollection/)\> [get_Shapes](./get_shapes/)() override | Возвращает коллекцию всех форм, связанных с узлом. Только для чтения [ISmartArtShapeCollection](../ismartartshapecollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrame](./get_textframe/)() override | Возвращает текстовый кадр узла. Только для чтения [ITextFrame](../../aspose.slides/itextframe/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект типового значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| **bool** [Remove](./remove/)() override | Удаляет текущий узел. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счетчик совместных ссылок на указанное значение. |
| void [set_IsAssistant](./set_isassistant/)(**bool**) override | Устанавливает узел как помощника. Запись **bool**. |
| void [set_OrganizationChartLayout](./set_organizationchartlayout/)([OrganizationChartLayoutType](../organizationchartlayouttype/)) override | Устанавливает тип макета организационной схемы, связанный с текущим узлом. Запись [OrganizationChartLayoutType](../organizationchartlayouttype/). |
| void [set_Position](./set_position/)(**int32_t**) override | Устанавливает позицию узла среди соседних узлов, начиная с нуля. Запись **int32_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Задает n-й аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счетчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счетчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счетчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Смотрите также

* Класс [ISmartArtNode](../ismartartnode/)
* Пространство имён [Aspose::Slides::SmartArt](../)
* Библиотека [Aspose.Slides](../../)