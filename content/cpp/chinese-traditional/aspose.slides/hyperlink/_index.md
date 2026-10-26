---
title: Hyperlink
second_title: Aspose.Slides C++ API 參考
description: 表示一個超連結。
type: docs
weight: 1236
url: /zh-hant/aspose.slides/hyperlink/
---
## Hyperlink 類別


表示一個超連結。

```cpp
class Hyperlink : public Aspose::Slides::PVIObject,
                  public Aspose::Slides::IHyperlink
```

## 方法

| 方法 | 描述 |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 判斷兩個 [Hyperlink](./) 實例是否相等。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，其中兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，其中兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [HyperlinkActionType](../hyperlinkactiontype/) [get_ActionType](./get_actiontype/)() override | 傳回 [Hyperlink](./) 動作的類型。唯讀 [HyperlinkActionType](../hyperlinkactiontype/)。 |
| [HyperlinkColorSource](../hyperlinkcolorsource/) [get_ColorSource](./get_colorsource/)() override | 表示超連結顏色的來源──樣式或文字片段格式。唯讀 [HyperlinkColorSource](../hyperlinkcolorsource/)。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_EndShow](./get_endshow/)() | 傳回結束簡報的超連結。唯讀 [Hyperlink](./)。 |
| [System::String](../../system/string/) [get_ExternalUrl](./get_externalurl/)() override | 指定外部 URL。唯讀 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_ExternalUrlOriginal](./get_externalurloriginal/)() override | 表示針對此文字片段設定的超連結，與該片段的實際內容無關。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_FirstSlide](./get_firstslide/)() | 傳回指向簡報第一張投影片的超連結。唯讀 [Hyperlink](./)。 |
| **bool** [get_HighlightClick](./get_highlightclick/)() override | 判斷點擊時是否應突顯此超連結。讀取 **bool**。 |
| **bool** [get_History](./get_history/)() override | 判斷在呼叫父超連結時，是否將其目標加入已檢視超連結清單。讀取 **bool**。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_LastSlide](./get_lastslide/)() | 傳回指向簡報最後一張投影片的超連結。唯讀 [Hyperlink](./)。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_LastVievedSlide](./get_lastvievedslide/)() | 傳回指向最後檢視過的投影片的超連結。唯讀 [Hyperlink](./)。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_Media](./get_media/)() | 傳回特殊的「播放媒體檔」超連結。用於 [AudioFrame](../audioframe/) 與 [VideoFrame](../videoframe/)。唯讀 [Hyperlink](./)。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_NextSlide](./get_nextslide/)() | 傳回指向下一張投影片的超連結。唯讀 [Hyperlink](./)。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_NoAction](./get_noaction/)() | 傳回特殊的「什麼都不做」超連結。唯讀 [Hyperlink](./)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 傳回父層 [IPresentationComponent](../ipresentationcomponent/)。唯讀 [IPresentationComponent](../ipresentationcomponent/)。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_PreviousSlide](./get_previousslide/)() | 傳回指向前一張投影片的超連結。唯讀 [Hyperlink](./)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() override | 表示超連結的播放聲音。唯讀 [IAudio](../iaudio/)。 |
| **bool** [get_StopSoundOnClick](./get_stopsoundonclick/)() override | 判斷在點擊超連結時是否應停止聲音。讀取 **bool**。 |
| [System::String](../../system/string/) [get_TargetFrame](./get_targetframe/)() override | 傳回父 HTML 框架集中，父超連結目標所在的框架（若存在）。讀寫 [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() override | 如果 [Hyperlink](./) 目標為特定投影片，則傳回該投影片。唯讀 [ISlide](../islide/)。 |
| [System::String](../../system/string/) [get_Tooltip](./get_tooltip/)() override | 傳回可能在使用者介面中顯示、與父超連結關聯的字串。唯讀 [System::String](../../system/string/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 作為特定類型的雜湊函式，適用於雜湊演算法及如雜湊表等資料結構。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
|  [Hyperlink](./hyperlink/)([System::String](../../system/string/)) | 建立超連結的執行個體。 |
|  [Hyperlink](./hyperlink/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) | 建立指向特定投影片的超連結執行個體。注意：建立的超連結應指派給同一簡報中的物件，否則連結會儲存為 NoAction。 |
|  [Hyperlink](./hyperlink/)([System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\>, [System::String](../../system/string/), [System::String](../../system/string/), **bool**, **bool**, **bool**) | 使用另一個超連結作為來源，覆寫次要屬性，建立超連結執行個體。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的執行個體。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。可直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構函式。實際上不複製任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不複製任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值類型物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，適用於字串與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，適用於字串。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [set_ColorSource](./set_colorsource/)([HyperlinkColorSource](../hyperlinkcolorsource/)) override | 表示超連結顏色的來源──樣式或文字片段格式。寫入 [HyperlinkColorSource](../hyperlinkcolorsource/)。 |
| void [set_HighlightClick](./set_highlightclick/)(**bool**) override | 判斷點擊時是否應突顯此超連結。寫入 **bool**。 |
| void [set_History](./set_history/)(**bool**) override | 判斷在呼叫父超連結時，是否將其目標加入已檢視超連結清單。寫入 **bool**。 |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | 表示超連結的播放聲音。寫入 [IAudio](../iaudio/)。 |
| void [set_StopSoundOnClick](./set_stopsoundonclick/)(**bool**) override | 判斷在點擊超連結時是否應停止聲音。寫入 **bool**。 |
| void [set_TargetFrame](./set_targetframe/)([System::String](../../system/string/)) override | 傳回父 HTML 框架集中，父超連結目標所在的框架（若存在）。讀寫 [System::String](../../system/string/)。 |
| void [set_Tooltip](./set_tooltip/)([System::String](../../system/string/)) override | 傳回可能在使用者介面中顯示、與父超連結關聯的字串。寫入 [System::String](../../system/string/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱參考指標（而非共享）。允許在容器中切換指標至弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。可直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [PVIObject](../pviobject/)
* 類別 [IHyperlink](../ihyperlink/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)