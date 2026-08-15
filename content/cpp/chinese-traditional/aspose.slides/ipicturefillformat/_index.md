---
title: IPictureFillFormat
second_title: Aspose.Slides for C++ API 參考
description: 表示圖片填充樣式。
type: docs
weight: 3225
url: /zh-hant/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat 類別

代表一種圖片填充樣式。

```cpp
class IPictureFillFormat : public Aspose::Slides::IFillParamSource
```

## 方法

| Method | Description |
| --- | --- |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) | 根據形狀大小和指定的解析度縮減圖像尺寸以壓縮圖像。可選地，它還會刪除裁剪區域。 |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, **float**) | 根據形狀大小和指定的解析度縮減圖像尺寸以壓縮圖像。可選地，它還會刪除裁剪區域。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() | 刪除填充 [Picture](../picture/) 的裁剪區域。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考類型物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值類型物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual **float** [get_CropBottom](./get_cropbottom/)() | 返回實際圖像高度被裁剪掉的底部百分比。讀取 **float**。 |
| virtual **float** [get_CropLeft](./get_cropleft/)() | 返回實際圖像寬度被裁剪掉的左側百分比。讀取 **float**。 |
| virtual **float** [get_CropRight](./get_cropright/)() | 返回實際圖像寬度被裁剪掉的右側百分比。讀取 **float**。 |
| virtual **float** [get_CropTop](./get_croptop/)() | 返回實際圖像高度被裁剪掉的頂部百分比。讀取 **float**。 |
| virtual **int32_t** [get_Dpi](./get_dpi/)() | 返回用於填充圖片的 DPI。讀取 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | 返回圖片。唯讀 [ISlidesPicture](../islidespicture/)。 |
| virtual [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() | 返回圖片填充模式。讀取 [Slides::PictureFillMode](../picturefillmode/)。 |
| virtual **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() | 返回填充矩形的底部邊緣，該邊緣以形狀邊界框底部邊緣的百分比偏移定義。正百分比表示內縮，負百分比表示外伸。讀取 **float**。 |
| virtual **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() | 返回填充矩形的左側邊緣，該邊緣以形狀邊界框左側邊緣的百分比偏移定義。正百分比表示內縮，負百分比表示外伸。讀取 **float**。 |
| virtual **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() | 返回填充矩形的右側邊緣，該邊緣以形狀邊界框右側邊緣的百分比偏移定義。正百分比表示內縮，負百分比表示外伸。讀取 **float**。 |
| virtual **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() | 返回填充矩形的頂部邊緣，該邊緣以形狀邊界框頂部邊緣的百分比偏移定義。正百分比表示內縮，負百分比表示外伸。讀取 **float**。 |
| virtual [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() | 返回紋理在形狀中的對齊方式。此設定控制紋理圖案的起始點以及在形狀上的重複方式。讀取 [RectangleAlignment](../rectanglealignment/)。 |
| virtual [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() | 將紋理圖塊沿水平、垂直或兩個軸翻轉。讀取 [Slides::TileFlip](../tileflip/)。 |
| virtual **float** [get_TileOffsetX](./get_tileoffsetx/)() | 返回紋理相對於形狀原點的水平偏移（單位為點）。正值將紋理向右移動，負值將紋理向左移動。讀取 **float**。 |
| virtual **float** [get_TileOffsetY](./get_tileoffsety/)() | 返回紋理相對於形狀原點的垂直偏移（單位為點）。正值將紋理向下移動，負值將紋理向上移動。讀取 **float**。 |
| virtual **float** [get_TileScaleX](./get_tilescalex/)() | 返回紋理填充的水平縮放百分比。讀取 **float**。 |
| virtual **float** [get_TileScaleY](./get_tilescaley/)() | 返回紋理填充的垂直縮放百分比。讀取 **float**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 等同於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊功能。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。等同於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。等同於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 等同於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別以複製方式建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別以複製方式建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值類型物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共用參考計數減少指定的值。 |
| virtual void [set_CropBottom](./set_cropbottom/)(**float**) | 設定實際圖像高度被裁剪掉的底部百分比。寫入 **float**。 |
| virtual void [set_CropLeft](./set_cropleft/)(**float**) | 設定實際圖像寬度被裁剪掉的左側百分比。寫入 **float**。 |
| virtual void [set_CropRight](./set_cropright/)(**float**) | 設定實際圖像寬度被裁剪掉的右側百分比。寫入 **float**。 |
| virtual void [set_CropTop](./set_croptop/)(**float**) | 設定實際圖像高度被裁剪掉的頂部百分比。寫入 **float**。 |
| virtual void [set_Dpi](./set_dpi/)(**int32_t**) | 設定用於填充圖片的 DPI。寫入 **int32_t**。 |
| virtual void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) | 設定圖片填充模式。寫入 [Slides::PictureFillMode](../picturefillmode/)。 |
| virtual void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) | 設定填充矩形的底部邊緣，該邊緣以形狀邊界框底部邊緣的百分比偏移定義。正百分比表示內縮，負百分比表示外伸。寫入 **float**。 |
| virtual void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) | 設定填充矩形的左側邊緣，該邊緣以形狀邊界框左側邊緣的百分比偏移定義。正百分比表示內縮，負百分比表示外伸。寫入 **float**。 |
| virtual void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) | 設定填充矩形的右側邊緣，該邊緣以形狀邊界框右側邊緣的百分比偏移定義。正百分比表示內縮，負百分比表示外伸。寫入 **float**。 |
| virtual void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) | 設定填充矩形的頂部邊緣，該邊緣以形狀邊界框頂部邊緣的百分比偏移定義。正百分比表示內縮，負百分比表示外伸。寫入 **float**。 |
| virtual void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) | 設定紋理在形狀中的對齊方式。此設定控制紋理圖案的起始點以及在形狀上的重複方式。寫入 [RectangleAlignment](../rectanglealignment/)。 |
| virtual void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) | 將紋理圖塊沿水平、垂直或兩個軸翻轉。寫入 [Slides::TileFlip](../tileflip/)。 |
| virtual void [set_TileOffsetX](./set_tileoffsetx/)(**float**) | 設定紋理相對於形狀原點的水平偏移（單位為點）。正值將紋理向右移動，負值將紋理向左移動。寫入 **float**。 |
| virtual void [set_TileOffsetY](./set_tileoffsety/)(**float**) | 設定紋理相對於形狀原點的垂直偏移（單位為點）。正值將紋理向下移動，負值將紋理向上移動。寫入 **float**。 |
| virtual void [set_TileScaleX](./set_tilescalex/)(**float**) | 設定紋理填充的水平縮放百分比。寫入 **float**。 |
| virtual void [set_TileScaleY](./set_tilescaley/)(**float**) | 設定紋理填充的垂直縮放百分比。寫入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享指標）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共用參考計數的當前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共用參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 等同於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [IFillParamSource](../ifillparamsource/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)