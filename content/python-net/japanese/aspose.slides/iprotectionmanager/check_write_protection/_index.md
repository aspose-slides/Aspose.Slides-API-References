---
title: check_write_protection method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/iprotectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
プレゼンテーションが変更保護されたパスワードで保護されているかどうかを判定します。

### 戻り値
パスワードが有効な場合は true、そうでない場合は false。

```python
def check_write_protection(self, password):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| password | **str** | チェック用のパスワード。 |

### 備考
1. このメソッドを呼び出す前に [`IProtectionManager.is_write_protected`](/slides/python-net/ja/aspose.slides/iprotectionmanager/is_write_protected) プロパティを確認してください。
2. パスワードが None または空の場合、このメソッドは false を返します。

### 関連項目
* クラス [`IProtectionManager`](/slides/python-net/ja/aspose.slides/iprotectionmanager)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)