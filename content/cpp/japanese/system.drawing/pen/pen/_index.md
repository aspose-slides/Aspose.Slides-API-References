---
title: Pen()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された色を表す新しい Pen オブジェクトを構築します。
type: docs
weight: 1
url: /ja/system.drawing/pen/pen/
---
## Pen::Pen(const Color\&) constructor

指定された色を表す新しい[Pen](../)オブジェクトを構築します。

```cpp
System::Drawing::Pen::Pen(const Color &color)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| color | const [Color](../../color/)\& | 構築中のオブジェクトが表すペンの色 |

## Pen::Pen(const Color\&, float) constructor

指定された色と幅を表す新しい[Pen](../)オブジェクトを構築します。

```cpp
System::Drawing::Pen::Pen(const Color &color, float width)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| color | const [Color](../../color/)\& | 構築中のオブジェクトが表すペンの色 |
| width | **float** | 構築中のオブジェクトが表すペンの幅 |

## Pen::Pen(const SharedPtr\<Brush\>\&) constructor

指定された[Brush](../../brush/)オブジェクトで初期化された新しい[Pen](../)オブジェクトを構築します。

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 構築中のオブジェクトが表すペンの塗りつぶしプロパティを指定する[Brush](../../brush/)オブジェクト |

## Pen::Pen(const SharedPtr\<Brush\>\&, float) constructor

指定された[Brush](../../brush/)オブジェクトで初期化された新しい[Pen](../)オブジェクトを構築します。

```cpp
System::Drawing::Pen::Pen(const SharedPtr<Brush> &brush, float width)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 構築中のオブジェクトが表すペンの塗りつぶしプロパティを指定する[Brush](../../brush/)オブジェクト |
| width | **float** | 構築中のオブジェクトが表すペンの幅 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Color](../../color/)
* クラス [Pen](../)
* クラス [Brush](../../brush/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)