---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides for C++ API 參考
description: 不可變物件的基礎介面，此類物件包含實際文字區段格式屬性。
type: docs
weight: 1470
url: /zh-hant/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData 類別

不可變物件的基礎介面，這些物件包含實際的文字區段格式屬性。

```cpp
class IBasePortionFormatEffectiveData : public virtual System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN），兩個 NaN 仍被視為相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN），兩個 NaN 仍被視為相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | 傳回替代語言的 Id。唯讀 [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | 傳回複合文字腳本字型資訊。唯讀 [IFontData](../ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | 傳回東亞字型資訊。唯讀 [IFontData](../ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [get_EffectFormat](./get_effectformat/)() | 傳回文字 [EffectFormat](../effectformat/) 屬性。唯讀 [IEffectFormatEffectiveData](../ieffectformateffectivedata/)。 |
| virtual **float** [get_Escapement](./get_escapement/)() | 傳回上標或下標文字。值介於 -100%（下標）至 100%（上標）。唯讀 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_FillFormat](./get_fillformat/)() | 傳回文字 [FillFormat](../fillformat/) 屬性。唯讀 [IFillFormatEffectiveData](../ifillformateffectivedata/)。 |
| virtual **bool** [get_FontBold](./get_fontbold/)() | 判斷字型是否為粗體。唯讀 **bool**。 |
| virtual **float** [get_FontHeight](./get_fontheight/)() | 傳回文字區段的字型高度（點）。唯讀 **float**。 |
| virtual **bool** [get_FontItalic](./get_fontitalic/)() | 判斷字型是否為斜體。唯讀 **bool**。 |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | 傳回文字底線類型。唯讀 [TextUnderlineType](../textunderlinetype/)。 |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_HighlightColor](./get_highlightcolor/)() | 傳回用於突顯文字的顏色。唯讀 [System::Drawing::Color](../../system.drawing/color/)。 |
| virtual **bool** [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | 判斷底線樣式是否具有自訂的 [FillFormat](../fillformat/) 屬性，或從文字的 [FillFormat](../fillformat/) 屬性繼承。唯讀 **bool**。 |
| virtual **bool** [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | 判斷底線樣式是否具有自訂的 [LineFormat](../lineformat/) 屬性，或從文字的 [LineFormat](../lineformat/) 屬性繼承。唯讀 **bool**。 |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | 傳回最小字型尺寸，當字距微調應啟用時使用。唯讀 **float**。 |
| virtual **bool** [get_Kumimoji](./get_kumimoji/)() | 判斷數字是否應忽略文字的東方語言特定垂直排版。唯讀 **bool**。 |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | 傳回語言的 Id。唯讀 [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | 傳回拉丁字型資訊。唯讀 [IFontData](../ifontdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_LineFormat](./get_lineformat/)() | 傳回文字描邊的 [LineFormat](../lineformat/) 屬性。唯讀 [ILineFormatEffectiveData](../ilineformateffectivedata/)。 |
| virtual **bool** [get_NormaliseHeight](./get_normaliseheight/)() | 判斷文字的高度是否應正規化。唯讀 **bool**。 |
| virtual **bool** [get_ProofDisabled](./get_proofdisabled/)() | 判斷文字是否不應進行校對。唯讀 **bool**。 |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | 判斷智慧標籤是否應被清除。唯讀 **bool**。 |
| virtual **float** [get_Spacing](./get_spacing/)() | 傳回字元間距增量（點）。唯讀 **float**。 |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | 傳回文字的刪除線類型。唯讀 [TextStrikethroughType](../textstrikethroughtype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | 傳回符號字型資訊。唯讀 [IFontData](../ifontdata/)。 |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | 傳回文字大小寫類型。唯讀 [Slides::TextCapType](../textcaptype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | 傳回底線線條 [FillFormat](../fillformat/) 屬性。唯讀 [IFillFormatEffectiveData](../ifillformateffectivedata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | 傳回用於描邊底線線條的 [LineFormat](../lineformat/) 屬性。唯讀 [ILineFormatEffectiveData](../ilineformateffectivedata/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。允許自訂物件雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。允許複製自訂型別。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 針對字串與 nullptr 情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 針對字串情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。允許將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [Object](../../system/object/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)