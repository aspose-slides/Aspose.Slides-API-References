---
title: delete_embedded_binary_objects property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/loadoptions/delete_embedded_binary_objects/
weight: 70
---
## delete_embedded_binary_objects プロパティ
プレゼンテーションの読み込み中に、Aspose.Slides がすべての埋め込みバイナリオブジェクトを削除するかどうかを決定します。

埋め込みバイナリオブジェクトの種類:

* VBA Project [`IPresentation.vba_project`](/slides/python-net/ja/aspose.slides/ipresentation/vba_project)
* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/ja/aspose.slides/ioleembeddeddatainfo/embedded_file_data)
* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/ja/aspose.slides/icontrol/active_x_control_binary)

            読み書き **bool**.

### 備考

デフォルトは **false** .

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
* class [`LoadOptions`](/slides/python-net/ja/aspose.slides/loadoptions)
* module [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)