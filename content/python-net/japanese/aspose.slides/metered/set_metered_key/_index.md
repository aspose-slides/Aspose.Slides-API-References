---
title: set_metered_key method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/metered/set_metered_key/
weight: 60
---
## set_metered_key(self, public_key, private_key) {#str-str}
メータリングされた公開鍵と秘密鍵を設定します。
            メータリングライセンスを購入した場合、アプリケーションの起動時にこの API を呼び出す必要があります。通常、これだけで十分です。
            しかし、消費データのアップロードが常に失敗し、24 時間を超えると、ライセンスは評価ステータスに設定されます。
            このような事態を防ぐために、定期的にライセンスステータスを確認し、評価ステータスである場合は再度この API を呼び出してください。

```python
def set_metered_key(self, public_key, private_key):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| public_key | **str** | 公開鍵 |
| private_key | **str** | 秘密鍵 |

### 参照
* クラス [`Metered`](/slides/python-net/ja/aspose.slides/metered)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)