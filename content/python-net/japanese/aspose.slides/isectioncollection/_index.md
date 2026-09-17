---
title: ISectionCollection class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/isectioncollection/
---
## ISectionCollection クラス

セクションのコレクションを表します。

ISectionCollection 型は以下のメンバーを公開します。

指定されたインデックスの要素を取得します。
            読み取り専用 [`ISection`](/slides/python-net/ja/aspose.slides/isection)。

## インデクサ

| 名前 | 説明 |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides/isectioncollection/__getitem__/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`add_section(self, name, started_from_slide)`](/slides/python-net/ja/aspose.slides/isectioncollection/add_section/#str-islide) | 特定のスライドから開始される新しいセクションを追加します。 |
| [`add_empty_section(self, name, index)`](/slides/python-net/ja/aspose.slides/isectioncollection/add_empty_section/#str-int) | コレクションの指定された位置に空のセクションを追加します。 |
| [`remove_section_with_slides(self, section)`](/slides/python-net/ja/aspose.slides/isectioncollection/remove_section_with_slides/#isection) | セクションとその中に含まれるスライドを削除します。 |
| [`remove_section(self, section)`](/slides/python-net/ja/aspose.slides/isectioncollection/remove_section/#isection) | セクションを削除します。セクションに含まれるスライドは前のセクションにマージされます。 |
| [`reorder_section_with_slides(self, section, index)`](/slides/python-net/ja/aspose.slides/isectioncollection/reorder_section_with_slides/#isection-int) | セクションとそのスライドをコレクション内の指定された位置に移動します。 |
| [`append_empty_section(self, name)`](/slides/python-net/ja/aspose.slides/isectioncollection/append_empty_section/#str) | コレクションの末尾に空のセクションを追加します。 |
| [`index_of(self, section)`](/slides/python-net/ja/aspose.slides/isectioncollection/index_of/#isection) | コレクション内の指定されたセクションのインデックスを返します。 |
| [`clear(self)`](/slides/python-net/ja/aspose.slides/isectioncollection/clear/#) | コレクションからすべてのセクションを削除します。 |

### 参照
* クラス [`ISection`](/slides/python-net/ja/aspose.slides/isection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)