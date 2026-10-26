---
title: ITextFrameFormat
second_title: Aspose.Slides for C++ API 參考文件
description: 包含 TextFrame 的格式屬性。
type: docs
weight: 4083
url: /zh-hant/aspose.slides/itextframeformat/
---
## ITextFrameFormat 類別

包含 [TextFrame](../textframe/) 的格式屬性。

```cpp
class ITextFrameFormat : public virtual System::Object
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 在 C# 風格中比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 在 C# 風格中比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C#-style 浮點比較，其中兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C#-style 浮點比較，其中兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | 傳回 [TextFrame](../textframe/) 中的垂直錨點文字。讀取 [TextAnchorType](../textanchortype/)。 |
| virtual [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() | 傳回文字的自動調整模式。讀取 [TextAutofitType](../textautofittype/)。 |
| virtual [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() | 如果 [NullableBool::True](../nullablebool/)，則文字應水平置中於方框內。讀取 [NullableBool](../nullablebool/)。 |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | 傳回文字區域中的列數。此數值必須是正數。否則，該數值會被設定為零。值 0 表示未定義的值。讀取 **int32_t**。 |
| virtual **double** [get_ColumnSpacing](./get_columnspacing/)() | 傳回文字區域中列與列之間的間距（以點為單位）。僅在存在超過一列時適用。此數值必須是正數。否則，該數值會被設定為零。讀取 **double**。 |
| virtual **bool** [get_KeepTextFlat](./get_keeptextflat/)() | 傳回或設定將文字完全排除於 3D 場景之外。讀取 **bool**。 |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | 傳回 [TextFrame](../textframe/) 中的底部邊距（點）。讀取 **double**。 |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | 傳回 [TextFrame](../textframe/) 中的左側邊距（點）。讀取 **double**。 |
| virtual **double** [get_MarginRight](./get_marginright/)() | 傳回 [TextFrame](../textframe/) 中的右側邊距（點）。讀取 **double**。 |
| virtual **double** [get_MarginTop](./get_margintop/)() | 傳回 [TextFrame](../textframe/) 中的頂部邊距（點）。讀取 **double**。 |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | 指定套用於文字於邊界框內的自訂旋轉。如果未指定，則使用伴隨圖形的旋轉。如果已指定，則此旋轉獨立於圖形。也就是說，圖形可以有旋轉，同時文字本身也可以有旋轉。此屬性與屬性 TextVerticalType 中的預定義垂直類型共同匯總得到的視覺文字旋轉值。讀取 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TextStyle](./get_textstyle/)() | 傳回文字的樣式。唯讀 [ITextStyle](../itextstyle/)。 |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | 決定文字方向。此屬性與屬性 RotationAngle 中的自訂角度共同匯總得到的視覺文字旋轉值。讀取 [Slides::TextVerticalType](../textverticaltype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | 傳回表示文字 3D 效果屬性的 [ThreeDFormat](../threedformat/) 物件。唯讀 [IThreeDFormat](../ithreedformat/)。 |
| virtual [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() | 取得文字換行形狀。讀取 [TextShapeType](../textshapetype/)。 |
| virtual [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() | **True** 如果文字在 [TextFrame](../textframe/) 的邊緣換行。讀取 [NullableBool](../nullablebool/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關的參照計數資料結構。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() | 取得套用繼承後的有效文字框格式資料。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指定運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參照方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參照方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參照方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參照計數減少指定的值。 |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) | 設定 [TextFrame](../textframe/) 中的垂直錨點文字。寫入 [TextAnchorType](../textanchortype/)。 |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) | 設定文字的自動調整模式。寫入 [TextAutofitType](../textautofittype/)。 |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) | 如果 [NullableBool::True](../nullablebool/)，則文字應水平置中於方框內。寫入 [NullableBool](../nullablebool/)。 |
| virtual void [set_ColumnCount](./set_columncount/)(**int32_t**) | 設定文字區域的列數。此數值必須是正數。否則，該數值會被設定為零。值 0 表示未定義的值。寫入 **int32_t**。 |
| virtual void [set_ColumnSpacing](./set_columnspacing/)(**double**) | 設定文字區域中列與列之間的間距（以點為單位）。僅在存在超過一列時適用。此數值必須是正數。否則，該數值會被設定為零。寫入 **double**。 |
| virtual void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) | 傳回或設定將文字完全排除於 3D 場景之外。寫入 **bool**。 |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | 設定 [TextFrame](../textframe/) 中的底部邊距（點）。寫入 **double**。 |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | 設定 [TextFrame](../textframe/) 中的左側邊距（點）。寫入 **double**。 |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | 設定 [TextFrame](../textframe/) 中的右側邊距（點）。寫入 **double**。 |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | 設定 [TextFrame](../textframe/) 中的頂部邊距（點）。寫入 **double**。 |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | 指定套用於文字於邊界框內的自訂旋轉。如果未指定，則使用伴隨圖形的旋轉。如果已指定，則此旋轉獨立於圖形。也就是說，圖形可以有旋轉，同時文字本身也可以有旋轉。此屬性與屬性 TextVerticalType 中的預定義垂直類型共同匯總得到的視覺文字旋轉值。寫入 **float**。 |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | 決定文字方向。此屬性與屬性 RotationAngle 中的自訂角度共同匯總得到的視覺文字旋轉值。寫入 [Slides::TextVerticalType](../textverticaltype/)。 |
| virtual void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) | 設定文字換行形狀。寫入 [TextShapeType](../textshapetype/)。 |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) | **True** 如果文字在 [TextFrame](../textframe/) 的邊緣換行。寫入 [NullableBool](../nullablebool/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參照計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參照計數。 不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共享參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參照計數。 不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參照計數。 不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [Object](../../system/object/)
* 命名空間 [Aspose::Slides](../)
* 程式庫 [Aspose.Slides](../../)