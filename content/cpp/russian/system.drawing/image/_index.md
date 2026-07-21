---
title: Image
second_title: Aspose.Slides для C++ справочник API
description: "Базовый класс для классов System::Drawing::Bitmap и System::Drawing::Metafile, предоставляющий базовую функциональность. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам времени выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 144
url: /ru/system.drawing/image/
---
## Класс Image

Базовый класс для [System::Drawing::Bitmap](../bitmap/) и классов System::Drawing::Metafile, предоставляющий базовую функциональность. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам времени выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class Image : public virtual System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Image](./)\> [Clone](./clone/)() | Создаёт копию текущего объекта. |
| void [Dispose](./dispose/)() override | Освобождает все ресурсы, полученные текущим объектом. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних нужд. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](./)\> [FromFile](./fromfile/)(const [String](../../system/string/)\&, **bool**) | Создаёт объект [Image](./) из указанного файла. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](../bitmap/)\> [FromHbitmap](./fromhbitmap/)(IntPtr) | Создаёт объект [Bitmap](../bitmap/) из указанного GDI-bitmap. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](./)\> [FromStream](./fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | Создаёт объект [Image](./) из указанного потока. |
| virtual **int32_t** [get_Flags](./get_flags/)() const | Возвращает побитовую комбинацию значений перечисления ImageFlags, представляющих атрибуты изображения. |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](./get_framedimensionslist/)() const | Возвращает массив GUID, представляющих размеры фреймов внутри изображения, представленного текущим объектом. |
| virtual int [get_Height](./get_height/)() const | Возвращает высоту изображения в пикселях. |
| **float** [get_HorizontalResolution](./get_horizontalresolution/)() const | Возвращает горизонтальное разрешение изображения, представленного текущим объектом, в пикселях на дюйм. |
| virtual [Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/) [get_Palette](./get_palette/)() const | Возвращает цветовую палитру, используемую изображением, представленного текущим объектом. |
| virtual [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/) [get_PixelFormat](./get_pixelformat/)() const | Возвращает формат пикселей изображения, представленного текущим объектом. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](./get_propertyidlist/)() const | Получает идентификаторы элементов свойств, хранящихся в этом изображении. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../../system.drawing.imaging/propertyitem/)\>\> [get_PropertyItems](./get_propertyitems/)() const | Получает все элементы свойств (фрагменты метаданных), хранящиеся в этом изображении. |
| virtual [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/) [get_RawFormat](./get_rawformat/)() const | Возвращает формат файла изображения, представленного текущим объектом. |
| [Size](../size/) [get_Size](./get_size/)() const | Возвращает объект [Size](../size/), представляющий ширину и высоту изображения в пикселях. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](./get_tag/)() const | Получает объект, предоставляющий дополнительные данные об изображении. |
| **float** [get_VerticalResolution](./get_verticalresolution/)() const | Возвращает вертикальное разрешение изображения, представленного текущим объектом, в пикселях на дюйм. |
| virtual int [get_Width](./get_width/)() const | Возвращает ширину изображения в пикселях. |
| [RectangleF](../rectanglef/) [GetBounds](./getbounds/)([GraphicsUnit](../graphicsunit/)\&) | Возвращает границы изображения в указанных единицах измерения. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| int [GetFrameCount](./getframecount/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&) | Возвращает количество фреймов указанного измерения кадра. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хэшировать пользовательские объекты. |
| static int [GetPixelFormatSize](./getpixelformatsize/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Возвращает количество бит, используемых для представления глубины цвета в указанном формате пикселей. |
| virtual const SkBitmap * [GetSkBitmap](./getskbitmap/)() const | Возвращает базовый объект SkBitmap. |
| [SharedPtr](../../system/sharedptr/)\<[Image](./)\> [GetThumbnailImage](./getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](./getthumbnailimageabort/), IntPtr) | Получает миниатюру для этого объекта [System::Drawing::Image](./). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| static **bool** [IsAlphaPixelFormat](./isalphapixelformat/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Определяет, содержит ли указанный формат пикселей альфа-информацию. |
| virtual **bool** [IsMultiImage](./ismultiimage/)() const | Возвращает, является ли оригинальный формат многократным изображением. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копирующее конструирование подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копирующее конструирование подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект типa значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual void [RotateFlip](./rotateflip/)([RotateFlipType](../rotatefliptype/)) | Поворачивает изображение на кратное 90-м градусам и отражает. |
| void [Save](./save/)(const [String](../../system/string/)\&) | Сохраняет изображение, представленное текущим объектом, в указанный файл в формате PNG. |
| void [Save](./save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Сохраняет изображение, представленное текущим объектом, в указанный файл в указанном формате. |
| void [Save](./save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Сохраняет изображение, представленное текущим объектом, в указанный поток в указанном формате. |
| void [Save](./save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Сохраняет изображение, представленное текущим объектом, в указанный файл с помощью указанного кодировщика и параметров кодировщика. |
| void [Save](./save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Сохраняет изображение, представленное текущим объектом, в указанный поток с помощью указанного кодировщика и параметров кодировщика. |
| void [SaveAdd](./saveadd/)(const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Добавляет фрейм в файл или поток, указанный в предыдущем вызове метода [Save()](./save/). |
| void [SaveAdd](./saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](./)\>\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Добавляет фрейм в файл или поток, указанный в предыдущем вызове метода [Save()](./save/). |
| int [SelectActiveFrame](./selectactiveframe/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&, int) | Выбирает указанный фрейм. |
| virtual void [set_Palette](./set_palette/)([Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/)) | Устанавливает цветовую палитру, используемую изображением, представленного текущим объектом. |
| virtual void [set_Tag](./set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Устанавливает объект, предоставляющий дополнительные данные об изображении. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент в виде слабого указателя (вместо shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкт C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Типы

| Тип | Описание |
| --- | --- |
| [GetThumbnailImageAbort](./getthumbnailimageabort/) | Обратный вызов для отмены выполнения GetThumbnailImage. |

## См. также

* Класс [IDisposable](../../system/idisposable/)
* Пространство имён [System::Drawing](../)
* Библиотека [Aspose.Slides](../../)