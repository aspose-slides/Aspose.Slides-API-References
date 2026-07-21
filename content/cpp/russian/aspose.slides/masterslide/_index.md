---
title: MasterSlide
second_title: Справочник API Aspose.Slides для C++
description: Представляет главный слайд в презентации.
type: docs
weight: 4473
url: /ru/aspose.slides/masterslide/
---
## MasterSlide класс


Представляет главный слайд в презентации.

```cpp
class MasterSlide : public Aspose::Slides::BaseSlide,
                    public Aspose::Slides::IMasterSlide
```

## Методы

| Метод | Описание |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\> [ApplyExternalThemeToDependingSlides](./applyexternalthemetodependingslides/)([System::String](../../system/string/)) override | Создает новый главный слайд на основе текущего, применяя к нему внешний шаблон, и применяет созданный главный слайд ко всем зависимым слайдам. |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../baseslide/createthemeeffective/)() override | Возвращает действующий шаблон для этого слайда. |
| **bool** [Equals](../baseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) override | Определяет, равны ли два экземпляра [IBaseSlide](../ibaseslide/). Возвращаемое значение рассчитывается на основе структуры слайда и статического контента. Два слайда равны, если все фигуры, стили, тексты, анимация и другие настройки и т.д. равны. При сравнении не учитываются уникальные идентификаторы, такие как SlideId, и динамический контент, например текущее значение даты в Date [Placeholder](../placeholder/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../baseslide/findshapebyalttext/)([System::String](../../system/string/)) override | Находит первое вхождение фигуры с указанным альтернативным текстом. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../baseslide/get_background/)() override | Возвращает фон слайда. Только для чтения [IBackground](../ibackground/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_BodyStyle](./get_bodystyle/)() override | Возвращает стиль основного текста. Только для чтения [ITextStyle](../itextstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../baseslide/get_control/)(**int32_t**) override | Возвращает элемент управления ActiveX по указанному индексу. |
| [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../baseslide/get_controls/)() override | Возвращает коллекцию элементов управления ActiveX на слайде. Только для чтения [IControlCollection](../icontrolcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../baseslide/get_customdata/)() override | Возвращает пользовательские данные слайда. Только для чтения [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDrawingGuidesCollection](../idrawingguidescollection/)\> [get_DrawingGuides](./get_drawingguides/)() override | Возвращает коллекцию направляющих рисования для главного слайда. Только для чтения [IDrawingGuidesCollection](../idrawingguidescollection/) |
| **bool** [get_HasDependingSlides](./get_hasdependingslides/)() override | Возвращает true, если существует хотя бы один слайд, зависящий от этого главного слайда. Только для чтения **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() override | Возвращает менеджер колонтитулов главного слайда. Только для чтения [IMasterSlideHeaderFooterManager](../imasterslideheaderfootermanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../baseslide/get_hyperlinkqueries/)() override | Обеспечивает простой доступ к содержащимся гиперссылкам. Только для чтения [IHyperlinkQueries](../ihyperlinkqueries/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)(**int32_t**) override | Возвращает дочерний макетный слайд для этого главного слайда по указанному индексу. Только для чтения [Aspose::Slides::ILayoutSlide](../ilayoutslide/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterLayoutSlideCollection](../imasterlayoutslidecollection/)\> [get_LayoutSlides](./get_layoutslides/)() override | Возвращает коллекцию дочерних макетных слайдов для этого главного слайда. Только для чтения [IMasterLayoutSlideCollection](../imasterlayoutslidecollection/). |
| [System::String](../../system/string/) [get_Name](./get_name/)() override | Возвращает имя главного слайда. Только для чтения [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_OtherStyle](./get_otherstyle/)() override | Возвращает стиль другого текста. Только для чтения [ITextStyle](../itextstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../baseslide/get_presentation/)() override | Возвращает интерфейс [IPresentation](../ipresentation/). Только для чтения [IPresentation](../ipresentation/). |
| **bool** [get_Preserve](./get_preserve/)() override | Определяет, будет ли соответствующий главный слайд удалён, когда все слайды, следующие за этим главным, будут удалены. Примечание: [Aspose.Slides](../) никогда сам не удалит неиспользуемый главный слайд; для фактического удаления неиспользуемых мастеров вызовите [MasterSlideCollection::RemoveUnused](../masterslidecollection/removeunused/). Только для чтения **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../baseslide/get_shape/)(**int32_t**) override | Возвращает фигуру по указанному индексу. Только для чтения [Aspose::Slides::IShape](../ishape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../baseslide/get_shapes/)() override | Возвращает фигуры слайда. Только для чтения [IShapeCollection](../ishapecollection/). |
| **bool** [get_ShowMasterShapes](./get_showmastershapes/)() override | Указывает, должны ли фигуры на главном слайде отображаться на слайдах или нет. Для самого главного слайда это свойство всегда возвращает **false**. Только для чтения **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Возвращает базовый слайд. Только для чтения [IBaseSlide](../ibaseslide/). |
| **uint32_t** [get_SlideId](../baseslide/get_slideid/)() override | Возвращает идентификатор слайда. Только для чтения **uint32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../baseslide/get_slideshowtransition/)() override | Возвращает объект Transition, содержащий информацию о том, как указанный слайд переходит в показе слайдов. Только для чтения [ISlideShowTransition](../islideshowtransition/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/)\> [get_ThemeManager](./get_thememanager/)() override | Возвращает менеджер шаблонов. Только для чтения [Theme::IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../baseslide/get_timeline/)() override | Возвращает объект анимационной временной шкалы. Только для чтения [IAnimationTimeLine](../ianimationtimeline/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TitleStyle](./get_titlestyle/)() override | Возвращает стиль заголовочного текста. Только для чтения [ITextStyle](../itextstyle/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [GetDependingSlides](./getdependingslides/)() override | Возвращает массив со всеми слайдами, зависящими от этого главного слайда. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)() override | Объединяет отрезки с одинаковым форматированием во всех абзацах всех допустимых фигур. |
| virtual void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\>) | Объединяет отрезки с одинаковым форматированием во всех абзацах во всех допустимых фигурках. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызовите напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счетчик общих ссылок на указанное значение. |
| void [set_Name](./set_name/)([System::String](../../system/string/)) override | Устанавливает имя главного слайда. Запись [System::String](../../system/string/). |
| void [set_Preserve](./set_preserve/)(**bool**) override | Определяет, будет ли соответствующий главный слайд удалён, когда все слайды, следующие за этим мастером, будут удалены. Примечание: [Aspose.Slides](../) никогда сам не удалит неиспользуемый главный слайд; для фактического удаления неиспользуемых мастеров вызовите [MasterSlideCollection::RemoveUnused](../masterslidecollection/removeunused/). Запись **bool**. |
| void [set_ShowMasterShapes](./set_showmastershapes/)(**bool**) override | Указывает, должны ли фигуры на главном слайде отображаться на слайдах или нет. Для самого главного слайда это свойство всегда возвращает **false**. Запись **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й параметр шаблона как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счетчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счетчик общих ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счетчик общих ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызовите напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счетчик слабых ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счетчик слабых ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [BaseSlide](../baseslide/)
* Класс [IMasterSlide](../imasterslide/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)