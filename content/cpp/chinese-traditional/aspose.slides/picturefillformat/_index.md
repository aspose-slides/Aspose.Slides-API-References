---
title: PictureFillFormat
second_title: Aspose.Slides C++ API 參考
description: 表示圖片填充樣式。
type: docs
weight: 4720
url: /zh-hant/aspose.slides/picturefillformat/
---
## PictureFillFormat 類別

表示圖片填充樣式。

```cpp
class PictureFillFormat : public Aspose::Slides::PVIObject,
                          public Aspose::Slides::IPictureFillFormat
```

## 方法

| 方法 | 說明 |
| --- | --- |
| **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) override | 壓縮圖像，根據形狀大小和指定的解析度減小其尺寸。可選地，它還會刪除裁剪區域。 |
| **bool** [CompressImage](./compressimage/)(**bool**, **float**) override | 壓縮圖像，根據形狀大小和指定的解析度減小其尺寸。可選地，它還會刪除裁剪區域。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() override | 刪除填充 [Picture](../picture/) 的裁剪區域。 |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 與指定的物件比較。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語義比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考類型物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| **float** [get_CropBottom](./get_cropbottom/)() override | 返回圖片底部裁剪的實際影像高度百分比。讀取 **float**。 |
| **float** [get_CropLeft](./get_cropleft/)() override | 返回圖片左側裁剪的實際影像寬度百分比。讀取 **float**。 |
| **float** [get_CropRight](./get_cropright/)() override | 返回圖片右側裁剪的實際影像寬度百分比。讀取 **float**。 |
| **float** [get_CropTop](./get_croptop/)() override | 返回圖片頂部裁剪的實際影像高度百分比。讀取 **float**。 |
| **int32_t** [get_Dpi](./get_dpi/)() override | 返回用於填充圖片的 DPI。讀取 **int32_t**。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | 返回 Parent_Immediate 物件。唯讀 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 返回父層 [IPresentationComponent](../ipresentationcomponent/)。唯讀 [IPresentationComponent](../ipresentationcomponent/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | 返回圖片。唯讀 [ISlidesPicture](../islidespicture/)。 |
| [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() override | 返回圖片填充模式。讀取 [Slides::PictureFillMode](../picturefillmode/)。 |
| **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() override | 返回填充矩形的底部邊緣，該邊緣以相對於形狀邊界框底部邊緣的百分比偏移定義。正百分比表示內縮，負百分比表示外伸。讀取 **float**。 |
| **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() override | 返回填充矩形的左側邊緣，該邊緣以相對於形狀邊界框左側邊緣的百分比偏移定義。正百分比表示內縮，負百分比表示外伸。讀取 **float**。 |
| **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() override | 返回填充矩形的右側邊緣，該邊緣以相對於形狀邊界框右側邊緣的百分比偏移定義。正百分比表示內縮，負百分比表示外伸。讀取 **float**。 |
| **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() override | 返回填充矩形的頂部邊緣，該邊緣以相對於形狀邊界框頂部邊緣的百分比偏移定義。正百分比表示內縮，負百分比表示外伸。讀取 **float**。 |
| [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() override | 返回紋理在形狀內的對齊方式。此設定控制紋理圖案的起始點以及在形狀上的重複方式。讀取 [RectangleAlignment](../rectanglealignment/)。 |
| [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() override | 水平、垂直或同時翻轉紋理瓦片。讀取 [Slides::TileFlip](../tileflip/)。 |
| **float** [get_TileOffsetX](./get_tileoffsetx/)() override | 返回紋理相對於形狀原點的水平偏移（點）。正值向右移動，負值向左移動。讀取 **float**。 |
| **float** [get_TileOffsetY](./get_tileoffsety/)() override | 返回紋理相對於形狀原點的垂直偏移（點）。正值向下移動，負值向上移動。讀取 **float**。 |
| **float** [get_TileScaleX](./get_tilescalex/)() override | 返回紋理填充的水平縮放比例（百分比）。讀取 **float**。 |
| **float** [get_TileScaleY](./get_tilescaley/)() override | 返回紋理填充的垂直縮放比例（百分比）。讀取 **float**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數器資料結構。 |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | 返回雜湊碼。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視器物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [set_CropBottom](./set_cropbottom/)(**float**) override | 設定圖片底部裁剪的實際影像高度百分比。寫入 **float**。 |
| void [set_CropLeft](./set_cropleft/)(**float**) override | 設定圖片左側裁剪的實際影像寬度百分比。寫入 **float**。 |
| void [set_CropRight](./set_cropright/)(**float**) override | 設定圖片右側裁剪的實際影像寬度百分比。寫入 **float**。 |
| void [set_CropTop](./set_croptop/)(**float**) override | 設定圖片頂部裁剪的實際影像高度百分比。寫入 **float**。 |
| void [set_Dpi](./set_dpi/)(**int32_t**) override | 設定用於填充圖片的 DPI。寫入 **int32_t**。 |
| void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) override | 設定圖片填充模式。寫入 [Slides::PictureFillMode](../picturefillmode/)。 |
| void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) override | 設定填充矩形的底部邊緣，該邊緣以相對於形狀邊界框底部邊緣的百分比偏移定義。正百分比表示內縮，負百分比表示外伸。寫入 **float**。 |
| void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) override | 設定填充矩形的左側邊緣，該邊緣以相對於形狀邊界框左側邊緣的百分比偏移定義。正百分比表示內縮，負百分比表示外伸。寫入 **float**。 |
| void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) override | 設定填充矩形的右側邊緣，該邊緣以相對於形狀邊界框右側邊緣的百分比偏移定義。正百分比表示內縮，負百分比表示外伸。寫入 **float**。 |
| void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) override | 設定填充矩形的頂部邊緣，該邊緣以相對於形狀邊界框頂部邊緣的百分比偏移定義。正百分比表示內縮，負百分比表示外伸。寫入 **float**。 |
| void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) override | 設定紋理在形狀內的對齊方式。此設定控制紋理圖案的起始點以及在形狀上的重複方式。寫入 [RectangleAlignment](../rectanglealignment/)。 |
| void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) override | 水平、垂直或同時翻轉紋理瓦片。寫入 [Slides::TileFlip](../tileflip/)。 |
| void [set_TileOffsetX](./set_tileoffsetx/)(**float**) override | 設定紋理相對於形狀原點的水平偏移（點）。正值向右移動，負值向左移動。寫入 **float**。 |
| void [set_TileOffsetY](./set_tileoffsety/)(**float**) override | 設定紋理相對於形狀原點的垂直偏移（點）。正值向下移動，負值向上移動。寫入 **float**。 |
| void [set_TileScaleX](./set_tilescalex/)(**float**) override | 設定紋理填充的水平縮放比例（百分比）。寫入 **float**。 |
| void [set_TileScaleY](./set_tilescaley/)(**float**) override | 設定紋理填充的垂直縮放比例（百分比）。寫入 **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的當前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視器物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 參見

* 類別 [PVIObject](../pviobject/)
* 類別 [IPictureFillFormat](../ipicturefillformat/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)