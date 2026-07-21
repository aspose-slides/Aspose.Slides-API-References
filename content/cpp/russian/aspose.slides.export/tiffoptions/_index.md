---
title: TiffOptions
second_title: Справочник API Aspose.Slides для C++
description: Предоставляет параметры, контролирующие способ сохранения презентации в формате TIFF.
type: docs
weight: 768
url: /ru/aspose.slides.export/tiffoptions/
---
## TiffOptions class

Предоставляет параметры, контролирующие способ сохранения презентации в формате TIFF.

```cpp
class TiffOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::ITiffOptions
```

## Methods

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типовых значений в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [BlackWhiteConversionMode](../blackwhiteconversionmode/) [get_BwConversionMode](./get_bwconversionmode/)() override | Указывает алгоритм преобразования цветного изображения в черно-белое. Этот параметр будет применяться только если [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) установлен в [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) или [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/). Чтение [BlackWhiteConversionMode](../blackwhiteconversionmode/). По умолчанию [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/). |
| [TiffCompressionTypes](../tiffcompressiontypes/) [get_CompressionType](./get_compressiontype/)() override | Указывает тип сжатия. Чтение [TiffCompressionTypes](../tiffcompressiontypes/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Возвращает шрифт, используемый в случае, когда исходный шрифт не найден. Чтение [System::String](../../system/string/). |
| **uint32_t** [get_DpiX](./get_dpix/)() override | Указывает горизонтальное разрешение в точках на дюйм. Чтение **uint32_t**. |
| **uint32_t** [get_DpiY](./get_dpiy/)() override | Указывает вертикальное разрешение в точках на дюйм. Чтение **uint32_t**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Возвращает визуальный стиль градиента. Чтение [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Size](../../system.drawing/size/) [get_ImageSize](./get_imagesize/)() override | Указывает размер генерируемого TIFF-изображения. Значение по умолчанию 0x0, что означает, что размеры генерируемого изображения будут вычислены на основе размера слайда презентации. Чтение [System::Drawing::Size](../../system.drawing/size/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Предоставляет параметры, контролирующие внешний вид объектов [Ink](../../aspose.slides.ink/) в экспортируемом документе. Только для чтения [IInkOptions](../iinkoptions/) |
| [ImagePixelFormat](../imagepixelformat/) [get_PixelFormat](./get_pixelformat/)() override | Указывает формат пикселей для генерируемых изображений. Чтение [ImagePixelFormat](../imagepixelformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Представляет объект обратного вызова для сохранения обновлений прогресса в процентах. Смотрите [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Указывает, должен ли генерируемый документ включать скрытые слайды или нет. По умолчанию **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Чтение **bool**. Значение по умолчанию **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Получает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../islideslayoutoptions/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Возвращает или задает объект, получающий предупреждения и определяющий, будет ли процесс загрузки продолжен или прерван. Чтение [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типового значения со ссылкой на nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счетчик общих ссылок на указанное значение. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BwConversionMode](./set_bwconversionmode/)([BlackWhiteConversionMode](../blackwhiteconversionmode/)) override | Указывает алгоритм преобразования цветного изображения в черно-белое. Этот параметр будет применяться только если [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) установлен в [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) или [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/). Запись [BlackWhiteConversionMode](../blackwhiteconversionmode/). По умолчанию [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/). |
| void [set_CompressionType](./set_compressiontype/)([TiffCompressionTypes](../tiffcompressiontypes/)) override | Указывает тип сжатия. Запись [TiffCompressionTypes](../tiffcompressiontypes/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Устанавливает шрифт, используемый в случае, когда исходный шрифт не найден. Запись [System::String](../../system/string/). |
| void [set_DpiX](./set_dpix/)(**uint32_t**) override | Указывает горизонтальное разрешение в точках на дюйм. Запись **uint32_t**. |
| void [set_DpiY](./set_dpiy/)(**uint32_t**) override | Указывает вертикальное разрешение в точках на дюйм. Запись **uint32_t**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Устанавливает визуальный стиль градиента. Запись [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageSize](./set_imagesize/)([System::Drawing::Size](../../system.drawing/size/)) override | Указывает размер генерируемого TIFF-изображения. Значение по умолчанию 0x0, что означает, что размеры генерируемого изображения будут вычислены на основе размера слайда презентации. Запись [System::Drawing::Size](../../system.drawing/size/). |
| void [set_PixelFormat](./set_pixelformat/)([ImagePixelFormat](../imagepixelformat/)) override | Указывает формат пикселей для генерируемых изображений. Запись [ImagePixelFormat](../imagepixelformat/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Представляет объект обратного вызова для сохранения обновлений прогресса в процентах. Смотрите [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Указывает, должен ли генерируемый документ включать скрытые слайды или нет. По умолчанию **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Запись **bool**. Значение по умолчанию **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Устанавливает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Возвращает или задает объект, получающий предупреждения и определяющий, будет ли процесс загрузки продолжен или прерван. Запись [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й параметр шаблона как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счетчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счетчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счетчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
|  [TiffOptions](./tiffoptions/)() | Конструктор по умолчанию. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Примечания

Следующий пример демонстрирует, как преобразовать PowerPoint в TIFF с размером по умолчанию. 
```cpp
// Создайте объект Presentation, представляющий файл презентации
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

// Сохранение презентации в документ TIFF
presentation->Save(u"Tiffoutput_out.tiff", SaveFormat::Tiff);
```
Следующий пример демонстрирует, как преобразовать PowerPoint в TIFF с пользовательским размером. 
```cpp
// Создайте объект Presentation, представляющий файл презентации
auto pres = System::MakeObject<Presentation>(u"Convert_Tiff_Custom.pptx");

// Создайте объект класса TiffOptions
System::SharedPtr<TiffOptions> opts = System::MakeObject<TiffOptions>();
// Установка типа сжатия
opts->set_CompressionType(TiffCompressionTypes::Default);

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
opts->set_SlidesLayoutOptions(slidesLayoutOptions);

// Типы сжатия
// Default - Указывает схему сжатия по умолчанию (LZW).
// None - Указывает отсутствие сжатия.
// CCITT3
// CCITT4
// LZW
// RLE
// Глубина зависит от типа сжатия и не может быть установлена вручную.
// Единица измерения разрешения всегда равна "2" (точек на дюйм)
// Установка DPI изображения
opts->set_DpiX(200);
opts->set_DpiY(100);
// Установка размера изображения
opts->set_ImageSize(System::Drawing::Size(1728, 1078));
// Сохраните презентацию в TIFF с указанным размером изображения
pres->Save(u"TiffWithCustomSize_out.tiff", SaveFormat::Tiff, opts);
```
Следующий пример демонстрирует, как преобразовать PowerPoint в TIFF с пользовательским форматом пикселей изображения. 
```cpp
// Создайте объект Presentation, представляющий файл презентации
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_PixelFormat(ImagePixelFormat::Format8bppIndexed);

// Сохраните презентацию в TIFF с указанным размером изображения
presentation->Save(u"Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat::Tiff, options);
```

## См. также

* Класс [SaveOptions](../saveoptions/)
* Класс [ITiffOptions](../itiffoptions/)
* Пространство имён [Aspose::Slides::Export](../)
* Библиотека [Aspose.Slides](../../)