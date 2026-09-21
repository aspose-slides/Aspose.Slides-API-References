---
title: ITextFrameFormat class
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/itextframeformat/
---
## ITextFrameFormat 類別

包含 TextFrame 的格式屬性。

ITextFrameFormat 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`text_style`](/slides/python-net/zh-hant/aspose.slides/itextframeformat/text_style/) | 返回文字的樣式。<br/>            唯讀 [`ITextStyle`](/slides/python-net/zh-hant/aspose.slides/itextstyle). |
| [`margin_left`](/slides/python-net/zh-hant/aspose.slides/itextframeformat/margin_left/) | 返回或設定 TextFrame 中的左邊距（點）。<br/>            讀寫 **float**. |
| [`margin_right`](/slides/python-net/zh-hant/aspose.slides/itextframeformat/margin_right/) | 返回或設定 TextFrame 中的右邊距（點）。<br/>            讀寫 **float**. |
| [`margin_top`](/slides/python-net/zh-hant/aspose.slides/itextframeformat/margin_top/) | 返回或設定 TextFrame 中的上邊距（點）。<br/>            讀寫 **float**. |
| [`margin_bottom`](/slides/python-net/zh-hant/aspose.slides/itextframeformat/margin_bottom/) | 返回或設定 TextFrame 中的下邊距（點）。<br/>            讀寫 **float**. |
| [`wrap_text`](/slides/python-net/zh-hant/aspose.slides/itextframeformat/wrap_text/) | **True** 如果文字在 TextFrame 的邊距處換行。<br/>            讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/zh-hant/aspose.slides/itextframeformat/anchoring_type/) | 返回或設定 TextFrame 中的垂直錨點文字。<br/>            讀寫 [`TextAnchorType`](/slides/python-net/zh-hant/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/zh-hant/aspose.slides/itextframeformat/center_text/) | 如果 NullableBool.True，則文字應水平置中於盒子內。<br/>            讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/zh-hant/aspose.slides/itextframeformat/text_vertical_type/) | 決定文字方向。<br/>            此屬性與屬性 RotationAngle 中的自訂角度所彙總的視覺文字旋轉結果值。<br/>            讀寫 [`TextVerticalType`](/slides/python-net/zh-hant/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/zh-hant/aspose.slides/itextframeformat/autofit_type/) | 返回或設定文字的自動調整模式。<br/>            讀寫 [`TextAutofitType`](/slides/python-net/zh-hant/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/zh-hant/aspose.slides/itextframeformat/column_count/) | 返回或設定文字區域中的欄數。<br/>            此值必須為正數。否則，該值將設定為 0。 <br/>            值 0 表示未定義值。<br/>            讀寫 **int**. |
| [`column_spacing`](/slides/python-net/zh-hant/aspose.slides/itextframeformat/column_spacing/) | 返回或設定文字區域中欄間距（以點為單位）。此設定僅在存在超過 1 個欄時適用。<br/>            此值必須為正數。否則，該值將設定為 0。 <br/>            讀寫 **float**. |
| [`three_d_format`](/slides/python-net/zh-hant/aspose.slides/itextframeformat/three_d_format/) | 返回表示文字 3D 效果屬性的 ThreeDFormat 物件。<br/>            唯讀 [`IThreeDFormat`](/slides/python-net/zh-hant/aspose.slides/ithreedformat). |
| [`keep_text_flat`](/slides/python-net/zh-hant/aspose.slides/itextframeformat/keep_text_flat/) | 返回或設定將文字完全排除於 3D 場景之外。<br/>            讀寫 **bool**. |
| [`rotation_angle`](/slides/python-net/zh-hant/aspose.slides/itextframeformat/rotation_angle/) | 指定套用於文字於邊界框內的自訂旋轉。<br/>            如果未指定，則使用伴隨形狀的旋轉。<br/>            如果已指定，則此旋轉獨立於形狀套用。<br/>            也就是說，形狀可以有旋轉，同時文字本身也可以有旋轉。<br/>            此屬性與屬性 TextVerticalType 中預定義的垂直類型所彙總的視覺文字旋轉結果值。<br/>            讀寫 **float**. |
| [`transform`](/slides/python-net/zh-hant/aspose.slides/itextframeformat/transform/) | 取得或設定文字換行形狀。<br/>            讀寫 [`TextShapeType`](/slides/python-net/zh-hant/aspose.slides/textshapetype). |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/zh-hant/aspose.slides/itextframeformat/get_effective/#) | 取得套用繼承後的有效文字框格式資料。 |

### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)