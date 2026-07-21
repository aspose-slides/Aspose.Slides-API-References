---
title: IPortionFormat
second_title: Aspose.Slides для C++ справочник API
description: Этот класс содержит свойства форматирования текстовых частей. В отличие от IPortionFormatEffectiveData, все свойства этого класса доступны для записи.
type: docs
weight: 3329
url: /ru/aspose.slides/iportionformat/
---
## IPortionFormat класс

Этот класс содержит свойства форматирования текстовых частей. В отличие от [IPortionFormatEffectiveData](../iportionformateffectivedata/), все свойства этого класса доступны для записи.

```cpp
class IPortionFormat : public virtual Aspose::Slides::IBasePortionFormat,
                       public Aspose::Slides::IHyperlinkContainer
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../ibaseportionformat/get_alternativelanguageid/)() | Возвращает идентификатор альтернативного языка. Читать [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() | Возвращает идентификатор закладки. Читать [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../ibaseportionformat/get_complexscriptfont/)() | Возвращает информацию о шрифте сложных сценариев. Null означает, что шрифт не определён и должен наследоваться от Master. Читать [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../ibaseportionformat/get_eastasianfont/)() | Возвращает информацию о восточноазиатском шрифте. Null означает, что шрифт не определён и должен наследоваться от Master. Читать [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ibaseportionformat/get_effectformat/)() | Возвращает свойства текста [EffectFormat](../effectformat/). Наследование не применяется. Только для чтения [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](../ibaseportionformat/get_escapement/)() | Возвращает надстрочный или нижстрочный текст. Значение от -100% (нижстрочный) до 100% (надстрочный). **std::numeric_limits<float>::quiet_NaN()** означает, что значение не определено и должно наследоваться от Master. Читать **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ibaseportionformat/get_fillformat/)() | Возвращает свойства текста [FillFormat](../fillformat/). Наследование не применяется. Только для чтения [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](../ibaseportionformat/get_fontbold/)() | Определяет, является ли шрифт полужирным. Наследование не применяется. Читать [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](../ibaseportionformat/get_fontheight/)() | Возвращает высоту шрифта части. **std::numeric_limits<float>::quiet_NaN()** означает, что высота не определена и должна наследоваться от Master. Читать **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](../ibaseportionformat/get_fontitalic/)() | Определяет, является ли шрифт курсивным. Наследование не применяется. Читать [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../ibaseportionformat/get_fontunderline/)() | Возвращает тип подчёркивания текста. Наследование не применяется. Читать [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../ibaseportionformat/get_highlightcolor/)() | Возвращает цвет, используемый для выделения текста. Наследование не применяется. Только для чтения [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Возвращает гиперссылку, определённую для клика мышью. Читать [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Менеджер гиперссылок Только для чтения [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Возвращает гиперссылку, определённую для наведения мышью. Читать [IHyperlink](../ihyperlink/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../ibaseportionformat/get_ishardunderlinefill/)() | Определяет, имеет ли стиль подчёркивания собственные свойства [FillFormat](../fillformat/) или наследует их из свойств [FillFormat](../fillformat/) текста. Читать [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../ibaseportionformat/get_ishardunderlineline/)() | Определяет, имеет ли стиль подчёркивания собственные свойства [LineFormat](../lineformat/) или наследует их из свойств [LineFormat](../lineformat/) текста. Читать [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](../ibaseportionformat/get_kerningminimalsize/)() | Возвращает минимальный размер шрифта, при котором должно включаться кернинг. **std::numeric_limits<float>::quiet_NaN()** означает, что значение не определено и должно наследоваться от Master. Читать **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](../ibaseportionformat/get_kumimoji/)() | Определяет, должны ли числа игнорировать специфическую для восточных языков вертикальную компоновку текста. Наследование не применяется. Читать [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](../ibaseportionformat/get_languageid/)() | Возвращает идентификатор проверочного языка. Используется для проверки орфографии и грамматики. Читать [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../ibaseportionformat/get_latinfont/)() | Возвращает информацию о латинском шрифте. Null означает, что шрифт не определён и должен наследоваться от Master. Читать [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ibaseportionformat/get_lineformat/)() | Возвращает свойства [LineFormat](../lineformat/) для обводки текста. Наследование не применяется. Точно для чтения [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](../ibaseportionformat/get_normaliseheight/)() | Определяет, должна ли высота текста нормализоваться. Наследование не применяется. Читать [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](../ibaseportionformat/get_proofdisabled/)() | Определяет, не должен ли текст проверяться. Наследование не применяется. Читать [NullableBool](../nullablebool/). |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | Определяет, должен ли смарт-тег быть очищен. Наследование не применяется. Читать **bool**. |
| virtual **float** [get_Spacing](../ibaseportionformat/get_spacing/)() | Возвращает увеличение межсимвольного интервала. **std::numeric_limits<float>::quiet_NaN()** означает, что значение не определено и должно наследоваться от Master. Читать **float**. |
| virtual **bool** [get_SpellCheck](../ibaseportionformat/get_spellcheck/)() | Возвращает значение, указывающее, включена ли проверка орфографии для части текста. Когда это свойство установлено в false, проверки орфографии для текстовых элементов подавляются. Когда установлено в true, проверка орфографии разрешена. Значение по умолчанию **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../ibaseportionformat/get_strikethroughtype/)() | Возвращает тип зачеркивания текста. Наследование не применяется. Читать [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../ibaseportionformat/get_symbolfont/)() | Возвращает информацию о символическом шрифте. Null означает, что шрифт не определён и должен наследоваться от Master. Читать [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../ibaseportionformat/get_textcaptype/)() | Возвращает тип капитализации текста. Наследование не применяется. Читать [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../ibaseportionformat/get_underlinefillformat/)() | Возвращает свойства линии подчёркивания [FillFormat](../fillformat/). Наследование не применяется. Точно для чтения [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../ibaseportionformat/get_underlinelineformat/)() | Возвращает свойства [LineFormat](../lineformat/), используемые для обводки линии подчёркивания. Наследование не применяется. Точно для чтения [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() | Получает эффективные данные форматирования части с учётом наследования. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| virtual void [set_AlternativeLanguageId](../ibaseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) | Устанавливает идентификатор альтернативного языка. Записать [System::String](../../system/string/). |
| virtual void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) | Устанавливает идентификатор закладки. Записать [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](../ibaseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Устанавливает информацию о шрифте сложных сценариев. Null означает, что шрифт не определён и должен наследоваться от Master. Записать [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](../ibaseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Устанавливает информацию о восточноазиатском шрифте. Null означает, что шрифт не определён и должен наследоваться от Master. Записать [IFontData](../ifontdata/). |
| virtual void [set_Escapement](../ibaseportionformat/set_escapement/)(**float**) | Устанавливает надстрочный или нижстрочный текст. Значение от -100% (нижстрочный) до 100% (надстрочный). **std::numeric_limits<float>::quiet_NaN()** означает, что значение не определено и должно наследоваться от Master. Записать **float**. |
| virtual void [set_FontBold](../ibaseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) | Определяет, является ли шрифт полужирным. Наследование не применяется. Записать [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](../ibaseportionformat/set_fontheight/)(**float**) | Устанавливает высоту шрифта части. **std::numeric_limits<float>::quiet_NaN()** означает, что высота не определена и должна наследоваться от Master. Записать **float**. |
| virtual void [set_FontItalic](../ibaseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) | Определяет, является ли шрифт курсивным. Наследование не применяется. Записать [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](../ibaseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | Устанавливает тип подчёркивания текста. Наследование не применяется. Записать [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Устанавливает гиперссылку, определённую для клика мышью. Записать [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Устанавливает гиперссылку, определённую для наведения мышью. Записать [IHyperlink](../ihyperlink/). |
| virtual void [set_IsHardUnderlineFill](../ibaseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | Определяет, имеет ли стиль подчёркивания собственные свойства [FillFormat](../fillformat/) или наследует их из свойств [FillFormat](../fillformat/) текста. Записать [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](../ibaseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) | Определяет, имеет ли стиль подчёркивания собственные свойства [LineFormat](../lineformat/) или наследует их из свойств [LineFormat](../lineformat/) текста. Записать [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](../ibaseportionformat/set_kerningminimalsize/)(**float**) | Устанавливает минимальный размер шрифта, при котором должен включаться кернинг. **std::numeric_limits<float>::quiet_NaN()** означает, что значение не определено и должно наследоваться от Master. Записать **float**. |
| virtual void [set_Kumimoji](../ibaseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) | Определяет, должны ли числа игнорировать специфическую для восточных языков вертикальную компоновку текста. Наследование не применяется. Записать [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](../ibaseportionformat/set_languageid/)([System::String](../../system/string/)) | Устанавливает идентификатор проверочного языка. Используется для проверки орфографии и грамматики. Записать [System::String](../../system/string/). |
| virtual void [set_LatinFont](../ibaseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Устанавливает информацию о латинском шрифте. Null означает, что шрифт не определён и должен наследоваться от Master. Записать [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](../ibaseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) | Определяет, должна ли высота текста нормализоваться. Наследование не применяется. Записать [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](../ibaseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) | Определяет, не должен ли текст проверяться. Наследование не применяется. Записать [NullableBool](../nullablebool/). |
| virtual void [set_SmartTagClean](./set_smarttagclean/)(**bool**) | Определяет, должен ли смарт-тег быть очищен. Наследование не применяется. Записать **bool**. |
| virtual void [set_Spacing](../ibaseportionformat/set_spacing/)(**float**) | Устанавливает увеличение межсимвольного интервала. **std::numeric_limits<float>::quiet_NaN()** означает, что значение не определено и должно наследоваться от Master. Записать **float**. |
| virtual void [set_SpellCheck](../ibaseportionformat/set_spellcheck/)(**bool**) | Устанавливает значение, указывающее, включена ли проверка орфографии для части текста. Когда это свойство установлено в false, проверки орфографии для текстовых элементов подавляются. Когда установлено в true, проверка орфографии разрешена. Значение по умолчанию **false**. |
| virtual void [set_StrikethroughType](../ibaseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | Устанавливает тип зачеркивания текста. Наследование не применяется. Записать [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](../ibaseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Устанавливает информацию о символическом шрифте. Null означает, что шрифт не определён и должен наследоваться от Master. Записать [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](../ibaseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | Устанавливает тип капитализации текста. Наследование не применяется. Записать [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Примечания

Этот класс используется для получения и изменения свойств форматирования текстовой части, определённых для конкретной части. Это означает, что при получении значений наследование не применяется, поэтому в большинстве случаев вы получите значения, означающие «неопределено».

Чтобы получить эффективные значения параметров форматирования, включая унаследованные, необходимо использовать метод [IPortionFormat::GetEffective](./geteffective/), который возвращает экземпляр [IPortionFormatEffectiveData](../iportionformateffectivedata/).

## См. также

* Класс [IBasePortionFormat](../ibaseportionformat/)
* Класс [IHyperlinkContainer](../ihyperlinkcontainer/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)