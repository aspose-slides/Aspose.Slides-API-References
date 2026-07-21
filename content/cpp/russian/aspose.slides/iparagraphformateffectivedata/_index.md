---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides для C++ справочник API
description: Неизменяемый объект, содержащий эффективные свойства форматирования абзаца.
type: docs
weight: 3160
url: /ru/aspose.slides/iparagraphformateffectivedata/
---
## IParagraphFormatEffectiveData класс

Неизменяемый объект, содержащий эффективные свойства форматирования абзаца.

```cpp
class IParagraphFormatEffectiveData : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типа значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | Возвращает выравнивание текста в абзаце. Только для чтения [TextAlignment](../textalignment/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [get_Bullet](./get_bullet/)() | Возвращает формат маркера абзаца. Только для чтения [IBulletFormatEffectiveData](../ibulletformateffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | Возвращает формат части по умолчанию абзаца. Только для чтения [IPortionFormatEffectiveData](../iportionformateffectivedata/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | Возвращает размер табуляции по умолчанию. Только для чтения **float**. |
| virtual **int16_t** [get_Depth](./get_depth/)() | Возвращает глубину абзаца. Только для чтения **int16_t**. |
| virtual **bool** [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | Определяет, используется ли разрыв строки восточноазиатский в абзаце. Только для чтения **bool**. |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | Возвращает выравнивание шрифта в абзаце. Только для чтения [Slides::FontAlignment](../fontalignment/). |
| virtual **bool** [get_HangingPunctuation](./get_hangingpunctuation/)() | Определяет, используется ли висячая пунктуация в абзаце. Только для чтения **bool**. |
| virtual **float** [get_Indent](./get_indent/)() | Возвращает отступ первой строки/висячий отступ абзаца. Висячий отступ может задаваться отрицательными значениями. Только для чтения **float**. |
| virtual **bool** [get_LatinLineBreak](./get_latinlinebreak/)() | Определяет, используется ли разрыв строки латинский в абзаце. Только для чтения **bool**. |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | Возвращает левый отступ в абзаце. Только для чтения **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | Возвращает правый отступ в абзаце. Только для чтения **float**. |
| virtual **bool** [get_RightToLeft](./get_righttoleft/)() | Определяет, используется ли написание справа налево в абзаце. Только для чтения **bool**. |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | Возвращает количество пространства после последней строки в абзаце. Только для чтения **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | Возвращает количество пространства перед первой строкой в абзаце. Только для чтения **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | Возвращает количество пространства между базовыми строками в абзаце. Только для чтения **float**. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITabEffectiveData](../itabeffectivedata/)\>\> [get_Tabs](./get_tabs/)() | Возвращает табуляции абзаца. Только для чтения [ITabEffectiveData](../itabeffectivedata/)[]. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать при построении подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать при построении подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект типа значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счетчик разделяемых ссылок на указанное значение. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не разделяемый). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика разделяемых ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик разделяемых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик разделяемых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Замечания

Этот интерфейс используется вместе с интерфейсом [IParagraphFormat](../iparagraphformat/) для возврата эффективных значений форматирования с применённым наследованием. 

## См. также

* Класс [Object](../../system/object/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)