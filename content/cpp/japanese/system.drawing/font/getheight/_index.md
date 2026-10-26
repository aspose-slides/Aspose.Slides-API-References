---
title: GetHeight()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトで表されるフォントの行間を、指定された Graphics オブジェクトの現在の単位で返します。
type: docs
weight: 14
url: /ja/system.drawing/font/getheight/
---
## Font::GetHeight(const SharedPtr\<Graphics\>\&) method

現在のオブジェクトで表されるフォントの行間を、指定された [Graphics](../../graphics/) オブジェクトの現在の単位で返します。

```cpp
float System::Drawing::Font::GetHeight(const SharedPtr<Graphics> &graphics)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | 測定単位を指定する [Graphics](../../graphics/) オブジェクト |

## Font::GetHeight(float) method

現在のオブジェクトで表されるフォントの高さを、指定された垂直解像度を持つ表示デバイスに描画した場合に返します。

```cpp
float System::Drawing::Font::GetHeight(float dpi=DEFAULT_FONT_OPERATIONS_DPI)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| dpi | **float** | 表示デバイスの垂直解像度 |

### Return Value

フォントの高さ（ピクセル単位）

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Graphics](../../graphics/)
* Class [Font](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)