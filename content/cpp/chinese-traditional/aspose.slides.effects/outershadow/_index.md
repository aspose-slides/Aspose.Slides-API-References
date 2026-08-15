---
title: OuterShadow
second_title: Aspose.Slides for C++ API 參考
description: 表示一個外部陰影效果。
type: docs
weight: 1041
url: /zh-hant/aspose.slides.effects/outershadow/
---
## OuterShadow 類別


Represents an Outer Shadow effect.

```cpp
class OuterShadow : public Aspose::Slides::Effects::IOuterShadow,
                    public Aspose::Slides::Effects::IVisualEffect,
                    public Aspose::Slides::IPVIObject
```

## 方法

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Determines whether the specified [OuterShadow](./) is equal to the current [OuterShadow](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) radius, in points. 預設值 \u2013 0 pt. 讀取 **double**. |
| **float** [get_Direction](./get_direction/)() override | Direction of the shadow, in degrees. 預設值 \u2013 0 \u00B0 (從左至右). 讀取 **float**. |
| **double** [get_Distance](./get_distance/)() override | Distance of the shadow from the object, in points. 預設值 \u2013 0 pt. 讀取 **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Returns parent [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). 唯讀 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | 矩形對齊。預設值 \u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). 讀取 [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | 指示陰影是否隨形狀一起旋轉。預設值 \u2013 true. 讀取 **bool**. |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | 水平縮放係數，以原始大小的百分比表示。負縮放會導致翻轉。預設值 \u2013 100 %. 讀取 **double**. |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | 垂直縮放係數，以原始大小的百分比表示。負縮放會導致翻轉。預設值 \u2013 100 %. 讀取 **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() override | Color of the shadow. 預設值 \u2013 automatic black (theme-dependent). 唯讀 [IColorFormat](../../aspose.slides/icolorformat/). |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | Horizontal skew angle, in degrees. 預設值 \u2013 0 \u00B0. 讀取 **double**. |
| **double** [get_SkewVertical](./get_skewvertical/)() override | Vertical skew angle, in degrees. 預設值 \u2013 0 \u00B0. 讀取 **double**. |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | 版本。唯讀 **uint32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IOuterShadowEffectiveData](../ioutershadoweffectivedata/)\> [GetEffective](./geteffective/)() override | 取得套用繼承後的有效 Outer Shadow 效果資料。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 作為特定類型的雜湊函式。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。C# [System.Object.GetType()](../../system/object/gettype/) 呼叫的類比。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。C# ‘is’ 運算子之類比。 |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類比。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並啟用子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並啟用子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 針對字串和 nullptr 的 [Object::ReferenceEquals](../../system/object/referenceequals/) 專門化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 針對字串的 [Object::ReferenceEquals](../../system/object/referenceequals/) 專門化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參考計數。 |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) radius, in points. 預設值 \u2013 0 pt. 寫入 **double**. |
| void [set_Direction](./set_direction/)(**float**) override | Direction of the shadow, in degrees. 預設值 \u2013 0 \u00B0 (從左至右). 寫入 **float**. |
| void [set_Distance](./set_distance/)(**double**) override | Distance of the shadow from the object, in points. 預設值 \u2013 0 pt. 寫入 **double**. |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | 矩形對齊。預設值 \u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). 寫入 [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | 指示陰影是否隨形狀一起旋轉。預設值 \u2013 true. 寫入 **bool**. |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | 水平縮放係數，以原始大小的百分比表示。負縮放會導致翻轉。預設值 \u2013 100 %. 寫入 **double**. |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | 垂直縮放係數，以原始大小的百分比表示。負縮放會導致翻轉。預設值 \u2013 100 %. 寫入 **double**. |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | Horizontal skew angle, in degrees. 預設值 \u2013 0 \u00B0. 寫入 **double**. |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | Vertical skew angle, in degrees. 預設值 \u2013 0 \u00B0. 寫入 **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 減少並返回共享參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的類比。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 減少弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [IOuterShadow](../ioutershadow/)
* 類別 [IVisualEffect](../ivisualeffect/)
* 類別 [IPVIObject](../../aspose.slides/ipviobject/)
* 命名空間 [Aspose::Slides::Effects](../)
* 程式庫 [Aspose.Slides](../../)