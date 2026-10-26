---
title: check_write_protection method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/protectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
プレゼンテーションが変更に対してパスワードで保護されているかどうかを判断します。

### Returns
パスワードが有効な場合は True、そうでない場合は false。

```python
def check_write_protection(self, password):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| password | **str** | チェック用のパスワード。 |

### 備考
1. このメソッドを呼び出す前に [`ProtectionManager.is_write_protected`](/slides/python-net/ja/aspose.slides/protectionmanager/is_write_protected) プロパティを確認すべきです。
2. パスワードが None または空の場合、このメソッドは false を返します。

### 参照
* クラス [`ProtectionManager`](/slides/python-net/ja/aspose.slides/protectionmanager)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)