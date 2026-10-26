---
title: IParagraphFormat class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/iparagraphformat/
---
## IParagraphFormat クラス

このクラスは段落書式プロパティを含みます。[`IParagraphFormatEffectiveData`](/slides/python-net/ja/aspose.slides/iparagraphformateffectivedata) とは異なり、このクラスのすべてのプロパティは書き込み可能です。

The IParagraphFormat type exposes the following members:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`bullet`](/slides/python-net/ja/aspose.slides/iparagraphformat/bullet/) | 段落の箇条書き形式を返します。<br/>            読み取り専用 [`IBulletFormat`](/slides/python-net/ja/aspose.slides/ibulletformat). |
| [`depth`](/slides/python-net/ja/aspose.slides/iparagraphformat/depth/) | 段落の深さを取得または設定します。<br/>            値 0 は未定義の値を意味します。<br/>            読み取り/書き込み **int**. |
| [`alignment`](/slides/python-net/ja/aspose.slides/iparagraphformat/alignment/) | 段落内のテキスト配置を取得または設定します（継承なし）。<br/>            読み取り/書き込み [`TextAlignment`](/slides/python-net/ja/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/ja/aspose.slides/iparagraphformat/space_within/) | 段落の基準線間の間隔を取得または設定します。正の値はパーセンテージ、負の値はポイント単位のサイズを意味します。継承は適用されません。<br/>            読み取り/書き込み **float**. |
| [`space_before`](/slides/python-net/ja/aspose.slides/iparagraphformat/space_before/) | 段落の最初の行の前の余白を取得または設定します（継承なし）。<br/>            正の値はフォントサイズのパーセンテージで余白を指定し、負の値はポイント単位で余白サイズを指定します。<br/>            読み取り/書き込み **float**. |
| [`space_after`](/slides/python-net/ja/aspose.slides/iparagraphformat/space_after/) | 段落の最後の行の後の余白を取得または設定します（継承なし）。<br/>            正の値はフォントサイズのパーセンテージで余白を指定し、負の値はポイント単位で余白サイズを指定します。<br/>            読み取り/書き込み **float**. |
| [`east_asian_line_break`](/slides/python-net/ja/aspose.slides/iparagraphformat/east_asian_line_break/) | 段落で東アジアの改行が使用されるかどうかを決定します。継承は適用されません。<br/>            読み取り/書き込み [`NullableBool`](/slides/python-net/ja/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/ja/aspose.slides/iparagraphformat/right_to_left/) | 段落で右から左への書き順が使用されるかどうかを決定します。継承は適用されません。<br/>            読み取り/書き込み [`NullableBool`](/slides/python-net/ja/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/ja/aspose.slides/iparagraphformat/latin_line_break/) | 段落でラテン文字の改行が使用されるかどうかを決定します。継承は適用されません。<br/>            読み取り/書き込み [`NullableBool`](/slides/python-net/ja/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/ja/aspose.slides/iparagraphformat/hanging_punctuation/) | 段落でハンギング句読点が使用されるかどうかを決定します。継承は適用されません。<br/>            読み取り/書き込み [`NullableBool`](/slides/python-net/ja/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/ja/aspose.slides/iparagraphformat/margin_left/) | 段落の左余白を取得または設定します（継承なし）。<br/>            読み取り/書き込み **float**. |
| [`margin_right`](/slides/python-net/ja/aspose.slides/iparagraphformat/margin_right/) | 段落の右余白を取得または設定します（継承なし）。<br/>            読み取り/書き込み **float**. |
| [`indent`](/slides/python-net/ja/aspose.slides/iparagraphformat/indent/) | 段落の最初の行インデント/ハンギングインデントを取得または設定します（継承なし）。ハンギングインデントは負の値で定義できます。<br/>            読み取り/書き込み **float**. |
| [`default_tab_size`](/slides/python-net/ja/aspose.slides/iparagraphformat/default_tab_size/) | デフォルトのタブ幅を取得または設定します（継承なし）。<br/>            読み取り/書き込み **float**. |
| [`tabs`](/slides/python-net/ja/aspose.slides/iparagraphformat/tabs/) | 段落のタブ設定を返します。継承は適用されません。<br/>            読み取り専用 [`ITabCollection`](/slides/python-net/ja/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/ja/aspose.slides/iparagraphformat/font_alignment/) | 段落でのフォント配置を取得または設定します（継承なし）。<br/>            読み取り/書き込み [`FontAlignment`](/slides/python-net/ja/aspose.slides/fontalignment). |
| [`default_portion_format`](/slides/python-net/ja/aspose.slides/iparagraphformat/default_portion_format/) | 段落のデフォルトの部分フォーマットを返します。継承は適用されません。<br/>            読み取り専用 [`IPortionFormat`](/slides/python-net/ja/aspose.slides/iportionformat). |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/ja/aspose.slides/iparagraphformat/get_effective/#) | 継承が適用された有効な段落書式データを取得します。 |

### 備考

このクラスは、特定の段落に対して定義された段落書式プロパティを取得および操作するために使用されます。つまり、値を取得するときに継承が適用されないため、ほとんどの場合「未定義」の意味の値が返されます。

継承された有効な書式パラメータ値を取得するには、[`IParagraphFormat.get_effective`](/slides/python-net/ja/aspose.slides/iparagraphformat/get_effective) メソッドを使用する必要があります。このメソッドは [`IParagraphFormatEffectiveData`](/slides/python-net/ja/aspose.slides/iparagraphformateffectivedata) インスタンスを返します。

### 関連項目
* クラス [`IParagraphFormatEffectiveData`](/slides/python-net/ja/aspose.slides/iparagraphformateffectivedata)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)