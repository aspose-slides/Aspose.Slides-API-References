---
title: TextFrameFormat
second_title: Aspose.Slides for C++ API 參考
description: 包含 TextFrame 的 formatTextFrameFormatting 屬性。
type: docs
weight: 5461
url: /zh-hant/aspose.slides/textframeformat/
---
## TextFrameFormat 類別


包含 [TextFrame](../textframe/) 的 formatTextFrameFormatting 屬性。

```cpp
class TextFrameFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::ITextFrameFormat,
                        public Aspose::Slides::Charts::IChartTextBlockFormat
```

## 方法

| 方法 | 說明 |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 與指定的物件比較。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() override | 返回 [TextFrame](../textframe/) 中的垂直錨點文字。閱讀 [TextAnchorType](../textanchortype/)。 |
| [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() override | 返回文字的自動調整模式。閱讀 [TextAutofitType](../textautofittype/)。 |
| [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() override | 如果 [NullableBool::True](../nullablebool/)，則文字應在框內水平置中。閱讀 [NullableBool](../nullablebool/)。 |
| **int32_t** [get_ColumnCount](./get_columncount/)() override | 返回文字區域中的列數。此值必須為正數。否則，該值將設定為 0。值 0 表示未定義的值。閱讀 **int32_t**。 |
| **double** [get_ColumnSpacing](./get_columnspacing/)() override | 返回文字區域中列與列之間的間距（以點為單位）。僅在存在多於 1 列時適用。此值必須為正數。否則，該值將設定為 0。閱讀 **double**。 |
| **bool** [get_KeepTextFlat](./get_keeptextflat/)() override | 取得即使套用 3-D 旋轉效果仍保持文字平面的設定。閱讀 **bool**。 |
| **double** [get_MarginBottom](./get_marginbottom/)() override | 返回 [TextFrame](../textframe/) 的下邊距（點）。閱讀 **double**。 |
| **double** [get_MarginLeft](./get_marginleft/)() override | 返回 [TextFrame](../textframe/) 的左邊距（點）。閱讀 **double**。 |
| **double** [get_MarginRight](./get_marginright/)() override | 返回 [TextFrame](../textframe/) 的右邊距（點）。閱讀 **double**。 |
| **double** [get_MarginTop](./get_margintop/)() override | 返回 [TextFrame](../textframe/) 的上邊距（點）。閱讀 **double**。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | 返回 Parent_Immediate 物件。唯讀 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 返回父層 [IPresentationComponent](../ipresentationcomponent/)。唯讀 [IPresentationComponent](../ipresentationcomponent/)。 |
| **float** [get_RotationAngle](./get_rotationangle/)() override | 指定套用於邊框內文字的自訂旋轉。如果未指定，則使用伴隨圖形的旋轉。如果已指定，則此旋轉獨立於圖形。也就是說，圖形可以有旋轉，同時文字本身也可以有旋轉。最終的視覺文字旋轉值由此屬性與屬性 TextVerticalType 中的預定義垂直類型彙總而成。閱讀 **float**。 |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | 確定文字方向。最終的視覺文字旋轉值由此屬性與屬性 RotationAngle 中的自訂角度彙總而成。閱讀 [Slides::TextVerticalType](../textverticaltype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | 返回代表文字 3D 效果屬性的 [ThreeDFormat](../threedformat/) 物件。唯讀 [IThreeDFormat](../ithreedformat/)。 |
| [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() override | 取得文字換行形狀。閱讀 [TextShapeType](../textshapetype/)。 |
| [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() override | 如果文字在 [TextFrame](../textframe/) 的邊距換行則為 **True**。閱讀 [NullableBool](../nullablebool/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() override | 取得套用繼承後的有效文字框格式資料。 |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | 返回雜湊碼。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
| [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參照方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參照方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參照方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況下的特殊化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況下的特殊化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的數值。 |
| void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) override | 設定 [TextFrame](../textframe/) 中的垂直錨點文字。寫入 [TextAnchorType](../textanchortype/)。 |
| void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) override | 設定文字的自動調整模式。寫入 [TextAutofitType](../textautofittype/)。 |
| void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) override | 如果 [NullableBool::True](../nullablebool/)，則文字應在框內水平置中。寫入 [NullableBool](../nullablebool/)。 |
| void [set_ColumnCount](./set_columncount/)(**int32_t**) override | 設定文字區域的列數。此值必須為正數。否則，該值將設定為 0。值 0 表示未定義的值。寫入 **int32_t**。 |
| void [set_ColumnSpacing](./set_columnspacing/)(**double**) override | 設定文字區域中列與列之間的間距（以點為單位）。僅在存在多於 1 列時適用。此值必須為正數。否則，該值將設定為 0。寫入 **double**。 |
| void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) override | 設定即使套用 3-D 旋轉效果仍保持文字平面的設定。寫入 **bool**。 |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | 設定 [TextFrame](../textframe/) 的下邊距（點）。寫入 **double**。 |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | 設定 [TextFrame](../textframe/) 的左邊距（點）。寫入 **double**。 |
| void [set_MarginRight](./set_marginright/)(**double**) override | 設定 [TextFrame](../textframe/) 的右邊距（點）。寫入 **double**。 |
| void [set_MarginTop](./set_margintop/)(**double**) override | 設定 [TextFrame](../textframe/) 的上邊距（點）。寫入 **double**。 |
| void [set_RotationAngle](./set_rotationangle/)(**float**) override | 指定套用於邊框內文字的自訂旋轉。如果未指定，則使用伴隨圖形的旋轉。如果已指定，則此旋轉獨立於圖形。也就是說，圖形可以有旋轉，同時文字本身也可以有旋轉。最終的視覺文字旋轉值由此屬性與屬性 TextVerticalType 中的預定義垂直類型彙總而成。寫入 **float**。 |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | 確定文字方向。最終的視覺文字旋轉值由此屬性與屬性 RotationAngle 中的自訂角度彙總而成。寫入 [Slides::TextVerticalType](../textverticaltype/)。 |
| void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) override | 設定文字換行形狀。寫入 [TextShapeType](../textshapetype/)。 |
| void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) override | 如果文字在 [TextFrame](../textframe/) 的邊距換行則為 **True**。寫入 [NullableBool](../nullablebool/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| [TextFrameFormat](./textframeformat/)() | 初始化 [TextFrameFormat](./) 類別的新實例。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [PVIObject](../pviobject/)
* 類別 [ITextFrameFormat](../itextframeformat/)
* 類別 [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)