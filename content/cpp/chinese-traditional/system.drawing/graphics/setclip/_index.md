---
title: SetClip()
second_title: Aspose.Slides 適用於 C++ 的 API 參考
description: 將由目前 Graphics 物件所表示的繪圖表面的裁剪區域設定為結合目前裁剪區域與指定區域之指定運算的結果。
type: docs
weight: 690
url: /zh-hant/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) method


設定由目前 [Graphics](../) 物件所表示的繪圖表面的裁剪區域為結合目前裁剪區域與指定區域之指定運算的結果。

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | 指定要結合的區域 |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | 指定結合運算 |

## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) method


設定由目前 [Graphics](../) 物件所表示的繪圖表面的裁剪區域為結合目前裁剪區域與指定區域之指定運算的結果。

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | 指定要結合的區域 |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | 指定結合運算 |

## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) method


設定由目前 [Graphics](../) 物件所表示的繪圖表面的裁剪區域為結合目前裁剪區域與指定區域之指定運算的結果。

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | 指定要結合的區域 |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | 指定結合運算 |

## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) method


未實作。

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) method


設定由目前 [Graphics](../) 物件所表示的繪圖表面的裁剪區域為結合目前裁剪區域與由圖形路徑指定之區域之指定運算的結果。

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 指定要結合的區域 |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | 指定結合運算 |

## 另請參閱

* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Region](../../region/)
* 類別 [Graphics](../)
* 類別 [Rectangle](../../rectangle/)
* 類別 [RectangleF](../../rectanglef/)
* 類別 [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* 命名空間 [System::Drawing](../../)
* Library [Aspose.Slides](../../../)