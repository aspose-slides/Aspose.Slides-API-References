---
title: IBasePortionFormatEffectiveData
second_title: Справочник API Aspose.Slides для C++
description: Базовый интерфейс для неизменяемых объектов, содержащих свойства форматирования эффективных фрагментов текста.
type: docs
weight: 1470
url: /ru/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData класс


Базовый интерфейс для неизменяемых объектов, содержащих свойства форматирования эффективных текстовых фрагментов.

```cpp
class IBasePortionFormatEffectiveData : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | Возвращает идентификатор альтернативного языка. Только для чтения [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | Возвращает информацию о шрифте сложных сценариев. Только для чтения [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | Возвращает информацию о восточноазиатском шрифте. Только для чтения [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [get_EffectFormat](./get_effectformat/)() | Возвращает свойства текста [EffectFormat](../effectformat/). Только для чтения [IEffectFormatEffectiveData](../ieffectformateffectivedata/). |
| virtual **float** [get_Escapement](./get_escapement/)() | Возвращает надстрочный или подстрочный текст. Значение от -100% (подстрочный) до 100% (надстрочный). Только для чтения **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_FillFormat](./get_fillformat/)() | Возвращает свойства текста [FillFormat](../fillformat/). Только для чтения [IFillFormatEffectiveData](../ifillformateffectivedata/). |
| virtual **bool** [get_FontBold](./get_fontbold/)() | Определяет, является ли шрифт полужирным. Только для чтения **bool**. |
| virtual **float** [get_FontHeight](./get_fontheight/)() | Возвращает высоту шрифта текстового фрагмента в пунктах. Только для чтения **float**. |
| virtual **bool** [get_FontItalic](./get_fontitalic/)() | Определяет, является ли шрифт курсивным. Только для чтения **bool**. |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | Возвращает тип подчеркивания текста. Только для чтения [TextUnderlineType](../textunderlinetype/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_HighlightColor](./get_highlightcolor/)() | Возвращает цвет, используемый для выделения текста. Только для чтения [System::Drawing::Color](../../system.drawing/color/). |
| virtual **bool** [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | Определяет, имеет ли стиль подчеркивания собственные свойства [FillFormat](../fillformat/) или наследует их из свойств [FillFormat](../fillformat/) текста. Только для чтения **bool**. |
| virtual **bool** [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | Определяет, имеет ли стиль подчеркивания собственные свойства [LineFormat](../lineformat/) или наследует их из свойств [LineFormat](../lineformat/) текста. Только для чтения **bool**. |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | Возвращает минимальный размер шрифта, при котором включается кернинг. Только для чтения **float**. |
| virtual **bool** [get_Kumimoji](./get_kumimoji/)() | Определяет, должны ли числа игнорировать специфическую для восточных языков вертикальную компоновку текста. Только для чтения **bool**. |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | Возвращает идентификатор языка. Только для чтения [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | Возвращает информацию о латинском шрифте. Только для чтения [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_LineFormat](./get_lineformat/)() | Возвращает свойства [LineFormat](../lineformat/) для обводки текста. Только для чтения [ILineFormatEffectiveData](../ilineformateffectivedata/). |
| virtual **bool** [get_NormaliseHeight](./get_normaliseheight/)() | Определяет, должна ли высота текста быть нормализована. Только для чтения **bool**. |
| virtual **bool** [get_ProofDisabled](./get_proofdisabled/)() | Определяет, не следует ли проверять текст. Только для чтения **bool**. |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | Определяет, следует ли очищать смарт-тег. Только для чтения **bool**. |
| virtual **float** [get_Spacing](./get_spacing/)() | Возвращает увеличение межсимвольного интервала в пунктах. Только для чтения **float**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | Возвращает тип зачеркивания текста. Только для чтения [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | Возвращает информацию о символьном шрифте. Только для чтения [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | Возвращает тип капитализации текста. Только для чтения [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | Возвращает свойства линии подчеркивания [FillFormat](../fillformat/). Только для чтения [IFillFormatEffectiveData](../ifillformateffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | Возвращает свойства [LineFormat](../lineformat/), используемые для обводки линии подчеркивания. Только для чтения [ILineFormatEffectiveData](../ilineformateffectivedata/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанного с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счетчик совместных ссылок на указанное значение. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим слабых. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счетчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счетчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает значение счетчика совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
## Смотрите также

* Класс [Object](../../system/object/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)