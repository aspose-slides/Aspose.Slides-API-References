---
title: IHyperlink
second_title: Aspose.Slides for C++ API 參考
description: 代表一個超連結。
type: docs
weight: 2523
url: /zh-hant/aspose.slides/ihyperlink/
---
## IHyperlink 類別


Represents a hyperlink.

```cpp
class IHyperlink : public virtual System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意來比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [HyperlinkActionType](../hyperlinkactiontype/) [get_ActionType](./get_actiontype/)() | 回傳 HyperLinkEx 的動作類型。唯讀 [HyperlinkActionType](../hyperlinkactiontype/)。 |
| virtual [HyperlinkColorSource](../hyperlinkcolorsource/) [get_ColorSource](./get_colorsource/)() | 表示超連結顏色的來源──樣式或區段格式。讀取 [HyperlinkColorSource](../hyperlinkcolorsource/)。 |
| virtual [System::String](../../system/string/) [get_ExternalUrl](./get_externalurl/)() | 指定外部 URL。如果此屬性變為非 null，則屬性 TargetSlide 變為 null。唯讀 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_ExternalUrlOriginal](./get_externalurloriginal/)() | 表示設定於此區段的超連結，與區段的實際內容無關。 |
| virtual **bool** [get_HighlightClick](./get_highlightclick/)() | 判斷點擊時是否應突顯此超連結。讀取 **bool**。 |
| virtual **bool** [get_History](./get_history/)() | 判斷在呼叫時，父超連結的目標是否應加入已檢視超連結的清單。讀取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() | 表示超連結的播放音效。讀取 [IAudio](../iaudio/)。 |
| virtual **bool** [get_StopSoundOnClick](./get_stopsoundonclick/)() | 判斷點擊超連結時是否應停止音效。讀取 **bool**。 |
| virtual [System::String](../../system/string/) [get_TargetFrame](./get_targetframe/)() | 當父超連結的目標存在時，返回父 HTML frameset 中的框架。讀取 [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() | 如果 HyperlinkEx 目標是特定投影片，則返回該投影片。如果此屬性變為非 null，則屬性 ExternalUrl 變為 null。唯讀 [ISlide](../islide/)。 |
| virtual [System::String](../../system/string/) [get_Tooltip](./get_tooltip/)() | 返回可能在使用者介面中顯示，且與父超連結相關聯的字串。讀取 [System::String](../../system/string/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。允許自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視器物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。允許自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參考計數。 |
| virtual void [set_ColorSource](./set_colorsource/)([HyperlinkColorSource](../hyperlinkcolorsource/)) | 表示超連結顏色的來源──樣式或區段格式。寫入 [HyperlinkColorSource](../hyperlinkcolorsource/)。 |
| virtual void [set_HighlightClick](./set_highlightclick/)(**bool**) | 判斷點擊時是否應突顯此超連結。寫入 **bool**。 |
| virtual void [set_History](./set_history/)(**bool**) | 判斷在呼叫時，父超連結的目標是否應加入已檢視超連結的清單。寫入 **bool**。 |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | 表示超連結的播放音效。寫入 [IAudio](../iaudio/)。 |
| virtual void [set_StopSoundOnClick](./set_stopsoundonclick/)(**bool**) | 判斷點擊超連結時是否應停止音效。寫入 **bool**。 |
| virtual void [set_TargetFrame](./set_targetframe/)([System::String](../../system/string/)) | 當父超連結的目標存在時，返回父 HTML frameset 中的框架。寫入 [System::String](../../system/string/)。 |
| virtual void [set_Tooltip](./set_tooltip/)([System::String](../../system/string/)) | 返回可能在使用者介面中顯示，且與父超連結相關聯的字串。寫入 [System::String](../../system/string/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中切換指標為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。允許將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視器物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [Object](../../system/object/)
* 名稱空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)