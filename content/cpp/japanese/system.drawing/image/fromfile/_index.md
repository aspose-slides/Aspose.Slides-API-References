---
title: FromFile()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたファイルから Image オブジェクトを作成します。
type: docs
weight: 352
url: /ja/system.drawing/image/fromfile/
---
## Image::FromFile(const String\&, bool) メソッド

指定されたファイルから [Image](../) オブジェクトを作成します。

```cpp
static SharedPtr<Image> System::Drawing::Image::FromFile(const String &filename, bool use_embedded_color_management=false)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 画像データが含まれるファイルの名前 |
| use_embedded_color_management | **bool** | 無視 |

### 戻り値

作成された [Image](../) オブジェクトへの共有ポインタ。

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Image](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)