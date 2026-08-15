---
title: IBasePortionFormat
second_title: Aspose.Slides for C++ API 參考
description: 此類別包含文字區段格式屬性。與 IPortionFormatEffectiveData 不同，此類別的所有屬性皆可寫入。
type: docs
weight: 1457
url: /zh-hant/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat 類別

此類別包含文字部份格式屬性。與 [IPortionFormatEffectiveData](../iportionformateffectivedata/) 不同，此類別的所有屬性皆可寫入。

```cpp
class IBasePortionFormat : public virtual System::Object
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | 傳回替代語言的 Id。請參閱 [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | 傳回複合文字腳本字型資訊。Null 表示字型未定義，應從母版繼承。請參閱 [IFontData](../ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | 傳回東亞字型資訊。Null 表示字型未定義，應從母版繼承。請參閱 [IFontData](../ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | 傳回文字 [EffectFormat](../effectformat/) 屬性。未套用繼承。唯讀 [IEffectFormat](../ieffectformat/)。 |
| virtual **float** [get_Escapement](./get_escapement/)() | 傳回上標或下標文字。值範圍從 -100%（下標）到 100%（上標）。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從母版繼承。唯讀 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | 傳回文字 [FillFormat](../fillformat/) 屬性。未套用繼承。唯讀 [IFillFormat](../ifillformat/)。 |
| virtual [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() | 判斷字型是否為粗體。未套用繼承。請參閱 [NullableBool](../nullablebool/)。 |
| virtual **float** [get_FontHeight](./get_fontheight/)() | 傳回部份的字型高度。**std::numeric_limits<float>::quiet_NaN()** 表示高度未定義，應從母版繼承。唯讀 **float**。 |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() | 判斷字型是否為斜體。未套用繼承。請參閱 [NullableBool](../nullablebool/)。 |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | 傳回文字底線類型。未套用繼承。請參閱 [TextUnderlineType](../textunderlinetype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() | 傳回用於標示文字的顏色。未套用繼承。唯讀 [IColorFormat](../icolorformat/)。 |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | 判斷底線樣式是否具有自己的 [FillFormat](../fillformat/) 屬性或從文字的 [FillFormat](../fillformat/) 屬性繼承。請參閱 [NullableBool](../nullablebool/)。 |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | 判斷底線樣式是否具有自己的 [LineFormat](../lineformat/) 屬性或從文字的 [LineFormat](../lineformat/) 屬性繼承。請參閱 [NullableBool](../nullablebool/)。 |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | 傳回啟用字距調整所需的最小字型大小。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從母版繼承。唯讀 **float**。 |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() | 判斷數字是否應忽略文字東方語言特定的垂直排版。未套用繼承。請參閱 [NullableBool](../nullablebool/)。 |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | 傳回校對語言的 Id。用於拼寫和文法檢查。請參閱 [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | 傳回拉丁字型資訊。Null 表示字型未定義，應從母版繼承。請參閱 [IFontData](../ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | 傳回文字描邊的 [LineFormat](../lineformat/) 屬性。未套用繼承。唯讀 [ILineFormat](../ilineformat/)。 |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() | 判斷文字高度是否應正規化。未套用繼承。請參閱 [NullableBool](../nullablebool/)。 |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() | 判斷文字是否不進行校對。未套用繼承。請參閱 [NullableBool](../nullablebool/)。 |
| virtual **float** [get_Spacing](./get_spacing/)() | 傳回字元間距增量。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從母版繼承。唯讀 **float**。 |
| virtual **bool** [get_SpellCheck](./get_spellcheck/)() | 取得指示文字部份是否啟用拼寫檢查的值。當此屬性設為 false 時，文字元素的拼寫檢查會被抑制。設為 true 時，則允許拼寫檢查。預設值為 **false**。 |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | 傳回文字的刪除線類型。未套用繼承。請參閱 [TextStrikethroughType](../textstrikethroughtype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | 傳回符號字型資訊。Null 表示字型未定義，應從母版繼承。請參閱 [IFontData](../ifontdata/)。 |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | 傳回文字大小寫類型。未套用繼承。請參閱 [Slides::TextCapType](../textcaptype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | 傳回底線線條 [FillFormat](../fillformat/) 屬性。未套用繼承。唯讀 [IFillFormat](../ifillformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | 傳回用於描邊底線線條的 [LineFormat](../lineformat/) 屬性。未套用繼承。唯讀 [ILineFormat](../ilineformat/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參照計數器資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述的類型實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 警戒物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指定運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參照方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參照方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參照方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，適用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，適用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值遞減共享參照計數。 |
| virtual void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) | 設定替代語言的 Id。寫入 [System::String](../../system/string/)。 |
| virtual void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | 設定複合文字腳本字型資訊。Null 表示字型未定義，應從母版繼承。寫入 [IFontData](../ifontdata/)。 |
| virtual void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | 設定東亞字型資訊。Null 表示字型未定義，應從母版繼承。寫入 [IFontData](../ifontdata/)。 |
| virtual void [set_Escapement](./set_escapement/)(**float**) | 設定上標或下標文字。值範圍從 -100%（下標）到 100%（上標）。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從母版繼承。寫入 **float**。 |
| virtual void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) | 判斷字型是否為粗體。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| virtual void [set_FontHeight](./set_fontheight/)(**float**) | 設定部份的字型高度。**std::numeric_limits<float>::quiet_NaN()** 表示高度未定義，應從母版繼承。寫入 **float**。 |
| virtual void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) | 判斷字型是否為斜體。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| virtual void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | 設定文字底線類型。未套用繼承。寫入 [TextUnderlineType](../textunderlinetype/)。 |
| virtual void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | 判斷底線樣式是否具有自己的 [FillFormat](../fillformat/) 屬性或從文字的 [FillFormat](../fillformat/) 屬性繼承。寫入 [NullableBool](../nullablebool/)。 |
| virtual void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) | 判斷底線樣式是否具有自己的 [LineFormat](../lineformat/) 屬性或從文字的 [LineFormat](../lineformat/) 屬性繼承。寫入 [NullableBool](../nullablebool/)。 |
| virtual void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) | 設定啟用字距調整所需的最小字型大小。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從母版繼承。寫入 **float**。 |
| virtual void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) | 判斷數字是否應忽略文字東方語言特定的垂直排版。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| virtual void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) | 設定校對語言的 Id。用於拼寫和文法檢查。寫入 [System::String](../../system/string/)。 |
| virtual void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | 設定拉丁字型資訊。Null 表示字型未定義，應從母版繼承。寫入 [IFontData](../ifontdata/)。 |
| virtual void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) | 判斷文字高度是否應正規化。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| virtual void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) | 判斷文字是否不進行校對。未套用繼承。寫入 [NullableBool](../nullablebool/)。 |
| virtual void [set_Spacing](./set_spacing/)(**float**) | 設定字元間距增量。**std::numeric_limits<float>::quiet_NaN()** 表示值未定義，應從母版繼承。寫入 **float**。 |
| virtual void [set_SpellCheck](./set_spellcheck/)(**bool**) | 設定指示文字部份是否啟用拼寫檢查的值。當此屬性設為 false 時，文字元素的拼寫檢查會被抑制。設為 true 時，則允許拼寫檢查。預設值為 **false**。 |
| virtual void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | 設定文字的刪除線類型。未套用繼承。寫入 [TextStrikethroughType](../textstrikethroughtype/)。 |
| virtual void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | 設定符號字型資訊。Null 表示字型未定義，應從母版繼承。寫入 [IFontData](../ifontdata/)。 |
| virtual void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | 設定文字大小寫類型。未套用繼承。寫入 [Slides::TextCapType](../textcaptype/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得當前共享參照計數的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共享參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 警戒物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 備註

此類別用於傳回與操作特定部份所定義的文字部份格式屬性。這表示在取得值時不會套用繼承，因此在大多數情況下會得到表示「未定義」的值。

若要取得包括繼承在內的實際格式參數值，需要使用 [IPortionFormat::GetEffective](../iportionformat/geteffective/) 方法，該方法傳回 [IPortionFormatEffectiveData](../iportionformateffectivedata/) 實例。

## 另請參閱

* 類別 [Object](../../system/object/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)