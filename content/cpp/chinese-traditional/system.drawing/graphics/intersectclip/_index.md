---
title: IntersectClip()
second_title: Aspose.Slides for C++ API 參考
description: 將此物件的裁剪區域更新為目前裁剪區域與指定裁剪區域的交集。
type: docs
weight: 950
url: /zh-hant/system.drawing/graphics/intersectclip/
---
## Graphics::IntersectClip(const System::SharedPtr\<Region\>\&) 方法

更新此物件的裁剪區域，使其與目前裁剪區域與指定裁剪區域的交集相同。

```cpp
void System::Drawing::Graphics::IntersectClip(const System::SharedPtr<Region> &region)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| region | const [System::SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | 要交集的區域 |

## Graphics::IntersectClip(System::Drawing::RectangleF) 方法

更新此物件的裁剪區域，使其與目前裁剪區域與指定裁剪區域的交集相同。

```cpp
void System::Drawing::Graphics::IntersectClip(System::Drawing::RectangleF rect)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rect | [System::Drawing::RectangleF](../../rectanglef/) | 要交集的矩形 |

## Graphics::IntersectClip(System::Drawing::Rectangle) 方法

更新此物件的裁剪區域，使其與目前裁剪區域與指定裁剪區域的交集相同。

```cpp
void System::Drawing::Graphics::IntersectClip(System::Drawing::Rectangle rect)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rect | [System::Drawing::Rectangle](../../rectangle/) | 要交集的矩形 |

## 另請參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Region](../../region/)
* 類別 [Graphics](../)
* 類別 [RectangleF](../../rectanglef/)
* 類別 [Rectangle](../../rectangle/)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)