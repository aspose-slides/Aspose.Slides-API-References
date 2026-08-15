---
title: ColorFormat
second_title: Aspose.Slides for C++ API 參考文件
description: 表示在簡報中使用的顏色。
type: docs
weight: 339
url: /zh-hant/aspose.slides/colorformat/
---
## ColorFormat 類別

表示在簡報中使用的顏色。

```cpp
class ColorFormat : public Aspose::Slides::PVIObject,
                    public Aspose::Slides::IColorFormat
```

## 方法

| Method | Description |
| --- | --- |
| void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\>) override | 從 \"color\" 複製顏色格式。 |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 檢查與指定物件的相等性。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| **uint8_t** [get_B](./get_b/)() override | 傳回顏色的藍色分量。所有顏色變換皆被忽略。讀取 **uint8_t**。 |
| [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() override | 傳回結果顏色（已套用所有顏色變換）。設定 RGB 顏色並清除所有顏色變換。讀取 [System::Drawing::Color](../../system.drawing/color/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) override | 傳回在指定索引套用於顏色的顏色變換操作。可讀寫 [Aspose::Slides::IColorOperation](../icoloroperation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() override | 傳回套用於顏色的顏色變換集合。唯讀 [IColorOperationCollection](../icoloroperationcollection/)。 |
| [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() override | 傳回顏色定義方法。讀取 [Slides::ColorType](../colortype/)。 |
| **float** [get_FloatB](./get_floatb/)() override | 傳回顏色的藍色分量。所有顏色變換皆被忽略。讀取 **float**。 |
| **float** [get_FloatG](./get_floatg/)() override | 傳回顏色的綠色分量。所有顏色變換皆被忽略。讀取 **float**。 |
| **float** [get_FloatR](./get_floatr/)() override | 傳回顏色的紅色分量。所有顏色變換皆被忽略。讀取 **float**。 |
| **uint8_t** [get_G](./get_g/)() override | 傳回顏色的綠色分量。所有顏色變換皆被忽略。 |
| **float** [get_Hue](./get_hue/)() override | 傳回 HSL 表示中的色相分量。所有顏色變換皆被忽略。讀取 **float**。 |
| **float** [get_Luminance](./get_luminance/)() override | 傳回 HSL 表示中的亮度分量。所有顏色變換皆被忽略。讀取 **float**。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | 傳回 Parent_Immediate 物件。唯讀 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 傳回父層 [IPresentationComponent](../ipresentationcomponent/)。唯讀 [IPresentationComponent](../ipresentationcomponent/)。 |
| [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() override | 傳回顏色預設值。讀取 [Slides::PresetColor](../presetcolor/)。 |
| **uint8_t** [get_R](./get_r/)() override | 傳回顏色的紅色分量。所有顏色變換皆被忽略。讀取 **uint8_t**。 |
| **float** [get_Saturation](./get_saturation/)() override | 傳回 HSL 表示中的飽和度分量。所有顏色變換皆被忽略。讀取 **float**。 |
| [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() override | 傳回由顏色配置識別的顏色。讀取 [Slides::SchemeColor](../schemecolor/)。 |
| [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() override | 傳回由系統顏色表識別的顏色。讀取 [Slides::SystemColor](../systemcolor/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 傳回雜湊碼。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。類似 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否代表 targetType 所描述的類型實例。類似 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 類似 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的複製。 |
| [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值類型物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定值。 |
| void [set_B](./set_b/)(**uint8_t**) override | 設定顏色的藍色分量。所有顏色變換皆被忽略。寫入 **uint8_t**。 |
| void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) override | 傳回結果顏色（已套用所有顏色變換）。設定 RGB 顏色並清除所有顏色變換。寫入 [System::Drawing::Color](../../system.drawing/color/)。 |
| void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) override | 設定在指定索引套用於顏色的顏色變換操作。可讀寫 [Aspose::Slides::IColorOperation](../icoloroperation/) |
| void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) override | 設定顏色定義方法。寫入 [Slides::ColorType](../colortype/)。 |
| void [set_FloatB](./set_floatb/)(**float**) override | 設定顏色的藍色分量。所有顏色變換皆被忽略。寫入 **float**。 |
| void [set_FloatG](./set_floatg/)(**float**) override | 設定顏色的綠色分量。所有顏色變換皆被忽略。寫入 **float**。 |
| void [set_FloatR](./set_floatr/)(**float**) override | 設定顏色的紅色分量。所有顏色變換皆被忽略。寫入 **float**。 |
| void [set_G](./set_g/)(**uint8_t**) override | 設定顏色的綠色分量。所有顏色變換皆被忽略。 |
| void [set_Hue](./set_hue/)(**float**) override | 設定 HSL 表示中的色相分量。所有顏色變換皆被忽略。寫入 **float**。 |
| void [set_Luminance](./set_luminance/)(**float**) override | 設定 HSL 表示中的亮度分量。所有顏色變換皆被忽略。寫入 **float**。 |
| void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) override | 設定顏色預設值。寫入 [Slides::PresetColor](../presetcolor/)。 |
| void [set_R](./set_r/)(**uint8_t**) override | 設定顏色的紅色分量。所有顏色變換皆被忽略。寫入 **uint8_t**。 |
| void [set_Saturation](./set_saturation/)(**float**) override | 設定 HSL 表示中的飽和度分量。所有顏色變換皆被忽略。寫入 **float**。 |
| void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) override | 設定由顏色配置識別的顏色。寫入 [Slides::SchemeColor](../schemecolor/)。 |
| void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) override | 設定由系統顏色表識別的顏色。寫入 [Slides::SystemColor](../systemcolor/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) override | 傳回代表目前顏色格式的 [System::String](../../system/string/)。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 類似 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [PVIObject](../pviobject/)
* 類別 [IColorFormat](../icolorformat/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)