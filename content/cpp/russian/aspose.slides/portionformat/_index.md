---
title: PortionFormat
second_title: Aspose.Slides для C++ справка API
description: Этот класс содержит свойства форматирования текстовых частей. В отличие от IPortionFormatEffectiveData, все свойства этого класса доступны для записи.
type: docs
weight: 4811
url: /ru/aspose.slides/portionformat/
---
## PortionFormat класс

Этот класс содержит свойства форматирования текстовых частей. В отличие от [IPortionFormatEffectiveData](../iportionformateffectivedata/), все свойства этого класса доступны для записи.

```cpp
class PortionFormat : public Aspose::Slides::BasePortionFormat,
                      public Aspose::Slides::IPortionFormat
```

## Методы

| Method | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Сравнивает с указанным объектом. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../baseportionformat/get_alternativelanguageid/)() override | Возвращает идентификатор альтернативного языка. Читать [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() override | Возвращает идентификатор закладки. Читать [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../baseportionformat/get_complexscriptfont/)() override | Возвращает информацию о шрифте сложных сценариев. Null означает, что шрифт неопределён и должен наследоваться от Master. Читать [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../baseportionformat/get_eastasianfont/)() override | Возвращает информацию о шрифте восточноазиатского текста. Null означает, что шрифт неопределён и должен наследоваться от Master. Читать [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../baseportionformat/get_effectformat/)() override | Возвращает свойства текста [EffectFormat](../effectformat/). Наследование не применяется. Только для чтения [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](../baseportionformat/get_escapement/)() override | Возвращает надстрочный или подстрочный текст. Значение от -100% (подстрочный) до 100% (надстрочный). **std::numeric_limits<float>::quiet_NaN()** означает, что значение неопределено и должно наследоваться от Master. Читать **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../baseportionformat/get_fillformat/)() override | Возвращает свойства текста [FillFormat](../fillformat/). Наследование не применяется. Только для чтения [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](../baseportionformat/get_fontbold/)() override | Определяет, является ли шрифт жирным. Наследование не применяется. Читать [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](../baseportionformat/get_fontheight/)() override | Возвращает высоту шрифта части. **std::numeric_limits<float>::quiet_NaN()** означает, что высота неопределена и должна наследоваться от Master. Читать **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](../baseportionformat/get_fontitalic/)() override | Определяет, является ли шрифт курсивным. Наследование не применяется. Читать [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../baseportionformat/get_fontunderline/)() override | Возвращает тип подчеркивания текста. Наследование не применяется. Читать [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../baseportionformat/get_highlightcolor/)() override | Возвращает цвет, используемый для выделения текста. Наследование не применяется. Только для чтения [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | Возвращает гиперссылку, определённую для щелчка мышью. Читать [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | Менеджер гиперссылок. Только для чтения [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | Возвращает гиперссылку, определённую для наведения мышью. Читать [IHyperlink](../ihyperlink/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../baseportionformat/get_ishardunderlinefill/)() override | Определяет, имеет ли стиль подчеркивания собственные свойства [FillFormat](../fillformat/) или наследует их от свойств [FillFormat](../fillformat/) текста. Читать [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../baseportionformat/get_ishardunderlineline/)() override | Определяет, имеет ли стиль подчеркивания собственные свойства [LineFormat](../lineformat/) или наследует их от свойств [LineFormat](../lineformat/) текста. Читать [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](../baseportionformat/get_kerningminimalsize/)() override | Возвращает минимальный размер шрифта, при котором следует включать кернинг. **std::numeric_limits<float>::quiet_NaN()** означает, что значение неопределено и должно наследоваться от Master. Читать **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](../baseportionformat/get_kumimoji/)() override | Определяет, должны ли числа игнорировать вертикальное расположение текста, специфичное для восточных языков. Наследование не применяется. Читать [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](../baseportionformat/get_languageid/)() override | Возвращает идентификатор языка проверки. Используется для проверки орфографии и грамматики. Читать [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../baseportionformat/get_latinfont/)() override | Возвращает информацию о латинском шрифте. Null означает, что шрифт неопределён и должен наследоваться от Master. Читать [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../baseportionformat/get_lineformat/)() override | Возвращает свойства [LineFormat](../lineformat/) для обводки текста. Наследование не применяется. Только для чтения [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](../baseportionformat/get_normaliseheight/)() override | Определяет, следует ли нормализовать высоту текста. Наследование не применяется. Читать [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Возвращает объект Parent_Immediate. Только для чтения [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Возвращает родительский [IPresentationComponent](../ipresentationcomponent/). Только для чтения [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](../baseportionformat/get_proofdisabled/)() override | Определяет, не следует ли проверять текст. Наследование не применяется. Читать [NullableBool](../nullablebool/). |
| **bool** [get_SmartTagClean](./get_smarttagclean/)() override | Определяет, следует ли очищать смарт-тег. Наследование не применяется. Читать **bool**. |
| **float** [get_Spacing](../baseportionformat/get_spacing/)() override | Возвращает приращение межсимвольного интервала. **std::numeric_limits<float>::quiet_NaN()** означает, что значение неопределено и должно наследоваться от Master. Читать **float**. |
| **bool** [get_SpellCheck](../baseportionformat/get_spellcheck/)() override | Получает значение, указывающее, включена ли проверка правописания для части текста. Когда свойство установлено в false, проверки правописания для текстовых элементов подавляются. Когда установлено в true, проверка правописания разрешена. Значение по умолчанию — **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../baseportionformat/get_strikethroughtype/)() override | Возвращает тип зачеркивания текста. Наследование не применяется. Читать [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../baseportionformat/get_symbolfont/)() override | Возвращает информацию о символическом шрифте. Null означает, что шрифт неопределён и должен наследоваться от Master. Читать [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../baseportionformat/get_textcaptype/)() override | Возвращает тип капитализации текста. Наследование не применяется. Читать [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../baseportionformat/get_underlinefillformat/)() override | Возвращает свойства линии подчёркивания [FillFormat](../fillformat/). Наследование не применяется. Только для чтения [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../baseportionformat/get_underlinelineformat/)() override | Возвращает свойства [LineFormat](../lineformat/), используемые для обводки линии подчёркивания. Наследование не применяется. Только для чтения [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() override | Получает эффективные данные форматирования части с применённым наследованием. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Возвращает хеш-код. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструктором подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструктором подклассы. |
|  [PortionFormat](./portionformat/)() | Инициализирует новый экземпляр класса [PortionFormat](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик разделяемых ссылок на указанное значение. |
| void [set_AlternativeLanguageId](../baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | Устанавливает идентификатор альтернативного языка. Записать [System::String](../../system/string/). |
| void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) override | Устанавливает идентификатор закладки. Записать [System::String](../../system/string/). |
| void [set_ComplexScriptFont](../baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Устанавливает информацию о шрифте сложных сценариев. Null означает, что шрифт неопределён и должен наследоваться от Master. Записать [IFontData](../ifontdata/). |
| void [set_EastAsianFont](../baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Устанавливает информацию о восточноазиатском шрифте. Null означает, что шрифт неопределён и должен наследоваться от Master. Записать [IFontData](../ifontdata/). |
| void [set_Escapement](../baseportionformat/set_escapement/)(**float**) override | Устанавливает надстрочный или подстрочный текст. Значение от -100% (подстрочный) до 100% (надстрочный). **std::numeric_limits<float>::quiet_NaN()** означает, что значение неопределено и должно наследоваться от Master. Записать **float**. |
| void [set_FontBold](../baseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) override | Определяет, является ли шрифт жирным. Наследование не применяется. Записать [NullableBool](../nullablebool/). |
| void [set_FontHeight](../baseportionformat/set_fontheight/)(**float**) override | Устанавливает высоту шрифта части. **std::numeric_limits<float>::quiet_NaN()** означает, что высота неопределена и должна наследоваться от Master. Записать **float**. |
| void [set_FontItalic](../baseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) override | Определяет, является ли шрифт курсивным. Наследование не применяется. Записать [NullableBool](../nullablebool/). |
| void [set_FontUnderline](../baseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | Устанавливает тип подчеркивания текста. Наследование не применяется. Записать [TextUnderlineType](../textunderlinetype/). |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Устанавливает гиперссылку, определённую для щелчка мышью. Записать [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Устанавливает гиперссылку, определённую для наведения мышью. Записать [IHyperlink](../ihyperlink/). |
| void [set_IsHardUnderlineFill](../baseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | Определяет, имеет ли стиль подчеркивания собственные свойства [FillFormat](../fillformat/) или наследует их от свойств [FillFormat](../fillformat/) текста. Записать [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](../baseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | Определяет, имеет ли стиль подчеркивания собственные свойства [LineFormat](../lineformat/) или наследует их от свойств [LineFormat](../lineformat/) текста. Записать [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](../baseportionformat/set_kerningminimalsize/)(**float**) override | Устанавливает минимальный размер шрифта, при котором следует включить кернинг. **std::numeric_limits<float>::quiet_NaN()** означает, что значение неопределено и должно наследоваться от Master. Записать **float**. |
| void [set_Kumimoji](../baseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) override | Определяет, должны ли числа игнорировать вертикальное расположение текста, специфичное для восточных языков. Наследование не применяется. Записать [NullableBool](../nullablebool/). |
| void [set_LanguageId](../baseportionformat/set_languageid/)([System::String](../../system/string/)) override | Устанавливает идентификатор языка проверки. Используется для проверки орфографии и грамматики. Записать [System::String](../../system/string/). |
| void [set_LatinFont](../baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Устанавливает информацию о латинском шрифте. Null означает, что шрифт неопределён и должен наследоваться от Master. Записать [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](../baseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) override | Определяет, следует ли нормализовать высоту текста. Наследование не применяется. Записать [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](../baseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) override | Определяет, не следует ли проверять текст. Наследование не применяется. Записать [NullableBool](../nullablebool/). |
| void [set_SmartTagClean](./set_smarttagclean/)(**bool**) override | Определяет, следует ли очищать смарт-тег. Наследование не применяется. Записать **bool**. |
| void [set_Spacing](../baseportionformat/set_spacing/)(**float**) override | Устанавливает приращение межсимвольного интервала. **std::numeric_limits<float>::quiet_NaN()** означает, что значение неопределено и должно наследоваться от Master. Записать **float**. |
| void [set_SpellCheck](../baseportionformat/set_spellcheck/)(**bool**) override | Устанавливает значение, указывающее, включена ли проверка правописания для части текста. Когда свойство установлено в false, проверки правописания для текстовых элементов подавляются. Когда установлено в true, проверка правописания разрешена. Значение по умолчанию — **false**. |
| void [set_StrikethroughType](../baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | Устанавливает тип зачеркивания текста. Наследование не применяется. Записать [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](../baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Устанавливает информацию о символическом шрифте. Null означает, что шрифт неопределён и должен наследоваться от Master. Записать [IFontData](../ifontdata/). |
| void [set_TextCapType](../baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | Устанавливает тип капитализации текста. Наследование не применяется. Записать [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-ый аргумент шаблона как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика разделяемых ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик разделяемых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик разделяемых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Примечания

Этот класс используется для получения и изменения свойств форматирования части текста, определённых для конкретной части. Это означает, что при получении значений наследование не применяется, поэтому в большинстве случаев вы получите значения, означающие «неопределено».

Чтобы получить эффективные значения параметров форматирования, включая унаследованные, необходимо использовать метод [PortionFormat::GetEffective](./geteffective/), который возвращает экземпляр [IPortionFormatEffectiveData](../iportionformateffectivedata/).

Следующий пример показывает, как назначить латинский шрифт части [Paragraph](../paragraph/) в PowerPoint [Presentation](../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f);

System::SharedPtr<Paragraph> paragraph = System::MakeObject<Paragraph>();
System::SharedPtr<Portion> portion = System::MakeObject<Portion>(u"Theme text format");
paragraph->get_Portions()->Add(portion);
shape->get_TextFrame()->get_Paragraphs()->Add(paragraph);
// Aspose.Slides использует эти специальные идентификаторы (аналогичные тем, что используются в PowerPoint):
// +mn-lt - Шрифт тела Latin (Minor Latin Font)
// +mj-lt - Шрифт заголовка Latin (Major Latin Font)
// +mn-ea - Шрифт тела East Asian (Minor East Asian Font)
// +mj-ea - Шрифт тела East Asian (Minor East Asian Font)
portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"+mn-lt"));
```

## См. также

* Класс [BasePortionFormat](../baseportionformat/)
* Класс [IPortionFormat](../iportionformat/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)