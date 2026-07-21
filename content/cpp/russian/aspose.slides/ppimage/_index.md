---
title: PPImage
second_title: Справочник API Aspose.Slides для C++
description: Представляет изображение в презентации.
type: docs
weight: 4824
url: /ru/aspose.slides/ppimage/
---
## PPImage класс

Представляет изображение в презентации.

```cpp
class PPImage : public Aspose::Slides::IPPImage,
                public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| void [Dispose](./dispose/)() override | Освобождает объект. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типа значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_BinaryData](./get_binarydata/)() override | Возвращает копию данных изображения. Только для чтения **uint8_t**[]. |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Возвращает MIME-тип изображения, кодированный в [PPImage::get_BinaryData](./get_binarydata/). Только для чтения [System::String](../../system/string/). |
| **int32_t** [get_Height](./get_height/)() override | Возвращает высоту изображения. Только для чтения **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IImage](../iimage/)\> [get_Image](./get_image/)() override | Возвращает копию изображения. Только для чтения [IImage](../iimage/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::ISvgImage](../isvgimage/)\> [get_SvgImage](./get_svgimage/)() const override | Возвращает объект [ISvgImage](../isvgimage/) [ISvgImage](../isvgimage/). |
| **int32_t** [get_Width](./get_width/)() override | Возвращает ширину изображения. Только для чтения **int32_t**. |
| **int32_t** [get_X](./get_x/)() override | Возвращает смещение X изображения. Только для чтения **int32_t**. |
| **int32_t** [get_Y](./get_y/)() override | Возвращает смещение Y изображения. Только для чтения **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Возвращает хеш-код изображения. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку, как в операторе C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, только инициализирует новый объект и позволяет копирующее конструирование подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, только инициализирует новый объект и позволяет копирующее конструирование подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типа значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [ReplaceImage](./replaceimage/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Заменяет данные изображения. |
| void [ReplaceImage](./replaceimage/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IImage](../iimage/)\>) override | Заменяет данные изображения. Внимание: когда Image является метафайлом, он будет растеризован. Вместо этого используйте ReplaceImage(byte[]). |
| void [ReplaceImage](./replaceimage/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IPPImage](../ippimage/)\>) override | Заменяет данные изображения. |
| virtual void [ReplaceImage](../ippimage/replaceimage/)([System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>) | Заменяет изображение. |
| virtual void [ReplaceImage](../ippimage/replaceimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) | Заменяет изображение. |
| void [set_SvgImage](./set_svgimage/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::ISvgImage](../isvgimage/)\>) override | Устанавливает объект [ISvgImage](../isvgimage/) [ISvgImage](../isvgimage/). |
| virtual void [set_SvgImage](../ippimage/set_svgimage/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgImage](../isvgimage/)\>) | Устанавливает объект [ISvgImage](../isvgimage/) [ISvgImage](../isvgimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-ый параметр шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку, как в операторе C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [IPPImage](../ippimage/)
* Класс [IDisposable](../../system/idisposable/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)