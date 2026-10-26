---
title: Pen()
second_title: Aspose.Slides for C++ API 參考
description: 建構一個代表指定顏色的 Pen 物件。
type: docs
weight: 1
url: /zh-hant/system.drawing/pen/pen/
---
## Pen::Pen(const Color\&) 建構函式

建構一個代表指定顏色的 [Pen](../) 物件。

```cpp
System::Drawing::Pen::Pen(const Color &color)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| color | const [Color](../../color/)\& | 建構之物件所代表之筆的顏色 |

## Pen::Pen(const Color\&, float) 建構函式

建構一個代表指定顏色與寬度的 [Pen](../) 物件。

```cpp
System::Drawing::Pen::Pen(const Color &color, float width)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| color | const [Color](../../color/)\& | 建構之物件所代表之筆的顏色 |
| width | **float** | 建構之物件所代表之筆的寬度 |

## Pen::Pen(const SharedPtr\<Brush\>\&) 建構函式

建構一個 [Pen](../) 物件，並以指定的 [Brush](../../brush/) 物件進行初始化。

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 指定建構之物件所代表之筆的填充屬性的 [Brush](../../brush/) 物件。 |

## Pen::Pen(const SharedPtr\<Brush\>\&, float) 建構函式

建構一個 [Pen](../) 物件，並以指定的 [Brush](../../brush/) 物件進行初始化。

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush, float width)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 指定建構之物件所代表之筆的填充屬性的 [Brush](../../brush/) 物件。 |
| width | **float** | 建構之物件所代表之筆的寬度 |

## 相關參考

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Color](../../color/)
* 類別 [Pen](../)
* 類別 [Brush](../../brush/)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)