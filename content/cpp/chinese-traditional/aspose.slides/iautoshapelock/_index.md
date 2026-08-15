---
title: IAutoShapeLock
second_title: Aspose.Slides for C++ API 參考
description: 決定在父 AutoshapeEx 上哪些操作被停用。
type: docs
weight: 1379
url: /zh-hant/aspose.slides/iautoshapelock/
---
## IAutoShapeLock 類


決定在父 AutoshapeEx 上哪些操作被禁用。

```cpp
class IAutoShapeLock : public virtual Aspose::Slides::IBaseShapeLock
```

## 方法

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 比較物件使用 C# [Object.Equals](../../system/object/equals/) 語意。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參照類型物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值類型物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 式的浮點比較，兩個 NaN 被視為相等，即使依 IEC 60559:1989 NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 式的浮點比較，兩個 NaN 被視為相等，即使依 IEC 60559:1989 NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | 判斷是否禁止變更調整值。讀取 **bool**。 |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | 判斷是否禁止變更箭頭形狀。讀取 **bool**。 |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | 判斷在調整大小時形狀是否必須保持長寬比。讀取 **bool**。 |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | 判斷是否禁止直接變更此形狀的輪廓。讀取 **bool**。 |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | 判斷是否禁止將此形狀加入群組。讀取 **bool**。 |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | 若所有鎖定旗標皆已停用則回傳 true。唯讀 **bool**。 |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | 判斷是否禁止移動此形狀。讀取 **bool**。 |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | 判斷是否禁止變更此形狀的旋轉角度。讀取 **bool**。 |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | 判斷是否禁止選取此形狀。讀取 **bool**。 |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | 判斷是否禁止變更形狀類型。讀取 **bool**。 |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | 判斷是否禁止調整此形狀大小。讀取 **bool**。 |
| virtual **bool** [get_TextLocked](./get_textlocked/)() | 判斷是否禁止編輯文字。讀取 **bool**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參照計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為目標類型的實例。相當於 C# 的 `is` 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參照比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參照比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參照比較值類型物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參照計數。 |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | 判斷是否禁止變更調整值。寫入 **bool**。 |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | 判斷是否禁止變更箭頭形狀。寫入 **bool**。 |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | 判斷在調整大小時形狀是否必須保持長寬比。寫入 **bool**。 |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | 判斷是否禁止直接變更此形狀的輪廓。寫入 **bool**。 |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | 判斷是否禁止將此形狀加入群組。寫入 **bool**。 |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | 判斷是否禁止移動此形狀。寫入 **bool**。 |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | 判斷是否禁止變更此形狀的旋轉角度。寫入 **bool**。 |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | 判斷是否禁止選取此形狀。寫入 **bool**。 |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | 判斷是否禁止變更形狀類型。寫入 **bool**。 |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | 判斷是否禁止調整此形狀大小。寫入 **bool**。 |
| virtual void [set_TextLocked](./set_textlocked/)(**bool**) | 判斷是否禁止編輯文字。寫入 **bool**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得目前的共享參照計數值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享參照計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 減少並回傳共享參照計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 運算式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱參照計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 減少弱參照計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |
## 參見

* 類 [IBaseShapeLock](../ibaseshapelock/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)