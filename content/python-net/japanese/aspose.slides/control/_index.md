---
title: Control class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/control/
---
## Control クラス

ActiveX コントロールを表します。

Control 型は次のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`persistence`](/slides/python-net/ja/aspose.slides/control/persistence/) | ActiveX コントロールのプロパティを保存するために使用されるメソッドを取得します。<br/>            読み取り専用 [`PersistenceType`](/slides/python-net/ja/aspose.slides/persistencetype)。 |
| [`name`](/slides/python-net/ja/aspose.slides/control/name/) | このコントロールの名前を取得または設定します。<br/>            読み書き **str**。 |
| [`class_id`](/slides/python-net/ja/aspose.slides/control/class_id/) | このコントロールのクラス ID を取得します。<br/>            読み取り専用 **System.Guid**。 |
| [`substitute_picture_format`](/slides/python-net/ja/aspose.slides/control/substitute_picture_format/) | Control 画像塗りつぶしプロパティ オブジェクトを返します。<br/>            読み取り専用 [`IPictureFillFormat`](/slides/python-net/ja/aspose.slides/ipicturefillformat)。 |
| [`frame`](/slides/python-net/ja/aspose.slides/control/frame/) | コントロールのフレームを取得または設定します。<br/>            読み書き [`IShapeFrame`](/slides/python-net/ja/aspose.slides/ishapeframe)。 |
| [`properties`](/slides/python-net/ja/aspose.slides/control/properties/) | ActiveX プロパティのコレクションを返します。<br/>            注: Aspose.Slides は XML ベースの ActiveX プロパティのみをサポートします。プロパティがバイナリ形式で保存されている場合、このプロパティは None を返します。<br/>            読み取り専用 [`IControlPropertiesCollection`](/slides/python-net/ja/aspose.slides/icontrolpropertiescollection)。 |
| [`active_x_control_binary`](/slides/python-net/ja/aspose.slides/control/active_x_control_binary/) | PersistStream、PersistStreamInit、または PersistStorage のいずれかの永続化メソッドが使用される場合の ActiveX コントロールの永続性を指定します。 |
| [`slide`](/slides/python-net/ja/aspose.slides/control/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides/control/presentation/) |  |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)