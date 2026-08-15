---
title: IGroupShapeLock
second_title: Aspose.Slides C++ API 參考
description: 判斷在父級 GroupShape 上哪些操作被停用。
type: docs
weight: 2497
url: /zh-hant/aspose.slides/igroupshapelock/
---
## IGroupShapeLock 類別


決定在父級 [GroupShape](../groupshape/) 上哪些操作被停用。

```cpp
class IGroupShapeLock : public virtual Aspose::Slides::IBaseShapeLock
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | 決定形狀在調整大小時是否必須保留長寬比。讀取 **bool**。 |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | 決定是否禁止將此形狀加入群組。讀取 **bool**。 |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | 如果所有鎖定旗標已停用，則回傳 true。唯讀 **bool**。 |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | 決定是否禁止移動此形狀。讀取 **bool**。 |
| virtual **bool** [get_RotationLocked](./get_rotationlocked/)() | 決定是否禁止變更此形狀的旋轉角度。讀取 **bool**。 |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | 決定是否禁止選取此形狀。讀取 **bool**。 |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | 決定是否禁止調整此形狀的大小。讀取 **bool**。 |
| virtual **bool** [get_UngroupingLocked](./get_ungroupinglocked/)() | 決定是否禁止分割此群組形狀。讀取 **bool**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 將值型別物件與 nullptr 以參考方式比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 針對字串與 nullptr 情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 針對字串情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | 決定形狀在調整大小時是否必須保留長寬比。寫入 **bool**。 |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | 決定是否禁止將此形狀加入群組。寫入 **bool**。 |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | 決定是否禁止移動此形狀。寫入 **bool**。 |
| virtual void [set_RotationLocked](./set_rotationlocked/)(**bool**) | 決定是否禁止變更此形狀的旋轉角度。寫入 **bool**。 |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | 決定是否禁止選取此形狀。寫入 **bool**。 |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | 決定是否禁止調整此形狀的大小。寫入 **bool**。 |
| virtual void [set_UngroupingLocked](./set_ungroupinglocked/)(**bool**) | 決定是否禁止分割此群組形狀。寫入 **bool**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享指標）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 構造。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [IBaseShapeLock](../ibaseshapelock/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)