---
title: LayoutSlideHeaderFooterManager class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/layoutslideheaderfootermanager/
---
## LayoutSlideHeaderFooterManager クラス

Represents manager which holds behavior of the layout slide footer, date-time, page number placeholders and all child placeholders.
            Child placeholders mean placeholders are contained on depending slides.
            Depending slides use and depend on layout slide.

**継承:**[`LayoutSlideHeaderFooterManager`](/slides/python-net/ja/aspose.slides/layoutslideheaderfootermanager) → [`BaseSlideHeaderFooterManager`](/slides/python-net/ja/aspose.slides/baseslideheaderfootermanager) → [`BaseHeaderFooterManager`](/slides/python-net/ja/aspose.slides/baseheaderfootermanager)

LayoutSlideHeaderFooterManager 型は以下のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`is_footer_visible`](/slides/python-net/ja/aspose.slides/layoutslideheaderfootermanager/is_footer_visible/) | フッタープレースホルダーが存在することを示す値を取得します。<br/>            読み取り **bool**. |
| [`is_slide_number_visible`](/slides/python-net/ja/aspose.slides/layoutslideheaderfootermanager/is_slide_number_visible/) | ページ番号プレースホルダーが存在することを示す値を取得します。<br/>            読み取り**bool**. |
| [`is_date_time_visible`](/slides/python-net/ja/aspose.slides/layoutslideheaderfootermanager/is_date_time_visible/) | 日時プレースホルダーが存在することを示す値を取得します。<br/>            読み取り**bool**. |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`set_footer_visibility(self, is_visible)`](/slides/python-net/ja/aspose.slides/layoutslideheaderfootermanager/set_footer_visibility/#bool) | スライドフッタープレースホルダーの表示状態を変更します。 |
| [`set_slide_number_visibility(self, is_visible)`](/slides/python-net/ja/aspose.slides/layoutslideheaderfootermanager/set_slide_number_visibility/#bool) | スライドページ番号プレースホルダーの表示状態を変更します。 |
| [`set_date_time_visibility(self, is_visible)`](/slides/python-net/ja/aspose.slides/layoutslideheaderfootermanager/set_date_time_visibility/#bool) | スライド日時プレースホルダーの表示状態を変更します。 |
| [`set_footer_text(self, text)`](/slides/python-net/ja/aspose.slides/layoutslideheaderfootermanager/set_footer_text/#str) | スライドフッタープレースホルダーにテキストを設定します。 |
| [`set_date_time_text(self, text)`](/slides/python-net/ja/aspose.slides/layoutslideheaderfootermanager/set_date_time_text/#str) | スライド日時プレースホルダーにテキストを設定します。 |
| [`set_footer_and_child_footers_visibility(self, is_visible)`](/slides/python-net/ja/aspose.slides/layoutslideheaderfootermanager/set_footer_and_child_footers_visibility/#bool) | レイアウトスライドのフッタープレースホルダーとすべての子フッタープレースホルダーの表示状態を変更します。<br/>            子プレースホルダーは、依存スライドに含まれるプレースホルダーを意味します。<br/>            依存スライドはマスタースライドを使用し、依存します。 |
| [`set_slide_number_and_child_slide_numbers_visibility(self, is_visible)`](/slides/python-net/ja/aspose.slides/layoutslideheaderfootermanager/set_slide_number_and_child_slide_numbers_visibility/#bool) | レイアウトスライドのページ番号プレースホルダーとすべての子ページ番号プレースホルダーの表示状態を変更します。<br/>            子プレースホルダーは、依存スライドに含まれるプレースホルダーを意味します。<br/>            依存スライドはレイアウトスライドを使用し、依存します。 |
| [`set_date_time_and_child_date_times_visibility(self, is_visible)`](/slides/python-net/ja/aspose.slides/layoutslideheaderfootermanager/set_date_time_and_child_date_times_visibility/#bool) | レイアウトスライドの日時プレースホルダーとすべての子日時プレースホルダーの表示状態を変更します。<br/>            子プレースホルダーは、依存スライドに含まれるプレースホルダーを意味します。<br/>            依存スライドはレイアウトスライドを使用し、依存します。 |
| [`set_footer_and_child_footers_text(self, text)`](/slides/python-net/ja/aspose.slides/layoutslideheaderfootermanager/set_footer_and_child_footers_text/#str) | レイアウトスライドのフッタープレースホルダーとすべての子フッタープレースホルダーにテキストを設定します。<br/>            子プレースホルダーは、依存スライドに含まれるプレースホルダーを意味します。<br/>            依存スライドはレイアウトスライドを使用し、依存します。 |
| [`set_date_time_and_child_date_times_text(self, text)`](/slides/python-net/ja/aspose.slides/layoutslideheaderfootermanager/set_date_time_and_child_date_times_text/#str) | レイアウトスライドの日時プレースホルダーとすべての子日時プレースホルダーにテキストを設定します。<br/>            子プレースホルダーは、依存スライドに含まれるプレースホルダーを意味します。<br/>            依存スライドはレイアウトスライドを使用し、依存します。 |

### 参照
* クラス [`BaseHeaderFooterManager`](/slides/python-net/ja/aspose.slides/baseheaderfootermanager)
* クラス [`BaseSlideHeaderFooterManager`](/slides/python-net/ja/aspose.slides/baseslideheaderfootermanager)
* クラス [`LayoutSlideHeaderFooterManager`](/slides/python-net/ja/aspose.slides/layoutslideheaderfootermanager)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)