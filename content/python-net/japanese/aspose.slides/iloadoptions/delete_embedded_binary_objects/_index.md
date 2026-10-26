---
title: delete_embedded_binary_objects property
second_title: Aspose.Slides for Python 用 .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/iloadoptions/delete_embedded_binary_objects/
weight: 60
---
## delete_embedded_binary_objects プロパティ
プレゼンテーションのロード中に Aspose.Slides がすべての埋め込みバイナリ オブジェクトを削除するかどうかを決定します。

埋め込みバイナリ オブジェクトのタイプ:

* VBA Project [`IPresentation.vba_project`](/slides/python-net/ja/aspose.slides/ipresentation/vba_project)
* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/ja/aspose.slides/ioleembeddeddatainfo/embedded_file_data)
* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/ja/aspose.slides/icontrol/active_x_control_binary)

読み取り/書き込み **bool**.

### 備考

デフォルトは **false** です。

### 定義:
```python
@property
def delete_embedded_binary_objects(self):
    ...

@delete_embedded_binary_objects.setter
def delete_embedded_binary_objects(self, value):
    ...
```

### 参照
* クラス [`ILoadOptions`](/slides/python-net/ja/aspose.slides/iloadoptions)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)