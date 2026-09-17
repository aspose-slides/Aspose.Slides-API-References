---
title: InterruptionToken class
second_title: Aspose.Slides for Python via .NET APIリファレンス
description: 
type: docs
url: /ja/aspose.slides/interruptiontoken/
---
## InterruptionToken クラス

このクラスは、長時間実行タスクに対して割り込みが要求されたかどうかを示すトークンを表します。

InterruptionToken 型は次のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`none`](/slides/python-net/ja/aspose.slides/interruptiontoken/none/) | 空の割り込みトークンを表します。<br/>            長時間実行する操作は [`InterruptionTokenSource.interrupt`](/slides/python-net/ja/aspose.slides/interruptiontokensource/interrupt) を介しては決して割り込まれません。<br/>            このトークンを使用する場合。 |
| [`is_interruption_requested`](/slides/python-net/ja/aspose.slides/interruptiontoken/is_interruption_requested/) | 割り込みが要求された場合、**bool**.true を返します。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`throw_if_interruption_requested(self)`](/slides/python-net/ja/aspose.slides/interruptiontoken/throw_if_interruption_requested/#) | OperationCanceledException をスローします。<br/>            割り込みが要求された場合。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)