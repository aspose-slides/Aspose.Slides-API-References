---
title: Intersect()
second_title: Aspose.Slides for C++ API 參考文件
description: 用與指定物件所代表的矩形相交後得到的矩形，取代目前物件所代表的矩形。
type: docs
weight: 274
url: /zh-hant/system.drawing/rectangle/intersect/
---
## Rectangle::Intersect(const Rectangle\&) 方法


用與指定物件所代表的矩形相交後得到的矩形，取代目前物件所代表的矩形。

```cpp
void System::Drawing::Rectangle::Intersect(const Rectangle &rect)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | 代表與目前物件所代表的矩形相交之矩形的 [Rectangle](../) 物件 |

## Rectangle::Intersect(const Rectangle\&, const Rectangle\&) 方法


傳回一個矩形，該矩形是指定矩形相交的結果。

```cpp
static Rectangle System::Drawing::Rectangle::Intersect(const Rectangle &a, const Rectangle &b)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| a | const [Rectangle](../)\& | 第一個要相交的矩形 |
| b | const [Rectangle](../)\& | 第二個要相交的矩形 |

### 返回值

**a** 與 **b** 相交的結果

## 另請參閱

* 類別 [Rectangle](../)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)