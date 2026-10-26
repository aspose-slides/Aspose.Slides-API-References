---
title: Rotation3D
second_title: Aspose.Slides for C++ API 參考
description: 表示圖表的 3D 旋轉。
type: docs
weight: 1327
url: /zh-hant/aspose.slides.charts/rotation3d/
---
## Rotation3D 類別

表示圖表的 3D 旋轉。

```cpp
class Rotation3D : public Aspose::Slides::Charts::IRotation3D,
                   public Aspose::Slides::IDOMObject
```

## 方法

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 比較物件使用 C# [Object.Equals](../../system/object/equals/) 語意。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C#-style 浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C#-style 浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| **uint16_t** [get_DepthPercents](./get_depthpercents/)() override | 傳回 3D 圖表的深度，作為圖表寬度的百分比（介於 20% 到 2000% 之間）。讀取 **uint16_t**。 |
| **uint16_t** [get_HeightPercents](./get_heightpercents/)() override | 指定 3-D 圖表的高度，作為圖表寬度的百分比（介於 5% 到 500% 之間）。讀取 **uint16_t**。 |
| **uint8_t** [get_Perspective](./get_perspective/)() override | 傳回 3D 圖表的透視值（視野角度）（介於 0 到 240 之間）。若 RightAngleAxes 屬性值為 true，則會被忽略。讀取 **uint8_t**。 |
| **bool** [get_RightAngleAxes](./get_rightangleaxes/)() override | 決定圖表座標軸是否為直角，而非以透視方式繪製。換句話說，它決定座標軸的角度是否獨立於圖表的旋轉或傾斜。讀取 **bool**。 |
| **int8_t** [get_RotationX](./get_rotationx/)() override | 傳回繞 X 軸的旋轉角度，即 3D 圖表的 Y 方向（介於 -90 到 90 度）。此屬性對應 ECMA-376 的 21.2.2.157 rotX（X Rotation）項目，以及 PowerPoint 2007+ 的「Y Rotation」選項。讀取 **int8_t**。 |
| **uint16_t** [get_RotationY](./get_rotationy/)() override | 傳回繞 Y 軸的旋轉角度，即 3D 圖表的 X 方向（介於 0 到 360 度）。此屬性對應 ECMA-376 的 21.2.2.158 rotY（Y Rotation）項目，以及 PowerPoint 2007+ 的「X Rotation」選項。讀取 **uint16_t**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類比。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。C# [System.Object.GetType()](../../system/object/gettype/) 呼叫的類比。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。C# 'is' 運算子的類比。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類比。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，適用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，適用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) override | 設定 3D 圖表的深度，作為圖表寬度的百分比（介於 20% 到 2000% 之間）。寫入 **uint16_t**。 |
| void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) override | 指定 3-D 圖表的高度，作為圖表寬度的百分比（介於 5% 到 500% 之間）。寫入 **uint16_t**。 |
| void [set_Perspective](./set_perspective/)(**uint8_t**) override | 設定 3D 圖表的透視值（視野角度）（介於 0 到 240 之間）。若 RightAngleAxes 屬性值為 true，則會被忽略。寫入 **uint8_t**。 |
| void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) override | 決定圖表座標軸是否為直角，而非以透視方式繪製。換句話說，它決定座標軸的角度是否獨立於圖表的旋轉或傾斜。寫入 **bool**。 |
| void [set_RotationX](./set_rotationx/)(**int8_t**) override | 設定繞 X 軸的旋轉角度，即 3D 圖表的 Y 方向（介於 -90 到 90 度）。此屬性對應 ECMA-376 的 21.2.2.157 rotX（X Rotation）項目，以及 PowerPoint 2007+ 的「Y Rotation」選項。寫入 **int8_t**。 |
| void [set_RotationY](./set_rotationy/)(**uint16_t**) override | 設定繞 Y 軸的旋轉角度，即 3D 圖表的 X 方向（介於 0 到 360 度）。此屬性對應 ECMA-376 的 21.2.2.158 rotY（Y Rotation）項目，以及 PowerPoint 2007+ 的「X Rotation」選項。寫入 **uint16_t**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中切換指標為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 將共享參考計數遞減並傳回。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的類比。啟用自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [IRotation3D](../irotation3d/)
* 類別 [IDOMObject](../../aspose.slides/idomobject/)
* 名稱空間 [Aspose::Slides::Charts](../)
* 函式庫 [Aspose.Slides](../../)