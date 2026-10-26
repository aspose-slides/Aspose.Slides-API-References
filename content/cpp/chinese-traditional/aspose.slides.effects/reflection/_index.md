---
title: Reflection
second_title: Aspose.Slides for C++ API 參考
description: 表示一個 Reflection 效果。
type: docs
weight: 1067
url: /zh-hant/aspose.slides.effects/reflection/
---
## 反射類別

表示一個 [Reflection](./) 效果。

```cpp
class Reflection : public Aspose::Slides::Effects::IReflection,
                   public Aspose::Slides::Effects::IVisualEffect,
                   public Aspose::Slides::IPVIObject
```

## 方法

| 方法 | 描述 |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 判斷指定的 [Reflection](./) 是否等於當前的 [Reflection](./)。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN）。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN）。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) 半徑。讀取 **double**。 |
| **float** [get_Direction](./get_direction/)() override | 反射方向。讀取 **float**。 |
| **double** [get_Distance](./get_distance/)() override | 反射距離。讀取 **double**。 |
| **float** [get_EndPosAlpha](./get_endposalpha/)() override | 指定結束位置（沿 alpha 漸層坡度）之結束 alpha 值（百分比）。讀取 **float**。 |
| **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() override | 結束反射不透明度。（百分比）。讀取 **float**。 |
| **float** [get_FadeDirection](./get_fadedirection/)() override | 指定偏移反射的方向。（角度）。讀取 **float**。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | 傳回父層 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)。唯讀 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)。 |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | 矩形對齊。讀取 [RectangleAlignment](../../aspose.slides/rectanglealignment/)。 |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | 指定當形狀旋轉時，反射是否應隨之旋轉。讀取 **bool**。 |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | 指定水平縮放係數，負值會導致翻轉。（百分比）讀取 **double**。 |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | 指定垂直縮放係數，負值會導致翻轉。（百分比）讀取 **double**。 |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | 指定水平斜角。讀取 **double**。 |
| **double** [get_SkewVertical](./get_skewvertical/)() override | 指定垂直斜角。讀取 **double**。 |
| **float** [get_StartPosAlpha](./get_startposalpha/)() override | 指定起始位置（沿 alpha 漸層坡度）之起始 alpha 值（百分比）。讀取 **float**。 |
| **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() override | 起始反射不透明度。（百分比）。讀取 **float**。 |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | 版本。唯讀 **uint32_t**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IReflectionEffectiveData](../ireflectioneffectivedata/)\> [GetEffective](./geteffective/)() override | 取得套用繼承後的有效 [Reflection](./) 效果資料。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 作為特定型別的雜湊函式。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# 的 [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所述型別的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守衛物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# 的 [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
| [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構函式。實際上不會拷貝任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會拷貝任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 依參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 依參考比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) 半徑。寫入 **double**。 |
| void [set_Direction](./set_direction/)(**float**) override | 反射方向。寫入 **float**。 |
| void [set_Distance](./set_distance/)(**double**) override | 反射距離。寫入 **double**。 |
| void [set_EndPosAlpha](./set_endposalpha/)(**float**) override | 指定結束位置（沿 alpha 漸層坡度）之結束 alpha 值（百分比）。寫入 **float**。 |
| void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) override | 結束反射不透明度。（百分比）。寫入 **float**。 |
| void [set_FadeDirection](./set_fadedirection/)(**float**) override | 指定偏移反射的方向。（角度）。寫入 **float**。 |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | 矩形對齊。寫入 [RectangleAlignment](../../aspose.slides/rectanglealignment/)。 |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | 指定當形狀旋轉時，反射是否應隨之旋轉。寫入 **bool**。 |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | 指定水平縮放係數，負值會導致翻轉。（百分比）寫入 **double**。 |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | 指定垂直縮放係數，負值會導致翻轉。（百分比）寫入 **double**。 |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | 指定水平斜角。寫入 **double**。 |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | 指定垂直斜角。寫入 **double**。 |
| void [set_StartPosAlpha](./set_startposalpha/)(**float**) override | 指定起始位置（沿 alpha 漸層坡度）之起始 alpha 值（百分比）。寫入 **float**。 |
| void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) override | 起始反射不透明度。（百分比）。寫入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中切換指標為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# 的 [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守衛物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [IReflection](../ireflection/)
* 類別 [IVisualEffect](../ivisualeffect/)
* 類別 [IPVIObject](../../aspose.slides/ipviobject/)
* 命名空間 [Aspose::Slides::Effects](../)
* 函式庫 [Aspose.Slides](../../)