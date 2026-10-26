---
title: IVideoPlayerHtmlController
second_title: Справочник API Aspose.Slides для C++
description: Этот класс позволяет экспортировать видео- и аудиофайлы в HTML
type: docs
weight: 508
url: /ru/aspose.slides.export/ivideoplayerhtmlcontroller/
---
## IVideoPlayerHtmlController класс


Этот класс позволяет экспортировать видеофайлы и аудиофайлы в HTML

```cpp
class IVideoPlayerHtmlController : public Aspose::Slides::Export::IHtmlFormattingController,
                                   public Aspose::Slides::Export::ISvgShapeFormattingController,
                                   public Aspose::Slides::Export::ILinkEmbedController
```

## Методы

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa-значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual void [FormatShape](../isvgshapeformattingcontroller/formatshape/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShape](../isvgshape/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>) | Эта функция вызывается перед рендерингом фигуры в SVG, позволяя пользователю управлять полученным SVG. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual [LinkEmbedDecision](../linkembeddecision/) [GetObjectStoringLocation](../ilinkembedcontroller/getobjectstoringlocation/)(**int32_t**, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::String](../../system/string/), [System::String](../../system/string/), [System::String](../../system/string/)) | Определяет, где объект должен быть сохранён. Этот метод вызывается один раз для каждого идентификатора объекта. Не гарантируется, что не будет двух объектов с одинаковыми данными, semanticName и contentType, но с разными идентификаторами. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::String](../../system/string/) [GetUrl](../ilinkembedcontroller/geturl/)(**int32_t**, **int32_t**) | Возвращает URL внешнего объекта. Этот метод всегда вызывается, если [ILinkEmbedController::GetObjectStoringLocation](../ilinkembedcontroller/getobjectstoringlocation/) вернул [LinkEmbedDecision::Link](../linkembeddecision/), и может быть вызван, если [ILinkEmbedController::GetObjectStoringLocation](../ilinkembedcontroller/getobjectstoringlocation/) вернул [LinkEmbedDecision::Embed](../linkembeddecision/), но внедрение невозможно. Может вызываться многократно для одного и того же идентификатора объекта. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывается напрямую или с использованием объекта-сторожа [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, а лишь инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, а лишь инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual void [SaveExternal](../ilinkembedcontroller/saveexternal/)(**int32_t**, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Сохраняет внешний объект. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й параметр шаблона как слабый указатель (а не общедоступный). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывается напрямую или с использованием объект-сторожа [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual void [WriteDocumentEnd](../ihtmlformattingcontroller/writedocumentend/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>) | Вызывается для записи нижнего колонтитула HTML-документа. Вызывается один раз за конверсию презентации. |
| virtual void [WriteDocumentStart](../ihtmlformattingcontroller/writedocumentstart/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>) | Вызывается для записи заголовка HTML-документа. Вызывается один раз за конверсию презентации. |
| virtual void [WriteShapeEnd](../ihtmlformattingcontroller/writeshapeend/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>) | Вызывается перед рендерингом фигуры. Вызывается один раз для каждой фигуры. Если эта функция записывает что-либо в генератор, текущая генерация изображения слайда будет завершена, добавленный HTML-фрагмент вставлен, и новое изображение будет начато поверх предыдущего. |
| virtual void [WriteShapeStart](../ihtmlformattingcontroller/writeshapestart/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>) | Вызывается перед рендерингом фигуры. Вызывается один раз для каждой фигуры. Если эта функция записывает что-либо в генератор, текущая генерация изображения слайда будет завершена, добавленный HTML-фрагмент вставлен, и новое изображение будет начато поверх предыдущего. |
| virtual void [WriteSlideEnd](../ihtmlformattingcontroller/writeslideend/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../../aspose.slides/islide/)\>) | Вызывается для записи нижнего колонтитула HTML-слайда. Вызывается один раз для каждого слайда. |
| virtual void [WriteSlideStart](../ihtmlformattingcontroller/writeslidestart/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../../aspose.slides/islide/)\>) | Вызывается для записи заголовка HTML-слайда. Вызывается один раз для каждого слайда. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [IHtmlFormattingController](../ihtmlformattingcontroller/)
* Класс [ISvgShapeFormattingController](../isvgshapeformattingcontroller/)
* Класс [ILinkEmbedController](../ilinkembedcontroller/)
* Пространство имён [Aspose::Slides::Export](../)
* Библиотека [Aspose.Slides](../../)