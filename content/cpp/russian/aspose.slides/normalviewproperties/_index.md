---
title: NormalViewProperties
second_title: "Aspose.Slides для C++ справочник API"
description: "Представляет свойства обычного просмотра. Обычный просмотр состоит из трёх областей содержимого: самого слайда, боковой области содержимого и нижней области содержимого."
type: docs
weight: 4525
url: /ru/aspose.slides/normalviewproperties/
---
## NormalViewProperties класс

Представляет свойства обычного просмотра. Обычный просмотр состоит из трёх областей содержимого: самого слайда, боковой области содержимого и нижней области содержимого.

```cpp
class NormalViewProperties : public Aspose::Slides::INormalViewProperties
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты с использованием семантики C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типовых значений в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| [SplitterBarStateType](../splitterbarstatetype/) [get_HorizontalBarState](./get_horizontalbarstate/)() override | Указывает состояние, в котором должна отображаться горизонтальная разделительная полоса. Горизонтальная разделительная полоса отделяет слайд от области содержимого под слайдом. |
| **bool** [get_PreferSingleView](./get_prefersingleview/)() override | Указывает, предпочитает ли пользователь видеть в окне одну область содержимого вместо стандартного обычного просмотра с тремя областями. Если включено, приложение может отобразить одну из областей содержимого во всём окне. Чтение **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredLeft](./get_restoredleft/)() override | Этот элемент задаёт размер боковой области содержимого обычного просмотра, когда область имеет переменный восстановленный размер (не свернута и не развернута). Только для чтения [INormalViewRestoredProperties](../inormalviewrestoredproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredTop](./get_restoredtop/)() override | Этот элемент задаёт размер верхней области слайда обычного просмотра, когда область имеет переменный восстановленный размер (не свернута и не развернута). Только для чтения [INormalViewRestoredProperties](../inormalviewrestoredproperties/). |
| **bool** [get_ShowOutlineIcons](./get_showoutlineicons/)() override | Указывает, должна ли приложение показывать значки при отображении содержания конспекта в любой из областей содержимого в режиме обычного просмотра. Чтение **bool**. |
| **bool** [get_SnapVerticalSplitter](./get_snapverticalsplitter/)() override | Указывает, должна ли вертикальная разделительная полоса переходить в состояние свернутости, когда боковая область достаточно мала. Чтение **bool**. |
| [SplitterBarStateType](../splitterbarstatetype/) [get_VerticalBarState](./get_verticalbarstate/)() override | Указывает состояние, в котором должна отображаться вертикальная разделительная полоса. Вертикальная разделительная полоса отделяет слайд от боковой области содержимого. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного целевым типом. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкцию подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкцию подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типового значения со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [set_HorizontalBarState](./set_horizontalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) override | Указывает состояние, в котором должна отображаться горизонтальная разделительная полоса. Горизонтальная разделительная полоса отделяет слайд от области содержимого под слайдом. |
| void [set_PreferSingleView](./set_prefersingleview/)(**bool**) override | Указывает, предпочитает ли пользователь видеть в окне одну область содержимого вместо стандартного обычного просмотра с тремя областями. Если включено, приложение может отобразить одну из областей содержимого во всём окне. Записать **bool**. |
| void [set_ShowOutlineIcons](./set_showoutlineicons/)(**bool**) override | Указывает, должна ли приложение показывать значки при отображении содержания конспекта в любой из областей содержимого в режиме обычного просмотра. Записать **bool**. |
| void [set_SnapVerticalSplitter](./set_snapverticalsplitter/)(**bool**) override | Указывает, должна ли вертикальная разделительная полоса переходить в состояние свернутости, когда боковая область достаточно мала. Записать **bool**. |
| void [set_VerticalBarState](./set_verticalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) override | Указывает состояние, в котором должна отображаться вертикальная разделительная полоса. Вертикальная разделительная полоса отделяет слайд от боковой области содержимого. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n't-й аргумент шаблона в виде слабой ссылки (а не совместной). Позволяет переключать указатели в контейнерах в режим слабой ссылки. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает значение счётчика совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Примечания

Следующий пример показывает, как настроить свойства [ViewProperties::get_NormalViewProperties](../viewproperties/get_normalviewproperties/) в PowerPoint [Presentation](../presentation/).
```cpp
// Создать объект презентации, представляющий файл презентации
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto normalViewProperties = pres->get_ViewProperties()->get_NormalViewProperties();

normalViewProperties->set_HorizontalBarState(SplitterBarStateType::Restored);
normalViewProperties->set_VerticalBarState(SplitterBarStateType::Maximized);
normalViewProperties->get_RestoredTop()->set_AutoAdjust(true);
normalViewProperties->get_RestoredTop()->set_DimensionSize(80.0f);
normalViewProperties->set_ShowOutlineIcons(true);
pres->Save(u"presentation_normal_view_state.pptx", SaveFormat::Pptx);
```

## См. также

* Класс [INormalViewProperties](../inormalviewproperties/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)