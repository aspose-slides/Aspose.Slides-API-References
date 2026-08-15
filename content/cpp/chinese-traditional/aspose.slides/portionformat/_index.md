---
title: PortionFormat
second_title: Aspose.Slides for C++ API 參考文件
description: 此類別包含文字區段格式屬性。不同於 IPortionFormatEffectiveData，此類別的所有屬性皆可寫入。
type: docs
weight: 4811
url: /zh-hant/aspose.slides/portionformat/
---
## PortionFormat 類別


此類別包含文字區段格式屬性。不同於 [IPortionFormatEffectiveData](../iportionformateffectivedata/)，此類別的所有屬性皆可寫入。

```cpp
class PortionFormat : public Aspose::Slides::BasePortionFormat,
                      public Aspose::Slides::IPortionFormat
```

## 方法

| Method | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 與指定物件比較。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../baseportionformat/get_alternativelanguageid/)() override | 傳回替代語言的 Id。請閱讀 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() override | 傳回書籤識別碼。請閱讀 [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../baseportionformat/get_complexscriptfont/)() override | 傳回複雜腳本字型資訊。Null 表示字型未定義，應從主體繼承。請閱讀 [IFontData](../ifontdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../baseportionformat/get_eastasianfont/)() override | 傳回東亞字型資訊。Null 表示字型未定義，應從主體繼承。請閱讀 [IFontData](../ifontdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../baseportionformat/get_effectformat/)() override | 傳回文字 [EffectFormat](../effectformat/) 屬性。未套用繼承。唯讀 [IEffectFormat](../ieffectformat/)。 |
| **float** [get_Escapement](../baseportionformat/get_escapement/)() override | 傳回上標或下標文字。值介於 -100%（下標）至 100%（上標）。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從主體繼承。讀取 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../baseportionformat/get_fillformat/)() override | 傳回文字 [FillFormat](../fillformat/) 屬性。未套用繼承。唯讀 [IFillFormat](../ifillformat/)。 |
| [NullableBool](../nullablebool/) [get_FontBold](../baseportionformat/get_fontbold/)() override | 判斷字型是否為粗體。未套用繼承。讀取 [NullableBool](../nullablebool/)。 |
| **float** [get_FontHeight](../baseportionformat/get_fontheight/)() override | 傳回區段的字型高度。**std::numeric_limits<float>::quiet_NaN()** 表示高度未定義，應從主體繼承。讀取 **float**。 |
| [NullableBool](../nullablebool/) [get_FontItalic](../baseportionformat/get_fontitalic/)() override | 判斷字型是否為斜體。未套用繼承。讀取 [NullableBool](../nullablebool/)。 |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../baseportionformat/get_fontunderline/)() override | 傳回文字底線類型。未套用繼承。讀取 [TextUnderlineType](../textunderlinetype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../baseportionformat/get_highlightcolor/)() override | 傳回用於突出顯示文字的顏色。未套用繼承。唯讀 [IColorFormat](../icolorformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | 傳回滑鼠點擊時的超連結。請閱讀 [IHyperlink](../ihyperlink/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | 超連結管理器。唯讀 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | 傳回滑鼠懸停時的超連結。請閱讀 [IHyperlink](../ihyperlink/)。 |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../baseportionformat/get_ishardunderlinefill/)() override | 判斷底線樣式是否具有自己的 [FillFormat](../fillformat/) 屬性，或從文字的 [FillFormat](../fillformat/) 屬性繼承。讀取 [NullableBool](../nullablebool/)。 |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../baseportionformat/get_ishardunderlineline/)() override | 判斷底線樣式是否具有自己的 [LineFormat](../lineformat/) 屬性，或從文字的 [LineFormat](../lineformat/) 屬性繼承。讀取 [NullableBool](../nullablebool/)。 |
| **float** [get_KerningMinimalSize](../baseportionformat/get_kerningminimalsize/)() override | 傳回應啟用字距微調的最小字型大小。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從主體繼承。讀取 **float**。 |
| [NullableBool](../nullablebool/) [get_Kumimoji](../baseportionformat/get_kumimoji/)() override | 判斷數字是否應忽略文字東方語言特定的垂直排版。未套用繼承。讀取 [NullableBool](../nullablebool/)。 |
| [System::String](../../system/string/) [get_LanguageId](../baseportionformat/get_languageid/)() override | 傳回校對語言的 Id。用於拼寫與文法檢查。請閱讀 [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../baseportionformat/get_latinfont/)() override | 傳回 Latin 字型資訊。Null 表示字型未定義，應從主體繼承。請閱讀 [IFontData](../ifontdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../baseportionformat/get_lineformat/)() override | 傳回文字輪廓的 [LineFormat](../lineformat/) 屬性。未套用繼承。唯讀 [ILineFormat](../ilineformat/)。 |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](../baseportionformat/get_normaliseheight/)() override | 判斷文字的高度是否應正規化。未套用繼承。讀取 [NullableBool](../nullablebool/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | 傳回 Parent_Immediate 物件。唯讀 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 傳回父項 [IPresentationComponent](../ipresentationcomponent/)。唯讀 [IPresentationComponent](../ipresentationcomponent/)。 |
| [NullableBool](../nullablebool/) [get_ProofDisabled](../baseportionformat/get_proofdisabled/)() override | 判斷文字是否不應校對。未套用繼承。讀取 [NullableBool](../nullablebool/)。 |
| **bool** [get_SmartTagClean](./get_smarttagclean/)() override | 判斷智慧標籤是否應清除。未套用繼承。讀取 **bool**。 |
| **float** [get_Spacing](../baseportionformat/get_spacing/)() override | 傳回字元間距遞增值。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從主體繼承。讀取 **float**。 |
| **bool** [get_SpellCheck](../baseportionformat/get_spellcheck/)() override | 取得指示文字區段是否啟用拼寫檢查的值。當此屬性設定為 false 時，文字元素的拼寫檢查將被抑制。設定為 true 時，允許拼寫檢查。預設值為 **false**。 |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../baseportionformat/get_strikethroughtype/)() override | 傳回文字的刪除線類型。未套用繼承。讀取 [TextStrikethroughType](../textstrikethroughtype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../baseportionformat/get_symbolfont/)() override | 傳回象徵字型資訊。Null 表示字型未定義，應從主體繼承。請閱讀 [IFontData](../ifontdata/)。 |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../baseportionformat/get_textcaptype/)() override | 傳回文字大小寫類型。未套用繼承。讀取 [Slides::TextCapType](../textcaptype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../baseportionformat/get_underlinefillformat/)() override | 傳回底線線條 [FillFormat](../fillformat/) 屬性。未套用繼承。唯讀 [IFillFormat](../ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../baseportionformat/get_underlinelineformat/)() override | 傳回用於輪廓底線線條的 [LineFormat](../lineformat/) 屬性。未套用繼承。唯讀 [ILineFormat](../ilineformat/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參照計數資料結構。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() override | 取得套用繼承的有效區段格式資料。 |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | 傳回雜湊碼。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構子。實際上不會拷貝任何東西，只是初始化新物件並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會拷貝任何東西，只是初始化新物件並允許子類別的拷貝建構。 |
|  [PortionFormat](./portionformat/)() | 初始化 [PortionFormat](./) 類別的新執行個體。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參照比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參照比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參照比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，適用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，適用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參照計數。 |
| void [set_AlternativeLanguageId](../baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | 設定替代語言的 Id。寫入 [System::String](../../system/string/)。 |
| void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) override | 設定書籤識別碼。寫入 [System::String](../../system/string/)。 |
| void [set_ComplexScriptFont](../baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 設定複雜腳本字型資訊。Null 表示字型未定義，應從主體繼承。寫入 [IFontData](../ifontdata/)。 |
| void [set_EastAsianFont](../baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 設定東亞字型資訊。Null 表示字型未定義，應從主體繼承。寫入 [IFontData](../ifontdata/)。 |
| void [set_Escapement](../baseportionformat/set_escapement/)(**float**) override | 設定上標或下標文字。值介於 -100%（下標）至 100%（上標）。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從主體繼承。寫入 **float**。 |
| void [set_FontBold](../baseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) override | 判斷字型是否為粗體。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| void [set_FontHeight](../baseportionformat/set_fontheight/)(**float**) override | 設定區段的字型高度。**std::numeric_limits<float>::quiet_NaN()** 表示高度未定義，應從主體繼承。寫入 **float**。 |
| void [set_FontItalic](../baseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) override | 判斷字型是否為斜體。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| void [set_FontUnderline](../baseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | 設定文字底線類型。未套用繼承。寫入 [TextUnderlineType](../textunderlinetype/)。 |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 設定滑鼠點擊時的超連結。寫入 [IHyperlink](../ihyperlink/)。 |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | 設定滑鼠懸停時的超連結。寫入 [IHyperlink](../ihyperlink/)。 |
| void [set_IsHardUnderlineFill](../baseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | 判斷底線樣式是否具有自己的 [FillFormat](../fillformat/) 屬性，或從文字的 [FillFormat](../fillformat/) 屬性繼承。寫入 [NullableBool](../nullablebool/)。 |
| void [set_IsHardUnderlineLine](../baseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | 判斷底線樣式是否具有自己的 [LineFormat](../lineformat/) 屬性，或從文字的 [LineFormat](../lineformat/) 屬性繼承。寫入 [NullableBool](../nullablebool/)。 |
| void [set_KerningMinimalSize](../baseportionformat/set_kerningminimalsize/)(**float**) override | 設定應啟用字距微調的最小字型大小。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從主體繼承。寫入 **float**。 |
| void [set_Kumimoji](../baseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) override | 判斷數字是否應忽略文字東方語言特定的垂直排版。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| void [set_LanguageId](../baseportionformat/set_languageid/)([System::String](../../system/string/)) override | 設定校對語言的 Id。用於拼寫與文法檢查。寫入 [System::String](../../system/string/)。 |
| void [set_LatinFont](../baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 設定 Latin 字型資訊。Null 表示字型未定義，應從主體繼承。寫入 [IFontData](../ifontdata/)。 |
| void [set_NormaliseHeight](../baseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) override | 判斷文字的高度是否應正規化。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| void [set_ProofDisabled](../baseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) override | 判斷文字是否不應校對。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| void [set_SmartTagClean](./set_smarttagclean/)(**bool**) override | 判斷智慧標籤是否應清除。未套用繼承。寫入 **bool**。 |
| void [set_Spacing](../baseportionformat/set_spacing/)(**float**) override | 設定字元間距遞增值。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從主體繼承。寫入 **float**。 |
| void [set_SpellCheck](../baseportionformat/set_spellcheck/)(**bool**) override | 設定指示文字區段是否啟用拼寫檢查的值。當此屬性設定為 false 時，文字元素的拼寫檢查將被抑制。設定為 true 時，允許拼寫檢查。預設值為 **false**。 |
| void [set_StrikethroughType](../baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | 設定文字的刪除線類型。未套用繼承。寫入 [TextStrikethroughType](../textstrikethroughtype/)。 |
| void [set_SymbolFont](../baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 設定象徵字型資訊。Null 表示字型未定義，應從主體繼承。寫入 [IFontData](../ifontdata/)。 |
| void [set_TextCapType](../baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | 設定文字大小寫類型。未套用繼承。寫入 [Slides::TextCapType](../textcaptype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中切換指標為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參照計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |
## 備註


此類別用於返回與操作針對特定區段所定義的文字區段格式屬性。這表示在取得值時不會套用繼承，因此在大多數情況下會得到表示「未定義」的值。

若要取得包括繼承在內的有效格式參數值，必須使用 [PortionFormat::GetEffective](./geteffective/) 方法，該方法傳回一個 [IPortionFormatEffectiveData](../iportionformateffectivedata/) 實例。

以下範例示範如何將 Latin 字型指定給 [Paragraph](../paragraph/) 的 PowerPoint [Presentation](../presentation/) 區段。

```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f);

System::SharedPtr<Paragraph> paragraph = System::MakeObject<Paragraph>();
System::SharedPtr<Portion> portion = System::MakeObject<Portion>(u"Theme text format");
paragraph->get_Portions()->Add(portion);
shape->get_TextFrame()->get_Paragraphs()->Add(paragraph);
// Aspose.Slides 使用這些特殊識別碼（類似於 PowerPoint 中使用的識別碼）:
// +mn-lt - 主體字型 Latin（次要 Latin 字型）
// +mj-lt - 標題字型 Latin（主要 Latin 字型）
// +mn-ea - 主體字型 East Asian（次要 East Asian 字型）
// +mj-ea - 主體字型 East Asian（次要 East Asian 字型）
portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"+mn-lt"));
```

## 另見

* 類別 [BasePortionFormat](../baseportionformat/)
* 類別 [IPortionFormat](../iportionformat/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)