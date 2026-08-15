---
title: IPortionFormat
second_title: Aspose.Slides for C++ API 參考
description: 此類別包含文字部分的格式屬性。與 IPortionFormatEffectiveData 不同，此類別的所有屬性皆可寫入。
type: docs
weight: 3329
url: /zh-hant/aspose.slides/iportionformat/
---
## IPortionFormat 類別

This class contains the text portion formatting properties. Unlike [IPortionFormatEffectiveData](../iportionformateffectivedata/), all properties of this class are writeable.

```cpp
class IPortionFormat : public virtual Aspose::Slides::IBasePortionFormat,
                       public Aspose::Slides::IHyperlinkContainer
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使 IEC 60559:1989 規定 NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使 IEC 60559:1989 規定 NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../ibaseportionformat/get_alternativelanguageid/)() | 取得替代語言的 Id。請閱讀 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() | 取得書籤識別碼。請閱讀 [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../ibaseportionformat/get_complexscriptfont/)() | 取得複合腳本字型資訊。Null 表示字型未定義，應從母版繼承。請閱讀 [IFontData](../ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../ibaseportionformat/get_eastasianfont/)() | 取得東亞字型資訊。Null 表示字型未定義，應從母版繼承。請閱讀 [IFontData](../ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ibaseportionformat/get_effectformat/)() | 取得文字 [EffectFormat](../effectformat/) 屬性。未套用繼承。唯讀 [IEffectFormat](../ieffectformat/)。 |
| virtual **float** [get_Escapement](../ibaseportionformat/get_escapement/)() | 取得上標或下標文字。值介於 -100%（下標）至 100%（上標）。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從母版繼承。唯讀 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ibaseportionformat/get_fillformat/)() | 取得文字 [FillFormat](../fillformat/) 屬性。未套用繼承。唯讀 [IFillFormat](../ifillformat/)。 |
| virtual [NullableBool](../nullablebool/) [get_FontBold](../ibaseportionformat/get_fontbold/)() | 判斷字型是否為粗體。未套用繼承。請閱讀 [NullableBool](../nullablebool/)。 |
| virtual **float** [get_FontHeight](../ibaseportionformat/get_fontheight/)() | 取得部分字型的高度。**std::numeric_limits<float>::quiet_NaN()** 表示高度未定義，應從母版繼承。唯讀 **float**。 |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](../ibaseportionformat/get_fontitalic/)() | 判斷字型是否為斜體。未套用繼承。請閱讀 [NullableBool](../nullablebool/)。 |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../ibaseportionformat/get_fontunderline/)() | 取得文字底線類型。未套用繼承。請閱讀 [TextUnderlineType](../textunderlinetype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../ibaseportionformat/get_highlightcolor/)() | 取得用於突出顯示文字的顏色。未套用繼承。唯讀 [IColorFormat](../icolorformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | 取得滑鼠點擊時定義的超連結。請閱讀 [IHyperlink](../ihyperlink/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | 超連結管理員。唯讀 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | 取得滑鼠移過時定義的超連結。請閱讀 [IHyperlink](../ihyperlink/)。 |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../ibaseportionformat/get_ishardunderlinefill/)() | 判斷底線樣式是否具有自己的 [FillFormat](../fillformat/) 屬性，或從文字的 [FillFormat](../fillformat/) 屬性繼承。請閱讀 [NullableBool](../nullablebool/)。 |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../ibaseportionformat/get_ishardunderlineline/)() | 判斷底線樣式是否具有自己的 [LineFormat](../lineformat/) 屬性，或從文字的 [LineFormat](../lineformat/) 屬性繼承。請閱讀 [NullableBool](../nullablebool/)。 |
| virtual **float** [get_KerningMinimalSize](../ibaseportionformat/get_kerningminimalsize/)() | 取得應開啟字距調整的最小字型大小。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從母版繼承。唯讀 **float**。 |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](../ibaseportionformat/get_kumimoji/)() | 判斷數字是否應忽略文字東方語系特定的垂直排版。未套用繼承。請閱讀 [NullableBool](../nullablebool/)。 |
| virtual [System::String](../../system/string/) [get_LanguageId](../ibaseportionformat/get_languageid/)() | 取得拼寫檢查語言的 Id。用於拼寫與文法檢查。請閱讀 [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../ibaseportionformat/get_latinfont/)() | 取得拉丁字型資訊。Null 表示字型未定義，應從母版繼承。請閱讀 [IFontData](../ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ibaseportionformat/get_lineformat/)() | 取得文字描邊的 [LineFormat](../lineformat/) 屬性。未套用繼承。唯讀 [ILineFormat](../ilineformat/)。 |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](../ibaseportionformat/get_normaliseheight/)() | 判斷文字高度是否應正規化。未套用繼承。請閱讀 [NullableBool](../nullablebool/)。 |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](../ibaseportionformat/get_proofdisabled/)() | 判斷文字是否不應進行校對。未套用繼承。請閱讀 [NullableBool](../nullablebool/)。 |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | 判斷智慧標籤是否應清除。未套用繼承。唯讀 **bool**。 |
| virtual **float** [get_Spacing](../ibaseportionformat/get_spacing/)() | 取得字元間距增量。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從母版繼承。唯讀 **float**。 |
| virtual **bool** [get_SpellCheck](../ibaseportionformat/get_spellcheck/)() | 取得指示文字部分是否已啟用拼寫檢查的值。當此屬性設為 false 時，會抑制文字元素的拼寫檢查；設為 true 時則允許。預設值為 **false**。 |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../ibaseportionformat/get_strikethroughtype/)() | 取得文字的刪除線類型。未套用繼承。請閱讀 [TextStrikethroughType](../textstrikethroughtype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../ibaseportionformat/get_symbolfont/)() | 取得符號字型資訊。Null 表示字型未定義，應從母版繼承。請閱讀 [IFontData](../ifontdata/)。 |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../ibaseportionformat/get_textcaptype/)() | 取得文字大小寫類型。未套用繼承。請閱讀 [Slides::TextCapType](../textcaptype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../ibaseportionformat/get_underlinefillformat/)() | 取得底線線條 [FillFormat](../fillformat/) 屬性。未套用繼承。唯讀 [IFillFormat](../ifillformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../ibaseportionformat/get_underlinelineformat/)() | 取得用於描邊底線線條的 [LineFormat](../lineformat/) 屬性。未套用繼承。唯讀 [ILineFormat](../ilineformat/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() | 取得套用繼承後的有效部分格式資料。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的等價。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為目標型別的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視器物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的等價。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 以指定值減少共享參考計數。 |
| virtual void [set_AlternativeLanguageId](../ibaseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) | 設定替代語言的 Id。寫入 [System::String](../../system/string/)。 |
| virtual void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) | 設定書籤識別碼。寫入 [System::String](../../system/string/)。 |
| virtual void [set_ComplexScriptFont](../ibaseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | 設定複合腳本字型資訊。Null 表示字型未定義，應從母版繼承。寫入 [IFontData](../ifontdata/)。 |
| virtual void [set_EastAsianFont](../ibaseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | 設定東亞字型資訊。Null 表示字型未定義，應從母版繼承。寫入 [IFontData](../ifontdata/)。 |
| virtual void [set_Escapement](../ibaseportionformat/set_escapement/)(**float**) | 設定上標或下標文字。值介於 -100%（下標）至 100%（上標）。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從母版繼承。寫入 **float**。 |
| virtual void [set_FontBold](../ibaseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) | 判斷字型是否為粗體。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| virtual void [set_FontHeight](../ibaseportionformat/set_fontheight/)(**float**) | 設定部分字型的高度。**std::numeric_limits<float>::quiet_NaN()** 表示高度未定義，應從母版繼承。寫入 **float**。 |
| virtual void [set_FontItalic](../ibaseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) | 判斷字型是否為斜體。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| virtual void [set_FontUnderline](../ibaseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | 設定文字底線類型。未套用繼承。寫入 [TextUnderlineType](../textunderlinetype/)。 |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | 設定滑鼠點擊時的超連結。寫入 [IHyperlink](../ihyperlink/)。 |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | 設定滑鼠移過時的超連結。寫入 [IHyperlink](../ihyperlink/)。 |
| virtual void [set_IsHardUnderlineFill](../ibaseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | 判斷底線樣式是否具有自己的 [FillFormat](../fillformat/) 屬性，或從文字的 [FillFormat](../fillformat/) 屬性繼承。寫入 [NullableBool](../nullablebool/)。 |
| virtual void [set_IsHardUnderlineLine](../ibaseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) | 判斷底線樣式是否具有自己的 [LineFormat](../lineformat/) 屬性，或從文字的 [LineFormat](../lineformat/) 屬性繼承。寫入 [NullableBool](../nullablebool/)。 |
| virtual void [set_KerningMinimalSize](../ibaseportionformat/set_kerningminimalsize/)(**float**) | 設定應開啟字距調整的最小字型大小。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從母版繼承。寫入 **float**。 |
| virtual void [set_Kumimoji](../ibaseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) | 判斷數字是否應忽略文字東方語系特定的垂直排版。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| virtual void [set_LanguageId](../ibaseportionformat/set_languageid/)([System::String](../../system/string/)) | 設定拼寫檢查語言的 Id。用於拼寫與文法檢查。寫入 [System::String](../../system/string/)。 |
| virtual void [set_LatinFont](../ibaseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | 設定拉丁字型資訊。Null 表示字型未定義，應從母版繼承。寫入 [IFontData](../ifontdata/)。 |
| virtual void [set_NormaliseHeight](../ibaseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) | 判斷文字高度是否應正規化。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| virtual void [set_ProofDisabled](../ibaseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) | 判斷文字是否不應進行校對。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| virtual void [set_SmartTagClean](./set_smarttagclean/)(**bool**) | 判斷智慧標籤是否應清除。未套用繼承。寫入 **bool**。 |
| virtual void [set_Spacing](../ibaseportionformat/set_spacing/)(**float**) | 設定字元間距增量。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從母版繼承。寫入 **float**。 |
| virtual void [set_SpellCheck](../ibaseportionformat/set_spellcheck/)(**bool**) | 設定指示文字部分是否已啟用拼寫檢查的值。當此屬性設為 false 時，會抑制文字元素的拼寫檢查；設為 true 時則允許。預設值為 **false**。 |
| virtual void [set_StrikethroughType](../ibaseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | 設定文字的刪除線類型。未套用繼承。寫入 [TextStrikethroughType](../textstrikethroughtype/)。 |
| virtual void [set_SymbolFont](../ibaseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | 設定符號字型資訊。Null 表示字型未定義，應從母版繼承。寫入 [IFontData](../ifontdata/)。 |
| virtual void [set_TextCapType](../ibaseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | 設定文字大小寫類型。未套用繼承。寫入 [Slides::TextCapType](../textcaptype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得目前共享參考計數的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 減少並回傳共享參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的等價。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視器物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 減少弱參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 備註

此類別用於返回與操作針對特定部分定義的文字部分格式屬性。這表示取得值時不會套用繼承，因此在大多數情況下會得到「未定義」的值。

若要取得包含繼承在內的有效格式參數值，需使用 [IPortionFormat::GetEffective](./geteffective/) 方法，該方法會回傳一個 [IPortionFormatEffectiveData](../iportionformateffectivedata/) 實例。

## 另請參閱

* 類別 [IBasePortionFormat](../ibaseportionformat/)
* 類別 [IHyperlinkContainer](../ihyperlinkcontainer/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)