---
title: IColorFormat
second_title: Справочник API Aspose.Slides для C++
description: Представляет цвет, используемый в презентации.
type: docs
weight: 1691
url: /ru/aspose.slides/icolorformat/
---
## IColorFormat класс

Represents a color used in a presentation.

```cpp
class IColorFormat : public Aspose::Slides::IFillParamSource
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](./)\>) | Копирует формат цвета из \"color\". |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типовых значений в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| virtual **uint8_t** [get_B](./get_b/)() | Возвращает синий компонент цвета. Все преобразования цвета игнорируются. Чтение **uint8_t**. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() | Возвращает полученный цвет (со всеми применёнными преобразованиями цвета). Устанавливает цвета RGB и очищает все преобразования цвета. Чтение [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) | Возвращает операцию преобразования цвета, применённую к цвету по указанному индексу. Чтение/запись [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() | Возвращает коллекцию преобразований цвета, применённых к цвету. Только для чтения [IColorOperationCollection](../icoloroperationcollection/). |
| virtual [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() | Возвращает метод определения цвета. Чтение [Slides::ColorType](../colortype/). |
| virtual **float** [get_FloatB](./get_floatb/)() | Возвращает синий компонент цвета. Все преобразования цвета игнорируются. Чтение **float**. |
| virtual **float** [get_FloatG](./get_floatg/)() | Возвращает зелёный компонент цвета. Все преобразования цвета игнорируются. Чтение **float**. |
| virtual **float** [get_FloatR](./get_floatr/)() | Возвращает красный компонент цвета. Все преобразования цвета игнорируются. Чтение **float**. |
| virtual **uint8_t** [get_G](./get_g/)() | Возвращает зелёный компонент цвета. Все преобразования цвета игнорируются. Чтение **uint8_t**. |
| virtual **float** [get_Hue](./get_hue/)() | Возвращает компонент оттенка цвета в представлении HSL. Все преобразования цвета игнорируются. Чтение **float**. |
| virtual **float** [get_Luminance](./get_luminance/)() | Возвращает компонент светлоты цвета в представлении HSL. Все преобразования цвета игнорируются. Чтение **float**. |
| virtual [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() | Возвращает предустановку цвета. Чтение [Slides::PresetColor](../presetcolor/). |
| virtual **uint8_t** [get_R](./get_r/)() | Возвращает красный компонент цвета. Все преобразования цвета игнорируются. Чтение **uint8_t**. |
| virtual **float** [get_Saturation](./get_saturation/)() | Возвращает компонент насыщения цвета в представлении HSL. Все преобразования цвета игнорируются. Чтение **float**. |
| virtual [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() | Возвращает цвет, определённый цветовой схемой. Чтение [Slides::SchemeColor](../schemecolor/). |
| virtual [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() | Возвращает цвет, определённый системной таблицей цветов. Чтение [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типового значения по ссылке с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual void [set_B](./set_b/)(**uint8_t**) | Устанавливает синий компонент цвета. Все преобразования цвета игнорируются. Запись **uint8_t**. |
| virtual void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) | Возвращает полученный цвет (со всеми применёнными преобразованиями цвета). Устанавливает цвета RGB и очищает все преобразования цвета. Запись [System::Drawing::Color](../../system.drawing/color/). |
| virtual void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) | Устанавливает операцию преобразования цвета, применяемую к цвету по указанному индексу. Чтение/запись [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) | Устанавливает метод определения цвета. Запись [Slides::ColorType](../colortype/). |
| virtual void [set_FloatB](./set_floatb/)(**float**) | Устанавливает синий компонент цвета. Все преобразования цвета игнорируются. Запись **float**. |
| virtual void [set_FloatG](./set_floatg/)(**float**) | Устанавливает зелёный компонент цвета. Все преобразования цвета игнорируются. Запись **float**. |
| virtual void [set_FloatR](./set_floatr/)(**float**) | Устанавливает красный компонент цвета. Все преобразования цвета игнорируются. Запись **float**. |
| virtual void [set_G](./set_g/)(**uint8_t**) | Устанавливает зелёный компонент цвета. Все преобразования цвета игнорируются. Запись **uint8_t**. |
| virtual void [set_Hue](./set_hue/)(**float**) | Устанавливает компонент оттенка цвета в представлении HSL. Все преобразования цвета игнорируются. Запись **float**. |
| virtual void [set_Luminance](./set_luminance/)(**float**) | Устанавливает компонент светлоты цвета в представлении HSL. Все преобразования цвета игнорируются. Запись **float**. |
| virtual void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) | Устанавливает предустановку цвета. Запись [Slides::PresetColor](../presetcolor/). |
| virtual void [set_R](./set_r/)(**uint8_t**) | Устанавливает красный компонент цвета. Все преобразования цвета игнорируются. Запись **uint8_t**. |
| virtual void [set_Saturation](./set_saturation/)(**float**) | Устанавливает компонент насыщения цвета в представлении HSL. Все преобразования цвета игнорируются. Запись **float**. |
| virtual void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) | Устанавливает цвет, определённый цветовой схемой. Запись [Slides::SchemeColor](../schemecolor/). |
| virtual void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) | Устанавливает цвет, определённый системной таблицей цветов. Запись [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный параметр как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) | Возвращает [System::String](../../system/string/), представляющий текущий формат цвета. |
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