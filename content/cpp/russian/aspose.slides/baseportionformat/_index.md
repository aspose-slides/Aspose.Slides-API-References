---
title: BasePortionFormat
second_title: Aspose.Slides для C++ Справочник API
description: Общие свойства форматирования текстовой части.
type: docs
weight: 144
url: /ru/aspose.slides/baseportionformat/
---
## BasePortionFormat класс

Common text portion formatting properties.

```cpp
class BasePortionFormat : public Aspose::Slides::PVIObject,
                          public virtual Aspose::Slides::IBasePortionFormat
```

## Методы

| Method | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Сравнивает с указанным объектом. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() override | Возвращает идентификатор альтернативного языка. Читайте [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() override | Возвращает информацию о шрифте сложного письма. Null означает, что шрифт не определён и должен наследоваться от Master. Читайте [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() override | Возвращает информацию о восточноазиатском шрифте. Null означает, что шрифт не определён и должен наследоваться от Master. Читайте [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | Возвращает свойства текста [EffectFormat](../effectformat/). Наследование не применяется. Только для чтения [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](./get_escapement/)() override | Возвращает надстрочный или подстрочный текст. Значение от -100% (подстрочный) до 100% (надстрочный). **std::numeric_limits<float>::quiet_NaN()** означает, что значение не определено и должно наследоваться от Master. Читайте **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | Возвращает свойства текста [FillFormat](../fillformat/). Наследование не применяется. Только для чтения [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() override | Определяет, является ли шрифт жирным. Наследование не применяется. Читайте [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](./get_fontheight/)() override | Возвращает высоту шрифта части. **std::numeric_limits<float>::quiet_NaN()** означает, что высота не определена и должна наследоваться от Master. Читайте **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() override | Определяет, является ли шрифт курсивным. Наследование не применяется. Читайте [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() override | Возвращает тип подчеркивания текста. Наследование не применяется. Читайте [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() override | Возвращает цвет, используемый для выделения текста. Наследование не применяется. Только для чтения [IColorFormat](../icolorformat/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() override | Определяет, имеет ли стиль подчеркивания собственные свойства [FillFormat](../fillformat/) или наследует их от свойств [FillFormat](../fillformat/) текста. Читайте [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() override | Определяет, имеет ли стиль подчеркивания собственные свойства [LineFormat](../lineformat/) или наследует их от свойств [LineFormat](../lineformat/) текста. Читайте [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() override | Возвращает минимальный размер шрифта, при котором включается кёрнинг. **std::numeric_limits<float>::quiet_NaN()** означает, что значение не определено и должно наследоваться от Master. Читайте **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() override | Определяет, должны ли числа игнорировать специфическую для восточных языков вертикальную раскладку текста. Наследование не применяется. Читайте [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() override | Возвращает идентификатор языка проверки. Используется для проверки орфографии и грамматики. Читайте [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() override | Возвращает информацию о латинском шрифте. Null означает, что шрифт не определён и должен наследоваться от Master. Читайте [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | Возвращает свойства [LineFormat](../lineformat/) для обведения текста. Наследование не применяется. Только для чтения [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() override | Определяет, должна ли высота текста быть нормализована. Наследование не применяется. Читайте [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Возвращает объект Parent_Immediate. Только для чтения [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Возвращает родительский [IPresentationComponent](../ipresentationcomponent/). Только для чтения [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() override | Определяет, не следует ли проверять текст. Наследование не применяется. Читайте [NullableBool](../nullablebool/). |
| **float** [get_Spacing](./get_spacing/)() override | Возвращает приращение межсимвольного интервала. **std::numeric_limits<float>::quiet_NaN()** означает, что значение не определено и должно наследоваться от Master. Читайте **float**. |
| **bool** [get_SpellCheck](./get_spellcheck/)() override | Получает значение, указывающее, включена ли проверка орфографии для части текста. Когда это свойство установлено в false, проверка орфографии для текстовых элементов подавляется. Когда установлено в true, проверка орфографии разрешена. Значение по умолчанию **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() override | Возвращает тип зачеркивания текста. Наследование не применяется. Читайте [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() override | Возвращает информацию о символическом шрифте. Null означает, что шрифт не определён и должен наследоваться от Master. Читайте [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() override | Возвращает тип капитализации текста. Наследование не применяется. Читайте [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() override | Возвращает свойства линии подчеркивания [FillFormat](../fillformat/). Наследование не применяется. Только для чтения [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() override | Возвращает свойства [LineFormat](../lineformat/), используемые для обведения линии подчеркивания. Наследование не применяется. Только для чтения [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Возвращает хеш-код. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку операторa C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, только инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, только инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счетчик общих ссылок на указанное значение. |
| void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) override | Устанавливает идентификатор альтернативного языка. Запишите [System::String](../../system/string/). |
| void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Устанавливает информацию о шрифте сложного письма. Null означает, что шрифт не определён и должен наследоваться от Master. Запишите [IFontData](../ifontdata/). |
| void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Устанавливает информацию о восточноазиатском шрифте. Null означает, что шрифт не определён и должен наследоваться от Master. Запишите [IFontData](../ifontdata/). |
| void [set_Escapement](./set_escapement/)(**float**) override | Устанавливает надстрочный или подстрочный текст. Значение от -100% (подстрочный) до 100% (надстрочный). **std::numeric_limits<float>::quiet_NaN()** означает, что значение не определено и должно наследоваться от Master. Запишите **float**. |
| void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) override | Определяет, является ли шрифт жирным. Наследование не применяется. Запишите [NullableBool](../nullablebool/). |
| void [set_FontHeight](./set_fontheight/)(**float**) override | Устанавливает высоту шрифта части. **std::numeric_limits<float>::quiet_NaN()** означает, что высота не определена и должна наследоваться от Master. Запишите **float**. |
| void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) override | Определяет, является ли шрифт курсивным. Наследование не применяется. Запишите [NullableBool](../nullablebool/). |
| void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | Устанавливает тип подчеркивания текста. Наследование не применяется. Запишите [TextUnderlineType](../textunderlinetype/). |
| void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | Определяет, имеет ли стиль подчеркивания собственные свойства [FillFormat](../fillformat/) или наследует их от свойств [FillFormat](../fillformat/) текста. Запишите [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | Определяет, имеет ли стиль подчеркивания собственные свойства [LineFormat](../lineformat/) или наследует их от свойств [LineFormat](../lineformat/) текста. Запишите [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) override | Устанавливает минимальный размер шрифта, при котором включается кёрнинг. **std::numeric_limits<float>::quiet_NaN()** означает, что значение не определено и должно наследоваться от Master. Запишите **float**. |
| void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) override | Определяет, должны ли числа игнорировать специфическую для восточных языков вертикальную раскладку текста. Наследование не применяется. Запишите [NullableBool](../nullablebool/). |
| void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) override | Устанавливает идентификатор языка проверки. Используется для проверки орфографии и грамматики. Запишите [System::String](../../system/string/). |
| void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Устанавливает информацию о латинском шрифте. Null означает, что шрифт не определён и должен наследоваться от Master. Запишите [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) override | Определяет, должна ли высота текста быть нормализована. Наследование не применяется. Запишите [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) override | Определяет, не следует ли проверять текст. Наследование не применяется. Запишите [NullableBool](../nullablebool/). |
| void [set_Spacing](./set_spacing/)(**float**) override | Устанавливает приращение межсимвольного интервала. **std::numeric_limits<float>::quiet_NaN()** означает, что значение не определено и должно наследоваться от Master. Запишите **float**. |
| void [set_SpellCheck](./set_spellcheck/)(**bool**) override | Устанавливает значение, указывающее, включена ли проверка орфографии для части текста. Когда это свойство установлено в false, проверка орфографии для текстовых элементов подавляется. Когда установлено в true, проверка орфографии разрешена. Значение по умолчанию **false**. |
| void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | Устанавливает тип зачеркивания текста. Наследование не применяется. Запишите [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Устанавливает информацию о символическом шрифте. Null означает, что шрифт не определён и должен наследоваться от Master. Запишите [IFontData](../ifontdata/). |
| void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | Устанавливает тип капитализации текста. Наследование не применяется. Запишите [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку операторa C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [PVIObject](../pviobject/)
* Класс [IBasePortionFormat](../ibaseportionformat/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)