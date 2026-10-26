---
title: PictureFillFormat
second_title: Справочник API Aspose.Slides для C++
description: Представляет стиль заливки изображением.
type: docs
weight: 4720
url: /ru/aspose.slides/picturefillformat/
---
## PictureFillFormat класс

Представляет стиль заливки изображением.

```cpp
class PictureFillFormat : public Aspose::Slides::PVIObject,
                          public Aspose::Slides::IPictureFillFormat
```

## Методы

| Метод | Описание |
| --- | --- |
| **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) override | Сжимает изображение, уменьшая его размер в зависимости от размера фигуры и указанного разрешения. При необходимости также удаляет обрезанные области. |
| **bool** [CompressImage](./compressimage/)(**bool**, **float**) override | Сжимает изображение, уменьшая его размер в зависимости от размера фигуры и указанного разрешения. При необходимости также удаляет обрезанные области. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() override | Удаляет обрезанные области заливки [Picture](../picture/). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Сравнивает с указанным объектом. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| **float** [get_CropBottom](./get_cropbottom/)() override | Возвращает процент реальной высоты изображения, который обрезан снизу картинки. Только чтение **float**. |
| **float** [get_CropLeft](./get_cropleft/)() override | Возвращает процент реальной ширины изображения, который обрезан слева картинки. Только чтение **float**. |
| **float** [get_CropRight](./get_cropright/)() override | Возвращает процент реальной ширины изображения, который обрезан справа картинки. Только чтение **float**. |
| **float** [get_CropTop](./get_croptop/)() override | Возвращает процент реальной высоты изображения, который обрезан сверху картинки. Только чтение **float**. |
| **int32_t** [get_Dpi](./get_dpi/)() override | Возвращает dpi, используемый для заливки изображения. Только чтение **int32_t**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Возвращает объект Parent_Immediate. Только для чтения [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Возвращает родитель [IPresentationComponent](../ipresentationcomponent/). Только для чтения [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Возвращает изображение. Только для чтения [ISlidesPicture](../islidespicture/). |
| [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() override | Возвращает режим заливки изображения. Только чтение [Slides::PictureFillMode](../picturefillmode/). |
| **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() override | Возвращает нижнюю границу прямоугольника заливки, определяемую процентным смещением от нижней границы ограничивающего прямоугольника фигуры. Положительный процент задаёт врезку, отрицательный — выступ. Только чтение **float**. |
| **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() override | Возвращает левую границу прямоугольника заливки, определяемую процентным смещением от левой границы ограничивающего прямоугольника фигуры. Положительный процент задаёт врезку, отрицательный — выступ. Только чтение **float**. |
| **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() override | Возвращает правую границу прямоугольника заливки, определяемую процентным смещением от правой границы ограничивающего прямоугольника фигуры. Положительный процент задаёт врезку, отрицательный — выступ. Только чтение **float**. |
| **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() override | Возвращает верхнюю границу прямоугольника заливки, определяемую процентным смещением от верхней границы ограничивающего прямоугольника фигуры. Положительный процент задаёт врезку, отрицательный — выступ. Только чтение **float**. |
| [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() override | Возвращает способ выравнивания текстуры внутри фигуры. Этот параметр определяет начальную точку узора текстуры и то, как он повторяется по фигуре. Только чтение [RectangleAlignment](../rectanglealignment/). |
| [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() override | Отражает квадрат текстуры по горизонтальной, вертикальной или обеим осям. Только чтение [Slides::TileFlip](../tileflip/). |
| **float** [get_TileOffsetX](./get_tileoffsetx/)() override | Возвращает горизонтальное смещение текстуры от начала фигуры в пунктах. Положительное значение смещает текстуру вправо, отрицательное — влево. Только чтение **float**. |
| **float** [get_TileOffsetY](./get_tileoffsety/)() override | Возвращает вертикальное смещение текстуры от начала фигуры в пунктах. Положительное значение смещает текстуру вниз, отрицательное — вверх. Только чтение **float**. |
| **float** [get_TileScaleX](./get_tilescalex/)() override | Возвращает горизонтальный масштаб текстурной заливки в процентах. Только чтение **float**. |
| **float** [get_TileScaleY](./get_tilescaley/)() override | Возвращает вертикальный масштаб текстурной заливки в процентах. Только чтение **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Возвращает хеш-код. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператором C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, только инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, только инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [set_CropBottom](./set_cropbottom/)(**float**) override | Устанавливает процент реальной высоты изображения, который обрезан снизу картинки. Запись **float**. |
| void [set_CropLeft](./set_cropleft/)(**float**) override | Устанавливает процент реальной ширины изображения, который обрезан слева картинки. Запись **float**. |
| void [set_CropRight](./set_cropright/)(**float**) override | Устанавливает процент реальной ширины изображения, который обрезан справа картинки. Запись **float**. |
| void [set_CropTop](./set_croptop/)(**float**) override | Устанавливает процент реальной высоты изображения, который обрезан сверху картинки. Запись **float**. |
| void [set_Dpi](./set_dpi/)(**int32_t**) override | Устанавливает dpi, используемый для заливки изображения. Запись **int32_t**. |
| void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) override | Устанавливает режим заливки изображения. Запись [Slides::PictureFillMode](../picturefillmode/). |
| void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) override | Устанавливает нижнюю границу прямоугольника заливки, определяемую процентным смещением от нижней границы ограничивающего прямоугольника фигуры. Положительный процент задаёт врезку, отрицательный — выступ. Запись **float**. |
| void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) override | Устанавливает левую границу прямоугольника заливки, определяемую процентным смещением от левой границы ограничивающего прямоугольника фигуры. Положительный процент задаёт врезку, отрицательный — выступ. Запись **float**. |
| void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) override | Устанавливает правую границу прямоугольника заливки, определяемую процентным смещением от правой границы ограничивающего прямоугольника фигуры. Положительный процент задаёт врезку, отрицательный — выступ. Запись **float**. |
| void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) override | Устанавливает верхнюю границу прямоугольника заливки, определяемую процентным смещением от верхней границы ограничивающего прямоугольника фигуры. Положительный процент задаёт врезку, отрицательный — выступ. Запись **float**. |
| void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) override | Устанавливает способ выравнивания текстуры внутри фигуры. Этот параметр определяет начальную точку узора текстуры и то, как он повторяется по фигуре. Запись [RectangleAlignment](../rectanglealignment/). |
| void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) override | Отражает квадрат текстуры по горизонтальной, вертикальной или обеим осям. Запись [Slides::TileFlip](../tileflip/). |
| void [set_TileOffsetX](./set_tileoffsetx/)(**float**) override | Устанавливает горизонтальное смещение текстуры от начала фигуры в пунктах. Положительное значение смещает текстуру вправо, отрицательное — влево. Запись **float**. |
| void [set_TileOffsetY](./set_tileoffsety/)(**float**) override | Устанавливает вертикальное смещение текстуры от начала фигуры в пунктах. Положительное значение смещает текстуру вниз, отрицательное — вверх. Запись **float**. |
| void [set_TileScaleX](./set_tilescalex/)(**float**) override | Устанавливает горизонтальный масштаб текстурной заливки в процентах. Запись **float**. |
| void [set_TileScaleY](./set_tilescaley/)(**float**) override | Устанавливает вертикальный масштаб текстурной заливки в процентах. Запись **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператором C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [PVIObject](../pviobject/)
* Класс [IPictureFillFormat](../ipicturefillformat/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)