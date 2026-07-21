---
title: PdfOptions
second_title: Справочник API Aspose.Slides для C++
description: Предоставляет параметры, контролирующие, как презентация сохраняется в формате Pdf.
type: docs
weight: 573
url: /ru/aspose.slides.export/pdfoptions/
---
## PdfOptions класс

Предоставляет параметры, контролирующие, как презентация сохраняется в формате Pdf.

```cpp
class PdfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IPdfOptions
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() override | Содержит набор флагов, указывающих, какие разрешения доступа должны быть предоставлены при открытии документа пользователем. См. [PdfAccessPermissions](../pdfaccesspermissions/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() override | Возвращает массив пользовательских имён семейств шрифтов, которые [Aspose.Slides](../../aspose.slides/) должен рассматривать как общие. Читать [System::String](../../system/string/)[]. |
| **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() override | Применяет указанный прозрачный цвет к изображению, если **true**. |
| **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() override | Указывает, следует ли автоматически выбирать наиболее эффективное сжатие (вместо используемого по умолчанию) для каждого изображения. Если установлено в **bool**.true, для каждого изображения в презентации будет выбран наиболее подходящий алгоритм сжатия, что приведёт к меньшему размеру получаемого PDF-документа. |
| [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() override | Желаемый уровень соответствия генерируемого PDF-документа. Читать [PdfCompliance](../pdfcompliance/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Возвращает шрифт, используемый в случае, если исходный шрифт не найден. Читает [System::String](../../system/string/). |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | **true**, чтобы нарисовать чёрную рамку вокруг каждого слайда. Читать **bool**. |
| **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() override | Определяет, следует ли встраивать все символы шрифта или только используемую часть. Читать **bool**. |
| **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() override | Определяет, будет ли [Aspose.Slides](../../aspose.slides/) встраивать общие шрифты для текста ASCII (диапазон кодов 33..127). [Fonts](../../aspose.slides/fonts/) для кодов символов более 127 всегда встраиваются. Список общих шрифтов включает базовые 14 шрифтов PDF и дополнительные пользовательские шрифты. Читать **bool**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Возвращает визуальный стиль градиента. Читать [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() override | Получает прозрачный цвет изображения. |
| **bool** [get_IncludeOleData](./get_includeoledata/)() override | **true**, чтобы преобразовать все данные OLE из презентации во встроенные файлы в результирующем PDF. Читать **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Предоставляет параметры, контролирующие внешний вид объектов [Ink](../../aspose.slides.ink/) в экспортированном документе. Только для чтения [IInkOptions](../iinkoptions/) |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | Возвращает значение, определяющее качество JPEG-изображений в PDF-документе. Читать **uint8_t**. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | Установка пользовательского пароля для защиты PDF-документа. Читать [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Представляет объект обратного вызова для сохранения обновлений прогресса в процентах. См. [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() override | Указывает, следует ли растеризовать текст как растровое изображение и сохранить в PDF, когда шрифт не поддерживает полужирное начертание. Этот подход может улучшить качество текста в результирующем PDF для некоторых шрифтов. Читать **bool**. |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | **true**, чтобы преобразовать все метафайлы, используемые в презентации, в изображения PNG. Читать **bool**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Указывает, должен ли генерируемый документ включать скрытые слайды. По умолчанию **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Читать **bool**. Значение по умолчанию **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Получает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../islideslayoutoptions/). |
| **float** [get_SufficientResolution](./get_sufficientresolution/)() override | Возвращает значение, определяющее разрешение изображений в PDF-документе. |
| [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() override | Указывает тип сжатия, используемый для всего текстового содержимого документа. Читать [PdfTextCompression](../pdftextcompression/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Возвращает или задает объект, получающий предупреждения и решающий, будет ли процесс загрузки продолжен или прерван. Читать [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет выполнять копирующее построение подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет выполнять копирующее построение подклассов. |
|  [PdfOptions](./pdfoptions/)() | Конструктор по умолчанию. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект типa значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) override | Содержит набор флагов, указывающих, какие разрешения доступа должны быть предоставлены при открытии документа пользователем. См. [PdfAccessPermissions](../pdfaccesspermissions/). |
| void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | Устанавливает массив пользовательских имён семейств шрифтов, которые [Aspose.Slides](../../aspose.slides/) должен рассматривать как общие. Записать [System::String](../../system/string/)[]. |
| void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) override | Применяет указанный прозрачный цвет к изображению, если **true**. |
| void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) override | Указывает, следует ли автоматически выбирать наиболее эффективное сжатие (вместо используемого по умолчанию) для каждого изображения. Если установлено в **bool**.true, для каждого изображения в презентации будет выбран наиболее подходящий алгоритм сжатия, что приведёт к меньшему размеру получаемого PDF-документа. |
| void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) override | Желаемый уровень соответствия генерируемого PDF-документа. Записать [PdfCompliance](../pdfcompliance/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Устанавливает шрифт, используемый в случае, если исходный шрифт не найден. Записывает [System::String](../../system/string/). |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | **true**, чтобы нарисовать чёрную рамку вокруг каждого слайда. Записать **bool**. |
| void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) override | Определяет, следует ли встраивать все символы шрифта или только используемую часть. Записать **bool**. |
| void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) override | Определяет, будет ли [Aspose.Slides](../../aspose.slides/) встраивать общие шрифты для текста ASCII (диапазон кодов 33..127). [Fonts](../../aspose.slides/fonts/) для кодов символов более 127 всегда встраиваются. Список общих шрифтов включает базовые 14 шрифтов PDF и дополнительные пользовательские шрифты. Записать **bool**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Устанавливает визуальный стиль градиента. Записать [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) override | Устанавливает прозрачный цвет изображения. |
| void [set_IncludeOleData](./set_includeoledata/)(**bool**) override | **true**, чтобы преобразовать все данные OLE из презентации во встроенные файлы в результирующем PDF. Записать **bool**. |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | Устанавливает значение, определяющее качество JPEG-изображений в PDF-документе. Записать **uint8_t**. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | Установка пользовательского пароля для защиты PDF-документа. Записать [System::String](../../system/string/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Представляет объект обратного вызова для сохранения обновлений прогресса в процентах. См. [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) override | Указывает, следует ли растеризовать текст как растровое изображение и сохранить в PDF, когда шрифт не поддерживает полужирное начертание. Этот подход может улучшить качество текста в результирующем PDF для некоторых шрифтов. Записать **bool**. |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | **true**, чтобы преобразовать все метафайлы, используемые в презентации, в изображения PNG. Записать **bool**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Указывает, должен ли генерируемый документ включать скрытые слайды. По умолчанию **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Записать **bool**. Значение по умолчанию **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Устанавливает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_SufficientResolution](./set_sufficientresolution/)(**float**) override | Устанавливает значение, определяющее разрешение изображений в PDF-документе. |
| void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) override | Указывает тип сжатия, используемый для всего текстового содержимого документа. Записать [PdfTextCompression](../pdftextcompression/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Возвращает или задает объект, получающий предупреждения и решающий, будет ли процесс загрузки продолжен или прерван. Записать [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-ый шаблонный аргумент в слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Примечания

Следующий пример показывает, как преобразовать PowerPoint в PDF с пользовательскими параметрами.  
```cpp
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Создаёт экземпляр класса PdfOptions
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Устанавливает качество JPEG
pdfOptions->set_JpegQuality(90);
// Устанавливает поведение для метафайлов
pdfOptions->set_SaveMetafilesAsPng(true);
// Устанавливает уровень сжатия текста
pdfOptions->set_TextCompression(PdfTextCompression::Flate);
// Задает стандарт PDF
pdfOptions->set_Compliance(PdfCompliance::Pdf15);
// Сохраняет презентацию в PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```  
Следующий пример показывает, как преобразовать PowerPoint в PDF с скрытыми слайдами.  
```cpp
// Создаёт объект класса Presentation, представляющего файл PowerPoint
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Создаёт объект класса PdfOptions
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Добавляет скрытые слайды
pdfOptions->set_ShowHiddenSlides(true);
// Сохраняет презентацию в PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```  
Следующий пример показывает, как преобразовать PowerPoint в PDF с защитой паролем.  
```cpp
// Создаёт объект Presentation, представляющий файл PowerPoint
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();

// Устанавливает пароль PDF и разрешения доступа
pdfOptions->set_Password(u"password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
// Сохраняет презентацию в PDF
presentation->Save(u"PPTX-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```  
Следующий пример показывает, как преобразовать PowerPoint в PDF с заметками.  
```cpp
// Создаёт объект Presentation, представляющий файл презентации
auto presentation = System::MakeObject<Presentation>(u"SelectedSlides.pptx");

auto auxPresentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auxPresentation->get_Slides()->InsertClone(0, slide);

// Setting Slide Type and Size
auxPresentation->get_SlideSize()->SetSize(612.F, 792.F, SlideSizeScaleType::EnsureFit);

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
pdfOptions->set_SlidesLayoutOptions(slidesLayoutOptions);
auxPresentation->Save(u"PDFnotes_out.pdf", SaveFormat::Pdf, pdfOptions);
```

## См. также

* Класс [SaveOptions](../saveoptions/)
* Класс [IPdfOptions](../ipdfoptions/)
* Пространство имён [Aspose::Slides::Export](../)
* Библиотека [Aspose.Slides](../../)