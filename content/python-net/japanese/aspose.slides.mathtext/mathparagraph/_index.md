---
title: MathParagraph class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathparagraph/
---
## MathParagraph クラス

Mathematical paragraph that is a container for mathematical blocks (IMathBlock)

The MathParagraph type exposes the following members:

## コンストラクタ

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathparagraph/__init__/#) | MathParagraph クラスの新しいインスタンスを初期化します。 |
| [`__init__(self, math_block)`](/slides/python-net/ja/aspose.slides.mathtext/mathparagraph/__init__/#imathblock) | MathParagraph クラスの新しいインスタンスを初期化します。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`justification`](/slides/python-net/ja/aspose.slides.mathtext/mathparagraph/justification/) | 段落の配置 <br/>            Default value: CenteredAsGroup |
| [`count`](/slides/python-net/ja/aspose.slides.mathtext/mathparagraph/count/) | コレクションに実際に含まれる要素数を取得します。<br/>            読み取り専用 **int**. |

指定されたインデックスの項目を取得します。
            Read-only [`IMathBlock`](/slides/python-net/ja/aspose.slides.mathtext/imathblock).

## インデクサ

| 名前 | 説明 |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides.mathtext/mathparagraph/__getitem__/) | 取得する項目のゼロベースインデックス |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`clear(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathparagraph/clear/#) | コレクションからすべての要素を削除します。 |
| [`add(self, math_block)`](/slides/python-net/ja/aspose.slides.mathtext/mathparagraph/add/#imathblock) | IMathBlock をコレクションの末尾に追加します。 |
| [`remove(self, math_block)`](/slides/python-net/ja/aspose.slides.mathtext/mathparagraph/remove/#imathblock) | コレクションから特定のオブジェクトの最初の出現を削除します/>。 |
| [`contains(self, math_block)`](/slides/python-net/ja/aspose.slides.mathtext/mathparagraph/contains/#imathblock) | コレクションが特定の値を含むかどうかを判断します。 |
| [`index_of(self, math_block)`](/slides/python-net/ja/aspose.slides.mathtext/mathparagraph/index_of/#imathblock) | コレクション内の特定の IMathBlock のインデックスを決定します。 |
| [`insert(self, index, math_block)`](/slides/python-net/ja/aspose.slides.mathtext/mathparagraph/insert/#int-imathblock) | 指定されたインデックスに IMathBlock をコレクションに挿入します。 |
| [`remove_at(self, index)`](/slides/python-net/ja/aspose.slides.mathtext/mathparagraph/remove_at/#int) | コレクションの指定されたインデックスの項目を削除します。 |
| [`write_as_math_ml(self, stream)`](/slides/python-net/ja/aspose.slides.mathtext/mathparagraph/write_as_math_ml/#iorawiobase) | この [`MathParagraph`](/slides/python-net/ja/aspose.slides.mathtext/mathparagraph) の内容を MathML として保存します |
| [`to_latex(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathparagraph/to_latex/#) | LaTeX 形式の数式を取得します |

### 参照
* クラス [`IMathBlock`](/slides/python-net/ja/aspose.slides.mathtext/imathblock)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)