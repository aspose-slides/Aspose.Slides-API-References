---
title: BasePortionFormat
second_title: Aspose.Slides for C++ API 參考文件
description: 常見文字部份格式屬性。
type: docs
weight: 144
url: /zh-hant/aspose.slides/baseportionformat/
---
## BasePortionFormat 類別

常見文字部份格式屬性。

```cpp
class BasePortionFormat : public Aspose::Slides::PVIObject,
                          public virtual Aspose::Slides::IBasePortionFormat
```

## 方法

| 方法 | 說明 |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 與指定的物件比較。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管依 IEC 60559:1989，NaN 與任何值（包括 NaN）都不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管依 IEC 60559:1989，NaN 與任何值（包括 NaN）都不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() override | 傳回替代語言的 Id。讀取 [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() override | 傳回複雜文字腳本的字型資訊。Null 表示字型未定義，應從主體繼承。讀取 [IFontData](../ifontdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() override | 傳回東亞字型資訊。Null 表示字型未定義，應從主體繼承。讀取 [IFontData](../ifontdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | 傳回文字 [EffectFormat](../effectformat/) 屬性。未套用繼承。唯讀 [IEffectFormat](../ieffectformat/)。 |
| **float** [get_Escapement](./get_escapement/)() override | 傳回上標或下標文字。值介於 -100%（下標）至 100%（上標）。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從主體繼承。讀取 **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | 傳回文字 [FillFormat](../fillformat/) 屬性。未套用繼承。唯讀 [IFillFormat](../ifillformat/)。 |
| [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() override | 判斷字型是否為粗體。未套用繼承。讀取 [NullableBool](../nullablebool/)。 |
| **float** [get_FontHeight](./get_fontheight/)() override | 傳回部份的字型高度。**std::numeric_limits<float>::quiet_NaN()** 表示高度未定義，應從主體繼承。讀取 **float**。 |
| [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() override | 判斷字型是否為斜體。未套用繼承。讀取 [NullableBool](../nullablebool/)。 |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() override | 傳回文字底線類型。未套用繼承。讀取 [TextUnderlineType](../textunderlinetype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() override | 傳回用於突顯文字的顏色。未套用繼承。唯讀 [IColorFormat](../icolorformat/)。 |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() override | 判斷底線樣式是否具有自己的 [FillFormat](../fillformat/) 屬性，或從文字的 [FillFormat](../fillformat/) 屬性繼承。讀取 [NullableBool](../nullablebool/)。 |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() override | 判斷底線樣式是否具有自己的 [LineFormat](../lineformat/) 屬性，或從文字的 [LineFormat](../lineformat/) 屬性繼承。讀取 [NullableBool](../nullablebool/)。 |
| **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() override | 傳回字型最小尺寸，當字距調整應啟用時。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從主體繼承。讀取 **float**。 |
| [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() override | 判斷數字是否應忽略文字東方語言特定的垂直排版。未套用繼承。讀取 [NullableBool](../nullablebool/)。 |
| [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() override | 傳回校對語言的 Id。用於拼寫與文法檢查。讀取 [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() override | 傳回拉丁字型資訊。Null 表示字型未定義，應從主體繼承。讀取 [IFontData](../ifontdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | 傳回文字描邊的 [LineFormat](../lineformat/) 屬性。未套用繼承。唯讀 [ILineFormat](../ilineformat/)。 |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() override | 判斷文字的高度是否應正規化。未套用繼承。讀取 [NullableBool](../nullablebool/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | 傳回 Parent_Immediate 物件。唯讀 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 傳回父層 [IPresentationComponent](../ipresentationcomponent/)。唯讀 [IPresentationComponent](../ipresentationcomponent/)。 |
| [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() override | 判斷文字是否不應進行校對。未套用繼承。讀取 [NullableBool](../nullablebool/)。 |
| **float** [get_Spacing](./get_spacing/)() override | 傳回字元間距增量。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從主體繼承。讀取 **float**。 |
| **bool** [get_SpellCheck](./get_spellcheck/)() override | 取得指示是否為文字部份啟用拼寫檢查的值。當此屬性設為 false 時，文字元素的拼寫檢查會被抑制。設為 true 時，允許拼寫檢查。預設值為 **false**。 |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() override | 傳回文字的刪除線類型。未套用繼承。讀取 [TextStrikethroughType](../textstrikethroughtype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() override | 傳回符號字型資訊。Null 表示字型未定義，應從主體繼承。讀取 [IFontData](../ifontdata/)。 |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() override | 傳回文字大寫類型。未套用繼承。讀取 [Slides::TextCapType](../textcaptype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() override | 傳回底線線條 [FillFormat](../fillformat/) 屬性。未套用繼承。唯讀 [IFillFormat](../ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() override | 傳回用於描邊底線線條的 [LineFormat](../lineformat/) 屬性。未套用繼承。唯讀 [ILineFormat](../ilineformat/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | 傳回雜湊碼。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 描述的型別實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
|   [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|   [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 將值型別物件與 nullptr 進行參考比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 針對字串與 nullptr 情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 針對字串情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參考計數。 |
| void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) override | 設定替代語言的 Id。寫入 [System::String](../../system/string/)。 |
| void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 設定複雜文字腳本的字型資訊。Null 表示字型未定義，應從主體繼承。寫入 [IFontData](../ifontdata/)。 |
| void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 設定東亞字型資訊。Null 表示字型未定義，應從主體繼承。寫入 [IFontData](../ifontdata/)。 |
| void [set_Escapement](./set_escapement/)(**float**) override | 設定上標或下標文字。值介於 -100%（下標）至 100%（上標）。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從主體繼承。寫入 **float**。 |
| void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) override | 判斷字型是否為粗體。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| void [set_FontHeight](./set_fontheight/)(**float**) override | 設定部份的字型高度。**std::numeric_limits<float>::quiet_NaN()** 表示高度未定義，應從主體繼承。寫入 **float**。 |
| void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) override | 判斷字型是否為斜體。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | 設定文字底線類型。未套用繼承。寫入 [TextUnderlineType](../textunderlinetype/)。 |
| void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | 判斷底線樣式是否具有自己的 [FillFormat](../fillformat/) 屬性，或從文字的 [FillFormat](../fillformat/) 屬性繼承。寫入 [NullableBool](../nullablebool/)。 |
| void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | 判斷底線樣式是否具有自己的 [LineFormat](../lineformat/) 屬性，或從文字的 [LineFormat](../lineformat/) 屬性繼承。寫入 [NullableBool](../nullablebool/)。 |
| void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) override | 設定字型最小尺寸，當字距調整應啟用時。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從主體繼承。寫入 **float**。 |
| void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) override | 判斷數字是否應忽略文字東方語言特定的垂直排版。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) override | 設定校對語言的 Id。用於拼寫與文法檢查。寫入 [System::String](../../system/string/)。 |
| void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 設定拉丁字型資訊。Null 表示字型未定義，應從主體繼承。寫入 [IFontData](../ifontdata/)。 |
| void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) override | 判斷文字的高度是否應正規化。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) override | 判斷文字是否不應進行校對。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| void [set_Spacing](./set_spacing/)(**float**) override | 設定字元間距增量。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從主體繼承。寫入 **float**。 |
| void [set_SpellCheck](./set_spellcheck/)(**bool**) override | 設定指示是否為文字部份啟用拼寫檢查的值。當此屬性設為 false 時，文字元素的拼寫檢查會被抑制。設為 true 時，允許拼寫檢查。預設值為 **false**。 |
| void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | 設定文字的刪除線類型。未套用繼承。寫入 [TextStrikethroughType](../textstrikethroughtype/)。 |
| void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | 設定符號字型資訊。Null 表示字型未定義，應從主體繼承。寫入 [IFontData](../ifontdata/)。 |
| void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | 設定文字大寫類型。未套用繼承。寫入 [Slides::TextCapType](../textcaptype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [PVIObject](../pviobject/)
* 類別 [IBasePortionFormat](../ibaseportionformat/)
* 命名空間 [Aspose::Slides](../)
* 程式庫 [Aspose.Slides](../../)