---
title: ISwfOptions
second_title: Aspose.Slides для C++ справочник API
description: Предоставляет параметры, которые контролируют, как презентация сохраняется в формате SWF.
type: docs
weight: 469
url: /ru/aspose.slides.export/iswfoptions/
---
## ISwfOptions класс

Provides options that control how a presentation is saved in SWF format.

```cpp
class ISwfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual **bool** [get_Compressed](./get_compressed/)() | Указывает, следует ли сжимать генерируемый SWF документ. По умолчанию **true**. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Возвращает шрифт, используемый в случае, если исходный шрифт не найден. Чтение [System::String](../../system/string/). |
| virtual **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() | Включить/выключить контекстное меню. По умолчанию **true**. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Возвращает визуальный стиль градиента. Чтение [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | Указывает качество JPEG-изображений. По умолчанию 95. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() | Изображение, которое будет отображено в качестве логотипа в правом верхнем углу просмотрщика.  

Изображение должно быть PNG размером 32x64 пикселей, иначе логотип может отображаться некорректно. |
| virtual [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() | Получает полный адрес гиперссылки для логотипа. Действует только если указан [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Представляет объект обратного вызова для сохранения обновлений прогресса в процентах. См. [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_ShowBottomPane](./get_showbottompane/)() | Показывать/скрывать нижнюю панель. Можно переопределить во flashvars. По умолчанию **true**. |
| virtual **bool** [get_ShowFullScreen](./get_showfullscreen/)() | Показывать/скрывать кнопку полноэкранного режима. Можно переопределить во flashvars. По умолчанию **true**. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | Указывает, следует ли включать скрытые слайды в генерируемый документ. По умолчанию **false**. |
| virtual **bool** [get_ShowLeftPane](./get_showleftpane/)() | Показывать/скрывать левую панель. Можно переопределить во flashvars. По умолчанию **true**. |
| virtual **bool** [get_ShowPageBorder](./get_showpageborder/)() | Указывает, следует ли показывать границу вокруг страниц. По умолчанию **true**. |
| virtual **bool** [get_ShowPageStepper](./get_showpagestepper/)() | Показывать/скрывать переключатель страниц. Можно переопределить во flashvars. По умолчанию **true**. |
| virtual **bool** [get_ShowSearch](./get_showsearch/)() | Показывать/скрывать секцию поиска. Можно переопределить во flashvars. По умолчанию **true**. |
| virtual **bool** [get_ShowTopPane](./get_showtoppane/)() | Показывать/скрывать всю верхнюю панель. Можно переопределить во flashvars. По умолчанию **true**. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Чтение **bool**. Значение по умолчанию **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | Получает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../islideslayoutoptions/). Это свойство не поддерживает назначение объектов типа **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** |
| virtual **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() | Запускать с открытой левой панелью. Можно переопределить во flashvars. По умолчанию **false**. |
| virtual **bool** [get_ViewerIncluded](./get_viewerincluded/)() | Указывает, следует ли включать интегрированный просмотрщик документов в генерируемый SWF документ. По умолчанию **true**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Возвращает объект, который получает предупреждения и решает, будет ли процесс загрузки продолжен или прерван. Чтение [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструктором подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструктором подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счетчик общих ссылок на указанное значение. |
| virtual void [set_Compressed](./set_compressed/)(**bool**) | Указывает, следует ли сжимать генерируемый SWF документ. По умолчанию **true**. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Устанавливает шрифт, используемый в случае, если исходный шрифт не найден. Записывает [System::String](../../system/string/). |
| virtual void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) | Включить/выключить контекстное меню. По умолчанию **true**. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Устанавливает визуальный стиль градиента. Запись [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | Указывает качество JPEG-изображений.  

По умолчанию 95. |
| virtual void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Изображение, которое будет отображено в качестве логотипа в правом верхнем углу просмотрщика.  

Изображение должно быть PNG размером 32x64 пикселей, иначе логотип может отображаться некорректно. |
| virtual void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) | Устанавливает полный адрес гиперссылки для логотипа. Действует только если указан [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Представляет объект обратного вызова для сохранения обновлений прогресса в процентах. См. [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShowBottomPane](./set_showbottompane/)(**bool**) | Показывать/скрывать нижнюю панель. Можно переопределить во flashvars. По умолчанию **true**. |
| virtual void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) | Показывать/скрывать кнопку полноэкранного режима. Можно переопределить во flashvars. По умолчанию **true**. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Указывает, следует ли включать скрытые слайды в генерируемый документ. По умолчанию **false**. |
| virtual void [set_ShowLeftPane](./set_showleftpane/)(**bool**) | Показывать/скрывать левую панель. Можно переопределить во flashvars. По умолчанию **true**. |
| virtual void [set_ShowPageBorder](./set_showpageborder/)(**bool**) | Указывает, следует ли показывать границу вокруг страниц. По умолчанию **true**. |
| virtual void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) | Показывать/скрывать переключатель страниц. Можно переопределить во flashvars. По умолчанию **true**. |
| virtual void [set_ShowSearch](./set_showsearch/)(**bool**) | Показывать/скрывать секцию поиска. Можно переопределить во flashvars. По умолчанию **true**. |
| virtual void [set_ShowTopPane](./set_showtoppane/)(**bool**) | Показывать/скрывать всю верхнюю панель. Можно переопределить во flashvars. По умолчанию **true**. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Указывает, следует ли пропускать гиперссылки с JavaScript вызовами при сохранении презентации. Запись **bool**. Значение по умолчанию **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | Устанавливает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../islideslayoutoptions/). Это свойство не поддерживает назначение объектов типа **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** |
| virtual void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) | Запускать с открытой левой панелью. Можно переопределить во flashvars. По умолчанию **false**. |
| virtual void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) | Указывает, следует ли включать интегрированный просмотрщик документов в генерируемый SWF документ. По умолчанию **true**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Устанавливает объект, который получает предупреждения и решает, будет ли процесс загрузки продолжен или прерван. Запись [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счетчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счетчик общих ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счетчик общих ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счетчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счетчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | Уничтожает объект. Очищает все внутренние структуры данных. |

## См. также

* Класс [ISaveOptions](../isaveoptions/)
* Пространство имён [Aspose::Slides::Export](../)
* Библиотека [Aspose.Slides](../../)