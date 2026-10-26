---
title: ColorFormat
second_title: Справочник API Aspose.Slides для C++
description: Представляет цвет, используемый в презентации.
type: docs
weight: 339
url: /ru/aspose.slides/colorformat/
---
## ColorFormat класс

Представляет цвет, используемый в презентации.

```cpp
class ColorFormat : public Aspose::Slides::PVIObject,
                    public Aspose::Slides::IColorFormat
```

## Методы

| Method | Description |
| --- | --- |
| void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\>) override | Копирует формат цвета из \"color\". |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Проверяет равенство с указанным объектом. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| **uint8_t** [get_B](./get_b/)() override | Возвращает синий компонент цвета. Все преобразования цвета игнорируются. Читает **uint8_t**. |
| [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() override | Возвращает полученный цвет (с примененными всеми преобразованиями цвета). Устанавливает RGB-цвета и очищает все преобразования цвета. Читает [System::Drawing::Color](../../system.drawing/color/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) override | Возвращает операцию преобразования цвета, примененную к цвету по указанному индексу. Чтение/запись [Aspose::Slides::IColorOperation](../icoloroperation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() override | Возвращает коллекцию преобразований цвета, примененных к цвету. Только для чтения [IColorOperationCollection](../icoloroperationcollection/). |
| [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() override | Возвращает метод определения цвета. Читает [Slides::ColorType](../colortype/). |
| **float** [get_FloatB](./get_floatb/)() override | Возвращает синий компонент цвета. Все преобразования цвета игнорируются. Читает **float**. |
| **float** [get_FloatG](./get_floatg/)() override | Возвращает зеленый компонент цвета. Все преобразования цвета игнорируются. Читает **float**. |
| **float** [get_FloatR](./get_floatr/)() override | Возвращает красный компонент цвета. Все преобразования цвета игнорируются. Читает **float**. |
| **uint8_t** [get_G](./get_g/)() override | Возвращает зеленый компонент цвета. Все преобразования цвета игнорируются. |
| **float** [get_Hue](./get_hue/)() override | Возвращает значение тона (hue) цвета в представлении HSL. Все преобразования цвета игнорируются. Читает **float**. |
| **float** [get_Luminance](./get_luminance/)() override | Возвращает значение яркости (luminance) цвета в представлении HSL. Все преобразования цвета игнорируются. Читает **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Возвращает объект Parent_Immediate. Только для чтения [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Возвращает родительский [IPresentationComponent](../ipresentationcomponent/). Только для чтения [IPresentationComponent](../ipresentationcomponent/). |
| [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() override | Возвращает предустановленный цвет. Читает [Slides::PresetColor](../presetcolor/). |
| **uint8_t** [get_R](./get_r/)() override | Возвращает красный компонент цвета. Все преобразования цвета игнорируются. Читает **uint8_t**. |
| **float** [get_Saturation](./get_saturation/)() override | Возвращает значение насыщенности (saturation) цвета в представлении HSL. Все преобразования цвета игнорируются. Читает **float**. |
| [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() override | Возвращает цвет, определенный схемой цветов. Читает [Slides::SchemeColor](../schemecolor/). |
| [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() override | Возвращает цвет, определенный системной таблицей цветов. Читает [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Возвращает хеш-код. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператором C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типа значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счетчик совместных ссылок на указанное значение. |
| void [set_B](./set_b/)(**uint8_t**) override | Устанавливает синий компонент цвета. Все преобразования цвета игнорируются. Записывает **uint8_t**. |
| void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) override | Возвращает полученный цвет (с примененными всеми преобразованиями цвета). Устанавливает RGB-цвета и очищает все преобразования цвета. Записывает [System::Drawing::Color](../../system.drawing/color/). |
| void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) override | Устанавливает операцию преобразования цвета, примененную к цвету по указанному индексу. Чтение/запись [Aspose::Slides::IColorOperation](../icoloroperation/) |
| void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) override | Устанавливает метод определения цвета. Записывает [Slides::ColorType](../colortype/). |
| void [set_FloatB](./set_floatb/)(**float**) override | Устанавливает синий компонент цвета. Все преобразования цвета игнорируются. Записывает **float**. |
| void [set_FloatG](./set_floatg/)(**float**) override | Устанавливает зеленый компонент цвета. Все преобразования цвета игнорируются. Записывает **float**. |
| void [set_FloatR](./set_floatr/)(**float**) override | Устанавливает красный компонент цвета. Все преобразования цвета игнорируются. Записывает **float**. |
| void [set_G](./set_g/)(**uint8_t**) override | Устанавливает зеленый компонент цвета. Все преобразования цвета игнорируются. |
| void [set_Hue](./set_hue/)(**float**) override | Устанавливает значение тона (hue) цвета в представлении HSL. Все преобразования цвета игнорируются. Записывает **float**. |
| void [set_Luminance](./set_luminance/)(**float**) override | Устанавливает значение яркости (luminance) цвета в представлении HSL. Все преобразования цвета игнорируются. Записывает **float**. |
| void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) override | Устанавливает предустановленный цвет. Записывает [Slides::PresetColor](../presetcolor/). |
| void [set_R](./set_r/)(**uint8_t**) override | Устанавливает красный компонент цвета. Все преобразования цвета игнорируются. Записывает **uint8_t**. |
| void [set_Saturation](./set_saturation/)(**float**) override | Устанавливает значение насыщенности (saturation) цвета в представлении HSL. Все преобразования цвета игнорируются. Записывает **float**. |
| void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) override | Устанавливает цвет, определенный схемой цветов. Записывает [Slides::SchemeColor](../schemecolor/). |
| void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) override | Устанавливает цвет, определенный системной таблицей цветов. Записывает [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n'th шаблонный аргумент как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счетчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счетчик совместных ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счетчик совместных ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) override | Возвращает [System::String](../../system/string/), представляющий текущий формат цвета. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператором C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счетчик слабых ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счетчик слабых ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [PVIObject](../pviobject/)
* Класс [IColorFormat](../icolorformat/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)