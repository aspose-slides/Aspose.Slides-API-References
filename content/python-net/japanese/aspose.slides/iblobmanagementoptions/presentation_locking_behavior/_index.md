---
title: presentation_locking_behavior property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/
weight: 30
---
## presentation_locking_behavior プロパティ
このプロパティは、Presentation クラスのインスタンスがインスタンスの存続期間中にソース（ファイルまたはストリーム）の所有者になれるかどうかを定義します。
インスタンスが所有者である場合、ソースがロックされます。これにより、BLOB の操作時のメモリ使用量とパフォーマンスが向上しますが、ソース（ストリームまたはファイル）は Presentation のインスタンス存続期間中に変更できません。
以下は例です：

### 定義:
```python
@property
def presentation_locking_behavior(self):
    ...

@presentation_locking_behavior.setter
def presentation_locking_behavior(self, value):
    ...
```

### 参照
* クラス [`IBlobManagementOptions`](/slides/python-net/ja/aspose.slides/iblobmanagementoptions)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)