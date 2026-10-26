---
title: IResourceLoadingArgs class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/iresourceloadingargs/
---
## IResourceLoadingArgs クラス

外部リソースの読み込み引数のインターフェイスです。

IResourceLoadingArgs 型は次のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`original_uri`](/slides/python-net/ja/aspose.slides/iresourceloadingargs/original_uri/) | インポートされたプレゼンテーションで指定されたリソースの元の URI。 |
| [`uri`](/slides/python-net/ja/aspose.slides/iresourceloadingargs/uri/) | リソースの URI で、**Aspose.Slides.IResourceLoadingCallback.ResourceLoading(Aspose.Slide** が返す [`ResourceLoadingAction.DEFAULT`](/slides/python-net/ja/aspose.slides/resourceloadingaction/DEFAULT) の場合にダウンロードに使用されます。<br/>            最初はリソースの元の URI に設定されていますが、任意の値に再定義できます。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`set_data(self, data)`](/slides/python-net/ja/aspose.slides/iresourceloadingargs/set_data/#bytes) | リソースのユーザー提供データを設定します。**Aspose.Slides.IResourceLoadingCallback.ResourceLoading(Aspose.Slide** が<br/>            [`ResourceLoadingAction.USER_PROVIDED`](/slides/python-net/ja/aspose.slides/resourceloadingaction/USER_PROVIDED) を返す場合に使用されます。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)