---
title: SVGOptions
second_title: Справочник API Aspose.Slides для C++
description: Представляет параметры SVG.
type: docs
weight: 703
url: /ru/aspose.slides.export/svgoptions/
---
## Класс SVGOptions

Представляет параметры SVG.

```cpp
class SVGOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISVGOptions
```

## Методы

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Default](./get_default/)() | Возвращает настройки по умолчанию. Только для чтения [SVGOptions](./). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Возвращает шрифт, используемый в случае, если исходный шрифт не найден. Читает [System::String](../../system/string/). |
| **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() override | Булевый флаг указывает, остаются ли обрезанные части частью документа. Если true, обрезанные части будут удалены, если false, они будут сериализованы в документе (что может привести к увеличению размера файла). |
| **bool** [get_Disable3DText](./get_disable3dtext/)() override | Определяет, отключён ли 3D-текст в SVG. Чтение **bool**. |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | Получает значение, указывающее, рендерится ли текст без использования лигатур. При установке в **true** лигатуры будут отключены в выводе. По умолчанию свойство имеет значение **false**. |
| **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() override | Отключает разделение градиентов FromCornerX и FromCenter. Чтение **bool**. |
| **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() override | В SVG 1.1 отсутствует возможность задавать отступы для маркеров. [Aspose.Slides](../../aspose.slides/) движок записи SVG имеет обходное решение этой проблемы: он обрезает конец линии со стрелкой, так линия не пересекает маркеры. Эта опция отключает такое поведение. Чтение **bool**. |
| [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() override | Определяет способ обработки загруженных извне шрифтов. Чтение [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Возвращает визуальный стиль градиента. Чтение [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Предоставляет параметры, управляющие внешним видом объектов [Ink](../../aspose.slides.ink/) в экспортированном документе. Только для чтения [IInkOptions](../iinkoptions/) |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | Определяет качество кодирования JPEG. Чтение **int32_t**. |
| **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() override | Возвращает нижний предел разрешения для растеризации метафайла. Чтение **int32_t**. |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | Представляет уровень сжатия изображений |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Представляет объект обратного вызова для сохранения обновлений прогресса в процентах. См. [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() override | Возвращает и задаёт интерфейс обратного вызова, позволяющий пользователю управлять преобразованием фигур. Чтение [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Simple](./get_simple/)() | Возвращает параметры для создания самого простого и маленького SVG-файла. Только для чтения [SVGOptions](./). |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Чтение **bool**. Значение по умолчанию — **false**. |
| **bool** [get_UseFrameRotation](./get_useframerotation/)() override | Определяет, выполнять ли указанное вращение фигуры при рендеринге. Чтение **bool**. Значение по умолчанию — **true**. |
| **bool** [get_UseFrameSize](./get_useframesize/)() override | Определяет, будет ли текстовый блок включён в область рендеринга. Чтение **bool**. Значение по умолчанию — **false**. |
| **bool** [get_VectorizeText](./get_vectorizetext/)() override | Определяет, будет ли текст на слайде сохранён как графика. Чтение **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Возвращает или задаёт объект, получающий предупреждения и определяющий, будет ли процесс загрузки продолжен или прерван. Чтение [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_WYSIWYG](./get_wysiwyg/)() | Возвращает параметры для наиболее точного создания SVG-файла. Только для чтения [SVGOptions](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанного с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-охранник [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Устанавливает шрифт, используемый в случае, если исходный шрифт не найден. Запись [System::String](../../system/string/). |
| void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) override | Булевый флаг указывает, остаются ли обрезанные части частью документа. Если true, обрезанные части будут удалены, если false, они будут сериализованы в документе (что может привести к увеличению размера файла). |
| void [set_Disable3DText](./set_disable3dtext/)(**bool**) override | Определяет, отключён ли 3D-текст в SVG. Запись **bool**. |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | Устанавливает значение, указывающее, рендерится ли текст без использования лигатур. При установке в **true** лигатуры будут отключены в выводе. По умолчанию свойство имеет значение **false**. |
| void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) override | Отключает разделение градиентов FromCornerX и FromCenter. Запись **bool**. |
| void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) override | В SVG 1.1 отсутствует возможность задавать отступы для маркеров. [Aspose.Slides](../../aspose.slides/) движок записи SVG имеет обходное решение этой проблемы: он обрезает конец линии со стрелкой, так линия не пересекает маркеры. Эта опция отключает такое поведение. Запись **bool**. |
| void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) override | Определяет способ обработки загруженных извне шрифтов. Запись [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Устанавливает визуальный стиль градиента. Запись [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | Определяет качество кодирования JPEG. Запись **int32_t**. |
| void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) override | Устанавливает нижний предел разрешения для растеризации метафайла. Запись **int32_t**. |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | Представляет уровень сжатия изображений |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Представляет объект обратного вызова для сохранения обновлений прогресса в процентах. См. [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) override | Возвращает и задаёт интерфейс обратного вызова, позволяющий пользователю управлять преобразованием фигур. Запись [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Запись **bool**. Значение по умолчанию — **false**. |
| void [set_UseFrameRotation](./set_useframerotation/)(**bool**) override | Определяет, выполнять ли указанное вращение фигуры при рендеринге. Запись **bool**. Значение по умолчанию — **true**. |
| void [set_UseFrameSize](./set_useframesize/)(**bool**) override | Определяет, будет ли текстовый блок включён в область рендеринга. Запись **bool**. Значение по умолчанию — **false**. |
| void [set_VectorizeText](./set_vectorizetext/)(**bool**) override | Определяет, будет ли текст на слайде сохранён как графика. Запись **bool**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Возвращает или задаёт объект, получающий предупреждения и определяющий, будет ли процесс загрузки продолжен или прерван. Запись [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
|  [SVGOptions](./svgoptions/)() | Инициализирует новый экземпляр класса [SVGOptions](./). |
|  [SVGOptions](./svgoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ILinkEmbedController](../ilinkembedcontroller/)\>) | Инициализирует новый экземпляр класса [SVGOptions](./), указывая объект контроллера внедрения ссылок. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-охранник [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [SaveOptions](../saveoptions/)
* Класс [ISVGOptions](../isvgoptions/)
* Пространство имён [Aspose::Slides::Export](../)
* Библиотека [Aspose.Slides](../../)