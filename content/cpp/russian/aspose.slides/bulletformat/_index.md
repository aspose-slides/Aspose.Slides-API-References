---
title: BulletFormat
second_title: Справочник API Aspose.Slides для C++
description: Представляет свойства форматирования маркеров абзаца.
type: docs
weight: 248
url: /ru/aspose.slides/bulletformat/
---
## BulletFormat класс

Represents paragraph bullet formatting properties.

```cpp
class BulletFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IBulletFormat
```

## Методы

| Method | Description |
| --- | --- |
| void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() override | Устанавливает смещения по умолчанию, отличные от нуля, для эффективных значений Indent и MarginLeft абзаца, когда маркеры включены (как делает PowerPoint при включении маркеров/нумерации абзаца). Если маркеры выключены, то просто сбрасываются значения Indent и MarginLeft абзаца (как делает PowerPoint при отключении маркеров/нумерации). Смещения отступов применяются с учётом текущего контекста маркера — IBulletFormat::get(set)_Type, .NumberedBulletStyle и FontHeight первой части. Смещения, отличные от нуля, применяются к эффективным Indent и MarginLeft текущего абзаца (значения становятся локальными). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Сравнивает с указанным объектом. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| char16_t [get_Char](./get_char/)() override | Возвращает символ маркера абзаца без наследования. Читает **wchar_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() override | Возвращает формат цвета маркера абзаца без наследования. Только для чтения [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() override | Возвращает шрифт маркера абзаца без наследования. Читает [IFontData](../ifontdata/). |
| **float** [get_Height](./get_height/)() override | Возвращает высоту маркера абзаца без наследования. Значение std::numeric_limits<float>::quiet_NaN() определяет, что маркер наследует высоту от первой части абзаца. Читает **float**. |
| [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() override | Определяет, имеет ли маркер собственный цвет или наследует его от первой части абзаца. **[NullableBool::True](../nullablebool/)**, если у маркера собственный цвет, и **[NullableBool::False](../nullablebool/)**, если маркер наследует цвет от первой части абзаца. Читает [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() override | Определяет, имеет ли маркер собственный шрифт или наследует его от первой части абзаца. **[NullableBool::True](../nullablebool/)**, если маркер имеет собственный шрифт, и **[NullableBool::False](../nullablebool/)**, если маркер наследует шрифт от первой части абзаца. Читает [NullableBool](../nullablebool/). |
| **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() override | Возвращает первое число, используемое для группы нумерованных маркеров без наследования. Читает **int16_t**. |
| [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() override | Возвращает стиль нумерованного маркера без наследования. Читает [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Возвращает объект Parent_Immediate. Только для чтения [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Возвращает родительский [IPresentationComponent](../ipresentationcomponent/). Только для чтения [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Возвращает изображение, используемое как маркер в абзаце без наследования. Только для чтения [ISlidesPicture](../islidespicture/). |
| [BulletType](../bullettype/) [get_Type](./get_type/)() override | Возвращает тип маркера абзаца без наследования. Читает [BulletType](../bullettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() override | Получает эффективные данные форматирования маркера с примененным наследованием. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Возвращает хеш-код. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает ссылкой объект типa значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [set_Char](./set_char/)(char16_t) override | Устанавливает символ маркера абзаца без наследования. Записывает **wchar_t**. |
| void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Устанавливает шрифт маркера абзаца без наследования. Записывает [IFontData](../ifontdata/). |
| void [set_Height](./set_height/)(**float**) override | Устанавливает высоту маркера абзаца без наследования. Значение std::numeric_limits<float>::quiet_NaN() определяет, что маркер наследует высоту от первой части абзаца. Записывает **float**. |
| void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) override | Определяет, имеет ли маркер собственный цвет или наследует его от первой части абзаца. **[NullableBool::True](../nullablebool/)**, если маркер имеет собственный цвет, и **[NullableBool::False](../nullablebool/)**, если маркер наследует цвет от первой части абзаца. Записывает [NullableBool](../nullablebool/). |
| void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) override | Определяет, имеет ли маркер собственный шрифт или наследует его от первой части абзаца. **[NullableBool::True](../nullablebool/)**, если маркер имеет собственный шрифт, и **[NullableBool::False](../nullablebool/)**, если маркер наследует шрифт от первой части абзаца. Записывает [NullableBool](../nullablebool/). |
| void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) override | Устанавливает первое число, используемое для группы нумерованных маркеров без наследования. Записывает **int16_t**. |
| void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) override | Устанавливает стиль нумерованного маркера без наследования. Записывает [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| void [set_Type](./set_type/)([BulletType](../bullettype/)) override | Устанавливает тип маркера абзаца без наследования. Записывает [BulletType](../bullettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
## Смотрите также

* Класс [PVIObject](../pviobject/)
* Класс [IBulletFormat](../ibulletformat/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)