---
title: BaseSlide
second_title: Aspose.Slides для C++ API справочное руководство
description: Представляет общие данные для всех типов слайдов.
type: docs
weight: 170
url: /ru/aspose.slides/baseslide/
---
## BaseSlide класс


Represents common data for all slide types.

```cpp
class BaseSlide : public virtual Aspose::Slides::IBaseSlide,
                  public Aspose::Slides::IDOMObject,
                  public Aspose::Slides::IStyleColorOwner
```

## Методы

| Метод | Описание |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](./createthemeeffective/)() override | Возвращает эффективную тему для этого слайда. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) override | Определяет, равны ли два экземпляра [IBaseSlide](../ibaseslide/). Возвращаемое значение вычисляется на основе структуры слайда и статического контента. Два слайда считаются равными, если все фигуры, стили, тексты, анимация и другие параметры и т.д. равны. При сравнении не учитываются уникальные идентификаторы, например SlideId, и динамический контент, например текущее значение даты в Date [Placeholder](../placeholder/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних нужд. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](./findshapebyalttext/)([System::String](../../system/string/)) override | Находит первое вхождение фигуры с указанным альтернативным текстом. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](./get_background/)() override | Возвращает фон слайда. Только для чтения [IBackground](../ibackground/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](./get_control/)(**int32_t**) override | Возвращает элемент управления ActiveX по указанному индексу. |
| [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](./get_controls/)() override | Возвращает коллекцию элементов управления ActiveX на слайде. Только для чтения [IControlCollection](../icontrolcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() override | Возвращает пользовательские данные слайда. Только для чтения [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](./get_hyperlinkqueries/)() override | Обеспечивает простой доступ к содержащимся гиперссылкам. Только для чтения [IHyperlinkQueries](../ihyperlinkqueries/). |
| [System::String](../../system/string/) [get_Name](./get_name/)() override | Возвращает имя слайда. Чтение [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | Возвращает интерфейс [IPresentation](../ipresentation/). Только для чтения [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)(**int32_t**) override | Возвращает фигуру по указанному индексу. Только для чтения [Aspose::Slides::IShape](../ishape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](./get_shapes/)() override | Возвращает фигуры слайда. Только для чтения [IShapeCollection](../ishapecollection/). |
| virtual **bool** [get_ShowMasterShapes](./get_showmastershapes/)() | Указывает, должны ли фигуры на слайде-мастере отображаться на слайдах или нет. Для самого слайда-мастера это свойство всегда возвращает **false**. Чтение **bool**. |
| **uint32_t** [get_SlideId](./get_slideid/)() override | Возвращает идентификатор слайда. Только для чтения **uint32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](./get_slideshowtransition/)() override | Возвращает объект Transition, содержащий информацию о том, как указанный слайд переходит во время показа. Только для чтения [ISlideShowTransition](../islideshowtransition/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](./get_timeline/)() override | Возвращает объект таймлайна анимации. Только для чтения [IAnimationTimeLine](../ianimationtimeline/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() override | Объединяет участки с одинаковым форматированием во всех абзацах всех приемлемых фигур. |
| virtual void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\>) | Объединяет участки с одинаковым форматированием во всех абзацах всех приемлемых фигур. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-охранник [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, только инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, только инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения со ссылкой nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [set_Name](./set_name/)([System::String](../../system/string/)) override | Задаёт имя слайда. Запись [System::String](../../system/string/). |
| virtual void [set_ShowMasterShapes](./set_showmastershapes/)(**bool**) | Указывает, должны ли фигуры на слайде-мастере отображаться на слайдах или нет. Для самого слайда-мастера это свойство всегда возвращает **false**. Запись **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-ый аргумент шаблона как слабый указатель (а не разделяемый). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-охранник [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [IBaseSlide](../ibaseslide/)
* Класс [IDOMObject](../idomobject/)
* Класс [IStyleColorOwner](../istylecolorowner/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)