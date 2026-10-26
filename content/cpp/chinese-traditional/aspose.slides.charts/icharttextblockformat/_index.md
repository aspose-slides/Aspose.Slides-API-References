---
title: IChartTextBlockFormat
second_title: Aspose.Slides for C++ API 參考
description: 表示圖表文字元素的格式屬性。
type: docs
weight: 885
url: /zh-hant/aspose.slides.charts/icharttextblockformat/
---
## IChartTextBlockFormat 類別


表示圖表文字元素的格式屬性。

```cpp
class IChartTextBlockFormat : public virtual System::Object
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語義比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [TextAnchorType](../../aspose.slides/textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | 在 [TextFrame](../../aspose.slides/textframe/) 中返回垂直錨點文字。讀取 [TextAnchorType](../../aspose.slides/textanchortype/)。 |
| virtual [TextAutofitType](../../aspose.slides/textautofittype/) [get_AutofitType](./get_autofittype/)() | 返回文字的自動調整模式。變更此屬性僅會對以下圖表部件產生特定影響：[DataLabel](../datalabel/) 和 [DataLabelFormat](../datalabelformat/)（在 PowerPoint 2013 中完整支援；在 PowerPoint 2007 中對呈現無效）。讀取 [TextAutofitType](../../aspose.slides/textautofittype/)。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_CenterText](./get_centertext/)() | 如果 [NullableBool::True](../../aspose.slides/nullablebool/)，則文字應在框內水平置中。讀取 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | 在 [TextFrame](../../aspose.slides/textframe/) 中返回底部邊距（點）。變更此屬性僅會對以下圖表部件產生特定影響：[DataLabel](../datalabel/) 和 [DataLabelFormat](../datalabelformat/)（在 PowerPoint 2013 中完整支援；在 PowerPoint 2007 中對呈現無效）。讀取 **double**。 |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | 在 [TextFrame](../../aspose.slides/textframe/) 中返回左側邊距（點）。變更此屬性僅會對以下圖表部件產生特定影響：[DataLabel](../datalabel/) 和 [DataLabelFormat](../datalabelformat/)（在 PowerPoint 2013 中完整支援；在 PowerPoint 2007 中對呈現無效）。讀取 **double**。 |
| virtual **double** [get_MarginRight](./get_marginright/)() | 在 [TextFrame](../../aspose.slides/textframe/) 中返回右側邊距（點）。變更此屬性僅會對以下圖表部件產生特定影響：[DataLabel](../datalabel/) 和 [DataLabelFormat](../datalabelformat/)（在 PowerPoint 2013 中完整支援；在 PowerPoint 2007 中對呈現無效）。讀取 **double**。 |
| virtual **double** [get_MarginTop](./get_margintop/)() | 在 [TextFrame](../../aspose.slides/textframe/) 中返回頂部邊距（點）。變更此屬性僅會對以下圖表部件產生特定影響：[DataLabel](../datalabel/) 和 [DataLabelFormat](../datalabelformat/)（在 PowerPoint 2013 中完整支援；在 PowerPoint 2007 中對呈現無效）。讀取 **double**。 |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | 指定套用於邊界框內文字的自訂旋轉。如果未指定，則使用伴隨形狀的旋轉。如果已指定，則此旋轉獨立於形狀應用。也就是說，形狀可以有旋轉，同時文字本身也可以有旋轉。最終的視覺文字旋轉值是從此屬性與屬性 TextVerticalType 中預先定義的垂直類型彙總而得。讀取 **float**。 |
| virtual [Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | 決定文字方向。最終的視覺文字旋轉值是從此屬性與屬性 RotationAngle 中的自訂角度彙總而得。讀取 [Slides::TextVerticalType](../../aspose.slides/textverticaltype/)。 |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_WrapText](./get_wraptext/)() | **True** 如果文字在 [TextFrame](../../aspose.slides/textframe/) 的邊緣換行則為 **True**。變更此屬性僅會對以下圖表部件產生特定影響：[DataLabel](../datalabel/) 和 [DataLabelFormat](../datalabelformat/)（在 PowerPoint 2007/2013 中完整支援）。讀取 [NullableBool](../../aspose.slides/nullablebool/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的引用計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類比。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類比。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以引用方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以引用方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以引用方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況下的特殊化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況下的特殊化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享引用計數減少指定的值。 |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../../aspose.slides/textanchortype/)) | 在 [TextFrame](../../aspose.slides/textframe/) 中設定垂直錨點文字。寫入 [TextAnchorType](../../aspose.slides/textanchortype/)。 |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../../aspose.slides/textautofittype/)) | 設定文字的自動調整模式。變更此屬性僅會對以下圖表部件產生特定影響：[DataLabel](../datalabel/) 和 [DataLabelFormat](../datalabelformat/)（在 PowerPoint 2013 中完整支援；在 PowerPoint 2007 中對呈現無效）。寫入 [TextAutofitType](../../aspose.slides/textautofittype/)。 |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../../aspose.slides/nullablebool/)) | 如果 [NullableBool::True](../../aspose.slides/nullablebool/)，則文字應在框內水平置中。寫入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | 在 [TextFrame](../../aspose.slides/textframe/) 中設定底部邊距（點）。變更此屬性僅會對以下圖表部件產生特定影響：[DataLabel](../datalabel/) 和 [DataLabelFormat](../datalabelformat/)（在 PowerPoint 2013 中完整支援；在 PowerPoint 2007 中對呈現無效）。寫入 **double**。 |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | 在 [TextFrame](../../aspose.slides/textframe/) 中設定左側邊距（點）。變更此屬性僅會對以下圖表部件產生特定影響：[DataLabel](../datalabel/) 和 [DataLabelFormat](../datalabelformat/)（在 PowerPoint 2013 中完整支援；在 PowerPoint 2007 中對呈現無效）。寫入 **double**。 |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | 在 [TextFrame](../../aspose.slides/textframe/) 中設定右側邊距（點）。變更此屬性僅會對以下圖表部件產生特定影響：[DataLabel](../datalabel/) 和 [DataLabelFormat](../datalabelformat/)（在 PowerPoint 2013 中完整支援；在 PowerPoint 2007 中對呈現無效）。寫入 **double**。 |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | 在 [TextFrame](../../aspose.slides/textframe/) 中設定頂部邊距（點）。變更此屬性僅會對以下圖表部件產生特定影響：[DataLabel](../datalabel/) 和 [DataLabelFormat](../datalabelformat/)（在 PowerPoint 2013 中完整支援；在 PowerPoint 2007 中對呈現無效）。寫入 **double**。 |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | 指定套用於邊界框內文字的自訂旋轉。如果未指定，則使用伴隨形狀的旋轉。如果已指定，則此旋轉獨立於形狀應用。也就是說，形狀可以有旋轉，同時文字本身也可以有旋轉。最終的視覺文字旋轉值是從此屬性與屬性 TextVerticalType 中預先定義的垂直類型彙總而得。寫入 **float**。 |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../../aspose.slides/textverticaltype/)) | 決定文字方向。最終的視覺文字旋轉值是從此屬性與屬性 RotationAngle 中的自訂角度彙總而得。寫入 [Slides::TextVerticalType](../../aspose.slides/textverticaltype/)。 |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../../aspose.slides/nullablebool/)) | **True** 如果文字在 [TextFrame](../../aspose.slides/textframe/) 的邊緣換行則為 **True**。變更此屬性僅會對以下圖表部件產生特定影響：[DataLabel](../datalabel/) 和 [DataLabelFormat](../datalabelformat/)（在 PowerPoint 2007/2013 中完整支援）。寫入 [NullableBool](../../aspose.slides/nullablebool/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享引用計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享引用計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享引用計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的類比。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱引用計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱引用計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [Object](../../system/object/)
* 命名空間 [Aspose::Slides::Charts](../)
* 函式庫 [Aspose.Slides](../../)