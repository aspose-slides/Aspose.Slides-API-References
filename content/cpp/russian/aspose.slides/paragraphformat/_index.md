---
title: ParagraphFormat
second_title: Справочник API Aspose.Slides для C++
description: Этот класс содержит свойства форматирования абзаца. В отличие от IParagraphFormatEffectiveData, все свойства этого класса доступны для записи.
type: docs
weight: 4668
url: /ru/aspose.slides/paragraphformat/
---
## ParagraphFormat класс


This class contains the paragraph formatting properties. Unlike [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/), all properties of this class are writeable.

```cpp
class ParagraphFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IParagraphFormat,
                        public Aspose::Slides::Charts::IChartParagraphFormat
```

## Методы

| Метод | Описание |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Сравнивает с указанным объектом. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних нужд. |
| [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() override | Возвращает выравнивание текста в абзаце без наследования. Читать [TextAlignment](../textalignment/). |
| **float** [get_DefaultTabSize](./get_defaulttabsize/)() override | Возвращает размер табуляции по умолчанию без наследования. Читать **float**. |
| [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() override | Определяет, используется ли разрыв строки Восточной Азии в абзаце. Наследование не применяется. Читать [NullableBool](../nullablebool/). |
| [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() override | Возвращает выравнивание шрифта в абзаце без наследования. Читать [Slides::FontAlignment](../fontalignment/). |
| [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() override | Определяет, используется ли висячая пунктуация в абзаце. Наследование не применяется. Читать [NullableBool](../nullablebool/). |
| **float** [get_Indent](./get_indent/)() override | Возвращает отступ первой строки/висячий отступ абзаца без наследования. Висячий отступ может быть задан отрицательными значениями. Читать **float**. |
| [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() override | Определяет, используется ли латинский разрыв строки в абзаце. Наследование не применяется. Читать [NullableBool](../nullablebool/). |
| **float** [get_MarginLeft](./get_marginleft/)() override | Возвращает левый отступ в абзаце без наследования. Читать **float**. |
| **float** [get_MarginRight](./get_marginright/)() override | Возвращает правый отступ в абзаце без наследования. Читать **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Возвращает объект Parent_Immediate. Только для чтения [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Возвращает родитель [IPresentationComponent](../ipresentationcomponent/). Только для чтения [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() override | Определяет, используется ли написание справа налево в абзаце. Наследование не применяется. Читать [NullableBool](../nullablebool/). |
| **float** [get_SpaceAfter](./get_spaceafter/)() override | Возвращает количество пространства после последней строки в абзаце без наследования. Положительное значение указывает процент от размера шрифта, который должен занимать пробел. Отрицательное значение задает размер пробела в пунктах. Читать **float**. |
| **float** [get_SpaceBefore](./get_spacebefore/)() override | Возвращает количество пространства перед первой строкой в абзаце без наследования. Положительное значение указывает процент от размера шрифта, который должен занимать пробел. Отрицательное значение задает размер пробела в пунктах. Читать **float**. |
| **float** [get_SpaceWithin](./get_spacewithin/)() override | Возвращает количество пространства между базовыми линиями в абзаце. Положительное значение означает процент, отрицательное — размер в пунктах. Наследование не применяется. Читать **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) override | Возвращает табуляцию абзаца по указанному индексу. Наследование не применяется. Только для чтения [Aspose::Slides::ITab](../itab/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() override | Возвращает табуляции абзаца. Наследование не применяется. Только для чтения [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() override | Получает эффективные данные форматирования абзаца с применённым наследованием. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Возвращает хэш-код. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
|  [ParagraphFormat](./paragraphformat/)() | Инициализирует новый экземпляр класса [ParagraphFormat](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект типа значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) override | Устанавливает выравнивание текста в абзаце без наследования. Записать [TextAlignment](../textalignment/). |
| void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) override | Устанавливает размер табуляции по умолчанию без наследования. Записать **float**. |
| void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) override | Определяет, используется ли разрыв строки Восточной Азии в абзаце. Наследование не применяется. Записать [NullableBool](../nullablebool/). |
| void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) override | Устанавливает выравнивание шрифта в абзаце без наследования. Записать [Slides::FontAlignment](../fontalignment/). |
| void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) override | Определяет, используется ли висячая пунктуация в абзаце. Наследование не применяется. Записать [NullableBool](../nullablebool/). |
| void [set_Indent](./set_indent/)(**float**) override | Устанавливает отступ первой строки/висячий отступ абзаца без наследования. Висячий отступ может быть задан отрицательными значениями. Записать **float**. |
| void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) override | Определяет, используется ли латинский разрыв строки в абзаце. Наследование не применяется. Записать [NullableBool](../nullablebool/). |
| void [set_MarginLeft](./set_marginleft/)(**float**) override | Устанавливает левый отступ в абзаце без наследования. Записать **float**. |
| void [set_MarginRight](./set_marginright/)(**float**) override | Устанавливает правый отступ в абзаце без наследования. Записать **float**. |
| void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) override | Определяет, используется ли написание справа налево в абзаце. Наследование не применяется. Записать [NullableBool](../nullablebool/). |
| void [set_SpaceAfter](./set_spaceafter/)(**float**) override | Устанавливает количество пространства после последней строки в абзаце без наследования. Положительное значение указывает процент от размера шрифта, который должен занимать пробел. Отрицательное значение задает размер пробела в пунктах. Записать **float**. |
| void [set_SpaceBefore](./set_spacebefore/)(**float**) override | Устанавливает количество пространства перед первой строкой в абзаце без наследования. Положительное значение указывает процент от размера шрифта, который должен занимать пробел. Отрицательное значение задает размер пробела в пунктах. Записать **float**. |
| void [set_SpaceWithin](./set_spacewithin/)(**float**) override | Устанавливает количество пространства между базовыми линиями в абзаце. Положительное значение означает процент, отрицательное — размер в пунктах. Наследование не применяется. Записать **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-е шаблонное аргумент как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим слабых. |
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
## Замечания


Этот класс используется для получения и изменения свойств форматирования абзаца, определённых для конкретного абзаца. Это означает, что при получении значений наследование не применяется, поэтому в большинстве случаев вы получите значения, означающие «неопределено».

Чтобы получить эффективные значения параметров форматирования, включая унаследованные, необходимо использовать метод [ParagraphFormat::GetEffective](./geteffective/), который возвращает экземпляр [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/).

## См. также

* Класс [PVIObject](../pviobject/)
* Класс [IParagraphFormat](../iparagraphformat/)
* Класс [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)