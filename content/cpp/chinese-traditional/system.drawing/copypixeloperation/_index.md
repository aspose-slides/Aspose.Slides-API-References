---
title: CopyPixelOperation
second_title: Aspose.Slides for C++ API 參考
description: 指定在像素複製操作中，來源顏色如何與目標顏色結合，以產生最終顏色。
type: docs
weight: 391
url: /zh-hant/system.drawing/copypixeloperation/
---
## CopyPixelOperation 列舉

指定在像素複製操作中，來源顏色如何與目標顏色結合，形成最終顏色。

```cpp
enum class CopyPixelOperation
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| NoMirrorBitmap | n/a | 位圖未鏡像。 |
| Blackness | 66 | 使用實體調色盤中索引為 0 的顏色填充目標區域。 |
| NotSourceErase | 1114278 | 將來源和目標顏色進行 OR 運算，然後將產生的顏色反相。 |
| NotSourceCopy | 3342344 | 來源區域先被反相，然後複製到目標。 |
| SourceErase | 4457256 | 目標區域的反相顏色與來源區域的顏色進行 AND 運算。 |
| DestinationInvert | 5570569 | 目標區域被反相。 |
| PatInvert | 5898313 | 目前在目標裝置情境中選取的畫筆顏色與目標的顏色進行 XOR 運算。 |
| SourceInvert | 6684742 | 來源與目標區域的顏色進行 XOR 運算。 |
| SourceAnd | 8913094 | 來源與目標區域的顏色進行 AND 運算。 |
| MergePaint | 12255782 | 反相來源區域的顏色與目標區域的顏色進行 OR 運算。 |
| MergeCopy | 12583114 | 來源區域的顏色與目標裝置情境中選取的畫筆顏色進行 AND 運算。 |
| SourceCopy | 13369376 | 來源區域直接複製到目標區域。 |
| SourcePaint | 15597702 | 來源與目標區域的顏色進行 OR 運算。 |
| PatCopy | 15728673 | 目前在目標裝置情境中選取的畫筆被複製到目標位圖。 |
| PatPaint | 16452105 | 目前在目標裝置情境中選取的畫筆顏色與反相來源區域的顏色進行 OR 運算。此操作的結果再與目標區域的顏色進行 OR 運算。 |
| Whiteness | 16711778 | 使用實體調色盤中索引為 1 的顏色填充目標區域。 |
| CaptureBlt | 1073741824 | [Windows](../../system.windows/) 那些層疊在應用程式視窗之上的內容會包含在產生的影像中。 |

## 另見

* 命名空間 [System::Drawing](../)
* 函式庫 [Aspose.Slides](../../)