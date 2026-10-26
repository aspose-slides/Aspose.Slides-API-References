---
title: MasterNotesSlideHeaderFooterManager class
second_title: Aspose.Slides の Python 用 .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/masternotesslideheaderfootermanager/
---
## MasterNotesSlideHeaderFooterManager クラス

Represents manager which holds behavior of the master notes slide footer, date-time, page number placeholders and all child placeholders.
            Child placeholders mean placeholders are contained on depending notes slides.
            Depending notes slides use and depend on master notes slide.

**継承:**[`MasterNotesSlideHeaderFooterManager`](/slides/python-net/ja/aspose.slides/masternotesslideheaderfootermanager) → [`BaseHandoutNotesSlideHeaderFooterManager`](/slides/python-net/ja/aspose.slides/basehandoutnotesslideheaderfootermanager) → [`BaseSlideHeaderFooterManager`](/slides/python-net/ja/aspose.slides/baseslideheaderfootermanager) → [`BaseHeaderFooterManager`](/slides/python-net/ja/aspose.slides/baseheaderfootermanager)

The MasterNotesSlideHeaderFooterManager type exposes the following members:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`is_footer_visible`](/slides/python-net/ja/aspose.slides/masternotesslideheaderfootermanager/is_footer_visible/) | フッタープレースホルダーが存在することを示す値を取得します。<br/>            読み取り **bool**。 |
| [`is_slide_number_visible`](/slides/python-net/ja/aspose.slides/masternotesslideheaderfootermanager/is_slide_number_visible/) | ページ番号プレースホルダーが存在することを示す値を取得します。<br/>            読み取り**bool**。 |
| [`is_date_time_visible`](/slides/python-net/ja/aspose.slides/masternotesslideheaderfootermanager/is_date_time_visible/) | 日時プレースホルダーが存在することを示す値を取得します。<br/>            読み取り**bool**。 |
| [`is_header_visible`](/slides/python-net/ja/aspose.slides/masternotesslideheaderfootermanager/is_header_visible/) | ヘッダープレースホルダーが存在することを示す値を取得します。<br/>            読み取り **bool**。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`set_footer_visibility(self, is_visible)`](/slides/python-net/ja/aspose.slides/masternotesslideheaderfootermanager/set_footer_visibility/#bool) | スライドのフッタープレースホルダーの表示状態を変更します。 |
| [`set_slide_number_visibility(self, is_visible)`](/slides/python-net/ja/aspose.slides/masternotesslideheaderfootermanager/set_slide_number_visibility/#bool) | スライドのページ番号プレースホルダーの表示状態を変更します。 |
| [`set_date_time_visibility(self, is_visible)`](/slides/python-net/ja/aspose.slides/masternotesslideheaderfootermanager/set_date_time_visibility/#bool) | スライドの日時プレースホルダーの表示状態を変更します。 |
| [`set_footer_text(self, text)`](/slides/python-net/ja/aspose.slides/masternotesslideheaderfootermanager/set_footer_text/#str) | スライドのフッタープレースホルダーにテキストを設定します。 |
| [`set_date_time_text(self, text)`](/slides/python-net/ja/aspose.slides/masternotesslideheaderfootermanager/set_date_time_text/#str) | スライドの日時プレースホルダーにテキストを設定します。 |
| [`set_header_visibility(self, is_visible)`](/slides/python-net/ja/aspose.slides/masternotesslideheaderfootermanager/set_header_visibility/#bool) | スライドのヘッダープレースホルダーの表示状態を変更します。 |
| [`set_header_text(self, text)`](/slides/python-net/ja/aspose.slides/masternotesslideheaderfootermanager/set_header_text/#str) | スライドのヘッダープレースホルダーにテキストを設定します。 |
| [`set_header_and_child_headers_visibility(self, is_visible)`](/slides/python-net/ja/aspose.slides/masternotesslideheaderfootermanager/set_header_and_child_headers_visibility/#bool) | マスターノートスライドのヘッダープレースホルダーとすべての子ヘッダープレースホルダーの表示状態を変更します。<br/>            子プレースホルダーは、依存ノートスライドに含まれるプレースホルダーを意味します。<br/>            依存ノートスライドはマスターノートスライドを使用し、依存します。 |
| [`set_header_and_child_headers_text(self, text)`](/slides/python-net/ja/aspose.slides/masternotesslideheaderfootermanager/set_header_and_child_headers_text/#str) | マスターノートスライドのヘッダープレースホルダーとすべての子ヘッダープレースホルダーにテキストを設定します。<br/>            子プレースホルダーは、依存ノートスライドに含まれるプレースホルダーを意味します。<br/>            依存ノートスライドはマスターノートスライドを使用し、依存します。 |
| [`set_footer_and_child_footers_visibility(self, is_visible)`](/slides/python-net/ja/aspose.slides/masternotesslideheaderfootermanager/set_footer_and_child_footers_visibility/#bool) | マスタースライドのフッタープレースホルダーとすべての子フッタープレースホルダーの表示状態を変更します。<br/>            子プレースホルダーは、依存ノートスライドに含まれるプレースホルダーを意味します。<br/>            依存ノートスライドはマスターノートスライドを使用し、依存します。 |
| [`set_slide_number_and_child_slide_numbers_visibility(self, is_visible)`](/slides/python-net/ja/aspose.slides/masternotesslideheaderfootermanager/set_slide_number_and_child_slide_numbers_visibility/#bool) | マスタースライドのページ番号プレースホルダーとすべての子ページ番号プレースホルダーの表示状態を変更します。<br/>            子プレースホルダーは、依存ノートスライドに含まれるプレースホルダーを意味します。<br/>            依存ノートスライドはマスターノートスライドを使用し、依存します。 |
| [`set_date_time_and_child_date_times_visibility(self, is_visible)`](/slides/python-net/ja/aspose.slides/masternotesslideheaderfootermanager/set_date_time_and_child_date_times_visibility/#bool) | マスタースライドの日時プレースホルダーとすべての子日時プレースホルダーの表示状態を変更します。<br/>            子プレースホルダーは、依存ノートスライドに含まれるプレースホルダーを意味します。<br/>            依存ノートスライドはマスターノートスライドを使用し、依存します。 |
| [`set_footer_and_child_footers_text(self, text)`](/slides/python-net/ja/aspose.slides/masternotesslideheaderfootermanager/set_footer_and_child_footers_text/#str) | マスタースライドのフッタープレースホルダーとすべての子フッタープレースホルダーにテキストを設定します。<br/>            子プレースホルダーは、依存ノートスライドに含まれるプレースホルダーを意味します。<br/>            依存ノートスライドはマスターノートスライドを使用し、依存します。 |
| [`set_date_time_and_child_date_times_text(self, text)`](/slides/python-net/ja/aspose.slides/masternotesslideheaderfootermanager/set_date_time_and_child_date_times_text/#str) | マスタースライドの日時プレースホルダーとすべての子日時プレースホルダーにテキストを設定します。<br/>            子プレースホルダーは、依存ノートスライドに含まれるプレースホルダーを意味します。<br/>            依存ノートスライドはマスターノートスライドを使用し、依存します。 |

### 参照
* クラス [`BaseHandoutNotesSlideHeaderFooterManager`](/slides/python-net/ja/aspose.slides/basehandoutnotesslideheaderfootermanager)
* クラス [`BaseHeaderFooterManager`](/slides/python-net/ja/aspose.slides/baseheaderfootermanager)
* クラス [`BaseSlideHeaderFooterManager`](/slides/python-net/ja/aspose.slides/baseslideheaderfootermanager)
* クラス [`MasterNotesSlideHeaderFooterManager`](/slides/python-net/ja/aspose.slides/masternotesslideheaderfootermanager)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)