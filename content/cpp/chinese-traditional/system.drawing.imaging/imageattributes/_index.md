---
title: ImageAttributes
second_title: Aspose.Slides for C++ API 參考
description: "表示在渲染過程中圖像顏色的操作資訊。此類別的物件只能使用 System::MakeObject() 函式分配。切勿在堆疊上或使用 new 運算子建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。始終將此類別包裝成 System::SmartPtr 指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 105
url: /zh-hant/system.drawing.imaging/imageattributes/
---
## ImageAttributes 類別

表示在渲染過程中圖像顏色的操作資訊。此類別的物件只能使用 [System::MakeObject()](../../system/makeobject/) 函式分配。切勿在堆疊上或使用 new 運算子建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。總是將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。

```cpp
class ImageAttributes : public System::Object
```

## 方法

| 方法 | 說明 |
| --- | --- |
| void [ClearBrushRemapTable](./clearbrushremaptable/)() | 未實作。 |
| void [ClearColorKey](./clearcolorkey/)([ColorAdjustType](../coloradjusttype/)) | 未實作。 |
| void [ClearColorMatrix](./clearcolormatrix/)([ColorAdjustType](../coloradjusttype/)) | 未實作。 |
| void [ClearGamma](./cleargamma/)([ColorAdjustType](../coloradjusttype/)) | 未實作。 |
| void [ClearNoOp](./clearnoop/)([ColorAdjustType](../coloradjusttype/)) | 未實作。 |
| void [ClearOutputChannel](./clearoutputchannel/)([ColorAdjustType](../coloradjusttype/)) | 未實作。 |
| void [ClearOutputChannelColorProfile](./clearoutputchannelcolorprofile/)([ColorAdjustType](../coloradjusttype/)) | 未實作。 |
| void [ClearRemapTable](./clearremaptable/)([ColorAdjustType](../coloradjusttype/)) | 未實作。 |
| void [ClearThreshold](./clearthreshold/)([ColorAdjustType](../coloradjusttype/)) | 未實作。 |
| [SharedPtr](../../system/sharedptr/)\<[ImageAttributes](./)\> [Clone](./clone/)() | 建立目前物件的副本。 |
| void [Dispose](./dispose/)() | 釋放目前物件取得的所有作業系統資源。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| void [GetAdjustedPalette](./getadjustedpalette/)(const [SharedPtr](../../system/sharedptr/)\<[ColorPalette](../colorpalette/)\>\&, [ColorAdjustType](../coloradjusttype/)) | 未實作。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類比。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。C# [System.Object.GetType()](../../system/object/gettype/) 呼叫的類比。 |
|  [ImageAttributes](./imageattributes/)() | 預設建構子。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否代表 targetType 所描述的類型實例。C# 'is' 運算子的類比。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類比。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，適用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，適用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [SetBrushRemapTable](./setbrushremaptable/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[ColorMap](../colormap/)\>\>\&) | 未實作。 |
| void [SetColorKey](./setcolorkey/)([Color](../../system.drawing/color/), [Color](../../system.drawing/color/), [ColorAdjustType](../coloradjusttype/)) | 未實作。 |
| void [SetColorMatrices](./setcolormatrices/)(const [SharedPtr](../../system/sharedptr/)\<[ColorMatrix](../colormatrix/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[ColorMatrix](../colormatrix/)\>\&, [ColorMatrixFlag](../colormatrixflag/), [ColorAdjustType](../coloradjusttype/)) | 未實作。 |
| void [SetColorMatrix](./setcolormatrix/)(const [SharedPtr](../../system/sharedptr/)\<[ColorMatrix](../colormatrix/)\>\&, [ColorMatrixFlag](../colormatrixflag/), [ColorAdjustType](../coloradjusttype/)) | 設定顏色調整矩陣。 |
| void [SetGamma](./setgamma/)(**float**, [ColorAdjustType](../coloradjusttype/)) | 未實作。 |
| void [SetNoOp](./setnoop/)([ColorAdjustType](../coloradjusttype/)) | 未實作。 |
| void [SetOutputChannel](./setoutputchannel/)([ColorChannelFlag](../colorchannelflag/), [ColorAdjustType](../coloradjusttype/)) | 未實作。 |
| void [SetOutputChannelColorProfile](./setoutputchannelcolorprofile/)(const [String](../../system/string/)\&, [ColorAdjustType](../coloradjusttype/)) | 未實作。 |
| void [SetRemapTable](./setremaptable/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[ColorMap](../colormap/)\>\>\&, [ColorAdjustType](../coloradjusttype/)) | 未實作。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中切換指標為弱模式。 |
| void [SetThreshold](./setthreshold/)(**float**, [ColorAdjustType](../coloradjusttype/)) | 未實作。 |
| void [SetWrapMode](./setwrapmode/)([Drawing2D::WrapMode](../../system.drawing.drawing2d/wrapmode/), [Color](../../system.drawing/color/), **bool**) | 設定平鋪模式以及用於決定如何在形狀或形狀邊界上平鋪紋理的顏色。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 將共享參考計數遞減並回傳。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的類比。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 將弱參考計數遞減。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [Object](../../system/object/)
* 命名空間 [System::Drawing::Imaging](../)
* 函式庫 [Aspose.Slides](../../)