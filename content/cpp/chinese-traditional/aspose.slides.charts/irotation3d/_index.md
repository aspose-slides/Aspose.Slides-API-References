---
title: IRotation3D
second_title: Aspose.Slides for C++ API 參考
description: 表示圖表的 3D 旋轉。
type: docs
weight: 1171
url: /zh-hant/aspose.slides.charts/irotation3d/
---
## IRotation3D 類別

表示圖表的 3D 旋轉。

```cpp
class IRotation3D : public virtual System::Object
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual **uint16_t** [get_DepthPercents](./get_depthpercents/)() | 傳回 3D 圖表的深度，以圖表寬度的百分比表示（介於 20% 到 2000% 之間）。讀取 **uint16_t**。 |
| virtual **uint16_t** [get_HeightPercents](./get_heightpercents/)() | 指定 3-D 圖表的高度，以圖表寬度的百分比表示（介於 5% 到 500% 之間）。讀取 **uint16_t**。 |
| virtual **uint8_t** [get_Perspective](./get_perspective/)() | 傳回 3D 圖表的透視值（視場角度），範圍在 0 到 100 之間。若 RightAngleAxes 屬性值為 true，則忽略此設定。讀取 **uint8_t**。 |
| virtual **bool** [get_RightAngleAxes](./get_rightangleaxes/)() | 判斷圖表坐標軸是否為直角，而非以透視方式繪製。換言之，決定坐標軸的角度是否獨立於圖表的旋轉或傾斜。讀取 **bool**。 |
| virtual **int8_t** [get_RotationX](./get_rotationx/)() | 傳回繞 X 軸（即 3D 圖表的 Y 方向）的旋轉角度（介於 -90 至 90 度）。此屬性與 ECMA-376 中的 21.2.2.157 rotX（X Rotation）項目以及 PowerPoint 2007+ 中的 \"Y Rotation\" 選項相符。讀取 **int8_t**。 |
| virtual **uint16_t** [get_RotationY](./get_rotationy/)() | 傳回繞 Y 軸（即 3D 圖表的 X 方向）的旋轉角度（介於 0 至 360 度）。此屬性與 ECMA-376 中的 21.2.2.158 rotY（Y Rotation）項目以及 PowerPoint 2007+ 中的 \"X Rotation\" 選項相符。讀取 **uint16_t**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。提供自訂物件的雜湊功能。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定功能。直接呼叫或使用 [LockContext](../../system/lockcontext/) 看守物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。提供自訂型別的克隆功能。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件，並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件，並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 進行比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，用於 string 與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) | 設定 3D 圖表的深度，以圖表寬度的百分比表示（介於 20% 到 2000% 之間）。寫入 **uint16_t**。 |
| virtual void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) | 指定 3-D 圖表的高度，以圖表寬度的百分比表示（介於 5% 到 500% 之間）。寫入 **uint16_t**。 |
| virtual void [set_Perspective](./set_perspective/)(**uint8_t**) | 設定 3D 圖表的透視值（視場角度），範圍在 0 到 100 之間。若 RightAngleAxes 屬性值為 true，則忽略此設定。寫入 **uint8_t**。 |
| virtual void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) | 判斷圖表坐標軸是否為直角，而非以透視方式繪製。換言之，決定坐標軸的角度是否獨立於圖表的旋轉或傾斜。寫入 **bool**。 |
| virtual void [set_RotationX](./set_rotationx/)(**int8_t**) | 設定繞 X 軸（即 3D 圖表的 Y 方向）的旋轉角度（介於 -90 至 90 度）。此屬性與 ECMA-376 中的 21.2.2.157 rotX（X Rotation）項目以及 PowerPoint 2007+ 中的 \"Y Rotation\" 選項相符。寫入 **int8_t**。 |
| virtual void [set_RotationY](./set_rotationy/)(**uint16_t**) | 設定繞 Y 軸（即 3D 圖表的 X 方向）的旋轉角度（介於 0 至 360 度）。此屬性與 ECMA-376 中的 21.2.2.158 rotY（Y Rotation）項目以及 PowerPoint 2007+ 中的 \"X Rotation\" 選項相符。寫入 **uint16_t**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。提供將自訂物件轉換為字串的功能。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖功能。直接呼叫或使用 [LockContext](../../system/lockcontext/) 看守物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [Object](../../system/object/)
* 命名空間 [Aspose::Slides::Charts](../)
* 函式庫 [Aspose.Slides](../../)