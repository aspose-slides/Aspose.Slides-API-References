---
title: GetHeight()
second_title: Aspose.Slides for C++ API 參考文件
description: 返回當前物件所代表字型的行距，以指定的 Graphics 物件的當前單位表示。
type: docs
weight: 14
url: /zh-hant/system.drawing/font/getheight/
---
## Font::GetHeight(const SharedPtr\<Graphics\>\&) 方法


返回當前物件所代表字型的行距，以指定的 [Graphics](../../graphics/) 物件的當前單位表示。

```cpp
float System::Drawing::Font::GetHeight(const SharedPtr<Graphics> &graphics)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | 一個 [Graphics](../../graphics/) 物件，指定測量單位 |

## Font::GetHeight(float) 方法


返回當前物件所代表字型的高度，當其在具有指定垂直解析度的顯示設備上繪製時。

```cpp
float System::Drawing::Font::GetHeight(float dpi=DEFAULT_FONT_OPERATIONS_DPI)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| dpi | **float** | 顯示裝置的垂直解析度 |

### 返回值

字型的高度（像素）

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Graphics](../../graphics/)
* 類別 [Font](../)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)