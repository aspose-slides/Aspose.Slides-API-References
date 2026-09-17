---
title: Zip64Mode enumeration
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/zip64mode/
---
## Zip64Mode 列挙型

OpenXML ファイルで ZIP64 形式拡張を使用するタイミングを指定します。

Zip64Mode 型は以下のメンバーを公開します。

## フィールド

| フィールド | 説明 |
| :- | :- |
| NEVER | ZIP64 形式拡張を使用しません。 |
| IF_NECESSARY | 必要に応じて ZIP64 形式拡張を使用します。 |
| ALWAYS | 常に ZIP64 形式拡張を使用します。 |

### 備考

OpenXML ファイルは ZIP アーカイブで、ファイルの非圧縮サイズ、圧縮サイズ、アーカイブ全体のサイズに 4 GB (2^32 バイト) の制限があり、  
            さらにアーカイブ内のファイル数は 65,535 (2^16-1) 件に制限されます。  
            ZIP64 形式拡張により、制限は 2^64 に拡大されます。

### 参照
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)