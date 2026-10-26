---
title: check_write_protection method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/presentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
書き込み保護されたプレゼンテーションの変更用 password が正しいかどうかをチェックします。

### 戻り値

プレゼンテーションが書き込み保護され、かつ password が正しい場合は True、そうでない場合は False を返します。



```python
def check_write_protection(self, password):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| password | **str** | チェックする password。 |

### 備考

1. このメソッドを呼び出す前に [`PresentationInfo.is_write_protected`](/slides/python-net/ja/aspose.slides/presentationinfo/is_write_protected) プロパティをチェックすべきです。
2. password が None または空の場合、このメソッドは false を返します。

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### 参照
* クラス [`PresentationInfo`](/slides/python-net/ja/aspose.slides/presentationinfo)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)