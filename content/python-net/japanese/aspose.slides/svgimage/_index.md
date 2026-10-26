---
title: SvgImage class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/svgimage/
---
## SvgImage クラス

SVG画像を表します。

SvgImage型は以下のメンバーを公開します。

## コンストラクタ

| Constructor | Description |
| :- | :- |
| [`__init__(self, data)`](/slides/python-net/ja/aspose.slides/svgimage/__init__/#bytes) | 新しい SvgImage オブジェクトを作成します。 |
| [`__init__(self, svg_content)`](/slides/python-net/ja/aspose.slides/svgimage/__init__/#str) | 新しい SvgImage オブジェクトを作成します。 |
| [`__init__(self, stream)`](/slides/python-net/ja/aspose.slides/svgimage/__init__/#iorawiobase) | 新しい SvgImage オブジェクトを作成します。 |
| [`__init__(self, data, external_res_resolver, base_uri)`](/slides/python-net/ja/aspose.slides/svgimage/__init__/#bytes-asposeslidesimportingiexternalresourceresolver-str) | 新しい SvgImage オブジェクトを作成します。 |
| [`__init__(self, svg_content, external_res_resolver, base_uri)`](/slides/python-net/ja/aspose.slides/svgimage/__init__/#str-asposeslidesimportingiexternalresourceresolver-str) | 新しい SvgImage オブジェクトを作成します。 |
| [`__init__(self, stream, external_res_resolver, base_uri)`](/slides/python-net/ja/aspose.slides/svgimage/__init__/#iorawiobase-asposeslidesimportingiexternalresourceresolver-str) | 新しい SvgImage オブジェクトを作成します。 |

## プロパティ

| Property | Description |
| :- | :- |
| [`svg_data`](/slides/python-net/ja/aspose.slides/svgimage/svg_data/) | SVGデータを返します。<br/> 読み取り専用 **int**[]。 |
| [`external_resource_resolver`](/slides/python-net/ja/aspose.slides/svgimage/external_resource_resolver/) | Svgドキュメントのインポート時に外部リソースを解決するために使用されるコールバックインターフェイスを返します。<br/> 読み取り専用 **IExternalResourceResolver**。 |
| [`base_uri`](/slides/python-net/ja/aspose.slides/svgimage/base_uri/) | 指定された Svg のベースURIを返します。相対リンクの解決に使用されます。<br/> 読み取り専用 **str**。 |
| [`svg_content`](/slides/python-net/ja/aspose.slides/svgimage/svg_content/) | SVGコンテンツを返します。<br/> 読み取り専用 **str**。 |

## メソッド

| Method | Description |
| :- | :- |
| [`write_as_emf(self, stream)`](/slides/python-net/ja/aspose.slides/svgimage/write_as_emf/#iorawiobase) | SVGイメージをEMFファイルとして保存します。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)