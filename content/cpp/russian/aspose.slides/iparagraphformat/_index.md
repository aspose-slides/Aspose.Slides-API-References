---
title: IParagraphFormat
second_title: Справочник API Aspose.Slides для C++
description: Этот класс содержит свойства форматирования абзаца. В отличие от IParagraphFormatEffectiveData, все свойства этого класса доступны для записи.
type: docs
weight: 3147
url: /ru/aspose.slides/iparagraphformat/
---
## IParagraphFormat класс


Этот класс содержит свойства форматирования абзаца. В отличие от [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/), все свойства этого класса доступны для записи.

```cpp
class IParagraphFormat : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен какому-либо значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен какому-либо значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | Возвращает выравнивание текста в абзаце без наследования. См. [TextAlignment](../textalignment/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormat](../ibulletformat/)\> [get_Bullet](./get_bullet/)() | Возвращает формат маркера абзаца. Только для чтения [IBulletFormat](../ibulletformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | Возвращает формат части абзаца по умолчанию. Наследование не применяется. Только для чтения [IPortionFormat](../iportionformat/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | Возвращает размер табуляции по умолчанию без наследования. Чтение **float**. |
| virtual **int16_t** [get_Depth](./get_depth/)() | Возвращает глубину абзаца. Значение 0 означает неопределённое значение. Чтение **int16_t**. |
| virtual [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | Определяет, используется ли разрыв строки восточно-азиатского типа в абзаце. Наследование не применяется. См. [NullableBool](../nullablebool/). |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | Возвращает выравнивание шрифта в абзаце без наследования. См. [Slides::FontAlignment](../fontalignment/). |
| virtual [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | Определяет, используется ли висячая пунктуация в абзаце. Наследование не применяется. См. [NullableBool](../nullablebool/). |
| virtual **float** [get_Indent](./get_indent/)() | Возвращает отступ первой строки/висячий отступ абзаца без наследования. Висячий отступ может задаваться отрицательными значениями. Чтение **float**. |
| virtual [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | Определяет, используется ли разрыв строки латинского типа в абзаце. Наследование не применяется. См. [NullableBool](../nullablebool/). |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | Возвращает левый отступ в абзаце без наследования. Чтение **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | Возвращает правый отступ в абзаце без наследования. Чтение **float**. |
| virtual [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() | Определяет, используется ли написание справа налево в абзаце. Наследование не применяется. См. [NullableBool](../nullablebool/). |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | Возвращает величину пространства после последней линии абзаца без наследования. Положительное значение указывает процент от размера шрифта, который должен занимать пробел. Отрицательное значение задаёт размер пробела в пунктах. Чтение **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | Возвращает величину пространства перед первой линией абзаца без наследования. Положительное значение указывает процент от размера шрифта, который должен занимать пробел. Отрицательное значение задаёт размер пробела в пунктах. Чтение **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | Возвращает величину пространства между базовыми линиями абзаца. Положительное значение означает процент, отрицательное — размер в пунктах. Наследование не применяется. Чтение **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) | Возвращает табуляцию абзаца по указанному индексу. Наследование не применяется. Только для чтения [Aspose::Slides::ITab](../itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() | Возвращает табуляции абзаца. Наследование не применяется. Только для чтения [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() | Получает эффективные данные форматирования абзаца с применённым наследованием. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать при построении подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать при построении подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик разделяемых ссылок на указанное значение. |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) | Устанавливает выравнивание текста в абзаце без наследования. Запись [TextAlignment](../textalignment/). |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | Устанавливает размер табуляции по умолчанию без наследования. Запись **float**. |
| virtual void [set_Depth](./set_depth/)(**int16_t**) | Устанавливает глубину абзаца. Значение 0 означает неопределённое значение. Запись **int16_t**. |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) | Определяет, используется ли разрыв строки восточно-азиатского типа в абзаце. Наследование не применяется. Запись [NullableBool](../nullablebool/). |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) | Устанавливает выравнивание шрифта в абзаце без наследования. Запись [Slides::FontAlignment](../fontalignment/). |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) | Определяет, используется ли висячая пунктуация в абзаце. Наследование не применяется. Запись [NullableBool](../nullablebool/). |
| virtual void [set_Indent](./set_indent/)(**float**) | Устанавливает отступ первой строки/висячий отступ абзаца без наследования. Висячий отступ может задаваться отрицательными значениями. Запись **float**. |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) | Определяет, используется ли разрыв строки латинского типа в абзаце. Наследование не применяется. Запись [NullableBool](../nullablebool/). |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | Устанавливает левый отступ в абзаце без наследования. Запись **float**. |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | Устанавливает правый отступ в абзаце без наследования. Запись **float**. |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) | Определяет, используется ли написание справа налево в абзаце. Наследование не применяется. Запись [NullableBool](../nullablebool/). |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | Устанавливает величину пространства после последней линии абзаца без наследования. Положительное значение указывает процент от размера шрифта, который должен занимать пробел. Отрицательное значение задаёт размер пробела в пунктах. Запись **float**. |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | Устанавливает величину пространства перед первой линией абзаца без наследования. Положительное значение указывает процент от размера шрифта, который должен занимать пробел. Отрицательное значение задаёт размер пробела в пунктах. Запись **float**. |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | Устанавливает величину пространства между базовыми линиями абзаца. Положительное значение означает процент, отрицательное — размер в пунктах. Наследование не применяется. Запись **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (вместо разделяемого). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика разделяемых ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик разделяемых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик разделяемых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
## Примечания


Этот класс используется для получения и изменения свойств форматирования абзаца, определённых для конкретного абзаца. Это означает, что при получении значений наследование не применяется, поэтому в большинстве случаев вы получите значения, означающие «неопределено».

Чтобы получить эффективные значения параметров форматирования с учётом наследования, необходимо использовать метод [IParagraphFormat::GetEffective](./geteffective/), который возвращает экземпляр [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/).

## См. также

* Класс [Object](../../system/object/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)