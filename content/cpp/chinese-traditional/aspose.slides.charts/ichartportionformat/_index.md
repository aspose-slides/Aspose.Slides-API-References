---
title: IChartPortionFormat
second_title: Aspose.Slides for C++ API 參考
description: 表示圖表中使用的圖表區段格式屬性。
type: docs
weight: 807
url: /zh-hant/aspose.slides.charts/ichartportionformat/
---
## IChartPortionFormat 類別


Represents the chart portion formatting properties used in charts.

```cpp
class IChartPortionFormat : public virtual Aspose::Slides::IBasePortionFormat
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語義比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../../aspose.slides/ibaseportionformat/get_alternativelanguageid/)() | 傳回替代語言的 Id。閱讀 [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_ComplexScriptFont](../../aspose.slides/ibaseportionformat/get_complexscriptfont/)() | 傳回複雜文字腳本字型資訊。Null 表示字型未定義，應從母版繼承。閱讀 [IFontData](../../aspose.slides/ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_EastAsianFont](../../aspose.slides/ibaseportionformat/get_eastasianfont/)() | 傳回東亞字型資訊。Null 表示字型未定義，應從母版繼承。閱讀 [IFontData](../../aspose.slides/ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ibaseportionformat/get_effectformat/)() | 傳回文字 [EffectFormat](../../aspose.slides/effectformat/) 屬性。未套用繼承。唯讀 [IEffectFormat](../../aspose.slides/ieffectformat/)。 |
| virtual **float** [get_Escapement](../../aspose.slides/ibaseportionformat/get_escapement/)() | 傳回上標或下標文字。值介於 -100%（下標）至 100%（上標）。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從母版繼承。閱讀 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ibaseportionformat/get_fillformat/)() | 傳回文字 [FillFormat](../../aspose.slides/fillformat/) 屬性。未套用繼承。唯讀 [IFillFormat](../../aspose.slides/ifillformat/)。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_FontBold](../../aspose.slides/ibaseportionformat/get_fontbold/)() | 判斷字型是否為粗體。未套用繼承。閱讀 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual **float** [get_FontHeight](../../aspose.slides/ibaseportionformat/get_fontheight/)() | 傳回部份的字型高度。**std::numeric_limits<float>::quiet_NaN()** 表示高度未定義，應從母版繼承。閱讀 **float**。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_FontItalic](../../aspose.slides/ibaseportionformat/get_fontitalic/)() | 判斷字型是否為斜體。未套用繼承。閱讀 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual [TextUnderlineType](../../aspose.slides/textunderlinetype/) [get_FontUnderline](../../aspose.slides/ibaseportionformat/get_fontunderline/)() | 傳回文字底線類型。未套用繼承。閱讀 [TextUnderlineType](../../aspose.slides/textunderlinetype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_HighlightColor](../../aspose.slides/ibaseportionformat/get_highlightcolor/)() | 傳回文字標示的顏色。未套用繼承。唯讀 [IColorFormat](../../aspose.slides/icolorformat/)。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/get_ishardunderlinefill/)() | 判斷底線樣式是否具有自己的 [FillFormat](../../aspose.slides/fillformat/) 屬性，或從文字的 [FillFormat](../../aspose.slides/fillformat/) 屬性繼承。閱讀 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/get_ishardunderlineline/)() | 判斷底線樣式是否具有自己的 [LineFormat](../../aspose.slides/lineformat/) 屬性，或從文字的 [LineFormat](../../aspose.slides/lineformat/) 屬性繼承。閱讀 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual **float** [get_KerningMinimalSize](../../aspose.slides/ibaseportionformat/get_kerningminimalsize/)() | 傳回最小字型大小，對於此大小應啟用字距微調。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從母版繼承。閱讀 **float**。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_Kumimoji](../../aspose.slides/ibaseportionformat/get_kumimoji/)() | 判斷數字是否應忽略文字東方語言特定的垂直排版。未套用繼承。閱讀 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual [System::String](../../system/string/) [get_LanguageId](../../aspose.slides/ibaseportionformat/get_languageid/)() | 傳回校對語言的 Id。用於檢查拼寫與文法。閱讀 [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_LatinFont](../../aspose.slides/ibaseportionformat/get_latinfont/)() | 傳回拉丁字型資訊。Null 表示字型未定義，應從母版繼承。閱讀 [IFontData](../../aspose.slides/ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ibaseportionformat/get_lineformat/)() | 傳回文字描邊的 [LineFormat](../../aspose.slides/lineformat/) 屬性。未套用繼承。唯讀 [ILineFormat](../../aspose.slides/ilineformat/)。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_NormaliseHeight](../../aspose.slides/ibaseportionformat/get_normaliseheight/)() | 判斷文字高度是否應正規化。未套用繼承。閱讀 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_ProofDisabled](../../aspose.slides/ibaseportionformat/get_proofdisabled/)() | 判斷文字是否不應校對。未套用繼承。閱讀 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual **float** [get_Spacing](../../aspose.slides/ibaseportionformat/get_spacing/)() | 傳回字元間距增量。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從母版繼承。閱讀 **float**。 |
| virtual **bool** [get_SpellCheck](../../aspose.slides/ibaseportionformat/get_spellcheck/)() | 取得指示文字部份是否已啟用拼寫檢查的值。當此屬性設為 false 時，會抑制文字元素的拼寫檢查。設為 true 時，允許拼寫檢查。預設值為 **false**。 |
| virtual [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/) [get_StrikethroughType](../../aspose.slides/ibaseportionformat/get_strikethroughtype/)() | 傳回文字的刪除線類型。未套用繼承。閱讀 [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\> [get_SymbolFont](../../aspose.slides/ibaseportionformat/get_symbolfont/)() | 傳回符號字型資訊。Null 表示字型未定義，應從母版繼承。閱讀 [IFontData](../../aspose.slides/ifontdata/)。 |
| virtual [Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/) [get_TextCapType](../../aspose.slides/ibaseportionformat/get_textcaptype/)() | 傳回文字大小寫類型。未套用繼承。閱讀 [Slides::TextCapType](../../aspose.slides/textcaptype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_UnderlineFillFormat](../../aspose.slides/ibaseportionformat/get_underlinefillformat/)() | 傳回底線線段 [FillFormat](../../aspose.slides/fillformat/) 屬性。未套用繼承。唯讀 [IFillFormat](../../aspose.slides/ifillformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_UnderlineLineFormat](../../aspose.slides/ibaseportionformat/get_underlinelineformat/)() | 傳回用於描邊底線線段的 [LineFormat](../../aspose.slides/lineformat/) 屬性。未套用繼承。唯讀 [ILineFormat](../../aspose.slides/ilineformat/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 針對字串與 nullptr 情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 針對字串情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [set_AlternativeLanguageId](../../aspose.slides/ibaseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) | 設定替代語言的 Id。寫入 [System::String](../../system/string/)。 |
| virtual void [set_ComplexScriptFont](../../aspose.slides/ibaseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) | 設定複雜文字腳本字型資訊。Null 表示字型未定義，應從母版繼承。寫入 [IFontData](../../aspose.slides/ifontdata/)。 |
| virtual void [set_EastAsianFont](../../aspose.slides/ibaseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) | 設定東亞字型資訊。Null 表示字型未定義，應從母版繼承。寫入 [IFontData](../../aspose.slides/ifontdata/)。 |
| virtual void [set_Escapement](../../aspose.slides/ibaseportionformat/set_escapement/)(**float**) | 設定上標或下標文字。值介於 -100%（下標）至 100%（上標）。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從母版繼承。寫入 **float**。 |
| virtual void [set_FontBold](../../aspose.slides/ibaseportionformat/set_fontbold/)([NullableBool](../../aspose.slides/nullablebool/)) | 判斷字型是否為粗體。未套用繼承。寫入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_FontHeight](../../aspose.slides/ibaseportionformat/set_fontheight/)(**float**) | 設定部份的字型高度。**std::numeric_limits<float>::quiet_NaN()** 表示高度未定義，應從母版繼承。寫入 **float**。 |
| virtual void [set_FontItalic](../../aspose.slides/ibaseportionformat/set_fontitalic/)([NullableBool](../../aspose.slides/nullablebool/)) | 判斷字型是否為斜體。未套用繼承。寫入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_FontUnderline](../../aspose.slides/ibaseportionformat/set_fontunderline/)([TextUnderlineType](../../aspose.slides/textunderlinetype/)) | 設定文字底線類型。未套用繼承。寫入 [TextUnderlineType](../../aspose.slides/textunderlinetype/)。 |
| virtual void [set_IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/set_ishardunderlinefill/)([NullableBool](../../aspose.slides/nullablebool/)) | 判斷底線樣式是否具有自己的 [FillFormat](../../aspose.slides/fillformat/) 屬性，或從文字的 [FillFormat](../../aspose.slides/fillformat/) 屬性繼承。寫入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/set_ishardunderlineline/)([NullableBool](../../aspose.slides/nullablebool/)) | 判斷底線樣式是否具有自己的 [LineFormat](../../aspose.slides/lineformat/) 屬性，或從文字的 [LineFormat](../../aspose.slides/lineformat/) 屬性繼承。寫入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_KerningMinimalSize](../../aspose.slides/ibaseportionformat/set_kerningminimalsize/)(**float**) | 設定最小字型大小，對於此大小應啟用字距微調。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從母版繼承。寫入 **float**。 |
| virtual void [set_Kumimoji](../../aspose.slides/ibaseportionformat/set_kumimoji/)([NullableBool](../../aspose.slides/nullablebool/)) | 判斷數字是否應忽略文字東方語言特定的垂直排版。未套用繼承。寫入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_LanguageId](../../aspose.slides/ibaseportionformat/set_languageid/)([System::String](../../system/string/)) | 設定校對語言的 Id。用於檢查拼寫與文法。寫入 [System::String](../../system/string/)。 |
| virtual void [set_LatinFont](../../aspose.slides/ibaseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) | 設定拉丁字型資訊。Null 表示字型未定義，應從母版繼承。寫入 [IFontData](../../aspose.slides/ifontdata/)。 |
| virtual void [set_NormaliseHeight](../../aspose.slides/ibaseportionformat/set_normaliseheight/)([NullableBool](../../aspose.slides/nullablebool/)) | 判斷文字高度是否應正規化。未套用繼承。寫入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_ProofDisabled](../../aspose.slides/ibaseportionformat/set_proofdisabled/)([NullableBool](../../aspose.slides/nullablebool/)) | 判斷文字是否不應校對。未套用繼承。寫入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_Spacing](../../aspose.slides/ibaseportionformat/set_spacing/)(**float**) | 設定字元間距增量。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從母版繼承。寫入 **float**。 |
| virtual void [set_SpellCheck](../../aspose.slides/ibaseportionformat/set_spellcheck/)(**bool**) | 設定指示文字部份是否已啟用拼寫檢查的值。當此屬性設為 false 時，會抑制文字元素的拼寫檢查。設為 true 時，允許拼寫檢查。預設值為 **false**。 |
| virtual void [set_StrikethroughType](../../aspose.slides/ibaseportionformat/set_strikethroughtype/)([TextStrikethroughType](../../aspose.slides/textstrikethroughtype/)) | 設定文字的刪除線類型。未套用繼承。寫入 [TextStrikethroughType](../../aspose.slides/textstrikethroughtype/)。 |
| virtual void [set_SymbolFont](../../aspose.slides/ibaseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../../aspose.slides/ifontdata/)\>) | 設定符號字型資訊。Null 表示字型未定義，應從母版繼承。寫入 [IFontData](../../aspose.slides/ifontdata/)。 |
| virtual void [set_TextCapType](../../aspose.slides/ibaseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../../aspose.slides/textcaptype/)) | 設定文字大小寫類型。未套用繼承。寫入 [Slides::TextCapType](../../aspose.slides/textcaptype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [IBasePortionFormat](../../aspose.slides/ibaseportionformat/)
* 命名空間 [Aspose::Slides::Charts](../)
* 函式庫 [Aspose.Slides](../../)