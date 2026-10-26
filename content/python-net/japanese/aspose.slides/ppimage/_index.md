---
title: PPImage class
second_title: Aspose.Slides の Python 用 .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ppimage/
---
## PPImage クラス

プレゼンテーション内の画像を表します。

PPImage 型は次のメンバーを公開します。

## プロパティ

| Property | Description |
| :- | :- |
| [`binary_data`](/slides/python-net/ja/aspose.slides/ppimage/binary_data/) | 画像データのコピーを取得します。<br/>            読み取り専用 **int**[]. |
| [`image`](/slides/python-net/ja/aspose.slides/ppimage/image/) | 画像のコピーを取得します。<br/>            読み取り専用 [`IImage`](/slides/python-net/ja/aspose.slides/iimage). |
| [`svg_image`](/slides/python-net/ja/aspose.slides/ppimage/svg_image/) | ISvgImage オブジェクト [`ISvgImage`](/slides/python-net/ja/aspose.slides/isvgimage) を取得または設定します |
| [`content_type`](/slides/python-net/ja/aspose.slides/ppimage/content_type/) | 画像の MIME タイプを [`PPImage.binary_data`](/slides/python-net/ja/aspose.slides/ppimage/binary_data) でエンコードして取得します。<br/>            読み取り専用 **str**. |
| [`width`](/slides/python-net/ja/aspose.slides/ppimage/width/) | 画像の幅を取得します。<br/>            読み取り専用 **int**. |
| [`height`](/slides/python-net/ja/aspose.slides/ppimage/height/) | 画像の高さを取得します。<br/>            読み取り専用 **int**. |
| [`x`](/slides/python-net/ja/aspose.slides/ppimage/x/) | 画像の X オフセットを取得します。<br/>            読み取り専用 **int**. |
| [`y`](/slides/python-net/ja/aspose.slides/ppimage/y/) | 画像の Y オフセットを取得します。<br/>            読み取り専用 **int**. |

## メソッド

| Method | Description |
| :- | :- |
| [`replace_image(self, new_image_data)`](/slides/python-net/ja/aspose.slides/ppimage/replace_image/#bytes) | 画像データを置き換えます。<br/>            newImageData パラメータが None の場合、新しい画像のデータです。 |
| [`replace_image(self, new_image)`](/slides/python-net/ja/aspose.slides/ppimage/replace_image/#iimage) | 画像データを置き換えます。注意: 画像がメタファイルの場合、ラスタライズされます。代わりに ReplaceImage(byte[]) を使用してください。<br/>            newImage パラメータが None の場合、新しい画像です。 |
| [`replace_image(self, new_image)`](/slides/python-net/ja/aspose.slides/ppimage/replace_image/#ippimage) | 画像データを置き換えます。<br/>            newImage パラメータが None の場合、新しい IPPImage です。 |


### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)