---
title: ChartPortionFormat
second_title: Aspose.Slides C++ API 參考
description: 此類別包含圖表中使用的圖表區段格式屬性。與 IPortionFormatEffectiveData 不同，此類別的所有屬性皆可寫入。
type: docs
weight: 261
url: /zh-hant/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat 類別


此類別包含圖表中使用的圖表區段格式屬性。與 [IPortionFormatEffectiveData](../../aspose.slides/iportionformateffectivedata/) 不同，此類別的所有屬性皆可寫。

```cpp
class ChartPortionFormat : public Aspose::Slides::BasePortionFormat,
                           public Aspose::Slides::Charts::IChartPortionFormat
```

## 方法

| 方法 | 說明 |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 與指定的物件比較。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../../aspose.slides/baseportionformat/get_alternativelanguageid/)() override | 返回替代語言的 Id。請閱讀 [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_ComplexScriptFont](../../aspose.slides/baseportionformat/get_complexscriptfont/)() override | 返回複合文字腳本字型資訊。Null 表示字型未定義，應從主字型繼承。請閱讀 [IFontData](../../aspose.slides/ifontdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_EastAsianFont](../../aspose.slides/baseportionformat/get_eastasianfont/)() override | 返回東亞字型資訊。Null 表示字型未定義，應從主字型繼承。請閱讀 [IFontData](../../aspose.slides/ifontdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/baseportionformat/get_effectformat/)() override | 返回文字 [EffectFormat](../../aspose.slides/effectformat/) 屬性。未套用繼承。唯讀 [IEffectFormat](../../aspose.slides/ieffectformat/)。 |
| **float** [get_Escapement](../../aspose.slides/baseportionformat/get_escapement/)() override | 返回上標或下標文字。值範圍為 -100%（下標）至 100%（上標）。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從主字型繼承。僅讀 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/baseportionformat/get_fillformat/)() override | 返回文字 [FillFormat](../../aspose.slides/fillformat/) 屬性。未套用繼承。唯讀 [IFillFormat](../../aspose.slides/ifillformat/)。 |
| [NullableBool](../../aspose.slides/nullablebool/) [get_FontBold](../../aspose.slides/baseportionformat/get_fontbold/)() override | 判斷字型是否為粗體。未套用繼承。讀取 [NullableBool](../../aspose.slides/nullablebool/)。 |
| **float** [get_FontHeight](../../aspose.slides/baseportionformat/get_fontheight/)() override | 返回區段的字型高度。**std::numeric_limits<float>::quiet_NaN()** 表示高度未定義，應從主字型繼承。僅讀 **float**。 |
| [NullableBool](../../aspose.slides/nullablebool/) [get_FontItalic](../../aspose.slides/baseportionformat/get_fontitalic/)() override | 判斷字型是否為斜體。未套用繼承。讀取 [NullableBool](../../aspose.slides/nullablebool/)。 |
| [TextUnderlineType](../../aspose.slides/textunderlinetype/) [get_FontUnderline](../../aspose.slides/baseportionformat/get_fontunderline/)() override | 返回文字底線類型。未套用繼承。讀取 [TextUnderlineType](../../aspose.slides/textunderlinetype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_HighlightColor](../../aspose.slides/baseportionformat/get_highlightcolor/)() override | 返回文字標示使用的顏色。未套用繼承。唯讀 [IColorFormat](../../aspose.slides/icolorformat/)。 |
| [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineFill](../../aspose.slides/baseportionformat/get_ishardunderlinefill/)() override | 判斷底線樣式是否擁有自己的 [FillFormat](../../aspose.slides/fillformat/) 屬性或從文字的 [FillFormat](../../aspose.slides/fillformat/) 屬性繼承。讀取 [NullableBool](../../aspose.slides/nullablebool/)。 |
| [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineLine](../../aspose.slides/baseportionformat/get_ishardunderlineline/)() override | 判斷底線樣式是否擁有自己的 [LineFormat](../../aspose.slides/lineformat/) 屬性或從文字的 [LineFormat](../../aspose.slides/lineformat/) 屬性繼承。讀取 [NullableBool](../../aspose.slides/nullablebool/)。 |
| **float** [get_KerningMinimalSize](../../aspose.slides/baseportionformat/get_kerningminimalsize/)() override | 返回應啟用字距調整的最小字型大小。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從主字型繼承。僅讀 **float**。 |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Kumimoji](../../aspose.slides/baseportionformat/get_kumimoji/)() override | 判斷數字是否應忽略文字東方語言特定的垂直排版。未套用繼承。讀取 [NullableBool](../../aspose.slides/nullablebool/)。 |
| [System::String](../../system/string/) [get_LanguageId](../../aspose.slides/baseportionformat/get_languageid/)() override | 返回校對語言的 Id。用於拼寫與文法檢查。讀取 [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_LatinFont](../../aspose.slides/baseportionformat/get_latinfont/)() override | 返回拉丁字型資訊。Null 表示字型未定義，應從主字型繼承。讀取 [IFontData](../../aspose.slides/ifontdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/baseportionformat/get_lineformat/)() override | 返回文字描邊的 [LineFormat](../../aspose.slides/lineformat/) 屬性。未套用繼承。唯讀 [ILineFormat](../../aspose.slides/ilineformat/)。 |
| [NullableBool](../../aspose.slides/nullablebool/) [get_NormaliseHeight](../../aspose.slides/baseportionformat/get_normaliseheight/)() override | 判斷文字高度是否應正規化。未套用繼承。讀取 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | 返回 Parent_Immediate 物件。唯讀 [IDOMObject](../../aspose.slides/idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | 返回父層 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)。唯讀 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)。 |
| [NullableBool](../../aspose.slides/nullablebool/) [get_ProofDisabled](../../aspose.slides/baseportionformat/get_proofdisabled/)() override | 判斷文字是否不應進行校對。未套用繼承。讀取 [NullableBool](../../aspose.slides/nullablebool/)。 |
| **float** [get_Spacing](../../aspose.slides/baseportionformat/get_spacing/)() override | 返回字元間距增量。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從主字型繼承。僅讀 **float**。 |
| **bool** [get_SpellCheck](../../aspose.slides/baseportionformat/get_spellcheck/)() override | 取得指示文字區段是否啟用拼寫檢查的值。當此屬性設為 false 時，文字元素的拼寫檢查會被抑制。設為 true 時，允許拼寫檢查。預設值為 **false**。 |
| [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/) [get_StrikethroughType](../../aspose.slides/baseportionformat/get_strikethroughtype/)() override | 返回文字的刪除線類型。未套用繼承。讀取 [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_SymbolFont](../../aspose.slides/baseportionformat/get_symbolfont/)() override | 返回符號字型資訊。Null 表示字型未定義，應從主字型繼承。讀取 [IFontData](../../aspose.slides/ifontdata/)。 |
| [Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/) [get_TextCapType](../../aspose.slides/baseportionformat/get_textcaptype/)() override | 返回文字大小寫類型。未套用繼承。讀取 [Slides::TextCapType](../../aspose.slides/textcaptype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_UnderlineFillFormat](../../aspose.slides/baseportionformat/get_underlinefillformat/)() override | 返回底線線條 [FillFormat](../../aspose.slides/fillformat/) 屬性。未套用繼承。唯讀 [IFillFormat](../../aspose.slides/ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_UnderlineLineFormat](../../aspose.slides/baseportionformat/get_underlinelineformat/)() override | 返回用於描邊底線線條的 [LineFormat](../../aspose.slides/lineformat/) 屬性。未套用繼承。唯讀 [ILineFormat](../../aspose.slides/ilineformat/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數器資料結構。 |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | 返回雜湊碼。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。允許自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構函式。實際上不拷貝任何資料，只是初始化新物件並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不拷貝任何資料，只是初始化新物件並允許子類別的拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化版本，適用於字串與 nullptr 情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化版本，適用於字串情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定值。 |
| void [set_AlternativeLanguageId](../../aspose.slides/baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | 設定替代語言的 Id。寫入 [System::String](../../system/string/)。 |
| void [set_ComplexScriptFont](../../aspose.slides/baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | 設定複合文字腳本字型資訊。Null 表示字型未定義，應從主字型繼承。寫入 [IFontData](../../aspose.slides/ifontdata/)。 |
| void [set_EastAsianFont](../../aspose.slides/baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | 設定東亞字型資訊。Null 表示字型未定義，應從主字型繼承。寫入 [IFontData](../../aspose.slides/ifontdata/)。 |
| void [set_Escapement](../../aspose.slides/baseportionformat/set_escapement/)(**float**) override | 設定上標或下標文字。值範圍為 -100%（下標）至 100%（上標）。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從主字型繼承。寫入 **float**。 |
| void [set_FontBold](../../aspose.slides/baseportionformat/set_fontbold/)([NullableBool](../../aspose.slides/nullablebool/)) override | 判斷字型是否為粗體。未套用繼承。寫入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| void [set_FontHeight](../../aspose.slides/baseportionformat/set_fontheight/)(**float**) override | 設定區段的字型高度。**std::numeric_limits<float>::quiet_NaN()** 表示高度未定義，應從主字型繼承。寫入 **float**。 |
| void [set_FontItalic](../../aspose.slides/baseportionformat/set_fontitalic/)([NullableBool](../../aspose.slides/nullablebool/)) override | 判斷字型是否為斜體。未套用繼承。寫入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| void [set_FontUnderline](../../aspose.slides/baseportionformat/set_fontunderline/)([TextUnderlineType](../../aspose.slides/textunderlinetype/)) override | 設定文字底線類型。未套用繼承。寫入 [TextUnderlineType](../../aspose.slides/textunderlinetype/)。 |
| void [set_IsHardUnderlineFill](../../aspose.slides/baseportionformat/set_ishardunderlinefill/)([NullableBool](../../aspose.slides/nullablebool/)) override | 判斷底線樣式是否擁有自己的 [FillFormat](../../aspose.slides/fillformat/) 屬性或從文字的 [FillFormat](../../aspose.slides/fillformat/) 屬性繼承。寫入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| void [set_IsHardUnderlineLine](../../aspose.slides/baseportionformat/set_ishardunderlineline/)([NullableBool](../../aspose.slides/nullablebool/)) override | 判斷底線樣式是否擁有自己的 [LineFormat](../../aspose.slides/lineformat/) 屬性或從文字的 [LineFormat](../../aspose.slides/lineformat/) 屬性繼承。寫入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| void [set_KerningMinimalSize](../../aspose.slides/baseportionformat/set_kerningminimalsize/)(**float**) override | 設定最小字型大小，對於此大小應啟用字距調整。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從主字型繼承。寫入 **float**。 |
| void [set_Kumimoji](../../aspose.slides/baseportionformat/set_kumimoji/)([NullableBool](../../aspose.slides/nullablebool/)) override | 判斷數字是否應忽略文字東方語言特定的垂直排版。未套用繼承。寫入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| void [set_LanguageId](../../aspose.slides/baseportionformat/set_languageid/)([System::String](../../system/string/)) override | 設定校對語言的 Id。用於拼寫與文法檢查。寫入 [System::String](../../system/string/)。 |
| void [set_LatinFont](../../aspose.slides/baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | 設定拉丁字型資訊。Null 表示字型未定義，應從主字型繼承。寫入 [IFontData](../../aspose.slides/ifontdata/)。 |
| void [set_NormaliseHeight](../../aspose.slides/baseportionformat/set_normaliseheight/)([NullableBool](../../aspose.slides/nullablebool/)) override | 判斷文字高度是否應正規化。未套用繼承。寫入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| void [set_ProofDisabled](../../aspose.slides/baseportionformat/set_proofdisabled/)([NullableBool](../../aspose.slides/nullablebool/)) override | 判斷文字是否不應校對。未套用繼承。寫入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| void [set_Spacing](../../aspose.slides/baseportionformat/set_spacing/)(**float**) override | 設定字元間距增量。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從主字型繼承。寫入 **float**。 |
| void [set_SpellCheck](../../aspose.slides/baseportionformat/set_spellcheck/)(**bool**) override | 設定指示文字區段是否啟用拼寫檢查的值。當此屬性設為 false 時，文字元素的拼寫檢查會被抑制。設為 true 時，允許拼寫檢查。預設值為 **false**。 |
| void [set_StrikethroughType](../../aspose.slides/baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../../aspose.slides/textstrikethroughtype/)) override | 設定文字的刪除線類型。未套用繼承。寫入 [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/)。 |
| void [set_SymbolFont](../../aspose.slides/baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) override | 設定符號字型資訊。Null 表示字型未定義，應從主字型繼承。寫入 [IFontData](../../aspose.slides/ifontdata/)。 |
| void [set_TextCapType](../../aspose.slides/baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/)) override | 設定文字大小寫類型。未套用繼承。寫入 [Slides::TextCapType](../../aspose.slides/textcaptype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得目前共享參考計數的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。允許將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |
## 備註


此類別用於返回與操作針對特定區段定義的文字區段格式屬性。這表示在取得值時不會套用繼承，因此在大多數情況下會取得意為「未定義」的值。

若要取得包括繼承在內的有效格式參數值，需使用 [PortionFormat::GetEffective](../../aspose.slides/portionformat/geteffective/) 方法，該方法會返回一個 [IPortionFormatEffectiveData](../../aspose.slides/iportionformateffectivedata/) 實例。
## 另請參閱

* 類別 [BasePortionFormat](../../aspose.slides/baseportionformat/)
* 類別 [IChartPortionFormat](../ichartportionformat/)
* 命名空間 [Aspose::Slides::Charts](../)
* 函式庫 [Aspose.Slides](../../)