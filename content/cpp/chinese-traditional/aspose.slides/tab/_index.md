---
title: Tab
second_title: Aspose.Slides for C++ API 參考
description: 代表文字的製表符。
type: docs
weight: 5370
url: /zh-hant/aspose.slides/tab/
---
## Tab 類別

Represents a tabulation for a text.

```cpp
class Tab : public Aspose::Slides::PVIObject,
            public Aspose::Slides::ITab
```

## 方法

| Method | Description |
| --- | --- |
| **int32_t** [CompareTo](./compareto/)([System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\>) override | 比較目前的實例與同類型的另一個物件。 |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 與指定的物件比較。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參照型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [TabAlignment](../tabalignment/) [get_Alignment](./get_alignment/)() override | 傳回 tab 的對齊樣式。請閱讀 [TabAlignment](../tabalignment/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | 傳回 Parent_Immediate 物件。唯讀 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 傳回父級 [IPresentationComponent](../ipresentationcomponent/)。唯讀 [IPresentationComponent](../ipresentationcomponent/)。 |
| **double** [get_Position](./get_position/)() override | 傳回 tab 的位置。指派此屬性可能會變更集合中 tab 的索引，並使列舉器失效。讀取 **double**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關的參照計數器資料結構。 |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | 傳回雜湊碼。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否代表 targetType 所描述的類型實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參照方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參照方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參照方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，針對字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，針對字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參照計數。 |
| void [set_Alignment](./set_alignment/)([TabAlignment](../tabalignment/)) override | 設定 tab 的對齊樣式。寫入 [TabAlignment](../tabalignment/)。 |
| void [set_Position](./set_position/)(**double**) override | 設定 tab 的位置。指派此屬性可能會變更集合中 tab 的索引，並使列舉器失效。寫入 **double**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中切換指標為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參照計數器的當前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
|  [Tab](./tab/)(**double**, [TabAlignment](../tabalignment/)) | 建立新的 [Tab](./) |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。允許將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解除鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [PVIObject](../pviobject/)
* 類別 [ITab](../itab/)
* 名稱空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)