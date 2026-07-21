---
title: IBasePortionFormat
second_title: Aspose.Slides для C++ справочник API
description: Этот класс содержит свойства форматирования текстовых фрагментов. В отличие от IPortionFormatEffectiveData, все свойства этого класса доступны для записи.
type: docs
weight: 1457
url: /ru/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat класс


Этот класс содержит свойства форматирования текстовых фрагментов. В отличие от [IPortionFormatEffectiveData](../iportionformateffectivedata/), все свойства этого класса доступны для записи.

```cpp
class IBasePortionFormat : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типажа значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | Возвращает идентификатор альтернативного языка. См. [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | Возвращает информацию о шрифте сложного письма. Null означает, что шрифт неопределён и должен наследоваться от Master. См. [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | Возвращает информацию о шрифте восточноазиатского письма. Null означает, что шрифт неопределён и должен наследоваться от Master. См. [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | Возвращает свойства текста [EffectFormat](../effectformat/). Наследование не применяется. Только для чтения [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](./get_escapement/)() | Возвращает надстрочный или нижний индекс текста. Значение от -100% (нижний индекс) до 100% (надстрочный). **std::numeric_limits<float>::quiet_NaN()** означает, что значение неопределено и должно наследоваться от Master. Только чтение **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | Возвращает свойства текста [FillFormat](../fillformat/). Наследование не применяется. Только для чтения [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() | Определяет, является ли шрифт полужирным. Наследование не применяется. См. [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](./get_fontheight/)() | Возвращает высоту шрифта фрагмента. **std::numeric_limits<float>::quiet_NaN()** означает, что высота неопределена и должна наследоваться от Master. Только чтение **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() | Определяет, является ли шрифт курсивным. Наследование не применяется. См. [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | Возвращает тип подчеркивания текста. Наследование не применяется. См. [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() | Возвращает цвет, используемый для выделения текста. Наследование не применяется. Только для чтения [IColorFormat](../icolorformat/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | Определяет, имеет ли стиль подчеркивания собственные свойства [FillFormat](../fillformat/) или наследует их из свойств текста [FillFormat](../fillformat/). См. [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | Определяет, имеет ли стиль подчеркивания собственные свойства [LineFormat](../lineformat/) или наследует их из свойств текста [LineFormat](../lineformat/). См. [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | Возвращает минимальный размер шрифта, при котором включается кернинг. **std::numeric_limits<float>::quiet_NaN()** означает, что значение неопределено и должно наследоваться от Master. Только чтение **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() | Определяет, должны ли числа игнорировать специфическую для восточных языков вертикальную раскладку текста. Наследование не применяется. См. [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | Возвращает идентификатор языка проверки. Используется для проверки орфографии и грамматики. См. [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | Возвращает информацию о латинском шрифте. Null означает, что шрифт неопределён и должен наследоваться от Master. См. [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | Возвращает свойства [LineFormat](../lineformat/) для контурирования текста. Наследование не применяется. Только для чтения [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() | Определяет, должна ли высота текста быть нормализована. Наследование не применяется. См. [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() | Определяет, не следует ли проверять текст. Наследование не применяется. См. [NullableBool](../nullablebool/). |
| virtual **float** [get_Spacing](./get_spacing/)() | Возвращает увеличение межсимвольного интервала. **std::numeric_limits<float>::quiet_NaN()** означает, что значение неопределено и должно наследоваться от Master. Только чтение **float**. |
| virtual **bool** [get_SpellCheck](./get_spellcheck/)() | Получает значение, указывающее, включена ли проверка орфографии для текстового фрагмента. Когда это свойство установлено в false, проверки орфографии для текстовых элементов подавляются. Когда установлено в true, проверка орфографии разрешена. Значение по умолчанию — **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | Возвращает тип зачеркивания текста. Наследование не применяется. См. [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | Возвращает информацию о символическом шрифте. Null означает, что шрифт неопределён и должен наследоваться от Master. См. [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | Возвращает тип капитализации текста. Наследование не применяется. См. [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | Возвращает свойства линии подчеркивания [FillFormat](../fillformat/). Наследование не применяется. Только для чтения [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | Возвращает свойства [LineFormat](../lineformat/), используемые для контурного подчеркивания линии. Наследование не применяется. Только для чтения [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-охранник [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает ссылкой объект типажа значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) | Устанавливает идентификатор альтернативного языка. Записать [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Устанавливает информацию о шрифте сложного письма. Null означает, что шрифт неопределён и должен наследоваться от Master. Записать [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Устанавливает информацию о шрифте восточноазиатского письма. Null означает, что шрифт неопределён и должен наследоваться от Master. Записать [IFontData](../ifontdata/). |
| virtual void [set_Escapement](./set_escapement/)(**float**) | Устанавливает надстрочный или нижний индекс текста. Значение от -100% (нижний индекс) до 100% (надстрочный). **std::numeric_limits<float>::quiet_NaN()** означает, что значение неопределено и должно наследоваться от Master. Записать **float**. |
| virtual void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) | Определяет, является ли шрифт полужирным. Наследование не применяется. Записать [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](./set_fontheight/)(**float**) | Устанавливает высоту шрифта фрагмента. **std::numeric_limits<float>::quiet_NaN()** означает, что высота неопределена и должна наследоваться от Master. Записать **float**. |
| virtual void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) | Определяет, является ли шрифт курсивным. Наследование не применяется. Записать [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | Устанавливает тип подчеркивания текста. Наследование не применяется. Записать [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | Определяет, имеет ли стиль подчеркивания собственные свойства [FillFormat](../fillformat/) или наследует их из свойств текста [FillFormat](../fillformat/). Записать [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) | Определяет, имеет ли стиль подчеркивания собственные свойства [LineFormat](../lineformat/) или наследует их из свойств текста [LineFormat](../lineformat/). Записать [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) | Устанавливает минимальный размер шрифта, при котором включается кернинг. **std::numeric_limits<float>::quiet_NaN()** означает, что значение неопределено и должно наследоваться от Master. Записать **float**. |
| virtual void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) | Определяет, должны ли числа игнорировать специфическую для восточных языков вертикальную раскладку текста. Наследование не применяется. Записать [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) | Устанавливает идентификатор языка проверки. Используется для проверки орфографии и грамматики. Записать [System::String](../../system/string/). |
| virtual void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Устанавливает информацию о латинском шрифте. Null означает, что шрифт неопределён и должен наследоваться от Master. Записать [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) | Определяет, должна ли высота текста быть нормализована. Наследование не применяется. Записать [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) | Определяет, не следует ли проверять текст. Наследование не применяется. Записать [NullableBool](../nullablebool/). |
| virtual void [set_Spacing](./set_spacing/)(**float**) | Устанавливает увеличение межсимвольного интервала. **std::numeric_limits<float>::quiet_NaN()** означает, что значение неопределено и должно наследоваться от Master. Записать **float**. |
| virtual void [set_SpellCheck](./set_spellcheck/)(**bool**) | Устанавливает значение, указывающее, включена ли проверка орфографии для текстового фрагмента. Когда это свойство установлено в false, проверки орфографии для текстовых элементов подавляются. Когда установлено в true, проверка орфографии разрешена. Значение по умолчанию — **false**. |
| virtual void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | Устанавливает тип зачеркивания текста. Наследование не применяется. Записать [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Устанавливает информацию о символическом шрифте. Null означает, что шрифт неопределён и должен наследоваться от Master. Записать [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | Устанавливает тип капитализации текста. Наследование не применяется. Записать [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-охранник [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Замечания


Этот класс используется для получения и изменения свойств форматирования текстовых фрагментов, определённых для конкретного фрагмента. Это означает, что при получении значений наследование не применяется, поэтому в большинстве случаев вы получите значения, означающие «неопределено».

Чтобы получить эффективные значения параметров форматирования, включая унаследованные, необходимо использовать метод [IPortionFormat::GetEffective](../iportionformat/geteffective/), который возвращает экземпляр [IPortionFormatEffectiveData](../iportionformateffectivedata/).

## См. также

* Класс [Object](../../system/object/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)