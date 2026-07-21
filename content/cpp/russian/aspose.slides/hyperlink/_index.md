---
title: Hyperlink
second_title: Справочная документация API Aspose.Slides для C++
description: Представляет гиперссылку.
type: docs
weight: 1236
url: /ru/aspose.slides/hyperlink/
---
## Класс Hyperlink

Представляет гиперссылку.

```cpp
class Hyperlink : public Aspose::Slides::PVIObject,
                  public Aspose::Slides::IHyperlink
```

## Методы

| Метод | Описание |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Определяет, равны ли два экземпляра [Hyperlink](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [HyperlinkActionType](../hyperlinkactiontype/) [get_ActionType](./get_actiontype/)() override | Возвращает тип действия [Hyperlink](./). Только для чтения [HyperlinkActionType](../hyperlinkactiontype/). |
| [HyperlinkColorSource](../hyperlinkcolorsource/) [get_ColorSource](./get_colorsource/)() override | Представляет источник цвета гиперссылки — стили или формат части. Читать [HyperlinkColorSource](../hyperlinkcolorsource/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_EndShow](./get_endshow/)() | Возвращает гиперссылку, завершающую показ. Только для чтения [Hyperlink](./). |
| [System::String](../../system/string/) [get_ExternalUrl](./get_externalurl/)() override | Указывает внешний URL. Только для чтения [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ExternalUrlOriginal](./get_externalurloriginal/)() override | Представляет гиперссылку, установленную для этой части без учета фактического содержимого части. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_FirstSlide](./get_firstslide/)() | Возвращает гиперссылку на первый слайд презентации. Только для чтения [Hyperlink](./). |
| **bool** [get_HighlightClick](./get_highlightclick/)() override | Определяет, должна ли гиперссылка подсвечиваться при щелчке. Читать **bool**. |
| **bool** [get_History](./get_history/)() override | Определяет, будет ли цель родительской гиперссылки добавлена в список просмотренных гиперссылок при её вызове. Читать **bool**. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_LastSlide](./get_lastslide/)() | Возвращает гиперссылку на последний слайд презентации. Только для чтения [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_LastVievedSlide](./get_lastvievedslide/)() | Возвращает гиперссылку на последний просмотренный слайд. Только для чтения [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_Media](./get_media/)() | Возвращает специальную гиперссылку «воспроизвести медиафайл». Используется в [AudioFrame](../audioframe/) и [VideoFrame](../videoframe/). Только для чтения [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_NextSlide](./get_nextslide/)() | Возвращает гиперссылку на следующий слайд. Только для чтения [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_NoAction](./get_noaction/)() | Возвращает специальную гиперссылку «ничего не делать». Только для чтения [Hyperlink](./). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Возвращает родительский [IPresentationComponent](../ipresentationcomponent/). Только для чтения [IPresentationComponent](../ipresentationcomponent/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_PreviousSlide](./get_previousslide/)() | Возвращает гиперссылку на предыдущий слайд. Только для чтения [Hyperlink](./). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() override | Представляет воспроизводимый звук гиперссылки. Читать [IAudio](../iaudio/). |
| **bool** [get_StopSoundOnClick](./get_stopsoundonclick/)() override | Определяет, должен ли звук останавливаться при щелчке по гиперссылке. Читать **bool**. |
| [System::String](../../system/string/) [get_TargetFrame](./get_targetframe/)() override | Возвращает фрейм в родительском наборе HTML-фреймов для цели родительской гиперссылки, если он существует. Чтение/запись [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() override | Если [Hyperlink](./) указывает на конкретный слайд, возвращает этот слайд. Только для чтения [ISlide](../islide/). |
| [System::String](../../system/string/) [get_Tooltip](./get_tooltip/)() override | Возвращает строку, которая может отображаться в пользовательском интерфейсе как ассоциированная с родительской гиперссылкой. Читать [System::String](../../system/string/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счетчика ссылок, связанную с объектом. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Служит в качестве хеш-функции для конкретного типа, пригодной для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
|  [Hyperlink](./hyperlink/)([System::String](../../system/string/)) | Создает экземпляр гиперссылки. |
|  [Hyperlink](./hyperlink/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) | Создает экземпляр гиперссылки, указывающий на конкретный слайд. Примечание: созданную гиперссылку следует назначить объекту из той же презентации, иначе ссылка будет сохранена как NoAction. |
|  [Hyperlink](./hyperlink/)([System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\>, [System::String](../../system/string/), [System::String](../../system/string/), **bool**, **bool**, **bool**) | Создает экземпляр гиперссылки, используя другую гиперссылку в качестве источника, переопределяя вторичные свойства. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывается напрямую или с использованием охранного объекта [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счетчик совместных ссылок на указанное значение. |
| void [set_ColorSource](./set_colorsource/)([HyperlinkColorSource](../hyperlinkcolorsource/)) override | Представляет источник цвета гиперссылки — стили или формат части. Записать [HyperlinkColorSource](../hyperlinkcolorsource/). |
| void [set_HighlightClick](./set_highlightclick/)(**bool**) override | Определяет, должна ли гиперссылка подсвечиваться при щелчке. Записать **bool**. |
| void [set_History](./set_history/)(**bool**) override | Определяет, будет ли цель родительской гиперссылки добавлена в список просмотренных гиперссылок при её вызове. Записать **bool**. |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | Представляет воспроизводимый звук гиперссылки. Записать [IAudio](../iaudio/). |
| void [set_StopSoundOnClick](./set_stopsoundonclick/)(**bool**) override | Определяет, должен ли звук останавливаться при щелчке по гиперссылке. Записать **bool**. |
| void [set_TargetFrame](./set_targetframe/)([System::String](../../system/string/)) override | Возвращает фрейм в родительском наборе HTML-фреймов для цели родительской гиперссылки, если он существует. Чтение/запись [System::String](../../system/string/). |
| void [set_Tooltip](./set_tooltip/)([System::String](../../system/string/)) override | Возвращает строку, которая может отображаться в пользовательском интерфейсе как ассоциированная с родительской гиперссылкой. Записать [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не общий). Позволяет переключать указатели в контейнерах в режим слабых. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счетчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счетчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает значение счетчика совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывается напрямую или с использованием охранного объекта [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [PVIObject](../pviobject/)
* Класс [IHyperlink](../ihyperlink/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)