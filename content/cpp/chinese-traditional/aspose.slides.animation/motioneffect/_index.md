---
title: MotionEffect
second_title: Aspose.Slides for C++ API 參考文件
description: 表示效果的運動效果行為。
type: docs
weight: 469
url: /zh-hant/aspose.slides.animation/motioneffect/
---
## MotionEffect 類別


Represent motion effect behavior of effect.

```cpp
class MotionEffect : public Aspose::Slides::Animation::Behavior,
                     public Aspose::Slides::Animation::IMotionEffect
```

## 方法

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../behavior/get_accumulate/)() override | 表示動畫行為是否累積。讀取 [NullableBool](../../aspose.slides/nullablebool/)。 |
| [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../behavior/get_additive/)() override | 表示當前動畫行為是否與其他正在執行的動畫合併。讀取 [BehaviorAdditiveType](../behavioradditivetype/)。 |
| **float** [get_Angle](./get_angle/)() override | 描述運動路徑的相對角度。讀取 **float**。 |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_By](./get_by/)() override | 描述動畫的相對位移值（以百分比表示）。讀取 [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_From](./get_from/)() override | 指定動畫起始的 x/y 座標（以百分比表示）。讀取 [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| [MotionOriginType](../motionorigintype/) [get_Origin](./get_origin/)() override | 指定運動路徑的原點相對於什麼，例如投影片的版面配置或父項目。讀取 [MotionOriginType](../motionorigintype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\> [get_Path](./get_path/)() override | 指定路徑原語及其後的座標，用於動畫運動。讀取 [IMotionPath](../imotionpath/)。 |
| [MotionPathEditMode](../motionpatheditmode/) [get_PathEditMode](./get_patheditmode/)() override | 指定形狀移動時運動路徑的移動方式。讀取 [MotionPathEditMode](../motionpatheditmode/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../behavior/get_properties/)() override | 表示行為的屬性。唯讀 [IBehaviorPropertyCollection](../ibehaviorpropertycollection/)。 |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_RotationCenter](./get_rotationcenter/)() override | 描述用於將運動路徑繞 X 角度旋轉的中心。讀取 [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../behavior/get_timing/)() override | 表示效果行為的時間屬性。讀取 [ITiming](../itiming/)。 |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_To](./get_to/)() override | 指定動畫運動效果的目標位置（以百分比表示）。讀取 [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊功能。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 描述的類型實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
|  [MotionEffect](./motioneffect/)() |  |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構函式。實際上不會複製任何內容，只是初始化新物件並允許為子類別執行拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許為子類別執行拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的數值。 |
| void [set_Accumulate](../behavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) override | 表示動畫行為是否累積。寫入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| void [set_Additive](../behavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) override | 表示當前動畫行為是否與其他正在執行的動畫合併。寫入 [BehaviorAdditiveType](../behavioradditivetype/)。 |
| void [set_Angle](./set_angle/)(**float**) override | 描述運動路徑的相對角度。寫入 **float**。 |
| void [set_By](./set_by/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | 描述動畫的相對位移值（以百分比表示）。寫入 [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| void [set_From](./set_from/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | 指定動畫起始的 x/y 座標（以百分比表示）。寫入 [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| void [set_Origin](./set_origin/)([MotionOriginType](../motionorigintype/)) override | 指定運動路徑的原點相對於什麼，例如投影片版面配置或父項目。寫入 [MotionOriginType](../motionorigintype/)。 |
| void [set_Path](./set_path/)([System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\>) override | 指定路徑原語及其後的座標，用於動畫運動。寫入 [IMotionPath](../imotionpath/)。 |
| void [set_PathEditMode](./set_patheditmode/)([MotionPathEditMode](../motionpatheditmode/)) override | 指定形狀移動時運動路徑的移動方式。寫入 [MotionPathEditMode](../motionpatheditmode/)。 |
| void [set_RotationCenter](./set_rotationcenter/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | 描述用於將運動路徑繞 X 角度旋轉的中心。寫入 [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| void [set_Timing](../behavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | 表示效果行為的時間屬性。寫入 [ITiming](../itiming/)。 |
| void [set_To](./set_to/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | 指定動畫運動效果的目標位置（以百分比表示）。寫入 [System::Drawing::PointF](../../system.drawing/pointf/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |
## 另請參閱

* 類別 [Behavior](../behavior/)
* 類別 [IMotionEffect](../imotioneffect/)
* 命名空間 [Aspose::Slides::Animation](../)
* 函式庫 [Aspose.Slides](../../)