---
title: Slide
second_title: Aspose.Slides для C++ справочник API
description: Представляет слайд в презентации.
type: docs
weight: 5175
url: /ru/aspose.slides/slide/
---
## Slide класс

Represents a slide in a presentation.

```cpp
class Slide : public Aspose::Slides::BaseSlide,
              public Aspose::Slides::ISlide
```

## Методы

| Метод | Описание |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../baseslide/createthemeeffective/)() override | Возвращает применяемую тему для этого слайда. |
| **bool** [Equals](../baseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) override | Определяет, равны ли два экземпляра [IBaseSlide](../ibaseslide/). Возвращаемое значение вычисляется на основе структуры слайда и статического содержимого. Два слайда считаются равными, если все формы, стили, тексты, анимация и другие параметры и т.д. равны. При сравнении не учитываются уникальные значения идентификаторов, например SlideId, и динамическое содержимое, например текущее значение даты в Date [Placeholder](../placeholder/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равно никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равно никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../baseslide/findshapebyalttext/)([System::String](../../system/string/)) override | Ищет первое вхождение фигуры с указанным альтернативным текстом. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../baseslide/get_background/)() override | Возвращает фон слайда. Только для чтения [IBackground](../ibackground/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../baseslide/get_control/)(**int32_t**) override | Возвращает элемент управления ActiveX по указанному индексу. |
| [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../baseslide/get_controls/)() override | Возвращает коллекцию элементов управления ActiveX на слайде. Только для чтения [IControlCollection](../icontrolcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../baseslide/get_customdata/)() override | Возвращает пользовательские данные слайда. Только для чтения [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideHeaderFooterManager](../islideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() override | Возвращает менеджер HeaderFooter слайда. Только для чтения [ISlideHeaderFooterManager](../islideheaderfootermanager/). |
| **bool** [get_Hidden](./get_hidden/)() override | Определяет, скрыт ли указанный слайд во время показа. Читает **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../baseslide/get_hyperlinkqueries/)() override | Обеспечивает простой доступ к содержащимся гиперссылкам. Только для чтения [IHyperlinkQueries](../ihyperlinkqueries/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)() override | Возвращает слайд макета для текущего слайда. Читает [ILayoutSlide](../ilayoutslide/). |
| [System::String](../../system/string/) [get_Name](../baseslide/get_name/)() override | Возвращает имя слайда. Читает [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[INotesSlideManager](../inotesslidemanager/)\> [get_NotesSlideManager](./get_notesslidemanager/)() override | Позволяет получать доступ к слайду заметок, добавлять и удалять его. Только для чтения [INotesSlideManager](../inotesslidemanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../baseslide/get_presentation/)() override | Возвращает интерфейс [IPresentation](../ipresentation/). Только для чтения [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../baseslide/get_shape/)(**int32_t**) override | Возвращает фигуру по указанному индексу. Только для чтения [Aspose::Slides::IShape](../ishape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../baseslide/get_shapes/)() override | Возвращает формы слайда. Только для чтения [IShapeCollection](../ishapecollection/). |
| **bool** [get_ShowMasterShapes](./get_showmastershapes/)() override | Указывает, должны ли формы на мастер-слайде отображаться на слайдах или нет. Читает **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Возвращает базовый слайд. Только для чтения [IBaseSlide](../ibaseslide/). |
| **uint32_t** [get_SlideId](../baseslide/get_slideid/)() override | Возвращает ID слайда. Только для чтения **uint32_t**. |
| **int32_t** [get_SlideNumber](./get_slidenumber/)() override | Возвращает номер слайда. Индекс слайда в [Presentation::get_Slides()](../presentation/get_slides/) коллекции всегда равен SlideNumber - Presentation::get(set)_FirstSlideNumber. Читает **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../baseslide/get_slideshowtransition/)() override | Возвращает объект Transition, содержащий информацию о том, как указанный слайд переходит в следующем показе. Только для чтения [ISlideShowTransition](../islideshowtransition/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](./get_thememanager/)() override | Возвращает менеджер переопределяющей темы. Только для чтения [Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../baseslide/get_timeline/)() override | Возвращает объект таймлайна анимации. Только для чтения [IAnimationTimeLine](../ianimationtimeline/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет вычислять хеш пользовательских объектов. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)(**float**, **float**) override | Возвращает объект Thumbnail Image с пользовательским масштабированием. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)() override | Возвращает объект Thumbnail Image (20% от реального размера). |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::Drawing::Size](../../system.drawing/size/)) override | Возвращает объект Thumbnail Image с указанным размером. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::SharedPtr](../../system/sharedptr/)\<[Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>) override | Возвращает объект TIFF-изображения Thumbnail с указанными параметрами. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) override | Возвращает объект Thumbnail Image. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, **float**, **float**) override | Возвращает объект Thumbnail Image с пользовательским масштабированием. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::Drawing::Size](../../system.drawing/size/)) override | Возвращает объект Thumbnail Image с указанным размером. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>\> [GetSlideComments](./getslidecomments/)([System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\>) override | Возвращает все комментарии к слайду, добавленные определённым автором. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() override | Объединяет участки с одинаковым форматированием во всех абзацах всех подходящих фигур. |
| virtual void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\>) | Объединяет участки с одинаковым форматированием во всех абзацах всех подходящих фигур. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| void [Remove](./remove/)() override | Удаляет слайд из презентации. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик разделяемых ссылок на указанное значение. |
| void [Reset](./reset/)() override | Сбрасывает позицию, размер и форматирование каждой фигуры, имеющей прототип на [LayoutSlide](../layoutslide/). |
| void [set_Hidden](./set_hidden/)(**bool**) override | Определяет, скрыт ли указанный слайд во время показа. Записывает **bool**. |
| void [set_LayoutSlide](./set_layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>) override | Устанавливает слайд макета для текущего слайда. Записывает [ILayoutSlide](../ilayoutslide/). |
| void [set_Name](../baseslide/set_name/)([System::String](../../system/string/)) override | Устанавливает имя слайда. Записывает [System::String](../../system/string/). |
| void [set_ShowMasterShapes](./set_showmastershapes/)(**bool**) override | Указывает, должны ли формы на мастер-слайде отображаться на слайдах или нет. Записывает **bool**. |
| void [set_SlideNumber](./set_slidenumber/)(**int32_t**) override | Возвращает номер слайда. Индекс слайда в [Presentation::get_Slides()](../presentation/get_slides/) коллекции всегда равен SlideNumber - Presentation::get(set)_FirstSlideNumber. Записывает **int32_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Задаёт n-й шаблонный параметр как слабый указатель (а не разделяемый). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика разделяемых ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик разделяемых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик разделяемых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WriteAsEmf](./writeasemf/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Сохраняет содержимое слайда в файл EMF. |
| void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Сохраняет содержимое слайда в файл SVG. |
| void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Сохраняет содержимое слайда в файл SVG. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Смотрите также

* Класс [BaseSlide](../baseslide/)
* Класс [ISlide](../islide/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)