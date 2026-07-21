---
title: IPictureFillFormat
second_title: Aspose.Slides для C++: справочник API
description: Представляет стиль заливки изображением.
type: docs
weight: 3225
url: /ru/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat класс

Представляет стиль заливки изображением.

```cpp
class IPictureFillFormat : public Aspose::Slides::IFillParamSource
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) | Сжимает изображение, уменьшая его размер в зависимости от размера фигуры и указанного разрешения. При желании также удаляет обрезанные области. |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, **float**) | Сжимает изображение, уменьшая его размер в зависимости от размера фигуры и указанного разрешения. При желании также удаляет обрезанные области. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() | Удаляет обрезанные области заливки [Picture](../picture/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних нужд. |
| virtual **float** [get_CropBottom](./get_cropbottom/)() | Возвращает количество процентов реальной высоты изображения, которое обрезано снизу картинки. Чтение **float**. |
| virtual **float** [get_CropLeft](./get_cropleft/)() | Возвращает количество процентов реальной ширины изображения, которое обрезано слева картинки. Чтение **float**. |
| virtual **float** [get_CropRight](./get_cropright/)() | Возвращает количество процентов реальной ширины изображения, которое обрезано справа картинки. Чтение **float**. |
| virtual **float** [get_CropTop](./get_croptop/)() | Возвращает количество процентов реальной высоты изображения, которое обрезано сверху картинки. Чтение **float**. |
| virtual **int32_t** [get_Dpi](./get_dpi/)() | Возвращает DPI, используемый для заливки изображения. Чтение **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | Возвращает изображение. Только чтение [ISlidesPicture](../islidespicture/). |
| virtual [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() | Возвращает режим заливки изображения. Чтение [Slides::PictureFillMode](../picturefillmode/). |
| virtual **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() | Возвращает нижний край прямоугольника заливки, определяемый процентным смещением от нижнего края ограничивающего кадра фигуры. Положительный процент задает врезку, отрицательный — выступ. Чтение **float**. |
| virtual **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() | Возвращает левый край прямоугольника заливки, определяемый процентным смещением от левого края ограничивающего кадра фигуры. Положительный процент задает врезку, отрицательный — выступ. Чтение **float**. |
| virtual **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() | Возвращает правый край прямоугольника заливки, определяемый процентным смещением от правого края ограничивающего кадра фигуры. Положительный процент задает врезку, отрицательный — выступ. Чтение **float**. |
| virtual **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() | Возвращает верхний край прямоугольника заливки, определяемый процентным смещением от верхнего края ограничивающего кадра фигуры. Положительный процент задает врезку, отрицательный — выступ. Чтение **float**. |
| virtual [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() | Возвращает способ выравнивания текстуры внутри фигуры. Эта настройка определяет начальную точку шаблона текстуры и способ её повторения по фигуре. Чтение [RectangleAlignment](../rectanglealignment/). |
| virtual [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() | Отражает плитку текстуры по горизонтальной, вертикальной или обеим осям. Чтение [Slides::TileFlip](../tileflip/). |
| virtual **float** [get_TileOffsetX](./get_tileoffsetx/)() | Возвращает горизонтальное смещение текстуры от начала фигуры в пунктах. Положительное значение перемещает текстуру вправо, отрицательное — влево. Чтение **float**. |
| virtual **float** [get_TileOffsetY](./get_tileoffsety/)() | Возвращает вертикальное смещение текстуры от начала фигуры в пунктах. Положительное значение перемещает текстуру вниз, отрицательное — вверх. Чтение **float**. |
| virtual **float** [get_TileScaleX](./get_tilescalex/)() | Возвращает горизонтальный масштаб заливки текстурой в процентах. Чтение **float**. |
| virtual **float** [get_TileScaleY](./get_tilescaley/)() | Возвращает вертикальный масштаб заливки текстурой в процентах. Чтение **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет вычислять хеш пользовательских объектов. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, а лишь инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, а лишь инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект типa значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик разделяемых ссылок на указанное значение. |
| virtual void [set_CropBottom](./set_cropbottom/)(**float**) | Устанавливает количество процентов реальной высоты изображения, которое обрезано снизу картинки. Запись **float**. |
| virtual void [set_CropLeft](./set_cropleft/)(**float**) | Устанавливает количество процентов реальной ширины изображения, которое обрезано слева картинки. Запись **float**. |
| virtual void [set_CropRight](./set_cropright/)(**float**) | Устанавливает количество процентов реальной ширины изображения, которое обрезано справа картинки. Запись **float**. |
| virtual void [set_CropTop](./set_croptop/)(**float**) | Устанавливает количество процентов реальной высоты изображения, которое обрезано сверху картинки. Запись **float**. |
| virtual void [set_Dpi](./set_dpi/)(**int32_t**) | Устанавливает DPI, используемый для заливки изображения. Запись **int32_t**. |
| virtual void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) | Устанавливает режим заливки изображения. Запись [Slides::PictureFillMode](../picturefillmode/). |
| virtual void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) | Устанавливает нижний край прямоугольника заливки, определяемый процентным смещением от нижнего края ограничивающего кадра фигуры. Положительный процент задает врезку, отрицательный — выступ. Запись **float**. |
| virtual void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) | Устанавливает левый край прямоугольника заливки, определяемый процентным смещением от левого края ограничивающего кадра фигуры. Положительный процент задает врезку, отрицательный — выступ. Запись **float**. |
| virtual void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) | Устанавливает правый край прямоугольника заливки, определяемый процентным смещением от правого края ограничивающего кадра фигуры. Положительный процент задает врезку, отрицательный — выступ. Запись **float**. |
| virtual void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) | Устанавливает верхний край прямоугольника заливки, определяемый процентным смещением от верхнего края ограничивающего кадра фигуры. Положительный процент задает врезку, отрицательный — выступ. Запись **float**. |
| virtual void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) | Устанавливает способ выравнивания текстуры внутри фигуры. Эта настройка определяет начальную точку шаблона текстуры и способ её повторения по фигуре. Запись [RectangleAlignment](../rectanglealignment/). |
| virtual void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) | Отражает плитку текстуры по горизонтальной, вертикальной или обеим осям. Запись [Slides::TileFlip](../tileflip/). |
| virtual void [set_TileOffsetX](./set_tileoffsetx/)(**float**) | Устанавливает горизонтальное смещение текстуры от начала фигуры в пунктах. Положительное значение перемещает текстуру вправо, отрицательное — влево. Запись **float**. |
| virtual void [set_TileOffsetY](./set_tileoffsety/)(**float**) | Устанавливает вертикальное смещение текстуры от начала фигуры в пунктах. Положительное значение перемещает текстуру вниз, отрицательное — вверх. Запись **float**. |
| virtual void [set_TileScaleX](./set_tilescalex/)(**float**) | Устанавливает горизонтальный масштаб заливки текстурой в процентах. Запись **float**. |
| virtual void [set_TileScaleY](./set_tilescaley/)(**float**) | Устанавливает вертикальный масштаб заливки текстурой в процентах. Запись **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не разделяемый). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика разделяемых ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик разделяемых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик разделяемых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [IFillParamSource](../ifillparamsource/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)