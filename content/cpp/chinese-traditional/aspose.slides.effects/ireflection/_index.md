---
title: IReflection
second_title: Aspose.Slides for C++ API 參考
description: 代表反射效果。
type: docs
weight: 937
url: /zh-hant/aspose.slides.effects/ireflection/
---
## IReflection 類別

代表反射效果。

```cpp
class IReflection : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                    public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IReflectionEffectiveData>>
```

## 方法

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點數比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點數比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) 半徑。讀取 **double**。 |
| virtual **float** [get_Direction](./get_direction/)() | 反射方向。讀取 **float**。 |
| virtual **double** [get_Distance](./get_distance/)() | 反射距離。讀取 **double**。 |
| virtual **float** [get_EndPosAlpha](./get_endposalpha/)() | 指定結束 α 值（百分比）在 alpha 漸層坡道上的結束位置。讀取 **float**。 |
| virtual **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() | 結束反射不透明度（百分比）。讀取 **float**。 |
| virtual **float** [get_FadeDirection](./get_fadedirection/)() | 指定偏移反射的方向（角度）。讀取 **float**。 |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | 矩形對齊。讀取 [RectangleAlignment](../../aspose.slides/rectanglealignment/)。 |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | 指定當形狀旋轉時，反射是否隨之旋轉。讀取 **bool**。 |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | 指定水平縮放係數，負值會導致翻轉（百分比）。讀取 **double**。 |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | 指定垂直縮放係數，負值會導致翻轉（百分比）。讀取 **double**。 |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | 指定水平斜切角度。讀取 **double**。 |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | 指定垂直斜切角度。讀取 **double**。 |
| virtual **float** [get_StartPosAlpha](./get_startposalpha/)() | 指定起始 α 值（百分比）在 alpha 漸層坡道上的起始位置。讀取 **float**。 |
| virtual **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() | 起始反射不透明度（百分比）。讀取 **float**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | 取得套用繼承後的有效資料。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 等同於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。等同於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為目標型別所描述的實例。等同於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 等同於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的專門化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的專門化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參考計數。 |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) 半徑。寫入 **double**。 |
| virtual void [set_Direction](./set_direction/)(**float**) | 反射方向。寫入 **float**。 |
| virtual void [set_Distance](./set_distance/)(**double**) | 反射距離。寫入 **double**。 |
| virtual void [set_EndPosAlpha](./set_endposalpha/)(**float**) | 指定結束 α 值（百分比）在 alpha 漸層坡道上的結束位置。寫入 **float**。 |
| virtual void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) | 結束反射不透明度（百分比）。寫入 **float**。 |
| virtual void [set_FadeDirection](./set_fadedirection/)(**float**) | 指定偏移反射的方向（角度）。寫入 **float**。 |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | 矩形對齊。寫入 [RectangleAlignment](../../aspose.slides/rectanglealignment/)。 |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | 指定當形狀旋轉時，反射是否隨之旋轉。寫入 **bool**。 |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | 指定水平縮放係數，負值會導致翻轉（百分比）。寫入 **double**。 |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | 指定垂直縮放係數，負值會導致翻轉（百分比）。寫入 **double**。 |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | 指定水平斜切角度。寫入 **double**。 |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | 指定垂直斜切角度。寫入 **double**。 |
| virtual void [set_StartPosAlpha](./set_startposalpha/)(**float**) | 指定起始 α 值（百分比）在 alpha 漸層坡道上的起始位置。寫入 **float**。 |
| virtual void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) | 起始反射不透明度（百分比）。寫入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 等同於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另見

* 類別 [IImageTransformOperation](../iimagetransformoperation/)
* 類別 [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* 命名空間 [Aspose::Slides::Effects](../)
* 函式庫 [Aspose.Slides](../../)