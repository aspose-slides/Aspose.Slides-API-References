---
title: ConnectorLock
second_title: Aspose.Slides C++ API 參考
description: 決定在父 Connector 上哪些操作被禁用。
type: docs
weight: 495
url: /zh-hant/aspose.slides/connectorlock/
---
## ConnectorLock 類別


決定在父項 [Connector](../connector/) 上哪些操作被禁用。

```cpp
class ConnectorLock : public Aspose::Slides::BaseShapeLock,
                      public Aspose::Slides::IConnectorLock
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 比較 C# 風格的參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 比較 C# 風格的值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使依據 IEC 60559:1989 NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使依據 IEC 60559:1989 NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | 決定是否禁止變更調整值。讀取 **bool**。 |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | 決定是否禁止變更箭頭形狀。讀取 **bool**。 |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | 決定形狀在調整大小時是否必須保持長寬比。讀取 **bool**。 |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | 決定是否禁止直接變更此形狀的輪廓。讀取 **bool**。 |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | 決定是否禁止將此形狀加入群組。讀取 **bool**。 |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | 若所有鎖定旗標皆已停用則回傳 true。唯讀 **bool**。 |
| **bool** [get_PositionMove](./get_positionmove/)() override | 決定是否禁止移動此形狀。讀取 **bool**。 |
| **bool** [get_RotateLocked](./get_rotatelocked/)() override | 決定是否禁止變更此形狀的旋轉角度。讀取 **bool**。 |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | 決定是否禁止選取此形狀。讀取 **bool**。 |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | 決定是否禁止變更形狀類型。讀取 **bool**。 |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | 決定是否禁止調整此形狀大小。讀取 **bool**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類似功能。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。C# [System.Object.GetType()](../../system/object/gettype/) 呼叫的類似功能。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為目標類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類似功能。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況下的特殊化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況下的特殊化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 以指定值減少共享參考計數。 |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | 決定是否禁止變更調整值。寫入 **bool**。 |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | 決定是否禁止變更箭頭形狀。寫入 **bool**。 |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | 決定形狀在調整大小時是否必須保持長寬比。寫入 **bool**。 |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | 決定是否禁止直接變更此形狀的輪廓。寫入 **bool**。 |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | 決定是否禁止將此形狀加入群組。寫入 **bool**。 |
| void [set_PositionMove](./set_positionmove/)(**bool**) override | 決定是否禁止移動此形狀。寫入 **bool**。 |
| void [set_RotateLocked](./set_rotatelocked/)(**bool**) override | 決定是否禁止變更此形狀的旋轉角度。寫入 **bool**。 |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | 決定是否禁止選取此形狀。寫入 **bool**。 |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | 決定是否禁止變更形狀類型。寫入 **bool**。 |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | 決定是否禁止調整此形狀大小。寫入 **bool**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得目前的共享參考計數值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享參考計數。請勿直接呼叫；請使用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 減少並回傳共享參考計數。請勿直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的類似功能。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱參考計數。請勿直接呼叫；請使用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 減少弱參考計數。請勿直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* Class [BaseShapeLock](../baseshapelock/)
* Class [IConnectorLock](../iconnectorlock/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)