---
title: HyperlinkActionType
second_title: Aspose.Slides for C++ API リファレンス
description: ハイパーリンクアクションのタイプを表します。
type: docs
weight: 5916
url: /ja/aspose.slides/hyperlinkactiontype/
---
## HyperlinkActionType 列挙型

ハイパーリンクアクションの種類を表します。

```cpp
enum class HyperlinkActionType
```

### 値

| Name | Value | Description |
| --- | --- | --- |
| Unknown | -1 | 認識できないアクションタイプです。 |
| NoAction | 0 | アクションなし。 |
| Hyperlink | 1 | 通常のハイパーリンクです。 |
| JumpFirstSlide | 2 | プレゼンテーションの最初のスライドへジャンプします。 |
| JumpPreviousSlide | 3 | 前のスライドへジャンプします。 |
| JumpNextSlide | 4 | 次のスライドへジャンプします。 |
| JumpLastSlide | 5 | プレゼンテーションの最後のスライドへジャンプします。 |
| JumpEndShow | 6 | スライドショーの終了へジャンプします。 |
| JumpLastViewedSlide | 7 | 最後に表示されたスライドへジャンプします。 |
| JumpSpecificSlide | 8 | [IHyperlink::get_TargetSlide](../ihyperlink/get_targetslide/) の値で指定された特定のスライドへジャンプします。 |
| StartCustomSlideShow | 9 | カスタムスライドショーを開始します。 |
| OpenFile | 10 | 参照されたファイルを開きます。 |
| OpenPresentation | 11 | 参照されたプレゼンテーションを開きます。 |
| StartStopMedia | 12 | メディアファイルの再生を開始/停止します。 |
| StartMacro | 13 | マクロスクリプトの実行を開始します。 |
| StartProgram | 14 | プログラムを開始します。 |

## 参照

* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)