---
title: Point class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.animation/point/
---
## Point クラス

アニメーションポイントを表します。

Point 型は次のメンバーを公開します：

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides.animation/point/__init__/#) | デフォルトコンストラクタ。 |
| [`__init__(self, time, value, formula)`](/slides/python-net/ja/aspose.slides.animation/point/__init__/#float-any-str) | 時間、値、式を使用してアニメーションポイントを作成します。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`time`](/slides/python-net/ja/aspose.slides.animation/point/time/) | 時間値を表します。<br/>            読み書き **float**. |
| [`value`](/slides/python-net/ja/aspose.slides.animation/point/value/) | ポイント値を表します。<br/>            対象: bool, ColorFormat, float, int, string.<br/>            読み書き **any**. |
| [`formula`](/slides/python-net/ja/aspose.slides.animation/point/formula/) | values, from, to, by 属性の式は次の要素で構成できます：<br/>            標準算術演算子: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)<br/>            定数: ‘pi’ ‘e’<br/>            条件演算子: ‘abs’, ‘min’, ‘max’, ‘?’ (if)<br/>            比較演算子: '==', '>=', '', '!=', '!'<br/>            三角関数演算子: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’<br/>            自然対数 ‘ln()’<br/>            プロパティ参照 (ホストがサポートするプロパティ)<br/>            <br/>            例: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>            読み書き **str**. |

### 参照
* モジュール [`aspose.slides.animation`](/slides/python-net/ja/aspose.slides.animation)
* ライブラリ [`Aspose.Slides`](/slides/python-net)