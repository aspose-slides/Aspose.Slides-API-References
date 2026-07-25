---
title: Trace
second_title: Aspose.Slides for C++ API リファレンス
description: デバッガートレース（存在する場合）にアクセスするインターフェイスを提供します。Debug モードでのみ動作します。インスタンスサービスを持たない static 型です。いかなる方法でもこの型のインスタンスを作成してはいけません。
type: docs
weight: 131
url: /ja/system.diagnostics/trace/
---
## Trace struct


デバッガのトレースへのインターフェイスを提供します（存在する場合）。[Debug](../debug/) モードでのみ動作します。これはインスタンスサービスを持たない static 型です。いかなる方法でもこの型のインスタンスを作成してはいけません。

```cpp
class Trace
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static void [Flush](./flush/)() | 出力バッファをフラッシュし、バッファされたデータをリスナーへ書き込みます。 |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | デバッガのトレースに行を書き込みます。 |
## 参照

* 名前空間 [System::Diagnostics](../)
* ライブラリ [Aspose.Slides](../../)