---
title: IPoint class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.animation/ipoint/
---
## IPoint クラス

アニメーションのポイントを表します。

IPoint型は次のメンバーを公開します:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`time`](/slides/python-net/ja/aspose.slides.animation/ipoint/time/) | 時間の値を表します。<br/>            読み取り/書き込み **float**. |
| [`value`](/slides/python-net/ja/aspose.slides.animation/ipoint/value/) | ポイントの値を表します。<br/>            対象: bool, ColorFormat, float, int, string.<br/>            読み取り/書き込み **any**. |
| [`formula`](/slides/python-net/ja/aspose.slides.animation/ipoint/formula/) | 値、from、to、by 属性内の数式は以下で構成できます：<br/>            標準の算術演算子: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)<br/>            定数: ‘pi’ ‘e’<br/>            条件演算子: ‘abs’, ‘min’, ‘max’, ‘?’ (if)<br/>            比較演算子: '==', '>=', '', '!=', '!'<br/>            三角関数演算子: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’<br/>            自然対数 ‘ln()’<br/>            プロパティ参照 (ホストがサポートするプロパティ)<br/>            <br/>            例: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>            読み取り/書き込み **str**. |

### 参照
* モジュール [`aspose.slides.animation`](/slides/python-net/ja/aspose.slides.animation)
* ライブラリ [`Aspose.Slides`](/slides/python-net)