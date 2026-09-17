---
title: check_password method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/presentationinfo/check_password/
weight: 10
---
## check_password(self, password) {#str}
プレゼンテーションがオープンパスワードで保護されている場合に、パスワードが正しいかどうかを確認します。

### 戻り値

True if the presentation is protected with open password and the password is correct and false otherwise.



```python
def check_password(self, password):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| password | **str** | 確認するパスワードです。 |

### 備考

パスワードが None または空の場合、このメソッドは false を返します。

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |
| **RuntimeError(Proxy error(NotSupportedException))** |  |



### 参照
* クラス [`PresentationInfo`](/slides/python-net/ja/aspose.slides/presentationinfo)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)