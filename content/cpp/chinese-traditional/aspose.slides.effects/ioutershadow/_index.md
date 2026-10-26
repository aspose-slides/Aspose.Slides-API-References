---
title: IOuterShadow
second_title: Aspose.Slides for C++ API 參考文件
description: 表示外部陰影效果。
type: docs
weight: 885
url: /zh-hant/aspose.slides.effects/ioutershadow/
---
## IOuterShadow 類別

Represents an Outer Shadow effect.

```cpp
class IOuterShadow : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                     public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IOuterShadowEffectiveData>>
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考類型物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值類型物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）都不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）都不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) 半徑，以點為單位。預設值 \\u2013 0 pt。讀取 **double**。 |
| virtual **float** [get_Direction](./get_direction/)() | 陰影方向，以度為單位。預設值 \\u2013 0 \\u00B0（從左到右）。讀取 **float**。 |
| virtual **double** [get_Distance](./get_distance/)() | 陰影與物件的距離，以點為單位。預設值 \\u2013 0 pt。讀取 **double**。 |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | 矩形對齊。預設值 \\u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/)。讀取 [RectangleAlignment](../../aspose.slides/rectanglealignment/)。 |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | 指示陰影是否隨形狀一起旋轉。預設值 \\u2013 true。讀取 **bool**。 |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | 水平縮放係數，以原始大小的百分比表示。負的縮放會導致翻轉。預設值 \\u2013 100 %。讀取 **double**。 |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | 垂直縮放係數，以原始大小的百分比表示。負的縮放會導致翻轉。預設值 \\u2013 100 %。讀取 **double**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() | 陰影顏色。預設值 \\u2013 自動黑色（依主題）。唯讀 [IColorFormat](../../aspose.slides/icolorformat/)。 |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | 水平斜切角度，以度為單位。預設值 \\u2013 0 \\u00B0。讀取 **double**。 |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | 垂直斜切角度，以度為單位。預設值 \\u2013 0 \\u00B0。讀取 **double**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數器資料結構。 |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | 取得套用繼承後的有效資料。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值類型物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，針對字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，針對字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) 半徑，以點為單位。預設值 \\u2013 0 pt。寫入 **double**。 |
| virtual void [set_Direction](./set_direction/)(**float**) | 陰影方向，以度為單位。預設值 \\u2013 0 \\u00B0（從左到右）。寫入 **float**。 |
| virtual void [set_Distance](./set_distance/)(**double**) | 陰影與物件的距離，以點為單位。預設值 \\u2013 0 pt。寫入 **double**。 |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | 矩形對齊。預設值 \\u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/)。寫入 [RectangleAlignment](../../aspose.slides/rectanglealignment/)。 |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | 指示陰影是否隨形狀一起旋轉。預設值 \\u2013 true。寫入 **bool**。 |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | 水平縮放係數，以原始大小的百分比表示。負的縮放會導致翻轉。預設值 \\u2013 100 %。寫入 **double**。 |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | 垂直縮放係數，以原始大小的百分比表示。負的縮放會導致翻轉。預設值 \\u2013 100 %。寫入 **double**。 |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | 水平斜切角度，以度為單位。預設值 \\u2013 0 \\u00B0。寫入 **double**。 |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | 垂直斜切角度，以度為單位。預設值 \\u2013 0 \\u00B0。寫入 **double**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [IImageTransformOperation](../iimagetransformoperation/)
* 類別 [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* 命名空間 [Aspose::Slides::Effects](../)
* 函式庫 [Aspose.Slides](../../)