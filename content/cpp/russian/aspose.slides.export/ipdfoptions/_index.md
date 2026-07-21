---
title: IPdfOptions
second_title: Aspose.Slides для C++ справочник API
description: Предоставляет параметры, которые управляют тем, как презентация сохраняется в формате PDF.
type: docs
weight: 274
url: /ru/aspose.slides.export/ipdfoptions/
---
## Класс IPdfOptions

Предоставляет параметры, которые управляют тем, как презентация сохраняется в формате PDF.

```cpp
class IPdfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() | Содержит набор флагов, определяющих, какие разрешения доступа следует предоставить при открытии документа с пользовательским доступом. См. [PdfAccessPermissions](../pdfaccesspermissions/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() | Возвращает массив пользовательских имен семейств шрифтов, которые [Aspose.Slides](../../aspose.slides/) следует рассматривать как общие. Читайте [System::String](../../system/string/)[]. |
| virtual **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() | Применяет указанный прозрачный цвет к изображению, если **true**. |
| virtual **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() | Указывает, следует ли автоматически выбирать наиболее эффективное сжатие (вместо стандартного) для каждого изображения. Если установлено **bool**.true, для каждого изображения в презентации будет выбран наиболее подходящий алгоритм сжатия, что приведет к уменьшенному размеру получаемого PDF-документа. |
| virtual [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() | Желаемый уровень соответствия генерируемого PDF-документа. Читайте [PdfCompliance](../pdfcompliance/). |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Возвращает шрифт, используемый в случае, если исходный шрифт не найден. Читает [System::String](../../system/string/). |
| virtual **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() | Установить **bool** в true, чтобы рисовать черную рамку вокруг каждого слайда. Читайте **bool**. |
| virtual **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() | Определяет, должны ли быть внедрены все символы шрифта или только используемое подмножество. Читайте **bool**. |
| virtual **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() | Установить **bool** в true, чтобы внедрять шрифты TrueType для символов ASCII 32-127. [Fonts](../../aspose.slides/fonts/) для кодов символов более 127 всегда внедряются. Читайте **bool**. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Возвращает визуальный стиль градиента. Читайте [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() | Получает прозрачный цвет изображения. |
| virtual **bool** [get_IncludeOleData](./get_includeoledata/)() | Установите **bool** в true, чтобы преобразовать все данные OLE из презентации в внедренные файлы в получаемом PDF. Читайте **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | Предоставляет параметры, которые управляют внешним видом объектов [Ink](../../aspose.slides.ink/) в экспортируемом документе. Только чтение [IInkOptions](../iinkoptions/) |
| virtual **uint8_t** [get_JpegQuality](./get_jpegquality/)() | Возвращает значение, определяющее качество JPEG-изображений внутри PDF-документа. Читайте **uint8_t**. |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | Установка пароля пользователя для защиты PDF-документа. Читайте [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Представляет объект обратного вызова для сохранения обновлений прогресса в процентах. См. [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() | Указывает, следует ли растрировать текст как bitmap и сохранять в PDF, когда шрифт не поддерживает полужирное начертание. Этот подход может повысить качество текста в получаемом PDF для некоторых шрифтов. Читайте **bool**. |
| virtual **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() | Установите **bool** в true, чтобы преобразовать все метафайлы, используемые в презентации, в изображения PNG. Читайте **bool**. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | Указывает, следует ли включать скрытые слайды в генерируемый документ. По умолчанию **false**. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Читайте **bool**. Значение по умолчанию **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | Получает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual **float** [get_SufficientResolution](./get_sufficientresolution/)() | Возвращает значение, определяющее разрешение изображений внутри PDF-документа. |
| virtual [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() | Указывает тип сжатия, используемый для всего текстового содержимого в документе. Читайте [PdfTextCompression](../pdftextcompression/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Возвращает объект, получающий предупреждения и решающий, продолжить загрузку или прервать её. Читайте [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Обеспечивает хеширование пользовательских объектов. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует оператор C# lock() для блокировки. Вызовите напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Обеспечивает клонирование пользовательских типов. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения со значением nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместного использования на указанное значение. |
| virtual void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) | Содержит набор флагов, определяющих, какие разрешения доступа следует предоставить при открытии документа с пользовательским доступом. См. [PdfAccessPermissions](../pdfaccesspermissions/). |
| virtual void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) | Устанавливает массив пользовательских имен семейств шрифтов, которые [Aspose.Slides](../../aspose.slides/) следует рассматривать как общие. Запишите [System::String](../../system/string/)[]. |
| virtual void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) | Применяет указанный прозрачный цвет к изображению, если **true**. |
| virtual void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) | Указывает, следует ли автоматически выбирать наиболее эффективное сжатие (вместо стандартного) для каждого изображения. Если установлено **bool**.true, для каждого изображения в презентации будет выбран наиболее подходящий алгоритм сжатия, что приведет к уменьшенному размеру получаемого PDF-документа. |
| virtual void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) | Желаемый уровень соответствия генерируемого PDF-документа. Запишите [PdfCompliance](../pdfcompliance/). |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Устанавливает шрифт, используемый в случае, если исходный шрифт не найден. Записывает [System::String](../../system/string/). |
| virtual void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) | Установить **bool** в true, чтобы рисовать черную рамку вокруг каждого слайда. Запишите **bool**. |
| virtual void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) | Определяет, должны ли быть внедрены все символы шрифта или только используемое подмножество. Запишите **bool**. |
| virtual void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) | Установить **bool** в true, чтобы внедрять шрифты TrueType для символов ASCII 32-127. [Fonts](../../aspose.slides/fonts/) для кодов символов более 127 всегда внедряются. Запишите **bool**. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Устанавливает визуальный стиль градиента. Запишите [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) | Устанавливает прозрачный цвет изображения. |
| virtual void [set_IncludeOleData](./set_includeoledata/)(**bool**) | Установить **bool** в true, чтобы преобразовать все данные OLE из презентации в внедренные файлы в получаемом PDF. Запишите **bool**. |
| virtual void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) | Устанавливает значение, определяющее качество JPEG-изображений внутри PDF-документа. Запишите **uint8_t**. |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | Установка пароля пользователя для защиты PDF-документа. Запишите [System::String](../../system/string/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Представляет объект обратного вызова для сохранения обновлений прогресса в процентах. См. [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) | Указывает, следует ли растрировать текст как bitmap и сохранять в PDF, когда шрифт не поддерживает полужирное начертание. Этот подход может повысить качество текста в получаемом PDF для некоторых шрифтов. Запишите **bool**. |
| virtual void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) | Установить **bool** в true, чтобы преобразовать все метафайлы, используемые в презентации, в изображения PNG. Запишите **bool**. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Указывает, следует ли включать скрытые слайды в генерируемый документ. По умолчанию **false**. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Запишите **bool**. Значение по умолчанию **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | Устанавливает режим размещения слайдов на странице при экспорте презентации [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual void [set_SufficientResolution](./set_sufficientresolution/)(**float**) | Устанавливает значение, определяющее разрешение изображений внутри PDF-документа. |
| virtual void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) | Указывает тип сжатия, используемый для всего текстового содержимого в документе. Запишите [PdfTextCompression](../pdftextcompression/). |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Устанавливает объект, получающий предупреждения и решающий, продолжить загрузку или прервать её. Запишите [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й параметр шаблона как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместного использования. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместного использования. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместного использования. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Обеспечивает преобразование пользовательских объектов в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкт C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует оператор C# lock() для разблокировки. Вызовите напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [ISaveOptions](../isaveoptions/)
* Пространство имен [Aspose::Slides::Export](../)
* Библиотека [Aspose.Slides](../../)