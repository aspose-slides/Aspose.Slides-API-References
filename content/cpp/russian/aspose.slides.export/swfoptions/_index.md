---
title: SwfOptions
second_title: Справочник API Aspose.Slides для C++
description: Предоставляет параметры, управляющие тем, как презентация сохраняется в формате Swf.
type: docs
weight: 742
url: /ru/aspose.slides.export/swfoptions/
---
## SwfOptions класс


Предоставляет параметры, управляющие тем, как презентация сохраняется в формате Swf.

```cpp
class SwfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISwfOptions
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типа ссылки в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| **bool** [get_Compressed](./get_compressed/)() override | Указывает, следует ли сжимать сгенерированный документ SWF. По умолчанию **true**. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Возвращает шрифт, используемый в случае, если исходный шрифт не найден. Читает [System::String](../../system/string/). |
| **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() override | Включить/выключить контекстное меню. По умолчанию true. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Возвращает визуальный стиль градиента. Читает [GradientStyle](../../aspose.slides/gradientstyle/). |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | Указывает качество JPEG-изображений. По умолчанию 95. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() override | Изображение, которое будет отображаться как логотип в верхнем правом углу просмотрщика. Должно быть PNG-изображение 32×64 пикселей, иначе логотип может отображаться некорректно. |
| [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() override | Получает полную гиперссылку для логотипа. Действует только если указан [set_LogoImageBytes()](./set_logoimagebytes/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Представляет объект обратного вызова для сохранения прогресса в процентах. См. [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowBottomPane](./get_showbottompane/)() override | Показать/скрыть нижнюю панель. Может быть переопределено во flashvars. По умолчанию true. |
| **bool** [get_ShowFullScreen](./get_showfullscreen/)() override | Показать/скрыть кнопку полноэкранного режима. Может быть переопределено во flashvars. По умолчанию true. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Указывает, следует ли включать скрытые слайды в сгенерированный документ. По умолчанию **false**. |
| **bool** [get_ShowLeftPane](./get_showleftpane/)() override | Показать/скрыть левую панель. Может быть переопределено во flashvars. По умолчанию true. |
| **bool** [get_ShowPageBorder](./get_showpageborder/)() override | Указывает, следует ли показывать рамку вокруг страниц. По умолчанию true. |
| **bool** [get_ShowPageStepper](./get_showpagestepper/)() override | Показать/скрыть переключатель страниц. Может быть переопределено во flashvars. По умолчанию true. |
| **bool** [get_ShowSearch](./get_showsearch/)() override | Показать/скрыть раздел поиска. Может быть переопределено во flashvars. По умолчанию true. |
| **bool** [get_ShowTopPane](./get_showtoppane/)() override | Показать/скрыть всю верхнюю панель. Может быть переопределено во flashvars. По умолчанию true. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Читает **bool**. Значение по умолчанию **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Получает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../islideslayoutoptions/). Это свойство не поддерживает присваивание объектов типа [HandoutLayoutingOptions](../handoutlayoutingoptions/). |
| **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() override | Запускать с открытой левой панелью. Может быть переопределено во flashvars. По умолчанию false. |
| **bool** [get_ViewerIncluded](./get_viewerincluded/)() override | Указывает, следует ли включать в сгенерированный документ SWF интегрированный просмотрщик документов. По умолчанию **true**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Возвращает/устанавливает объект, получающий предупреждения и решающий, будет ли процесс загрузки продолжен или прерван. Читает [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# `is`. |
| void [Lock](../../system/object/lock/)() | Реализует поведение оператора C# lock() для блокировки. Вызывается напрямую или через объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, а лишь инициализирует новый объект и позволяет копировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, а лишь инициализирует новый объект и позволяет копировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект-значение с `nullptr`. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для строки и `nullptr`. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_Compressed](./set_compressed/)(**bool**) override | Указывает, следует ли сжимать сгенерированный документ SWF. По умолчанию **true**. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Устанавливает шрифт, используемый в случае, если исходный шрифт не найден. Записывает [System::String](../../system/string/). |
| void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) override | Включить/выключить контекстное меню. По умолчанию true. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Устанавливает визуальный стиль градиента. Записывает [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | Указывает качество JPEG-изображений. По умолчанию 95. |
| void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Изображение, которое будет отображаться как логотип в верхнем правом углу просмотрщика. Должно быть PNG-изображение 32×64 пикселей, иначе логотип может отображаться некорректно. |
| void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) override | Устанавливает полную гиперссылку для логотипа. Действует только если указан [set_LogoImageBytes()](./set_logoimagebytes/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Представляет объект обратного вызова для сохранения прогресса в процентах. См. [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowBottomPane](./set_showbottompane/)(**bool**) override | Показать/скрыть нижнюю панель. Может быть переопределено во flashvars. По умолчанию true. |
| void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) override | Показать/скрыть кнопку полноэкранного режима. Может быть переопределено во flashvars. По умолчанию true. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Указывает, следует ли включать скрытые слайды в сгенерированный документ. По умолчанию **false**. |
| void [set_ShowLeftPane](./set_showleftpane/)(**bool**) override | Показать/скрыть левую панель. Может быть переопределено во flashvars. По умолчанию true. |
| void [set_ShowPageBorder](./set_showpageborder/)(**bool**) override | Указывает, следует ли показывать рамку вокруг страниц. По умолчанию true. |
| void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) override | Показать/скрыть переключатель страниц. Может быть переопределено во flashvars. По умолчанию true. |
| void [set_ShowSearch](./set_showsearch/)(**bool**) override | Показать/скрыть раздел поиска. Может быть переопределено во flashvars. По умолчанию true. |
| void [set_ShowTopPane](./set_showtoppane/)(**bool**) override | Показать/скрыть всю верхнюю панель. Может быть переопределено во flashvars. По умолчанию true. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Записывает **bool**. Значение по умолчанию **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Устанавливает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../islideslayoutoptions/). Это свойство не поддерживает присваивание объектов типа [HandoutLayoutingOptions](../handoutlayoutingoptions/). |
| void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) override | Запускать с открытой левой панелью. Может быть переопределено во flashvars. По умолчанию false. |
| void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) override | Указывает, следует ли включать в сгенерированный документ SWF интегрированный просмотрщик документов. По умолчанию **true**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Возвращает/устанавливает объект, получающий предупреждения и решающий, будет ли процесс загрузки продолжен или прерван. Записывает [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не должен вызываться напрямую; используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не должен вызываться напрямую; используйте умные указатели или ThisProtector. |
|  [SwfOptions](./swfoptions/)() | Конструктор по умолчанию. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывается напрямую или через объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не должен вызываться напрямую; используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не должен вызываться напрямую; используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
## Замечания


Следующий пример демонстрирует, как преобразовать PowerPoint в SWF-Flash. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"HelloWorld.pptx");
auto swfOptions = System::MakeObject<SwfOptions>();

swfOptions->set_ViewerIncluded(false);
auto notesOptions = swfOptions->get_NotesCommentsLayouting();
notesOptions->set_NotesPosition(NotesPositions::BottomFull);

// Saving presentation and notes pages
presentation->Save(u"SaveAsSwf_out.swf", SaveFormat::Swf, swfOptions);
swfOptions->set_ViewerIncluded(true);
presentation->Save(u"SaveNotes_out.swf", SaveFormat::Swf, swfOptions);
```

## См. также

* Класс [SaveOptions](../saveoptions/)
* Класс [ISwfOptions](../iswfoptions/)
* Пространство имен [Aspose::Slides::Export](../)
* Библиотека [Aspose.Slides](../../)